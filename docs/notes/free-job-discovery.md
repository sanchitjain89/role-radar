# Free discovery of relevant jobs

Scope: discovering and identifying openings only. This note preserves the November 1-2, 2026 research; nothing was installed, configured, or live-tested.

## Recommendation and search profile

The assistant recommended free LinkedIn and Naukri searches/alerts, supplemented by Wellfound. Native alerts already automate notification of new results without maintaining a custom program. This was a recommendation, not a tool choice the user had adopted.

The user has 10+ years of Java/Spring backend experience, REST APIs, microservices, distributed systems, migrations, and production reliability. The work rule is **remote work performable from Delhi, India**. Search India-wide remote openings while retaining Delhi as the actual residence. Restricting the posting location to Delhi alone can hide suitable India-wide roles.

Suggested separate searches:

- Senior Backend Engineer with Java/Spring.
- Senior Software Engineer with Java/microservices.
- Selective Lead or Staff Software Engineer with backend/platform responsibilities.

These are search concepts, not universal Boolean syntax. Judge responsibilities and ownership as well as titles. Do not require every experience keyword in one search. Check explicit India eligibility; a remote label alone does not imply worldwide hiring. Ambiguous eligibility remains unknown.

No compensation floor, working-hour preference, contracting preference, sponsorship status, or employer list has been supplied.

## Boards, career pages, and public feeds

| Option | Relevant coverage and automation | Setup and costs | Limitations and evidence |
|---|---|---|---|
| LinkedIn | Broad employer discovery; saved searches with daily/weekly email/app alerts; free profile-based recommendations. | Low effort, free account; Premium unnecessary for basic discovery. | Relevance, seniority and India eligibility need review. Official documentation, not an account-level trial. |
| Naukri | Additional India-focused hiring coverage; email alerts using keywords, location and experience. | Low effort; free alerts are separate from paid services. | Keyword noise remains. Official indexed help supported free alerts; one direct FAQ request returned 403. |
| Wellfound | Startup and technology openings; remote-only preferences and country eligibility information. | Low effort; candidate access is free. | Inspect “Hires Remotely From.” Official help warns that eligibility for some auto-posted jobs is unconfirmed. Email automation was not established in this review. |
| Employer career pages | Direct vacancies for selected employers; employer-provided alerts where offered. | Free public browsing; company-by-company setup. | Requires an employer list; alerts vary. No universal cross-company index. |
| Public employer feeds | Machine-readable published vacancies from Greenhouse, Lever and Ashby. | Public listing endpoints need no paid job-seeker API subscription. | Need company/board identifiers and software to fetch/filter results and generate alerts. Feeds are data sources, not finished personal search tools. |

Official sources:

- [LinkedIn alerts](https://www.linkedin.com/help/linkedin/answer/a511279/job-alerts-on-linkedin?lang=en) and [free recommendations](https://www.linkedin.com/help/linkedin/answer/a512279/).
- [Naukri free alerts](https://resume.naukri.com/frequently-asked-questions-faq/how-to-create-free-job-alerts/) and [setup guide](https://resume.naukri.com/guides/2021/07/29/step-by-step-guide-on-setting-up-job-alerts/).
- [Wellfound remote filters](https://help.wellfound.com/article/762-remote-job-search-filters) and [candidate access](https://wellfound.com/candidates/remote).
- [Greenhouse Job Board API](https://docs.greenhouse.io/job-board), [Lever Postings API](https://github.com/lever/postings-api), and [Ashby public postings API](https://developers.ashbyhq.com/docs/public-job-posting-api).

## GitHub options that actually concern discovery

The [original audit](../research/2026-11-01-github-evidence.txt) contains pinned source paths, commits, issues, licenses and caveats. **Code inspected means an implemented path exists, not that every connector currently works.** GitHub tools generally combine existing sources; they do not establish a unique, comprehensive database of vacancies.

| Project | Supported finding | Direct use versus setup | Free-use limitations |
|---|---|---|---|
| [JobSentinel](https://github.com/cboyd0319/JobSentinel), MIT | Code inspected for scheduled searches, scoring, duplicate handling, source registry and notifications. | Closest reviewed candidate to a ready-made Windows app. Installer documented; configure sources/preferences, normally without custom coding. | Core local discovery has no mandatory paid AI service. Computer must run for local checks. Naukri coverage not established; restricted sources require user interaction. India coverage and USD-specific salary assumptions need checking. |
| [JobSpy](https://github.com/speedyapply/JobSpy), MIT | Dispatcher and LinkedIn/Naukri adapters inspected; a Python library returns normalized job records. | Requires Python and a small calling script. Recurring checks, deduplication and alerts need a wrapper/configuration. | Basic path has no mandatory paid API. Optional proxies cost money; blocking can still make sources unusable. Not a complete resume-based relevance engine. |
| [HeadStart](https://github.com/davidcristian/HeadStart), SSPL v1 | Greenhouse adapter and filtering/deduplication/notification pipeline inspected. | Existing application, but several services to run/configure; heavier setup. | Local core discovery can avoid paid hosting/model services, but consumes resources and maintenance effort. India coverage and live reliability unverified. Source-available licensing differs from MIT. |
| [Jobsmith](https://github.com/TheDevRo/Jobsmith), AGPL-3.0 | Public-feed/board aggregation documented; discovery connectors were not inspected enough to verify the advertised breadth. | Windows setup uses Docker and source configuration. | A no-paid-AI path for public sources is documented, not independently run. More setup and less discovery-specific verification than the leading candidates. |
| [Reactive Resume](https://github.com/reactive-resume/reactive-resume), MIT | Discovery and scheduled execution exist in inspected code. | Search-provider configuration required. | Avoiding paid search APIs means extra infrastructure such as self-hosted SearXNG. Not a zero-configuration free discovery tool. |

Maintenance observed in the original audit:

- JobSpy: release 1.4.1 on October 23; inspected main October 27. Recent adapter repairs indicate maintenance and ongoing website breakage. [Google Jobs issue #284](https://github.com/speedyapply/JobSpy/issues/284) remained open.
- JobSentinel: public 2.9.5/default branch dated July 18; v3 was an open PR. October activity did not establish a newer stable release. Earlier Windows complaints were closed, not retested here.
- HeadStart: inspected default branch August 11; later push metadata did not prove a merged functional update.
- Jobsmith: inspected main October 9, newer than its September 23 release.
- Reactive Resume: main November 1, newer than release 6.0.9 on October 29. Main/release equivalence must not be assumed.

Other previously mentioned projects:

- [job-radar](https://github.com/anadivatsa/job-radar): code for Greenhouse/Lever collection, keyword scoring, seen-job storage and Telegram notifications exists. Requires source/profile configuration. Only two commits and no license found; not the preferred adoption baseline.
- [ApplyPilot](https://github.com/mrunalhatwar/ApplyPilot): includes discovery through JobSpy. The larger workflow is unnecessary for discovery alone.
- [n8n AI Job Search Agent](https://github.com/mnsair/AI-Job-Search-Agent): inspected workflow connects chat, OpenAI, SerpAPI and Sheets. An ongoing entirely free path was not established; no schedule trigger or license found.
- [Resume Matcher](https://github.com/srbhr/Resume-Matcher) and [Waddington's tracker](https://github.com/waddington/job-application-tracker): do not discover openings.

## Simplify correction

The earlier recommendation of Simplify Copilot and its tracker concerned application administration. It was premature for the discovery-only question.

**Simplify Job Matches** is the relevant discovery feature: profile/preference-based recommendations, advertised as free. Documented coverage includes India, but this does not establish individual remote eligibility. No actual result comparison established an advantage over LinkedIn/Naukri/Wellfound for this user. It remains optional.

Sources: [Job Matches](https://help.simplify.jobs/en/articles/2166608-use-your-job-matches), [free-feature statement](https://simplify.jobs/), and [regions](https://help.simplify.jobs/articles/6895855-supported-countries-and-regions).

## Reliability and next step

Board filters and keyword scores are approximate. Listings can be stale, duplicated, incomplete or region-restricted. Public listings and model explanations cannot establish employer intent or hiring probability.

Scraper availability does not establish permission: [LinkedIn restricts third-party scraping/automation](https://www.linkedin.com/help/linkedin/answer/a1340567/automated-activity-on-linkedin?lang=en), and [Indeed restricts unauthorized automated access](https://www.indeed.com/legal?hl=en_US). Native alerts avoid that scraper dependency. No bypass techniques were recommended.

The proposed simplest start is native board searches/alerts plus Wellfound and selected employer pages. JobSentinel is an optional app evaluation; JobSpy is an optional programmable component. Neither has been installed, selected conclusively, or tested here. There is no measured coverage or relevance benchmark yet.
