# Head of AI (Engineering dept; reports to CTO; leads AI team of 3-4 engineers; "hands-on leadership role, not a management layer"; path to VP of AI) — Maze (trading name; mazehq.com) — London-based AI vulnerability-management startup founded 2024 by Harry Wetherald (CEO) and Adrian Jozwik. Exact UK Ltd name not confirmed via Companies House (note: "MAZE SECURITY LIMITED" 06939441, Kent, 2009, is an unrelated company). NOT Maze the user-research SaaS (maze.co) that the scout report described.

- Verified: 2026-08-21 · live: **live** · private sector: **confirmed** · decision: **hand_to_phil**
- Why: Live, direct private employer, £180k-£250k + equity, fully remote (Europe), Ashby form with no login — on paper a proceed. But (a) the form requires a resume file upload plus LinkedIn, start date and visa answers only Phil can supply; (b) the scout's fit analysis was for the wrong company, so the pitch must be rebuilt around agent-eval frameworks (his RL eval-environment design + Albie in production + founder signal) rather than the discarded cover note; and (c) Phil needs to judge honestly whether he can pass a direct test on transformer internals/LoRA fine-tuning and whether the 'security background strongly preferred' gap is worth the effort. Strong upside if he wants to take the shot; not something to spend application effort on without his call.
- Pay (as listed): £180,000 – £250,000 per year base + 0.2% – 0.5% equity (stated identically on Wellfound JSON-LD baseSalary and Ashby compensationTiers). Scout report said "Unstated" — wrong; this is well above the £80k floor.
- Location/remote: Ashby (employer source): "Remote (Europe)", workplaceType Remote. Wellfound copy: "Remote (Everywhere) / Hires remotely in Everywhere"; "Visa Sponsorship Not Available"; "Relocation Not Allowed". Team described as "remote-first, English-speaking". No onsite days stated. UK-based candidate (Derry) fits the Europe remote scope.
- Type: permanent · posted/updated: Ashby publishedAt 2026-07-02; Wellfound datePosted 2026-07-10 ("Posted: 1 month ago" as of 2026-08-21). Still listed on both.
- End client: Direct employer (not a recruiter ad). Hiring contact on Wellfound: Harry Wetherald, Co-Founder & CEO, London.
- Apply: https://jobs.ashbyhq.com/mazehq/a2d62030-f2da-4ab2-8459-04e33137940c/application (Ashby; account required: no)
- Contact email printed in listing: none
- Red flags: 1) Scout misidentified the employer: this is Maze the cybersecurity/vuln-management startup (mazehq.com), not Maze the user-research SaaS; the drafted cover note and the 'non-PhD path' framing are based on the wrong company and must be discarded. 2) Hard technical bar: 'You can explain transformer architecture, training, fine-tuning (e.g. LoRA), and inference from first principles. We test this directly' — and the 60-day milestone is fine-tuning a model into production; classical/ML-engineering depth is not on Phil's CV. 3) Security background 'Strongly preferred. Every candidate we've rated highly has had it.' 4) 'Top-tier pedigree' at a leading AI org or strong AI-native startup expected. 5) Role explicitly 'Not For: Fractional, advisory, or part-time profiles' — full-time permanent only, against Phil's contract/fractional preference. 6) Required CV/resume file upload and LinkedIn URL — cannot be submitted without Phil. 7) Minor: Wellfound says 'Remote (Everywhere)' but employer's Ashby says 'Remote (Europe)'; no visa sponsorship (irrelevant for UK candidate).
- Liveness evidence: Fetched today (2026-08-21): https://wellfound.com/jobs/4452741-head-of-ai returned HTTP 200 with full JobPosting JSON-LD (datePosted 2026-07-10, directApply true, page shows "Apply Now", "Posted: 1 month ago", "Actively Hiring"). Employer's own Ashby board https://api.ashbyhq.com/posting-api/job-board/mazehq lists "Head of AI" (id a2d62030-f2da-4ab2-8459-04e33137940c), isListed true, publishedAt 2026-07-02, and the Ashby GraphQL job-posting endpoint returned the live application form.
- Private-sector evidence: VC-backed private startup: $6M seed led by Cherry Ventures, $25M Series A led by Theory Ventures with Tapestry VC (Jun 2025; total $31M). Listing itself says "a well-funded Series A (Theory Ventures) behind us, and a Series B on the horizon". Customers are enterprises (incl. two Fortune 200). No state, academic or Gulf ownership found.

## Form fields
- First Name (required) — text
- Last Name (required) — text
- Preference (optional) — text; helper: "How do you pronounce your name? Which pronouns would you like us to use when referring to you?"
- Email (required) — email
- Resume (required) — file upload; helper: "Feel free to upload a PDF of your Linkedin if you don't have a resume written up"
- Location (required) — location picker
- Linkedin (required) — URL
- Portfolio / Github / Publications (optional) — URL
- When is the earliest you would want to start? (required) — date
- Will you now or in the future require visa sponsorship for employment? (required) — yes/no
- Is there anything you would like the Maze team know about you? (optional) — free text

## Custom questions
- When is the earliest you would want to start?
- Will you now or in the future require visa sponsorship for employment?
- Is there anything you would like the Maze team know about you?
- Preference: How do you pronounce your name? Which pronouns would you like us to use when referring to you?

## Cover note (147 words · fact-check: fixed)

Maze's stated core problem is evaluating non-deterministic, multi-step agents running across 180-plus tools against a ground-truth exploit lab. That is the capability I bring. I designed RL evaluation environments for a HUD.ai vendor proposal: rubric-graded, mutation-tested eval tasks built to catch agents that pass by accident rather than by competence. I also built and operate Albie, a 24/7 autonomous multi-channel operator on the Claude Agent SDK that runs my company's inbox, Apollo campaigns, proposals, coding and scheduled tasks in production with persistent memory. Founder signal is unambiguous: Blue Canvas AI has six live client engagements and a measurable P&L result, The Wall Group's net profit up 17% year on year from AI workflow integration. Before that, 18 years of commercial and deep-tech leadership, including building a global team of eight at Skipshift. Based in Derry, Northern Ireland; fully remote, UK right to work, available within four weeks.

Fact-check notes:
- Cover note: 'I designed RL evaluation environments for HUD.ai' implies a delivered engagement; allowed fact is a HUD.ai vendor proposal. Reworded to 'for a HUD.ai vendor proposal'.
- Cover note: 'The Wall Group's net profit up 17% year on year from agent workflow integration' — allowed fact says 'AI workflow integration'. Restored exact wording.
- Cover note: 'Maze's stated hardest problem' — listing says 'core problem of the role' / 'the one we most want'; 'hardest' is not stated. Changed to 'stated core problem'.
- Screening 'Why this company': claimed the full 90-day plan 'reads as a description of work I already do', but the day-60 milestone is fine-tuning a small model into production, which is not in Phil's allowed facts (he has no model-training evidence). Narrowed the claim to the days 61-90 evaluation-scaling goal only.
- Screening 'Is there anything you would like the Maze team know': same 'for HUD.ai' inflation as the cover note; reworded to 'for a HUD.ai vendor proposal'.
- Word count: original 144, fixed 147 (within 100-150). No banned openers, no exclamation marks, no 'passion', British spelling, employer-specific hook present (180+ tools, ground-truth exploit lab, founder signal), salary within band and above floor, notice period and start date flagged ASSUMPTION, unanswerable items flagged NEEDS PHIL, email_body correctly empty since no contact email printed.

## Screening answers

- **Years of experience** — 18 years of commercial and deep-tech leadership (Commercial Director, BD Director, NED, Senior Fund Manager); hands-on agentic-AI production delivery since March 2025 (around 18 months), building and operating production agent systems on the Claude Agent SDK.
- **Notice period / availability** — No notice period: I run my own company. I can start within 2-4 weeks to hand over live client work.  _[ASSUMPTION: founder with no employer notice period; 2-4 week handover window inferred from pack defaults, not confirmed by Phil.]_
- **Salary expectation** — Within the advertised band: targeting £215,000-£250,000 base, plus equity within the stated 0.2%-0.5% range.  _[ASSUMPTION: upper half of the listing's £180k-£250k band per pack defaults; Phil to confirm the exact figure.]_
- **Right to work** — Yes. Full right to work in the UK and Ireland. No sponsorship required now or in the future.
- **Why this company** — Maze has named the problem I want to work on: evaluating non-deterministic multi-step agents against ground truth, at production scale, for paying enterprise customers. I have designed rubric-graded, mutation-tested RL eval environments and I run an autonomous agent system in production daily, so the days 61-90 goal of scaling the evaluation approach describes work I already do rather than an aspiration.
- **When is the earliest you would want to start? (required, date field)** — 2026-09-18 (four weeks from application date, to hand over client work). Could be brought forward to 2026-09-04 if needed.  _[ASSUMPTION: derived from the 2-4 week default; NEEDS PHIL: confirm the actual date before submission.]_
- **Will you now or in the future require visa sponsorship for employment? (required)** — No.
- **Is there anything you would like the Maze team know about you? (optional, free text)** — Two things. First, the eval work: I designed RL evaluation environments for a HUD.ai vendor proposal, built around rubric grading and mutation testing, specifically to distinguish agents that solve a task from agents that happen to pass it. That is the same failure mode you face scoring multi-step trajectories against an exploit lab. Second, the founder signal: Blue Canvas AI sells, scopes, builds and runs production agent systems for six live clients, and the business itself runs on Albie, a 24/7 autonomous operator I built on the Claude Agent SDK. I have not worked in security; I have shipped agents that paying businesses depend on.
- **Preference: How do you pronounce your name? Which pronouns would you like us to use when referring to you? (optional)** — Phil Patterson, pronounced as written. Pronouns: leave for Phil to state or leave blank.  _[NEEDS PHIL: personal preference; do not fill in pronouns on his behalf.]_
- **First Name / Last Name (required)** — Phil / Patterson
- **Email (required)** — philpatterson85@gmail.com
- **Location (required, location picker)** — Derry/Londonderry, Northern Ireland, United Kingdom (within the Remote (Europe) scope stated on Ashby).
- **LinkedIn (required, URL)** — https://www.linkedin.com/in/philpatterson1
- **Resume (required, file upload)** — Upload Phil's current CV PDF. Ashby helper text permits a PDF export of the LinkedIn profile if no CV file is to hand.  _[NEEDS PHIL: file upload; only Phil can attach and approve the CV version.]_
- **Portfolio / Github / Publications (optional, URL)** — Leave blank unless Phil supplies a link.  _[NEEDS PHIL: no portfolio or GitHub link beyond LinkedIn is in the allowed facts.]_
- **How did you hear about us? (not on form; for reference)** — Wellfound job board listing, applied via the Ashby board.

## Probe line

The direct first-principles test on transformer architecture, training, LoRA fine-tuning and inference, with the day-60 milestone being a fine-tuned model shipped to production: Phil's evidence is agent orchestration and eval design, not model training, and he has no security background, which the listing says every highly rated candidate has had.

