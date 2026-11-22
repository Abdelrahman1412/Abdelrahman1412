# Abdelrahman Tarek

I build delivery and quality systems from zero.

At my last company, a fast-growing HR and payroll SaaS in the Gulf, I joined with no QA process, no frontend tests, no test data and no shared way of shipping. A year later, features started from a clear brief, tests meant something when they passed, every engineer could stand up a realistic company in one command, and AI coding agents worked under the same rules as the team.

These repos are generic, rebuilt-from-scratch versions of that work. Each one is configurable for any company.

## How a team ships

- **[delivery-kit](https://github.com/Abdelrahman1412/delivery-kit)**: from a one-line request to shipped, proven work. Briefs with testable acceptance criteria, approved designs, small PRs and proof before hand-off, packaged as Claude Code skills. Replaying three shipped features showed the brief alone would have caught 42% of the issues QA later found.
- **[review-feedback-loop](https://github.com/Abdelrahman1412/review-feedback-loop)**: turns review comments that keep coming back into rule changes, and flags rules that are not working.

## Making AI agents safe in real codebases

- **[agent-guardrails](https://github.com/Abdelrahman1412/agent-guardrails)**: an `AGENTS.md` generator, a review rubric mined from your own PR history, and pre-push hooks that stop unproven work from leaving the machine.
- **[design-system-drift](https://github.com/Abdelrahman1412/design-system-drift)**: keeps design, code and Storybook on one source, so agents build what was approved and drift fails CI.

## Testing that people trust

- **[playwright-claude-kit](https://github.com/Abdelrahman1412/playwright-claude-kit)**: a Playwright E2E and API framework built for teams and AI agents: page objects, multi-role auth that just works, API-seeded data, and the rules that let Claude explore a screen and write reliable tests instead of guessing. The generic version of the first frontend test framework I built.
- **[golden-seed](https://github.com/Abdelrahman1412/golden-seed)**: a realistic company, ready to test, in one command, with a verifier that blocks broken data before anyone tests on it.
- **[fast-ci](https://github.com/Abdelrahman1412/fast-ci)**: CI that is fast and honest. Sharded backend tests on a cached database, sharded Playwright with a mocked fast lane, and guards against retries that hide failures. In practice: backend tests from about 20 minutes to under 5, the frontend gate from 45 minutes to 16.
- **[local-stack](https://github.com/Abdelrahman1412/local-stack)**: many isolated copies of a multi-service app on one machine, so people and agents can validate features in parallel without collisions.

## Voice AI

- **strix-halo-ai**: a private Egyptian Arabic and English voice assistant running fully on local open models, with an Egyptian evaluation set, blind A/B voice ratings and a pronunciation layer for Egyptian speech.

---

Lead SDET turned delivery lead. Arabic and English. Open to roles in the UAE and Saudi Arabia.
