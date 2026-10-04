# ai-quality-lab

A year-long, public lab where a QA automation engineer learns to test, evaluate and ship machine learning and LLM systems.

## About me

I'm Juan José Betancourt, a QA Automation Engineer with 4+ years of experience in banking, healthcare and marketing. I build test automation with Selenium, Serenity BDD, Cypress and REST Assured, and I'm finishing a Master's in Artificial Intelligence (December 2026).

This repo is where I bring QA discipline to AI systems: data validation, ML model testing and evaluation of LLM applications.

## Goal

By September 2027, work as an **AI Quality Engineer** or **AI Engineer** on a remote, international team, with every skill listed here backed by working code in this repo.

## Roadmap

| Phase | Dates | Focus | Project | Status |
|---|---|---|---|---|
| 1 | Sep – Nov 2026 | Python engineering and testing foundations | `qa-python-toolkit` | In progress |
| 2 | Nov 2026 – Jan 2027 | Applied ML for credit risk and model quality | `credit-risk-model-qa` | Planned |
| 3 | Feb – Apr 2027 | MLOps: from notebook to production | `credit-risk-mlops` | Planned |
| 4 | Apr – Jul 2027 | LLMs, RAG, agents and evaluation | `bank-rag-evals`, `qa-agent` | Planned |
| 5 | Jul – Sep 2027 | Certification, portfolio and job search | — | Planned |

## What each project will show

- **qa-python-toolkit**: UI tests with Playwright, API tests with pytest and httpx, and data validation with Pandera, all running in GitHub Actions.
- **credit-risk-model-qa**: a credit risk model with a full ML test suite: invariance and directional tests, fairness checks, SHAP explanations and a model card.
- **credit-risk-mlops**: the same model served with FastAPI and Docker, tracked in MLflow, guarded by quality gates in CI and monitored for drift.
- **bank-rag-evals**: a RAG assistant over public banking documents, with automated evals (Ragas, DeepEval), observability (Langfuse) and red teaming (Promptfoo).
- **qa-agent**: an agent that explores a web app through Playwright MCP, proposes test cases and writes Playwright tests, evaluated like any other system under test.

## Principles

1. **Tests first, in CI.** Nothing reaches `main` without automated checks, including models and prompts.
2. **Measure, don't guess.** Every claim in a README comes with a metric or a test.
3. **Public data only.** All projects use public datasets. No employer code, data or internal details.
4. **Learn in public.** Each milestone ends with a write-up on LinkedIn.

## Repository structure

```
ai-quality-lab/
├── 01-qa-python-toolkit/
├── 02-credit-risk-model-qa/
├── 03-credit-risk-mlops/
├── 04-bank-rag-evals/
├── 05-qa-agent/
├── notes/              # weekly learning notes
└── README.md
```

Folders are added as each phase starts.

## Stack

**Today:** Java, Selenium, Serenity BDD, Cypress, REST Assured, Postman, SQL, GitHub Actions, Harness.

**Learning this year:** Python, pytest, Playwright, pandas, scikit-learn, MLflow, FastAPI, Docker, Evidently, Ragas, DeepEval, Promptfoo, Langfuse.

## Weekly log

| Week | Dates | Done |
|---|---|---|
| 1 | Sep 28 – Oct 4, 2026 | Environment set up (Python 3.12, uv, VS Code, Git), repo created, roadmap defined. |

## Contact

[LinkedIn](https://www.linkedin.com/in/juan-jose-betancourt/)
