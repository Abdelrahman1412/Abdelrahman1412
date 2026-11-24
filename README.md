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

- **[quality-vault](https://github.com/Abdelrahman1412/quality-vault)**: one source of truth about an app for people and AI agents: a mind map, behaviour specs per module, test cases placed at the right layer, data inventories that drive the seed, and a register of past findings. A checker holds every claim to the code, and a per-release sweep names the changed functions and the rules to re-read, so nobody re-explores the app and the vault cannot quietly go stale.
- **[playwright-claude-kit](https://github.com/Abdelrahman1412/playwright-claude-kit)**: a Playwright E2E and API framework built for teams and AI agents: page objects, multi-role auth that just works, API-seeded data, and the rules that let Claude explore a screen and write reliable tests instead of guessing. The generic version of the first frontend test framework I built.
- **[golden-seed](https://github.com/Abdelrahman1412/golden-seed)**: a realistic company, ready to test, in one command, with a verifier that blocks broken data before anyone tests on it. Property-based tests (Hypothesis) found three payroll and leave bugs the hand-written suite missed.
- **[fast-ci](https://github.com/Abdelrahman1412/fast-ci)**: CI that is fast and honest. Sharded backend tests on a cached database, sharded Playwright with a mocked fast lane, and guards against retries that hide failures. In practice: backend tests from about 20 minutes to under 5, the frontend gate from 45 minutes to 16. A schema-driven API fuzzer (Schemathesis) runs as its own lane; on a demo API with 390 passing tests it found nine defects, one of which created a payroll run for 1970.
- **[vitest-migration-parity](https://github.com/Abdelrahman1412/vitest-migration-parity)**: move tests from Jest to Vitest and prove, with mutation testing, that each new test catches every bug the old one caught before the old one is deleted. A deliberately weakened port fails CI with the exact lines it stopped protecting.
- **[local-stack](https://github.com/Abdelrahman1412/local-stack)**: many isolated copies of a multi-service app on one machine, so people and agents can validate features in parallel without collisions.

## Framework toolkit

The same small demo HR app, tested five ways. Each one runs offline, in CI, and is ready to point at your own app.

- **[playwright-claude-kit](https://github.com/Abdelrahman1412/playwright-claude-kit)**: Playwright + TypeScript, with Playwright's planner, generator and healer test agents working under the kit's rules.
- **[cypress-framework](https://github.com/Abdelrahman1412/cypress-framework)**: Cypress 16 + TypeScript.
- **[selenium-java-framework](https://github.com/Abdelrahman1412/selenium-java-framework)**: Selenium 4, JUnit 5, Java 21, Selenium Grid and Allure.
- **[rest-assured-framework](https://github.com/Abdelrahman1412/rest-assured-framework)**: REST Assured API tests: auth, CRUD, validation, role permissions and response contracts, in about 10 seconds.
- **[robot-framework-starter](https://github.com/Abdelrahman1412/robot-framework-starter)**: Robot Framework 7, keyword-driven UI and API acceptance tests.

## Voice AI

- **[voice-agent-evals](https://github.com/Abdelrahman1412/voice-agent-evals)**: pick a voice and ship a voice agent on evidence instead of taste. Round-trip word error rate with Arabic normalisation, an Egyptian pronunciation lexicon, latency budgets, simulated conversations and blind A/B ratings, in Arabic and English.
- **strix-halo-ai**: a private Egyptian Arabic and English voice assistant running fully on local open models, with an Egyptian evaluation set, blind A/B voice ratings and a pronunciation layer for Egyptian speech.

---

Lead SDET turned delivery lead. Arabic and English. Open to roles in the UAE and Saudi Arabia.
