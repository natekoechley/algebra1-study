# Topic 14 — Graphing Parabolas in Standard Form: y = ax² + bx + c
**Textbook:** Big Ideas Math, Algebra 1, Section 8.3
**Source:** Mr. Mistry's "Graphing Quadratics Review" handout (May 2026 update)
**Time to learn:** 25–30 min (the form you'll see most often on tests)

---

## 🟢 The Big Idea (ELI5)

**Standard form** is the "default" way a quadratic is written:

`y = ax² + bx + c`

It's the form you'll see on tests **the most**, but it's also the form where the vertex is **hidden**. It doesn't hand you the vertex like vertex form does. You have to **compute** the vertex using a formula.

The good news: the formula is short, the recipe is only 4–5 steps, and once you've got the vertex, you fall back on tricks you already know (the **ax² heights pattern** and **symmetry**).

**The magic formula:** Axis of symmetry is at `x = −b / (2a)`. Once you have that x, plug it back into the equation to get the vertex y. That's it — you have the vertex.

---

## 📖 Vocab You Need

| Word | What it means |
|------|---------------|
| **Standard form** | y = ax² + bx + c — the "default" quadratic form |
| **a** | Coefficient of x² — controls direction (up/down) and width |
| **b** | Coefficient of x — used to find the AOS |
| **c** | Constant — IS the y-intercept (because plugging x=0 wipes out everything else) |
| **Axis of symmetry (AOS)** | Vertical line x = −b/(2a) — splits the parabola in half |
| **Vertex** | The tip of the U. x-coord = AOS; y-coord found by plugging AOS into equation |
| **y-intercept** | Where graph crosses y-axis. ALWAYS at (0, c) in standard form |
| **ax² heights pattern** | From vertex, the next points up the parabola are at heights a·1, a·4, a·9 (i.e. 1a, 4a, 9a steps left & right of vertex) |

---

## 🧾 The Recipe — Graphing y = ax² + bx + c (Raj's 5-step method)

1. **Find the AOS:** `x = −b / (2a)`. This is the x-coordinate of the vertex.
2. **Find vertex y:** Plug that x back into the equation. Now you have the vertex (x, y).
3. **Plot the y-intercept** at (0, c). Then plot its **mirror point** across the AOS (same y-value, equal distance on the other side).
4. **Use the ax² heights pattern** to plot more points from the vertex: 1 right and 1 left → ±a from vertex y. 2 right and 2 left → ±4a from vertex y. (Optional: 3 right/left → ±9a.)
5. **Smooth U through all points.** Label vertex, AOS, y-intercept.
6. *(Optional)* If you need **x-intercepts**, set y = 0 and either factor, complete the square, or use the quadratic formula.

---

## ✏️ Worked Example

**Graph:** `y = x² − 6x + 5`

**Step 1 — Find AOS:** a=1, b=−6. AOS x = −(−6) / (2·1) = **6/2 = 3**. So x = 3.

**Step 2 — Find vertex y:** plug x=3 into y = x² − 6x + 5 → y = 9 − 18 + 5 = **−4**. Vertex is **(3, −4)**.

**Step 3 — y-intercept and its mirror:** c = 5, so y-intercept is **(0, 5)**. AOS is at x=3, and (0,5) is 3 units LEFT of AOS. Mirror = 3 units RIGHT of AOS at the same height → **(6, 5)**.

**Step 4 — Heights pattern from vertex (a=1, so heights are 1, 4, 9):**
- 1 step right of vertex (x=4) → height +1 → y = −4 + 1 = **−3** → point (4, −3). Mirror: (2, −3).
- 2 steps right (x=5) → height +4 → y = −4 + 4 = **0** → point (5, 0). Mirror: (1, 0). (These also happen to be the x-intercepts!)

**Step 5 — Plot and connect:** (3,−4) vertex • (4,−3), (2,−3) • (5,0), (1,0) • (0,5), (6,5). Smooth U opening up. Label vertex, AOS x=3. ✅

---

## 🧠 Mnemonic — "AOS, VERTEX, c, Heights"

Four words, four steps:
- **AOS** → −b / (2a)
- **VERTEX** → plug AOS back in
- **c** → that's your y-intercept at (0, c). Mirror it across AOS.
- **HEIGHTS** → 1a, 4a, 9a up from vertex, left and right

Bonus mnemonic for the AOS formula: **"Negative B over Two A"** — say it out loud. Same rhythm as the start of the quadratic formula (which IS just AOS ± something).

---

## 📐 The ax² Heights Pattern (memorize cold)

For ANY parabola `y = ax² + ...`, once you know the vertex, the next points to the left and right look like this (measuring **up** from the vertex when a > 0, **down** when a < 0):

| Steps from vertex (left or right) | Height from vertex |
|---|---|
| ±1 | a · 1 = **a** |
| ±2 | a · 4 = **4a** |
| ±3 | a · 9 = **9a** |

So for a = 1: heights are **1, 4, 9**. For a = 2: heights are **2, 8, 18**. For a = ½: heights are **0.5, 2, 4.5**.

This works because the parent function y = x² has y-values 1, 4, 9 at x = 1, 2, 3 — and scaling by `a` just multiplies those heights.

---

## ⚠️ Common Traps

1. **Sign of b in the AOS formula.** `x = −b / (2a)`. If b is already negative (like b = −6), then −b = +6 (the double-negative cancels). Use parens: x = −(−6)/2 = +3.
2. **Forgetting the y-intercept is c.** In standard form ONLY, (0, c) is automatically the y-intercept. Free point — plot it.
3. **Forgetting to mirror the y-intercept.** The y-intercept has a twin on the other side of the AOS at the same height. Easy second point.
4. **Confusing heights with x-distances.** The heights pattern (1, 4, 9) is the **y-jump** from the vertex, not the x-distance. The x-distances are just 1, 2, 3.
5. **Not labeling AOS.** Test rubric wants the dashed AOS line labeled. Easy points.

---

## 🎯 Practice Problems (do all 5)

For each, find: (a) AOS, (b) vertex, (c) y-intercept, (d) one more point using heights pattern.

1. `y = x² − 4x + 3`
2. `y = x² + 2x − 8`
3. `y = 2x² − 8x + 6`
4. `y = −x² + 6x − 5`
5. `y = x² + 4x + 4`

---

## ✅ Answers

1. AOS x = 2. Vertex (2, −1). y-intercept (0, 3). Mirror of y-int at (4, 3). Heights from vertex (a=1): (1,0), (3,0). **x-intercepts at 1 and 3.**
2. AOS x = −1. Vertex (−1, −9). y-int (0, −8). Mirror at (−2, −8). Heights (a=1): (0, −8), (−2, −8) — already plotted. Try (1, −5), (−3, −5). x-intercepts at 2 and −4.
3. AOS x = 2. Vertex (2, −2). y-int (0, 6). Mirror at (4, 6). Heights (a=2): (1, 0), (3, 0). x-intercepts at 1 and 3.
4. AOS x = 3. Vertex (3, 4). Opens DOWN (a=−1). y-int (0, −5). Mirror at (6, −5). Heights (a=−1, so down from vertex): (2, 3), (4, 3). x-intercepts at 1 and 5.
5. AOS x = −2. Vertex (−2, 0). y-int (0, 4). Mirror at (−4, 4). Heights (a=1): (−1, 1), (−3, 1). Just touches x-axis at x=−2 (perfect square trinomial!).

(If you got 4 or 5 right → ✓ done. **If you missed AOS sign — that's THE trap. Redo tomorrow.**)

---

## 🌐 Use Desmos!

Type into https://www.desmos.com/calculator:

`y = ax^2 + bx + c`

Add sliders for a, b, c. Drag them. Watch how:
- **a** flips direction and changes width (same as Topic 7).
- **b** slides the parabola **diagonally** (not just left/right!) — the AOS moves.
- **c** slides it straight up/down — the y-intercept changes.

Then also type `x = -b/(2a)` as a separate equation — Desmos will draw the AOS line. Watch it track the vertex.

---

## 👨 Nate's Tutor Primer

**This topic was added based on Mr. Mistry's May 2026 emailed handout.** It explicitly fills a gap: every other graphing topic gives you the vertex (or roots) directly, but standard form hides it. Real test problems are almost always in standard form, so this technique is the one she'll use most.

When co-working:
- **Drill the AOS formula in isolation first.** Give her 10 quadratics in standard form and ask only "what's the AOS?" — nothing else. Get the formula `x = −b/(2a)` automatic before adding any other steps.
- **The y-intercept-and-mirror trick is huge.** It's two free points (plus the vertex = 3 points) before you even use the heights pattern. Most parabolas can be sketched with just those three points + symmetry.
- **The ax² heights pattern (1, 4, 9) is the unifying skill across topics 7, 8, 9, 14.** Once she has it cold, every graphing topic gets faster. If she doesn't have it yet, that's the highest-leverage drill.
- **Avoid the trap order.** Standard form has THREE common errors stacked on top of each other: sign of b in AOS formula → arithmetic when plugging back for vertex y → forgetting to mirror across AOS. Catch them one at a time; don't try to fix all three at once.

**Connecting the topics:** This is the form she'll be GIVEN. The other graphing forms (vertex Topic 9, intercept Topic 8) are forms she might **convert to** if she wants the vertex or roots without using the AOS formula. Standard ↔ vertex conversion uses **completing the square** (Topic 12). So Topic 14 + Topic 12 = "graph anything."

**Esme's known gap:** Mr. Mistry has repeatedly flagged that graphing is where she loses the most points. Standard form is the most common starting point, so getting confident here is highest-leverage. Pair this with Topic 9 for the most impact.

---

*Next up: review the mock test (Day 16) and target the topics with the most missed points.*
