# Awesome-Online-Form-Builder-Lead-Capture

## Top Online Form Builder & Lead Capture Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Conversational Forms, Lead Capture & Self-Hosted Form Infrastructure*  

**Last updated: November 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Online Form Builder & Lead Capture**. These tools enable marketers, founders, and teams to create forms, surveys, and lead-capture flows—embedding them anywhere, collecting responses, and routing data to CRMs, email tools, and webhooks without writing code.



**Examples** include HubSpot Forms Builder, Typeform, Jotform, Google Forms, Formstack, Paperform, Wufoo, 123FormBuilder, SurveySparrow, and Tally (the category leaders).



**Open-source emphasis**: Form Builder & Lead Capture is a domain where open-source tooling has **genuinely matured and now offers production-ready alternatives to commercial platforms**. **OpnForm** is the strongest all-around Typeform alternative—AGPLv3 licensed, with unlimited forms and submissions, form logic, file uploads, Slack/Discord notifications, webhooks, an MCP server for AI agents, and active development (3.8k+ GitHub stars, releases through September 2026) . **HeyForm** is the closest match to Typeform's conversational style—one-question-at-a-time flows, custom themes, drop-off analytics, and AGPL-3.0 licensing across the entire repository (9k+ stars, v3.0.3 September 2026) . **Formbricks** leads on community health (96/100, 13k+ stars, 526 commits in 90 days) and targets in-app and website surveys with user-group targeting, though SSO, teams, and audit logs require an Enterprise license . **Endatix** provides a developer-first, MIT-licensed alternative built on SurveyJS for .NET teams wanting a form management backend. The critical caveat: **open-core projects gate collaboration features**—OpnForm's self-hosted free tier limits OIDC to 2 users , and Formbricks reserves SSO and teams for Enterprise —so evaluate licensing against your team size before committing.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[HubSpot Forms Builder](https://www.hubspot.com/)**  

  Native form builder within HubSpot's Marketing Hub; creates lead-capture forms that sync directly to CRM contacts, with progressive profiling and automated follow-up workflows.



- **[Typeform](https://www.typeform.com/)**  

  The benchmark for conversational, one-question-at-a-time forms; known for engaging UX, conditional logic, and integrations with CRMs and marketing tools.



- **[Jotform](https://www.jotform.com/)**  

  Comprehensive form builder with 10,000+ templates, payment processing, file uploads, and conditional logic; free tier available with paid plans for higher volumes.



- **[Google Forms](https://forms.google.com/)**  

  Free form builder within Google Workspace; unlimited forms and questions, real-time response analysis, Google Sheets integration, and collaborative editing.



- **[Formstack](https://www.formstack.com/)**  

  Enterprise form and workflow platform with document generation, e-signatures, and approval workflows; drag-and-drop forms with 118+ integrations.



- **[Paperform](https://paperform.co/)**  

  Form builder emphasizing design flexibility and "human-first" forms; AI form creation from PDFs/images and 400+ integrations.



- **[Wufoo](https://www.wufoo.com/)**  

  Established form builder (part of SurveyMonkey) with drag-and-drop interface, payment integration, and reporting.



- **[123FormBuilder](https://www.123formbuilder.com/)**  

  Form builder with templates for surveys, orders, and registrations; positioned for ease of use.



- **[SurveySparrow](https://surveysparrow.com/)**  

  Survey and form platform with conversational UI, NPS tracking, and feedback management.



- **[Tally](https://tally.so/)**  

  Free-first form builder with unlimited forms and responses on the free tier; conditional logic, payment collection, and a clean editor.



## Open-Source GitHub Projects



### All-in-One Form Builders (Typeform Alternatives)



- **[OpnForm](https://github.com/opnform/opnform)**  

  The **most complete open-source Typeform alternative** for everyday web forms (AGPL-3.0 core with a small enterprise directory) . Features: **unlimited forms and submissions**; rich field types (text, date, URL, phone, email, checkboxes, select, multi-select, number, star-ratings, file uploads) ; **form logic**; **embed anywhere**; email notifications for owners and respondents; hidden fields and form passwords; URL pre-fill; **Slack and Discord notifications**; webhooks; captcha protection; form closing dates; submission limits; analytics; and an **MCP server for AI agents** . Self-hosting: Laravel/PHP + Vue, requires MySQL/PostgreSQL, Node.js for assets, and S3-compatible storage for file uploads . **Critical caveat**: the free self-hosted instance limits OIDC to **2 users**; more users require a license . **Best for teams wanting a feature-complete, self-hosted form builder** with unlimited forms—but verify the user limit against your team size.



- **[HeyForm](https://github.com/heyform/heyform)**  

  The **closest open-source match to Typeform's conversational style** (AGPL-3.0 across the entire repository, no enterprise directory) . Features: **conversational one-question-at-a-time forms** for surveys, quizzes, and polls; **conditional logic and redirects**; custom themes and CSS; **drop-off analytics**; webhooks; and self-hosting documentation with one-click deploy templates and OpenID Connect setup . Active development with v3.0.3 published September 2026 . **Caveat**: a small team ("the passionate duo behind HeyForm") that steers users toward the hosted service —self-hosting is supported but the team is tiny . **Best for teams wanting Typeform-style conversational forms** with full AGPL-3.0 freedom and no enterprise gates.



- **[Formbricks](https://github.com/formbricks/formbricks)**  

  The **healthiest open-source survey and experience management platform** (96/100 Repoly health score, 13k+ GitHub stars, 526 commits in 90 days, release 6.1.1) . Features: **link surveys, website surveys, in-app surveys, and email surveys**; drag-and-drop editor; **targeting by user group without code changes**; response collection and analysis; contact and segment management . Self-hostable with Docker without a subscription . **Critical open-core caveat**: SSO, teams, role management, audit logs, white-labelling, and workflows are in the `ee` directory and require a **paid Enterprise license in production** ; usage telemetry is sent to Formbricks unless disabled . **Best for product teams wanting in-app and website surveys** with a large community—but budget for Enterprise if you need SSO or team management.



- **[Endatix](https://github.com/endatix/endatix)**  

  A **developer-first, MIT-licensed form management system** built on the industry-leading **SurveyJS** form builder library . Positioned as a self-hosted alternative to Typeform, Formstack, Alchemer, and Qualtrics for .NET Core applications . Features: **form definitions powered by SurveyJS JSON** (complex validation rules and logic) ; submission storage and processing; RESTful API; event system for workflow automation; **storage-agnostic design** ; and native .NET Core integration . Deployable via NuGet package or Docker . **Best for .NET teams** wanting to embed form management into their applications—but it requires developer involvement rather than being a no-code end-user tool .



### WordPress-Integrated Form Builders



- **[Libre Form](https://github.com/libreform/libreform)**  

  Open-source WordPress form plugin (v2.0, GPL) that takes a **"WYSIWYG" approach**—you write plain HTML5 forms and the plugin handles submissions, validation, and storage . Features: **forms are plain HTML** (copy any valid form from a website and it works) ; submissions saved to **per-form database tables** ; AJAX submission with traditional fallback; HTML5 `required` validation; file uploads to Media Library; email notifications; multilingual support (Polylang); importable HTML templates; selector system (`## USER_EMAIL ##`, `## SUBMISSION ##`, `## FORM ##`) ; and a JavaScript API in TypeScript . **Best for developers** wanting complete control over form markup without a clunky builder—**not a no-code tool**, and requires MariaDB (MySQL compatibility removed) .



- **[Rollout Forms](https://wordpress.org/plugins/rolloutemail/)**  

  Lightweight **contact and lead collection form builder** for WordPress (open-source) . Features: multi-column forms, leads stored in your WordPress database, immediate notifications to team and subscribers, and **optional sync to RolloutEmail** SaaS (only when explicitly configured with an API key) . **100% offline-capable by default**—no external service required unless you opt in . **Best for WordPress sites** wanting a simple lead-capture form with no SaaS dependency—lighter than Libre Form but less flexible.



### Additional Strong Open-Source Options



- **[GopherCRM](https://github.com/florinel-chis/GopherCRM)** — Open-source, self-hosted **CRM with lead-capture forms** (Go + React, SQLite/MySQL) ; includes leads, deals, tickets, and tasks alongside form capture . **Best for teams wanting a CRM with built-in lead forms**—but the form builder is basic compared to dedicated tools .

- **OpenFlow** — Open-source **lead-gen form platform** positioned as a Typeform alternative for startups and SMEs; features form embedding with iframe postMessage, per-form subdomains with wildcard TLS, and integrations with self-hosted tools like lodgely (lead intake hub) and calon (booking engine) . **Best for teams wanting a self-hosted lead-gen platform with integrations**—but it is newer and less community-validated than OpnForm or HeyForm .



**Frameworks for building custom systems**: For **everyday web forms with unlimited submissions and AI-agent support**, OpnForm is the most complete open-source option (verify the 2-user OIDC limit) . For **conversational Typeform-style forms with full AGPL-3.0 freedom**, HeyForm . For **in-app and website surveys with a large community**, Formbricks (budget for Enterprise SSO) . For **.NET teams wanting SurveyJS-powered form management**, Endatix . For **WordPress with full HTML control**, Libre Form . No open-source project matches HubSpot Forms' **native CRM integration** or Typeform's **polished mobile experience**—those are commercial advantages tied to their broader platforms.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Form builder platforms handling lead data and submissions must comply with applicable privacy regulations (GDPR, CCPA) and implement proper consent mechanisms; **self-hosted solutions place full responsibility for data security, backups, and uptime on the operator**.

- **Open-source form builders are mature but open-core gating varies**—OpnForm limits free self-hosted OIDC to 2 users , and Formbricks reserves SSO, teams, and audit logs for Enterprise . **HeyForm is the only major option with AGPL-3.0 across the entire repository** (no enterprise directory) . Choose based on whether you need unlimited users (HeyForm) or can accept limits (OpnForm, Formbricks).

- Verify license terms for commercial use; OpnForm uses AGPL-3.0 for core with enterprise features under a separate license , HeyForm uses AGPL-3.0 , and Formbricks uses AGPL-3.0 for core with Enterprise features in the `ee` directory .



---



**Made for marketers, founders, and teams choosing their form and lead-capture stack.**  

Let's make form building and lead capture more open, but with clear eyes about the open-core user limits that define the real cost of self-hosting.
