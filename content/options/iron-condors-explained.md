---
title: "Iron Condors Explained | Dependability Holdings"
description: ""
date: 2026-04-30
type: page
layout: single
url: "/iron-condors-explained/"
draft: false
---


<header class="hero">
<div>Educational Resources</div>
<h1>Iron Condors <em>Explained</em></h1>
<p >A defined-risk strategy for earning income in sideways markets.</p>
</header>

<section class="section">
<div class="content-block">
<h2>What Is an Iron Condor?</h2>
<p>An iron condor is a multi-leg options strategy built from two put spreads and two call spreads. You sell an OTM call spread above the current stock price and an OTM put spread below it, collecting premium on both sides. The result is a position that profits when the stock stays within a defined range — the "condor wings" — and loses when it breaks out in either direction.</p>
<!-- Real Example Section -->
<div>
<h3>📌 Real Example: SPY Iron Condor</h3>
<p>Let's walk through a concrete iron condor trade:</p>
<ul>
<li><strong>Setup:</strong> SPY trading at <strong>$572</strong>. We sell an iron condor 30 days to expiration.</li>
<li><strong>Sell $577/$582 call spread</strong> (5-wide) — collect <strong>$0.45 credit</strong></li>
<li><strong>Sell $567/$562 put spread</strong> (5-wide) — collect <strong>$0.45 credit</strong></li>
<li><strong>Total credit collected:</strong> $0.90 per share ($90 per contract)</li>
<li><strong>Max risk per share:</strong> $5.00 - $0.90 = <strong>$4.10</strong> ($410 per contract)</li>
<li><strong>Probability of profit:</strong> ~65%</li>
<li><strong>Days to expiration:</strong> 30</li>
</ul>
<p><strong>At expiration:</strong></p>
<ul>
<li>🔵 <strong>SPY at $575</strong> — both spreads expire worthless → keep the full $0.90 credit = <strong>$90 profit per contract</strong></li>
<li>🔴 <strong>SPY at $585</strong> — call spread max loss ($4.10), put spread expires worthless → lose <strong>$410 per contract</strong></li>
<li>🔴 <strong>SPY at $560</strong> — put spread max loss ($4.10), call spread expires worthless → lose <strong>$410 per contract</strong></li>
</ul>
<p>In VIX 15–20 environments, a typical iron condor risks $1.00 to earn $0.30–$0.50 with 60–70% probability of profit.</p>
</div>
<!-- AdSense Vertical -->
<!-- AdSense -->
<p>Unlike naked options selling, iron condors have strictly defined risk on both sides. The most you can lose is the width of the wider spread minus the net premium received. This makes them popular among traders who want to collect time decay in range-bound environments without unlimited downside exposure.</p>
</div>
<div>
<h3>Iron Condor Risk Profile (Simplified)</h3>
<div>
<span >Max Loss</span>
<div></div>
</div>
<div>
<span >Profit Zone</span>
<div></div>
</div>
<div>
<span >Max Loss</span>
<div></div>
</div>
<div>
<span>Put Wing (Downside)</span>
<span>Profit Zone</span>
<span>Call Wing (Upside)</span>
</div>
</div>
</section>

<section class="section">
<h2 >When to Use Iron Condors</h2>
<p >Not every market suits every strategy. Iron condors have specific conditions where they thrive.</p>
<div class="resource-cards">
<div class="resource-card">
<div class="resource-category">Best Conditions</div>
<h3>Low Volatility Environments</h3>
<p>Iron condors are most profitable when implied volatility (IV) is high enough to generate meaningful premium but the stock is not making large directional moves. High IV means expensive options — meaning you collect more premium when selling the spreads. A flat or slowly drifting stock means neither wing gets tested. In VIX 15–20 environments, a typical iron condor risks $1.00 to earn $0.30–$0.50 with 60–70% probability of profit.</p>
</div>
<div class="resource-card">
<div class="resource-category">Best Conditions</div>
<h3>Post-Earnings Moves Complete</h3>
<p>IV crush — the rapid decline in implied volatility after a major event like earnings — is actually an opportunity for iron condor sellers. Selling the condor just after an earnings announcement when IV is still elevated, before it collapses over the following days and weeks, can be highly profitable as time decay accelerates.</p>
</div>
<div class="resource-card">
<div class="resource-category">Best Conditions</div>
<h3>Known Technical Ranges</h3>
<p>When a stock has clear support and resistance levels — where it has repeatedly bounced off a floor and failed to break a ceiling — iron condors are a natural fit. You set your wings just outside these known ranges, giving the stock room to move within your profit zone.</p>
</div>
</div>
</section>

<section class="section">
<h2 >Managing Winners vs. Losers</h2>
<p >The discipline of when to take profit and when to cut losses defines iron condor success.</p>
<div class="content-block">
<h2>Taking Profits Early</h2>
<p>Most traders target closing an iron condor for a profit when they have captured 50–75% of the maximum potential profit. Waiting until expiration to collect the last few dollars of premium exposes you to unexpected moves in the final days. The standard practice: if the position has reached 50% of its max profit, close it and move on.</p>
<h2>Managing Losing Positions</h2>
<p>When the stock approaches one of your short strikes — the edge of your profit zone — you have several choices:</p>
<ul>
<li><strong>Roll the threatened side:</strong> Close the threatened spread for a loss and sell a new spread further out, collecting new premium. This extends your time horizon but may still result in a net loss if done repeatedly in a trending market.</li>
<li><strong>Widen the spread:</strong> Rather than closing, you can buy back the threatened option and sell a further-out one, increasing your potential loss but reducing the immediate loss. This is generally not recommended — it increases risk, not reduces it.</li>
<li><strong>Take the loss:</strong> Sometimes the correct decision is to close the position, accept the loss, and move on. Fighting a trending market with a short premium strategy rarely ends well.</li>
</ul>
</div>
<div>
<p><strong>The key rule:</strong> Never adjust a losing iron condor in a way that increases your maximum potential loss. Every adjustment should either reduce risk or buy time without expanding the loss window. If a position is working against you in a trending market, sometimes the best trade is no trade — close it and wait for better conditions.</p>
</div>
</section>

<section class="section">
<h2 >Adjusting Positions</h2>
<p >Proactive adjustments can rescue a struggling condor — or make it worse.</p>
<div class="content-block">
<p>Adjustment is not the same as hope. A real adjustment changes the risk profile of the position in a deliberate way. Here are the most common valid adjustments:</p>
<ul>
<li><strong>Roll the entire condor:</strong> If the stock has drifted to the edge of your profit zone and you believe it will stay in a new range, you can close the entire position and open a new condor centered on the new price.</li>
<li><strong>Turn it into an iron butterfly:</strong> If the stock has drifted to one wing and you believe it will bounce back, you can close the threatened wing and widen the other side to maintain similar risk/reward.</li>
<li><strong>Add a position:</strong> Some traders add a second condor on the same stock at a different strike or expiration to average their entry — this increases both risk and opportunity and should be done with a clear plan.</li>
</ul>
<p>The most important question to ask before adjusting: does this adjustment still fit my thesis? If you originally sold an iron condor because you expected a range-bound market, and the market is now clearly trending, adjusting to stay in the trade is fighting the market — not trading with it.</p>
</div>
</section>

<section class="section">
<h2 >Risk Graph Walkthrough</h2>
<p >Understanding the visual language of iron condor P&L.</p>
<div class="content-block">
<p>An iron condor risk graph is typically symmetrical, with two "wings" representing your maximum loss zones and a broad plateau in the middle representing your profit zone. Here is how to read it:</p>
<ul>
<li><strong>The peak of the plateau</strong> is your maximum profit — achieved when the stock closes anywhere between your two short strikes at expiration.</li>
<li><strong>The edges of the plateau</strong> are your short strikes — the levels where if the stock closes beyond them, your profit begins to erode.</li>
<li><strong>The downward slopes</strong> represent your loss zones. The further the stock moves beyond a short strike, the more the position loses until it hits the long strike — your maximum loss.</li>
<li><strong>The width between short and long strikes</strong> on each side determines your maximum loss on that wing. A 5-wide spread (e.g., $95/$100 call spread) with a $1.00 credit collected means a $4.00 maximum loss per share on that side.</li>
</ul>
</div>
<div>
<p><strong>Practical tip:</strong> Always calculate your risk-to-reward ratio before entering an iron condor. If you collect $1.00 in net credit and your max loss is $4.00, you need a greater than 80% win rate just to break even over many trades. In practice, look for condors where the probability of profit (POP) from your broker is at least 60–65% based on the current price structure.</p>
</div>
</section>

<section class="section">
<div class="info-box">
<h3>Related Strategies</h3>
<div>
<a href="/covered-calls-guide/">Covered Calls</a>
<a href="/cash-secured-puts/">Cash-Secured Puts</a>
<a href="/trading-psychology/">Trading Psychology</a>
<a href="/trade-log-template/">Trade Log Template</a>
<a href="/educational-resources/">All Resources</a>
</div>
</div>
</section>
<div>
<div>
<strong>Important Disclaimer — Please Read</strong><br />
Dependability Holdings LLC is an investment holding company. This webpage is for informational and educational purposes only and does not constitute financial, investment, or legal advice.
Dependability Holdings LLC is not a registered investment advisor. The information provided herein should not be construed as personalized investment advice, a recommendation to buy, sell, or hold any investment, or an offer or solicitation to buy or sell securities.
<br /><br />
All investments involve risk, including the potential loss of principal. The value of investments can fluctuate, and past performance may not be indicative of future results. Please consult with a qualified financial advisor, attorney, or tax professional before making any investment decisions.
</div>
</div>
<!-- AdSense Horizontal -->
<!-- AdSense -->
