# Background and AI-experience clarifications

This preserves the earlier role-fit and learning discussion. **It is background, not the current task:** the user subsequently narrowed the work to free job discovery. No AI project was authorized or built in this chat.

## Factual profile and evidence limits

Sanchit Jain describes 10+ years of backend experience in Java/Spring, REST APIs, microservices, distributed systems, migrations and production reliability. He is currently out of work and wants remote work performable from Delhi, India.

The prior resume review identified payments/platform work at PayPal and Altimetrik/eBay, backend API ownership, migration work, production support, validation, retries and integration testing. It also identified Claude Code engineering workflows and Glean agents. These are resume-based evidence, not an independent employment verification.

The resume's “Present” entry conflicts with the user's later statement that he is out of work. The user statement controls the working context. The actual end date was not supplied, and the resume was not edited.

The user explicitly confirmed he has not independently built and operated an LLM application. AI-tool use and learning plans must not be presented as that experience. Conversely, his substantial backend reliability experience remains relevant; it should not be discounted because his LLM application work is early.

Original sources are external to this repository:

- Resume: original Windows path C:\Users\sanchit.jain\Downloads\Resume_Sanchit_Jain.pdf.
- AI journal: original Windows directory C:\Users\sanchit.jain\Documents\lab\learning-journal\ai.
- With sibling checkouts, the journal is at ../learning-journal/ai/ from the RoleRadar root. Read progress.md for evidence and roadmap.md for plans; they are not interchangeable.

## Role fit discussed

| Direction | Assessment, not a guarantee |
|---|---|
| Senior Java/backend engineering | Strongest immediate fit based on existing delivery and reliability experience. |
| Selective staff/backend/platform roles | Worth considering where architecture, ownership and cross-team scope match the user's actual experience. Tenure/title alone does not establish every employer's staff-level requirements. |
| Backend engineering on AI product teams | A plausible bridge using APIs, authentication, integrations, conversation infrastructure and production reliability. The team being “AI” does not automatically make the role an ML position. |
| Applied AI/LLM engineering | Selective stretch. Requirements for independent production Python, retrieval systems, model evaluation or serving go beyond the evidence established in this chat. |

The recommendation was to position the user as an experienced backend engineer expanding into applied AI. A course or personal project can broaden future options; neither should delay the existing job search.

Earlier employer descriptions were used only to illustrate differing requirements. They were not confirmed suitable vacancies, and some direct pages/feeds could not be verified. Exact links and access limits are in the [research appendix](../research/2026-11-01-github-evidence.txt).

## What “production LLM experience” means

Production LLM experience means building or operating software that uses a language model for real users or business work: connecting the model to an application, checking answer quality, handling failures, protecting data, and managing latency and cost. Training a model from scratch is not required. Production ML is broader and can include prediction or recommendation systems.

“Establish expertise” meant having evidence supporting a claim, not a judgment about the user's ability. Claude Code workflows and Glean agents count as practical AI-tooling experience; backend integrations around AI conversations also matter. They do not by themselves establish ownership of the underlying LLM application.

The conversation distinguished three levels:

| Level | Evidence it provides | Honest description, only after doing it |
|---|---|---|
| Working demonstration | Connect a model, provide inputs and obtain useful results. | “Built an LLM application prototype.” |
| Personal application used and maintained | Use it for real tasks, evaluate mistakes, handle failures and improve it over time. | “Built and maintained a personal LLM application,” with specific evidence and limits. |
| Professional production experience | Deliver and operate an application for an employer/client's real workflows, with responsibility for behavior. | Describe the actual professional responsibilities and scope held. |

A personal application can provide operational experience without becoming commercial experience or proving readiness for every AI engineering role.

The user's contribution would need to include implementing and explaining the model request, how evidence reaches the model, response validation, failure behavior, and why reviewed outputs are correct or wrong. Assistance with syntax or debugging is compatible with learning, but generated code and successful runs alone do not establish independent understanding. Keep an accurate record of assistance and decisions the learner can reproduce.

## The “small build” example

This was an optional explanation, not an implementation commitment.

**Input:** a factual experience profile, one job description, and the work rule “Delhi, remote.” Learning goals are recorded separately from demonstrated skills.

A hypothetical posting asks for Java/Spring, reliable APIs, production LLM integration and “remote” work. The suggested output was:

| Requirement | Assessment | Evidence / explanation |
|---|---|---|
| Java/Spring backend work | Supported match | Resume lists Java/Spring and substantial backend API experience. |
| API reliability | Supported match | eBay work includes validation, retries and integration tests; PayPal includes production support. |
| Building production LLM applications | Current gap | The user confirmed he has not done this independently. Claude Code and Glean work should be described separately. |
| Working remotely from Delhi | Unknown | “Remote” does not establish that the employer hires people working from India. |

The point is to help decide which openings deserve attention and which facts need checking. It is not a hiring prediction, an employer's ATS score, or a substitute for reviewing eligibility.

The smallest useful version was described as one local script that sends those inputs to a model and displays fixed fields: requirement, assessment, evidence and explanation. Outputs would be reviewed before use. No portal, multiple agents, or automatic submission is necessary.

The learning value would be model API calls, structured output validation (for example required JSON fields), separating facts from instructions/goals, catching invented claims, handling timeouts or malformed responses, and comparing judgments with the user's own labels on a small set of postings. This is preserved explanation; no implementation or additional provider recommendation was made during preservation.

## Journal evidence and the later snapshot

At the original research point, the journal documented prior AI systems study and a partially completed coding-agent evaluation harness. Three recorded case-1 passes under a string-based grader established an execution milestone, not a complete reliable suite or independent mastery. An auth-contract scaffold existed without a recorded run in the earlier inspection. RAG/chatbot study and an older mock were historical exposure, not a current readiness test.

During preservation on November 2, the separate journal's progress.md had been updated by other work. It now records a **guided successful first model call**, a learner-authored prompt change and rerun, a correct request/response explanation, and recognition that an incident note did not establish root cause. The journal explicitly says the assistant supplied the API code/setup and independent SDK implementation remains untested.

This is a newer external-source snapshot, not work performed by RoleRadar or a reason to upgrade the user to production LLM experience. The next learning capability was only suggested in the journal; no learning task was continued here. Consult that journal for later changes instead of treating this snapshot as permanent.

## Preferences retained

The user plans AI learning but supplied no ongoing study-time commitment or deadline in this conversation. He described some job-search urgency without quantifying it. Do not invent a daily schedule, a course completion date, or a tool budget. The current job-discovery requirement is free tools only.

The user agreed that searching should start with existing tools while learning happens alongside it. Building this checker remains optional and outside the active discovery-only scope.
