# Topic 3 — Greatest Common Factor (GCF)
**Textbook:** Not a single section — practiced via `Alg2HWPrimeFactors.pdf` and `GreatestCommonFactorandLeastCommonMultiplePracticeGCFandLCMWorksheet-1.pdf`
**Time to learn:** 15–20 min

---

## 🟢 The Big Idea (ELI5)

GCF = **the biggest thing that divides into all the terms.**

It's like asking, "What's the biggest box that fits inside all of these?" Take that box out, and what's left goes in parentheses.

`6x³ + 9x²` → the biggest thing that fits in both `6x³` and `9x²` is `3x²`. Pull it out:
`6x³ + 9x² = 3x²(2x + 3)`

If you multiplied it back out, you'd get `6x³ + 9x²` again. That's how you check.

---

## 📖 Vocab You Need

| Word | What it means |
|------|---------------|
| **Factor** | Something that divides evenly into another number/term. Factors of 12: 1, 2, 3, 4, 6, 12. |
| **Prime number** | Only factors are 1 and itself: 2, 3, 5, 7, 11, 13… |
| **Prime factorization** | Breaking a number into all primes: 12 = 2·2·3 |
| **GCF** | Greatest Common **Factor** — biggest factor shared by all terms |
| **"Factor out"** | Take the GCF out, write the rest in parens |

---

## 🧾 The Recipe — GCF of Numbers

For numbers like "GCF of 12, 18":
1. **List all factors** of each: 12 → 1, 2, 3, 4, 6, 12. 18 → 1, 2, 3, 6, 9, 18.
2. **Find the biggest one shared** → **6**.

Faster trick: **Prime factorize**, then multiply the shared primes.
- 12 = 2·2·3
- 18 = 2·3·3
- Shared: one 2 and one 3 → **GCF = 2·3 = 6** ✅

---

## 🧾 The Recipe — GCF of Polynomial Terms

For `6x³ + 9x²`:

1. **GCF of the numbers** (coefficients): GCF of 6 and 9 = **3**
2. **GCF of the variables:** Take the **smallest power** that's in every term. `x³` and `x²` → smallest power is **x²**.
3. **Combine:** GCF = **3x²**.
4. **Factor it out:** Divide each term by the GCF, put the result in parens.
   - `6x³ ÷ 3x² = 2x`
   - `9x² ÷ 3x² = 3`
   - Answer: `3x²(2x + 3)` ✅
5. **Check by re-multiplying.**

---

## 🧠 Mnemonic — "Smallest Power Wins"

For variables: you can only pull out **the smallest power** that's in every term. (Logical — you can't pull out `x³` from `x²` because `x²` only has 2 x's.)

For numbers: think of prime factorization. **Shared primes, multiplied.**

---

## ✏️ Worked Example

**Factor out the GCF:** `12x⁴ + 18x³ − 6x²`

Step 1: GCF of `12, 18, 6` = **6** (12 = 2·2·3, 18 = 2·3·3, 6 = 2·3 → shared 2·3)
Step 2: Smallest power of x present = **x²** (powers are 4, 3, 2)
Step 3: GCF = **6x²**
Step 4: Divide each term:
- `12x⁴ ÷ 6x² = 2x²`
- `18x³ ÷ 6x² = 3x`
- `−6x² ÷ 6x² = −1`
Answer: **`6x²(2x² + 3x − 1)`** ✅

Check: `6x²·2x² = 12x⁴` ✓, `6x²·3x = 18x³` ✓, `6x²·(−1) = −6x²` ✓.

---

## ⚠️ Common Traps

1. **Forgetting the "−1" when a term equals the GCF.** `−6x² ÷ 6x² = −1`, NOT 0. Many kids leave it blank — wrong!
2. **Pulling out too much.** You can only pull `x²` from `x³` and `x²` — not `x³`.
3. **Pulling out too little.** Always check: is there a *bigger* GCF you missed? Especially with numbers — kids find a common factor but not the *greatest*.
4. **Forgetting to check by multiplying back out.** This catches every mistake.

---

## 🎯 Practice Problems (do all 5)

1. Find the GCF of 24 and 36.
2. Factor out the GCF: `4x² + 12x`
3. Factor out the GCF: `15x³ − 10x²`
4. Factor out the GCF: `8x² + 4x − 12`
5. Factor out the GCF: `9x⁴ + 6x³ − 3x²`

---

## ✅ Answers

1. **12** (24 = 2·2·2·3, 36 = 2·2·3·3 → shared: 2·2·3 = 12)
2. `4x(x + 3)`
3. `5x²(3x − 2)`
4. `4(2x² + x − 3)` (no x is common — third term has no x!)
5. `3x²(3x² + 2x − 1)`

(If you got 4 or 5 right → ✓ done. **Common error to watch:** problem #4 — the constant `−12` has no x, so you can only pull out the number 4, no x.)

---

## 👨 Nate's Tutor Primer

**This is foundational.** GCF is step 1 of EVERY factoring problem from here on. If she skips it, harder factoring problems become impossible.

When co-working:
- **Always check: "Is there a GCF first?"** Make this her reflex before any factoring problem. Tape it to the wall.
- **For variable GCF, use the phrase "smallest power wins."** Don't try to explain why — just install the rule.
- **Prime factorization is your friend** for finding number GCF if she's shaky on factor lists. Her textbook spends time on this (Alg2HWPrimeFactors.pdf).
- **Watch the −1 trap** in problem #4 / #5 style problems. When a term equals the GCF exactly, it leaves a `1` (or `−1`) behind, not zero.

**"New math" note:** Same as how you learned it. Just make sure she always checks by re-multiplying — that's the modern emphasis on "verify your work."

---

*Next up: Topic 4 — Factoring Trinomials (Basic).*
