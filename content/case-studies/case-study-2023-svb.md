---
title: "Case Study: 2023 SVB Crisis | Dependability Holdings"
description: "How Silicon Valley Bank&#x27;s collapse reshaped markets in March 2023 — contagion dynamics, what worked, and what failed."
date: 2026-04-30
type: page
layout: single
url: "/case-study-2023-svb/"
draft: false
---


<header class="hero">
<div>Case Study</div>
<h1>SVB Banking <em>Crisis</em></h1>
<p >The March 2023 Silicon Valley Bank collapse and what it revealed about contagion, hedging, and risk in financial systems.</p>
</header>

<section class="section">
<div>
<div>
<div class="stat-value">~7%</div>
<div class="stat-label">S&P 500 Drop in 3 Days</div>
</div>
<div>
<div class="stat-value">~30</div>
<div class="stat-label">VIX Spike Peak</div>
</div>
<div>
<div class="stat-value">-50%+</div>
<div class="stat-label">Regional Bank Stock Decline</div>
</div>
<div>
<div class="stat-value">$42B</div>
<div class="stat-label">SVB Deposit Flight (48hrs)</div>
</div>
</div>
</section>

<section class="section">
<div class="content-block">
<h2>Timeline of Events</h2>
<p>What happened with Silicon Valley Bank was not a slow-motion trainwreck — it was a rapid unraveling that surprised even sophisticated observers. Understanding the sequence of events matters for anyone building risk models around systemic financial events.</p>
<div>
<div>
<div>March 8, 2023 — Wednesday</div>
<div>SVB Announces $1.8B Asset Sale at Loss</div>
<div>Silicon Valley Bank disclosed it had sold a portfolio of mortgage-backed securities for a $1.8 billion loss and was seeking to raise $2.25 billion in equity capital. The announcement was framed as a routine balance sheet adjustment, but the market recognized it for what it was: a distress signal from one of the largest banks in the technology and venture capital ecosystem.</div>
</div>
<div>
<div>March 9, 2023 — Thursday</div>
<div>Deposit Flight Begins: $42 Billion Withdrawn in 24 Hours</div>
<div>Fear cascaded through the tech and VC community faster than any regulatory response could materialize. In a 24-hour window, SVB saw an estimated $42 billion in deposit outflows — the largest bank run in U.S. financial history. The speed was unprecedented, fueled by digital banking and social media making it trivial for depositors to move money instantly. Venture capital firms and technology companies with deposits above the FDIC insurance limit began frantically wiring funds to larger, systemically important banks.</div>
</div>
<div>
<div>March 10, 2023 — Friday Morning</div>
<div>FDIC Seizes SVB; California DFPI Takes Control</div>
<div>The California Department of Financial Protection and Innovation closed Silicon Valley Bank and placed it into FDIC receivership at 1:00 PM ET on Friday, March 10. The FDIC created the Deposit Insurance National Bank of Santa Clara to ensure uninterrupted service for insured deposits. The bank's 2022 annual report, filed just days earlier, showed $209 billion in total assets — making SVB the second-largest bank failure in U.S. history after Washington Mutual in 2008.</div>
</div>
<div>
<div>March 10–12, 2023 — Weekend</div>
<div>Contagion Fears Spread; Signature Bank Also Closed</div>
<div>The weekend brought the full weight of financial media attention and government emergency response. President Biden addressed the nation. The Fed announced an emergency lending facility to prevent liquidity crises at other banks. Signature Bank was closed on Sunday, March 12, for similar reasons — rapid deposit flight and exposure to the same interest rate risk that had sunk SVB. The question on every market participant's mind: who is next?</div>
</div>
<div>
<div>March 13–17, 2023</div>
<div>Market Volatility Peaks; First Republic Under Pressure</div>
<div>The S&P 500 dropped approximately 7% in three trading days as the full scope of potential regional bank contagion became impossible to model with confidence. Credit spreads on regional bank bonds widened dramatically. First Republic Bank, another technology-focused regional bank, saw its stock fall over 80% in the week following SVB's collapse before a coordinated group of major banks injected $30 billion in deposits to stabilize it — a move that ultimately proved insufficient before First Republic was seized in early May 2023.</div>
</div>
</div>
</div>
<!-- AdSense -->
<!-- AdSense -->
</section>

<section class="section">
<h2 >Contagion Dynamics</h2>
<p >SVB did not fail in isolation — its collapse revealed a set of interconnected vulnerabilities that markets immediately tried to price.</p>
<div class="content-block">
<h3>The Interest Rate Risk Hidden in Plain Sight</h3>
<p>SVB's failure was fundamentally a story about interest rate risk — not credit risk in the traditional sense. The bank had purchased long-duration fixed-income assets (primarily mortgage-backed securities and Treasuries) funded by short-duration liabilities (tech VC deposits that could leave overnight). When rates rose sharply in 2022, the market value of SVB's asset portfolio fell far below its book value. SVB was technically solvent — but illiquid. It needed to sell assets at a loss to meet deposit withdrawals, which triggered the run. This mismatch between duration of assets and liabilities is a structural vulnerability that exists to varying degrees across many regional and community banks.</p>
<h3>The Social Media Acceleration Problem</h3>
<p>Prior to digital banking, a bank run took time — depositors had to physically show up at a branch to withdraw funds. Silicon Valley Bank served a client base — technology startups and venture capital firms — that was among the most digitally connected in the world. When a prominent VC firm texted a few peers suggesting they pull deposits from SVB, the signal propagated across the entire ecosystem within hours via Twitter, Slack, and text chains. The speed of modern bank runs is a risk that most financial models did not adequately incorporate before March 2023.</p>
<h3>The Uninsured Deposit Premium</h3>
<p>Before SVB, the practical risk of having deposits above the $250,000 FDIC insurance limit was considered theoretical for well-capitalized banks. SVB demonstrated that "too big to fail" logic applies not just to large banks but to banks whose deposit base is heavily concentrated in a single sector that moves as a herd. The technology and VC ecosystem treated SVB's uninsured deposits as effectively insured by virtue of the bank's systemic importance to their world — and that assumption was catastrophically wrong.</p>
</div>
</section>

<section class="section">
<h2 >Strategies That Worked</h2>
<p >During a rapid systemic stress event, the difference between a hedging strategy that worked and one that did not came down to speed of implementation and strike selection.</p>
<div class="content-block">
<h3>Protective Puts on Broad Indices</h3>
<p>Traders who held protective put positions on SPY or QQQ going into March 2023 had the most direct hedge against the rapid market drawdown. The S&P 500 fell roughly 7% in three trading days — a sharp, fast move that most long-equity portfolios cannot weather without meaningful drawdown. A protective put — owning shares or an ETF while holding a put option for downside protection — allowed those portfolios to participate in any recovery while limiting losses during the acute crisis phase. The key was that these puts were established before the crisis, not bought during it when IV was already spiking and premiums were elevated.</p>
<h3>Long Volatility / VIX Calls</h3>
<p>Buying VIX calls or long-gamma strategies (via ETF structures like VIXY or UVXY) during the early stages of the SVB crisis were highly profitable. The VIX spiked from around 18 on March 7 to approximately 30 by March 13 — a move that made VIX call positions extremely lucrative. The challenge, as always with volatility instruments, is timing: buying VIX calls after the spike has already occurred is chasing the move and likely to underperform. Traders who had established small long-VIX positions before the crisis, or who bought VIX calls when the initial SVB announcement showed potential for systemic concern, captured significant gains.</p>
<h3>Short Regional Bank Exposure</h3>
<p>Direct short positions against regional bank stocks — KRE (the SPDR S&P Regional Banking ETF) or individual regional bank names — were profitable as a short-term tactical trade. Once SVB was seized and the contagion narrative took hold, the path of least resistance for regional bank stocks was sharply lower. Short sellers who established positions in the $42 billion deposit flight window (March 9–10) captured the initial crash. Managing the risk of a government backstop that might squeeze shorts required active position management, but the directional trade was clearly correct in the immediate aftermath of the SVB announcement.</p>
<h3>Flight to Safety: Long Treasuries</h3>
<p>Ironically, in a banking crisis driven by interest rate risk, long-duration U.S. Treasuries were one of the best-performing asset classes during the acute crisis phase. The logic: if the Fed pivots toward easing (or even pauses rate hikes) due to financial stability concerns, long-duration Treasuries benefit from both the safety bid and the rate pivot. Traders who held long Treasury positions (via TLT or individual bonds) as a flight-to-safety hedge saw meaningful gains as the crisis unfolded — even as equity positions were getting hammered.</p>
</div>
</section>

<section class="section">
<h2 >Strategies That Failed</h2>
<p >The SVB crisis also revealed strategies that were structurally unprepared for a rapid, systemic financial event — or that actively made things worse.</p>
<div class="content-block">
<h3>Long Positions in Regional Bank Stocks</h3>
<p>Buying regional bank stocks on the dip — a common "value" strategy — was treacherous in the immediate aftermath of SVB. The market was not pricing regional banks on fundamentals in mid-March 2023; it was pricing them on contagion risk. Any bank with SVB-like characteristics (high uninsured deposits, duration mismatch, tech VC customer concentration) was under selling pressure regardless of actual solvency. The trader who bought FRC at $80 expecting a bounce was caught when it went to $3 before being seized. Without a way to differentiate which banks were sound and which were vulnerable, buying the sector on valuation grounds was picking up pennies in front of a steamroller.</p>
<h3>Momentum Strategies</h3>
<p>Momentum — the tendency of recent price trends to persist — is a well-documented factor in normal markets. During the SVB crisis, momentum signals generated whiplash after whiplash as regime changed multiple times within days. The sell-off on March 9 accelerated into March 10. A momentum system that read the sharp drop as a "continue short" signal got crushed when the Fed's emergency lending facility announcement on March 12 triggered a historic intraday reversal. On March 13, the S&P 500 opened up 4% from the prior close — the largest gap-up open in years. Any strategy built on recent trend persistence was fighting violent regime changes that momentum models were not designed to handle.</p>
<h3>Unhedged Long Equity Exposure</h3>
<p>The most basic failure mode in the SVB crisis was simply being long equities without any put protection or volatility hedge. The S&P 500 dropped 7% in three days — meaningful enough to significantly impact a long-only portfolio, especially one with concentrated regional bank exposure. This is not a sophisticated strategy failure; it is a risk management failure. In any market environment, having some form of downside protection — even if it costs carry — prevents the kind of portfolio drawdown that forces poor selling decisions at the worst possible time.</p>
<h3>Buying VIX After the Spike</h3>
<p>VIX reached approximately 30 by March 13 — and then collapsed back toward 20 over the following weeks as it became clear the Fed and FDIC had contained the immediate contagion. Traders who bought VIX call options at the peak of the crisis — when premium was most expensive and IV was highest — found that even a correct directional bet on volatility could lose money as VIX mean-reverted. The time decay on long VIX positions after a crisis is contained is punishing. Chasing volatility after it has already spiked is almost always a losing trade for retail options participants.</p>
</div>
<div>
<p><strong>The key lesson:</strong> SVB was a fast-moving, narrative-driven crisis. The strategies that worked were ones that had been established before the event — protective puts, long volatility positions, short regional bank exposure — not strategies that tried to chase the move after the market had already repriced it. The cost of waiting is always highest in a crisis, because by the time the narrative is clear, option premiums have already adjusted and the edge is gone.</p>
</div>
</section>

<section class="section">
<h2 >Broader Implications for Options Traders</h2>
<div class="content-block">
<p>The SVB crisis is not just a banking story — it is a case study in how quickly systemic risk can materialize and how market microstructure changes during a financial crisis. Several patterns emerge:</p>
<ul>
<li><strong>Contagion is non-linear.</strong> Traditional risk models that assume contagion spreads proportionally to exposure dramatically underestimate the speed and scale of cascade failures in a digitally-connected financial system. Options traders should think about tail risk as having a binary quality — either contagion does not spread beyond the initial event, or it spreads much faster than models predict.</li>
<li><strong>Duration risk is underestimated in banking.</strong> The 2022–2023 rate environment exposed duration mismatches across the banking system that are not adequately captured by standard credit risk models. If you are trading bank-related options or have regional bank exposure, interest rate sensitivity should be a primary risk consideration alongside traditional credit metrics.</li>
<li><strong>Government response speed can compress volatility quickly.</strong> The Fed's emergency lending facility announcement on March 12 compressed VIX dramatically within days of the spike. Traders who held long volatility positions expecting an extended crisis found that government intervention could end the acute phase faster than expected. The lesson: do not confuse a contained acute crisis with a resolved structural problem — but also do not underestimate how fast regulatory response can change the options market landscape.</li>
</ul>
</div>
</section>

<section class="section">
<div class="info-box">
<h3>Continue Learning</h3>
<p>Explore risk management frameworks and volatility analysis in our educational hubs.</p>
<div>
<a href="/risk-hub/">Risk Management Hub</a>
<a href="/vix-hub/">VIX & Volatility Hub</a>
<a href="/protective-strategies/">Protective Strategies</a>
<a href="/iron-condors-explained/">Iron Condors Explained</a>
<a href="/educational-resources/">All Resources</a>
</div>
</div>
</section>
<div>
<div>
<strong>Important Disclaimer — Please Read</strong><br />
Dependability Holdings LLC is an investment holding company. This webpage is for informational and educational purposes only and does not constitute financial, investment, or legal advice.
Dependability Holdings LLC is not a registered broker-dealer. All content is for educational purposes only. The information provided herein should not be construed as personalized investment advice, a recommendation to buy, sell, or hold any investment, or an offer or solicitation to buy or sell securities.
<br /><br />
All investments involve risk, including the potential loss of principal. The value of investments can fluctuate, and past performance may not be indicative of future results. Please consult with a qualified financial advisor, attorney, or tax professional before making any investment decisions.
</div>
</div>
