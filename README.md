**English** | [Türkçe](README.tr.md)

# Gürkan Uzunpınar

**AI & Automation Developer** · verifiable AI systems for finance and operations · philologist by training

I build AI systems for work where a wrong number costs money. I'm self-taught: I have worked hands-on with AI since 2024, when I started training LLMs through RLHF at Outlier, and I have been building production software since 2026. I work AI-natively: I co-design the architecture with AI in brainstorming sessions, write the specifications and own the verification, and coding agents write most of the code under that control.

## Featured

**[Z-Report Pipeline: case study](https://github.com/gurkanuzunpinar/z-report-pipeline)**
A deterministic parsing and verification engine for accounting data, running in production. Every month it turns an average of 1,500 end-of-day Z-reports, printed by the fiscal cash registers of nine fuel stations, into validated accounting records that go into tax filings. The design rule: a value is either proven by the receipt's own arithmetic or put in front of a person. The repository includes a runnable reference implementation on synthetic data.
`Python` `FastAPI` `SQL Server` `PaddleOCR` `pytest`: 598 commits and 2,850+ automated tests.

## How I work

- **Errors must never pass silently.** A plausible wrong value is more dangerous than an empty cell, so uncertainty is shown, not hidden.
- **Deterministic rules decide; models read.** In financial data, an LLM's guess is never treated as fact.
- **Measure before optimizing.** False acceptance, operator questions and P95 latency are tracked as separate KPIs.
- **Agents get the same distrust as OCR.** What an agent produces is a candidate until something independent confirms it. Tasks are closed briefs with measured evidence and acceptance criteria, work happens in isolated worktrees and database clones, measurement decides, and a reviewer that shares no context tries to break the result. No sub-agent has a write path to financial data. ([The full method](https://github.com/gurkanuzunpinar/z-report-pipeline#how-it-was-built-ai-native-with-the-same-distrust))

## Background

English Language & Literature (Ege University) → teaching → Turkish Airlines → international travel sales, where I was product owner for custom sales and accounting software → AI training data (Outlier) → in-house AI & automation at a fuel retail group. Language, structure and ambiguity have always been my material. Now I work with them in software.

📫 [LinkedIn](https://www.linkedin.com/in/gurkanuzunpinar) · Ankara / remote
