---
title: "Our Research Methodology | Dependability Holdings"
description: "How Dependability Holdings builds its market forecasts — data sources, analytical process, and trade strategy framework."
date: 2026-04-30
type: page
layout: single
url: "/methodology/"
draft: false
---


<section class="page-hero">
<div class="container">
<h1>How We Make Our <span class="text-accent">Market Forecasts</span></h1>
<p class="page-hero-sub">A transparent look at the data, process, and reasoning behind our S&P 500 outlooks and options trade ideas.</p>
</div>
</section>
<section class="content-section">
<div class="container">
<div class="content-block">
<h2>Introduction</h2>
<p>Our forecasts are built from publicly available market data and established financial theory. Every update follows a structured process — not gut feelings, not algorithmic signals, and not proprietary black boxes. Here's exactly what goes into each market outlook we publish.</p>
<!-- AdSense Vertical -->
<!-- AdSense -->
</div>
<div class="content-block">
<h2>Data Sources</h2>
<p>We rely exclusively on publicly available market data. No proprietary feeds, no insider information, no premium subscriptions required to verify our work.</p>
<ul>
<li><strong>Yahoo Finance</strong> — Daily closing prices and volume for SPY, QQQ, VIX, and DIA</li>
<li><strong>CBOE VIX</strong> — The CBOE Volatility Index, our primary measure of market uncertainty</li>
<li><strong>Public.com API</strong> — Options chain data including open interest, volume, and implied volatility by strike</li>
<li><strong>Standard Options Pricing Theory</strong> — The Black-Scholes framework informs our understanding of option valuation, though we don't calculate Black-Scholes directly in our analysis</li>
<li><strong>FRED (Federal Reserve Economic Data)</strong> — For macroeconomic context including GDP, employment, and interest rate data</li>
</ul>
<p>All data is fetched and analyzed as of the most recent trading day's close. We do not trade on pre-market or intraday data for our daily outlooks.</p>
</div>
<div class="content-block">
<h2>Our Six-Step Process</h2>
<p>Each market update follows the same repeatable framework:</p>
</div>
<div class="diff-grid">
<div class="diff-item">
<h3>1. Market Data Collection</h3>
<p>We record the closing prices of SPY (S&amp;P 500 ETF), QQQ (Nasdaq 100 ETF), VIX (CBOE Volatility Index), and DIA (Dow Jones ETF) each trading day. These four instruments give us a clear picture of broad market direction and volatility regime.</p>
</div>
<div class="diff-item">
<h3>2. Options Chain Analysis</h3>
<p>We examine the options chain for nearby expirations — typically the nearest monthly or weekly expiration — looking at open interest concentrations, put/call ratios, and implied volatility levels across strikes. This tells us where the market sees risk and where the "insurance" demand is highest.</p>
</div>
<div class="diff-item">
<h3>3. VIX Regime Classification</h3>
<p>We classify the current volatility environment into one of four regimes:</p>
<ul>
<li><strong>Calm</strong> — VIX below 15. Low fear, favorable for premium-selling strategies.</li>
<li><strong>Elevated</strong> — VIX 15–20. Normal uncertainty, balanced approach.</li>
<li><strong>High</strong> — VIX 20–30. Elevated fear, wider spreads, higher premiums available.</li>
<li><strong>Panic</strong> — VIX above 30. Crisis conditions, defensive posture only.</li>
</ul>
<p>The VIX regime directly determines which option strategies we consider and how we size positions.</p>
</div>
<div class="diff-item">
<h3>4. Directional Bias Assessment</h3>
<p>We evaluate directional signals from both technical and fundamental sources:</p>
<ul>
<li><strong>Technical:</strong> Price vs. key moving averages (50-day, 200-day), trend direction, support and resistance zones</li>
<li><strong>Fundamental:</strong> Macro environment (GDP, employment, Fed policy), earnings trajectory, valuation levels</li>
</ul>
<p>We form a directional bias — bullish, bearish, or neutral — and state our confidence level clearly. We do not pretend to precision we don't have.</p>
</div>
<div class="diff-item">
<h3>5. Spread Strategy Selection</h3>
<p>Once we have a VIX regime and directional bias, we select a spread structure that matches the conditions. The table below shows our default framework:</p>
</div>
<div class="diff-item">
<h3>6. Trade Idea Formatting</h3>
<p>Every trade idea we publish is formatted with: the underlying instrument, the specific strikes and expiration, the net cost or credit, the maximum risk, the maximum reward, and the probability of profit based on the VIX-derived probability distribution. This gives you everything you need to evaluate the idea on your own.</p>
</div>
</div>
<div class="content-block">
<h2>Strategy Selection Framework</h2>
<p>Our strategy selection is governed by two inputs: VIX regime and directional bias.</p>
<div>
<table>
<thead>
<tr>
<th>VIX Regime</th>
<th>VIX Level</th>
<th>Bullish Bias</th>
<th>Neutral Bias</th>
<th>Bearish Bias</th>
</tr>
</thead>
<tbody>
<tr>
<td><strong>Calm</strong></td>
<td>&lt; 15</td>
<td>Bull Put Spread</td>
<td>Iron Condor</td>
<td>Bear Call Spread</td>
</tr>
<tr>
<td><strong>Elevated</strong></td>
<td>15–20</td>
<td>Bull Call Spread</td>
<td>Iron Condor</td>
<td>Bear Put Spread</td>
</tr>
<tr>
<td><strong>High</strong></td>
<td>20–30</td>
<td>Bull Put Spread (wider)</td>
<td>Iron Condor (wider)</td>
<td>Bear Call Spread (wider)</td>
</tr>
<tr>
<td><strong>Panic</strong></td>
<td>&gt; 30</td>
<td>Defensive — reduce size</td>
<td>Defensive — reduce size</td>
<td>Defensive — reduce size</td>
</tr>
</tbody>
</table>
</div>
</div>
<div class="content-block">
<h2>Defined-Risk Spreads Only</h2>
<p>One principle we hold firmly: <strong>we only recommend defined-risk spreads.</strong> Every strategy we publish has a maximum loss that is known before you place the trade. We do not recommend naked short volatility positions, uncovered short options, or any strategy where your downside is theoretically unlimited.</p>
<p>The strategies we use:</p>
<ul>
<li><strong>Bull Put Spread</strong> — Sell a higher strike put, buy a lower strike put for protection. Max loss = spread width minus net credit.</li>
<li><strong>Bull Call Spread</strong> — Buy a lower strike call, sell a higher strike call. Max loss = net cost paid.</li>
<li><strong>Bear Call Spread</strong> — Sell a lower strike call, buy a higher strike call for protection. Max loss = spread width minus net credit.</li>
<li><strong>Bear Put Spread</strong> — Buy a higher strike put, sell a lower strike put. Max loss = net cost paid.</li>
<li><strong>Iron Condor</strong> — A bull put spread combined with a bear call spread. Four legs, defined max loss on each side.</li>
<li><strong>Calendar Spread</strong> — Sell a short-dated option, buy a longer-dated option at the same strike. Profits from time decay differential.</li>
</ul>
</div>
<div class="content-block">
<h2>What We Don't Do</h2>
<p>For transparency, here is what we explicitly avoid:</p>
<ul>
<li><strong>No naked short calls or puts</strong> — Unlimited loss potential; we don't recommend these to readers</li>
<li><strong>No short volatility ETFs</strong> — VXX, SVIX, and similar products lose value structurally in trending markets</li>
<li><strong>No leveraged ETFs for directional bets</strong> — TQQQ, SPXL, and 3x products are tools for short-term traders, not long-term investors</li>
<li><strong>No earnings plays</strong> — Binary events introduce volatility crush risk we don't find suitable for educational recommendations</li>
<li><strong>No illiquid options</strong> — We only analyze options with sufficient open interest and volume</li>
</ul>
</div>
<div class="content-block">
<h2>Probability and Risk Management</h2>
<p>No trade is a sure thing. We estimate probability of profit using a simplified model based on VIX-derived implied volatility and the distance of strikes from current price. These are estimates, not guarantees — but they give you a disciplined framework for position sizing.</p>
<p>We generally aim for trades with a probability of profit in the 55–75% range. Lower probability trades are reserved for situations where the reward-to-risk ratio is exceptional.</p>
</div>
<div class="content-block">
<h2>Update Schedule</h2>
<p>Our market outlook is updated at the end of each trading day, using closing prices. We do not update during the trading day — closing prices are the foundation of our analysis. If market conditions change significantly between updates (e.g., a major geopolitical event or Fed announcement), we may publish an interim note.</p>
<p>Educational content is reviewed and updated on a quarterly basis, or sooner if we identify a material inaccuracy.</p>
</div>
<div class="content-block">
<h2>Last Updated</h2>
<p><em>April 2026</em></p>
<p>This methodology page is reviewed quarterly. Last substantive review: April 2026.</p>
</div>
<div class="content-block">
<p><a href="/dependability-forecast/" class="btn btn-primary">View Today's Market Forecast →</a>
<a href="/editorial-policy/" class="btn btn-secondary">Editorial Policy →</a></p>
</div>
</div>
</section>
