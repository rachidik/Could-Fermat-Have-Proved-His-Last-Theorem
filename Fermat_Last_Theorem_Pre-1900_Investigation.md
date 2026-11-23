# Could Fermat Have Proved His Last Theorem? A Pre-1900 Investigation

Nov 22, 2026 · @Rachid EL BAJI

## Verdict in brief

No complete proof of Fermat's Last Theorem is known that uses only mathematics from before 1900, and Fermat almost certainly did not have one. Yet nobody can prove that such a proof is impossible. What can be proved is exactly where each classical method stops.

- **Descent**, Fermat's own method, proves the exponents 4 and 3 completely. Both proofs are given in full below, with no tool later than 1763.
- **Congruences**, Sophie Germain's method, provably cannot finish. For exponent 5 they show that 32,341,210 divides xyz, and nothing stronger.
- **Factorization**, the method of Lamé and Kummer, is the strongest pre-1900 route. It proves the theorem for every exponent divisible by 4 or by a regular prime, and it stalls at 37.
- **Logic** supplies no impossibility theorem. Specialists expect the theorem to be provable in elementary arithmetic in principle, but no short elementary proof is known.

The historical record points the same way. Fermat never repeated the general claim, wrote out a proof for one exponent only, and was wrong about another result he credited to descent.

## Ground rules and the pre-1900 toolbox

Every claim below carries one of four labels, and every tool used inside a proof is dated before 1900.

| Label | Meaning |
| --- | --- |
| **\[Fact\]** | Documented history, sourced in the last section |
| **\[Math\]** | A theorem with a complete proof, given here or in the cited literature |
| **\[Reconstruction\]** | A proof strategy assembled for this article from period tools |
| **\[Speculation\]** | A judgment about Fermat's thinking that no document settles |

The toolbox, oldest first:

| Tool | Origin | Used here for |
| --- | --- | --- |
| Unique factorization of integers; coprime factors of a perfect power are perfect powers | Euclid, Elements VII–IX, about 300 BC | Every proof |
| Formula for Pythagorean triples | Euclid, Elements X | Exponent 4 |
| Chord and tangent substitutions for new rational solutions | Diophantus, 3rd century; Fermat | The chord remark under impossibility |
| Chinese remainder theorem | Sunzi, 3rd to 5th century; Gauss 1801 | The ceiling on congruences |
| Composition identity for a² + Nb² | Brahmagupta, 7th century | Exponent 3 |
| Infinite descent | Fermat; described in his 1659 letter | Exponents 4 and 3 |
| Fermat's little theorem | Fermat 1640; proof by Euler 1736 | Kummer's first case |
| Derivative of a polynomial | Newton and Leibniz, 1660s–80s | Polynomial analogue only |
| Bernoulli numbers | Jakob Bernoulli, 1713 | Kummer's regularity test |
| Prime divisors of a² + 3b² | Stated by Fermat; proved by Euler 1759–63 | Exponent 3 |
| Reduced quadratic forms and class number | Lagrange 1773; Gauss 1801 | The break at 23 |
| Congruences, power residues modulo primes and prime powers, roots of unity | Gauss, Disquisitiones Arithmeticae, 1801 | Germain's theorem; the ceiling on congruences; factorization |
| Factor relations for xᵖ + yᵖ | Barlow 1810; Abel 1823 | First reductions |
| Sophie Germain's theorem | Germain, by 1819; printed by Legendre 1823–27 | First case |
| Jacobi sums | Jacobi 1827–37 | Why Germain's plan fails |
| Cyclotomic integers, ideal numbers, units, regular primes | Kummer 1844–50 | The strongest route |
| Genus formula for maps between curves | Riemann 1857; Hurwitz 1891 | One remark on descent |

Origins for Fermat, Euler, Germain and Kummer are sourced in the last section. The other rows are standard reference dates.

Later material appears in two flagged roles only. Modern computation re-checks period arithmetic. Results after 1900 (Dickson 1909, Jensen 1915, mathematical logic) are cited to judge the methods, never inside a proof.

## What Fermat actually wrote and proved

Fermat left one private sentence claiming a general proof, and one written proof, for the exponent 4. **\[Fact\]**

| Year | What the record shows |
| --- | --- |
| 1630s | Fermat writes the claim in the margin of his 1621 Diophantus. The usual date is about 1637. The annotated copy is lost. |
| 1636–1657 | His letters set the cases n = 3 and n = 4 as challenges. The general claim never appears again. |
| 1640–1658 | He conjectures that every number 2^(2^n) + 1 is prime, and says he has no proof. |
| 1659 | His summary letter to Carcavi lists results obtained by descent. It names cubes, not all powers. It also includes the claim about 2^(2^n) + 1. |
| 1670 | His son Samuel prints the marginal note, five years after Fermat's death. |
| 1732 | Euler shows that 641 divides 2^32 + 1. The 1659 claim was false. |
| 1770 | Euler prints a proof for n = 3 that contains a gap. |
| 1819–1823 | Germain proves her theorem on the first case. Legendre prints it. |
| 1825 | Dirichlet and Legendre settle n = 5. |
| 1839 | Lamé settles n = 7. |
| 1847 | Lamé announces a general proof. Liouville and Kummer point out that it assumes unique factorization, which fails. |
| 1847–1850 | Kummer proves the theorem for all regular primes. |
| 1857 | Kummer's criteria cover 37, 59 and 67, hence every exponent below 100. Vandiver later corrected part of the argument. |
| 1995 | Wiles, with Taylor, publishes a proof by modern methods. |

The marginal claim ends: *cuius rei demonstrationem mirabilem sane detexi. Hanc marginis exiguitas non caperet.* It survives only in the 1670 printing.

The single proof in Fermat's surviving work shows that no right triangle with whole-number sides has a square area. That statement yields the exponent 4.

Sources for this table: [MacTutor](https://mathshistory.st-andrews.ac.uk/HistTopics/Fermat%27s_last_theorem/), [St John's College](https://www.joh.cam.ac.uk/node/2312), [MathPages](https://mathpages.com/home/kmath195/kmath195.htm), [Wikipedia on specific exponents](https://en.wikipedia.org/wiki/Proof_of_Fermat%27s_Last_Theorem_for_specific_exponents), [Corry](https://www.tau.ac.il/~corry/publications/articles/pdf/FLT%20-%20SWAC.pdf), [Encyclopedia of Mathematics](https://encyclopediaofmath.org/wiki/Fermat_last_theorem).

## First reductions: what any proof must face

Only the exponent 4 and the odd prime exponents need proof. **\[Math\]** If n = km, a solution for n gives the solution (xᵏ, yᵏ, zᵏ) for m. Every n > 2 is divisible by 4 or by an odd prime.

One may also assume that no two of x, y, z share a factor. A prime dividing two of them divides the third and can be removed.

For an odd prime p, move everything to one side, xᵖ + yᵖ + zᵖ = 0, and split off a linear factor:

```latex
-z^p = x^p+y^p = (x+y)\,\Phi(x,y),\qquad \Phi(x,y)=x^{p-1}-x^{p-2}y+\cdots+y^{p-1}
```

**Lemma 1 \[Math; Barlow 1810, Abel 1823\].** If x and y are coprime, the only prime that can divide both x + y and Φ(x, y) is p.

*Proof.* Modulo x + y we have x ≡ −y, and each of the p terms of Φ becomes yᵖ⁻¹. So Φ ≡ p·yᵖ⁻¹. A common prime factor cannot divide y, so it divides p. ∎

Since Germain's time the problem is split in two. **\[Fact\]** In the *first case* p divides none of x, y, z. In the *second case* p divides exactly one of them.

In the first case the two factors are coprime, so each is a p-th power. The same holds for the other two pairs:

```latex
x+y=c^p,\qquad y+z=a^p,\qquad z+x=b^p,\qquad \Phi(x,y)=\gamma^p,\qquad z=-c\gamma
```

**\[Reconstruction\]** These relations were within Fermat's reach, and they look decisive. They are not. They restrict a solution without contradicting it, and the section on congruences shows why reasoning of that kind cannot close the gap.

## Descent where it works: the exponent 4

The equation x⁴ + y⁴ = z² has no solution in positive integers, which settles n = 4. **\[Math\]** The proof uses three tools: Euclid's formula for Pythagorean triples, the rule that coprime factors of a square are squares, and descent.

1. Take a solution with z as small as possible. Then x and y are coprime: a common prime d would give the smaller solution (x/d, y/d, z/d²).
2. x and y are not both odd, since then z² ≡ 2 (mod 4). Say y is even. Then x², y², z form a primitive Pythagorean triple.
3. Euclid's formula gives coprime m > n > 0, one even and one odd, with x² = m² − n², y² = 2mn, z = m² + n².
4. In x² + n² = m² the number x is odd, so n is even and m is odd. Euclid's formula again gives coprime r, s with n = 2rs and m = r² + s².
5. Now (y/2)² = rs(r² + s²). The three factors are coprime in pairs, so each is a square: r = a², s = b², r² + s² = c².
6. Hence a⁴ + b⁴ = c² with c ≤ c² = m < z. This contradicts the choice of z. ∎

**\[Fact\]** Fermat's own version proves a sister statement: no right triangle with whole-number sides has a square area. Frénicle (1676) and Euler (1738) printed later proofs. The version above is the usual modern form.

**Why it closes. \[Reconstruction\]** Reading the steps backwards gives fixed formulas:

```latex
x=a^4-b^4,\qquad y=2abc,\qquad z=c^4+4a^4b^4
```

Every solution would be the image of a smaller one under one polynomial map of degree 4. Descent says this map can always be undone. That structural fact returns in the section on impossibility.

## The cube case: a complete descent, with Euler's gap repaired

The equation x³ + y³ = z³ has no solution in nonzero integers, and the proof needs only tools that Fermat used or stated. **\[Math\]**

**\[Fact\]** Fermat listed this result in 1659 and left no proof. Euler's printed proof of 1770 has a gap at the lemma on cubes below. His own results of 1759–63 on the form a² + 3b² fill it.

The symbol √−3 serves as bookkeeping only. The product (c + d√−3)(e + f√−3) abbreviates the pair (ce − 3df, cf + de). The fact behind it is an identity between integers:

```latex
(c^2+3d^2)(e^2+3f^2)=(ce-3df)^2+3(cf+de)^2
```

**Lemma 2 (division) \[Math; Euler\].** Let P = c² + 3d² be a prime, or P = 4. Let a, b be coprime, with P dividing a² + 3b². Then, after a suitable choice of the sign of d, there are coprime e, f with

```latex
a+b\sqrt{-3}=(c+d\sqrt{-3})(e+f\sqrt{-3}),\qquad a^2+3b^2=P\,(e^2+3f^2)
```

*Proof.* P divides (ad − bc)(ad + bc), because this product equals d²(a² + 3b²) − b²(c² + 3d²). Choose the sign of d so that P divides ad − bc. (For P = 4, a and b are odd, so 4 divides a − b or a + b.) In the identity (ac + 3bd)² + 3(ad − bc)² = P(a² + 3b²), the right side and the second term are divisible by P². So P divides ac + 3bd. Put e = (ac + 3bd)/P and f = (bc − ad)/P. Direct substitution gives both displayed equations. A common factor of e and f would divide a and b. ∎

**Lemma 3 (divisors) \[Math; Euler 1759–63\].** If a and b are coprime, every odd prime factor of a² + 3b² has the form c² + 3d².

*Proof by descent.* Let P be the smallest odd prime that divides such a number and lacks this form. Replace a, b by their least remainders modulo P. Then a² + 3b² = PQ with Q < P, because a² + 3b² < P². Divide out the square of gcd(a, b), which is prime to P; the cofactor Q only shrinks. If Q is even, then a and b are odd, exactly one factor 4 is present, and Lemma 2 removes it. Every odd prime factor of Q is smaller than P, so it has the form c² + 3d², and Lemma 2 removes it too. What remains is P = e² + 3f², a contradiction. ∎

**Lemma 4 (cubes) \[Math\].** Let a, b be coprime, with a² + 3b² = s³ and s odd. Then a + b√−3 = (e + f√−3)³ for some coprime e, f. Explicitly:

```latex
a=e(e-3f)(e+3f),\qquad b=3f(e-f)(e+f),\qquad s=e^2+3f^2
```

*Proof.* Write s as a product of odd primes Pᵢ = cᵢ² + 3dᵢ², using Lemma 3. Apply Lemma 2 three times for each prime. The result is a + b√−3 = ±∏(cᵢ ± dᵢ√−3), with three factors per prime. For equal primes all signs agree. Otherwise the product would contain (c + d√−3)(c − d√−3) = P, and P would divide both a and b. So the product is a cube, and −1 is a cube as well. ∎

**Theorem \[Math\].** The equation x³ + y³ + z³ = 0 has no solution with xyz ≠ 0.

1. Take a solution, coprime in pairs. Exactly one member is even. Call it z, and choose |z| as small as possible.
2. Put x = u + v and y = u − v. Then u, v are coprime, one even and one odd, and −z³ = 2u(u² + 3v²). Neither is zero: u = 0 gives z = 0, and v = 0 gives 2x³ = −z³.
3. u² + 3v² is odd and 8 divides z³, so u is even and v is odd. The only prime that can divide both 2u and u² + 3v² is 3.
4. **If 3 does not divide u,** the two factors are coprime cubes: 2u = r³ and u² + 3v² = s³. Lemma 4 gives u = e(e − 3f)(e + 3f) and v = 3f(e − f)(e + f), with e even and f odd.
5. Then 2e, e − 3f, e + 3f are coprime in pairs, because e divides u and so is prime to 3f, and e ± 3f are odd. Their product is r³, so they are cubes k³, l³, m³, and l³ + m³ = k³.
6. Here k is even and nonzero, and |z|³ = |k|³·|e² − 9f²|·(u² + 3v²) ≥ 3|k|³. So |k| < |z|, against step 1.
7. **If 3 divides u,** write u = 3w. Then −z³ = 18w(3w² + v²) with coprime factors, so 18w = r³ and v² + 3w² = s³. Lemma 4 gives v = e(e − 3f)(e + 3f) and w = 3f(e − f)(e + f), with e odd and f even.
8. Now 18w = 27·2f(e − f)(e + f). So 2f, e − f, e + f are coprime cubes k³, l³, m³, with k³ + l³ = m³. Again k is even and nonzero, and |z|³ ≥ 27|k|³. Contradiction. ∎

**Why it closes. \[Reconstruction\]** Two facts about a² + 3b² did all the work. Its prime divisors have the same form, and its cubes arise only by composition. Unwinding the steps writes x, y, z as fixed polynomials of degree 9 in k, l, m.

## Why the pattern strains at 5 and 7

For p = 5 and p = 7 a descent still exists, but each exponent demanded new machinery, and the direct method went no further. **\[Fact\]**

Gauss showed in 1801 that 4Φ is always a quadratic expression Y² ± pZ² in two auxiliary forms Y and Z of degree (p − 1)/2. **\[Math\]** The first three cases, checked symbolically for this article:

```latex
4\Phi_3=(2x-y)^2+3y^2
```

```latex
4\Phi_5=(2x^2-xy+2y^2)^2-5(xy)^2
```

```latex
4\Phi_7=(2x^3-x^2y-xy^2+2y^3)^2+7\,\bigl(xy(x-y)\bigr)^2
```

**Exponent 3. \[Reconstruction\]** Y and Z are linear in x and y. Knowing that Y + Z√−3 is a cube therefore hands back x and y themselves, and the descent closes inside one equation.

**Exponent 5. \[Fact\]** Y and Z are quadratic, so a fifth-power statement about Y² − 5Z² does not return x and y directly. Dirichlet and Legendre (1825) split the second case in two and descended through companion equations. They needed the arithmetic of a² − 5b², where Pell's equation supplies infinitely many unit factors.

**Exponent 7. \[Fact\]** The classical proofs (Lamé 1839, simplified by Lebesgue 1840) turn on an identity special to seventh powers:

```latex
(x+y+z)^7-(x^7+y^7+z^7)=7(x+y)(y+z)(z+x)\left[(x^2+y^2+z^2+xy+yz+zx)^2+xyz(x+y+z)\right]
```

MacTutor's history reads Lamé's proof as a sign that larger exponents needed a wholly new idea. The exponents 11, 13, 17 and 19 were first reached by Kummer's theory, not by a direct descent.

**The lesson. \[Reconstruction\]** Each new prime required the arithmetic of a larger number system: a² + 3b² for 3, a² − 5b² for 5, a one-off identity for 7. The pattern does not continue with ordinary integers alone.

## Congruences: Germain's theorem and why her plan fails

Congruence arguments prove real restrictions on a solution, but for each exponent they stop at one fixed divisibility statement. **\[Math\]**

**Germain's theorem \[Math; Germain by 1819, printed 1823–27\].** Let p be an odd prime and θ a prime with two properties:

- (i) no two nonzero p-th power residues modulo θ differ by 1;
- (ii) p is not a p-th power residue modulo θ.

Then every solution of xᵖ + yᵖ + zᵖ = 0 has p dividing xyz.

1. Condition (i) says: if xᵖ + yᵖ + zᵖ ≡ 0 (mod θ), then θ divides xyz. Otherwise (x/z)ᵖ and (−y/z)ᵖ would differ by 1.
2. Suppose a solution, coprime in pairs, with p not dividing xyz. The factor relations give y + z = aᵖ, z + x = bᵖ, x + y = cᵖ, Φ(y, z) = αᵖ, Φ(x, y) = γᵖ.
3. By step 1, θ divides one of x, y, z; say x. Then bᵖ + cᵖ + (−a)ᵖ = 2x ≡ 0 (mod θ), so θ divides abc, by step 1 again.
4. θ cannot divide b or c: from θ | b we would get θ | z + x and then θ | z. So θ divides a, that is, y ≡ −z (mod θ).
5. Then αᵖ = Φ(y, z) ≡ p·yᵖ⁻¹ and γᵖ = Φ(x, y) ≡ yᵖ⁻¹ (mod θ). So p ≡ (α/γ)ᵖ, against (ii). ∎

**Example. \[Math\]** For p = 5 take θ = 11. The fifth-power residues are 1 and 10, so (i) and (ii) both hold. The first case is impossible for p = 5.

**\[Fact\]** Germain found such a θ for every prime below 100, and Legendre extended the table below 197. **\[Math; computed\]** A recomputation agrees. Some θ = 2Np + 1 with N ≤ 8 works for every odd prime p < 197, while p = 197 needs N = 19, θ = 7487.

**The grand plan. \[Fact\]** Germain hoped to show that, for each p, infinitely many primes θ satisfy (i). Each of them would divide xyz, so no nonzero solution could exist.

**Why it fails. \[Math\]** Only primes θ ≡ 1 (mod p) matter, since otherwise every residue is a p-th power. For those, Jacobi sums (1837) count the solutions of Xᵖ + Yᵖ = 1 modulo θ:

```latex
N=\theta-(p-1)+E,\qquad |E|\le (p-1)(p-2)\sqrt{\theta}
```

Only 2p of these solutions have XY = 0. Any other solution yields two consecutive residues, (−X)ᵖ and Yᵖ. So condition (i) must fail as soon as

```latex
\theta\ \ge\ (p-1)^2(p-2)^2+6p-2
```

**\[Fact\]** Libri claimed this finiteness in 1829. Pépin and Pellet confirmed it later in the century, and Dickson published explicit bounds in 1909.

Checking every prime below the bound gives the complete lists. **\[Math; computed\]**

| p | Bound | Every odd prime θ satisfying (i) |
| --- | --- | --- |
| 3 | 20 | 7, 13 |
| 5 | 172 | 11, 41, 71, 101 |
| 7 | 940 | 29, 71, 113, 491 |
| 11 | 8,164 | 23, 89, 947, 1409 |
| 13 | 17,500 | 53, 131, 443, 521 |
| 17 | 57,700 | 137, 239, 443, 1667, 4013 |

**\[Fact\]** Germain herself proved the first line, and Legendre presumed the second.

**The ceiling. \[Math\]** Call a prime *forced* if congruences modulo its powers show that it divides xyz. The forced primes are 2, the primes in the table, and p itself when the first case is impossible modulo p². Let M be their product.

| p | Forced primes | M |
| --- | --- | --- |
| 3 | 2, 3, 7, 13 | 546 |
| 5 | 2, 5, 11, 41, 71, 101 | 32,341,210 |
| 7 | 2, 29, 71, 113, 491 | 228,478,994 |

Then M divides xyz in every solution. Conversely, for every modulus m the congruence xᵖ + yᵖ ≡ zᵖ (mod m) has a solution in which gcd(xyz, m) divides M. So no congruence, to any modulus, can prove more than “M divides xyz”.

*Proof of the converse.* For a forced prime θ, the triple (1, θ, z) with zᵖ = 1 + θᵖ exists modulo every power of θ, and θ divides its xyz exactly once. For any other prime, a solution with xyz prime to it exists modulo the prime (modulo p² for the prime p) and lifts to every higher power by successive approximation. The Chinese remainder theorem combines them. ∎

Sources: [Laubenbacher and Pengelley](https://ar5iv.arxiv.org/html/0801.1809) for Germain, Libri, Pellet and Dickson; [MacTutor](https://mathshistory.st-andrews.ac.uk/HistTopics/Fermat%27s_last_theorem/) for Legendre's extension.

## Factorization: Lamé's error and Kummer's repair

Factoring xᵖ + yᵖ completely is the strongest idea available before 1900. It proves the theorem for every regular prime, and nothing uniform beyond them. **\[Math\]**

With ζ a primitive p-th root of unity:

```latex
x^p+y^p=\prod_{k=0}^{p-1}\bigl(x+\zeta^k y\bigr)
```

**Lamé's attempt. \[Fact\]** On 1 March 1847 Lamé treated the numbers a₀ + a₁ζ + a₂ζ² + … like ordinary integers. Coprime factors of a p-th power would then be p-th powers, and a descent would follow. Liouville objected that unique factorization was unproved. Kummer had already shown in 1844 that it fails.

**Where it fails. \[Math\]** Unique factorization holds for p ≤ 19 and fails at p = 23. A trace is visible with tools from 1801. The forms x² + xy + 6y² and 2x² ± xy + 3y² all have discriminant −23 and are inequivalent. Correspondingly, the number 6 has two different factorizations into irreducible numbers:

```latex
6 = 2\cdot 3=\frac{1+\sqrt{-23}}{2}\cdot\frac{1-\sqrt{-23}}{2}
```

Both lie inside the 23rd cyclotomic integers.

**Kummer's repair. \[Fact\]** In 1846–47 he introduced ideal numbers, for which unique factorization holds again. The class number h measures the gap between ideal and actual numbers. A prime p is *regular* if p does not divide h.

**Theorem \[Math; Kummer 1847–50\].** Fermat's Last Theorem holds for every regular prime.

*First case, p ≥ 5.* Assume xᵖ + yᵖ = zᵖ, coprime in pairs, with p not dividing xyz. Write λ = 1 − ζ.

1. The factors x + ζᵏy are coprime in pairs. A common ideal prime would divide λx and λy, hence λ. Then p would divide x + y and so z, against the assumption.
2. Each factor is therefore an ideal p-th power. By regularity it comes from a number: x + ζy = ε·αᵖ with ε a unit.
3. Kummer supplies two facts. The unit ε is a power ζʳ times a real unit, and αᵖ is congruent to an ordinary integer modulo p. Comparing x + ζy with its complex conjugate gives the congruence displayed below the list.
4. The powers 1, ζ, …, ζᵖ⁻² are independent modulo p. Unless two of the four exponents coincide, p divides x and y. The coincidences leave only x ≡ y (mod p).
5. The same argument applied to xᵖ + (−z)ᵖ = (−y)ᵖ gives x ≡ −z. Then 0 = xᵖ + yᵖ − zᵖ ≡ 3x (mod p), by Fermat's little theorem. So p divides x, a contradiction. ∎

```latex
x+\zeta y-\zeta^{2r}x-\zeta^{2r-1}y\equiv 0 \pmod p
```

*Second case.* It needs Kummer's lemma on units: a unit congruent to an integer modulo p is a p-th power. It then descends on the power of λ dividing z. Both steps require regularity. The proof is not reproduced here.

**The test. \[Math; Kummer\]** A prime p is regular exactly when it divides none of the numerators of the Bernoulli numbers B₂, B₄, … up to index p − 3.

**\[Math; computed\]** Recomputed for this article: the irregular primes below 100 are 37, 59 and 67. For instance, 37 divides the numerator of B₃₂ = −7709321041217/510. Below 1000, 64 of the 167 odd primes are irregular.

**The ceiling in 1900. \[Fact\]** Kummer's extra criteria of 1857 handled 37, 59 and 67 one prime at a time. No uniform argument existed for irregular primes.

**Still open. \[Fact\]** Infinitely many irregular primes exist (Jensen 1915). Nobody has proved that infinitely many regular primes exist.

Sources: [MacTutor](https://mathshistory.st-andrews.ac.uk/HistTopics/Fermat%27s_last_theorem/) for 1844–47; [Conrad](https://kconrad.math.uconn.edu/blurbs/gradnumthy/fltreg.pdf) for class numbers and the first-case argument; [Corry](https://www.tau.ac.il/~corry/publications/articles/pdf/FLT%20-%20SWAC.pdf) for 1857.

## A reconstruction: the best pre-1900 proof, step by step

Assembled into one argument, the classical tools prove the theorem for every exponent divisible by 4 or by a regular prime. For the rest, the argument breaks at two named steps. **\[Reconstruction\]**

| Step | Statement | Tool and date | Status |
| --- | --- | --- | --- |
| 1 | Reduce to n = 4 and odd primes p | Euclid | Proved |
| 2 | Settle n = 4 by descent | Fermat | Proved |
| 3 | Split xᵖ + yᵖ = (x + y)·Φ and bound the common factor | Barlow 1810, Abel 1823 | Proved |
| 4 | Split Φ into the linear factors x + ζᵏy | Gauss 1801, Lamé 1847 | Proved |
| 5 | Coprime factors of a p-th power are p-th powers | Kummer's ideal numbers, 1847 | True for ideal numbers only |
| 6 | A number that is an ideal p-th power is a unit times a p-th power | Class number, 1847 | Needs p ∤ h; false as a rule for 37, 59, 67, … |
| 7 | The leftover unit does no harm | Kummer's lemma on units, 1850 | Needs regularity again |
| 8 | Produce a smaller solution | Fermat's descent | Follows once 5–7 hold |

**What Fermat's own version would look like. \[Reconstruction\]** In 1637, steps 4 to 7 had to be done with ordinary integers and forms. For p = 3 the form is a² + 3b², and the cube section shows the chain closing. For a general p he would have needed this principle:

*If Φ(x, y) is a p-th power and x, y are coprime, then x and y arise by p-fold composition from smaller integers.*

For p = 3 this is Lemma 4. For p = 5 and 7 it took Dirichlet, Legendre and Lamé. In general it is the content of steps 5 to 7.

**Assessment. \[Math\]** The reconstruction is a complete proof for n = 4 and for p = 3, 5, 7, 11, 13, 17, 19, 23, 29, 31 and every other regular prime. An exponent needs only one good factor, so the first exponents left open are 37, 59, 67 and 74.

It cannot be completed for all n. In the 37th cyclotomic integers step 6 is false as a general rule. Ideal classes of order 37 exist there, so some numbers are ideal 37th powers without being a unit times a 37th power.

Whether step 6 fails for the particular numbers x + ζy of a Fermat solution is invisible to this method. That is exactly the gap.

**Could a 19th-century mathematician have gone around it? \[Speculation\]** Kummer, Kronecker, Dedekind and Hilbert all knew the obstacle, and none removed it. The proof of 1995 runs through elliptic curves and modular forms. Their link to Fermat's equation was first noticed in the mid-1980s.

## Can impossibility be proved?

No. There is no rigorous argument that a pre-1900 proof cannot exist, and logic suggests none will be found. What can be proved are limits on each method. **\[Math\]**

**What an impossibility proof would need. \[Math\]** “Pre-1900 mathematics” is not a formal system. The nearest precise stand-in is first-order arithmetic: whole numbers, addition, multiplication and induction. Infinite descent is induction in another dress, and every proof above can be written in that system.

**\[Fact\]** Fermat's Last Theorem is a statement of that arithmetic. McLarty's survey of the logic reports that the 1995 proof probably needs no more than first-order arithmetic in principle. Friedman conjectures that a much weaker system suffices. Neither claim has been written out in full.

**\[Math\]** If the expectation is right, an elementary proof exists in the logical sense, and impossibility is not merely unproved but false. Such a proof could be astronomically long. No known theorem bounds its length from below.

**A precedent. \[Fact\]** The prime number theorem was proved in 1896 with complex analysis. Hardy doubted that an elementary proof could exist. Selberg and Erdős found one in 1948.

**Five limits that are proved. \[Math\]**

| Method | What is proved about its reach | Established by |
| --- | --- | --- |
| Congruences to any modulus | They show that M divides xyz, and nothing more | Jacobi sums and lifting; computed above |
| Germain's plan | Each p has only finitely many auxiliary primes | Libri 1829, Pellet 1887, Dickson 1909 |
| Unique factorization of cyclotomic integers | Fails from p = 23 | Kummer 1844 |
| Kummer's method | Covers regular primes only; infinitely many primes are irregular | Kummer 1850, Jensen 1915 |
| Descent by a fixed formula on the Fermat curve | Impossible for n ≥ 4 | Hurwitz 1891 |

**The last line, explained. \[Math\]** In the sections on 4 and 3, every solution is the image of a smaller one under a fixed polynomial map of degree above 1. Both maps live on curves of genus 1. The curve xⁿ + yⁿ = zⁿ has genus (n − 1)(n − 2)/2, which is at least 3 when n ≥ 4. Hurwitz's formula says that a map of degree d from a curve of genus g to itself satisfies

```latex
2g-2\ \ge\ d\,(2g-2)
```

So d = 1 whenever g ≥ 2. No formula can carry solutions of the Fermat equation to other solutions, apart from its obvious symmetries.

This does not exclude descents that pass through other equations, as Dirichlet's and Kummer's do. It does explain why the proof for 4 works on x⁴ + y⁴ = z², a curve of genus 1, and not on the quartic itself.

**The classical chord method. \[Math\]** Diophantus and Fermat found new rational solutions by substitutions that amount to drawing a line through known ones. On a conic such a line meets the curve in one further point, and on a cubic a line through two known points meets it in exactly one more. On xⁿ + yⁿ = 1 with n ≥ 4 it meets the curve in at least two further points, which need not be rational. The method gives nothing to climb with.

**Where a marvelous proof does exist. \[Math\]** For polynomials in one variable the theorem is attributed to Liouville (1879), and a proof by differentiation takes a few lines. Let x, y, z be coprime polynomials, not all constant, with xⁿ + yⁿ = zⁿ. Differentiate, and eliminate zⁿ:

```latex
x^{n-1}\,(xz'-x'z)=y^{n-1}\,(y'z-yz')
```

Since x and y are coprime, xⁿ⁻¹ divides y′z − yz′, which is not zero. Hence (n − 1)·deg x ≤ deg y + deg z − 1. Adding the three symmetric inequalities gives (n − 3)(deg x + deg y + deg z) ≤ −3, which is impossible for n ≥ 3. ∎

**\[Speculation\]** That proof runs on one tool, the derivative. Integers have no known counterpart to it. A marvelous proof for integers would have to supply one, and nothing in the 17th or 19th century points to such a tool.

Sources: [McLarty](https://www.cs.umd.edu/users/gasarch/BLOGPAPERS/fltlargecard.pdf) on the logic; [Wikipedia, Elementary proof](https://en.wikipedia.org/wiki/Elementary_proof) on the prime number theorem; [Laeng](https://parabola.unsw.edu.au/sites/default/files/2024-03/vol35_no1_1.pdf) on polynomials.

## What Fermat probably had

The most likely story is that Fermat briefly believed his descent for squares and cubes extended to every power, and later saw that it did not. **\[Speculation\]**

**The evidence. \[Fact\]**

- The note was private. He never published it, and he never repeated the general claim in his letters.
- He kept setting n = 3 and n = 4 as separate challenges, and wrote out a proof only for 4. A general proof would have made both redundant.
- His 1659 summary of descent results claims cubes, not all powers.
- The same letter lists the primality of every 2^(2^n) + 1 among the propositions handled by descent. That claim is false. At least once his confidence in descent outran his proofs.

**Three candidate mechanisms. \[Speculation\]**

1. *An over-extended composition law.* He had the formula for Pythagorean triples, and he stated the divisor property of a² + 3b². He may have assumed that a matching law holds for every exponent. That is steps 5 and 6 of the reconstruction: Lamé's error, two centuries early.
2. *A proof for small exponents, stated generally.* A marginal note is not a publication, and “generally” may record a hope.
3. *An argument from the factor relations.* The relations in the section on first reductions look decisive without being so.

**What a correct proof would have required. \[Reconstruction\]** By his documented methods, Fermat would have had to solve in 1637 the problem that stopped Kummer in 1850. No trace of the necessary ideas appears in his letters.

**How historians read it. \[Fact\]** MacTutor's history suggests he may have realised the proof was wrong, since he restated his other theorems as challenges and never this one. The Encyclopedia of Mathematics calls the idea that he had a proof “quite absurd”. Weil's verdict, as usually quoted, is that Fermat briefly deluded himself with an idea that cannot be recovered.

**What he very plausibly did have. \[Speculation\]** A correct descent for cubes, along the lines of the cube section, lies within his stated toolkit.

## Conclusions: the seven requirements answered

A complete pre-1900 proof is not known, cannot be shown impossible, and was realistically out of reach.

1. **No later concepts.** Every proof above uses tools dated before 1900. Results after 1900 appear only as flagged commentary on the methods.
2. **Tools identified.** The toolbox table dates each one, from Euclid to Hurwitz.
3. **Known approaches analyzed.** Descent, congruences and factorization each get a section, and the classical chord method is weighed with the limits. Complete proofs are given for the exponents 4 and 3, for Germain's theorem and for Kummer's first case.
4. **Could a complete proof have existed?** Not realistically. The strongest period method leaves infinitely many prime exponents uncovered, and the people who built it knew why.
5. **Is it impossible?** That cannot be proved, and it is probably false in the logical sense. What is proved are five limits, one per method.
6. **The plausible route.** Descent through cyclotomic factorization is developed step by step. It proves the theorem for exponents divisible by 4 or by a regular prime, not for all n > 2.
7. **Labels.** Fact, Math, Reconstruction and Speculation are marked throughout.

**\[Speculation\]** The best reconstruction of the “marvelous proof” is a correct descent for fourth powers and cubes, wrapped in a generalization that Fermat's tools could not support beyond them.

## Sources

Pages opened and checked for this article on 22 November 2026:

- [MacTutor, “Fermat's last theorem”](https://mathshistory.st-andrews.ac.uk/HistTopics/Fermat%27s_last_theorem/): the record from Fermat to Kummer
- [Laubenbacher and Pengelley, “Voici ce que j'ai trouvé: Sophie Germain's grand plan to prove Fermat's Last Theorem”](https://ar5iv.arxiv.org/html/0801.1809): Germain, Libri, Pellet, Dickson
- [McLarty, “What does it take to prove Fermat's Last Theorem?”, Bulletin of Symbolic Logic 16 (2010)](https://www.cs.umd.edu/users/gasarch/BLOGPAPERS/fltlargecard.pdf): the logic of the 1995 proof
- [Conrad, “Fermat's Last Theorem for regular primes”](https://kconrad.math.uconn.edu/blurbs/gradnumthy/fltreg.pdf): class numbers and Kummer's first case
- [Corry, on Kummer, Vandiver and computation](https://www.tau.ac.il/~corry/publications/articles/pdf/FLT%20-%20SWAC.pdf): the 1857 criteria and their later correction
- [MathPages, “Fermat's Fallibility”](https://mathpages.com/home/kmath195/kmath195.htm): the claim about 2^(2^n) + 1
- [MAA, on the 1659 letter to Carcavi](https://old.maa.org/node/3575258): Fermat's own account of descent
- [Wikipedia, “Proof of Fermat's Last Theorem for specific exponents”](https://en.wikipedia.org/wiki/Proof_of_Fermat%27s_Last_Theorem_for_specific_exponents): who proved which exponent, and when
- [Wikipedia, “Elementary proof”](https://en.wikipedia.org/wiki/Elementary_proof): the prime number theorem and Friedman's conjecture
- [Encyclopedia of Mathematics, “Fermat last theorem”](https://encyclopediaofmath.org/wiki/Fermat_last_theorem): Vandiver, and the 1980s chain to Wiles
- [Laeng, “Fermat's Last Theorem for polynomials”, Parabola 35 (1999)](https://parabola.unsw.edu.au/sites/default/files/2024-03/vol35_no1_1.pdf): the attribution to Liouville
- [St John's College, Cambridge, on the 1670 Diophantus](https://www.joh.cam.ac.uk/node/2312): the lost original

Standard print references, used from memory and not opened here: H. M. Edwards, *Fermat's Last Theorem: A Genetic Introduction* (1977); P. Ribenboim, *13 Lectures on Fermat's Last Theorem* (1979); A. Weil, *Number Theory: An Approach through History* (1984). They stand behind the repair of Euler's lemma, the identity for 7, the Barlow and Abel dates, and Weil's verdict.

All computed statements are reproduced in full in the [Computation log](#computation-log) appendix below.

---

## Computation log

Every statement marked “computed” in the article comes from the checks below. They use exact integer and symbolic arithmetic in Python 3 with SymPy, run on 22 November 2026. The script is available on request.

### Algebraic identities

Each was confirmed by symbolic expansion.

- (u + v)³ + (u − v)³ = 2u(u² + 3v²)
- a = e³ − 9ef² and b = 3e²f − 3f³ give a² + 3b² = (e² + 3f²)³
- (ce − 3df)² + 3(cf + de)² = (c² + 3d²)(e² + 3f²), in both sign conventions
- (ad − bc)(ad + bc) = d²(a² + 3b²) − b²(c² + 3d²)
- The two uses of Euclid's triple formula for the exponent 4, and the map (a, b, c) → (a⁴ − b⁴, 2abc, c⁴ + 4a⁴b⁴)
- The expressions for 4Φ at p = 3, 5, 7 shown in the article
- The seventh-power identity
- Φ(−y, y) = p·yᵖ⁻¹ for p = 3, 5, 7, 11, 13

### Primes with no consecutive p-th power residues

Every prime below the bound (p − 1)²(p − 2)² + 6p − 2 was tested. As a check on the bound, primes up to three times the bound were tested too, and none qualified.

| p | Bound | Count | Complete list |
| --- | --- | --- | --- |
| 3 | 20 | 2 | 7, 13 |
| 5 | 172 | 4 | 11, 41, 71, 101 |
| 7 | 940 | 4 | 29, 71, 113, 491 |
| 11 | 8,164 | 4 | 23, 89, 947, 1409 |
| 13 | 17,500 | 4 | 53, 131, 443, 521 |
| 17 | 57,700 | 5 | 137, 239, 443, 1667, 4013 |
| 19 | 93,748 | 7 | 191, 419, 647, 761, 1217, 1901, 2129 |
| 23 | 213,580 | 12 | 47, 461, 599, 1289, 1427, 1979, 3083, 3221, 3911, 4049, 4877, 6947 |

Only one entry fails Germain's second condition: 443 for p = 13.

### Smallest auxiliary prime meeting both conditions

| p | θ = 2Np + 1 | N |
| --- | --- | --- |
| 3 | 7 | 1 |
| 5 | 11 | 1 |
| 7 | 29 | 2 |
| 11 | 23 | 1 |
| 13 | 53 | 2 |
| 17 | 137 | 4 |
| 19 | 191 | 5 |
| 23 | 47 | 1 |
| 29 | 59 | 1 |
| 31 | 311 | 5 |
| 37 | 149 | 2 |
| 41 | 83 | 1 |
| 43 | 173 | 2 |
| 47 | 659 | 7 |
| 53 | 107 | 1 |
| 59 | 827 | 7 |
| 61 | 977 | 8 |
| 67 | 269 | 2 |
| 71 | 569 | 4 |
| 73 | 293 | 2 |
| 79 | 317 | 2 |
| 83 | 167 | 1 |
| 89 | 179 | 1 |
| 97 | 389 | 2 |

For every prime between 100 and 197, some N ≤ 8 works as well. For p = 197 the only primes 2N·197 + 1 with N < 19 are 3547 and 4729, and both have consecutive residues. N = 19 gives 7487, which meets both conditions.

### First case modulo p²

The congruence xᵖ + yᵖ ≡ zᵖ (mod p²) with p dividing none of x, y, z was searched for every odd prime below 100.

- No solution: p = 3, 5, 11, 17, 23, 29, 41, 47, 53, 71, 89.
- A solution exists: p = 7, 13, 19, 31, 37, 43, 59, 61, 67, 73, 79, 83, 97. Example: 1⁷ + 2⁷ ≡ 3⁷ (mod 49).

### Forced primes and their product M

| p | Forced primes | M |
| --- | --- | --- |
| 3 | 2, 3, 7, 13 | 546 |
| 5 | 2, 5, 11, 41, 71, 101 | 32,341,210 |
| 7 | 2, 29, 71, 113, 491 | 228,478,994 |
| 11 | 2, 11, 23, 89, 947, 1409 | 60,089,901,982 |
| 13 | 2, 53, 131, 443, 521 | 3,204,930,458 |

The local solutions used in the converse were confirmed by brute force for p = 3 and p = 5 at every prime from 2 to 31 that the argument touches.

### Irregular primes

A prime p is irregular when it divides the numerator of some Bernoulli number of even index between 2 and p − 3.

| Irregular prime | Index of the Bernoulli number |
| --- | --- |
| 37 | 32 |
| 59 | 44 |
| 67 | 58 |
| 101 | 68 |
| 103 | 24 |
| 131 | 22 |
| 149 | 130 |
| 157 | 62 and 110 |

Below 1000 there are 167 odd primes, and 64 of them are irregular (38.3%). The numerator of B₃₂ is −7709321041217 = −37 × 208360028141, and its denominator is 510.

### Small facts

- 2³² + 1 = 4294967297 = 641 × 6700417.
- The reduced forms of discriminant −23 are (1, 1, 6), (2, 1, 3) and (2, −1, 3). The discriminants −3, −7, −11, −19 and −43 have one reduced form each.
- x² + xy + 6y² takes the value 6 but never 2 or 3.
- Sanity searches found no solution of x⁴ + y⁴ = z² with 1 ≤ x ≤ y < 400, and none of x³ + y³ = z³ with 1 ≤ x ≤ y < 1500. The proofs do not depend on these searches.
