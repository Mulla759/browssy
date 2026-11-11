# Browser Agent Research Task: Google TPM Internship Questionnaire and Recruiting Timeline

## Goal
Investigate what happens **after receiving the "Google TPM Summer Questionnaire"** for a **Google Technical Program Manager (TPM) Summer 2027 internship**. The candidate received the questionnaire on **November 8, 2026**. Find verifiable, dated applicant accounts and official Google guidance. Prioritize evidence over generic career advice.

## Central questions
1. Is the questionnaire an initial screening, a project/team-interest survey, or a formal team-matching step? Does its wording or timing distinguish these?
2. How long did **TPM intern** applicants wait between questionnaire receipt/submission and first recruiter contact, interview invitation, team match, and offer/rejection?
3. What rounds follow? Identify reported interview lengths, number of interviews, technical/program-management emphasis, and whether matching occurs before or after interviews.
4. Are November questionnaire recipients likely to interview in November, December, January, or later? What is actually documented versus speculative?
5. Are there Summer 2027-cycle reports as of **2026-11-08**? Compare them with Summer 2026 and Summer 2025 cycles.
6. Are there meaningful differences between **TPM intern**, full-time TPM, SWE intern, STEP, and APM intern pipelines? Do **not** conflate these groups.

## Search strategy
Use a real browser to explore public search results, open individual posts/pages, and follow relevant discussion threads. Search Google, Reddit (especially r/csMajors, r/leetcode, r/GoogleInterns), TeamBlind, Glassdoor, LinkedIn public posts, and official Google Careers / candidate guidance. Try Google/Bing indexed search when a site's native search is weak. Search variations:

- `"Google TPM Summer Questionnaire"`
- `"Google TPM" "Summer Questionnaire"`
- `"Technical Program Manager Intern" "questionnaire" Google`
- `"Google TPM intern" questionnaire interview timeline`
- `"Google TPM" team matching questionnaire 2025 2026`
- `"Google TPM intern" questionnaire reddit`
- `"Google TPM Intern" interview December 2025 January 2026`
- `"Google TPM" "questionnaire" "interview" site:reddit.com`
- `"Google TPM" questionnaire site:teamblind.com`
- `Google Technical Program Manager Intern Summer 2027 recruiting process`
- `Google TPM internship questionnaire how long to hear back`

Also follow **comment replies**, not only the original posts; many useful updates appear weeks later. Expand the query by year, season, and synonyms (`survey`, `project matching`, `candidate questionnaire`, `team preference`, `host matching`). Look for a complete sequence by the **same applicant**. Do not treat repeated cross-posts as independent observations.

## Evidence collection rules
For every relevant applicant account, capture:
- Anonymized handle or post identifier
- Exact source URL (permalink, preferably directly to the comment)
- Original post date and latest update date
- Internship season being discussed (Summer 2025 / 2026 / 2027)
- Whether the position is unambiguously **TPM intern**
- Dates of application, questionnaire received, questionnaire submitted, interview invitation, interviews, team match, and final decision **only when supplied**
- Calculated days between known milestones; mark unknown milestones as `not reported`
- A short supporting quotation (maximum 20 words per source) or careful paraphrase
- Evidence rating: **High** = directly dated firsthand TPM account; **Medium** = credible but incomplete firsthand account; **Low** = secondhand, ambiguous role, or undated
- The distinction between `candidate report`, `official Google information`, and `your inference`

**Important:** Never invent missing dates or infer interview dates solely from a comment's posting date. Separate **application-to-response** from **questionnaire-to-response**. A pending applicant is a censored observation, **not** evidence of an eventual interview or rejection. If a candidate reports "still waiting," report the elapsed minimum wait and do not compute it as a completed interval. Respect logins, access rules, and privacy; do not seek private candidate information.

## Required deliverable: `google-tpm-findings.md`
Organize the findings as follows:

1. **Executive answer** (5-8 sentences): what receiving the questionnaire likely means and a realistic, clearly qualified first-response window for someone who received it 2026-11-08.
2. **Official versus anecdotal**: what Google actually says about the TPM summer process, and what comes only from applicant posts.
3. **Evidence table** with one row per unique applicant: `Cycle | Evidence source/date | Questionnaire date | Next known stage/date | Elapsed time | Status | Confidence | URL`.
4. **Observed timeline**: earliest, longest, and central wait among *completed and sufficiently dated TPM cases*. If sample is tiny or biased, explicitly say a reliable median cannot be estimated. Include the number of cases used.
5. **Process map**: possible stage sequences and where these differ, with source links.
6. **Summer 2027 signals**: verified current-cycle reports, dated as of research day, or state that none were found.
7. **What this means for a Nov 8 recipient**: specific date ranges to monitor (late Nov, Dec, Jan, later), marking each as observed, plausible, or speculative; sensible follow-up timing.
8. **Uncertainties and counterexamples**: delayed/nonresponses, seasonality, team dependence, survivorship bias, and differences from SWE/APM.
9. **Source index** with clickable permalinks, access date, and a note explaining what each source establishes.

## Working method
- Aim for **10+ unique TPM-specific candidate reports** if available, but never pad with unrelated SWE stories. Report the true count found.
- Prefer accounts dated **2025–2026** and public official sources. Use older accounts only for historical context.
- Verify the date when the interview actually happened, not just the date the user posted.
- Flag any evidence or claim that cannot be independently accessed.
- If an exact questionnaire copy is unavailable, state that and explain what wording from the candidate's email would distinguish questionnaire types.
- Give links to the **three most informative threads** at the top of the source index.
- Complete the task by writing the Markdown report to `google-tpm-findings.md`, not just producing a chat summary.
