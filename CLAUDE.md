# Algebra 1 Study Site — Project Context

> Loaded automatically by Claude Code. Gives you (the agent) and Nate (the human) a complete picture of the project in one place. Keep this file updated as the project evolves.

---

## One-line

Interactive web app + Markdown study kit for an Algebra 1 student preparing for a focused make-up test on 13 specific topics. Built to be ADHD- and dyscalculia-friendly. Deployed as a single-page site on GitHub Pages.

## Who & Why

- **Student:** Esme (16, sophomore at Tam High, ADHD + dyscalculia, currently struggling with Algebra 1 — see memory notes if relevant).
- **Teacher:** Mr. Mistry, Esme's Algebra 1 teacher. He agreed to a custom-built make-up test covering a condensed essentials curriculum. His original spreadsheet defined 13 topics; on May 21, 2026 he emailed a "Graphing Quadratics Review" handout adding **Topic 14: Graphing in Standard Form (8.3)**, now integrated into the kit.
- **Tutor:** Nate (her father — the human you're talking to).
- **Tutor consultant:** Julia, Esme's regular tutor (Mondays 5pm).

## Critical dates

- **Plan start:** Sunday, May 17, 2026 (Day 1 of a 19-day plan).
- **Mock test:** Tuesday, June 2, 2026 (Day 17) — full 107-pt simulation. (Shifted from Day 16 when Topic 14 was inserted as Day 11.)
- **Real test (target):** ~Thursday, June 4, 2026 (Day 19), the week before school ends.
- **School ends:** Thursday, June 11, 2026 (some buffer days available).
- **Family meetings:** Sun 7pm, Tue 7:45pm, Fri 6:30pm (factored into the schedule).

## The 14 topics (Mr. Mistry's spreadsheet + May 2026 update)

Source: [Google Sheet](https://docs.google.com/spreadsheets/d/1reiPf1mvEb37xc8f8pLlP02DhvD33Y6hz7LfPENkUPw/edit) plus the "Graphing Quadratics Review" PDF Mr. Mistry emailed on May 21, 2026 (Topic 14). All map to Big Ideas Math Algebra 1 (cc19), chapters 7–9.

Schedule order: 1, 2, 3, 4, 5, 6, 7, 8, 9, **14** (capstone of graphing block), 10, 11, 12, 13. The "14" is intentionally placed after Topic 9 in the sequence so it caps the graphing block while keeping the numeric label that matches its add-on origin.

| # | Topic | Textbook |
|---|-------|----------|
| 1 | Adding & Subtracting Polynomials | 7.1 |
| 2 | Multiplying Polynomials (FOIL) | 7.2 |
| 3 | Greatest Common Factor (GCF) | — |
| 4 | Factoring Trinomials — Basic | 7.5 |
| 5 | Factoring Trinomials — Advanced (AC) | 7.6 |
| 6 | Difference of Squares | 7.7 |
| 7 | Graphing Basic Parabolas (y = ax²) | 8.1 |
| 8 | Graphing in Intercept Form | 8.5 |
| 9 | Graphing in Vertex Form | 8.4 |
| **14** | **Graphing in Standard Form (NEW, per Raj)** | **8.3** |
| 10 | Solving by Factoring (Zero Product) | 7.4 |
| 11 | Solving by Square Roots | 9.3 |
| 12 | Completing the Square | 9.4 |
| 13 | The Quadratic Formula | 9.5 |

**Important:** All "top 10%" advanced material is intentionally excluded per Mr. Mistry's guidance. The kit covers core 80–90% only.

## Where things live

- **Project root:** `/Users/natekoechley/Documents/Claude/Projects/Web/algebra1-study/`
- **GitHub repo:** https://github.com/natekoechley/algebra1-study (public)
- **Live site:** https://natekoechley.github.io/algebra1-study/
- **GitHub Pages config:** Deploy from `main` branch, `/(root)`. Auto-redeploys ~30 sec after push.
- **Original raw source materials** (Canvas downloads, Mr. Mistry's PDFs): These were in `/Users/natekoechley/Documents/Claude/Projects/Family OS/Algebra 2 - downloaded class files/` but may have been reorganized. The cc19_algebra1_ipe_XX_YY.pdf URLs on the Big Ideas Math CDN are the authoritative textbook PDFs.

## File structure

```
algebra1-study/
├── index.html              # The interactive study site (the main deliverable)
├── README.md               # Repo landing page (renders on github.com)
├── CLAUDE.md               # THIS FILE — project context for agents/humans
├── .nojekyll               # Tells GitHub Pages not to process via Jekyll
├── .gitignore              # OS junk
│
├── 00 — START HERE — Master Hub.md          # Orientation, schedule, panic card
├── 00 — Nate's Tutor Primer.md              # "New math" vs old math, tutoring tactics
├── 00 — One-Page Wall Cheat Sheet.md        # Print + tape to wall
├── 00 — Printable Schedule (Pin to Wall).md # 19-day schedule with checkboxes
├── 00 — Mini-Quiz #1 (Day 6, May 22).md     # After topics 1–5
├── 00 — Mini-Quiz #2 (Day 12, May 28).md    # After topics 6–9 + 14
├── 00 — Mock Test (Day 17, June 2).md       # Full 107-pt simulation (all 14 topics)
│
├── 01 — Adding & Subtracting Polynomials (7.1).md
├── 02 — Multiplying Polynomials (7.2).md
├── 03 — Greatest Common Factor (GCF).md
├── 04 — Factoring Trinomials Basic (7.5).md
├── 05 — Factoring Trinomials Advanced (7.6).md
├── 06 — Difference of Squares (7.7).md
├── 07 — Graphing Basic Parabolas (8.1).md
├── 08 — Graphing Parabolas Intercept Form (8.5).md
├── 09 — Graphing Parabolas Vertex Form (8.4).md
├── 10 — Solving by Factoring (7.4).md
├── 11 — Solving by Square Roots (9.3).md
├── 12 — Completing the Square (9.4).md
├── 13 — Quadratic Formula (9.5).md
├── 14 — Graphing Standard Form (8.3).md       # NEW — per Raj's May 2026 handout
│
├── Cheatsheet — Factoring (Topics 1–6).pdf     # One-page, teacher-approval-ready
├── Cheatsheet — Graphing (Topics 7–9, 14).pdf
├── Cheatsheet — Solving (Topics 10–13).pdf
│
├── flashcards-vocab.csv             # 40 vocab terms (Quizlet-import format)
├── flashcards-formulas.csv          # 22 formulas
├── flashcards-traps.csv             # 15 common-mistake cards
├── Quizlet Import Instructions.md
│
├── DEPLOY-INSTRUCTIONS.md           # First-time deploy guide
└── PUSH-UPGRADES.sh                 # Script to commit + push (handles stale locks)
```

Each topic Markdown file follows the same structure: ELI5 intro, vocab table, recipe (numbered steps), mnemonic, worked example, 5 practice problems with answers, common traps, and "Nate's Tutor Primer" section.

Filename convention: em-dash (`—`, U+2014), NOT hyphen.

## Features in `index.html`

The HTML site is a single-page app, ~150KB, no build step, vanilla JS + minimal CSS. External dependency: Marked.js (loaded from cdnjs) for Markdown rendering.

### Sections (tabs in top nav):
1. **🏠 Home** — Auto-detects which day of the 19-day plan today is. Shows today's topic.
2. **📘 Topics** — All 14 topics. Click any to see a detail view with two tabs:
   - **Quick Recipe** — crisp summary (recipe steps, formula, mnemonic, traps)
   - **Full Guide** — fetches and renders the corresponding `.md` file via Marked.js. Cached after first load.
3. **📝 Practice** — Generates fresh problems on demand:
   - Topic picker (13 buttons)
   - Slider: 3–10 problems per set
   - Difficulty: Easy / Medium / Hard / Progressive (escalates within a set)
   - Per-problem "🔥 Try a harder version" button
   - Each problem has a "Show step-by-step solution" toggle with full narrative + vocab defined inline + final answer
4. **📈 Parabola** — Interactive visualizer with sliders for a/b/c (standard), a/h/k (vertex), or a/p/q (intercept). Live SVG.
5. **🎴 Flashcards** — 3 decks (vocab/formulas/traps) with flip + next/prev navigation.
6. **✅ Quiz** — Custom quiz builder:
   - Topic checkboxes (any combination of 1–13)
   - "Up to lesson N" dropdown shortcut
   - Select all / Clear shortcuts
   - Slider: 3–20 questions
   - Pulls random questions from a 52-question hand-written bank (4 per topic)
7. **🚨 Cheat Sheet** — Searchable cheat sheet (19 cards).
8. **😰 Panic** — When-she's-stuck flow + decision tree for "which topic is this?"

### Practice problem generators (JavaScript, in `index.html`)

13 generators, one per topic, signature `gen(difficulty = 'easy') → {problem, answer, overall, steps, difficulty}`.

Each `steps` array contains objects: `{title, narrative, math}`. The narrative defines vocabulary in parens inline (e.g., *"the coefficient (the number in front of a variable)"*).

Difficulty knobs in each generator scale number ranges and (for graphing topics) the set of `a` coefficients available. All factoring problems still produce clean integer factorizations.

**Tested** at all 3 difficulty levels for all 14 topics — 42 trials, all pass.

### Quiz bank

`QUIZ_BANK` is an object keyed by topic number (1–13), each with an array of 4 multiple-choice questions. Each question: `{q, a: [4 options], correct: index, why: explanation}`. Total: 52 questions.

## Workflow

### To edit content
1. Edit any file in `algebra1-study/`.
2. `git add -A && git commit -m "..." && git push`
3. Wait ~30 sec for GitHub Pages to redeploy.

### Lock files keep showing up
The sandbox in Cowork mode sometimes leaves stale `.git/*.lock` files. Clear them with:
```bash
rm -f .git/*.lock
```

### To add a new topic
1. Add to spreadsheet → add to `README.md` table → create `NN — Title.md` file.
2. Update `index.html`:
   - `TOPICS` array (the quick recipe data)
   - `TOPIC_NAMES_PRAC` object
   - `TOPIC_GUIDE_FILES` object
   - Add a generator to `PRACTICE_GENERATORS` and a 4-question bank to `QUIZ_BANK`
3. Commit + push.

### To tweak a generator
- All 13 are inside `const PRACTICE_GENERATORS = { ... }` in `index.html`.
- Helper functions: `randInt`, `randNonZero`, `randPick`, `fmtPoly`, `fmtSign`, `fmtTerm`, `fmtBinomX`, `fmtBinomScaled`, `fmtSignTerm`, `fmtSignX`, `superscript`, `diffRange`.
- Test changes with the Node smoke-test pattern (see prior conversation history — eval the generator block in node and verify output).

### To add quiz questions
- Just add objects to the appropriate array in `QUIZ_BANK`.
- Format: `{q: "Question text", a: ["A", "B", "C", "D"], correct: 0-indexed, why: "explanation"}`.

## What's NOT done (open work)

- **No proactive engagement with Mr. Mistry yet** — Nate hasn't (as of this writing) shared the URL with him for sign-off. Could be worth doing.
- **No coordination with Julia (tutor) yet** — same. A short brief sharing the topic list and current weakness areas would help her Monday sessions reinforce, not diverge.
- **No "Topic 0" times-table / number fluency supplement** — would help dyscalculia. Suggested earlier but not built.
- **Schedule day auto-detection** in `index.html` uses the visitor's local date. If we're past June 4, the home view says "Test day or beyond — you did the work." Doesn't gracefully handle a re-run scenario.
- **No analytics** (intentional — keep it simple, no tracking).
- **No backup/export** of Esme's mock test results.

## Important context (non-obvious)

- **Esme has dyscalculia AND ADHD.** Always favor: small clean integers, sign-discipline drilled, recipes over conceptual explanations, short sessions (15–20 min), always close on a problem she got right.
- **Esme dislikes math.** The goal isn't to make her love it. It's to make her **confident with these 13 specific moves by June 4**.
- **Practice-to-test gap was the original problem.** She scored 10/10 on practice but 25–72% on tests in chapters 7–8. The new mock-test feature is specifically designed to bridge that gap (timed, no help, then targeted review).
- **Mr. Mistry's spreadsheet was the seed.** He said: *"This spreadsheet contains some focused extra practice on the essentials for Esme. Many of these she's got a good start on but will need refining."* The 13 topics in this kit are exactly what he listed.
- **Sign-flip traps are the single most common error pattern** — both in vertex form (`(x − 3)²` → `h = +3`) and intercept form (`(x − 5)` → root at `+5`). These are drilled in every relevant topic, quiz, and cheat sheet.
- **Filename convention:** em-dash `—` (U+2014) not hyphen `-`. This was a deliberate stylistic choice from earlier Family OS work, kept consistent here.
- **Public visibility was a deliberate choice.** Nate accepted that Esme's name appears in some Markdown files. Choice was: simple/free GitHub Pages with public repo vs. paid private. He picked public.

## Tech architecture

- **No build step.** `index.html` is the deployed artifact directly.
- **Vanilla JS.** No framework. ~1200 lines of JS in `<script>` tag.
- **One external dep:** Marked.js (loaded from cdnjs) for rendering the embedded Markdown guides.
- **Markdown guides loaded via `fetch()`** at runtime (cached after first load).
- **SVG for the parabola visualizer.** No canvas, no charting library.
- **No backend.** No accounts, no analytics, no tracking. Static files only.
- **Mobile-friendly.** Viewport meta tag, flexible layouts. Tested on phone-sized viewports.

## Useful URLs

- **Mr. Mistry's source spreadsheet:** https://docs.google.com/spreadsheets/d/1reiPf1mvEb37xc8f8pLlP02DhvD33Y6hz7LfPENkUPw/edit
- **Big Ideas Math textbook PDFs (cc19 Algebra 1):** https://static.bigideasmath.com/protected/content/ipe/cc19/cc19_algebra1_ipe_XX_YY.pdf (replace XX with chapter, YY with section)
- **Desmos graphing calculator** (recommended visual tool for topics 7–9): https://www.desmos.com/calculator
- **Khan Academy Algebra 1 Quadratics:** https://www.khanacademy.org/math/algebra/x2f8bb11595b61c86:quadratics-multiplying-factoring
- **Symbolab** (step-by-step solver, for verification): https://www.symbolab.com

## Conversation history with Cowork agent

The project went through these phases:
1. **Inventory** — Found the existing course materials Nate had downloaded from Canvas.
2. **Mapping** — Mapped Mr. Mistry's 13 spreadsheet topics to the downloaded PDFs.
3. **Build (v1)** — Created the 13 topic Markdown guides, schedule, mini-quizzes, mock test, tutor primer, cheat sheet, flashcards. Built the single-file HTML study site with topic navigator, parabola visualizer, flashcards, quizzes.
4. **Practice generator (v1.5)** — Added the on-demand problem generator with step-by-step solutions and inline vocabulary definitions.
5. **Bug fixes** — Cleaned up edge cases in the generators (e.g., `x² − 1x − 30` → `x² − x − 30`, integer AOS for intercept form, sign handling for negative `b`).
6. **GitHub deploy** — Created the public repo and GitHub Pages site.
7. **Upgrade (v2 — current)** — Integrated Full Guides as tabs in topic detail, added practice problem count + difficulty controls (Easy/Medium/Hard/Progressive) + per-problem "Try harder" button, redesigned the quiz with topic-selection + 52-question bank.

## Suggested next moves

1. **Email Mr. Mistry the URL.** Get his sign-off / corrections on scope.
2. **Send Julia (tutor) the URL** + a short note on Esme's weakest 2–3 topics.
3. **Print the wall cheat sheet and 19-day schedule.** Tape them in her workspace.
4. **Build a "Topic 0: Number Fluency" supplement** for dyscalculia support — times tables 1–12, perfect squares 1–12, factor pairs of 1–60. Could be flashcards or a quick-drill page.
5. **After the test:** archive the kit, write a short postmortem on what worked / what didn't (informs Esme's next-semester support).

---

*Last updated: end of v2 upgrade session in Cowork mode. If you're picking this up in Claude Code: the live site is at https://natekoechley.github.io/algebra1-study/, all source lives here, deploys happen on push to main.*
