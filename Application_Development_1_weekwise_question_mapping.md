# Application Development-1: weekwise question mapping

Mapping basis: the supplied `syllabus.md`. The source corpus contains 46 PDFs, 1,044 question entries and 4,120 options. The current PDFs retain **725 representative questions**; **319 repeated variants** are excluded. Original question numbers are retained.

## Assignment rules and overlaps

- Assign by the principal concept being tested, not the exam type or incidental library names.
- Week 2 covers static HTML/CSS and encoding; Week 8 covers forms, browser interaction and JavaScript; Week 11 covers HTML evolution, semantic web and accessibility.
- Week 3 covers standalone view/template and supporting Python-formatting problems. Flask request/routing/template integration belongs to Week 5; SQLAlchemy queries and models belong to Week 4 even inside a Flask program.
- A supplied Flask wrapper does not move a Jinja2 macro, loop, scope or inheritance question out of Week 3 when routing is incidental. Conversely, choosing a route, interpreting request arguments or configuring Flask templates requires Week 5. HTML containing the literal words Flask/SQLAlchemy is still Week 2 when only markup is tested.
- REST/API request construction belongs to Week 6. Generic curl/HTTP/URL/network fundamentals belong to Week 1. Serving HTML files belongs to Week 2. Stateful session/cookie behavior belongs to Week 7; authentication and attacks belong to Week 9.
- Python decorators supporting Flask controllers belong to Week 5. Questions testing url_for URL construction belong to Week 5 even when test_request_context is used merely to print the result. Native HTML5 form-validation exercises belong to Week 8.
- Logging is treated as debugging in Week 10. Git, dependency/virtual-environment management and CI/CD support deployment workflows in Week 12.
- Broad-syllabus interpretations: hardware memory/disk processing supports Backend Systems (Week 7); standalone complexity/performance calculations support Website Performance (Week 1); Python argument handling supporting view programs is grouped with Week 3. These subtopics are not separately named in the supplied syllabus.
- Original code images, diagrams, tables, all options and supplied answer keys are preserved. OCR is a mapping aid and is not substituted for source images in the output.

## Source PDFs

| Source | Short exam heading | Questions | Source file |
|---|---|---:|---|
| S01 | 2024 Sept01 ET | 32 | MAD-1-End-Term-1-Sept-2024-Set-QDF1-Quiz-Space.pdf |
| S02 | 2024 Sept01 ET | 32 | MAD-1-End-Term-1-Sept-2024-Set-QDF3-Quiz-Space.pdf |
| S03 | 2026 May10 ET | 25 | MAD-1-End-Term-10-May-2026-Quiz-Space.pdf |
| S04 | 2022 Dec11 ET | 32 | MAD-1-End-Term-11-Dec-2022-Set-ETD1-2-Quiz-Space.pdf |
| S05 | 2022 Dec11 ET | 32 | MAD-1-End-Term-11-Dec-2022-Set-ETD1-Quiz-Space.pdf |
| S06 | 2025 Apr13 ET | 32 | MAD-1-End-Term-13-Apr-2025-Set-QDD1-Quiz-Space.pdf |
| S07 | 2025 Apr13 ET | 32 | MAD-1-End-Term-13-Apr-2025-Set-QDD3-Quiz-Space.pdf |
| S08 | 2025 Dec21 ET | 21 | MAD-1-End-Term-21-Dec-2025-Quiz-Space.pdf |
| S09 | 2024 Dec22 ET | 32 | MAD-1-End-Term-22-Dec-2024-Quiz-Space.pdf |
| S10 | 2023 Dec24 ET | 32 | MAD-1-End-Term-24-Dec-2023-Set-ADD3-Quiz-Space.pdf |
| S11 | 2023 Dec24 ET | 32 | MAD-1-End-Term-24-Dec-2023-Set-FDD1-Quiz-Space.pdf |
| S12 | 2024 Apr28 ET | 32 | MAD-1-End-Term-28-Apr-2024-Set-QDF1-Quiz-Space.pdf |
| S13 | 2024 Apr28 ET | 32 | MAD-1-End-Term-28-Apr-2024-Set-QDF3-Quiz-Space.pdf |
| S14 | 2022 Apr03 ET | 32 | MAD-1-End-Term-3-Apr-2022-Quiz-Space.pdf |
| S15 | 2023 Sept03 ET | 32 | MAD-1-End-Term-3-Sept-2023-Set-QPD1-S1-Quiz-Space.pdf |
| S16 | 2023 Sept03 ET | 32 | MAD-1-End-Term-3-Sept-2023-Set-QPD1-S2-Quiz-Space.pdf |
| S17 | 2023 Apr30 ET | 32 | MAD-1-End-Term-30-Apr-2023-Set-QPD1-S1-Quiz-Space.pdf |
| S18 | 2023 Apr30 ET | 32 | MAD-1-End-Term-30-Apr-2023-Set-QPD1-S2-Quiz-Space.pdf |
| S19 | 2025 Aug31 ET | 32 | MAD-1-End-Term-31-Aug-2025-Set-QDB3-Quiz-Space.pdf |
| S20 | 2025 Aug31 ET | 32 | MAD-1-End-Term-31-Aug-2025-Set-QDD1-Quiz-Space.pdf |
| S21 | 2022 Aug07 ET | 32 | MAD-1-End-Term-7-Aug-2022-Quiz-Space.pdf |
| S22 | 2025 July13 Quiz-1 | 16 | MAD-1-Quiz-1-13-Jul-2025-Quiz-Space.pdf |
| S23 | 2026 Mar15 Quiz-1 | 15 | MAD-1-Quiz-1-15-Mar-2026-Quiz-Space.pdf |
| S24 | 2023 July16 Quiz-1 | 16 | MAD-1-Quiz-1-16-Jul-2023-Quiz-Space.pdf |
| S25 | 2022 Oct16 Quiz-1 | 17 | MAD-1-Quiz-1-16-Oct-2022-Quiz-Space.pdf |
| S26 | 2026 July19 Quiz-1 | 13 | MAD-1-Quiz-1-19-Jul-2026-Set-1-2-Quiz-Space.pdf |
| S27 | 2026 July19 Quiz-1 | 13 | MAD-1-Quiz-1-19-Jul-2026-Set-1-Quiz-Space.pdf |
| S28 | 2025 Feb23 Quiz-1 | 16 | MAD-1-Quiz-1-23-Feb-2025-Quiz-Space.pdf |
| S29 | 2024 Feb25 Quiz-1 | 16 | MAD-1-Quiz-1-25-Feb-2024-Quiz-Space.pdf |
| S30 | 2023 Feb26 Quiz-1 | 16 | MAD-1-Quiz-1-26-Feb-2023-Quiz-Space.pdf |
| S31 | 2025 Oct26 Quiz-1 | 16 | MAD-1-Quiz-1-26-Oct-2025-Quiz-Space.pdf |
| S32 | 2024 Oct27 Quiz-1 | 16 | MAD-1-Quiz-1-27-Oct-2024-Quiz-Space.pdf |
| S33 | 2023 Oct29 Quiz-1 | 16 | MAD-1-Quiz-1-29-Oct-2023-Quiz-Space.pdf |
| S34 | 2022 Jun05 Quiz-1 | 16 | MAD-1-Quiz-1-5-Jun-2022-Quiz-Space.pdf |
| S35 | 2024 July07 Quiz-1 | 16 | MAD-1-Quiz-1-7-Jul-2024-Quiz-Space.pdf |
| S36 | 2024 Dec01 Quiz-2 | 16 | MAD-1-Quiz-2-1-Dec-2024-Quiz-Space.pdf |
| S37 | 2022 July10 Quiz-2 | 16 | MAD-1-Quiz-2-10-Jul-2022-Quiz-Space.pdf |
| S38 | 2026 Apr12 Quiz-2 | 15 | MAD-1-Quiz-2-12-Apr-2026-Quiz-Space.pdf |
| S39 | 2026 Aug16 Quiz-2 | 13 | MAD-1-Quiz-2-16-Aug-2026-Quiz-Space.pdf |
| S40 | 2025 Mar16 Quiz-2 | 16 | MAD-1-Quiz-2-16-Mar-2025-Quiz-Space.pdf |
| S41 | 2025 Nov23 Quiz-2 | 16 | MAD-1-Quiz-2-23-Nov-2025-Quiz-Space.pdf |
| S42 | 2024 Mar24 Quiz-2 | 16 | MAD-1-Quiz-2-24-Mar-2024-Quiz-Space.pdf |
| S43 | 2025 Aug03 Quiz-2 | 16 | MAD-1-Quiz-2-3-Aug-2025-Quiz-Space.pdf |
| S44 | 2023 Dec03 Quiz-2 | 16 | MAD-1-Quiz-2-3-Dec-2023-Quiz-Space.pdf |
| S45 | 2024 Aug04 Quiz-2 | 16 | MAD-1-Quiz-2-4-Aug-2024-Quiz-Space.pdf |
| S46 | 2023 Aug06 Quiz-2 | 16 | MAD-1-Quiz-2-6-Aug-2023-Quiz-Space.pdf |

## Syllabus correction audit — 16 November 2026

Mixed-topic questions remain complete and appear once, under the concept needed to answer them. Incidental framework names do not determine the week.

| Source/question | Previous week | Corrected week | Reason |
|---|---:|---:|---|
| S02 Q20 | 1 | 2 | Serving HTML files and selecting the default HTML document: explicit Week 2 syllabus coverage. |
| S04 Q7 | 1 | 2 | Serving HTML files and selecting the default HTML document: explicit Week 2 syllabus coverage. |
| S05 Q14 | 1 | 2 | Serving HTML files and selecting the default HTML document: explicit Week 2 syllabus coverage. |
| S29 Q3 | 1 | 2 | Serving HTML files and selecting the default HTML document: explicit Week 2 syllabus coverage. |
| S32 Q6 | 1 | 2 | Serving HTML files and selecting the default HTML document: explicit Week 2 syllabus coverage. |
| S03 Q1 | 1 | 5 | Mixed matching question includes HTML and Flask @app.route decorators; requires controller knowledge beyond web foundations. |
| S04 Q8 | 1 | 6 | Mixed API/MVC/routing/stateless matching: API concepts are explicitly introduced in Week 6. |
| S05 Q15 | 1 | 6 | Mixed API/MVC/routing/stateless matching: API concepts are explicitly introduced in Week 6. |
| S09 Q12 | 3 | 4 | Determining the rendered result requires SQLAlchemy filter_by query selection; template loop alone is insufficient. |
| S17 Q8 | 3 | 4 | Determining the rendered result requires SQLAlchemy filter_by query selection; template loop alone is insufficient. |
| S18 Q16 | 3 | 4 | Determining the rendered result requires SQLAlchemy filter_by query selection; template loop alone is insufficient. |
| S21 Q5 | 3 | 5 | Tests Flask route matching, trailing slashes and url_for alongside template rendering. |
| S10 Q9 | 6 | 1 | Generic curl/HTTP request methods and headers, with no REST resource or API implementation being tested. |
| S11 Q4 | 6 | 1 | Generic curl/HTTP request methods and headers, with no REST resource or API implementation being tested. |
| S23 Q9 | 6 | 1 | Generic curl/HTTP request methods and headers, with no REST resource or API implementation being tested. |
| S28 Q2 | 6 | 1 | Generic curl/HTTP request methods and headers, with no REST resource or API implementation being tested. |
| S21 Q18 | 7 | 1 | Network bandwidth and response size determine website request throughput; hardware specifications are incidental. |
| S25 Q10 | 8 | 2 | Tests CSS selector specificity before and after a stated class removal; no JavaScript implementation is required. |

## Week counts

| Week | Topic | Questions |
|---|---|---:|
| 1 | Web foundations and performance | 72 |
| 2 | HTML, CSS and information representation | 86 |
| 3 | Presentation layer and Jinja2 | 106 |
| 4 | Databases and SQLAlchemy models | 96 |
| 5 | Flask controllers and routing | 148 |
| 6 | APIs and REST | 62 |
| 7 | Backend systems and application state | 19 |
| 8 | Application frontend and interaction | 49 |
| 9 | Application security | 10 |
| 10 | Testing and debugging | 43 |
| 11 | HTML evolution and accessibility | 12 |
| 12 | Deployment and production workflows | 22 |

## Week 1: Web foundations and performance

Syllabus coverage: Client-server/P2P architecture, MVC and protocols; URLs, networks, bandwidth and latency; Application and algorithm performance.

| Source | Original question | PDF pages | Assignment basis |
|---|---:|---|---|
| S01 | 14 | 16 | Web foundations and performance |
| S01 | 16 | 18 | Web foundations and performance |
| S01 | 22 | 23 | Web foundations and performance |
| S02 | 9 | 7, 8 | Web foundations and performance |
| S02 | 31 | 32, 33 | Web foundations and performance |
| S03 | 3 | 2 | Web foundations and performance |
| S03 | 10 | 6, 7 | Web foundations and performance |
| S04 | 1 | 1 | Web foundations and performance |
| S04 | 20 | 15 | Web foundations and performance |
| S04 | 31 | 28, 29 | Web foundations and performance |
| S04 | 32 | 29, 30 | Web foundations and performance |
| S06 | 8 | 8 | Web foundations and performance |
| S06 | 10 | 9 | Web foundations and performance |
| S06 | 19 | 17, 18 | Web foundations and performance |
| S06 | 22 | 21 | Web foundations and performance |
| S07 | 2 | 1 | Web foundations and performance |
| S07 | 5 | 3 | Web foundations and performance |
| S07 | 19 | 16, 17 | Web foundations and performance |
| S09 | 5 | 4 | Web foundations and performance |
| S09 | 7 | 5, 6 | Web foundations and performance |
| S09 | 26 | 24 | Web foundations and performance |
| S10 | 4 | 4 | Web foundations and performance |
| S10 | 9 | 8 | Generic curl/HTTP request methods and headers, with no REST resource or API implementation being tested. |
| S10 | 29 | 27, 28 | Web foundations and performance |
| S10 | 30 | 28 | Web foundations and performance |
| S10 | 31 | 29 | Web foundations and performance |
| S10 | 32 | 29 | Web foundations and performance |
| S11 | 4 | 3, 4 | Generic curl/HTTP request methods and headers, with no REST resource or API implementation being tested. |
| S12 | 27 | 26, 27 | Web foundations and performance |
| S12 | 28 | 27 | Web foundations and performance |
| S14 | 18 | 17, 18 | Web foundations and performance |
| S14 | 21 | 21, 22 | Web foundations and performance |
| S14 | 32 | 34 | Web foundations and performance |
| S15 | 1 | 1 | Web foundations and performance |
| S15 | 2 | 1, 2 | Web foundations and performance |
| S15 | 6 | 3, 4 | Web foundations and performance |
| S15 | 23 | 20, 21 | Web foundations and performance |
| S15 | 32 | 29 | Web foundations and performance |
| S16 | 24 | 21 | Web foundations and performance |
| S17 | 3 | 2 | Web foundations and performance |
| S18 | 26 | 21 | Web foundations and performance |
| S19 | 13 | 10 | Web foundations and performance |
| S21 | 11 | 18 | Web foundations and performance |
| S21 | 18 | 26 | Network bandwidth and response size determine website request throughput; hardware specifications are incidental. |
| S22 | 10 | 10 | Web foundations and performance |
| S22 | 11 | 10 | Web foundations and performance |
| S23 | 9 | 8 | Generic curl/HTTP request methods and headers, with no REST resource or API implementation being tested. |
| S23 | 11 | 9 | Web foundations and performance |
| S24 | 1 | 1 | Web foundations and performance |
| S24 | 9 | 7 | Web foundations and performance |
| S25 | 9 | 10, 11 | Web foundations and performance |
| S26 | 11 | 9 | Web foundations and performance |
| S28 | 10 | 9, 10 | Web foundations and performance |
| S28 | 12 | 12, 13 | Web foundations and performance |
| S29 | 7 | 8 | Web foundations and performance |
| S30 | 11 | 7, 8 | Web foundations and performance |
| S30 | 16 | 12 | Web foundations and performance |
| S31 | 11 | 10 | Web foundations and performance |
| S32 | 1 | 1 | Web foundations and performance |
| S32 | 11 | 10 | Web foundations and performance |
| S32 | 12 | 10, 11 | Web foundations and performance |
| S33 | 8 | 7 | Web foundations and performance |
| S34 | 1 | 1 | Web foundations and performance |
| S34 | 11 | 13 | Web foundations and performance |
| S35 | 2 | 1 | Web foundations and performance |
| S35 | 5 | 3 | Web foundations and performance |
| S35 | 12 | 10 | Web foundations and performance |
| S37 | 15 | 18, 19 | Web foundations and performance |
| S38 | 6 | 3, 4 | Web foundations and performance |
| S40 | 3 | 2 | Web foundations and performance |
| S41 | 12 | 9 | Web foundations and performance |
| S45 | 1 | 1 | Web foundations and performance |

## Week 2: HTML, CSS and information representation

Syllabus coverage: HTML structure and CSS selectors/cascade/layout; Markup and information representation; Character encodings and number representations.

| Source | Original question | PDF pages | Assignment basis |
|---|---:|---|---|
| S01 | 2 | 2, 3 | HTML, CSS and information representation |
| S01 | 12 | 14, 15 | HTML, CSS and information representation |
| S01 | 21 | 22, 23 | HTML, CSS and information representation |
| S02 | 2 | 1 | HTML, CSS and information representation |
| S02 | 8 | 6, 7 | HTML, CSS and information representation |
| S02 | 10 | 8 | HTML, CSS and information representation |
| S02 | 20 | 21, 22 | Serving HTML files and selecting the default HTML document: explicit Week 2 syllabus coverage. |
| S03 | 8 | 5 | HTML, CSS and information representation |
| S03 | 14 | 9 | HTML, CSS and information representation |
| S04 | 3 | 3 | HTML, CSS and information representation |
| S04 | 23 | 18 | HTML, CSS and information representation |
| S05 | 14 | 11, 12 | Serving HTML files and selecting the default HTML document: explicit Week 2 syllabus coverage. |
| S06 | 7 | 6, 7 | HTML, CSS and information representation |
| S06 | 9 | 8, 9 | HTML, CSS and information representation |
| S07 | 9 | 6, 7 | HTML, CSS and information representation |
| S09 | 15 | 13, 14, 15 | HTML, CSS and information representation |
| S09 | 24 | 23, 24 | HTML, CSS and information representation |
| S09 | 25 | 24 | HTML, CSS and information representation |
| S10 | 2 | 2, 3 | HTML, CSS and information representation |
| S10 | 10 | 8 | HTML, CSS and information representation |
| S10 | 26 | 23, 24, 25 | HTML, CSS and information representation |
| S11 | 12 | 8, 9, 10 | HTML, CSS and information representation |
| S12 | 17 | 15, 16 | HTML, CSS and information representation |
| S12 | 23 | 22, 23, 24 | HTML, CSS and information representation |
| S14 | 1 | 1 | HTML, CSS and information representation |
| S14 | 2 | 1 | HTML, CSS and information representation |
| S14 | 3 | 2 | HTML, CSS and information representation |
| S14 | 13 | 11, 12 | HTML, CSS and information representation |
| S14 | 19 | 18, 19 | HTML, CSS and information representation |
| S15 | 11 | 8, 9 | HTML, CSS and information representation |
| S15 | 12 | 9, 10 | HTML, CSS and information representation |
| S16 | 6 | 6, 7, 8 | HTML, CSS and information representation |
| S17 | 10 | 8, 9, 10 | HTML, CSS and information representation |
| S17 | 11 | 10, 11, 12 | HTML, CSS and information representation |
| S17 | 16 | 16, 17 | HTML, CSS and information representation |
| S17 | 17 | 17, 18 | HTML, CSS and information representation |
| S18 | 1 | 1 | HTML, CSS and information representation |
| S18 | 25 | 20, 21 | HTML, CSS and information representation |
| S19 | 15 | 11, 12 | HTML, CSS and information representation |
| S20 | 11 | 7 | HTML, CSS and information representation |
| S20 | 14 | 9, 10 | HTML, CSS and information representation |
| S21 | 6 | 10, 11 | HTML, CSS and information representation |
| S21 | 7 | 11, 12, 13 | HTML, CSS and information representation |
| S21 | 21 | 31 | HTML, CSS and information representation |
| S21 | 28 | 37, 38, 39, 40 | HTML, CSS and information representation |
| S22 | 1 | 1, 2 | HTML, CSS and information representation |
| S22 | 3 | 3, 4 | HTML, CSS and information representation |
| S22 | 7 | 7 | HTML, CSS and information representation |
| S23 | 2 | 1, 2, 3 | HTML, CSS and information representation |
| S23 | 10 | 8, 9 | HTML, CSS and information representation |
| S23 | 13 | 9, 10 | HTML, CSS and information representation |
| S23 | 14 | 10 | HTML, CSS and information representation |
| S24 | 2 | 1, 2 | HTML, CSS and information representation |
| S24 | 10 | 7, 8, 9 | HTML, CSS and information representation |
| S24 | 13 | 12, 13, 14 | HTML, CSS and information representation |
| S25 | 5 | 4, 5, 6 | HTML, CSS and information representation |
| S25 | 7 | 8, 9 | HTML, CSS and information representation |
| S25 | 10 | 11, 12 | Tests CSS selector specificity before and after a stated class removal; no JavaScript implementation is required. |
| S25 | 13 | 15 | HTML, CSS and information representation |
| S26 | 1 | 1 | HTML, CSS and information representation |
| S28 | 1 | 1 | HTML, CSS and information representation |
| S28 | 5 | 3, 4, 5 | HTML, CSS and information representation |
| S28 | 6 | 5 | HTML, CSS and information representation |
| S28 | 13 | 13 | HTML, CSS and information representation |
| S29 | 1 | 1, 2 | HTML, CSS and information representation |
| S29 | 4 | 4, 5 | HTML, CSS and information representation |
| S29 | 9 | 9, 10 | HTML, CSS and information representation |
| S29 | 11 | 11, 12 | HTML, CSS and information representation |
| S30 | 3 | 2, 3 | HTML, CSS and information representation |
| S30 | 7 | 6 | HTML, CSS and information representation |
| S30 | 9 | 6, 7 | HTML, CSS and information representation |
| S31 | 3 | 2, 3 | HTML, CSS and information representation |
| S31 | 9 | 7, 8 | HTML, CSS and information representation |
| S31 | 12 | 10, 11 | HTML, CSS and information representation |
| S32 | 3 | 2, 3 | HTML, CSS and information representation |
| S33 | 3 | 2, 3 | HTML, CSS and information representation |
| S33 | 7 | 6, 7 | HTML, CSS and information representation |
| S33 | 15 | 12, 13, 14 | HTML, CSS and information representation |
| S34 | 3 | 1, 2 | HTML, CSS and information representation |
| S34 | 4 | 2, 3 | HTML, CSS and information representation |
| S34 | 5 | 3, 4, 5 | HTML, CSS and information representation |
| S35 | 6 | 3, 4 | HTML, CSS and information representation |
| S35 | 11 | 8, 9, 10 | HTML, CSS and information representation |
| S37 | 13 | 15, 16 | HTML, CSS and information representation |
| S38 | 7 | 4, 5 | HTML, CSS and information representation |
| S39 | 4 | 3 | HTML, CSS and information representation |

## Week 3: Presentation layer and Jinja2

Syllabus coverage: Python formatting and command-line inputs supporting views; Jinja2 expressions, filters, loops and inheritance; Dynamic HTML generation.

| Source | Original question | PDF pages | Assignment basis |
|---|---:|---|---|
| S01 | 1 | 1, 2 | Presentation layer and Jinja2 |
| S01 | 17 | 18, 19, 20 | Presentation layer and Jinja2 |
| S01 | 19 | 21, 22 | Presentation layer and Jinja2 |
| S01 | 23 | 23, 24 | Presentation layer and Jinja2 |
| S02 | 4 | 2, 3 | Presentation layer and Jinja2 |
| S03 | 12 | 7, 8 | Presentation layer and Jinja2 |
| S03 | 22 | 14, 15 | Presentation layer and Jinja2 |
| S04 | 4 | 3, 4 | Presentation layer and Jinja2 |
| S04 | 11 | 9, 10 | Presentation layer and Jinja2 |
| S04 | 19 | 14, 15 | Presentation layer and Jinja2 |
| S04 | 24 | 18, 19 | Presentation layer and Jinja2 |
| S04 | 25 | 19, 20 | Presentation layer and Jinja2 |
| S05 | 11 | 8, 9 | Presentation layer and Jinja2 |
| S06 | 1 | 1 | Presentation layer and Jinja2 |
| S06 | 2 | 1, 2 | Presentation layer and Jinja2 |
| S06 | 17 | 15, 16 | Presentation layer and Jinja2 |
| S06 | 21 | 19, 20, 21 | Presentation layer and Jinja2 |
| S07 | 20 | 17, 18 | Presentation layer and Jinja2 |
| S08 | 1 | 1, 2 | Presentation layer and Jinja2 |
| S08 | 2 | 2, 3 | Presentation layer and Jinja2 |
| S09 | 3 | 3 | Presentation layer and Jinja2 |
| S09 | 14 | 12, 13 | Presentation layer and Jinja2 |
| S09 | 17 | 17 | Presentation layer and Jinja2 |
| S10 | 11 | 8, 9 | Presentation layer and Jinja2 |
| S10 | 16 | 11, 12 | Presentation layer and Jinja2 |
| S10 | 17 | 13, 14, 15 | Presentation layer and Jinja2 |
| S11 | 5 | 4 | Presentation layer and Jinja2 |
| S12 | 1 | 1, 2 | Presentation layer and Jinja2 |
| S12 | 16 | 14, 15 | Presentation layer and Jinja2 |
| S12 | 26 | 25, 26 | Presentation layer and Jinja2 |
| S12 | 31 | 30, 31 | Presentation layer and Jinja2 |
| S13 | 31 | 30, 31 | Presentation layer and Jinja2 |
| S14 | 6 | 3, 4, 5 | Presentation layer and Jinja2 |
| S14 | 17 | 16, 17 | Presentation layer and Jinja2 |
| S14 | 20 | 19, 20, 21 | Presentation layer and Jinja2 |
| S14 | 22 | 22, 23 | Presentation layer and Jinja2 |
| S14 | 25 | 26, 27 | Presentation layer and Jinja2 |
| S14 | 26 | 27, 28, 29 | Presentation layer and Jinja2 |
| S15 | 9 | 6, 7 | Presentation layer and Jinja2 |
| S15 | 13 | 10, 11 | Presentation layer and Jinja2 |
| S15 | 14 | 11, 12 | Presentation layer and Jinja2 |
| S15 | 28 | 24, 25, 26 | Presentation layer and Jinja2 |
| S17 | 5 | 3, 4 | Presentation layer and Jinja2 |
| S17 | 23 | 23, 24, 25 | Presentation layer and Jinja2 |
| S18 | 11 | 7, 8 | Presentation layer and Jinja2 |
| S18 | 27 | 21, 22, 23 | Presentation layer and Jinja2 |
| S19 | 9 | 6, 7 | Presentation layer and Jinja2 |
| S19 | 12 | 9 | Presentation layer and Jinja2 |
| S19 | 21 | 17, 18 | Presentation layer and Jinja2 |
| S20 | 17 | 11, 12, 13 | Presentation layer and Jinja2 |
| S21 | 2 | 2, 3, 4 | Presentation layer and Jinja2 |
| S21 | 9 | 14, 15, 16 | Presentation layer and Jinja2 |
| S21 | 16 | 23, 24, 25 | Presentation layer and Jinja2 |
| S21 | 17 | 25 | Presentation layer and Jinja2 |
| S21 | 25 | 34, 35 | Presentation layer and Jinja2 |
| S22 | 4 | 4, 5 | Presentation layer and Jinja2 |
| S22 | 5 | 5, 6 | Presentation layer and Jinja2 |
| S22 | 8 | 7, 8, 9 | Presentation layer and Jinja2 |
| S22 | 9 | 9, 10 | Presentation layer and Jinja2 |
| S22 | 12 | 11, 12 | Presentation layer and Jinja2 |
| S22 | 14 | 13, 14 | Presentation layer and Jinja2 |
| S23 | 5 | 4, 5 | Presentation layer and Jinja2 |
| S23 | 6 | 5, 6 | Presentation layer and Jinja2 |
| S23 | 7 | 6, 7 | Presentation layer and Jinja2 |
| S23 | 12 | 9 | Presentation layer and Jinja2 |
| S23 | 15 | 10, 11 | Presentation layer and Jinja2 |
| S24 | 7 | 4, 5 | Presentation layer and Jinja2 |
| S24 | 12 | 11 | Presentation layer and Jinja2 |
| S24 | 14 | 14, 15 | Presentation layer and Jinja2 |
| S25 | 4 | 3, 4 | Presentation layer and Jinja2 |
| S25 | 12 | 13, 14 | Presentation layer and Jinja2 |
| S25 | 14 | 15, 16, 17 | Presentation layer and Jinja2 |
| S26 | 7 | 6, 7 | Presentation layer and Jinja2 |
| S26 | 13 | 10, 11 | Presentation layer and Jinja2 |
| S28 | 7 | 6, 7, 8 | Presentation layer and Jinja2 |
| S28 | 8 | 8, 9 | Presentation layer and Jinja2 |
| S28 | 14 | 14, 15 | Presentation layer and Jinja2 |
| S28 | 15 | 15, 16 | Presentation layer and Jinja2 |
| S28 | 16 | 17 | Presentation layer and Jinja2 |
| S29 | 5 | 5, 6 | Presentation layer and Jinja2 |
| S29 | 6 | 7, 8 | Presentation layer and Jinja2 |
| S29 | 10 | 11 | Presentation layer and Jinja2 |
| S30 | 5 | 4 | Presentation layer and Jinja2 |
| S30 | 10 | 7 | Presentation layer and Jinja2 |
| S31 | 1 | 1 | Presentation layer and Jinja2 |
| S31 | 5 | 4, 5 | Presentation layer and Jinja2 |
| S31 | 6 | 5 | Presentation layer and Jinja2 |
| S31 | 7 | 5, 6 | Presentation layer and Jinja2 |
| S32 | 4 | 3, 4 | Presentation layer and Jinja2 |
| S32 | 7 | 7 | Presentation layer and Jinja2 |
| S33 | 5 | 5 | Presentation layer and Jinja2 |
| S33 | 10 | 8, 9 | Presentation layer and Jinja2 |
| S33 | 14 | 12 | Presentation layer and Jinja2 |
| S34 | 6 | 5, 6 | Presentation layer and Jinja2 |
| S34 | 7 | 6, 7, 8, 9 | Presentation layer and Jinja2 |
| S34 | 10 | 11, 12 | Presentation layer and Jinja2 |
| S34 | 14 | 15, 16, 17 | Presentation layer and Jinja2 |
| S34 | 15 | 17, 18, 19 | Presentation layer and Jinja2 |
| S35 | 3 | 2 | Presentation layer and Jinja2 |
| S35 | 10 | 7, 8 | Presentation layer and Jinja2 |
| S37 | 6 | 7, 8, 9 | Presentation layer and Jinja2 |
| S37 | 14 | 16, 17, 18 | Presentation layer and Jinja2 |
| S39 | 5 | 3, 4 | Presentation layer and Jinja2 |
| S40 | 5 | 3, 4 | Presentation layer and Jinja2 |
| S42 | 6 | 4, 5 | Presentation layer and Jinja2 |
| S44 | 6 | 6 | Presentation layer and Jinja2 |

## Week 4: Databases and SQLAlchemy models

Syllabus coverage: SQLite, SQL and database design; SQLAlchemy models, keys and relationships; Queries, transactions, indexing and migrations.

| Source | Original question | PDF pages | Assignment basis |
|---|---:|---|---|
| S01 | 15 | 17, 18 | Databases and SQLAlchemy models |
| S01 | 26 | 26, 27, 28 | Databases and SQLAlchemy models |
| S02 | 26 | 27 | Databases and SQLAlchemy models |
| S02 | 27 | 27, 28 | Databases and SQLAlchemy models |
| S03 | 4 | 2 | Databases and SQLAlchemy models |
| S03 | 9 | 5, 6 | Databases and SQLAlchemy models |
| S04 | 15 | 11, 12 | Databases and SQLAlchemy models |
| S04 | 17 | 13 | Databases and SQLAlchemy models |
| S04 | 22 | 17, 18 | Databases and SQLAlchemy models |
| S04 | 26 | 20, 21 | Databases and SQLAlchemy models |
| S04 | 27 | 21, 22, 23 | Databases and SQLAlchemy models |
| S05 | 19 | 14, 15 | Databases and SQLAlchemy models |
| S05 | 23 | 18, 19, 20 | Databases and SQLAlchemy models |
| S06 | 4 | 3, 4 | Databases and SQLAlchemy models |
| S06 | 31 | 30, 31 | Databases and SQLAlchemy models |
| S06 | 32 | 31, 32 | Databases and SQLAlchemy models |
| S07 | 7 | 4, 5 | Databases and SQLAlchemy models |
| S07 | 15 | 12, 13 | Databases and SQLAlchemy models |
| S07 | 27 | 25, 26 | Databases and SQLAlchemy models |
| S07 | 28 | 26, 27 | Databases and SQLAlchemy models |
| S08 | 10 | 9, 10 | Databases and SQLAlchemy models |
| S09 | 1 | 1 | Databases and SQLAlchemy models |
| S09 | 4 | 4 | Databases and SQLAlchemy models |
| S09 | 12 | 9, 10, 11 | Determining the rendered result requires SQLAlchemy filter_by query selection; template loop alone is insufficient. |
| S09 | 23 | 22, 23 | Databases and SQLAlchemy models |
| S10 | 15 | 10, 11 | Databases and SQLAlchemy models |
| S10 | 23 | 21 | Databases and SQLAlchemy models |
| S10 | 24 | 21, 22 | Databases and SQLAlchemy models |
| S11 | 6 | 4 | Databases and SQLAlchemy models |
| S11 | 15 | 12, 13 | Databases and SQLAlchemy models |
| S12 | 8 | 6 | Databases and SQLAlchemy models |
| S12 | 9 | 7 | Databases and SQLAlchemy models |
| S12 | 18 | 16 | Databases and SQLAlchemy models |
| S12 | 25 | 25 | Databases and SQLAlchemy models |
| S13 | 17 | 14 | Databases and SQLAlchemy models |
| S14 | 12 | 10, 11 | Databases and SQLAlchemy models |
| S14 | 23 | 23, 24, 25 | Databases and SQLAlchemy models |
| S14 | 24 | 25, 26 | Databases and SQLAlchemy models |
| S15 | 3 | 2 | Databases and SQLAlchemy models |
| S15 | 19 | 16, 17 | Databases and SQLAlchemy models |
| S15 | 21 | 18, 19 | Databases and SQLAlchemy models |
| S16 | 7 | 8 | Databases and SQLAlchemy models |
| S17 | 12 | 12, 13 | Databases and SQLAlchemy models |
| S17 | 14 | 14, 15, 16 | Databases and SQLAlchemy models |
| S17 | 29 | 32, 33 | Databases and SQLAlchemy models |
| S17 | 30 | 33, 34 | Databases and SQLAlchemy models |
| S18 | 20 | 15, 16 | Databases and SQLAlchemy models |
| S19 | 1 | 1 | Databases and SQLAlchemy models |
| S19 | 2 | 1, 2 | Databases and SQLAlchemy models |
| S19 | 14 | 10, 11 | Databases and SQLAlchemy models |
| S20 | 28 | 24, 25 | Databases and SQLAlchemy models |
| S21 | 4 | 6, 7 | Databases and SQLAlchemy models |
| S21 | 29 | 40, 41 | Databases and SQLAlchemy models |
| S21 | 30 | 42 | Databases and SQLAlchemy models |
| S25 | 2 | 1, 2 | Databases and SQLAlchemy models |
| S25 | 8 | 9, 10 | Databases and SQLAlchemy models |
| S25 | 15 | 17, 18 | Databases and SQLAlchemy models |
| S25 | 16 | 18, 19, 20 | Databases and SQLAlchemy models |
| S25 | 17 | 20, 21, 22 | Databases and SQLAlchemy models |
| S28 | 4 | 3 | Databases and SQLAlchemy models |
| S28 | 11 | 10, 11, 12 | Databases and SQLAlchemy models |
| S29 | 14 | 14 | Databases and SQLAlchemy models |
| S30 | 6 | 5 | Databases and SQLAlchemy models |
| S30 | 12 | 8, 9 | Databases and SQLAlchemy models |
| S30 | 15 | 11, 12 | Databases and SQLAlchemy models |
| S33 | 13 | 11 | Databases and SQLAlchemy models |
| S34 | 8 | 9, 10 | Databases and SQLAlchemy models |
| S35 | 4 | 2, 3 | Databases and SQLAlchemy models |
| S35 | 14 | 12 | Databases and SQLAlchemy models |
| S36 | 2 | 1, 2, 3 | Databases and SQLAlchemy models |
| S36 | 10 | 11, 12 | Databases and SQLAlchemy models |
| S37 | 3 | 4, 5 | Databases and SQLAlchemy models |
| S37 | 4 | 5, 6 | Databases and SQLAlchemy models |
| S37 | 5 | 6, 7 | Databases and SQLAlchemy models |
| S37 | 7 | 9, 10, 11 | Databases and SQLAlchemy models |
| S37 | 11 | 13, 14 | Databases and SQLAlchemy models |
| S38 | 1 | 1 | Databases and SQLAlchemy models |
| S38 | 14 | 9, 10 | Databases and SQLAlchemy models |
| S38 | 15 | 10, 11 | Databases and SQLAlchemy models |
| S40 | 1 | 1 | Databases and SQLAlchemy models |
| S40 | 13 | 11, 12 | Databases and SQLAlchemy models |
| S41 | 8 | 6 | Databases and SQLAlchemy models |
| S41 | 9 | 6, 7 | Databases and SQLAlchemy models |
| S41 | 16 | 11, 12 | Databases and SQLAlchemy models |
| S42 | 8 | 6, 7 | Databases and SQLAlchemy models |
| S42 | 14 | 13, 14 | Databases and SQLAlchemy models |
| S43 | 3 | 2 | Databases and SQLAlchemy models |
| S43 | 12 | 10 | Databases and SQLAlchemy models |
| S43 | 15 | 12, 13 | Databases and SQLAlchemy models |
| S43 | 16 | 14, 15 | Databases and SQLAlchemy models |
| S44 | 5 | 6 | Databases and SQLAlchemy models |
| S44 | 9 | 8, 9 | Databases and SQLAlchemy models |
| S44 | 11 | 11, 12, 13 | Databases and SQLAlchemy models |
| S45 | 2 | 1, 2 | Databases and SQLAlchemy models |
| S45 | 4 | 3, 4, 5 | Databases and SQLAlchemy models |
| S45 | 13 | 14, 15, 16 | Databases and SQLAlchemy models |

## Week 5: Flask controllers and routing

Syllabus coverage: Flask application setup and routes; HTTP request/response handling and redirects; Connecting templates and models to controllers.

| Source | Original question | PDF pages | Assignment basis |
|---|---:|---|---|
| S01 | 3 | 3, 4 | Flask controllers and routing |
| S01 | 4 | 4, 5 | Flask controllers and routing |
| S01 | 10 | 12, 13, 14 | Flask controllers and routing |
| S01 | 24 | 24, 25 | Flask controllers and routing |
| S01 | 25 | 25, 26 | Flask controllers and routing |
| S01 | 27 | 28, 29 | Flask controllers and routing |
| S01 | 29 | 31, 32 | Flask controllers and routing |
| S01 | 30 | 32, 33 | Flask controllers and routing |
| S01 | 31 | 33, 34, 35 | Flask controllers and routing |
| S01 | 32 | 35, 36 | Flask controllers and routing |
| S03 | 1 | 1 | Mixed matching question includes HTML and Flask @app.route decorators; requires controller knowledge beyond web foundations. |
| S03 | 6 | 3, 4 | Flask controllers and routing |
| S03 | 7 | 4, 5 | Flask controllers and routing |
| S03 | 16 | 10, 11 | Flask controllers and routing |
| S03 | 17 | 11, 12 | Flask controllers and routing |
| S03 | 23 | 15, 16 | Flask controllers and routing |
| S03 | 25 | 16, 17 | Flask controllers and routing |
| S04 | 5 | 4, 5 | Flask controllers and routing |
| S04 | 12 | 10 | Flask controllers and routing |
| S04 | 13 | 10, 11 | Flask controllers and routing |
| S04 | 21 | 15, 16, 17 | Flask controllers and routing |
| S05 | 5 | 4, 5 | Flask controllers and routing |
| S06 | 6 | 5, 6 | Flask controllers and routing |
| S06 | 11 | 9, 10 | Flask controllers and routing |
| S06 | 15 | 13, 14 | Flask controllers and routing |
| S06 | 20 | 18, 19 | Flask controllers and routing |
| S06 | 26 | 25, 26 | Flask controllers and routing |
| S06 | 27 | 26, 27 | Flask controllers and routing |
| S06 | 28 | 28 | Flask controllers and routing |
| S08 | 3 | 3, 4 | Flask controllers and routing |
| S09 | 6 | 4, 5 | Flask controllers and routing |
| S09 | 13 | 11, 12 | Flask controllers and routing |
| S09 | 18 | 17, 18 | Flask controllers and routing |
| S09 | 20 | 20, 21 | Flask controllers and routing |
| S09 | 27 | 24, 25 | Flask controllers and routing |
| S09 | 28 | 26, 27 | Flask controllers and routing |
| S10 | 21 | 19 | Flask controllers and routing |
| S10 | 22 | 20, 21 | Flask controllers and routing |
| S10 | 27 | 25, 26 | Flask controllers and routing |
| S11 | 17 | 13, 14 | Flask controllers and routing |
| S11 | 24 | 23, 24 | Flask controllers and routing |
| S11 | 27 | 27, 28 | Flask controllers and routing |
| S12 | 2 | 2, 3 | Flask controllers and routing |
| S12 | 12 | 10 | Flask controllers and routing |
| S12 | 29 | 27, 28, 29 | Flask controllers and routing |
| S14 | 8 | 6, 7 | Flask controllers and routing |
| S14 | 15 | 14, 15 | Flask controllers and routing |
| S14 | 27 | 29, 30 | Flask controllers and routing |
| S14 | 29 | 30, 31, 32 | Flask controllers and routing |
| S15 | 8 | 5, 6 | Flask controllers and routing |
| S15 | 25 | 21, 22 | Flask controllers and routing |
| S15 | 30 | 27, 28 | Flask controllers and routing |
| S15 | 31 | 28, 29 | Flask controllers and routing |
| S17 | 13 | 13, 14 | Flask controllers and routing |
| S18 | 2 | 1, 2 | Flask controllers and routing |
| S18 | 21 | 17 | Flask controllers and routing |
| S19 | 4 | 2, 3 | Flask controllers and routing |
| S19 | 10 | 7 | Flask controllers and routing |
| S19 | 19 | 14, 15 | Flask controllers and routing |
| S19 | 26 | 22, 23, 24 | Flask controllers and routing |
| S19 | 27 | 24, 25 | Flask controllers and routing |
| S19 | 30 | 28, 29 | Flask controllers and routing |
| S19 | 31 | 29, 30 | Flask controllers and routing |
| S19 | 32 | 30, 31 | Flask controllers and routing |
| S20 | 2 | 1 | Flask controllers and routing |
| S20 | 4 | 2 | Flask controllers and routing |
| S20 | 6 | 3, 4 | Flask controllers and routing |
| S20 | 26 | 21, 22 | Flask controllers and routing |
| S20 | 27 | 22, 23, 24 | Flask controllers and routing |
| S20 | 29 | 26, 27 | Flask controllers and routing |
| S21 | 3 | 4, 5, 6 | Flask controllers and routing |
| S21 | 5 | 7, 8, 9, 10 | Tests Flask route matching, trailing slashes and url_for alongside template rendering. |
| S21 | 10 | 16, 17, 18 | Flask controllers and routing |
| S21 | 19 | 26, 27, 28 | Flask controllers and routing |
| S21 | 27 | 36, 37 | Flask controllers and routing |
| S22 | 2 | 2, 3 | Flask controllers and routing |
| S22 | 6 | 6, 7 | Flask controllers and routing |
| S22 | 15 | 14, 15, 16 | Flask controllers and routing |
| S22 | 16 | 16, 17, 18 | Flask controllers and routing |
| S23 | 3 | 3, 4 | Flask controllers and routing |
| S23 | 4 | 4 | Flask controllers and routing |
| S23 | 8 | 7, 8 | Flask controllers and routing |
| S24 | 15 | 15, 16, 17 | Flask controllers and routing |
| S25 | 6 | 7 | Flask controllers and routing |
| S26 | 3 | 3, 4 | Flask controllers and routing |
| S26 | 6 | 5, 6 | Flask controllers and routing |
| S26 | 8 | 7 | Flask controllers and routing |
| S26 | 9 | 7, 8 | Flask controllers and routing |
| S29 | 12 | 12, 13 | Flask controllers and routing |
| S29 | 15 | 14, 15 | Flask controllers and routing |
| S29 | 16 | 15, 16 | Flask controllers and routing |
| S31 | 4 | 3, 4 | Flask controllers and routing |
| S31 | 8 | 6, 7 | Flask controllers and routing |
| S31 | 10 | 8, 9 | Flask controllers and routing |
| S31 | 13 | 11, 12 | Flask controllers and routing |
| S31 | 14 | 13, 14 | Flask controllers and routing |
| S31 | 15 | 14, 15 | Flask controllers and routing |
| S31 | 16 | 15, 16 | Flask controllers and routing |
| S32 | 13 | 11, 12 | Flask controllers and routing |
| S32 | 15 | 13, 14 | Flask controllers and routing |
| S32 | 16 | 14, 15, 16 | Flask controllers and routing |
| S33 | 16 | 14, 15 | Flask controllers and routing |
| S35 | 9 | 6, 7 | Flask controllers and routing |
| S35 | 13 | 10, 11, 12 | Flask controllers and routing |
| S35 | 15 | 12, 13 | Flask controllers and routing |
| S35 | 16 | 13, 14, 15 | Flask controllers and routing |
| S36 | 4 | 5, 6 | Flask controllers and routing |
| S36 | 5 | 6, 7 | Flask controllers and routing |
| S36 | 8 | 10, 11 | Flask controllers and routing |
| S37 | 1 | 1, 2 | Flask controllers and routing |
| S37 | 2 | 2, 3, 4 | Flask controllers and routing |
| S38 | 3 | 2 | Flask controllers and routing |
| S38 | 4 | 2, 3 | Flask controllers and routing |
| S38 | 9 | 5, 6 | Flask controllers and routing |
| S38 | 10 | 6 | Flask controllers and routing |
| S38 | 13 | 8, 9 | Flask controllers and routing |
| S39 | 6 | 4, 5 | Flask controllers and routing |
| S40 | 4 | 2, 3 | Flask controllers and routing |
| S40 | 6 | 5 | Flask controllers and routing |
| S40 | 12 | 10, 11 | Flask controllers and routing |
| S40 | 14 | 12, 13 | Flask controllers and routing |
| S41 | 2 | 1, 2 | Flask controllers and routing |
| S41 | 3 | 2, 3 | Flask controllers and routing |
| S41 | 4 | 3, 4 | Flask controllers and routing |
| S41 | 10 | 7 | Flask controllers and routing |
| S41 | 11 | 7, 8 | Flask controllers and routing |
| S42 | 1 | 1 | Flask controllers and routing |
| S42 | 2 | 2 | Flask controllers and routing |
| S42 | 4 | 3, 4 | Flask controllers and routing |
| S42 | 9 | 7, 8 | Flask controllers and routing |
| S42 | 11 | 10 | Flask controllers and routing |
| S42 | 12 | 11 | Flask controllers and routing |
| S42 | 13 | 12, 13 | Flask controllers and routing |
| S43 | 5 | 3, 4, 5 | Flask controllers and routing |
| S43 | 6 | 5 | Flask controllers and routing |
| S43 | 10 | 8, 9 | Flask controllers and routing |
| S44 | 4 | 5 | Flask controllers and routing |
| S44 | 14 | 14, 15 | Flask controllers and routing |
| S45 | 5 | 5, 6 | Flask controllers and routing |
| S45 | 6 | 6, 7 | Flask controllers and routing |
| S45 | 10 | 11, 12 | Flask controllers and routing |
| S45 | 11 | 13, 14 | Flask controllers and routing |
| S45 | 15 | 17, 18 | Flask controllers and routing |
| S46 | 1 | 1 | Flask controllers and routing |
| S46 | 5 | 3, 4 | Flask controllers and routing |
| S46 | 8 | 6, 7 | Flask controllers and routing |
| S46 | 15 | 13, 14 | Flask controllers and routing |
| S46 | 16 | 14, 15 | Flask controllers and routing |

## Week 6: APIs and REST

Syllabus coverage: REST architectural constraints and resource design; API methods, status codes and JSON exchange; Flask-RESTful resources and request parsing.

| Source | Original question | PDF pages | Assignment basis |
|---|---:|---|---|
| S01 | 8 | 9, 10 | APIs and REST |
| S03 | 15 | 9, 10 | APIs and REST |
| S03 | 20 | 13 | APIs and REST |
| S04 | 6 | 5, 6 | APIs and REST |
| S04 | 8 | 7, 8 | Mixed API/MVC/routing/stateless matching: API concepts are explicitly introduced in Week 6. |
| S04 | 28 | 23, 24, 25 | APIs and REST |
| S04 | 29 | 25, 26, 27 | APIs and REST |
| S04 | 30 | 27, 28 | APIs and REST |
| S05 | 13 | 10, 11 | APIs and REST |
| S06 | 12 | 10, 11 | APIs and REST |
| S06 | 25 | 24, 25 | APIs and REST |
| S07 | 24 | 21, 22 | APIs and REST |
| S08 | 15 | 12 | APIs and REST |
| S09 | 29 | 27, 28 | APIs and REST |
| S09 | 30 | 28, 29, 30 | APIs and REST |
| S09 | 31 | 30, 31, 32 | APIs and REST |
| S09 | 32 | 32, 33, 34 | APIs and REST |
| S11 | 30 | 29, 30, 31 | APIs and REST |
| S11 | 31 | 31, 32 | APIs and REST |
| S11 | 32 | 32, 33, 34 | APIs and REST |
| S12 | 22 | 20, 21, 22 | APIs and REST |
| S13 | 16 | 13, 14 | APIs and REST |
| S13 | 20 | 17, 18, 19, 20 | APIs and REST |
| S14 | 7 | 5, 6 | APIs and REST |
| S15 | 10 | 7, 8 | APIs and REST |
| S15 | 26 | 22, 23 | APIs and REST |
| S17 | 24 | 25, 26, 27 | APIs and REST |
| S17 | 25 | 27, 28, 29 | APIs and REST |
| S17 | 26 | 29, 30, 31 | APIs and REST |
| S17 | 31 | 34, 35 | APIs and REST |
| S17 | 32 | 36, 37 | APIs and REST |
| S19 | 28 | 25, 26, 27 | APIs and REST |
| S19 | 29 | 27, 28 | APIs and REST |
| S20 | 1 | 1 | APIs and REST |
| S20 | 20 | 15, 16 | APIs and REST |
| S21 | 13 | 19, 20, 21 | APIs and REST |
| S21 | 15 | 21, 22, 23 | APIs and REST |
| S21 | 20 | 28, 29, 30, 31 | APIs and REST |
| S21 | 31 | 43, 44 | APIs and REST |
| S21 | 32 | 44, 45, 46 | APIs and REST |
| S30 | 8 | 6 | APIs and REST |
| S33 | 2 | 1, 2 | APIs and REST |
| S36 | 3 | 3, 4, 5 | APIs and REST |
| S36 | 7 | 8, 9, 10 | APIs and REST |
| S36 | 11 | 13, 14 | APIs and REST |
| S36 | 12 | 14, 15, 16 | APIs and REST |
| S37 | 9 | 12, 13 | APIs and REST |
| S37 | 16 | 19, 20 | APIs and REST |
| S39 | 7 | 5, 6 | APIs and REST |
| S40 | 9 | 6, 7 | APIs and REST |
| S40 | 15 | 13, 14, 15 | APIs and REST |
| S41 | 6 | 5 | APIs and REST |
| S41 | 7 | 5 | APIs and REST |
| S41 | 15 | 10, 11 | APIs and REST |
| S42 | 16 | 16, 17 | APIs and REST |
| S43 | 11 | 9 | APIs and REST |
| S43 | 13 | 10, 11, 12 | APIs and REST |
| S44 | 7 | 7 | APIs and REST |
| S44 | 10 | 9, 10, 11 | APIs and REST |
| S45 | 7 | 7, 8 | APIs and REST |
| S46 | 2 | 2 | APIs and REST |
| S46 | 14 | 12, 13 | APIs and REST |

## Week 7: Backend systems and application state

Syllabus coverage: Backend memory/storage and server processing; Application state, cookies and sessions; Caching, background processing and service integration.

| Source | Original question | PDF pages | Assignment basis |
|---|---:|---|---|
| S01 | 6 | 7 | Backend systems and application state |
| S01 | 9 | 10, 11, 12 | Backend systems and application state |
| S01 | 20 | 22 | Backend systems and application state |
| S03 | 24 | 16 | Backend systems and application state |
| S06 | 29 | 29 | Backend systems and application state |
| S06 | 30 | 29, 30 | Backend systems and application state |
| S07 | 21 | 18 | Backend systems and application state |
| S14 | 14 | 12, 13 | Backend systems and application state |
| S14 | 28 | 30 | Backend systems and application state |
| S14 | 30 | 32, 33, 34 | Backend systems and application state |
| S15 | 24 | 21 | Backend systems and application state |
| S16 | 2 | 2 | Backend systems and application state |
| S18 | 5 | 3 | Backend systems and application state |
| S21 | 23 | 32 | Backend systems and application state |
| S36 | 1 | 1 | Backend systems and application state |
| S37 | 12 | 14, 15 | Backend systems and application state |
| S39 | 13 | 9 | Backend systems and application state |
| S42 | 3 | 2, 3 | Backend systems and application state |
| S44 | 13 | 13, 14 | Backend systems and application state |

## Week 8: Application frontend and interaction

Syllabus coverage: Forms, input handling and validation; JavaScript, DOM and browser events; Frontend workflows and client-side interaction.

| Source | Original question | PDF pages | Assignment basis |
|---|---:|---|---|
| S03 | 18 | 12 | Application frontend and interaction |
| S03 | 19 | 12, 13 | Application frontend and interaction |
| S04 | 9 | 8, 9 | Application frontend and interaction |
| S06 | 13 | 11, 12 | Application frontend and interaction |
| S06 | 23 | 22 | Application frontend and interaction |
| S06 | 24 | 22, 23, 24 | Application frontend and interaction |
| S07 | 8 | 5 | Application frontend and interaction |
| S08 | 4 | 5 | Application frontend and interaction |
| S08 | 5 | 5, 6 | Application frontend and interaction |
| S08 | 7 | 6, 7 | Application frontend and interaction |
| S08 | 8 | 7, 8 | Application frontend and interaction |
| S08 | 9 | 8, 9 | Application frontend and interaction |
| S08 | 14 | 11, 12 | Application frontend and interaction |
| S08 | 16 | 12, 13 | Application frontend and interaction |
| S09 | 9 | 7, 8 | Application frontend and interaction |
| S09 | 10 | 8, 9 | Application frontend and interaction |
| S09 | 22 | 22 | Application frontend and interaction |
| S10 | 19 | 16, 17 | Application frontend and interaction |
| S12 | 5 | 4, 5 | Application frontend and interaction |
| S12 | 6 | 5, 6 | Application frontend and interaction |
| S13 | 4 | 4 | Application frontend and interaction |
| S14 | 10 | 8, 9 | Application frontend and interaction |
| S14 | 11 | 9, 10 | Application frontend and interaction |
| S14 | 16 | 15, 16 | Application frontend and interaction |
| S16 | 1 | 1 | Application frontend and interaction |
| S17 | 18 | 18, 19, 20 | Application frontend and interaction |
| S18 | 14 | 9, 10 | Application frontend and interaction |
| S19 | 5 | 3 | Application frontend and interaction |
| S19 | 6 | 3 | Application frontend and interaction |
| S20 | 5 | 3 | Application frontend and interaction |
| S24 | 3 | 2 | Application frontend and interaction |
| S33 | 1 | 1 | Application frontend and interaction |
| S36 | 6 | 7, 8 | Application frontend and interaction |
| S36 | 13 | 16 | Application frontend and interaction |
| S38 | 2 | 1 | Application frontend and interaction |
| S38 | 12 | 7, 8 | Application frontend and interaction |
| S39 | 3 | 2 | Application frontend and interaction |
| S39 | 8 | 6 | Application frontend and interaction |
| S39 | 12 | 8, 9 | Application frontend and interaction |
| S40 | 2 | 1, 2 | Application frontend and interaction |
| S41 | 13 | 9, 10 | Application frontend and interaction |
| S41 | 14 | 10 | Application frontend and interaction |
| S42 | 15 | 14, 15, 16 | Application frontend and interaction |
| S43 | 2 | 1, 2 | Application frontend and interaction |
| S43 | 4 | 2, 3 | Application frontend and interaction |
| S43 | 9 | 7, 8 | Application frontend and interaction |
| S44 | 15 | 15, 16 | Application frontend and interaction |
| S45 | 16 | 18, 19 | Application frontend and interaction |
| S46 | 6 | 4, 5 | Application frontend and interaction |

## Week 9: Application security

Syllabus coverage: Authentication and authorization; Passwords, encryption and transport security; Injection, XSS, CSRF and browser security policies.

| Source | Original question | PDF pages | Assignment basis |
|---|---:|---|---|
| S03 | 13 | 8 | Application security |
| S04 | 2 | 1, 2 | Application security |
| S07 | 4 | 2, 3 | Application security |
| S08 | 21 | 16 | Application security |
| S09 | 11 | 9 | Application security |
| S16 | 16 | 16 | Application security |
| S18 | 7 | 4 | Application security |
| S18 | 15 | 10, 11 | Application security |
| S19 | 3 | 2 | Application security |
| S43 | 8 | 6, 7 | Application security |

## Week 10: Testing and debugging

Syllabus coverage: Unit, integration, system and regression tests; Pytest and Flask test clients; Debugging, logging and test results.

| Source | Original question | PDF pages | Assignment basis |
|---|---:|---|---|
| S01 | 5 | 5, 6 | Testing and debugging |
| S01 | 7 | 7, 8 | Testing and debugging |
| S01 | 13 | 15, 16 | Testing and debugging |
| S01 | 18 | 20 | Testing and debugging |
| S01 | 28 | 29, 30, 31 | Testing and debugging |
| S02 | 22 | 22, 23 | Testing and debugging |
| S02 | 23 | 23, 24 | Testing and debugging |
| S03 | 2 | 1, 2 | Testing and debugging |
| S03 | 21 | 13, 14 | Testing and debugging |
| S04 | 10 | 9 | Testing and debugging |
| S06 | 14 | 12, 13 | Testing and debugging |
| S06 | 16 | 14, 15 | Testing and debugging |
| S06 | 18 | 16, 17 | Testing and debugging |
| S07 | 6 | 3, 4 | Testing and debugging |
| S08 | 6 | 6 | Testing and debugging |
| S08 | 11 | 10 | Testing and debugging |
| S08 | 12 | 10, 11 | Testing and debugging |
| S08 | 17 | 13 | Testing and debugging |
| S08 | 18 | 13, 14 | Testing and debugging |
| S08 | 19 | 14, 15 | Testing and debugging |
| S09 | 8 | 6, 7 | Testing and debugging |
| S09 | 19 | 19 | Testing and debugging |
| S09 | 21 | 21, 22 | Testing and debugging |
| S10 | 3 | 3 | Testing and debugging |
| S10 | 18 | 15, 16 | Testing and debugging |
| S11 | 11 | 8 | Testing and debugging |
| S14 | 9 | 7, 8 | Testing and debugging |
| S15 | 17 | 14, 15 | Testing and debugging |
| S16 | 21 | 19, 20 | Testing and debugging |
| S17 | 4 | 2, 3 | Testing and debugging |
| S17 | 9 | 7, 8 | Testing and debugging |
| S17 | 19 | 20 | Testing and debugging |
| S18 | 3 | 2 | Testing and debugging |
| S18 | 12 | 8, 9 | Testing and debugging |
| S19 | 17 | 13 | Testing and debugging |
| S19 | 20 | 16, 17 | Testing and debugging |
| S19 | 23 | 19 | Testing and debugging |
| S19 | 24 | 19, 20, 21 | Testing and debugging |
| S21 | 12 | 18, 19 | Testing and debugging |
| S21 | 14 | 21 | Testing and debugging |
| S42 | 10 | 9 | Testing and debugging |
| S44 | 16 | 16, 17 | Testing and debugging |
| S45 | 14 | 16, 17 | Testing and debugging |

## Week 11: HTML evolution and accessibility

Syllabus coverage: HTML5 and evolving web capabilities; Semantic web and accessibility principles; Modern browser APIs and multimedia.

| Source | Original question | PDF pages | Assignment basis |
|---|---:|---|---|
| S02 | 3 | 2 | HTML evolution and accessibility |
| S06 | 5 | 4, 5 | HTML evolution and accessibility |
| S10 | 12 | 9, 10 | HTML evolution and accessibility |
| S10 | 14 | 10 | HTML evolution and accessibility |
| S11 | 7 | 4, 5 | HTML evolution and accessibility |
| S13 | 27 | 26 | HTML evolution and accessibility |
| S17 | 7 | 5 | HTML evolution and accessibility |
| S18 | 4 | 2, 3 | HTML evolution and accessibility |
| S18 | 6 | 3, 4 | HTML evolution and accessibility |
| S29 | 2 | 2, 3 | HTML evolution and accessibility |
| S34 | 12 | 13 | HTML evolution and accessibility |
| S35 | 1 | 1 | HTML evolution and accessibility |

## Week 12: Deployment and production workflows

Syllabus coverage: Hosting, WSGI and server environments; Git, dependencies and deployment workflows; CI/CD, production configuration and scaling.

| Source | Original question | PDF pages | Assignment basis |
|---|---:|---|---|
| S02 | 1 | 1 | Deployment and production workflows |
| S03 | 5 | 2, 3 | Deployment and production workflows |
| S04 | 14 | 11 | Deployment and production workflows |
| S04 | 16 | 12, 13 | Deployment and production workflows |
| S06 | 3 | 2, 3 | Deployment and production workflows |
| S08 | 20 | 15, 16 | Deployment and production workflows |
| S10 | 13 | 10 | Deployment and production workflows |
| S11 | 16 | 13 | Deployment and production workflows |
| S12 | 7 | 6 | Deployment and production workflows |
| S13 | 6 | 4, 5 | Deployment and production workflows |
| S13 | 26 | 25, 26 | Deployment and production workflows |
| S14 | 4 | 3 | Deployment and production workflows |
| S14 | 5 | 3 | Deployment and production workflows |
| S15 | 5 | 2, 3 | Deployment and production workflows |
| S16 | 15 | 15, 16 | Deployment and production workflows |
| S17 | 2 | 1, 2 | Deployment and production workflows |
| S17 | 22 | 23 | Deployment and production workflows |
| S18 | 22 | 17, 18 | Deployment and production workflows |
| S19 | 18 | 13, 14 | Deployment and production workflows |
| S37 | 10 | 13 | Deployment and production workflows |
| S43 | 1 | 1 | Deployment and production workflows |
| S46 | 3 | 2 | Deployment and production workflows |

## Repeated-pattern exclusions

One complete source question represents each reviewed family. Numeric/name-only variants are excluded; distinct operations, constraints and error paths remain separate. Original questions/options are not rewritten or shortened.

| Week | Retained question | Excluded variants | Basis |
|---|---|---|---|
| 1 | S01Q14 | S03Q11, S12Q21, S13Q21 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 1 | S01Q16 | S02Q32, S18Q29 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 1 | S01Q22 | S12Q4, S13Q24, S36Q16 | Definition of a stateless server; wording/options vary. |
| 1 | S02Q31 | S18Q28 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 1 | S02Q9 | S30Q2 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 1 | S03Q3 | S26Q4, S27Q4 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 1 | S04Q1 | S05Q8, S10Q1, S11Q1, S17Q6, S21Q1, S24Q4, S32Q2 | Identify URL scheme, domain, path, query and fragment; changed host/path literals. |
| 1 | S04Q20 | S05Q21 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 1 | S04Q31 | S05Q26 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 1 | S04Q32 | S05Q27 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 1 | S06Q10 | S33Q12 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 1 | S06Q19 | S07Q18 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 1 | S06Q8 | S25Q11 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 1 | S07Q5 | S23Q1, S24Q6, S29Q8 | Data consumed before moving out of tower range: range/speed multiplied by bandwidth. |
| 1 | S09Q26 | S38Q5, S40Q7 | Maximum request rate is the smaller of network capacity and application processing capacity. |
| 1 | S09Q7 | S14Q31 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 1 | S10Q31 | S11Q28, S17Q27 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 1 | S10Q32 | S11Q29, S17Q28 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 1 | S10Q4 | S30Q1 | Connect a netcat client to a simple shell server; port/text changes only. |
| 1 | S12Q28 | S13Q28, S15Q7 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 1 | S14Q32 | S21Q22 | Scale sorting time from a known sample using n log n. |
| 1 | S15Q23 | S16Q22, S18Q30 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 1 | S15Q32 | S16Q30 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 1 | S18Q26 | S42Q7 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 1 | S19Q13 | S20Q8 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 1 | S21Q11 | S32Q9 | Additional bandwidth when both request size and request count change. |
| 1 | S22Q11 | S34Q16, S44Q12 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 1 | S23Q9 | S28Q2 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 1 | S24Q9 | S36Q14 | Order DNS resolution, request, server response and browser processing. |
| 1 | S26Q11 | S27Q11, S41Q1 | Propagation-only round trip time 2d/v; medium and distance change. |
| 1 | S33Q8 | S45Q3 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 2 | S01Q12 | S28Q3, S30Q13 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 2 | S01Q2 | S02Q12 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 2 | S01Q21 | S02Q7, S10Q7, S11Q14, S16Q5 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 2 | S02Q10 | S17Q15, S18Q13 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 2 | S02Q2 | S07Q1, S25Q1 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 2 | S02Q20 | S04Q7, S29Q3, S32Q6 | Python HTTP server serves index.html at the base URL. |
| 2 | S02Q8 | S34Q13 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 2 | S04Q23 | S05Q7 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 2 | S04Q3 | S05Q10 | Order of inline, internal and external CSS styles. |
| 2 | S06Q9 | S07Q11, S24Q5 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 2 | S07Q9 | S19Q8 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 2 | S10Q10 | S11Q2 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 2 | S10Q2 | S11Q8 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 2 | S10Q26 | S11Q23 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 2 | S12Q17 | S13Q15, S17Q1 | HTML anchor href syntax for navigation between local pages. |
| 2 | S12Q23 | S13Q22 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 2 | S14Q1 | S34Q2 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 2 | S14Q2 | S26Q12, S27Q12 | Minimum fixed-width bits per character from alphabet cardinality. |
| 2 | S17Q10 | S18Q19 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 2 | S18Q25 | S24Q8, S35Q8 | CSS ID selector overrides element rules for shared properties; other properties persist. |
| 2 | S19Q15 | S20Q10 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 2 | S24Q13 | S33Q4 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 2 | S26Q1 | S27Q1 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 2 | S28Q5 | S30Q14 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 2 | S33Q7 | S36Q9, S42Q5 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 2 | S35Q6 | S43Q14 | Change in fixed-width encoded document size when the character alphabet grows. |
| 3 | S01Q1 | S02Q11, S24Q11 | Match argv-based Jinja text rendering to command line inputs; changed names and professions. |
| 3 | S01Q17 | S02Q5, S12Q10, S13Q8 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 3 | S01Q19 | S02Q14, S09Q2, S12Q20, S13Q19, S15Q20, S16Q12 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 3 | S01Q23 | S29Q13 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 3 | S03Q12 | S26Q10, S27Q10 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 3 | S04Q11 | S05Q3 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 3 | S04Q19 | S05Q20 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 3 | S04Q25 | S05Q24, S05Q25 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 3 | S06Q17 | S07Q25 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 3 | S06Q2 | S30Q4 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 3 | S07Q20 | S20Q22 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 3 | S09Q3 | S10Q25 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 3 | S10Q11 | S11Q3, S28Q9 | Imported module executes first; sys.argv remains that of the main script. |
| 3 | S10Q16 | S11Q19 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 3 | S10Q17 | S11Q20 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 3 | S12Q1 | S13Q1 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 3 | S12Q16 | S13Q14 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 3 | S12Q26 | S13Q13, S16Q18, S33Q9, S43Q7 | Identify substitutions that supply every required string.Template key. |
| 3 | S12Q31 | S12Q32, S13Q32 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 3 | S15Q28 | S16Q26 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 3 | S19Q12 | S20Q7 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 3 | S22Q12 | S22Q13 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 3 | S23Q5 | S25Q3 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 3 | S26Q13 | S27Q13 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 3 | S26Q7 | S27Q7 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 3 | S29Q5 | S32Q5, S35Q7 | Trace substitute versus safe_substitute with missing keys and a final KeyError. |
| 3 | S39Q5 | S38Q11 | Jinja set inside a loop does not bind the outer variable. |
| 4 | S01Q15 | S02Q24, S11Q9 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 4 | S02Q27 | S04Q18, S05Q18 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 4 | S03Q9 | S39Q1 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 4 | S04Q17 | S05Q17 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 4 | S04Q26 | S05Q28 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 4 | S04Q27 | S05Q29 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 4 | S06Q4 | S20Q12 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 4 | S07Q15 | S40Q10, S44Q1, S46Q11 | Retrieve a model object, update its attributes, commit and print resulting rows. |
| 4 | S09Q12 | S17Q8, S18Q16 | SQLAlchemy filter_by selects records, then a Jinja loop prints their fields. |
| 4 | S10Q23 | S18Q8 | Same customer/order ERD optionality and one-to-many cardinality. |
| 4 | S12Q18 | S01Q11, S10Q8, S39Q2, S44Q8 | Infer one-to-many relationship from a non-unique foreign key; renamed models. |
| 4 | S12Q25 | S13Q25, S15Q22 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 4 | S12Q8 | S13Q5 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 4 | S12Q9 | S13Q7, S46Q9 | Complete one-to-many SQLAlchemy foreign key and relationship declarations. |
| 4 | S13Q17 | S18Q24, S46Q10 | Infer one-to-one relationship from a unique foreign key; renamed models. |
| 4 | S15Q19 | S16Q11 | Filter records by designation/gender, assign new field values and commit. |
| 4 | S15Q21 | S16Q13 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 4 | S17Q12 | S21Q8 | Filter female workers, increment salary and commit; renamed table/data. |
| 4 | S17Q14 | S21Q26 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 4 | S19Q14 | S20Q9 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 4 | S25Q8 | S34Q9 | Trace an equijoin between users and books; changed records and projected attribute. |
| 5 | S01Q10 | S02Q19, S10Q5 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 5 | S01Q24 | S02Q25 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 5 | S01Q25 | S02Q28 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 5 | S01Q29 | S02Q30, S10Q28, S11Q26 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 5 | S01Q3 | S02Q13, S33Q11 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 5 | S01Q30 | S18Q9, S32Q14 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 5 | S01Q31 | S45Q8 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 5 | S01Q32 | S45Q9 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 5 | S03Q16 | S26Q2, S27Q2 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 5 | S03Q23 | S07Q16 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 5 | S04Q12 | S05Q4 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 5 | S04Q21 | S05Q22 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 5 | S04Q5 | S05Q12 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 5 | S06Q11 | S07Q12, S46Q13 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 5 | S06Q15 | S07Q13, S19Q16, S20Q13 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 5 | S06Q26 | S20Q23 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 5 | S06Q27 | S07Q29 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 5 | S06Q28 | S07Q30 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 5 | S06Q6 | S24Q16 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 5 | S09Q18 | S44Q3 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 5 | S09Q20 | S17Q21, S18Q10 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 5 | S09Q6 | S12Q3, S13Q3, S46Q4 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 5 | S10Q27 | S11Q25 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 5 | S12Q12 | S13Q10, S15Q27, S16Q31 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 5 | S12Q2 | S13Q2 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 5 | S12Q29 | S13Q29 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 5 | S14Q15 | S21Q24 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 5 | S15Q30 | S16Q28 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 5 | S15Q31 | S16Q29 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 5 | S19Q10 | S26Q5, S27Q5 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 5 | S19Q19 | S20Q18 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 5 | S19Q30 | S20Q30 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 5 | S19Q31 | S20Q31 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 5 | S19Q32 | S20Q32 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 5 | S23Q4 | S31Q2, S41Q5 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 5 | S26Q3 | S27Q3 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 5 | S26Q6 | S27Q6 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 5 | S26Q8 | S27Q8 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 5 | S26Q9 | S27Q9 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 5 | S29Q12 | S32Q10 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 5 | S31Q4 | S32Q8, S33Q6 | Find route mismatch among dynamic path declarations and an extra literal path segment. |
| 5 | S32Q13 | S40Q11 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 5 | S33Q16 | S40Q16 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 5 | S43Q10 | S44Q2 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 6 | S01Q8 | S02Q17, S12Q15, S16Q3 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 6 | S03Q15 | S08Q13 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 6 | S03Q20 | S39Q9 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 6 | S04Q28 | S05Q30 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 6 | S04Q29 | S05Q31 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 6 | S04Q30 | S05Q32 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 6 | S04Q8 | S05Q15 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 6 | S06Q12 | S16Q8, S46Q7 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 6 | S06Q25 | S07Q26 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 6 | S07Q24 | S17Q20, S19Q22, S39Q11 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 6 | S12Q22 | S16Q25 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 6 | S15Q10 | S16Q19 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 6 | S15Q26 | S16Q32 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 6 | S17Q31 | S18Q31 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 6 | S17Q32 | S18Q32 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 7 | S01Q20 | S02Q16, S12Q14, S38Q8 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 7 | S01Q6 | S02Q21, S13Q12, S40Q8 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 7 | S01Q9 | S02Q18, S10Q20, S11Q18 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 7 | S03Q24 | S39Q10 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 7 | S06Q29 | S07Q31 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 7 | S06Q30 | S07Q32 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 7 | S15Q24 | S16Q23 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 7 | S18Q5 | S36Q15 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 7 | S36Q1 | S45Q12 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 8 | S04Q9 | S05Q1, S37Q8 | JSON.parse followed by DOM text concatenation from object fields. |
| 8 | S06Q23 | S07Q22, S46Q12 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 8 | S06Q24 | S07Q23, S19Q25, S20Q25 | Set input fontWeight to bold through DOM access after a button click. |
| 8 | S07Q8 | S16Q14, S20Q3 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 8 | S10Q19 | S11Q22 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 9 | S04Q2 | S05Q9 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 10 | S01Q13 | S13Q11, S15Q16 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 10 | S01Q18 | S02Q6, S12Q11, S13Q9, S15Q18, S16Q10 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 10 | S01Q28 | S02Q29, S10Q6, S11Q13, S12Q30, S13Q30, S16Q4 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 10 | S01Q5 | S11Q10, S12Q19, S13Q18, S15Q29, S16Q27 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 10 | S01Q7 | S02Q15, S12Q24, S13Q23 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 10 | S02Q22 | S18Q23 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 10 | S02Q23 | S12Q13 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 10 | S04Q10 | S05Q2 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 10 | S06Q16 | S07Q14, S19Q11 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 10 | S06Q18 | S07Q17, S09Q16 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 10 | S09Q8 | S15Q15 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 10 | S10Q18 | S11Q21 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 10 | S15Q17 | S16Q9 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 10 | S17Q4 | S18Q18 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 10 | S19Q17 | S20Q15 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 10 | S19Q20 | S20Q19 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 10 | S19Q23 | S20Q21 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 10 | S19Q24 | S20Q24 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 11 | S06Q5 | S07Q10 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 11 | S11Q7 | S15Q4 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 11 | S13Q27 | S16Q20 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 12 | S04Q14 | S05Q6 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 12 | S04Q16 | S05Q16 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 12 | S06Q3 | S07Q3, S19Q7 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 12 | S15Q5 | S16Q17 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 12 | S17Q2 | S18Q17 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
| 12 | S19Q18 | S20Q16 | Same solution pattern; repeated paper, reordered wording/options, or changed numeric/literal inputs. Distinct operations and edge cases are kept separately. |
