<div align="center">

<a href="https://github.com/MauricioTaguchi">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&amp;color=0:312E81,50:6D28D9,100:4338CA&amp;height=230&amp;section=header&amp;text=Maur%C3%ADcio%20Taguchi&amp;fontSize=48&amp;fontColor=FFFFFF&amp;animation=fadeIn&amp;fontAlignY=36&amp;desc=Data%20Analyst%20%7C%20Power%20BI%2C%20SQL%20%26amp%3B%20Python%20%7C%20ETL&amp;descSize=14&amp;descAlignY=57" alt="Maurício Taguchi — Data Analyst | Power BI, SQL &amp; Python | ETL" />
</a>

<a href="https://github.com/MauricioTaguchi#about">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&amp;weight=500&amp;size=19&amp;duration=3200&amp;pause=1000&amp;color=A78BFA&amp;center=true&amp;vCenter=true&amp;width=760&amp;height=52&amp;lines=Data+Analyst+%7C+Power+BI%2C+SQL+%26+Python+%7C+ETL;Turning+data+into+clear+decisions.;Data+quality%2C+automation+and+analytics." alt="Animated introduction: data analysis, Power BI, SQL, Python, ETL and automation" />
</a>

<br />

[![Computer Science](https://img.shields.io/badge/B.Sc.-Computer_Science-6D28D9?style=flat-square&labelColor=171329)](https://www.unip.br/)
[![UNIP](https://img.shields.io/badge/UNIP-Graduated_2026-4338CA?style=flat-square&labelColor=171329)](https://www.unip.br/)
[![Location](https://img.shields.io/badge/Location-S%C3%A3o_Paulo%2C_Brazil-7C3AED?style=flat-square&labelColor=171329)](https://www.linkedin.com/in/mauriciotaguchi/)

<br />

[![Portfolio](https://img.shields.io/badge/Portfolio-6D28D9?style=for-the-badge&logo=github&logoColor=white)](https://mauriciotaguchi.com.br/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-4338CA?style=for-the-badge&logoColor=white)](https://www.linkedin.com/in/mauriciotaguchi/)
[![Email](https://img.shields.io/badge/Email-7C3AED?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mauricioryotoitataguchi@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-312E81?style=for-the-badge&logo=github&logoColor=white)](https://github.com/MauricioTaguchi)

<br />

[Case studies](https://mauriciotaguchi.com.br/case-studies/) · [Technical blog](https://mauriciotaguchi.com.br/blog/)

[![Profile views](https://komarev.com/ghpvc/?username=MauricioTaguchi&label=PROFILE+VIEWS&color=6d28d9&style=flat-square)](https://github.com/MauricioTaguchi)
[![Followers](https://img.shields.io/github/followers/MauricioTaguchi?label=Followers&style=flat-square&color=7C3AED&labelColor=171329&logo=github&logoColor=white)](https://github.com/MauricioTaguchi?tab=followers)
[![Stars](https://img.shields.io/github/stars/MauricioTaguchi?label=Total%20Stars&style=flat-square&color=4338CA&labelColor=171329&logo=github&logoColor=white)](https://github.com/MauricioTaguchi?tab=repositories)

</div>

---

## About

I'm **Maurício Taguchi**, a data analyst and Computer Science graduate from UNIP in São Paulo, Brazil. I work with **SQL, Python, Power BI and Excel** to clean and validate data, automate recurring tasks and build dashboards. At FIPE, I prepared economic and collective bargaining data for researchers and managers.

My personal projects explore the engineering behind this work. In **Income Analysis in Brazil**, I use official IBGE data to compare income across states and quarters. In **DataFlow**, I built a tool for inspecting data quality and tracing or reversing changes to a dataset.

### Open To

I'm looking for **junior Data Analyst and Business Intelligence roles**, remote or based in São Paulo. I also offer freelance data analysis and automation services.

**Languages** · Portuguese (native) · English (advanced) · Spanish (basic)

---

## Featured Personal Projects

<details open>
<summary><strong>Brazil Income Analysis — Official IBGE Data Pipeline</strong></summary>

<br />

A reproducible data engineering and analytics case study using official IBGE SIDRA income data.

| Dimension | Details |
| :--- | :--- |
| **Stack** | Python · Pandas · SQL · Pytest · Ruff · GitHub Actions · HTML/CSS |
| **Scale** | Coverage validation for all 27 Brazilian federative units over the 20 quarters from Q2 2021 to Q1 2026. |
| **Performance** | Bounded quarterly extraction and deterministic offline rebuilding from a committed source snapshot. |
| **Security** | Public source data, pinned dependencies and automated dependency-update monitoring. |
| **Impact** | Produces analytical datasets, a static dashboard and an executive summary with traceable source definitions. |
| **Explore** | [Case study](https://mauriciotaguchi.com.br/case-studies/brazil-income.html) · [Interactive dashboard](https://mauriciotaguchi.com.br/demos/income/) · [Source code](https://github.com/MauricioTaguchi/analise-renda-brasil) |

The pipeline separates **raw, staging and analytical layers**, validates coverage and invalid values, and preserves original responses for reprocessing. Official-series outputs are clearly distinguished from complementary synthetic portfolio examples. Tests enforce a configured **80% minimum coverage threshold**.

</details>

<details>
<summary><strong>DataFlow — Data Analytics Platform</strong></summary>

<br />

A full-stack analytics workspace that takes a dataset from ingestion to validated transformations, interactive dashboards and PDF reporting.

| Dimension | Details |
| :--- | :--- |
| **Stack** | Python · FastAPI · React · TypeScript · PostgreSQL · Redis · Celery · Docker |
| **Scale** | Bounded workloads with account quotas, upload admission controls and background job concurrency limits. |
| **Performance** | Asynchronous import, profiling, transformations and reports; cached coordination and paginated previews. |
| **Security** | Tenant isolation, rotating refresh tokens, revoked sessions, rate limits and streamed upload validation. |
| **Impact** | Connects data-quality inspection, reversible transformations, lineage and reporting in one reviewable product workflow. |
| **Explore** | [Case study](https://mauriciotaguchi.com.br/case-studies/dataflow.html) · [Interactive demo](https://mauriciotaguchi.com.br/demos/dataflow/) · [Source code](https://github.com/MauricioTaguchi/data-analytics-platform) |

The engineering centers on **recoverable data operations**: optimistic versions prevent conflicting changes, idempotency keys make retries explicit, and a transactional outbox preserves committed work during broker failures. Backend checks, frontend tests and desktop/mobile end-to-end journeys support the application. Deployment limits and operational responsibilities are documented.

</details>

<details>
<summary><strong>MarketPulse — Market Data & Pipeline Observability</strong></summary>

<br />

A near-real-time dashboard that ingests public Binance Spot data and presents market activity, pipeline health and experimental statistical forecasts.

| Dimension | Details |
| :--- | :--- |
| **Stack** | Java 17 · Spring Boot · React · TypeScript · PostgreSQL · Redis · WebSocket/STOMP · Docker |
| **Scale** | Single-instance MVP with per-symbol streams, bounded buffers and durable closed-candle storage. |
| **Performance** | Push-based interface updates, backend coalescing, hot-state caching and measured ingestion latency. |
| **Security** | Read-only public-data integration, configured frontend origins, WebSocket transport limits and restricted operational endpoints. |
| **Impact** | Makes source freshness, reconnections, throughput and forecast uncertainty visible alongside market data. |
| **Repository** | [Explore MarketPulse](https://github.com/MauricioTaguchi/marketpulse-live-dashboard) |

The pipeline uses **ordering, deduplication and idempotent persistence** to keep streaming and stored data consistent. Closed candles are published after transaction commit, while reconnection and REST reconciliation support recovery. Forecasts use chronological evaluation and baseline comparisons; the project documents their experimental nature and makes no fixed-latency or predictive-return claim.

</details>

<details>
<summary><strong>Smart Budget AI API — AI-Assisted Financial Workflows</strong></summary>

<br />

A Java backend that turns Portuguese text and voice requests into structured financial queries and confirmation-based operations.

| Dimension | Details |
| :--- | :--- |
| **Stack** | Java 17 · Spring Boot · Spring AI · PostgreSQL · H2 · Docker · JUnit |
| **Scale** | Individual-deployment API with a local deterministic mode and optional external AI integration. |
| **Performance** | External-model-free automated tests; request tracing, health probes and graceful shutdown support diagnosis. |
| **Security** | Production API-key checks, explicit mutation confirmation, bounded inputs and redacted auditing. |
| **Impact** | Demonstrates how conversational interfaces can expose useful application capabilities while preserving explicit control over writes. |
| **Repository** | [Explore Smart Budget AI API](https://github.com/MauricioTaguchi/smart-budget-ai-api) |

The application separates **domain, application and infrastructure responsibilities**. Read operations and proposed mutations follow different paths, and writes require confirmation. Tests cover domain behavior and application safeguards. Multiuser authorization and additional deployment requirements are documented as extensions to the current scope.

</details>

<details>
<summary><strong>FinanceFlow API — Domain Modeling & Design Patterns</strong></summary>

<br />

A focused financial REST API demonstrating design patterns, domain invariants and transaction-aware events.

| Dimension | Details |
| :--- | :--- |
| **Stack** | Java 17 · Spring Boot · Spring Data JPA · H2 · JUnit · JaCoCo · Maven |
| **Scale** | Self-contained engineering laboratory with simulated notification adapters. |
| **Performance** | Small, testable domain; notification listeners run after successful transaction commit. |
| **Security** | HTTP validation and domain invariants; authentication remains outside the laboratory scope. |
| **Impact** | Makes Strategy, Factory, Observer, Facade and Repository patterns concrete in an understandable business workflow. |
| **Repository** | [Explore FinanceFlow API](https://github.com/MauricioTaguchi/finance-flow-api) |

The design emphasizes **correctness at the domain boundary**. Entities protect transaction rules independently of HTTP validation, while post-commit listeners avoid notifying on rolled-back operations. Architecture notes explain where real asynchronous delivery and authentication would fit.

</details>

<details>
<summary><strong>FocusBoard — Offline Desktop Task Management</strong></summary>

<br />

A Java Swing task manager with search, filters, local persistence and CSV import/export.

| Dimension | Details |
| :--- | :--- |
| **Stack** | Java 17 · Swing · Maven · JUnit · GitHub Actions |
| **Scale** | Single-user desktop application with local UTF-8 storage. |
| **Performance** | Local search and filtering without network dependencies; atomic file replacement for persistence. |
| **Security** | No account, cloud synchronization or telemetry; task data remains in local files. |
| **Impact** | Provides a portable task workflow with dependable persistence and interoperable CSV exchange. |
| **Repository** | [Explore FocusBoard](https://github.com/MauricioTaguchi/focusboard) |

The application separates **interface state, task rules and persistence**. Writes use a temporary file followed by replacement to reduce corruption risk. Automated tests cover filtering, Unicode persistence and CSV round trips; the delivery workflow packages the application as a JAR.

</details>

<details>
<summary><strong>NotebookLM Financial Education Guide — Applied Generative AI</strong></summary>

<br />

A source-based learning project exploring prompt design, financial education and critical review of AI-generated material.

| Dimension | Details |
| :--- | :--- |
| **Stack** | NotebookLM · Markdown · Prompt engineering · Source curation |
| **Scale** | A focused study guide built around public educational sources, a glossary and reusable prompts. |
| **Performance** | Documents prompt refinement and response review; no model benchmark is claimed. |
| **Security** | Uses public educational material; private financial records and application credentials are not required. |
| **Impact** | Turns curated reference material into structured summaries, revision questions and reusable study workflows. |
| **Repository** | [Explore the NotebookLM Guide](https://github.com/MauricioTaguchi/miniguia-financas-notebooklm) |

Developed as a **DIO learning challenge**, the guide records prompt iterations, source selection and response weaknesses. It demonstrates practical AI-assisted knowledge organization with human verification of the resulting material.

</details>

---

## Experience

### Freelance Data Analyst · Self-employed

**August 2026 – Present · São Paulo, Brazil**

I offer data preparation and validation, dashboard development and workflow automation using SQL, Python, Power BI and Excel. Services include integrating spreadsheets, databases and REST APIs and documenting the process so teams can repeat it.

### Data Analysis Intern · FIPE — Fundação Instituto de Pesquisas Econômicas

**June 2024 — December 2025 · São Paulo, Brazil**

Supported economic research and analytical operations through data collection, validation, automation and reporting. Worked with collective bargaining information and related datasets, connecting recurring research processes with reproducible technical workflows.

- Collected, organized and tabulated economic and collective bargaining data.
- Used **Python and R** to clean, transform and validate analytical inputs.
- Integrated information from databases, APIs and spreadsheets into research workflows.
- Built and maintained **Power BI dashboards, indicators and Excel reports**.
- Applied **Excel/VBA and scripting** to automate recurring preparation and reporting steps.
- Documented procedures and validation rules to support consistency and handover.
- Used AI tools to assist analytical and documentation tasks with human review.

[![Python](https://img.shields.io/badge/Python-6D28D9?style=flat-square&logo=python&logoColor=white)](https://www.python.org/)
[![SQL](https://img.shields.io/badge/SQL-4338CA?style=flat-square)](https://www.linkedin.com/in/mauriciotaguchi/)
[![R](https://img.shields.io/badge/R-7C3AED?style=flat-square&logo=r&logoColor=white)](https://www.r-project.org/)
[![Power BI](https://img.shields.io/badge/Power_BI-4F46E5?style=flat-square)](https://www.linkedin.com/in/mauriciotaguchi/)
[![Excel / VBA](https://img.shields.io/badge/Excel_%2F_VBA-6D28D9?style=flat-square)](https://www.linkedin.com/in/mauriciotaguchi/)
[![Data Quality](https://img.shields.io/badge/Data_Quality-4338CA?style=flat-square)](https://github.com/MauricioTaguchi/data-analytics-platform)

---

## Selected Training

- **SQL Server, Azure SQL Database and Power BI** · 97 hours.
- **Microsoft Learn** · Eight completed Power BI modules covering [DAX formulas](https://learn.microsoft.com/api/achievements/share/pt-br/MaurcioTaguchi-8057/EGYQ79BP?sharingId=94DB18D7F91024F3), [semantic models](https://learn.microsoft.com/api/achievements/share/pt-br/MaurcioTaguchi-8057/BUZM7MHD?sharingId=94DB18D7F91024F3), report design, workspaces and content distribution.
- **Fundação Bradesco, Escola Virtual** · Power BI data preparation and analysis, and Excel coursework from basic through advanced (2025).

---

## Tech Stack

### Languages

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=python,java,ts,js,r,c,kotlin&amp;theme=dark&amp;perline=7" alt="Python, Java, TypeScript, JavaScript, R, C and Kotlin" />
  </a>
</p>

<p align="center">
  <a href="https://github.com/MauricioTaguchi/analise-renda-brasil"><img src="https://img.shields.io/badge/SQL-6D28D9?style=flat-square&amp;labelColor=171329" alt="SQL" /></a>
  <a href="https://www.linkedin.com/in/mauriciotaguchi/"><img src="https://img.shields.io/badge/DAX-4338CA?style=flat-square&amp;labelColor=171329" alt="DAX" /></a>
  <a href="https://www.linkedin.com/in/mauriciotaguchi/"><img src="https://img.shields.io/badge/VBA-7C3AED?style=flat-square&amp;labelColor=171329" alt="VBA" /></a>
</p>

### Frontend

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=react,ts,html,css,tailwind,vite&amp;theme=dark&amp;perline=6" alt="React, TypeScript, HTML, CSS, Tailwind CSS and Vite" />
  </a>
</p>

### Backend & Databases

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=fastapi,flask,spring,postgres,mysql,redis&amp;theme=dark&amp;perline=6" alt="FastAPI, Flask, Spring, PostgreSQL, MySQL and Redis" />
  </a>
</p>

<p align="center">
  <a href="https://github.com/MauricioTaguchi/data-analytics-platform"><img src="https://img.shields.io/badge/Celery-6D28D9?style=flat-square&amp;logo=celery&amp;logoColor=white" alt="Celery" /></a>
  <a href="https://github.com/MauricioTaguchi/marketpulse-live-dashboard"><img src="https://img.shields.io/badge/WebSocket_%2F_STOMP-4338CA?style=flat-square" alt="WebSocket and STOMP" /></a>
  <a href="https://www.linkedin.com/in/mauriciotaguchi/"><img src="https://img.shields.io/badge/SQL_Server-7C3AED?style=flat-square" alt="SQL Server" /></a>
</p>

### Cloud, DevOps & Tooling

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=docker,git,github,githubactions,nginx,maven&amp;theme=dark&amp;perline=6" alt="Docker, Git, GitHub, GitHub Actions, Nginx and Maven" />
  </a>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/mauriciotaguchi/"><img src="https://img.shields.io/badge/Power_BI-6D28D9?style=flat-square" alt="Power BI" /></a>
  <a href="https://github.com/MauricioTaguchi/analise-renda-brasil"><img src="https://img.shields.io/badge/Pandas-4338CA?style=flat-square&amp;logo=pandas&amp;logoColor=white" alt="Pandas" /></a>
  <a href="https://github.com/MauricioTaguchi/data-analytics-platform"><img src="https://img.shields.io/badge/Pytest-7C3AED?style=flat-square&amp;logo=pytest&amp;logoColor=white" alt="Pytest" /></a>
  <a href="https://github.com/MauricioTaguchi/data-analytics-platform"><img src="https://img.shields.io/badge/Playwright-4F46E5?style=flat-square" alt="Playwright" /></a>
  <a href="https://github.com/MauricioTaguchi/marketpulse-live-dashboard"><img src="https://img.shields.io/badge/Prometheus-6D28D9?style=flat-square&amp;logo=prometheus&amp;logoColor=white" alt="Prometheus" /></a>
</p>

**Cloud development:** Azure SQL training; continuing study of AWS data engineering, including Glue and Athena.

---

## AI / ML Expertise

| Domain | Proficiency | Details |
| :--- | :--- | :--- |
| **LLM application engineering** | Applied project experience | Java and Spring AI integration; natural-language requests mapped to structured financial operations in [Smart Budget AI API](https://github.com/MauricioTaguchi/smart-budget-ai-api). |
| **Tool calling & application safeguards** | Applied project experience | Explicit confirmation before mutations, input limits, checks for common prompt-injection patterns and redacted audit records. |
| **Text & voice interfaces** | Applied project experience | Optional external AI integration for text commands, transcription and speech responses, with a deterministic local mode for testing. |
| **Time-series forecasting** | Experimental implementation | [MarketPulse](https://github.com/MauricioTaguchi/marketpulse-live-dashboard) evaluates statistical forecasts against a random-walk baseline using chronological holdouts and empirical prediction intervals. |
| **Data preparation & quality** | Professional and project experience | Python, SQL, Pandas and R for validation, cleaning, profiling, reproducible transformations and analytical datasets. |
| **Prompt engineering & source review** | Applied learning project | [NotebookLM study guide](https://github.com/MauricioTaguchi/miniguia-financas-notebooklm) with curated sources, reusable prompts, response refinement and manual verification. |
| **Machine-learning foundations** | Continuing development | Feature preparation, model evaluation and scikit-learn experimentation; emphasis on reproducibility and evidence before deployment. |

---

## Achievements

<div align="center">

| Recognition | Details |
| :---: | :--- |
| **Computer Science Graduate** | Bachelor's degree from Universidade Paulista — UNIP, completed in 2026. |
| **Professional Research Experience** | Economic data, automation and reporting work at FIPE from June 2024 to December 2025. |
| **End-to-End Product Portfolio** | Public projects spanning full-stack analytics, streaming systems, AI integrations, backend design and desktop software. |
| **Nationwide Data Coverage** | Reproducible IBGE pipeline with validation for all 27 Brazilian federative units. |
| **Engineering Quality Practices** | Portfolio implementations include CI, automated tests, domain validation, architecture documentation and explicit operational limits. |

</div>

---

## GitHub Analytics

<div align="center">

<a href="https://github.com/MauricioTaguchi">
  <img width="49%" src="https://github-stats-extended.vercel.app/api?username=MauricioTaguchi&amp;show_icons=true&amp;hide_rank=true&amp;hide_border=true&amp;bg_color=0D1117&amp;title_color=A78BFA&amp;text_color=C9D1D9&amp;icon_color=818CF8&amp;border_radius=12" alt="Maurício Taguchi's GitHub statistics" />
</a>
<a href="https://github.com/MauricioTaguchi?tab=overview">
  <img width="49%" src="https://streak-stats.demolab.com?user=MauricioTaguchi&amp;hide_border=true&amp;background=0D1117&amp;stroke=312E81&amp;ring=8B5CF6&amp;fire=A78BFA&amp;currStreakNum=E0E7FF&amp;sideNums=E0E7FF&amp;currStreakLabel=A78BFA&amp;sideLabels=818CF8&amp;dates=94A3B8&amp;border_radius=12" alt="Maurício Taguchi's GitHub contribution streak" />
</a>

<br />
<br />

<a href="https://github.com/MauricioTaguchi?tab=repositories">
  <img width="58%" src="https://github-stats-extended.vercel.app/api/top-langs/?username=MauricioTaguchi&amp;layout=compact&amp;langs_count=8&amp;hide_border=true&amp;bg_color=0D1117&amp;title_color=A78BFA&amp;text_color=C9D1D9&amp;border_radius=12" alt="Language distribution across Maurício Taguchi's public repositories" />
</a>

<br />

<sub>Language statistics reflect repository code composition, not proficiency. Widgets depend on their providers and GitHub API availability.</sub>

</div>

---

## GitHub Trophies

<div align="center">

<a href="https://github.com/MauricioTaguchi">
  <img width="100%" src="https://github-profile-trophy-unserori.vercel.app/?username=MauricioTaguchi&amp;theme=discord&amp;no-frame=true&amp;no-bg=true&amp;column=4&amp;margin-w=12&amp;margin-h=12" alt="Automatically generated GitHub activity trophies for Maurício Taguchi" />
</a>

</div>

---

## Contribution Activity

<div align="center">

<a href="https://github.com/MauricioTaguchi?tab=overview">
  <img width="100%" src="https://raw.githubusercontent.com/MauricioTaguchi/MauricioTaguchi/main/assets/activity-graph.svg" alt="Maurício Taguchi's recent GitHub contribution activity" />
</a>

</div>

---

## Connect

<div align="center">

For data and BI opportunities, contact me by email or LinkedIn.

<br />

[![Gmail](https://img.shields.io/badge/Gmail-6D28D9?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mauricioryotoitataguchi@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-4338CA?style=for-the-badge&logoColor=white)](https://www.linkedin.com/in/mauriciotaguchi/)
[![GitHub](https://img.shields.io/badge/GitHub-7C3AED?style=for-the-badge&logo=github&logoColor=white)](https://github.com/MauricioTaguchi)
[![Portfolio](https://img.shields.io/badge/Portfolio-312E81?style=for-the-badge&logo=github&logoColor=white)](https://mauriciotaguchi.com.br/)

[Case studies](https://mauriciotaguchi.com.br/case-studies/) · [Technical blog](https://mauriciotaguchi.com.br/blog/)

</div>

---

<div align="center">

<a href="https://github.com/MauricioTaguchi">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&amp;color=0:4338CA,50:6D28D9,100:312E81&amp;height=120&amp;section=footer" alt="Purple and indigo wave footer" />
</a>

</div>
