# Finding Factors and Trailing Zeroes
---

Question 1 — How many different factors does 48 have, excluding 1 and 48?  
Context/Rule: To get total factors, prime-factorize then use (e1+1)(e2+1)... and subtract 2 to exclude 1 and the number. 🧮  
Options:
- [ ] 9
- [ ] 10
- [x] 8
- [ ] 7

Steps:
- ✅ Step 1: Prime factorize 48 → 48 = 2^4 × 3^1. 🔍  
- ✅ Step 2: Total factors = (4+1) × (1+1) = 5 × 2 = 10. ✖️  
- ✅ Step 3: Excluding 1 and 48 → 10 − 2 = 8. ✅

Answer: 8

---

Question 2 — Find the number of factors of  expression 2^8 × 3^6 × 5^4 × 10^5  
Context/Rule: Expand composite powers (10^5 = 2^5×5^5), combine like bases, then use (ei+1) product. 🔗  
Options:
- [x] 980
- [ ] 920
- [ ] 770
- [ ] 840

Steps:
- ✅ Step 1: Expand 10^5 → 10^5 = 2^5 × 5^5. 🔁  
- ✅ Step 2: Combine exponents → 2^(8+5) × 3^6 × 5^(4+5) = 2^13 × 3^6 × 5^9. ➕  
- ✅ Step 3: Number of factors = (13+1)(6+1)(9+1) = 14×7×10 = 980. ✅

Answer: 980

---

Question 3 — The number of factors of 3600 is:  
Context/Rule: Factorize 3600, then apply factor-count formula (ei+1) product. 🧾  
Options:
- [ ] 43
- [ ] 44
- [x] 45
- [ ] 40

Steps:
- ✅ Step 1: Factorize: 3600 = 36×100 = (6^2)(10^2) = 2^4 × 3^2 × 5^2. 🔎  
- ✅ Step 2: Number of factors = (4+1)(2+1)(2+1) = 5×3×3 = 45. ✅

Answer: 45

---

Question 4 — How many distinct natural numbers are the divisors of 30^4?  
Context/Rule: 30 = 2×3×5, so 30^4 = 2^4×3^4×5^4; count divisors via (ei+1) product. 📐  
Options:
- [ ] 124
- [x] 125
- [ ] 122
- [ ] 123

Steps:
- ✅ Step 1: Express 30^4 = 2^4 × 3^4 × 5^4. 🔧  
- ✅ Step 2: Number of divisors = (4+1)(4+1)(4+1) = 5×5×5 = 125. ✅

Answer: 125

---

Question 5 — Find the number of odd factors of 70^3.  
Context/Rule: Odd factors exclude factor 2, so remove the 2-power and count factors of the remaining prime-power product. ♀️🔢  
Options:
- [x] 16
- [ ] 48
- [ ] None
- [ ] 64

Steps:
- ✅ Step 1: Factorize 70^3 → 70 = 2 × 5 × 7 → 70^3 = 2^3 × 5^3 × 7^3. 🔍  
- ✅ Step 2: Remove 2-power to get odd part 5^3 × 7^3. ➖  
- ✅ Step 3: Count odd factors = (3+1)(3+1) = 4×4 = 16. ✅

Answer: 16

---

Question 6 — Find the number of prime factors of 70^3 (counted with multiplicity).  
Context/Rule: For prime factors counted with multiplicity, sum the exponents in prime factorization. ➕  
Options:
- [ ] 16
- [x] 9
- [ ] 48
- [ ] 64

Steps:
- ✅ Step 1: 70^3 = 2^3 × 5^3 × 7^3. 🔎  
- ✅ Step 2: Total prime factors (with multiplicity) = 3 + 3 + 3 = 9. ✅

Answer: 9

---

Question 7 — Find the product of the factors of 66.  
Context/Rule: If a number has n divisors, the product of all divisors = number^(n/2). ⚖️  
Options:
- [x] 66^4
- [ ] 235224
- [ ] 182952
- [ ] 66^3

Steps:
- ✅ Step 1: Prime factorize 66 = 2 × 3 × 11 → exponents 1,1,1. 🔍  
- ✅ Step 2: Number of factors n = (1+1)(1+1)(1+1) = 2×2×2 = 8. 🔢  
- ✅ Step 3: Product of all factors = 66^(n/2) = 66^(8/2) = 66^4. ✅

Answer: 66^4

---

Question 8 — How many different factors does 90 have, excluding 1 or 90?  
Context/Rule: Factorize 90 and use (ei+1) product, then subtract 2 to exclude 1 and the number. 🧾  
Options:
- [ ] 11
- [x] 10
- [ ] 12
- [ ] None

Steps:
- ✅ Step 1: Prime factorize 90 = 2 × 3^2 × 5. 🔎  
- ✅ Step 2: Total factors = (1+1)(2+1)(1+1) = 2×3×2 = 12. 🔢  
- ✅ Step 3: Excluding 1 and 90 → 12 − 2 = 10. ✅

Answer: 10

---

Question 9 — Find the number of prime factors of 66^3 × 30^6 (counted with multiplicity).  
Context/Rule: Prime-factorize each base, add exponents for like primes, then sum exponents for total multiplicity. ➕  
Options:
- [ ] 30
- [x] 27
- [ ] 29
- [ ] 25

Steps:
- ✅ Step 1: 66^3 = 2^3 × 3^3 × 11^3 and 30^6 = 2^6 × 3^6 × 5^6. 🔁  
- ✅ Step 2: Combine = 2^(3+6) × 3^(3+6) × 5^6 × 11^3 = 2^9 × 3^9 × 5^6 × 11^3. 🔧  
- ✅ Step 3: Total prime factors = 9 + 9 + 6 + 3 = 27. ✅

Answer: 27

---

Question 10 — How many distinct even divisors of 30^4?  
Context/Rule: Even divisors must include at least one factor 2; subtract odd divisors (no 2) from total divisors. ⚖️  
Options:
- [ ] 120
- [ ] 123
- [ ] 125
- [x] 100

Steps:
- ✅ Step 1: 30^4 = 2^4 × 3^4 × 5^4 → total divisors = (4+1)^3 = 125. 🔢  
- ✅ Step 2: Odd divisors (no 2) = 1 × (4+1) × (4+1) = 25. ➖  
- ✅ Step 3: Even divisors = 125 − 25 = 100. ✅

Answer: 100

---

Question 11 — Find the number of zeros at the end of 66^3 × 30^6 × 51^6.  
Context/Rule: Trailing zeros come from pairs of (2×5); count total 2s and 5s and take the minimum. 🔢  
Options:
- [ ] 12
- [ ] 9
- [x] 6
- [ ] 8

Steps:
- ✅ Step 1: 66^3 contributes 2^3; 30^6 contributes 2^6×5^6; 51^6 has no 2 or 5. 🔎  
- ✅ Step 2: Total 2-exponent = 3 + 6 = 9, total 5-exponent = 6. ➕  
- ✅ Step 3: Trailing zeros = min(9,6) = 6. ✅

Answer: 6

---

Question 12 — Find the number of zeros at the end of 137!.  
Context/Rule: For n!, trailing zeros = sum_{k≥1} floor(n/5^k), i.e., count factors of 5 (multiplicity). 🧮  
Options:
- [ ] 32
- [ ] 35
- [x] 33
- [ ] 30

Steps:
- ✅ Step 1: Compute floors: ⌊137/5⌋ = 27. 🔢  
- ✅ Step 2: ⌊137/25⌋ = 5. 🔢  
- ✅ Step 3: ⌊137/125⌋ = 1; next term ⌊137/625⌋ = 0 → stop. 🔚  
- ✅ Step 4: Sum = 27 + 5 + 1 = 33 zeros. ✅

Answer: 33

---

Question 13 — Find the number of zeros at the end of 389!.  
Context/Rule: Use floor divisions by powers of 5: floor(n/5) + floor(n/25) + floor(n/125) + ... until zero. 🧾  
Options:
- [ ] 99
- [ ] 94
- [ ] 91
- [x] 95

Steps:
- ✅ Step 1: ⌊389/5⌋ = 77. 🔢  
- ✅ Step 2: ⌊389/25⌋ = 15. 🔢  
- ✅ Step 3: ⌊389/125⌋ = 3; ⌊389/625⌋ = 0 → stop. 🔚  
- ✅ Step 4: Sum = 77 + 15 + 3 = 95 zeros. ✅

Answer: 95

---

Question 14 — Find the highest power of 7 in 148!.  
Context/Rule: Highest power of prime p in n! is sum of floor(n/p^k) for k≥1 until zero. 🧠  
Options:
- [x] 24
- [ ] 26
- [ ] 23
- [ ] 21

Steps:
- ✅ Step 1: ⌊148/7⌋ = 21. 🔢  
- ✅ Step 2: ⌊148/49⌋ = 3. 🔢  
- ✅ Step 3: ⌊148/343⌋ = 0 → stop; sum = 21 + 3 = 24. ✅

Answer: 24

---

Question 15 — Find the number of zeros at the end of 16^6 × 70^10 × 95^6.  
Context/Rule: Convert each base to prime powers, sum exponents of 2 and 5, trailing zeros = min(exponent2, exponent5). 🔎  
Options:
- [ ] 18
- [x] 16
- [ ] 34
- [ ] 33

Steps:
- ✅ Step 1: 16^6 = (2^4)^6 = 2^24. 🔁  
- ✅ Step 2: 70^10 = (2×5×7)^10 = 2^10 × 5^10 × 7^10. 🔧  
- ✅ Step 3: 95^6 = (5×19)^6 = 5^6 × 19^6. 🔎  
- ✅ Step 4: Combined 2-exponent = 24+10 = 34; combined 5-exponent = 10+6 = 16. ➕  
- ✅ Step 5: Trailing zeros = min(34,16) = 16. ✅

Answer: 16

---

Question 16 — Find the number of zeros at the end of 614!.  
Context/Rule: Use floor division by powers of 5: sum ⌊614/5^k⌋ until zero. 🧮  
Options:
- [x] 150
- [ ] 154
- [ ] 146
- [ ] 151

Steps:
- ✅ Step 1: ⌊614/5⌋ = 122. 🔢  
- ✅ Step 2: ⌊614/25⌋ = 24. 🔢  
- ✅ Step 3: ⌊614/125⌋ = 4; ⌊614/625⌋ = 0 → stop. 🔚  
- ✅ Step 4: Sum = 122 + 24 + 4 = 150 zeros. ✅

Answer: 150

---

Question 17 — How many zeros at the end of 400!?  
Context/Rule: Trailing zeros = ⌊400/5⌋ + ⌊400/25⌋ + ⌊400/125⌋ + ... until zero. 🧾  
Options:
- [x] 99
- [ ] 98
- [ ] 101
- [ ] 100

Steps:
- ✅ Step 1: ⌊400/5⌋ = 80. 🔢  
- ✅ Step 2: ⌊400/25⌋ = 16. 🔢  
- ✅ Step 3: ⌊400/125⌋ = 3; ⌊400/625⌋ = 0 → stop. 🔚  
- ✅ Step 4: Sum = 80 + 16 + 3 = 99 zeros. ✅

Answer: 99

---

Question 18 — Find the highest power of 11 in 417!.  
Context/Rule: For prime p=11, sum ⌊417/11^k⌋ until zero to get exponent of 11 in 417!. 🔍  
Options:
- [x] 40
- [ ] 42
- [ ] None
- [ ] 38

Steps:
- ✅ Step 1: ⌊417/11⌋ = 37. 🔢  
- ✅ Step 2: ⌊417/121⌋ = 3. 🔢  
- ✅ Step 3: ⌊417/1331⌋ = 0 → stop; sum = 37 + 3 = 40. ✅

Answer: 40

---

Question 19 — Find the highest power of 12 in 24!.  
Context/Rule: 12 = 2^2 × 3; count total 2s and 3s in 24!, divide 2s by 2, divide 3s by 1, take the smaller quotient. ⚖️  
Options:
- [ ] 4
- [ ] 8
- [x] 10
- [ ] 2

Steps:
- ✅ Step 1: Count 2s in 24!: ⌊24/2⌋+⌊24/4⌋+⌊24/8⌋+⌊24/16⌋ = 12+6+3+1 = 22. 🔢  
- ✅ Step 2: Count 3s in 24!: ⌊24/3⌋+⌊24/9⌋ = 8+2 = 10. 🔢  
- ✅ Step 3: 12 uses 2 twos and 1 three → max by 2s = ⌊22/2⌋ = 11, by 3s = ⌊10/1⌋ = 10 → min = 10. ✅

Answer: 10

---

Question 20 — Find the highest power of 14 in 89!.  
Context/Rule: 14 = 2 × 7; count total 2s and 7s in 89!, then highest power of 14 = min(count2, count7). 🔎  
Options:
- [ ] 44
- [ ] 12
- [ ] 24
- [x] 13

Steps:
- ✅ Step 1: Count 2s in 89!: ⌊89/2⌋+⌊89/4⌋+⌊89/8⌋+⌊89/16⌋+⌊89/32⌋+⌊89/64⌋ = 44+22+11+5+2+1 = 85. 🔢  
- ✅ Step 2: Count 7s in 89!: ⌊89/7⌋+⌊89/49⌋ = 12 + 1 = 13. 🔢  
- ✅ Step 3: Highest power of 14 = min(85,13) = 13. ✅

Answer: 13

---
