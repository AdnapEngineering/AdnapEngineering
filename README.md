### Hi, I'm Justin 👋

I'm a full-stack engineer who likes working on growth: signup, onboarding, activation, and the experiments that show whether a change helped. Before I joined BILL's engineering team I ran customer support operations at Invoice2go, so I've seen firsthand where users get stuck. For four years at BILL I shipped fintech SaaS in React and TypeScript, with backend work in its Java, GraphQL and DynamoDB services.

**Stack:** TypeScript · React · Angular · GraphQL · Java · Node · Python · PostgreSQL · DynamoDB · AWS · Jest · Playwright<br>
**Growth tooling:** LaunchDarkly · Mixpanel · Segment · Datadog RUM

### Projects

[**job-search-pipeline**](https://github.com/AdnapEngineering/job-search-pipeline): I built my own job search as a funnel. It pulls postings from ATS feeds, LinkedIn, Indeed, Remote OK, Jobicy and HN "Who is hiring?", enriches them through each ATS's JSON API, scores them deterministically, then has an LLM grade the best ones against a 12-point rubric. The LLM has to quote the job description word for word to back its score, and Python checks the quote, so a hallucinated match can't make the cut. Matches go to Notion (or a plain `.txt` file) with an ntfy push. Every career-specific rule lives in `config.json`, so it works for any field, and the review step runs on Claude Code, Codex or agy. Python, cron, idempotent re-runs.

[**astro-baby-item-recalls**](https://github.com/AdnapEngineering/astro-baby-item-recalls) ([live site](https://adnapengineering.github.io/astro-baby-item-recalls/)): a small public-service site built with [Astro](https://astro.build) that tracks children's product recalls from the U.S. Consumer Product Safety Commission (CPSC), with search, hazard browsing and a detail page for each recall. A daily GitHub Actions job pulls from the CPSC API into Turso and rebuilds the static site, retrying the API's fake "200 OK" outages so a bad fetch never publishes half the data. Astro, React, TypeScript, Drizzle, Zod, Playwright + axe accessibility checks (WCAG 2.2 AA).

[**resume-tailor**](https://github.com/AdnapEngineering/resume-tailor): agent skills for Claude Code that tailor a LaTeX resume to a job posting without overclaiming. Every claim traces to an evidence bank with attribution ceilings, and a Python gate compiles the PDF and checks page count, the ATS text layer, keywords and scope before a variant ships.

[**expo-taskflow**](https://github.com/AdnapEngineering/expo-taskflow): a small Expo (React Native) task app for iOS, Android and web, with Expo Router, expo-sqlite on native and localStorage on web, swipe gestures and light/dark theming.

### Elsewhere

I'm open to **senior full-stack** roles, especially on **growth and product** teams, US-remote.

[LinkedIn](https://www.linkedin.com/in/justin-karcher/)
