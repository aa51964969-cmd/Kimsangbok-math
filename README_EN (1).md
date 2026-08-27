# Sangbun Vector Theory · T-Function Theory

**Sangbok Kim** — Independent Mathematics Researcher, Chuncheon, Gangwon-do, Republic of Korea

This repository provides public access to two independent branches of mathematics research that I have developed.
Papers and graph materials may be freely downloaded and used.

---

## 1. Sangbun Vector Theory

A geometric and vector theory developed since 2000.
It constructs direction vectors from points on a curve using only **finite Euclidean constructions**. The key feature of this approach is that it does not rely on calculus.

- Fundamental relation: **AA₁₂ = AA₆ + AA₁₁**
- Geometric invariant governing the branches: **@ = |OA₁| / |AA₁|**
- Complete branch formulas for @<1, @>1, and @=1 in the three modes Z1 · Z2 · Z3

### Four Vector Laws

| Law | Description |
|---|---|
| Balance Law | Balance structure of vector addition |
| Limit Direction Law | Convergence to ±45° in the limit |
| Sangbun Slope Transformation | Sangbun transformation relation of slopes |
| Oscillation Mean Recovery | Recovery property of the mean value of oscillation |

### Closed-Form Compression

The nine points A3a–A5b are absorbed into a single scalar λ, and A10′ is eliminated by a sign expression, yielding a direct calculation formula that bypasses the A1–A12 chain.
In the rotated coordinate system (τ, β), rotational invariance was confirmed from A7 onward.

---

## 2. T-Function Theory

A separate theory begun in May 2026. **It is independent of Sangbun Vector Theory.**

Instead of the gamma function, it uses the combinatorial sequence **T(p, q)** to calculate factorials of integers, fractions, and complex numbers.

- Derivation of a closed form for T(p, q)
- Fractional-factorial interpolation and a complex-factorial formula
- Discovery of the constant **C = lim(S(n) − H(n)) ≈ −0.8660648296…**
  - Verified to more than 60 digits with mpmath
  - Precision of more than 200 digits achieved through an integral representation using the exponential integral Ei
  - PSLQ searches did not yield a closed form as a combination of standard constants

---

## Repository Structure

```
sangbun/     Sangbun Vector Theory — papers, new laws, graph collections, and videos
t-function/  T-Function Theory — papers and computational materials
```

## If a PDF Does Not Open

GitHub Preview may sometimes display **"Unable to render code block."**
This is an issue with the GitHub viewer, not with the file itself.
Use **⋯ → Download** in the upper-right corner to download and open the file normally.

## Citation

Please use the OSF DOI for formal citations.

> Kim, Sangbok. *Sangbun Vector Theory*. OSF.
> https://doi.org/10.17605/OSF.IO/G9KJW

## License

[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.en) — You are free to use the materials with appropriate attribution.

## About the Research Process

Sangbun Vector Theory was developed entirely through hand calculations for 25 years, beginning in 2000.
Since April 2025, I have used AI as a partner for calculation and documentation, allowing me to verify and organize parts that had previously been difficult to check by hand.
All results were developed independently by me, and the record also documents the process of identifying errors introduced into AI-assisted drafts and issuing corrections.

---

*Please leave questions or comments in the Issues tab.*
