# APP DEV-1 verification — 17 November 2026

## Selection and coverage

Original corpus: 1,044 questions and 4,120 options from 46 papers. Retained: **725 questions and 2,877 options**. Removed: **319 repeated variants**, including exact repeats and questions changing only numbers or names without changing the solution pattern.

The mapping MD records each retained source/question/week and each excluded variant with its representative and reason. Distinct logic, edge cases and response methods were retained. Similarity candidates were reviewed rather than automatically discarded.

Final output: 12 PDFs, 766 pages. Week 6 is complete with 62 selected questions and 90 pages.

| Week | Questions | Options | Pages |
|---|---:|---:|---:|
| 1 | 72 | 272 | 47 |
| 2 | 86 | 332 | 99 |
| 3 | 106 | 429 | 132 |
| 4 | 96 | 382 | 97 |
| 5 | 148 | 596 | 161 |
| 6 | 62 | 250 | 90 |
| 7 | 19 | 68 | 19 |
| 8 | 49 | 197 | 41 |
| 9 | 10 | 40 | 10 |
| 10 | 43 | 174 | 42 |
| 11 | 12 | 48 | 10 |
| 12 | 22 | 89 | 18 |

## Verification completed

- Preserved the syllabus correction audit and its 18 reassigned questions. HTML/CSS foundations are Week 2, Jinja/Python formatting Week 3, databases Week 4, and Flask controllers/routing Week 5. Mixed questions are assigned by the tested concept and kept whole.
- Checked every selected source/question reference against its mapped week and verified all option labels, native text and source-answer occurrences.
- Verified staged image assets byte-for-byte, continuous split-image coverage and image placements. Source diagrams, code indentation and image options remain preserved.
- Automated bounds, image, footer and font checks passed on all 766 pages with no reported layout issues.
- Rendered all pages to review sheets; visually sampled all 12 title pages and inspected the latest Week 5 title page at larger size using Poppler.
- Body typography remains Latin Modern Roman, 10.909 PDF points (LaTeX 11pt), matching the supplied reference. Source-image text retains its own typography.
- All PDFs retain double-border week headings, short exam labels and `Shiva(25f1000035)` at bottom right on every page. The unwanted disclaimer is absent.
- Site checks passed for 13 HTML pages, links, anchors, selected counts and 12 PDF targets. JavaScript syntax and simulated desktop/mobile viewer navigation/download/deep-link tests passed.
- All 12 versioned HTTP PDF responses match final local files byte-for-byte. PDF cache version: `4ccdccd2b04c`.

## Limits

- Source answer keys were preserved, not independently solved or certified.
- S04 Q20 has an unclear source math symbol in four options; original visual content is preserved. Its repeated S05 Q21 variant was excluded. Some source screenshots are soft.
- All pages received automated checks; visual inspection was sampled. Real-browser visual/responsive/fullscreen checks were not performed because browser automation was unavailable.
- Pattern equivalence involves judgment; ambiguous questions testing potentially different logic were retained. The mapping retains the reviewed selection and exclusion reasons.
- Site is local, not publicly deployed. Open http://localhost:8003 while the server runs; restart instructions are in README.md.
