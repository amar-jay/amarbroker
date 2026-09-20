# AmarBroker

## Purpose

AmarBroker is a private, AI-first investment assistant for an individual investor.

Its purpose is to turn a fragmented collection of brokerage records, market data, company disclosures, research, and personal notes into a coherent understanding of a portfolio. It should help its owner know what they own, why they own it, what has changed, and what deserves attention.

AmarBroker is not intended to replace judgment. It exists to make better judgment easier.

## The problem

Personal investment information is scattered across broker interfaces, market-data services, regulatory filings, news sources, spreadsheets, and notes. Traditional financial terminals make large amounts of information available, but they still expect the investor to find, reconcile, interpret, and remember that information manually.

General-purpose AI assistants can help analyze individual documents or questions, but they usually lack a durable understanding of the investor's actual portfolio, previous decisions, constraints, and investment theses.

AmarBroker brings those pieces together into one personal system that is built for both deterministic analysis and agentic interaction.

## What AmarBroker should accomplish

### Maintain an accurate portfolio record

AmarBroker should ingest transactions and statements, reconstruct holdings, and calculate balances, cost basis, gains, income, performance, and exposure. Financial calculations must be performed by deterministic code and remain traceable to their source records.

### Explain what matters

AmarBroker should turn raw portfolio and market activity into concise, personalized briefings. It should identify the events and changes that materially affect the owner's holdings, watchlist, risks, and stated investment goals.

### Support investment research

AmarBroker should gather and organize relevant market data, company fundamentals, regulatory filings, earnings information, news, and macroeconomic data. Important statements should retain citations and provenance so that conclusions can be verified.

### Preserve investment memory

AmarBroker should remember the reasoning behind a position: the original thesis, assumptions, expected catalysts, risks, valuation, time horizon, confidence, and conditions for adding or exiting. It should compare new evidence with that recorded thesis and highlight when the facts have materially changed.

### Improve decisions

Before a decision is made, AmarBroker should help evaluate its consequences. It should expose concentration, duplicated exposure, downside scenarios, conflicts with personal rules, unsupported assumptions, and evidence that could invalidate the proposed decision.

### Monitor quietly

AmarBroker should watch for relevant filings, earnings, price movements, estimate changes, portfolio risks, and thesis developments. Notifications should be selective and material rather than a continuous stream of generic market noise.

## Product principles

### Personal by design

AmarBroker is designed first for one owner, their accounts, their strategy, and their way of thinking. It does not need to imitate a public brokerage platform or optimize for a broad social audience.

### Private by default

Portfolio records, documents, research, credentials, and conversations are sensitive. AmarBroker should minimize exposure, collect only what it needs, and keep control of the data with its owner.

### Read-only by default

The initial product observes, imports, calculates, researches, and advises. Any future trading capability must be introduced gradually, require explicit approval, clearly display the proposed order, and reconcile the request with the actual broker response and fills.

### Evidence before eloquence

An answer should be grounded in identifiable records and sources. AmarBroker must distinguish sourced facts, deterministic calculations, interpretations, and uncertainty. It should say when information is missing, stale, conflicting, or unreliable.

### Deterministic where correctness matters

Language models may interpret, summarize, compare, and converse. They must not be the authority for balances, positions, returns, exposure, or other calculations that can be performed and tested in code.

### Memory with provenance

AmarBroker should retain not only conclusions but also when they were formed, which evidence supported them, and how they changed over time. New information must not silently rewrite the history of an investment decision.

### Useful rather than comprehensive

The product should prioritize a small number of dependable workflows over shallow access to every market, provider, asset class, or analytical technique. Additional capabilities should be introduced because they solve a real personal need.

### Provider-independent at its core

External APIs and brokers are replaceable sources and execution venues. AmarBroker should own its internal financial concepts and preserve source-specific details without allowing any provider's response format to become its permanent domain model.

### Human authority

AmarBroker may surface evidence, challenge assumptions, simulate outcomes, and propose actions. The owner remains responsible for investment decisions. The system should never imply certainty where none exists or silently act beyond the authority it has been given.

## Initial product promise

The first complete version of AmarBroker should allow its owner to:

1. Import a portfolio from a broker statement or structured file.
2. Review normalized transactions and calculated holdings.
3. Retrieve current and historical information for those holdings.
4. Record an investment thesis for each position.
5. Receive a concise, cited briefing about meaningful portfolio changes.
6. Ask questions about performance, exposure, events, and prior reasoning.

This is the minimum useful loop: **observe, understand, remember, and decide**.

## What AmarBroker is not

At its foundation, AmarBroker is not:

- A public brokerage or custodian
- A replacement for licensed market-data feeds
- A high-frequency or autonomous trading system
- A social investing network
- A generic market-news aggregator
- A promise of profitable recommendations
- A Bloomberg Terminal clone
- A system that delegates numerical truth to a language model

These boundaries protect the product from becoming broad before it becomes useful.

## Long-term direction

AmarBroker may eventually connect directly to brokerage accounts, prepare orders, run deeper scenario analysis, and execute explicitly approved actions. Those capabilities should extend the same foundation of privacy, provenance, deterministic calculation, and human control.

The long-term ambition is not to display the most information. It is to give one investor the clearest possible understanding of their portfolio and the strongest possible support for making deliberate decisions.

## Measure of success

AmarBroker succeeds when its owner can answer, with confidence and supporting evidence:

- What do I own?
- How is it performing, and why?
- What changed that matters to me?
- Why did I make this investment?
- Is the original thesis still intact?
- What risks am I taking?
- What deserves my attention next?
- How would a proposed decision change my portfolio?

If AmarBroker consistently makes those answers faster, clearer, and more trustworthy, it is fulfilling its purpose.
