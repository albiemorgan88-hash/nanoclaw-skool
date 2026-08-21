# Forward Deployed Engineer (Greenhouse title; metadata: Employment Type = Permanent, Work Type = Remote + Travel; department Software Development) — Nearform (Nearform Ltd, Irish-headquartered private software/AI consultancy; UK entity would employ for this UK-based perm role)

- Verified: 2026-08-21 · live: **live** · private sector: **confirmed** · decision: **hand_to_phil**
- Why: Live, direct private-sector employer, Greenhouse form reachable with no account and all fields/options captured. But three things only Phil can decide: (a) whether to apply into a band that starts at £75k (select '£80,000 – £90,000' or higher, or 'Prefer to discuss') given his £80k floor; (b) whether he will commit to 'frequent' European client-site travel on the required screener; (c) whether he wants to sit a 1-hour live Python coding challenge for a role specified as 8+ years Senior Engineer with Kubernetes — a materially harder engineering bar than the scout's 5/5 fit implied. If he says yes to all three, the application can be submitted with CV + LinkedIn + cover note without any login.
- Pay (as listed): "Our salary range starts from £75,000 + bonus & benefits and will be discussed during the initial interview based on your experience." No upper bound stated — the scout's "£75,000–£95,000" ceiling does not appear anywhere in the listing. The application form's salary-expectation dropdown runs up to "£110,000 +". Benefits: annual company profit-share bonus, 25 days leave + public holidays, up to €1,250 (GBP equiv) remote-working allowance every 2 years, up to €1,000 training allowance, private healthcare, pension match up to 5%, income protection, death in service.
- Location/remote: "Full-time, permanent opportunity for candidates based in the UK." Remote + Travel: "requires some travel to client sites within Europe, with travel expenses covered" — the screening question words it as "frequent travel to work from client sites within Europe". Must be currently residing in the UK (screening question); sponsorship question asked. No fixed onsite days.
- Type: permanent · posted/updated: First published 2026-02-04; last updated 2026-08-11 (Greenhouse API)
- End client: Not applicable — direct employer posting on Nearform's own Greenhouse board, not a recruiter ad.
- Apply: https://job-boards.greenhouse.io/nearform/jobs/7619129003 (Greenhouse; account required: no)
- Contact email printed in listing: none
- Red flags: (1) Pay: stated range "starts from £75,000" — below the £80k floor at the bottom, and the scout's £95k ceiling is not in the listing; no upper bound given, so it is negotiable but unverified. (2) Fit gap vs scout's 5/5: this is a hands-on Senior Engineer role — "at least 8 years of commercial experience" at Senior Engineer level, Kubernetes configuration/deployment, LangGraph/CrewAI/AutoGen, and a 1-hour live Python coding assessment. Phil has no formal software-engineering employment history; the coding test is the real gate. (3) "Frequent" travel to European client sites is a required yes/no screening question despite remote framing. (4) Posting has been open since 4 Feb 2026 (6+ months, refreshed 11 Aug) — may be an evergreen/pipeline requisition rather than a single open seat. (5) Possible public-sector client exposure on specific engagements (private employer, so not excluded).
- Liveness evidence: Greenhouse public API https://boards-api.greenhouse.io/v1/boards/nearform/jobs/7619129003?questions=true returned HTTP 200 on 21 Aug 2026 with full content and an active question set; updated_at 2026-08-11T09:11:04-04:00, first_published 2026-02-04. Absolute URL https://job-boards.greenhouse.io/nearform/jobs/7619129003. Also fetched nearform.com/about (HTTP 200) for company facts.
- Private-sector evidence: Listing describes Nearform as "an independent team of data & AI experts, engineers, and designers" partnering with "ambitious enterprises"; named clients are all private (Lululemon, Puma, Sun Life, Starbucks, Travelex, Virgin Media O2, Walmart). Not state-owned, not academic, not Gulf-linked. Private consultancy per brief rule. Exposure note: Nearform also does some public-sector client work in UK/EU, and the listing says there may be an additional client interview depending on project, so a specific engagement could be public-sector facing.

## Form fields
- First Name (required) — text
- Last Name (required) — text
- Preferred First Name (optional) — text
- Email (required) — text
- Phone (required) — text
- Resume/CV (required) — file upload OR paste-as-text (resume_text textarea)
- Cover Letter (optional) — file upload OR paste-as-text (cover_letter_text textarea)
- LinkedIn Profile (required) — text
- Are you currently residing in the UK? (required) — single select: 'Yes, I am currently based in the UK' / 'No, I am not currently based in the UK'
- Do you now, or will you in the future, require sponsorship to work in the UK? (required) — single select: 'Yes, I require sponsorship to work in the UK' / 'No, I do not require sponsorship to work in the UK'
- Travel requirement (required) — single select: 'Yes, I am open/willing to do frequent travels within Europe' / 'No, I am not open/willing to do frequent travels within Europe'
- Salary range expectation (required) — single select: '£60,000 – £70,000' / '£70,000 – £80,000' / '£80,000 – £90,000' / '£90,000 – £100,000' / '£100,000 – £110,000' / '£110,000 +' / 'Prefer to discuss during the interview process'
- How did you hear about Nearform? (required) — text
- Data Privacy (required) — multi-select checkbox, single option 'Confirm'
- GDPR compliance block present but requires_consent = false (no extra consent checkboxes)

## Custom questions
- LinkedIn Profile
- Are you currently residing in the UK?
- Do you now, or will you in the future, require sponsorship to work in the UK?
- This role requires frequent travel to work from client sites within Europe, with travel costs covered by the company. Are you able and willing to meet this travel requirement?
- Please select the salary range that best aligns with your base salary expectations for this role:
- How did you hear about Nearform?
- Data Privacy

## Cover note (150 words · fact-check: fixed)

Since March 2025 I have been shipping autonomous agents into production for paying businesses through Blue Canvas AI, not running chatbot pilots. The core of that is Albie, a 24/7 multi-channel operator built on the Anthropic Claude Agent SDK: inbox, Apollo and Zoho campaigns, proposals, coding and scheduled tasks with persistent memory across WhatsApp, Telegram, Slack and Discord. My own company runs on it daily. Nearform's mandate to build, implement and deploy agentic platforms inside client environments, wired into existing client systems, is the same work I do across six live SME engagements, including The Wall Group, where AI workflow integration lifted net profit 17% year on year. Stack: Python, TypeScript, REST APIs, multi-agent orchestration, tool use, RAG, eval design. Eighteen years of commercial leadership before that means I can hold the client conversation as well as the code. Based in Derry, UK right to work, remote with European travel.

Fact-check notes:
- Cover note sentence 4 attributed Nearform's own phrasing ('integrated with existing APIs, data platforms and cloud services') to Phil's work ('is the work I already do'). Pack facts support REST APIs, SQLite, browser automation and Shopify Admin API integrations for SMEs, not 'data platforms and cloud services'. Rewritten to 'wired into existing client systems' and 'six live SME engagements' so the claim matches the allowed facts; REST APIs added to the stack line from the allowed skills list. Word count held at exactly 150.
- Screening answer 'How did you hear about Nearform?' was unflagged but is an assumption about Phil's source (the role was found by the job-scout routine, not by Phil browsing a job board). Added an ASSUMPTION flag; answer text unchanged.
- All other checks clean: word count 150 (counted), no banned openers, no exclamation marks, no flattery or 'passion', British spelling, employer-specific mandate named from employer_specifics, salary answers at or above £80,000 base, no relocation agreement, travel answer flagged NEEDS PHIL, notice period flagged ASSUMPTION, CV flagged NEEDS PHIL, contact details verbatim, email_body empty because contact_email_printed is 'none'.

## Screening answers

- **Years of experience** — 18 years of commercial and deep-tech leadership; hands-on agentic-AI production delivery since March 2025 (around 18 months), building and operating multi-agent systems on the Anthropic Claude Agent SDK for live SME clients.  _[NEEDS PHIL: the listing specifies at least 8 years of commercial experience at Senior Engineer level. Phil's 18 years are commercial/deep-tech leadership, not software-engineering employment — he must decide how to frame this if asked directly, and must not claim formal engineering tenure.]_
- **Notice period / availability** — No notice period. I run my own company, so I can start within 2 to 4 weeks to hand over client work cleanly.  _[ASSUMPTION: founder with no notice period; 2-4 week handover window inferred from pack defaults, not confirmed by Phil.]_
- **Salary expectation** — £80,000 to £90,000 base plus the stated profit-share bonus and benefits, to be settled at interview against scope.  _[NEEDS PHIL: listing says the range 'starts from £75,000 + bonus' with no upper bound. Pack floor is £80,000 base, so the form dropdown answer should be '£80,000 – £90,000' (or '£90,000 – £100,000' if Phil wants to anchor higher, or 'Prefer to discuss during the interview process'). Phil to choose the band; never select '£70,000 – £80,000'.]_
- **Right to work** — Yes. Full right to work in the UK and Ireland. No sponsorship required now or in the future.
- **Why this company** — Nearform's Forward Deployed Engineer brief is to build and deploy agentic platforms inside client environments, wired into existing APIs, data platforms and cloud services. That is exactly what Blue Canvas does for SME clients today, and Albie is a production example of the same pattern on the Claude Agent SDK. I want to do that work at the scale of Nearform's enterprise client base rather than one SME at a time.
- **LinkedIn Profile** — https://www.linkedin.com/in/philpatterson1
- **Are you currently residing in the UK?** — Yes, I am currently based in the UK
- **Do you now, or will you in the future, require sponsorship to work in the UK?** — No, I do not require sponsorship to work in the UK
- **This role requires frequent travel to work from client sites within Europe, with travel costs covered by the company. Are you able and willing to meet this travel requirement?** — Yes, I am open/willing to do frequent travels within Europe  _[NEEDS PHIL: pack default is 'will travel / periodic onsite', but this screener says 'frequent' travel to European client sites. Phil must confirm he accepts frequent travel before this is submitted. Not relocation, so not a hard no.]_
- **Please select the salary range that best aligns with your base salary expectations for this role:** — £80,000 – £90,000  _[NEEDS PHIL: confirm band. Options below £80,000 must not be selected. Alternatives: '£90,000 – £100,000' or 'Prefer to discuss during the interview process'.]_
- **How did you hear about Nearform?** — Job board listing (Nearform Greenhouse careers page)  _[ASSUMPTION: source inferred (role surfaced by the job-scout routine from the Greenhouse listing); Phil to pick the matching dropdown option if the form offers a fixed list.]_
- **Data Privacy** — Confirm  _[ASSUMPTION: single 'Confirm' checkbox for processing application data under Nearform's privacy notice; standard Greenhouse data-handling consent, not a restrictive term. Phil to tick on submission.]_
- **Preferred First Name (optional)** — Phil
- **Email** — philpatterson85@gmail.com
- **Phone** — +44 7828 699027
- **First Name / Last Name** — Phil / Patterson
- **Resume/CV (required, file upload or paste)** — Upload Phil's current CV file.  _[NEEDS PHIL: supply the CV file (or pasted text) — not in the pack.]_
- **Cover Letter (optional, file upload or paste)** — Paste the cover note above into the cover_letter_text field.

## Probe line

The 1-hour live Python coding challenge over Zoom screen-share, against a spec of 8+ years at Senior Engineer level with Kubernetes deployment and LangGraph/CrewAI/AutoGen — Phil has no formal software-engineering employment, his build evidence is founder-built on the Claude Agent SDK, and he will be asked to prove hands-on Python depth live rather than describe Albie.

