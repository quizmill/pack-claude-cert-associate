# Claude Associate Practice — quizmill practice pack

**Unofficial** practice for the **Claude Certified Associate – Foundations (CCAO-F)** exam. Not
affiliated with or endorsed by Anthropic.

This is a learning pack for [quizmill](https://github.com/quizmill/quizmill).
The pack is pure JSON; the engine turns it into an installable, offline-first
practice app.

## What's in it

**60 questions** (50 single-answer, 10 "select TWO") from
Matthew Purcell's [CCAO-F full practice question set](https://www.linkedin.com/feed/update/urn:li:activity:7485091186098077697/), used
with his permission. It matches the live exam's item count, weighted to the
exam blueprint, with his rationale on every answer. The app offers it as the paper
"CCAO-F practice exam"; the domains below are also practised one by one.

| Domain | Weight | Questions |
|---|---|---|
| Prompting and Task Execution | 14% | 8 |
| Output Evaluation and Validation | 21% | 13 |
| Product and Model Selection | 12% | 7 |
| Workflow Integration and Solution Design | 16% | 10 |
| Configuration and Knowledge Management | 12% | 7 |
| Governance, Risk, and Responsible Use | 15% | 9 |
| Troubleshooting and Optimization | 10% | 6 |

His advice: 120 minutes for the whole set, the live exam's time limit, and
aim for about 75% in every domain.

## Run it

```
npx quizmill run quizmill/pack-claude-cert-associate
```

## Checking the pack

```
npx quizmill validate .
```

See [NOTICE.md](NOTICE.md) for attribution.
