# Topic 8 — Graphing Parabolas in Intercept Form: y = a(x − p)(x − q)
**Textbook:** Big Ideas Math, Algebra 1, Section 8.5
**PDF in folder:** `Algebra 2 - downloaded class files/cc19_algebra1_ipe_08_05 (1).pdf`
**Time to learn:** 25 min

---

## 🟢 The Big Idea (ELI5)

When a parabola is written as `y = a(x − p)(x − q)`, it's **already telling you where it crosses the x-axis** — at `x = p` and `x = q`.

Those two crossings are called **x-intercepts** (or **zeros** or **roots** — all the same thing).

Once you know where the parabola crosses the x-axis, finding the vertex is easy: **the vertex is exactly halfway between them.**

`y = (x − 2)(x − 6)` → crosses at x = 2 and x = 6 → vertex x is halfway: (2+6)/2 = 4 → plug in to find vertex y.

---

## 📖 Vocab You Need

| Word | What it means |
|------|---------------|
| **Intercept form** | y = a(x − p)(x − q) — also called **factored form** |
| **x-intercept** | Where the parabola crosses the x-axis (y = 0). Same as root, zero. |
| **Roots / zeros** | Same as x-intercepts. Three words, one idea. |
| **Sign flip** | The `−` in `(x − p)` means the x-intercept is at `+p`, not `−p`. Watch the sign! |

---

## 🧾 The Recipe — Graphing from Intercept Form

For `y = a(x − p)(x − q)`:

1. **Identify p and q.** Remember: `(x − 5)` means p = +5, NOT −5.
   - Sign flip trap: `(x + 3)` is really `(x − (−3))`, so p = −3.
2. **Plot the x-intercepts** at (p, 0) and (q, 0).
3. **Find the axis of symmetry** = (p + q) / 2.
4. **Find the vertex y-coordinate** by plugging the AOS x-value into the equation.
5. **Plot the vertex.** Note: if a > 0, vertex is min (below x-axis). If a < 0, vertex is max (above).
6. **Determine direction:** a > 0 → opens up. a < 0 → opens down.
7. **Sketch a smooth U through the three points.** Add 1–2 more if needed for accuracy.

---

## ✏️ Worked Example

**Graph:** `y = (x − 1)(x − 5)`

Step 1: p = 1, q = 5 (NOT −1 and −5 — sign flips).
Step 2: x-intercepts at (1, 0) and (5, 0).
Step 3: AOS = (1 + 5)/2 = **3** → x = 3.
Step 4: Vertex y: plug x = 3 → y = (3−1)(3−5) = (2)(−2) = **−4**. Vertex: (3, −4).
Step 5: Plot (1, 0), (3, −4), (5, 0). a = 1 (positive) → opens up.
Step 6: Smooth U through the three points.
Step 7: Label vertex (3, −4), AOS x = 3, x-intercepts (1, 0) and (5, 0). ✅

---

## 🧠 Mnemonic — "PQ → AOS halfway, Vertex underneath"

The roots are **p and q**. The AOS is **halfway** between them. The vertex sits **on the AOS**, find its y by plugging in.

**"P + Q divided by 2"** is the AOS.

Sign trick: **"The sign flips between the parens and the intercept."** `(x − 5)` → root at +5. `(x + 5)` → root at −5.

---

## 📐 The ax² Heights Pattern (for extra points beyond the vertex)

Once you have the vertex from AOS = (p+q)/2, use the **heights pattern** to plot more points:

| Steps left/right of vertex | y-jump from vertex |
|---|---|
| ±1 | a · 1 = **a** |
| ±2 | a · 4 = **4a** |
| ±3 | a · 9 = **9a** |

Memorize **1, 4, 9** for a = 1. Multiply by `a` for any other parabola. Same pattern used in Topics 7, 9, and 14.

---

## ⚠️ Common Traps

1. **Sign flip.** `(x − 3)` means x-intercept at **+3**, not −3. This is the #1 mistake. Highlight the sign.
2. **Forgetting to find the vertex.** The x-intercepts alone are not a graph! You need at least the vertex too.
3. **Computing AOS as p × q or p − q instead of (p + q)/2.** It's the AVERAGE.
4. **Forgetting to plug AOS back in for vertex y.** The vertex isn't on the x-axis (unless the parabola just barely touches).
5. **Not labeling everything.** Test rubric wants vertex, AOS, and both x-intercepts labeled.

---

## 🎯 Practice Problems (do all 5)

For each, find: (a) x-intercepts, (b) axis of symmetry, (c) vertex, (d) direction (up/down).

1. `y = (x − 2)(x − 4)`
2. `y = (x + 1)(x − 5)`
3. `y = (x + 3)(x + 7)`
4. `y = −(x − 2)(x − 6)`
5. `y = 2(x − 1)(x − 3)`

---

## ✅ Answers

1. Roots **(2, 0)** and **(4, 0)**; AOS x=3; vertex **(3, −1)**; opens **up**
2. Roots **(−1, 0)** and **(5, 0)**; AOS x=2; vertex **(2, −9)**; opens **up**
3. Roots **(−3, 0)** and **(−7, 0)**; AOS x=−5; vertex **(−5, −4)**; opens **up**
4. Roots **(2, 0)** and **(6, 0)**; AOS x=4; vertex **(4, 4)**; opens **down** (a is negative!)
5. Roots **(1, 0)** and **(3, 0)**; AOS x=2; vertex **(2, −2)**; opens **up**

(If you got 4 or 5 right → ✓ done. **If you missed the sign flips (problems 2, 3), redo those tomorrow.**)

---

## 🌐 Use Desmos!

Go to https://www.desmos.com/calculator and try:
- `y = (x - 2)(x - 4)` — see roots at 2 and 4
- `y = (x + 1)(x - 5)` — see roots at −1 and 5
- `y = -(x - 2)(x - 6)` — flips upside down

**Slider play:** `y = (x - p)(x - q)` with sliders for p and q. Drag them around. Watch what happens.

---

## 👨 Nate's Tutor Primer

**This topic IS Topic 4/5 in graphing clothing.** If she's solid on factoring, she's already 80% of the way here — she just needs to read off the roots and find the vertex.

When co-working:
- **The sign flip is the killer.** Make her say out loud, "The sign of p in the parens is opposite of the sign of the intercept." Drill it.
- **Always find the vertex.** It's the part she'll skip on the test. Make it part of the recipe, not optional.
- **Use Desmos to verify every problem.** She types the equation, eyes the roots and vertex, compares to her algebra.

**"New math" note:** Modern textbooks emphasize that intercept form = factored form. Same thing. The textbook calls it intercept form because that's the **useful property** — the form makes intercepts visible.

**Big test tip:** Sometimes the test gives a quadratic in standard form (Topic 7) and asks her to graph it. **Strategy: factor it first** to convert to intercept form, then graph from there. This is a more reliable path than computing −b/(2a) for the AOS.

**Connection to factoring:** Every problem here is a factored Topic 4/5 problem. If she has trouble with the algebra, drill those topics first.

---

*Next up: Topic 9 — Graphing Parabolas in Vertex Form.*
