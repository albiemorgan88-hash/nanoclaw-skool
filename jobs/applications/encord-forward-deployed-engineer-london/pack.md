# Forward Deployed Engineer (Ashby: department EPD, team "Forward Deployed Engineering"; WaaS copy titles it "Forward Deployed Engineer, London") — Encord (trading name; UK operating entity is understood to be Cord Technologies Limited, 12 Macklin Street, London WC2B 5NF — the legal name was not printed on the listing or careers page, only the address was)

- Verified: 2026-08-21 · live: **live** · private sector: **confirmed** · decision: **hand_to_phil**
- Why: Live, private-sector, direct employer, Ashby form needs no account — but it requires a CV file upload and Phil must personally answer the required 'are you OK with 4 days a week in our London office' and 'open to relocation' questions, which decide whether this is worth pursuing at all. The scout's 'hybrid' and '$150–250k' claims do not hold up on the employer's own ATS (OnSite, compensation hidden). Only worth Phil's time if he would take a London-based, mostly in-office permanent SWE-flavoured role; otherwise he should drop it.
- Pay (as listed): Ashby (employer ATS) shows no compensation — shouldDisplayCompensationOnJobPostings=false, no tiers; description says only "Competitive salary, commission, and meaningful equity". The USD band "$150K - $250K" in the scout report exists only on the YC Work at a Startup listing (salaryRange field, equityRange null) and is the same band YC shows for the SF and NYC FDE roles, so it is most likely a US-centric company-level figure rather than a confirmed London sterling band. Treat GBP salary as unstated.
- Location/remote: London, UK — Ashby workplaceType "OnSite", isRemote=false, address 12 Macklin Street, London WC2B 5NF. Description: "Strong in-person culture — most of the team works from our London office 4+ days/week". Application form asks (required): "This role is based out of our office in the city where it is posted, with an expectation of 4 days a week in-person at your assigned location. Does that work for you?" and "Are you open to relocation for this role?" — i.e. NOT hybrid; the scout report's "hybrid" is wrong. Travel for customer visits across UK/Europe. WaaS visa field reads "US citizen/visa only" (a WaaS company-level setting, odd for a London role); Ashby form asks whether you will need visa sponsorship in the country where the role is based.
- Type: permanent · posted/updated: Ashby publishedAt 2026-05-18 (publishedDate 2026-05-18); still listed 2026-08-21. WaaS listing carries no date. Note the Ashby description text has been revised since the WaaS copy was taken (WaaS version is client-facing/solutions-engineering flavoured; current Ashby version is "engineering-first" and asks for "3–8 years in a software engineering role").
- End client: n/a — direct employer posting (Encord's own Ashby board and its own YC Work at a Startup listing)
- Apply: https://jobs.ashbyhq.com/encord/2b1c10d4-cde7-422b-9f52-2739865d95cb/application (Ashby; account required: no)
- Contact email printed in listing: none
- Red flags: (1) Not hybrid: Ashby marks the role OnSite and the form requires a yes/no to 4 days a week in the London office plus a relocation question — from Derry this is effectively relocation to London. (2) No sterling salary anywhere on the employer's ATS; the $150K–$250K figure is a YC-board USD band shared with the SF and NYC postings. (3) The current Ashby version has hardened into an 'engineering-first' role asking for 3–8 years in a software engineering role — Phil's CV has no formal SWE employment history, and no computer-vision/annotation background. (4) Posted 18 May 2026, three months open. (5) Required CV upload and answers to in-office/relocation/start-date questions that only Phil can give.
- Liveness evidence: 2026-08-21: Encord's own Ashby board API (https://api.ashbyhq.com/posting-api/job-board/encord) returns "Forward Deployed Engineer", London, FullTime, OnSite, isListed=true, publishedAt 2026-05-18; the Ashby job page https://jobs.ashbyhq.com/encord/2b1c10d4-cde7-422b-9f52-2739865d95cb returns HTTP 200 with title "Forward Deployed Engineer @ Encord". The YC Work at a Startup page https://www.workatastartup.com/jobs/92688 also returned 200 today (needed an Accept: text/html header; bare curl gets 406) with the full description embedded in its data-page JSON.
- Private-sector evidence: Listing states Encord is a 100+ person venture-backed startup that has raised $60M Series C from Wellington Management, CRV, Next47 and Y Combinator (YC W21). Private investors only; no state, university or Gulf-sovereign ownership indicated. Customers named (Woven by Toyota, AXA, UiPath, Zipline) are all private-sector.

## Form fields
- Name (required) — text
- How do you pronounce your name? (optional) — text
- What are your preferred pronouns? (optional) — text
- Email (required) — email
- Resume (required) — file upload
- Linkedin Profile (required) — text
- Current Location (required) — location picker
- Preferred location? (required) — text
- This role is based out of our office in the city where it is posted, with an expectation of 4 days a week in-person at your assigned location. Does that work for you? (required) — Yes/No boolean
- Are you open to relocation for this role? (required) — text
- Will you now or in the future require visa sponsorship to work in the country where this role is based? (required) — Yes/No boolean
- What is the earliest you would want to start? (required) — text
- Do you have any deadlines or time constraints we should be aware of? (optional) — long text
- Why do you want to work at Encord? (Great answers are often 200-400 words) (optional) — long text
- I certify that the facts set forth in this application are true and complete to the best of my knowledge. I understand that any misrepresentation or omission may result in disqualification from consideration or, if hired, dismissal from employment. (required) — checkbox boolean

## Custom questions
- How do you pronounce your name?
- What are your preferred pronouns?
- Preferred location?
- This role is based out of our office in the city where it is posted, with an expectation of 4 days a week in-person at your assigned location. Does that work for you?
- Are you open to relocation for this role?
- Will you now or in the future require visa sponsorship to work in the country where this role is based?
- What is the earliest you would want to start?
- Do you have any deadlines or time constraints we should be aware of?
- Why do you want to work at Encord? (Great answers are often 200-400 words)
- I certify that the facts set forth in this application are true and complete to the best of my knowledge. I understand that any misrepresentation or omission may result in disqualification from consideration or, if hired, dismissal from employment.

## Cover note (149 words · fact-check: pass)

Since March 2025 I have been shipping autonomous agents into production for paying businesses. Albie, my 24/7 multi-channel operator on the Anthropic Claude Agent SDK, runs inbox, Apollo and Zoho campaigns, proposals, coding and scheduled tasks; my company runs on it daily. Six live client engagements, sold, scoped, built and operated by me; The Wall Group's net profit rose 17% year on year. Stack: Python, TypeScript, SQLite, REST APIs, RAG and eval design.

Encord's Forward Deployed function is new, and early members will own the system-design decisions for wiring the platform into customers' ML and data pipelines. That is what I already do for SMEs, with 18 years of commercial work behind it, so I hold the customer conversation as well as the architecture.

Based in Derry with UK and Irish right to work, available within four weeks; the four-day London office pattern is the point to settle early.

## Screening answers

- **Years of experience** — 18 years of commercial and deep-tech leadership (Commercial Director, BD Director, NED, Senior Fund Manager); hands-on agentic-AI production delivery since March 2025, roughly 18 months, building and operating production agent systems on the Claude Agent SDK for six live client engagements.  _[NEEDS PHIL: the current Ashby description asks for 3–8 years in a software engineering role. Phil has no formal SWE employment; his engineering evidence is founder-built (Albie, six client systems). Phil decides whether to apply against that requirement at all.]_
- **Notice period / availability** — No notice period — founder of my own company. I can start within 2–4 weeks of offer to hand over live client work cleanly.  _[ASSUMPTION: 2–4 week handover window is the pack default; Phil to confirm.]_
- **Salary expectation** — No sterling figure is published on Encord's own ATS. The YC Work at a Startup listing shows $150K–$250K for this role; I would expect the upper half of that band in sterling equivalent, and in any case not below £80,000 base, plus the stated commission and equity.  _[ASSUMPTION: the $150K–$250K band is a YC-board USD figure shared with the SF and NYC postings, not a confirmed London band; Ashby hides compensation. Note the Ashby form does not ask for salary, so this is for interview/recruiter screen only.]_
- **Right to work** — Yes — full right to work in the UK and Ireland. No sponsorship required now or in the future.
- **Why this company** — Encord's Forward Deployed function is new, and early members will own the system-design decisions for integrating the platform into customers' ML and data pipelines. That is the job I already do at SME scale — six live agent deployments, sold, built and operated by me — and Encord's 300+ AI-team customer base is the scale step up from that.
- **Name** — Phil Patterson
- **Email** — philpatterson85@gmail.com
- **Resume (file upload, required)** — Upload Phil's current CV (PDF).  _[NEEDS PHIL: CV file must be uploaded by Phil; pack cannot attach it.]_
- **Linkedin Profile** — https://www.linkedin.com/in/philpatterson1
- **Current Location (location picker)** — Derry/Londonderry, Northern Ireland, United Kingdom
- **How do you pronounce your name?** — Phil Patterson — as written (FIL PAT-er-son). Optional field; can be left blank.  _[ASSUMPTION: standard pronunciation; optional field.]_
- **What are your preferred pronouns?** — Optional field — leave blank unless Phil wants to state them.  _[NEEDS PHIL: personal preference, not in the allowed facts.]_
- **Preferred location?** — Derry/Londonderry, Northern Ireland, working remotely with regular travel to the London office and to customer sites across the UK and Europe. The role is posted as London, 4 days a week in-office.  _[NEEDS PHIL: the listing is OnSite London, not hybrid. If Phil will not base himself in London this answer will likely end the application; if he would, the answer should read 'London'.]_
- **This role is based out of our office in the city where it is posted, with an expectation of 4 days a week in-person at your assigned location. Does that work for you? (Yes/No)** — No, on the pack defaults (Derry-based, remote preferred, open to travel and periodic onsite). Only answer Yes if Phil personally decides to base himself in London four days a week.  _[NEEDS PHIL: this is the gating question for the whole application. Ashby marks the role OnSite, isRemote=false; 12 Macklin Street, London WC2B 5NF. Phil must answer it himself.]_
- **Are you open to relocation for this role?** — Not by default. Currently based in Derry/Londonderry with UK right to work; open to frequent travel to London and to customer sites, but a permanent move is a decision for Phil.  _[NEEDS PHIL: London is within the UK (not relocation abroad), but from Derry this is effectively relocation. Never answer Yes without Phil's explicit decision.]_
- **Will you now or in the future require visa sponsorship to work in the country where this role is based? (Yes/No)** — No — UK and Irish right to work, no sponsorship needed now or in future.
- **What is the earliest you would want to start?** — Within 2–4 weeks of an offer, allowing a clean handover of live client work.  _[ASSUMPTION: pack default notice window; Phil to confirm a date.]_
- **Do you have any deadlines or time constraints we should be aware of?** — None fixed. I run live client engagements through my own company, so the only constraint is a 2–4 week handover before a start date.  _[ASSUMPTION: no other deadlines known; Phil to confirm.]_
- **Why do you want to work at Encord? (Great answers are often 200-400 words)** — Encord describes itself as the universal data layer for AI: indexing, curating, annotating and evaluating data across the whole lifecycle for 300+ AI teams, with Woven by Toyota, AXA, UiPath and Zipline among them. The Forward Deployed function that sits on top of that is new, and the listing is explicit that early members will help define and scale it and own the system-design decisions for how Encord is wired into customers' ML and data pipelines.

That is the work I do now, at SME scale. Since March 2025 I have sold, scoped, built and operated production agent systems for six paying businesses across construction, equestrian, property, hospitality and ecommerce. The clearest result is The Wall Group, where AI workflow integration contributed to a 17% year-on-year rise in net profit that funded their acquisition of a new site. My own company runs on Albie, a 24/7 multi-channel operator I built on the Anthropic Claude Agent SDK that handles inbox, Apollo and Zoho campaigns, proposals, coding and scheduled tasks with persistent memory. I have also designed RL evaluation environments for a HUD.ai vendor proposal: rubric-graded, mutation-tested eval tasks. Python, TypeScript, SQLite, REST APIs, RAG and browser automation are the daily tools.

A forward deployed role is half customer conversation and half system design, and I have 18 years of the first half: Commercial Director at Tonomy Foundation, BD Director at Skipshift and MOF Technologies, Senior Fund Manager on a £10M VC fund at E-Synergy. I can sit with a customer's ML lead, work out what their pipeline actually needs, build it, and then run it.

What I want from Encord is the scale step: taking what I have proved with SME deployments into AI teams operating at the level of Woven by Toyota and AXA, inside a function small enough that the early design decisions are still mine to make. I am not arriving with a computer-vision background, and I would rather say that plainly than have you find it out at interview. I am arriving with production agent systems, customer P&L and a habit of shipping.  _[346 words. Optional field; uses only allowed facts. Phil may cut the final paragraph's computer-vision admission if he prefers to hold it for interview.]_
- **I certify that the facts set forth in this application are true and complete to the best of my knowledge. I understand that any misrepresentation or omission may result in disqualification from consideration or, if hired, dismissal from employment. (checkbox)** — Tick — every answer in this pack uses only verified facts from Phil's CV. This is a truth attestation, not a restrictive term.  _[NEEDS PHIL: Phil ticks this himself after reading every answer, since he is the one certifying.]_

## Probe line

No formal software-engineering employment against a listing that now asks for 3–8 years in a SWE role and a computer-vision/annotation product — Albie and the six client systems are founder-built evidence, not a SWE track record — and before any of that he has to say yes or no to four days a week in a London office from Derry.

