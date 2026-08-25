# Auto-apply brief — standing orders for the local apply leg

This file is the handoff contract between the **cloud scout** (twice-weekly cron, branch
`job-scout-reports`) and the **local apply leg** (Phil's local Albie instance, which holds
his Chrome sessions and CV v2 PDF).

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
- **Pay floor:** £80k+ permanent (local equivalents: ~AED 30k+/month, ~$110k+);
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

## CURRENT QUEUE (refreshed by the cloud scout — last update 2026-08-25, from the 2026-08-24 run)

Cover notes for all five are in `jobs/reports/2026-08-24.md` (also on the dashboard).
Every detail below came from search snippets, not the live page — **verify the listed
points on the live page before submitting.**

1. **AI Engineer (agentic architectures / multi-agent workflows)** — via Outside IR35 Tech Jobs
   - https://outsideir35.org.uk/jobs/ai-engineer/tYunWnFPB8
   - £112/hour (~£840/day), England remote, contract. Confidence: Medium.
   - Verify before submitting: employer name; that the rate is day-rate-equivalent as read; posting still live.
2. **Interim Head of AI (Outside IR35, 6-month contract)** — recruiter-posted, CV-Library
   - https://www.cv-library.co.uk/job/221108467/Interim-Head-of-AI-Outside-IR35-Contract-6-Month-Contract
   - £800/day, remote UK. Confidence: Medium.
   - Verify: employer name (unnamed); stack is Azure/Databricks-flavoured — cover note already positions agent-native experience as the complement, keep that framing.
3. **Fractional Head of AI — marketing agency engagement** — Head of AI (headofai.ai)
   - https://talents.studysmarter.co.uk/companies/head-of-ai/belfast/fractional-head-of-ai-full-service-marketing-agency-29028017/
   - Belfast, remote-first, £250k+ OTE pro-rated. Confidence: Medium.
   - Verify: aggregator URL — find the engagement on headofai.ai's own site first; note the partner-model overlap with Blue Canvas (bounds: no exclusivity undertakings).
4. **Senior Forward Deployed Engineer (AI Agent) — UK** — Cresta
   - https://job-boards.greenhouse.io/cresta/jobs/5097513008
   - UK remote, permanent, salary unstated (US band $185–235k). Confidence: High.
   - Verify: req still open; UK band unstated — if the form asks expectations, floor applies (£80k+; sensible ask given the US anchor is well above it).
5. **Artificial Intelligence Consultant (Director/Architect, LLM & RAG)** — global investment bank via CipherTek
   - https://contracts.outsidespy.co.uk/job/341484/artificial-intelligence-consultant-at-ciphertek-recruitment-london-800-1-300-per-day/
   - £800–1,300/day Outside IR35, London hybrid 1–2 days/week. Confidence: Medium.
   - Verify: end client sector (bank — fine), IR35 determination in writing; hybrid pattern is workable from Derry and the cover note says so.

**Also standing from 2026-08-21 (packs complete in `jobs/applications/<id>/pack.md`):**
- Distyl AI — AI Strategist, London (3 days/week onsite: only submit the "Yes" if Phil has confirmed it — otherwise handed-back)
- Maze — Head of AI (£180–250k remote Europe; pack ready; note the transformer-from-first-principles bar)
- Data Intellect — AI Engineer (Agentic Systems), Belfast (SmartRecruiters; the "what I'd change" free-text is Phil's to write — handed-back unless he supplies it)
- Harnham — AI Transformation Lead, Dublin (LinkedIn Easy Apply; 3-month-old ad — verify liveness first)

## DONE (written by the local leg; cloud scout reads and clears)

_(empty — local leg has not yet run under this brief)_
