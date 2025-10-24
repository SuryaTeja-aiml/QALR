# Finding Factors and Trailing Zeroes 
---

Question 1 — How many different factors does 48 have, excluding 1 and 48?  
Options:
- [ ] 9
- [ ] 10
- [x] 8
- [ ] 7

Solution:
- ✅ Given: 48 = 2^4 × 3^1. 🧩  
- 1️⃣ Total factors = (4+1)(1+1) = 5×2 = 10. 🔢  
- 2️⃣ Excluding 1 and 48 → 10 − 2 = 8. ✅

---

Question 2 — Find the number of factors of the expression 2^8 * 3^6 * 5^4 * 10^5  
Options:
- [x] 980
- [ ] 920
- [ ] 770
- [ ] 840

Solution:
- ✅ Expand 10^5 = 2^5 × 5^5. 🔁  
- 1️⃣ Combine exponents: 2^(8+5) × 3^6 × 5^(4+5) = 2^13 × 3^6 × 5^9. 🔧  
- 2️⃣ Number of factors = (13+1)(6+1)(9+1) = 14×7×10 = 980. ✅

---

Question 3 — The number of factors of 3600 is:  
Options:
- [ ] 43
- [ ] 44
- [x] 45
- [ ] 40

Solution:
- ✅ Factorize: 3600 = 2^4 × 3^2 × 5^2. 🧾  
- 1️⃣ Number of factors = (4+1)(2+1)(2+1) = 5×3×3 = 45. ✅

---

Question 4 — How many distinct natural numbers are the divisors of 30^4?  
Options:
- [ ] 124
- [x] 125
- [ ] 122
- [ ] 123

Solution:
- ✅ 30 = 2×3×5 so 30^4 = 2^4 × 3^4 × 5^4. 🧪  
- 1️⃣ Number of divisors = (4+1)(4+1)(4+1) = 5×5×5 = 125. ✅

---

Question 5 — Find the number of odd factors of 70^3  
Options:
- [x] 16
- [ ] 48
- [ ] None
- [ ] 64

Solution:
- ✅ 70^3 = 2^3 × 5^3 × 7^3; odd factors exclude 2. 🔍  
- 1️⃣ Remaining = 5^3 × 7^3 → (3+1)(3+1) = 4×4 = 16 odd factors. ✅

---

Question 6 — Find the number of prime factors of 70^3 (counted with multiplicity)  
Options:
- [ ] 16
- [x] 9
- [ ] 48
- [ ] 64

Solution:
- ✅ 70^3 = 2^3 × 5^3 × 7^3 so total prime factors (sum of exponents) = 3+3+3 = 9. ✅

---

Question 7 — Find the product of the factors of 66  
Options:
- [x] 66^4
- [ ] 235224
- [ ] 182952
- [ ] 66^3

Solution:
- ✅ 66 = 2×3×11 has n = (1+1)(1+1)(1+1) = 8 factors. 🔢  
- 1️⃣ Product of all factors = 66^(n/2) = 66^(8/2) = 66^4. ✅

---

Question 8 — How many different factors does 90 have, excluding 1 or 90?  
Options:
- [ ] 11
- [x] 10
- [ ] 12
- [ ] None

Solution:
- ✅ 90 = 2 × 3^2 × 5 so total factors = (1+1)(2+1)(1+1) = 2×3×2 = 12. 🔢  
- 1️⃣ Excluding 1 and 90 → 12 − 2 = 10. ✅

---

Question 9 — Find the number of prime factors of the expression 66^3 * 30^6 (counted with multiplicity)  
Options:
- [ ] 30
- [x] 27
- [ ] 29
- [ ] 25

Solution:
- ✅ 66^3 = 2^3 × 3^3 × 11^3 and 30^6 = 2^6 × 3^6 × 5^6. 🔁  
- 1️⃣ Combine: 2^(3+6) × 3^(3+6) × 5^6 × 11^3 = 2^9 × 3^9 × 5^6 × 11^3. 🔧  
- 2️⃣ Total prime factors = 9+9+6+3 = 27. ✅

---

Question 10 — How many distinct even divisors of 30^4?  
Options:
- [ ] 120
- [ ] 123
- [ ] 125
- [x] 100

Solution:
- ✅ 30^4 = 2^4 × 3^4 × 5^4 so total divisors = 5×5×5 = 125. 🔢  
- 1️⃣ Odd divisors (exclude 2) = 1×5×5 = 25. ➖  
- 2️⃣ Even divisors = 125 − 25 = 100. ✅

---

Question 11 — Find the number of zeros at the end of 66^3 * 30^6 * 51^6  
Options:
- [ ] 12
- [ ] 9
- [x] 6
- [ ] 8

Solution:
- ✅ Prime factors: 66^3 → 2^3; 30^6 → 2^6×5^6; 51^6 → (no 2 or 5). 🔎  
- 1️⃣ Combined 2-power = 3+6 = 9; 5-power = 6. 🔧  
- 2️⃣ Trailing zeros = min(9,6) = 6. ✅

---

Question 12 — Find the number of zeros at the end of 137!  
Options:
- [ ] 32
- [ ] 35
- [x] 33
- [ ] 30

Solution:
- ✅ Use floor divisions: ⌊137/5⌋ + ⌊137/25⌋ + ⌊137/125⌋ = 27 + 5 + 1 = 33. ✅

---

Question 13 — Find the number of zeros at the end of 389!  
Options:
- [ ] 99
- [ ] 94
- [ ] 91
- [x] 95

Solution:
- ✅ Sum floors: ⌊389/5⌋ + ⌊389/25⌋ + ⌊389/125⌋ = 77 + 15 + 3 = 95. ✅

---

Question 14 — Find the highest power of 7 in 148!  
Options:
- [x] 24
- [ ] 26
- [ ] 23
- [ ] 21

Solution:
- ✅ Sum floors: ⌊148/7⌋ + ⌊148/49⌋ = 21 + 3 = 24. ✅

---

Question 15 — Find the number of zeros at the end of 16^6 * 70^10 * 95^6  
Options:
- [ ] 18
- [x] 16
- [ ] 34
- [ ] 33

Solution:
- ✅ 16^6 = 2^24, 70^10 = 2^10×5^10, 95^6 = 5^6; combine → 2^(24+10)=2^34 and 5^(10+6)=5^16. 🔗  
- 1️⃣ Trailing zeros = min(34,16) = 16. ✅

---

Question 16 — Find the number of zeros at the end of 614!  
Options:
- [x] 150
- [ ] 154
- [ ] 146
- [ ] 151

Solution:
- ✅ Trailing zeros = ⌊614/5⌋ + ⌊614/25⌋ + ⌊614/125⌋ = 122 + 24 + 4 = 150. ✅

---

Question 17 — How many zeros at the end of 400!?  
Options:
- [x] 99
- [ ] 98
- [ ] 101
- [ ] 100

Solution:
- ✅ Trailing zeros = ⌊400/5⌋ + ⌊400/25⌋ + ⌊400/125⌋ = 80 + 16 + 3 = 99. ✅

---

Question 18 — Find the highest power of 11 in 417!  
Options:
- [x] 40
- [ ] 42
- [ ] None
- [ ] 38

Solution:
- ✅ Highest power = ⌊417/11⌋ + ⌊417/121⌋ = 37 + 3 = 40. ✅

---

Question 19 — Find the highest power of 12 in 24!  
Options:
- [ ] 4
- [ ] 8
- [x] 10
- [ ] 2

Solution:
- ✅ 12 = 2^2 × 3, count 2s and 3s in 24!: 2s = 22, 3s = 10. 🔢  
- 1️⃣ Max 12's limited by twos: 22÷2 = 11; by threes: 10÷1 = 10 → min = 10. ✅

---

Question 20 — Find the highest power of 14 in 89!  
Options:
- [ ] 44
- [ ] 12
- [ ] 24
- [x] 13

Solution:
- ✅ 14 = 2×7 so count 2s and 7s in 89!: 2s = 85, 7s = 13 → min(85,13) = 13. ✅

---
