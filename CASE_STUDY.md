# Portfolio case study · Governance GTM Lab

**Theme:** If I joined the Founder Fellow — GTM, Growth & Strategy team at an AI-native governance startup, how could I organize an early GTM learning loop?

## 1. The concrete business problem

In corporate governance, institutional investors, public-company teams and advisers work with voting policies, annual meeting materials, evidence from filings and engagement notes. Pennant publicly describes the challenge of bringing those sources together to support thoughtful decisions. Separately, the GTM fellow position emphasizes segment research, outbound experiments, metrics, and executing alongside founders. The portfolio opportunity is to connect both: **who might need the workflow, and how do we learn whether they care?**

## 2. The prototype (what I can show in two minutes)

1. **Rank the hypothetical market.** Inspect twelve explicitly fictitious account records, grouped by asset managers, public companies and governance advisers. Change the friction weight from 30 to 50 and watch the research order change.
2. **Open a prospect record.** Show a traceable, five-factor account score. The next action is to validate the manual notes and source links, not to claim those pain points are factual.
3. **Draft discovery outreach.** Switch two questions-first variants; show they ask whether a workflow is painful instead of claiming a product solves it.
4. **Compare funnel results.** Change demo sends/replies/meetings; watch the percentages and 95% Wilson intervals recompute. The starter campaign is invented—there is no actual measured lift.
5. **Paste a mock DEF 14A-style excerpt.** Show candidate board, executive pay, shareholder-rights and disclosure mentions with line citations; export the human-review checklist.

## 3. Design decisions and trade-offs

- **No API key or back end:** One downloaded file can demonstrate the product to a founder. This makes demos repeatable offline.
- **Explicit heuristic instead of magical AI prediction:** The score is inspectable and tied to questions a sales team could verify.
- **Discovery-first messaging:** Early outreach should test a customer's problem without pretending Pennant made particular commitments.
- **Data provenance as a first-class concern:** Keyword flags include excerpt line references; the brief requires human verification. No false “AI-powered proxy recommendation” claim.
- **Evals before bragging:** Automated tests cover deterministic logic and browser interactions. Real conversion validation is a later experiment, not something fabricated into the prototype.

## 4. Measurable results (engineering tests, not business performance)

- 23 automated logic/unit tests passed.
- 30 end-to-end browser smoke checks passed.
- Twelve clearly fictional accounts included, with CSV import/export.
- Four governance topic groups supported by deterministic keyword matching.

No claim of customer adoption, deployed production users, A/B winner, investor returns, or Pennant integration is made.

## 5. A failure case I would explain in an interview

**Problem:** A line can mention a shareholder proposal when it is only discussing a board's opposition. A pure keyword match would still flag “Shareholder rights.” This is a *candidate topic*, not proof that the proposal is material, eligible, adopted, or advisable.

**Mitigation in this prototype:** Attach the exact excerpt line, show the matched expression, state the limitation, and require analyst review against original proxy filings. A more advanced version would create a small hand-labeled evaluation set and measure precision/recall by topic before using an LLM parser.

## 6. Three next iterations worth doing with actual user input

1. **Real, cited account research:** Replace fictional companies with a small, properly sourced list of actual governance teams, including how you verified the contact and whether outreach would be appropriate.
2. **Discovery interviews:** Ask 3–5 industry contacts about workflow pain, document the answers and turn them into a revised score model. Do not claim interviews occurred unless they actually did.
3. **Human-labeled evidence evals:** Collect a small set of permissioned, public DEF 14A snippets, write topic labels, measure errors and then compare a real LLM API with the keyword baseline.

## 7. How to be transparent about AI assistance

The current application was **generated with AI coding assistance in response to the applicant's request**, with automated and browser-level checks performed as part of the build. The user did not personally write every line in this exchange. Before claiming the project as their own engineering accomplishment, the user should run it, inspect code and results, make at least one meaningful adjustment, and explain trade-offs without relying on memorized buzzwords.

## 8. Quick interview script (after hands-on review)

> “I was interested in Pennant because proxy voting is a nuanced capital-markets workflow, and your Founder Fellow role combines market research with sales experiments. I worked with AI-assisted coding to prototype Governance GTM Lab. It ranks research accounts using transparent inputs, drafts discovery messages for governance personas, compares response-rate experiments, and flags source lines in sample proxy text. I deliberately used fictional leads and didn't pretend the model knows what real buyers want. The next experiment I'd actually run is interviewing proxy and stewardship teams to see whether evidence traceability is a pain point.”

## Sources

- https://www.ycombinator.com/companies/pennant/jobs/21lflHF-founder-fellow-gtm-growth-strategy
- https://www.ycombinator.com/companies/pennant
- https://www.investor.gov/shareholder-voting
- https://www.sec.gov/edgar/search/


## v2 expansion (October 2026)

**New working feature — 14-day founder sprint:** The app now translates each of three ICPs into a stakeholder hypothesis, three discovery questions, and a proposed two-variant outbound test. The user can vary hypothetical list size, reply rate and meeting-per-reply rate; the scenario updates immediately and produces a downloadable Markdown memo with days 1–4, 5–10, 11–14 responsibilities. The outputs are mathematically consistent but are NOT performance predictions.

**New working feature — governance evals:** The app includes eleven educational, hand-labeled positive, negative, ambiguous and multi-label snippets. It evaluates its own deterministic keyword model and displays false-positive and false-negative cases. In this small synthetic set, initial micro precision and recall are both 75.0%; these were generated from deliberately chosen fixtures rather than an independent, representative test set, so they are NOT generalizable model accuracy measures. The errors show why context and negation matter.

**Public-source case:** The Evidence Review tab also offers a *paraphrased agenda summary* from Apple's genuine 2026 DEF 14A, linked directly to the original SEC filing. This is a source-checking exercise, not a complete extraction or a statement about the outcome of Apple's shareholder votes. It is distinct from the completely fictional research accounts and campaign data.

**Quality assurance:** 23 logic checks and 30 Chromium browser checks passed after this upgrade. Their scope is implementation behavior, not buyer validation or model reliability.

**Unchanged integrity limitations:** No real prospect outreach, no Pennant partnership, no real campaign growth data, no autonomous voting advice, and no paid model inference. The project remains an AI-assisted applicant portfolio piece.