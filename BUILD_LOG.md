# Build log (accurate account of AI assistance)

**2026-10-13 — Requested:** The applicant asked ChatGPT to make a small Pennant-relevant vibe-coding project after discussing the GTM Founder Fellow requirement.

**Scoping:** The public YC posting describes Pennant's focus on corporate governance, proxy voting and engagement with asset managers, public companies and advisers. It requests GTM research, sales collateral, outbound experimentation and measurement. The project was scoped to an independent research workbench, not a Pennant replica.

**Implementation v1:** AI-assisted code generated a static offline website and five-factor lead-priority heuristic. All sample organizations, deal statuses, contacts and A/B numbers were fabricated and explicitly labeled so they cannot be mistaken for actual buyer intelligence.

**Implementation v2:** Added local CSV import/export, responsive account workspace, segment-specific unsent outreach drafts, rate calculations with Wilson intervals, and deterministic topic flagging for user-pasted governance excerpts. Inputs are locally stored; no telemetry or AI endpoint was added.

**Test / fix:** A unit test initially expected the exported Markdown report to explicitly mention human review. The report was updated to say “Human review required,” then all 17 tests passed.

**Browser QA:** Desktop and mobile browser rendering and navigation were checked. Twenty browser interactions passed, including searching accounts, filtering, changing weights, editing and adding accounts, switching outreach variants, adjusting experiment inputs, and re-analyzing governance excerpts. No JavaScript page exceptions appeared during the checks.

**Candidate's next step:** The applicant should independently run the app, adjust one core component, and be able to demonstrate the difference. This distinction matters: the project is a real working prototype, but the conversation itself did not demonstrate the user's independent coding experience or real customer traction.


**2026-10-14 — v2 upgrade requested:** The applicant asked for a stronger project, an appropriate founder message recognizing the official YC application link, and public hosting. Public hosting remains pending because the GitHub integration is not connected and no authenticated deploy target is available in this session; the project has NOT been falsely described as published.

**v2 implementation:** Added 14-day sales-sprint planning with editable hypothetical funnel assumptions and downloadable founder memo; eleven hand-labeled synthetic evaluation cases with explicit false-positive/false-negative outcomes and export; linked a paraphrased Apple 2026 SEC proxy agenda to its original source. Updated the responsive UI and privacy/limitations text.

**v2 tests:** 23 Node unit/logic checks plus 30 Chromium/Playwright integration checks passed. Both are reproducible in the delivered source archive. The user must not claim external validity or customer traction.