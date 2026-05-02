---
title: "Protective Put Strategy | Dependability Holdings"
description: "Learn how protective puts work as portfolio insurance — the floor price, LEAPS vs short-dated puts, and when this strategy makes the most sense."
date: 2026-04-30
type: page
layout: single
url: "/protective-put-strategy/"
draft: false
---


<header class="hero">
<div>Options Strategy</div>
<h1>The Protective Put Strategy: <em>Insurance</em> for Your Stock Positions</h1>
<p >How buying puts gives your portfolio a floor — and why it's the closest thing to insurance the market offers.</p>
</header>

<section class="section">
<div class="content-block">
<h2>What Is a Protective Put?</h2>
<p>A protective put is one of the simplest and most intuitive options strategies: you buy a put option on a stock (or index) you already own. That's it. The put gives you the right to sell your shares at the strike price before expiration. You're purchasing downside insurance — paying a premium today to protect against a catastrophic loss tomorrow.</p>
<!-- AdSense Vertical -->
<!-- AdSense -->
<p>Because you're buying the put as a hedge against a stock you already hold, this strategy is sometimes called a "married put" — the put and the stock are bought and held together. The put cannot be separated from the underlying without closing the position.</p>
</div>
<div class="content-block">
<h2>How It Works — The Floor Price</h2>
<p>The most important concept in a protective put is the <strong>floor price</strong> — the lowest price at which you can exit your position regardless of how far the stock falls. Here's the formula:</p>
<p>
<strong>Floor Price = Strike Price − Premium Paid</strong>
</p>
<p>Your maximum loss on the position is capped at this floor price. The put itself can increase in value as the stock falls, effectively offsetting losses dollar-for-dollar up to the strike. Below the floor, you're protected — the put covers additional losses.</p>
<p>Meanwhile, your upside remains fully intact. If the stock rallies, you participate fully. The put may expire worthless, but you keep the stock's gains. The only cost of the insurance is the premium you paid.</p>
</div>
<div class="content-block">
<h2>Long-Dated Puts vs. Short-Dated Puts</h2>
<p>One of the most consequential decisions in protective put selection is the time horizon:</p>
</div>
<table >
<thead>
<tr>
<th>Feature</th>
<th>Short-Dated (30–60 DTE)</th>
<th>LEAPS (1–2+ Years)</th>
</tr>
</thead>
<tbody>
<tr>
<td>Cost</td>
<td>Lower premium, frequent rollovers</td>
<td>Higher premium, single purchase</td>
</tr>
<tr>
<td>Time Decay</td>
<td>Rapid — must roll frequently</td>
<td>Much slower — decays proportionally</td>
</tr>
<tr>
<td>Administrative Burden</td>
<td>High — requires ongoing management</td>
<td>Low — buy and hold the put</td>
</tr>
<tr>
<td>Best For</td>
<td>Event-driven hedges (earnings, Fed)</td>
<td>Long-term position protection</td>
</tr>
<tr>
<td>Continuity Risk</td>
<td>Gap risk between expiry and roll</td>
<td>Minimal — continuous protection</td>
</tr>
</tbody>
</table>
<div class="content-block">
<p>LEAPS (Long-Term Equity Anticipation Securities) are preferred by investors who want persistent, low-maintenance protection on large long-term holdings. The premium is higher upfront, but you avoid the compounding cost of rolling short-dated puts every 30–60 days. Rolling not only incurs transaction costs — it means buying a new put at the then-current implied volatility, which may be significantly higher after a crash has already occurred.</p>
</div>
<div class="content-block">
<h2>Protective Put vs. Stop-Loss Order</h2>
<p>A common question: why not just use a stop-loss order instead? The key difference is reliability during market dislocations:</p>
</div>
<table >
<thead>
<tr>
<th>Feature</th>
<th>Stop-Loss Order</th>
<th>Protective Put</th>
</tr>
</thead>
<tbody>
<tr>
<td>Execution guarantee</td>
<td>None — order may not fill in fast markets</td>
<td>100% — you own the right to sell at the strike</td>
</tr>
<tr>
<td>Gap risk</td>
<td>High — stock can gap through your stop</td>
<td>None — put covers entire downside beyond strike</td>
</tr>
<tr>
<td>Downside participation</td>
<td>You sell at whatever price the market offers</td>
<td>You sell at the strike price you chose</td>
</tr>
<tr>
<td>Cost</td>
<td>Free (but potentially free in a bad way)</td>
<td>Premium paid upfront</td>
</tr>
<tr>
<td>Works in after-hours</td>
<td>No — only during regular session</td>
<td>Yes — put functions through expiration</td>
</tr>
</tbody>
</table>
<div class="content-block">
<p>The gap risk of stop-loss orders is not theoretical. During the March 2020 COVID crash, the S&amp;P 500 gapped limit-down multiple days in a row. Investors with stop-losses on tech stocks found themselves selling at the worst possible prices — or not being filled at all. A protective put on SPY or QQQ at a reasonable strike would have been exercised at the strike price, regardless of where the market actually opened.</p>
</div>
<div>
<h4>📊 Real Trade Example</h4>
<p><strong>Setup:</strong> You buy 100 shares of AAPL at $170 per share — a $17,000 position. You're concerned about near-term risk given an upcoming earnings report and a large market index position. You want protection against a significant drop.</p>
<p><strong>Trade:</strong> Buy one AAPL $165 put expiring in 60 days for $3.00 per share ($300 total premium).</p>
<p><strong>Floor price:</strong> $165 strike − $3.00 premium = <strong>$162 per share</strong></p>
<p><strong>Maximum loss:</strong> $170 − $162 = $8 per share, or $800 total — regardless of how far AAPL falls</p>
<p><strong>Scenario 1 — AAPL falls to $150:</strong> Your put is deep in-the-money. Its intrinsic value = $165 − $150 = $15 per share. Combined with your stock loss ($170 − $150 = $20), net loss is capped at $8 per share ($800). Without the put, you'd have lost $2,000. The put saved you $1,200.</p>
<p><strong>Scenario 2 — AAPL rallies to $190:</strong> Your put expires worthless. You lost the $300 premium. Your stock gained $20/share = $2,000. Net gain: $1,700. The put cost you $300 but didn't prevent the gain.</p>
<p><strong>Scenario 3 — AAPL gaps down $30 on earnings miss:</strong> Opens at $140. Your stop-loss would have triggered around $140 (if at all). Your put is exercised at $165, capping your loss at the floor price. Actual loss: $170 − $165 = $5 stock loss + $3 premium = $8/share, vs. a potential $30/share loss with no protection.</p>
<div>
<div><span>Stock Entry</span><strong>$170/share</strong></div>
<div><span>Put Strike</span><strong>$165 (5% OTM)</strong></div>
<div><span>Premium</span><strong>$3.00/share ($300)</strong></div>
<div><span>Floor Price</span><strong>$162/share</strong></div>
<div><span>Max Loss</span><strong>$800 total (~$8/share)</strong></div>
</div>
</div>
<div class="content-block">
<h2>Cost Considerations</h2>
<p>Protective puts, like all insurance, have a carrying cost. The premium is determined by several factors:</p>
<ul>
<li><strong>Distance from strike</strong> — Deeper ITM (lower strike) puts cost more but provide more protection</li>
<li><strong>Time to expiration</strong> — Longer-dated puts cost more due to more time value</li>
<li><strong>Implied volatility</strong> — Higher <a href="/what-is-vix/">VIX</a> environment means more expensive premiums across the board</li>
<li><strong>Dividends</strong> — Stocks with high dividends tend to have more expensive puts due to early exercise risk on call side</li>
</ul>
<p>As a rough rule, a 5% OTM put with 60 days to expiration on a typical large-cap stock costs roughly 1–2% of the stock price in premium. For a $17,000 AAPL position, expect to pay $170–$340 per put cycle. LEAPS can cost 3–6% of the stock price but cover much longer periods.</p>
</div>
<div class="content-block">
<h2>When Protective Puts Make Sense</h2>
<ul>
<li><strong>Large unrealized gains</strong> — If a position has tripled and you'd face a massive tax bill selling now, a put insulates you without triggering a taxable event</li>
<li><strong>Upcoming catalysts</strong> — Earnings, FDA decisions, patent expirations, major legal rulings — events with binary outcomes are ideal put-buying opportunities</li>
<li><strong>Late-stage accumulation</strong> — If you're buying a position near a major financial goal (retirement, college, purchase), hedging the final accumulation tranche protects what you've already built</li>
<li><strong>Concentrated positions</strong> — Single-stock risk is uncompensated risk. A protective put on a large single-stock position is one of the most rational uses of options in personal finance</li>
<li><strong>Volatility is low</strong> — When <a href="/what-is-vix/">VIX</a> is below 15, put premiums are relatively affordable — good time to buy protection</li>
</ul>
</div>
<div>
<h3>📌 Key Takeaway</h3>
<p>Protective puts work exactly like insurance: you pay a known, bounded premium for protection against an unknown, potentially catastrophic loss. Your floor price is the strike minus the premium. Unlike stop-loss orders, protective puts cannot gap through — you have a guaranteed right to sell at the strike regardless of what happens in the market. LEAPS are ideal for long-term holdings; short-dated puts are better for event-driven hedges. The cost of puts varies with volatility, time, and strike distance, but on a $100,000 portfolio, a reasonable protective put hedge typically costs $500–$2,000 per year in most environments. For positions with large unrealized gains or near major financial milestones, that's often money very well spent.</p>
</div>
<div>
<a href="/portfolio-hedging-with-options/">Portfolio Hedging With Options →</a>
<a href="/covered-calls-explained/">Covered Calls Explained →</a>
<a href="/what-is-vix/">What Is VIX? →</a>
<a href="/risk-management/">Risk Management →</a>
</div>
</section>

<section >
<div>
<strong>Important Disclaimer — Please Read</strong><br />
Dependability Holdings LLC is an investment holding company. This webpage is for informational and educational purposes only and does not constitute financial, investment, or legal advice. Dependability Holdings LLC is not a registered investment advisor. The information provided herein should not be construed as personalized investment advice, a recommendation to buy, sell, or hold any investment, or an offer or solicitation to buy or sell securities. All investments involve risk, including the potential loss of principal. Please consult with a qualified financial advisor before making any investment decisions.
</div>
</section>
<!-- AdSense Horizontal -->
<!-- AdSense -->
