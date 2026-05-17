# Topic 12 — Solving Quadratics by Completing the Square
**Textbook:** Big Ideas Math, Algebra 1, Section 9.4
**PDF in folder:** `Algebra 2 - downloaded class files/cc19_algebra1_ipe_09_04 (1).pdf`
**Time to learn:** 25–30 min (this is one of the harder topics)

---

## 🟢 The Big Idea (ELI5)

**You take a quadratic that's NOT a nice square, and you FORCE it to become one by adding a specific number.** Then you can use the square root method (Topic 11).

The trick: take half of the middle coefficient (b), square it, and add it to both sides. Magic — the left side becomes a perfect square trinomial that factors into `(x + something)²`.

It's like making a stew that's missing one ingredient. You know exactly what's missing to make it whole.

---

## 📖 Vocab You Need

| Word | What it means |
|------|---------------|
| **Perfect square trinomial** | A trinomial that factors into something squared, like `x² + 6x + 9 = (x + 3)²` |
| **Complete the square** | The process of adding the right number to make a perfect square trinomial |
| **(b/2)²** | The magic number: half of b, squared. This is what you add. |

---

## 🧾 The Recipe (when a = 1)

For `x² + bx + c = 0`:

1. **Move c to the right side.** `x² + bx = −c`
2. **Find (b/2)².** Half the middle coefficient, squared.
3. **Add (b/2)² to BOTH sides.** Now the left side is a perfect square trinomial.
4. **Factor the left side** as `(x + b/2)²`.
5. **Take square root of both sides.** Don't forget ±.
6. **Solve for x.**

### When a ≠ 1: Divide through by a first.

---

## ✏️ Worked Example (a = 1)

**Solve:** `x² + 6x − 7 = 0`

Step 1: Move c: `x² + 6x = 7`
Step 2: (b/2)² = (6/2)² = 3² = **9**
Step 3: Add 9 to both sides: `x² + 6x + 9 = 7 + 9` → `x² + 6x + 9 = 16`
Step 4: Factor left: `(x + 3)² = 16`
Step 5: Square root: `x + 3 = ±4`
Step 6: Solve: x = −3 + 4 = **1** OR x = −3 − 4 = **−7**

Solutions: **x = 1 or x = −7** ✅

(Check: `1² + 6(1) − 7 = 1 + 6 − 7 = 0` ✓)

---

## ✏️ Worked Example (a = 1 with non-integer answer)

**Solve:** `x² − 4x − 1 = 0`

Step 1: Move c: `x² − 4x = 1`
Step 2: (b/2)² = (−4/2)² = (−2)² = **4**
Step 3: Add 4: `x² − 4x + 4 = 5`
Step 4: Factor: `(x − 2)² = 5`
Step 5: √: `x − 2 = ±√5`
Step 6: **x = 2 ± √5** (leave in exact form unless asked for decimal)

---

## 🧠 Mnemonic — "Half, Square, Add to Both"

Half of b. Square it. Add it to both sides. **Half-Square-Add-Both.**

Or: **"HSAB"** — say it before every problem.

Visual phrase: **"I'm forcing the left side to become a square."**

---

## ⚠️ Common Traps

1. **Forgetting to add to BOTH sides.** Algebra rule — what you do to one side, you do to the other.
2. **Sign error on (b/2)².** It's always positive (because squared). `(b/2)²` of b = −6 is `(−3)² = +9`, not −9.
3. **Forgetting the ±** at the square-root step.
4. **Trying it when a ≠ 1 without dividing first.** Step 0: if there's a coefficient on x², divide every term by it first.
5. **Forgetting to simplify the right side.** After adding, **add** the numbers: e.g., 7 + 9 = 16 (not "7 + 9").

---

## 🎯 Practice Problems (do all 5)

1. `x² + 4x − 5 = 0`
2. `x² − 6x + 8 = 0`
3. `x² + 8x = 9`
4. `x² − 2x − 8 = 0`
5. `x² + 10x + 21 = 0`

---

## ✅ Answers

1. (b/2)² = 4. Add: (x+2)² = 9. √: x+2 = ±3 → **x = 1 or x = −5**
2. (b/2)² = 9. Add: (x−3)² = 1. √: x−3 = ±1 → **x = 4 or x = 2**
3. (b/2)² = 16. Add: (x+4)² = 25. √: x+4 = ±5 → **x = 1 or x = −9**
4. (b/2)² = 1. Add: (x−1)² = 9. √: x−1 = ±3 → **x = 4 or x = −2**
5. (b/2)² = 25. Add: (x+5)² = 4. √: x+5 = ±2 → **x = −3 or x = −7**

(If you got 3+ right → ✓ done. **This topic is harder — 2 right is fine, just plan to revisit.**)

---

## 👨 Nate's Tutor Primer

**This is the trickiest of the solving methods** because there are more steps. Esme will need extra practice here. **Budget more time.**

When co-working:
- **Write each step on a new line. Always.** This topic punishes mental math.
- **The (b/2)² step is the hinge.** Have her say out loud: "Half of b is __. Squared is __. I add __ to both sides."
- **Color-code if it helps.** One color for left side moves, one for right side moves. Helps tracking.
- **Use easier examples first** (where the answer is whole numbers). Once she trusts the method, hit her with one that gives an irrational answer (`x² − 4x − 1 = 0` → x = 2 ± √5).

**"New math" note:** Same method, same name. Some textbooks include a visual aid called "**algebra tiles**" — physical or virtual tiles arranged into a literal square. If Mr. Mistry has used these, that's where the name "completing the square" comes from visually. Virtual tile tool: https://www.mathlearningcenter.org/apps/algebra-tiles

**Why bother learning this?** Two reasons:
1. It's how you convert standard form to vertex form (graphing).
2. It's the proof / derivation of the quadratic formula (Topic 13).

**Test-taking tip:** If a problem says "complete the square," she MUST use this method (even if factoring would work). If it just says "solve," she can pick any method — factoring (Topic 10) is usually faster.

---

*Next up: Topic 13 — The Quadratic Formula (the universal hammer).*
