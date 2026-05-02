---
title: "Options Greeks Explained: Delta, Gamma, Theta, Vega | Dependability Holdings"
description: "Delta, gamma, theta, and vega explained in plain English — with what they mean for your positions."
date: 2026-04-30
type: page
layout: single
url: "/options-greeks-explained/"
draft: false
---


<header class="hero">
<div>Trading Education</div>
<h1>Options <em>Greeks</em></h1>
<p >Delta, gamma, theta, and vega — the four numbers that tell you how your options position will behave as the market moves.</p>
</header>

<section class="section">
<article >
<p>Options prices don't move in a straight line with the underlying stock. They respond to time, volatility, interest rates, and the relationship between the current price and the strike. To understand how a position will behave — before you enter and after you're in it — you need to understand the <strong>Greeks</strong>.</p>
<!-- AdSense Vertical -->
<!-- AdSense -->
<p>The four primary Greeks are delta, gamma, theta, and vega. They are not abstract academic concepts — they are practical risk measurements that tell you exactly how much money you're making or losing, and why, as conditions change. Every options trader, regardless of strategy, should have a working knowledge of all four.</p>
<h2>Delta — Direction Sensitivity</h2>
<div>
<span >The most intuitive Greek</span>
<h3>How much does your position move with the underlying?</h3>
<p>Delta measures the rate of change in an option's price relative to a $1 move in the underlying asset. For a call option, delta ranges from 0 to 1.00. For a put option, delta ranges from 0 to -1.00.</p>
<p><strong>A delta of 0.50 means:</strong> For every $1 move in SPY, your option position gains or loses approximately $0.50. A portfolio with a net delta of 200 would gain roughly $200 for every $1 move in SPY.</p>
<p>Delta also approximates the <strong>probability</strong> that an option will expire in-the-money. A 30-delta option has roughly a 30% chance of finishing ITM. A 70-delta option has a 70% chance. This is why delta is often used as a shorthand for probability of profit in defined-risk strategies.</p>
<dl>
<dt>ATM options</dt><dd>Delta near 0.50 (calls) or -0.50 (puts)</dd>
<dt>Deep ITM options</dt><dd>Delta near 1.00 or -1.00 (behave like stock)</dd>
<dt>Deep OTM options</dt><dd>Delta near 0 — little sensitivity to underlying</dd>
<dt>Delta as position size</dt><dd>1 put with delta -0.40 = equivalent to being short 40 shares</dd>
</dl>
</div>
<h2>Gamma — Rate of Delta Change</h2>
<div>
<span >The Greek that accelerates</span>
<h3>How fast does your delta change as the stock moves?</h3>
<p>Gamma measures the rate of change of delta itself — not the change in option price, but the change in the <em>change</em>. If delta is your speed, gamma is your acceleration. This distinction matters most as you approach expiration.</p>
<p><strong>Why it matters:</strong> When you buy an option and the stock moves in your favor, delta increases — your option "acts more like stock" as it goes deeper ITM. This is gamma at work. Conversely, if the stock moves against you, delta decreases — your option "acts less like stock." Gamma determines whether your P&amp;L accelerates or decelerates as the underlying moves.</p>
<p>Gamma is highest for <strong>ATM options</strong> near expiration. This is why option buyers near expiration can experience rapid swings — even small moves in the underlying cause outsized moves in the option price because gamma is elevated.</p>
<dl>
<dt>ATM, near expiration</dt><dd>Highest gamma — fastest delta swings</dd>
<dt>Deep ITM or OTM</dt><dd>Low gamma — delta is stable</dd>
<dt>Long options (bought)</dt><dd>Positive gamma — accelerating P&amp;L in either direction near expiry</dd>
<dt>Short options (sold)</dt><dd>Negative gamma — decelerating P&amp;L, losing more when wrong</dd>
</dl>
</div>
<h2>Theta — Time Decay</h2>
<div>
<span >The investor's enemy, the option seller's friend</span>
<h3>How much value does your position lose each day?</h3>
<p>Theta measures the rate at which an option loses time value every day, all else being equal. It is almost always negative for long option positions — meaning you are always losing value simply by waiting, regardless of which way the stock moves.</p>
<p><strong>Why it's the investor's enemy:</strong> An option's value is partly made up of time value — the "something for something" premium above intrinsic value. That premium erodes every day, like sand leaking through an hourglass. Even if SPY goes exactly where you expected, you can still lose money on a long option position if theta decay outruns the move.</p>
<p><strong>Why it's the option seller's friend:</strong> If you sold the option, you collected that premium upfront. As theta works against the buyer, it works <em>for</em> you — each day that passes without a big move in the underlying is a day your short option moved closer to expiring worthless, and you kept the premium.</p>
<dl>
<dt>At expiration</dt><dd>Theta is maximal — time value collapses to zero</dd>
<dt>ATM options</dt><dd>Highest theta — most time value to lose</dd>
<dt>Far OTM options</dt><dd>Low theta — little time value to begin with</dd>
<dt>60 DTE</dt><dd>Theta is relatively low — slow decay</dd>
<dt>14 DTE</dt><dd>Theta is high — rapid decay acceleration</dd>
</dl>
</div>
<h2>Vega — Volatility Sensitivity</h2>
<div>
<span >The Greek that catches beginners off guard</span>
<h3>How much does your position gain or lose when implied volatility changes?</h3>
<p>Vega measures the sensitivity of an option's price to changes in implied volatility (IV). Specifically, a vega of 0.15 means the option gains or loses approximately $0.15 for every 1% change in implied volatility.</p>
<p><strong>Why it surprises beginners:</strong> A trader can be correct about direction and still lose money because implied volatility changed. If you buy a call option ahead of an earnings report and the stock moves up but IV collapses after the announcement, the option can lose value even though the stock went your way. That's vega.</p>
<p>Vega is highest for <strong>long-dated options</strong> and ATM contracts. A 6-month option has much more vega than a 2-week option — because the longer timeframe means more can happen, and the market prices in more uncertainty over longer periods.</p>
<dl>
<dt>High IV environment</dt><dd>Vega works against long option buyers — IV has nowhere to go but down</dd>
<dt>Low IV environment</dt><dd>Vega helps long option buyers — IV has room to expand</dd>
<dt>Before earnings</dt><dd>High IV = high option prices = large vega exposure</dd>
<dt>Post-earnings collapse</dt><dd>IV crush — vega becomes a sudden drag on long positions</dd>
</dl>
</div>
<h2>Practical Example: 30-DTE SPY Bull Put Spread</h2>
<div>
<h3>SPY Bull Put Spread — 30 Days to Expiration</h3>
<div>
<span>SPY price:</span><span>$515</span>
<span>Short put:</span><span>$505 strike (delta ~-0.25)</span>
<span>Long put:</span><span>$500 strike (delta ~-0.15)</span>
<span>Net premium:</span><span>$2.00 credit</span>
<span>Max risk:</span><span>$3.00 per share ($300 per contract)</span>
</div>
<p><strong>Which Greeks matter at entry (30 DTE)?</strong><br />
At 30 DTE, theta is the dominant Greek for this position. The short $505 put has meaningful time value that erodes daily. Every day without a large drop in SPY adds to your theoretical profit. Vega matters moderately — if IV drops 5%, the spread loses roughly $0.35 in value, offsetting some of your theta gains.</p>
<p><strong>At 7 DTE — which Greeks dominate?</strong><br />
Gamma accelerates sharply on both legs. Delta changes rapidly with any SPY move — the spread's sensitivity to SPY price accelerates as expiration approaches. Theta is maximal, working strongly in your favor if SPY stays above $505. Vega matters less now — most of the spread's value is intrinsic, not time value.</p>
</div>
<h2>The Greeks Work Together</h2>
<p>The key insight is that the four Greeks don't operate in isolation — they interact. At trade entry, theta and vega dominate. As expiration approaches, delta and gamma take over. A trader who only watches delta while ignoring theta accumulation is only seeing half the picture.</p>
<p>The best practice is to track all four Greeks for every position you hold, but focus your attention on whichever Greek is most relevant to the current phase of the trade. Early in a position: watch theta and vega. Late in a position: watch delta and gamma. This shift in focus as time passes is what separates disciplined options traders from those who get caught off guard byExpiration.</p>
</article>
<div>
<a href="/options-basics/">Options Basics →</a>
<a href="/vix-regime-guide/">VIX Regime Guide →</a>
<a href="/position-sizing-rules/">Position Sizing →</a>
</div>
</section>

<section class="cta-section">
<div>
<h2>Continue Your Education</h2>
<p>Build your complete options trading knowledge from the ground up.</p>
<a href="/options-basics/" class="btn btn-primary">View Learning Resources</a>
</div>
</section>
<div>
<div>
<strong>Important Disclaimer — Please Read</strong><br />
Dependability Holdings LLC is an investment holding company. This webpage is for informational and educational purposes only and does not constitute financial, investment, or legal advice. Dependability Holdings LLC is not a registered investment advisor. All investments involve risk, including the potential loss of principal. Please consult with a qualified financial advisor before making any investment decisions.
</div>
</div>
<!-- AdSense Horizontal -->
<!-- AdSense -->
