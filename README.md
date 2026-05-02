# GroveStreams Community

Welcome to the official GroveStreams community hub — the place to ask questions, share what you're building, suggest ideas, report bugs, and connect with other GroveStreams users.

## What is GroveStreams?

**GroveStreams is the Temporal Intelligence Platform™** — one platform that replaces your historian, relational database, analytics engine, dashboards, and ML pipeline.

> **Every Value. Every Relationship. Every Point in Time.**
>
> Most platforms forget. GroveStreams remembers — every value, every relationship, every change.

The architectural idea is simple: **everything is a stream**. Every property on every entity, and every relationship between entities, is a time-series stream with its own independent time axis — queryable through a single language (**GS SQL™**), with built-in AI forecasting and correlation detection. One primitive replaces history tables, audit triggers, materialized views, batch roll-up jobs, and junction tables.

Today the platform powers **6,600+ organizations**, **1.7 million streams**, and **307,000+ real-time derivations**, with 10 years in production.

### What's in the box

- **GS SQL** — purpose-built temporal query language; query 100M+ data points per stream in a single line.
- **AI forecasting** — TFT, N-BEATS, ARIMA, Prophet, TCN, Transformer, Exponential Smoothing, RNN — all built in.
- **AI Assistant** — multi-provider (OpenAI, Anthropic, Gemini, xAI) with 35+ tools and natural-language schema generation.
- **Real-time roll-ups & derived streams** — Excel-style formulas, automatic from seconds through years.
- **Full DDL** — `CREATE`, `ALTER`, `DROP` for 15+ entity types, with live schema reconciliation and zero downtime.
- **ODBC / JDBC / OData** — connect Power BI, Tableau, DBeaver, Grafana, Excel, SAP — with saved-query VIEWs for full time-series access.
- **Spatiotemporal** — lat, lon, elevation, heading as native streams.
- **Security** — SOC 2 certified, RBAC enforced at the query layer, 2FA, custom branding with branded subdomains.

Learn more at [grovestreams.com](https://www.grovestreams.com) · [GS SQL docs](https://www.grovestreams.com/developers/gsql.html) · [Forecasting docs](https://www.grovestreams.com/developers/forecasting.html)

---

## Where to post — Issues vs. Discussions

This repo uses **both** GitHub Issues and GitHub Discussions. Pick the right one:

### 🐞 Use [Issues](../../issues) for bugs and bug fixes

Open an Issue when something is broken, behaves unexpectedly, or you want to propose a specific fix.

- Reproducible bugs in the platform, GS SQL, dashboards, connectors, or the API
- Crashes, error messages, hangs, incorrect results
- Documentation that's wrong or out of date
- Pull requests against our [public example repos](https://github.com/GroveStreams) — link the relevant Issue

We track Issues like work items: they get labeled, triaged, assigned to a release, and closed when fixed.

### 💬 Use [Discussions](../../discussions) for everything else

Pick the category that fits:

- **📣 Announcements** — Release notes and platform updates from the GroveStreams team.
- **❓ Q&A** — "How do I…" questions. Mark answers as accepted so others can find them later.
- **💡 Ideas** — Feature requests and platform suggestions. Upvote ideas you'd like to see.
- **🛠 Show & Tell** — Share a project, dashboard, GS SQL recipe, integration, or use case.
- **💬 General** — Anything else community-related.

**Not sure which to use?** If you can describe steps to reproduce a wrong behavior, it's an Issue. If you're asking for help, sharing, brainstorming, or requesting something new, it's a Discussion. We'll move it if you guess wrong — no harm done.

---

## Filing a good bug report

The faster we can reproduce it, the faster it gets fixed. A good Issue includes:

- **What you expected** vs. **what actually happened**
- **Steps to reproduce** — exact clicks, exact GS SQL, exact API request
- **Environment** — browser & version, plan tier, organization region (US/EU/etc.) if relevant
- **Error messages or screenshots** — copy-paste, don't paraphrase
- **Approximate timestamp** — helps us cross-reference server logs
- **Code in code blocks** — wrap GS SQL, JSON, and DDL in triple backticks

**Don't post in a public Issue:**
- API keys, passwords, session tokens
- Organization UIDs tied to confidential data
- Customer or end-user PII

If reproducing the bug requires sharing private data, file a brief public Issue and email details to [support@grovestreams.com](mailto:support@grovestreams.com) referencing the Issue number.

## Asking a good question

In Q&A, the more context you give, the faster you'll get a useful answer:

- What you're trying to accomplish (the goal, not just the immediate step)
- What you've already tried
- The exact error or unexpected behavior
- Relevant DDL, GS SQL, or API request — in a code block

Search before you post — your question may already be answered.

## Community rules

- **Be respectful.** Disagree about ideas, not people.
- **Stay on topic.** This is a place to talk about GroveStreams.
- **No spam, no harassment, no sharing others' private info.** We'll remove posts and ban accounts that do.

## Other ways to reach us

- **Account, billing, or anything sensitive:** [support@grovestreams.com](mailto:support@grovestreams.com)
- **Code examples & integrations:** the other repos under [github.com/GroveStreams](https://github.com/GroveStreams)
- **Website:** [grovestreams.com](https://www.grovestreams.com)
- **Social:** [X / Twitter](https://x.com/grovestreams) · [LinkedIn](https://www.linkedin.com/company/grove-streams-llc)

---

Thanks for being part of the GroveStreams community. We're glad you're here.
