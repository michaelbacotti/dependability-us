---
title: "Risk Management Fundamentals | Dependability Holdings"
description: ""
date: 2026-04-30
type: page
layout: single
url: "/risk-management/"
draft: false
---


<header class="hero">
<div>Educational Resources</div>
<h1>Risk <em>Management</em></h1>
<p >How we think about position sizing, loss limits, portfolio construction, and the specific risks unique to options trading.</p>
</header>

<section class="section">
<div class="content-block">
<h2>The Only Rule That Matters</h2>
<p>In options trading, there are hundreds of strategies, Greeks to monitor, and market regimes to navigate. But the one principle that separates sustainable traders from those who blow up their accounts is simple: <strong>never risk more than you can afford to lose on any single position.</strong></p>
<!-- AdSense Vertical -->
<!-- AdSense -->
<p>Everything else in this article is an elaboration on what that rule looks like in practice — how to define "risk," how to size positions accordingly, and how to construct a portfolio that survives even when your analysis is wrong.</p>
</div>
<div>
<h3>The Asymmetry of Loss</h3>
<p>A 50% loss requires a 100% gain to break even. A 75% loss requires a 300% gain. This math doesn't change, no matter how sophisticated your strategy. Protecting capital is not a conservative mind-set — it is arithmetic. The traders who survive long enough to compound returns are the ones who take losses gracefully.</p>
</div>
<div class="content-block">
<h2>Position Sizing</h2>
<p>Position sizing is the primary lever for controlling risk at the individual-trade level. It answers the question: "How much of my portfolio should go into this one trade?" Getting this wrong — either by over-concentrating or over-diversifying into noise — is the most common source of preventable losses.</p>
</div>
<div>
<div>Maximum Position Size Formula</div>
<div>Max $ at risk per trade = Total Portfolio Value × Risk Per Trade %</div>
</div>
<p>
For most options traders, a sensible ceiling is <strong>2–5% of portfolio capital</strong> at risk per trade. That means if a trade goes completely wrong — options expire worthless or the position is closed at maximum loss — no single trade destroys the portfolio. At 2% per trade, you would need 50 consecutive losing trades to lose your entire account. That scenario is unlikely even for unprofitable traders.
</p>
<div>
<h3>Defined Risk vs. Undefined Risk</h3>
<p>Long options (buying calls or puts) have a <em>defined risk</em> — the absolute most you can lose is the premium paid. Short options (selling calls or puts) carry <em>undefined risk</em>, particularly with naked calls or short puts in volatile stocks. When position sizing, short option positions require significantly smaller notional sizes because the loss potential is theoretically unlimited.</p>
</div>
<div>
<h3>Adjust Sizing by Conviction</h3>
<p>Not every trade deserves the same size. High-conviction setups — where your thesis is well-supported by data and the risk/reward is clearly favorable — can warrant a larger allocation. Low-conviction, speculative trades should be sized smaller or passed on entirely. Size is how you vote with your capital; make sure your votes reflect your confidence level.</p>
</div>
</section>

<section class="section">
<div class="content-block">
<h2>Stop Losses and Exit Plans</h2>
<p>Every trade needs an exit plan before you enter it. This means defining, in advance, the price or condition at which you will close the position — either to take a loss or lock in a gain. Without a pre-committed exit plan, emotions take over and losses become larger than intended.</p>
</div>
<div>
<div>
<h3>Stop Loss Levels</h3>
<p>For long options, stop losses are typically defined as a percentage of premium paid. Common approaches:</p>
<ul class="content-list">
<li><strong>50% loss on premium</strong> — Close if the option loses half its value, to preserve capital for better setups.</li>
<li><strong>Time-based stop</strong> — Exit if the option hasn't moved in your favor within a set number of days.</li>
<li><strong>Technical stop</strong> — Exit if the underlying breaks a key support or resistance level.</li>
</ul>
</div>
<div>
<h3>Take Profit Levels</h3>
<p>Having a plan to take profits is equally important. Greedy holding through significant gains is just as destructive as stubborn holding through losses:</p>
<ul class="content-list">
<li><strong>Target multiple</strong> — Close when the option reaches 100%, 200%, or 300% of premium paid.</li>
<li><strong>Trailing stop</strong> — As the option gains, raise a mental or literal stop so that a reversal doesn't turn a gain into a loss.</li>
<li><strong>Earnings or event exit</strong> — Pre-schedule exits around earnings announcements or Fed meetings when implied volatility spikes.</li>
</ul>
</div>
</div>
</section>

<section class="section">
<div class="content-block">
<h2>Portfolio Diversification</h2>
<p>Diversification in an options portfolio is not simply about owning many different tickers. True diversification means building a portfolio where the outcomes of different positions are not highly correlated — so that a drawdown in one position doesn't automatically drag down others.</p>
<p>Options strategies fall into distinct risk categories. A portfolio made entirely of short premium strategies, for example, may appear diversified across tickers but will tend to suffer when volatility spikes — as happened in August 2015, February 2018, March 2020, and August 2024. Knowing the correlation structure of your strategies is more important than counting how many positions you hold.</p>
</div>
<div>
<h3>Diversification Across Dimensions</h3>
<p>Consider spreading risk across multiple dimensions:</p>
<ul class="content-list">
<li><strong>Strategy type</strong> — Balance directional trades with income-generating strategies like credit spreads or covered calls.</li>
<li><strong>Underlying sector</strong> — Technology, healthcare, financials, and commodities respond differently to economic data and interest rate changes.</li>
<li><strong>Time horizon</strong> — Mix weeklies, monthlies, and longer-dated options to avoid clustering expiration risk.</li>
<li><strong>Volatility regime</strong> — Some strategies thrive in high-vol environments (long straddles), others in low-vol environments (short premium).</li>
</ul>
</div>
</section>

<section class="section">
<div class="content-block">
<h2>Options-Specific Risk Factors</h2>
<p>Options introduce risks beyond stock direction. Failing to account for these is a primary reason options portfolios experience sudden, unexpected drawdowns.</p>
</div>
<div>
<h3>Implied Volatility Crush</h3>
<p>Options premiums are heavily influenced by implied volatility (IV). After earnings announcements or other catalysts, IV typically collapses — even if the stock moves in your favor. This is called an IV crush, and it can turn a profitable directional bet into a net loss. The defense: avoid buying near-term options before high-IV events, or sell options into those same events to capture the IV premium.</p>
</div>
<div>
<h3>Early Assignment Risk</h3>
<p>Short options — especially short puts on high-dividend stocks — can be assigned early if the option goes deep in-the-money before an ex-dividend date. Traders selling short options must monitor positions closely, particularly around earnings and dividend dates. Not managing early assignment can result in buying stock at a price you didn't choose at a time you didn't expect.</p>
</div>
<div>
<h3>Correlation Concentration in Indices</h3>
<p>When trading options on index products like SPX or QQQ, remember that these underlying assets are inherently diversified across many stocks. But index positions can still correlate heavily with equity portfolios. A "diversified" options book full of SPX and QQQ spreads may offer less actual diversification than it appears — particularly in a broad market selloff.</p>
</div>
<div>
<h3>Gamma Risk Near Expiration</h3>
<p>Gamma measures how fast delta changes. As expiration approaches, options near the money develop extremely high gamma — meaning their delta can shift violently with small moves in the underlying. This makes near-expiration short options particularly dangerous. Avoid adding new short-gamma positions in the last week before expiration.</p>
</div>
</section>

<section class="section">
<div class="content-block">
<h2>Portfolio-Level Risk Controls</h2>
<p>Beyond individual position sizing, you need a framework for managing overall portfolio risk:</p>
<ul class="content-list">
<li><strong>Daily mark-to-market review</strong> — At minimum, assess your portfolio's total P&L and largest unrealized losses each day.</li>
<li><strong>Maximum drawdown limit</strong> — Define in advance the portfolio drawdown level at which you will stop trading and reassess. For most traders, 10–15% is a reasonable limit before a formal pause.</li>
<li><strong>Leverage check</strong> — The aggregate delta or notional exposure of your options book should be measured against total portfolio value. Excessive net delta creates equity-like risk without equity-like diversification.</li>
<li><strong>Liquidity review</strong> — Ensure your portfolio holds positions with sufficient open interest and bid/ask spreads to exit cleanly. Illiquid options can result in paying twice the expected spread cost when exiting.</li>
</ul>
</div>
<div>
<a href="/options-basics/">Options Basics →</a>
<a href="/glossary/">Trading Glossary →</a>
<a href="/weekly-market-recap/">Market Recap Template →</a>
<a href="/about-strategy/">Our Strategy →</a>
</div>
</section>

<section class="cta-section">
<div>
<h2>Continue Learning</h2>
<p>Explore our full set of educational resources to build a complete understanding of the markets.</p>
<a href="/educational-resources/" class="btn btn-primary">View All Resources</a>
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
