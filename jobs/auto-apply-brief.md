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

## CURRENT QUEUE (refreshed by the cloud scout — last update 2026-08-31, from the 2026-08-31 run)

Cover notes for all five are in `jobs/reports/2026-08-31.md` (also on the dashboard).
Every detail below came from **search snippets, not the live page** — verify the listed points
before submitting. The cloud session sent **zero emails** this run: the dedicated email-hunt pass
(15 searches) found zero listings printing an application address anywhere.

**PRIORITY — not a job application, do this first.** Richard at Aruba Exec replied on 28 Aug to the
26 Aug candidate registration: *"We don't currently have a live search in those target areas of
interest, but I would welcome a copy of your CV for when the situation changes."* He asked for the CV
and has been waiting since. The cloud session cannot attach it (the 1.9 MB PDF is all embedded fonts
and does not compress — recompression saved 1 KB). **Reply to richard@arubaexec.com on the existing
thread with `jobs/cv/phil-patterson-cv.pdf` attached.**

1. **Senior Software Engineer, Applied AI (United Kingdom)** — Justworks
   - https://job-boards.greenhouse.io/justworks/jobs/7797380
   - **£132,000–170,000 base**, remote United Kingdom, permanent. Confidence: High. NEW this run.
   - Best new permanent find in several runs: pay is stated and well clear of the £100k floor, and the role is explicitly about building an agent platform that reads operational knowledge and executes tasks end-to-end — Albie, in someone else's product.
   - Verify before submitting: that the £132–170k band is current and applies to this req rather than a US-converted figure; whether it is genuinely fully remote UK or expects London presence; Northern Ireland eligibility and whether the UK entity employs directly or via an EOR; that "Senior" here is not screening primarily for large-scale distributed-systems depth.

2. **Artificial Intelligence Consultant (Director / Architect / Tech Lead, LLM / RAG / Agentic)** — global investment bank via CipherTek
   - https://contracts.outsidespy.co.uk/job/341484/artificial-intelligence-consultant-at-ciphertek-recruitment-london-800-1-300-per-day/
   - £800–1,300/day Outside IR35, London hybrid 1–2 days/week, contract. Confidence: High.
   - **Queued for the third consecutive run and still not actioned.** It resurfaced live in this run's contract lane. If there is a reason it keeps being skipped, mark it handed-back with that reason rather than leaving it to roll over again.
   - Verify: the Outside IR35 SDS in writing (banks frequently reclassify inside); the 1–2 day London cadence; that a candidate without prior regulated-financial-services delivery will be considered.

3. **Senior AI Engineer (Freelance)** — Elsewhen
   - https://careers.elsewhen.com/jobs/8058175-senior-ai-engineer-freelance
   - £500–600/day Outside IR35, 6 months, **fully remote, UK candidates only**, ASAP start. Confidence: High. NEW this run.
   - Cleanest location fit found in the entire sweep — fully remote UK with no onsite cadence at all, which suits a Derry base with zero travel cost.
   - Verify: how hard the LangGraph / Google ADK / LlamaIndex framework requirement is — Phil's production depth is the Claude Agent SDK, and a rigid framework screen is the likeliest rejection here; that "UK candidates only" explicitly covers Northern Ireland; that the ASAP req is still open.

4. **Senior AI Engineer (LLM / Agentic AI)** — via Edison Smart®
   - https://contracts.outsidespy.co.uk/job/348421/senior-ai-engineer-llm-agentic-ai-outside-ir35-at-edison-smart-london-area-600-700-per-day/
   - £600–700/day Outside IR35, 6 months, London hybrid — **1 day per week onsite** in Victoria. Confidence: High.
   - Lightest London cadence in the contract lane; designing and deploying production AI agents with RAG named explicitly.
   - Verify: whether the single onsite day can be batched, and price Derry–London travel into the rate; that the Outside IR35 SDS is issued; the end client's identity; whether they require enterprise-scale production deployments at a headcount Phil's SME engagements may not match.

5. **Director of AI Strategy** — global maritime & logistics business via Harnham
   - https://www.reed.co.uk/jobs/director-of-ai-strategy/57101940
   - **£1,000–1,500/day Outside IR35**, initial 6 months, London (Goodge Street) — **3 days onsite per week**. Confidence: High.
   - Highest day rate found anywhere in this run, and the brief (assess the AI/data landscape, find commercial value, build an adoption roadmap, operate credibly at C-suite) is the closest title-level match to what Phil actually does.
   - Verify FIRST: whether 3 days onsite weekly is genuinely non-negotiable — **that pattern is unworkable from Derry without a London base**, so establish it before investing in the application. Also confirm the £1,000–1,500 band is real budget not a headline range, that the Outside IR35 SDS has been issued, and — since ports and logistics can shade into harbour authorities — **confirm the end client is not a public body** before submitting.

**Also standing from earlier runs (packs complete in `jobs/applications/<id>/pack.md`):**
- Blackstone& — Forward Deployed Engineer, AWS Bedrock (£700–800/day Outside IR35, contractspy 140356). A **sibling Blackstone& listing** appeared this run (AI Data Engineer — agentic/evals/RAG/Bedrock, contractspy 354164, rate negotiable). Same agency, same stack: treat as one client family and **apply once only**.
- BCD Travel — Head of AI, remote United Kingdom (jobs.bcdtravel.com/job/Head-of-AI/1369556557/). Still live this run; the €160–200k figure did not reappear in the snippet, so re-confirm pay.
- Anthropic — Applied AI, Startups (UK/Ireland). A further req appeared this run: **Manager, Applied AI (Startups), EMEA** (job-boards.greenhouse.io/anthropic/jobs/5142110008). Check all Anthropic Applied AI reqs together and apply to the one matching seniority — do not submit twice for one mandate.
- OpenAI — Head of EMEA Partnerships; Distyl AI — AI Strategist (3 days onsite, Phil's call); Maze — Head of AI; Data Intellect — AI Engineer, Belfast (free-text answer is Phil's); Harnham — AI Transformation Lead, Dublin (**identify and clear the end client first**).

**Chase, do not re-apply — MCS Group.** Unchanged: Stuart Kennedy handed the AI Consultant application to Rachael Walker (r.walker@mcsgroup.jobs) on 26 Aug and CC'd her; Phil replied personally with the £100k+ expectation. **Still no reply from Walker, six days on.** Any move is a chase into the existing thread and it is Phil's to make.

## STANDING TASK — LinkedIn recruiter campaign (added on Phil's instruction, 2026-08-26: "are you able to do linkedin as well? contact a bunch of recruiters, based anywhere, share my cv")

For the LOCAL leg only (holds Phil's LinkedIn session; the cloud cannot log in):

- Target: recruiters and talent partners placing senior AI / data / tech leadership roles — UK, Ireland, Dubai/UAE, remote-first firms. Anywhere.
- Motion: connection request with a short note, then on accept a message with the pitch (agentic-AI founder, Wall Group +17% net profit, 18 yrs commercial leadership; targets Head of AI / AI consultant / FDE / fractional CAIO; £100k+ base perm or £500+/day contract; NI-based, remote preferred, open to Dubai) and the CV PDF attached (jobs/cv/phil-patterson-cv.pdf).
- PACE IT: max ~15 connection requests/day, spread through the day — a restricted LinkedIn account kills the whole pipeline. Never use automation patterns that look like scraping.
- Log every contact to jobs/applications/linkedin-outreach.md (name, firm, date, stage: requested/connected/messaged/replied). Never message the same recruiter twice without a reply.
- Recruiter replies are the highest-value event: surface them to Phil immediately.

## DONE (written by the local leg; cloud scout reads and clears)

**The local leg is running but is not logging.** The cloud scout found **seven LinkedIn Easy Apply
submissions made on 2026-08-28** via Gmail confirmations — none of them written to this DONE section
and none with a `jobs/applications/<id>/submitted.md`. They have been marked `applied` in the tracker
by the cloud scout instead. Please log future submissions here so the two legs stay in sync.

| Role | Company | Location | Evidence |
|---|---|---|---|
| Senior Director, AI Solutions | Intellias | United Kingdom | LinkedIn confirmation, 28 Aug |
| Director of Artificial Intelligence (AI) | The Portfolio Group | Manchester | LinkedIn confirmation, 28 Aug |
| Head of Artificial Intelligence | Hays | Dubai, UAE | LinkedIn confirmation, 28 Aug (+ "viewed by Hays", 31 Aug) |
| VP of AI | Salt | Dubai, UAE | LinkedIn confirmation, 28 Aug |
| Director of Technology Delivery & Transformation | TechHeads | not stated | LinkedIn confirmation, 28 Aug |
| Chief Commercial Officer (Dublin12) | VANRATH | Dublin | LinkedIn confirmation, 28 Aug |
| Head of Organic Growth (SEO & AI Search) | British Supplements | Gilford, NI | LinkedIn confirmation, 28 Aug |

Two notes on the above, for the local leg to take account of:
- **British Supplements — Head of Organic Growth (SEO & AI Search)** is off-brief. It is an SEO/growth
  marketing role at a supplements retailer, not one of the four target role types, and nothing suggests
  it clears the £100k floor. Do not submit this shape of role again.
- **None of the five roles in the previous CURRENT QUEUE were actioned**, while seven off-queue LinkedIn
  roles were. The queue exists because those roles were filtered, ranked and pay-checked. Work the queue
  first, then range wider.

