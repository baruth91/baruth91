<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/header.svg" />
  <img src="assets/header-light.svg" alt="Phillip Baruth — QA engineer. Quality is the mission. Code is the tool." width="100%" />
</picture>

I'm **Phillip Baruth**, a QA engineer with **12 years of experience in software quality assurance**.

I turn quality risks into readable tests and share the decisions behind the code.
This is my personal lab for test automation, programming and learning in public.

### Languages and automation

Tools used in the case studies below. Follow a badge to see the implementation.

<p>
  <a href="https://github.com/baruth91/playwright-python-qa-case-study/tree/main/tests"><img src="assets/python.svg" alt="Python — explore the Playwright tests" height="30" /></a>
  <a href="https://github.com/baruth91/cypress-typescript-qa-case-study/tree/main/cypress"><img src="assets/typescript.svg" alt="TypeScript — explore the Cypress tests" height="30" /></a>
  <a href="https://github.com/baruth91/selenium-java-qa-case-study/tree/main/src/test/java"><img src="assets/java.svg" alt="Java — explore the Selenium tests" height="30" /></a>
  <a href="https://github.com/baruth91/selenium-csharp-qa-case-study/tree/main/tests"><img src="assets/csharp.svg" alt="C# — explore the Selenium and NUnit tests" height="30" /></a>
</p>
<p>
  <a href="https://github.com/baruth91/playwright-python-qa-case-study"><img src="assets/playwright.svg" alt="Playwright case study" height="30" /></a>
  <a href="https://github.com/baruth91/cypress-typescript-qa-case-study"><img src="assets/cypress.svg" alt="Cypress case study" height="30" /></a>
  <a href="https://github.com/baruth91/selenium-java-qa-case-study"><img src="assets/selenium.svg" alt="Selenium case study" height="30" /></a>
  <a href="https://github.com/baruth91/postman-api-qa-case-study"><img src="assets/postman.svg" alt="Postman API case study" height="30" /></a>
  <a href="https://github.com/baruth91/ai-assisted-qa-evaluation-case-study"><img src="assets/llm-evaluation.svg" alt="LLM evaluation learning case with real recorded model responses" height="30" /></a>
</p>
<p>
  <a href="https://github.com/baruth91/python-api-database-qa-case-study/tree/main/tests"><img src="assets/requests.svg" alt="Requests API integration tests" height="30" /></a>
  <a href="https://github.com/baruth91/python-api-database-qa-case-study"><img src="assets/postgresql.svg" alt="PostgreSQL transaction and integrity case study" height="30" /></a>
  <a href="https://github.com/baruth91/python-api-database-qa-case-study/tree/main/sql"><img src="assets/sql.svg" alt="SQL migrations and reconciliation exercises" height="30" /></a>
</p>

### Featured case studies

**[Expense review and stale decisions](https://github.com/baruth91/selenium-csharp-qa-case-study)** · Selenium / C# / NUnit / ASP.NET Core<br />
Nine real-browser cases: row identity, exact totals, filters, rejection evidence and optimistic concurrency. A specific mutation proves stale approvals are detected with browser diagnostics. [Verified CI](https://github.com/baruth91/selenium-csharp-qa-case-study/actions/runs/40775613588).

**[SOAP transfer integrity](https://github.com/baruth91/soapui-soap-qa-case-study)** · SoapUI / SOAP / XML / Java<br />
Versioned WSDL, namespace-aware XPath, exact money movement, idempotent retries and faults with unchanged state. 13 cases / 296 assertions, plus a verified missing-debit regression. [Verified CI](https://github.com/baruth91/soapui-soap-qa-case-study/actions/runs/40773900067).

<a href="https://github.com/baruth91/soapui-soap-qa-case-study"><img src="assets/soapui.svg" alt="SoapUI SOAP contract and transfer integrity case study" height="30" /></a>

**[Object ownership and API security](https://github.com/baruth91/api-security-zap-python-case-study)** · Python / pytest / OWASP crAPI / ZAP<br />
Real Java service, two-account authorization matrix, known BOLA reproduction and a scoped controller correction. Passive scanner results are interpreted alongside explicit ownership checks. [Execution evidence](https://github.com/baruth91/api-security-zap-python-case-study/blob/main/docs/validation.md).

<a href="https://github.com/baruth91/api-security-zap-python-case-study"><img src="assets/zap.svg" alt="ZAP passive observation in a scoped API security learning case" height="30" /></a>

**[Shopping journey](https://github.com/baruth91/playwright-python-qa-case-study)** · Playwright / Python / pytest<br />
Risk-based selection, cart arithmetic, browser/API checks and traces. [Execution scope](https://github.com/baruth91/playwright-python-qa-case-study/blob/main/docs/validation.md).

**[Transaction integrity](https://github.com/baruth91/cypress-typescript-qa-case-study)** · Cypress / TypeScript<br />
Controlled data, network synchronization, persisted transactions and exact balance changes. [Verified CI](https://github.com/baruth91/cypress-typescript-qa-case-study/actions/runs/40697835286).

**[Owner-record workflows](https://github.com/baruth91/selenium-java-qa-case-study)** · Selenium / Java / JUnit / Maven<br />
Record identity, input validation, explicit waits and browser lifecycle. [Verified CI](https://github.com/baruth91/selenium-java-qa-case-study/actions/runs/40706015776).

**[Order integrity](https://github.com/baruth91/postman-api-qa-case-study)** · Postman / JavaScript / HTTP<br />
Request chaining, exact totals, stock changes, access control and data-driven rejections against a local teaching API. [Verified CI](https://github.com/baruth91/postman-api-qa-case-study/actions/runs/40715919540).

**[Committed order data](https://github.com/baruth91/python-api-database-qa-case-study)** · Python / Requests / pytest / PostgreSQL<br />
Independent SQL observations, relational constraints, multi-item rollback and reconciliation queries that detect inconsistent totals. [Verified CI](https://github.com/baruth91/python-api-database-qa-case-study/actions/runs/40719981385).

**[AI-assisted QA evaluation](https://github.com/baruth91/ai-assisted-qa-evaluation-case-study)** · Python / pytest / Ollama<br />
Versioned prompts, real local-model responses, recorded replay and documented evaluator blind spots. [Harness CI](https://github.com/baruth91/ai-assisted-qa-evaluation-case-study/actions/runs/40766754597) · [Observed model failures](https://github.com/baruth91/ai-assisted-qa-evaluation-case-study/blob/main/docs/validation.md).

Each repository includes setup instructions, test rationale, learning exercises and
documented limits. Cypress and Selenium run their applications inside CI. The
Playwright case documents its separate local and hosted execution boundaries.
Postman runs a controlled in-memory API. The Python and PostgreSQL case extends the
domain with committed data, relational integrity and transaction rollback.

### How I approach quality

- Understand the behavior and risk before choosing what to automate.
- Verify meaningful outcomes, including persisted state where relevant.
- Keep tests independent and environments reproducible.
- Investigate failures with evidence and explain what a passing test cannot prove.

### Learning in public

These case studies are also my study material. I'm developing practical QA training
resources one explained example at a time, with code people can run and question.

Gamer at heart. Curious about how things work — and what happens when they don't.
**Build · test · learn · respawn.**

<sub>Personal projects and independent learning. This profile does not represent employers or clients.</sub>
