# Topic 9 — Graphing Parabolas in Vertex Form: y = a(x − h)² + k
**Textbook:** Big Ideas Math, Algebra 1, Section 8.4
**PDF in folder:** `Algebra 2 - downloaded class files/cc19_algebra1_ipe_08_04 (1).pdf`
**Time to learn:** 25–30 min (the most important graphing form)

---

## 🟢 The Big Idea (ELI5)

**Vertex form is the cheat code for graphing parabolas.** It literally hands you the vertex on a silver platter.

`y = a(x − h)² + k`
- **Vertex is (h, k).** Just read it off.
- **a tells direction and width** (same as before).
- **Axis of symmetry is x = h.**

`y = 2(x − 3)² + 1` → Vertex is (3, 1). AOS is x = 3. Opens up (a = 2). Done.

**The only catch: the sign of h flips.** `(x − 3)²` → h = +3, NOT −3.

---

## 📖 Vocab You Need

| Word | What it means |
|------|---------------|
| **Vertex form** | y = a(x − h)² + k |
| **(h, k)** | The vertex coordinates |
| **h** | The horizontal shift — moves the parabola left/right |
| **k** | The vertical shift — moves the parabola up/down |
| **Transformation** | Modern math word for "moving / flipping / stretching" a graph |

---

## 🧾 The Recipe — Graphing from Vertex Form

For `y = a(x − h)² + k`:

1. **Identify h and k.** **Watch the sign of h!**
   - `(x − 3)²` → h = **+3**
   - `(x + 4)²` → h = **−4** (because + is really − of negative)
2. **Plot the vertex** at (h, k).
3. **Determine direction:** a > 0 → opens up. a < 0 → opens down.
4. **Determine width:** |a| > 1 narrower. |a| < 1 wider.
5. **Draw the axis of symmetry** (dashed vertical line at x = h).
6. **Pick 2 x-values on each side** of the vertex. Plug into the equation, get the y-values.
7. **Plot those points and draw a smooth U.**
8. **Label** vertex, AOS, direction.

---

## ✏️ Worked Example

**Graph:** `y = 2(x − 3)² + 1`

Step 1: h = **+3** (sign flips!), k = **+1**, a = **2**.
Step 2: Vertex (3, 1).
Step 3: a is positive → opens **up**.
Step 4: |a| = 2 → narrower than y = x².
Step 5: AOS: x = 3 (dashed line).
Step 6: Pick x-values:
- x = 2 → y = 2(2−3)² + 1 = 2(1) + 1 = 3 → point (2, 3)
- x = 1 → y = 2(1−3)² + 1 = 2(4) + 1 = 9 → point (1, 9)
- x = 4 → y = 2(4−3)² + 1 = 3 → point (4, 3) (mirror of x=2)
- x = 5 → y = 9 → point (5, 9) (mirror of x=1)

Step 7: Plot (3,1), (2,3), (4,3), (1,9), (5,9). Smooth U.
Step 8: Label vertex (3, 1), AOS x = 3, opens up. ✅

---

## 🧠 Mnemonic — "Vertex is the Opposite Sign Inside, Same Sign Outside"

- **Inside the parens** (the h): **flip the sign** to get the vertex x.
- **Outside the parens** (the k): **keep the sign** to get the vertex y.

`y = (x + 5)² − 7` → vertex is (**−5**, **−7**) — flip + to − inside, keep − outside.

Or: **"HK = Hidden inside (flips), Kept outside (stays)."**

---

## 📐 The ax² Heights Pattern (faster than table-of-values)

Once you have the vertex (h, k), don't redo a table — use the **heights pattern**:

| Steps left/right of vertex | y-jump from vertex |
|---|---|
| ±1 | a · 1 = **a** |
| ±2 | a · 4 = **4a** |
| ±3 | a · 9 = **9a** |

For `y = 2(x − 3)² + 1`, the vertex is (3, 1) and a = 2 → heights **2, 8, 18**. So:
- (4, 3) and (2, 3) — 1 step out, up by 2
- (5, 9) and (1, 9) — 2 steps out, up by 8

Memorize **1, 4, 9** as the parent pattern (for a = 1). Multiply by `a` for any other parabola. Same pattern used in Topics 7, 8, and 14.

---

## ⚠️ Common Traps

1. **The sign of h.** `(x − 3)²` → h = +3 (not −3). `(x + 3)²` → h = −3 (not +3). **#1 mistake.**
2. **Forgetting the +k.** Some kids write the vertex as (h, 0) and skip k.
3. **Square the WHOLE binomial** — don't distribute the exponent. `(x − 3)²` is `(x − 3)(x − 3)`, not `x² − 9`. (Same trap as Topic 2.)
4. **Symmetry shortcut:** once you find a point at (vertex_x − 1, y), the mirror point is at (vertex_x + 1, y). Use this to halve your work.

---

## 🎯 Practice Problems (do all 5)

For each, find: (a) vertex (h, k), (b) axis of symmetry, (c) opens up or down, (d) y-value when x = 0.

1. `y = (x − 5)² + 3`
2. `y = −2(x + 1)² − 4`
3. `y = ½(x − 2)²`
4. `y = −(x + 3)² + 7`
5. `y = 3(x − 1)² − 2`

---

## ✅ Answers

1. Vertex **(5, 3)**, AOS x=5, opens **up**, y(0) = (0−5)² + 3 = **28**
2. Vertex **(−1, −4)**, AOS x=−1, opens **down**, y(0) = −2(0+1)² − 4 = **−6**
3. Vertex **(2, 0)**, AOS x=2, opens **up** (wider), y(0) = ½(0−2)² = **2**
4. Vertex **(−3, 7)**, AOS x=−3, opens **down**, y(0) = −(0+3)² + 7 = **−2**
5. Vertex **(1, −2)**, AOS x=1, opens **up**, y(0) = 3(0−1)² − 2 = **1**

(If you got 4 or 5 right → ✓ done. **If you got the signs wrong, that's the topic — redo tomorrow.**)

---

## 🌐 Use Desmos! (essential for this topic)

This is the **best topic for Desmos.** Go to https://www.desmos.com/calculator and type:

`y = a(x - h)^2 + k`

Add sliders for `a`, `h`, `k`. Drag them around. **You will literally see the parabola move.** Five minutes of slider play teaches the topic better than 30 minutes of paper.

What to notice:
- Drag **h** → parabola slides left/right (and the sign is opposite of the direction it moves!).
- Drag **k** → parabola slides up/down (sign matches direction).
- Drag **a** → parabola gets narrower (|a| big), wider (|a| small), or flips (a < 0).

---

## 👨 Nate's Tutor Primer

**This is the most important graphing topic.** If she nails this one, she can convert any quadratic to vertex form (via completing the square — Topic 12) and graph anything. It's the unifying form.

When co-working:
- **Pair this with Desmos.** Don't try to teach vertex form by lecture — show her with the sliders. The visual intuition makes the algebra make sense.
- **The sign of h is the test trap.** Drill it. Write 10 vertex-form equations on a piece of paper. Have her say only the vertex out loud for each. Speed run.
- **Always plot the vertex first, then symmetric pairs of points.** Symmetry saves work and reduces errors.
- **Watch for the `(x + 3)²` → "h = +3" mistake.** This is by far the most common error. Build the mental check: "Plus inside means minus outside."

**"New math" note:** The whole "transformation" framework (shifts, stretches) is modern. You learned this as just "graphing a quadratic" — students today learn it as "transforming the parent function y = x²." Same math, more vocabulary. If she uses words like "translated 3 units right" or "reflected over x-axis," she's speaking modern math fluently — encourage it.

**Big test tip:** When given a problem in standard form (`y = ax² + bx + c`), it's often easier to **convert to vertex form first** (via completing the square — Topic 12) and graph from there. This is especially useful for problems asking for the vertex.

**Esme's known gap:** Per Mr. Mistry's past comments on Practice #18 — she has trouble graphing accurately from vertex form. Allocate the most tutor time to this topic.

---

*Next up: Topic 10 — Solving by Factoring (Zero Product Property).*
