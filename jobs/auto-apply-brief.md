# Auto-apply brief — standing orders for the local apply leg

This file is the handoff contract between the **cloud scout** (twice-weekly cron, branch
`job-scout-reports`) and the **local apply leg** — whichever local agent instance holds
Phil's Chrome sessions and logins. Today that is **Albie (OpenClaw, being retired)**; as
the NanoClaw instance takes over his sessions, it inherits this brief unchanged — the
contract is with the role, not the instance. The canonical CV is now in the repo at
`jobs/cv/phil-patterson-cv.pdf` (2-page, May 2026) — both legs use that file.

The cloud scout refreshes the CURRENT QUEUE section every run (Mon/Thu ~07:00 UTC) and
reads back the DONE section and `jobs/applications/<id>/submitted.md`. The local leg works
through the queue **without waiting for a per-run go**.

The cloud scout may edit ONLY the CURRENT QUEUE and DONE sections. The AUTHORISATION and
BOUNDS sections are Phil's — nobody edits them but him.

---

## AUTHORISATION (set by Phil, in session, 2026-08-25)

> "change the spine - you have to be submitting or theres' no point. take upwork and
> people per hour of it for now. you have my cv, you can crack on wherever you like
> elsewhere. no public sector."

Standing instruction: **submit applications for the roles in the CURRENT QUEUE by
default.** A role reaches Phil only as an exception (see hand-back rules in BOUNDS).
This extends the 2026-08-21 round-2 authorisation ("yes to all": answer screening
questions within bounds; apply to recruiter ads whose end client is unnamed; LinkedIn
session allowed) from a per-run go to a standing one.

**Upwork and PeoplePerHour are OFF** — removed from every leg of the pipeline until Phil
turns them back on (a `note:` line in jobs/feedback.md re-enables them).

## BOUNDS (per the ratified 2026-08-21 precedent — hand back anything outside them)

- **No public sector, anywhere, ever.** Doubt about an employer's ownership = do not
  submit; hand back with what was found.
- **Pay floor (raised by Phil in session, 2026-08-26: "id want the right money, 100k plus"):**
  £100k+ base permanent (local equivalents: ~AED 37k+/month, ~$135k+);
  £500+/day contract; ~€12,000+/month gross on FTC salary-expectation fields.
- **Screening answers:** factual yes/no within the CV; salary expectations at or above
  the floor; start date 2–6 weeks out; visa sponsorship: No (UK right to work);
  interview-recording consent: Yes; occasional travel (≤25%): Yes.
- **Hand back, never answer alone:** relocation commitments; exclusivity or non-compete
  undertakings that would conflict with Blue Canvas AI; anything requiring a figure or
  fact not derivable from the CV; free-text answers making claims beyond the CV.
- **Never fabricate.** Every claim in every submission must be anchored to the CV. A lost
  application is recoverable; an invented fact is not.
- **One submission per company per role.** Check `jobs/applications/` and the tracker
  before submitting; coordinate recruiter double-mandates (same client behind two ads).
- **Log everything:** each submission gets `jobs/applications/<id>/submitted.md` with an
  exact copy of what was sent and every screening answer given. Update the tracker entry
  to `"applied"`. Push to `job-scout-reports`.
- If a form is blocked (classifier, CAPTCHA, shadow-DOM upload, login wall Phil doesn't
  have), mark it **handed-back** in DONE with the reason and move on. Do not fight it.

---

## CURRENT QUEUE (refreshed by the cloud scout — last update 2026-08-27, from the 2026-08-27 run)

Cover notes for all five are in `jobs/reports/2026-08-27.md` (also on the dashboard).
Every detail below came from **search snippets, not the live page** — verify the listed points
before submitting. The cloud session sent **zero emails** this run (no listing printed a
qualifying address), so this queue is the whole of this run's submission activity.

1. **Forward Deployed Engineer — AWS Bedrock (agentic builds in production)** — Blackstone&
   - https://contracts.contractspy.co.uk/job/140356/forward-deployed-engineer-aws-bedrock-at-blackstone-london-remote-12-months-700-800-per-day-outside-ir35/
   - £700–800/day Outside IR35, 12 months, London/Remote hybrid, contract. Confidence: High.
   - Verify before submitting: the hybrid split (how many days on site, and whether Derry-based remote is workable); that the 12-month term and Outside IR35 determination are as advertised; posting still live.
   - Note: the stack is AWS Bedrock specifically and the ad wants a strong data background. The cover note is honest about Claude Agent SDK being the demonstrated depth — keep that framing, do not overclaim Bedrock.

2. **Artificial Intelligence Consultant (Director / Architect / Tech Lead, LLM / RAG / Agentic)** — global investment bank via CipherTek
   - https://contracts.outsidespy.co.uk/job/341484/artificial-intelligence-consultant-at-ciphertek-recruitment-london-800-1-300-per-day/
   - £800–1,300/day Outside IR35, London hybrid 1–2 days/week, contract. Confidence: High.
   - Verify: IR35 determination in writing; the hybrid pattern (1–2 days/week is workable from Derry and the cover note says so); end client sector is a bank, which is fine.
   - Carried over from the 2026-08-24 queue and still open — this one has now been queued twice without being actioned.

3. **Head of AI** — BCD Travel (BCD Group)
   - https://jobs.bcdtravel.com/job/Head-of-AI/1369556557/
   - €160,000–200,000, **fully remote United Kingdom**, permanent. Confidence: Medium.
   - Verify: posting dated 14 Aug — confirm the req is still open; confirm the salary band applies to the UK-remote posting and not just a mainland-Europe entity; confirm reporting line and team size.
   - Best remote-permanent Head of AI found in several runs: stated pay well clear of the £100k floor, no relocation.

4. **Head of EMEA Partnerships** — OpenAI
   - https://openai.com/careers/head-of-emea-partnerships-london-uk/
   - London, UK (EMEA remit), permanent, salary unstated. Confidence: High.
   - Verify: whether the role requires London presence or tolerates UK-remote with travel; if a salary-expectation field appears, the £100k+ floor applies (OpenAI London partnership leadership will clear it comfortably).
   - Commercial-AI hybrid: Phil's 18 years of BD leadership plus the fact that he personally ships agent systems is the differentiator here.

5. **Applied AI, Startups (UK or Ireland)** — Anthropic
   - https://job-boards.greenhouse.io/anthropic/jobs/4596796008
   - UK or Ireland, permanent, salary unstated. Confidence: Medium.
   - Verify: this is a distinct req from Anthropic's *Solutions Architect, Applied AI (Startups)* (greenhouse job 4968059008) — check both and apply to whichever matches seniority; do not submit twice for what is really one mandate.
   - Strongest genuine fit in the whole sweep: Phil runs production infrastructure on the Claude Agent SDK daily.

**Also standing from 2026-08-21 (packs complete in `jobs/applications/<id>/pack.md`):**
- Distyl AI — AI Strategist, London (3 days/week onsite: only submit the "Yes" if Phil has confirmed it — otherwise handed-back)
- Maze — Head of AI (£180–250k remote Europe; pack ready; note the transformer-from-first-principles bar)
- Data Intellect — AI Engineer (Agentic Systems), Belfast (SmartRecruiters; the "what I'd change" free-text is Phil's to write — handed-back unless he supplies it)
- Harnham — AI Transformation Lead, Dublin (LinkedIn Easy Apply; re-found live on 2026-08-27, so liveness is better than it looked — but the end client is unnamed and Harnham place into Irish semi-state bodies and universities, so **identify and clear the client before applying**)

**Worth a look but deliberately NOT auto-queued — Phil's call:**
- **Capitol AI (YC S24) — Forward Deployed Engineer, UK**, £100,000–150,000, London hybrid. High confidence, pay stated, strong fit — but Capitol AI's stated client base spans **central government departments** alongside City financial institutions. The employer is private, so it does not breach the letter of the exclusion, but the delivery work may be public-sector-facing. Not queued under a standing auto-submit authorisation. https://www.workatastartup.com/jobs/82521
- **Director of Agentic AI — undisclosed consulting firm via Omnis Partners**, £160,000–220,000 + bonus, UK-wide flexible. Top-of-market pay and an agentic-specific title, but the employer is hidden behind a recruiter and UK consulting firms with agentic-AI practices frequently run government programmes. Confirm the firm and its client mix first. https://www.itjobswatch.co.uk/jv/Omnis-Partners/Director-of-Artificial-Intelligence-Job-London-UK-4xbttw
- **Head of AI & Automation — global private capital investor via Charterhouse ME**, Dubai. Highest-confidence Dubai find, private sector, first dedicated AI hire and explicitly an individual-contributor seat. Salary unstated and it implies UAE presence. https://www.linkedin.com/jobs/view/4392507367/

**Chase, do not re-apply — MCS Group.** Stuart Kennedy replied on 26 Aug and handed Phil's AI Consultant
application to **Rachael Walker** (r.walker@mcsgroup.jobs, CC'd on the existing thread); Phil replied
personally and stated the £100k+ expectation. She has not come back. MCS also has a separate live
*Technology Consultant — Data/AI* mandate in Belfast with Walker as the named contact — but that one
carries a **high public-sector risk** (NI consultancy Data/AI practices lean heavily on government,
HSC and arms-length body programmes), so it is not queued. Any move here is a reply into the existing
thread, and it is Phil's to make.

## STANDING TASK — LinkedIn recruiter campaign (added on Phil's instruction, 2026-08-26: "are you able to do linkedin as well? contact a bunch of recruiters, based anywhere, share my cv")

For the LOCAL leg only (holds Phil's LinkedIn session; the cloud cannot log in):

- Target: recruiters and talent partners placing senior AI / data / tech leadership roles — UK, Ireland, Dubai/UAE, remote-first firms. Anywhere.
- Motion: connection request with a short note, then on accept a message with the pitch (agentic-AI founder, Wall Group +17% net profit, 18 yrs commercial leadership; targets Head of AI / AI consultant / FDE / fractional CAIO; £100k+ base perm or £500+/day contract; NI-based, remote preferred, open to Dubai) and the CV PDF attached (jobs/cv/phil-patterson-cv.pdf).
- PACE IT: max ~15 connection requests/day, spread through the day — a restricted LinkedIn account kills the whole pipeline. Never use automation patterns that look like scraping.
- Log every contact to jobs/applications/linkedin-outreach.md (name, firm, date, stage: requested/connected/messaged/replied). Never message the same recruiter twice without a reply.
- Recruiter replies are the highest-value event: surface them to Phil immediately.

## DONE (written by the local leg; cloud scout reads and clears)

_(empty — local leg has not yet run under this brief)_
