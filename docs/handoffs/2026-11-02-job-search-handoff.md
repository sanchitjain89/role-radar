This handoff comes from an earlier conversation. Read it and the linked topic notes as context for continuing the work.

# RoleRadar: job-search research handoff

Preserved November 2, 2026, using the user's Asia/Calcutta date. This is a curated handoff, not a verbatim transcript. It retains conclusions, corrections, examples, sources, and unfinished decisions without repeating the conversation.

## Goal and current scope

Sanchit Jain wants to understand and use practical automation for finding jobs relevant to his experience. He initially requested a broad survey of discovery, matching, alerts, tracking, tailoring, and application automation after seeing social-media demonstrations. The latest substantive request deliberately narrowed the task to **discovering and identifying relevant openings only**.

Current search constraints:

- Backend engineer with 10+ years in Java/Spring, REST APIs, microservices, distributed systems, migrations, and production reliability.
- Currently out of work. There is some urgency, but no deadline or study-time commitment was supplied.
- **Remote work that can be performed while based in Delhi, India.** This is the user's explicit correction and supersedes any broader or ambiguous location assumptions. It is not an instruction to include Delhi office/hybrid roles.
- **Free options only, with no required paid subscription or paid API**, for the current discovery workflow.
- Has used Claude Code and Glean agents for engineering workflows. Has not independently built and operated an LLM application; AI course plans are not production qualifications.
- Start searching with existing tools while learning separately. Building a portal or learning project is not a prerequisite.

The original preservation task authorized documentation and creation of the named local repository, while leaving committing and pushing to the user. In a subsequent follow-up, the user supplied the newly created GitHub repository and requested SSH communication; the follow-up transfers these preserved documents to that repository. This does not authorize continuing the research, installing/running job-search projects, creating alerts or schedules, applying, or contacting anyone.

## Read next

1. [Free job discovery](../notes/free-job-discovery.md) for the active topic and the most recent recommendation.
2. [Background and AI experience](../notes/background-and-ai-experience.md) for the factual profile, distinctions about experience, and the preserved small-build example.
3. [Earlier automation research](../notes/automation-research-archive.md) only if the user reopens the broader topic.
4. [Original evidence appendix](../research/2026-11-01-github-evidence.txt) for exact inspected revisions, code paths, issues, and historical product sources.

## Conclusions and decision status

| Status | Conclusion / decision | Reason |
|---|---|---|
| User decision | Focus on discovery, with free tools and Delhi/India-compatible remote work. | The user explicitly narrowed the question and corrected the work preference. |
| User decision | Use existing tools while learning alongside the search. | Do not delay the search behind a course or a portal build. |
| Assistant recommendation; not yet configured or adopted | Start with LinkedIn and Naukri free searches/alerts, supplement with Wellfound. | Low setup effort, no mandatory paid API, and useful board coverage without maintaining scrapers. |
| Assistant correction | Simplify Copilot and its tracker were premature recommendations for the discovery-only step. | Those chiefly help after finding an opening. Simplify Job Matches is the separate discovery feature; superiority for India-eligible backend roles was not established. |
| Assistant recommendation; not an installation decision | JobSentinel is the closest reviewed GitHub candidate to a ready-made Windows discovery app; JobSpy is the useful programmable discovery component. | JobSentinel implements search/scoring/notification workflows; JobSpy needs a small script and additional work for recurring checks or alerts. Neither has proven complete India coverage. |
| Evidence boundary | Code, official docs, and marketing claims are different evidence levels. | Implemented adapters and closed issues do not establish live reliability or hiring outcomes. |
| Assistant recommendation | Prioritize senior Java/backend roles; consider selective staff roles and backend roles on AI teams. | These draw on established backend experience. Applied AI roles are selective stretch opportunities, not a new proven specialty. |
| User decision | Name the new project RoleRadar, folder `role-radar`. | User approved the suggested name and creation after the initial chat was found to be projectless. |

## Completed work

- The earlier research read the resume and relevant AI journal material, then examined official product documentation and GitHub repositories beyond their READMEs.
- The saved November 1 appendix records ten application/workflow implementations plus the historical AIHawk redirect; search coverage was broad but not an exhaustive inventory of GitHub.
- Sources, commits, issues, licensing, setup needs, costs, and limits were compared. None of those repositories was installed or executed as part of this research.
- The focused follow-up reused that audit and checked material gaps in native alerts, free access, remote eligibility, Simplify matching, and public employer feeds.
- The conversation explained production LLM experience, honest levels of evidence, and a hypothetical small job-fit checker. Those explanations are preserved separately and are outside the current active scope.
- The preservation pass reviewed the chat history, reused the existing source appendix, and organized these documents. It also read the separate AI journal's latest progress entry; that source now records a guided first model call, not independent production experience.

## Unfinished work and unresolved questions

No job-search tool has been selected conclusively, configured, installed, or tested for this user. No live vacancy shortlist, employer list, alert set, matching benchmark, or comparison of actual India-eligible result counts exists.

Open decisions, only if needed for the next requested step:

- Whether to start with the proposed native-board searches or evaluate a GitHub tool.
- Exact mix of senior, lead, and selective staff individual-contributor roles; acceptable employers or industries if the user wants narrower targeting.
- Compensation floor, employment versus contracting preferences, acceptable time-zone overlap, and any eligibility/sponsorship details needed for a particular posting. Do not infer these from Delhi residence.
- Remote eligibility on individual postings. A remote label alone does not establish permission to work from India.
- Actual operating system and resources on the other laptop if a tool evaluation is later requested. Windows advice in this research comes from the original machine.
- The user subsequently selected GitHub repository `sanchitjain89/role-radar` and required SSH: `git@github.com:sanchitjain89/role-radar.git`. Repository visibility was not changed by this work. Future substantive changes still need to follow the user's requested scope.

No budget or study-time questions are needed to continue the current free discovery discussion. Do not reopen the broad survey by default.

## Proposed next steps, not executed

1. Resume with the discovery note, acknowledge the current scope, and answer the user's next specific question.
2. If asked to proceed with discovery setup, use separate senior-backend Java/Spring, senior-software-engineer Java/microservices, and selective lead/staff backend/platform searches. Use India-wide remote filters while retaining Delhi as the actual residence.
3. Evaluate promising results against responsibilities and explicit country eligibility. Treat missing eligibility as unknown, rather than assuming acceptance or rejection.
4. Only consider JobSentinel or JobSpy if the user wants consolidation beyond native alerts. Recheck the selected version, connectors, platform restrictions, and free-service dependencies at that time.

## Communication preferences and corrections

The user supplied these response rules: answer the exact question, then stop; use yes/no when enough; default to 1-3 sentences for simple questions; use plain language and define necessary terms briefly; keep clarifications tied to the original goal; skip unsolicited background and repeated summaries; expand when requested or needed for correctness.

Other important constraints:

- Preserve demonstrated experience separately from learning aspirations; do not invent qualifications, employment end dates, salary expectations, or study hours.
- The user's report of being out of work supersedes any resume entry still saying "Present." The actual end date was not supplied and the resume was not edited here.
- GitHub stars were not used as the primary ranking criterion. Flag unverified functionality and coverage gaps.
- A free repository can still require paid services or significant local resources. A limited trial/free quota is not the same as an established ongoing free workflow.
- The user invoked Prompt Forge earlier and requested GPT-6.1 Sol with "Heavy," interpreted then as high reasoning. That was prompt refinement, not a standing request to delegate every task or to execute the generated prompts.
- The preservation request specifically asked for files only, with no document contents or completion message returned in chat.

## Files, portability, and commands

All internal document links are project-relative. The project has no application code, runtime dependencies, or service credentials. The original public-source audit was copied as evidence rather than reproducing its detailed records in every note.

External inputs on the original machine, **not bundled in this repository**:

| Input | Original machine-specific location | Continuing elsewhere |
|---|---|---|
| Resume | `C:\Users\sanchit.jain\Downloads\Resume_Sanchit_Jain.pdf` | Use the factual summary in the background note; ask for the current resume location only if detailed review is needed. |
| AI journal | `C:\Users\sanchit.jain\Documents\lab\learning-journal\ai\` | If checked out beside RoleRadar, repository-root-relative location is `../learning-journal/ai/`. `progress.md` is the current evidence source; `roadmap.md` is a plan, not completed experience. |
| Separate AI demo and evaluation repositories | `C:\Users\sanchit.jain\Documents\lab\ai-demos\` and `...\learning-demos\` | Optional sibling checkouts `../ai-demos/` and `../learning-demos/`; not needed for job discovery or reading the handoff. |
| Prompt Forge skill | `C:\Users\sanchit.jain\.agents\skills\prompt-forge\SKILL.md` | Optional machine-specific skill, not needed for continuing the research. Earlier it was found under the learning-journal skill directory. |
| Original chat workspace | `C:\Users\sanchit.jain\Documents\Codex\2026-11-01\research-what-is-currently-possible-for\` | Contains scratch research scripts and downloaded public source snapshots under `work/`. They are not runtime dependencies and were not copied. The useful evidence appendix is retained under `docs/research/`. |

The research scripts included `audit_github.py`, `read_sources.py`, `read_followups.py`, and `compile_evidence.py`. They fetched/read public text; no repository code was run. Their exact invocation commands are not required to continue from the source URLs and inspected revisions in the appendix, and no missing invocation has been reconstructed.

From the new repository root, useful read-only PowerShell commands are:

```powershell
Get-Content -LiteralPath 'docs/handoffs/2026-11-02-job-search-handoff.md'
Get-Content -LiteralPath 'docs/notes/free-job-discovery.md'
git status --short --branch
git remote -v
```

Local initialization used `git init --initial-branch=main`. The later GitHub follow-up uses `origin` at `git@github.com:sanchitjain89/role-radar.git`, with SSH explicitly requested by the user. Before preparing publication, an authenticated SSH `git ls-remote --symref` check succeeded and found no existing remote refs.

On another laptop with an authorized SSH key, clone with `git clone git@github.com:sanchitjain89/role-radar.git`, open the resulting folder in Codex, and read this handoff. If already cloned, inspect local changes before `git pull --ff-only`. Use `git log -1 --oneline`, `git status --short --branch`, and `git remote -v` for the current commit and transfer state rather than relying on the historical preservation snapshot.

## Verification record

The research was static inspection and official-document review only. No live integration tests, installer tests, application submissions, scheduled jobs, ranking-quality benchmark, or outcome measurements were performed. Some employer-role examples were only search-indexed and are explicitly not live vacancy recommendations.

Preservation verification results are recorded in [preservation verification](../research/preservation-verification.md). No new research, learning exercise, or job-search setup was performed during preservation.
