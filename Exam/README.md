## 🔢 **Problem 1: Number of Divisors of 18⁴**

### 📝 Input
- Find divisors of 18⁴ excluding 1 and itself

### 📐 Formula
- Prime factorization: N = p₁^a × p₂^b × p₃^c
- Total divisors = (a+1)(b+1)(c+1)

### 🎯 How To Solve
1. Find prime factorization of 18
2. Raise powers to 4th power
3. Use divisor formula
4. Subtract 2 (for 1 and the number itself)

### ✏️ Steps
- 18 = 2 × 3²
- 18⁴ = 2⁴ × 3⁸
- Total divisors = (4+1)(8+1) = 5 × 9 = 45
- Excluding 1 and itself = 45 - 2 = **43**

### ✅ Output
**43 divisors**

---

## 🔢 **Problem 2: Prime Factors in 104⁵ × 126⁷ × 175²**

### 📝 Input
- Expression: 104⁵ × 126⁷ × 175²

### 📐 Formula
- Prime factorization of each number
- Add exponents of same primes
- Count total prime factors

### 🎯 How To Solve
1. Factorize each number
2. Multiply by respective powers
3. Sum all exponents

### ✏️ Steps
- 104 = 2³ × 13 → 104⁵ = 2¹⁵ × 13⁵
- 126 = 2 × 3² × 7 → 126⁷ = 2⁷ × 3¹⁴ × 7⁷
- 175 = 5² × 7 → 175² = 5⁴ × 7²
- Combined: 2²² × 3¹⁴ × 5⁴ × 7⁹ × 13⁵
- Total = 22 + 14 + 4 + 9 + 5 = **54**

### ✅ Output
**54 prime factors**

---

## 🔢 **Problem 3: Greatest Number (HCF with Remainders)**

### 📝 Input
- Number divides 575 leaving remainder 15
- Number divides 955 leaving remainder 35

### 📐 Formula
- Required number = HCF(N₁ - R₁, N₂ - R₂)

### 🎯 How To Solve
1. Subtract remainders from respective numbers
2. Find HCF of the differences

### ✏️ Steps
- 575 - 15 = 560
- 955 - 35 = 920
- HCF(560, 920) = HCF(560, 360) = HCF(200, 360) = HCF(200, 160) = HCF(40, 160) = **40**

### ✅ Output
**40**

---

## 🔢 **Problem 4: Least Perfect Square Divisible by 12, 20, 30, 50**

### 📝 Input
- Numbers: 12, 20, 30, 50

### 📐 Formula
- Find LCM
- Make all exponents even for perfect square

### 🎯 How To Solve
1. Find LCM of given numbers
2. Adjust prime factors to make even exponents
3. Calculate the result

### ✏️ Steps
- 12 = 2² × 3
- 20 = 2² × 5
- 30 = 2 × 3 × 5
- 50 = 2 × 5²
- LCM = 2² × 3 × 5² = 300
- For perfect square: 2² × 3² × 5² = 4 × 9 × 25 = **900**

### ✅ Output
**900**

---

## 🔢 **Problem 5: LCM and HCF Problem**

### 📝 Input
- LCM = 18 × HCF
- HCF + LCM = 2736
- One number = 576

### 📐 Formula
- Product of numbers = LCM × HCF
- Other number = (LCM × HCF) / First number

### 🎯 How To Solve
1. Find HCF from given conditions
2. Calculate LCM
3. Use product formula to find other number

### ✏️ Steps
- Let HCF = x, then LCM = 18x
- x + 18x = 2736
- 19x = 2736 → x = 144
- HCF = 144, LCM = 2592
- Other number = (144 × 2592) / 576 = **648**

### ✅ Output
**648**

---

## 🔢 **Problem 6: Least Number with Remainder 4**

### 📝 Input
- Divisors: 7, 8, 9, 12
- Remainder: 4 in each case

### 📐 Formula
- Required number = LCM(divisors) + remainder

### 🎯 How To Solve
1. Find LCM of all divisors
2. Add the common remainder

### ✏️ Steps
- LCM(7, 8, 9, 12) = LCM(7, 8, 9, 12) = 504
- Required number = 504 + 4 = **508**

### ✅ Output
**508**

---

## 🔢 **Problem 7: Remainder of 228 × 255 × 278 ÷ 23**

### 📝 Input
- Expression: (228 × 255 × 278) ÷ 23

### 📐 Formula
- (a × b × c) mod n = [(a mod n) × (b mod n) × (c mod n)] mod n

### 🎯 How To Solve
1. Find remainder of each number when divided by 23
2. Multiply remainders
3. Find final remainder

### ✏️ Steps
- 228 = 23 × 9 + 21 → remainder = 21
- 255 = 23 × 11 + 2 → remainder = 2
- 278 = 23 × 12 + 2 → remainder = 2
- (21 × 2 × 2) mod 23 = 84 mod 23 = **15**

### ✅ Output
**Remainder = 15**

---

## 🔢 **Problem 8: (55³ + 56³ + 57³ + 58³) ÷ 228**

### 📝 Input
- N = 55³ + 56³ + 57³ + 58³

### 📐 Formula
- For consecutive numbers: a³ + (a+1)³ + (a+2)³ + (a+3)³
- Use: sum is divisible by sum of numbers

### 🎯 How To Solve
1. Use the property of sum of consecutive cubes
2. Average = (55+58)/2 = 56.5
3. Sum of 4 consecutive cubes formula

### ✏️ Steps
- N = 55³ + 56³ + 57³ + 58³
- N = 166375 + 175616 + 185193 + 195112 = 722296
- 722296 ÷ 228 = 3167 remainder **32**
- Or use: N mod 228 = (55+56+57+58)² mod 228 = 226² mod 228 = **32**

### ✅ Output
**Remainder = 32**

---

## 🔢 **Problem 9: 17¹⁰⁰⁷ ÷ 18**

### 📝 Input
- 17¹⁰⁰⁷ divided by 18

### 📐 Formula
- Fermat's Little Theorem / Pattern recognition
- 17 ≡ -1 (mod 18)

### 🎯 How To Solve
1. Note that 17 = 18 - 1
2. Use binomial theorem concept

### ✏️ Steps
- 17 ≡ -1 (mod 18)
- 17¹⁰⁰⁷ ≡ (-1)¹⁰⁰⁷ (mod 18)
- (-1)¹⁰⁰⁷ = -1 ≡ **17** (mod 18)

### ✅ Output
**Remainder = 17**

---

## 🔢 **Problem 10: 9³³³ ÷ 730**

### 📝 Input
- 9³³³ divided by 730

### 📐 Formula
- Use Chinese Remainder Theorem
- 730 = 2 × 5 × 73

### 🎯 How To Solve
1. Find 9³³³ mod 2, mod 5, mod 73
2. Combine using CRT

### ✏️ Steps
- 9³³³ mod 2 = 1 (odd)
- 9³³³ mod 5 = 4³³³ mod 5 = 4 (since 4⁴ ≡ 1)
- 9³³³ mod 73: 9² = 81 ≡ 8, pattern analysis gives 1
- Combining: remainder = **729**

### ✅ Output
**Remainder = 729**

---

## 🔢 **Problem 11: Trailing Zeros in 825!**

### 📝 Input
- Find trailing zeros in 825!

### 📐 Formula
- Trailing zeros = ⌊n/5⌋ + ⌊n/25⌋ + ⌊n/125⌋ + ⌊n/625⌋ + ...

### 🎯 How To Solve
1. Count factors of 5 in 825!
2. Divide by increasing powers of 5

### ✏️ Steps
- ⌊825/5⌋ = 165
- ⌊825/25⌋ = 33
- ⌊825/125⌋ = 6
- ⌊825/625⌋ = 1
- Total = 165 + 33 + 6 + 1 = **205**

### ✅ Output
**205 trailing zeros**

---

## 🔢 **Problem 12: Trailing Zeros in 30! × 10!**

### 📝 Input
- 30! × 10!

### 📐 Formula
- Count factors of 5 separately and add

### 🎯 How To Solve
1. Find zeros in 30!
2. Find zeros in 10!
3. Add them

### ✏️ Steps
- Zeros in 30! = ⌊30/5⌋ + ⌊30/25⌋ = 6 + 1 = 7
- Zeros in 10! = ⌊10/5⌋ = 2
- Total = 7 + 2 = **9**

### ✅ Output
**9 trailing zeros**

---

## 🔢 **Problem 13: Unit Digit of 13²⁴ × 68⁵⁷ + 1235 + 5678**

### 📝 Input
- Expression: 13²⁴ × 68⁵⁷ + 1235 + 5678

### 📐 Formula
- Find unit digit of each term separately
- Add unit digits

### 🎯 How To Solve
1. Unit digit of 13²⁴: cycle of 3 (3,9,7,1) → 24/4 = 6 rem 0 → 1
2. Unit digit of 68⁵⁷: always 8
3. Add all unit digits

### ✏️ Steps
- 13 has cycle (3,9,7,1), period = 4, 24 mod 4 = 0 → unit digit = 1
- 68⁵⁷: unit digit = 8
- 1 × 8 = 8
- 8 + 5 (from 1235) + 8 (from 5678) = 21
- Unit digit = **1**

### ✅ Output
**Unit digit = 1**

---

## 🔢 **Problem 14: Last Digit of 1653²⁵⁸ + 2497³³⁷**

### 📝 Input
- 1653²⁵⁸ + 2497³³⁷

### 📐 Formula
- Find unit digit pattern for each base

### 🎯 How To Solve
1. Unit digit of 3²⁵⁸
2. Unit digit of 7³³⁷
3. Add them

### ✏️ Steps
- 1653 → unit digit 3: cycle (3,9,7,1), period = 4
- 258 mod 4 = 2 → unit digit = 9
- 2497 → unit digit 7: cycle (7,9,3,1), period = 4
- 337 mod 4 = 1 → unit digit = 7
- 9 + 7 = 16 → unit digit = **6**

### ✅ Output
**Last digit = 6**

---

## 🔢 **Problem 15: Unit Digit of 7¹⁰⁵ × 9¹⁴³**

### 📝 Input
- 7¹⁰⁵ × 9¹⁴³

### 📐 Formula
- Find unit digit of each power
- Multiply unit digits

### 🎯 How To Solve
1. Unit digit pattern of 7
2. Unit digit pattern of 9
3. Multiply results

### ✏️ Steps
- 7 has cycle (7,9,3,1), period = 4
- 105 mod 4 = 1 → unit digit = 7
- 9 has cycle (9,1), period = 2
- 143 mod 2 = 1 → unit digit = 9
- 7 × 9 = 63 → unit digit = **3**

### ✅ Output
**Unit digit = 3**

---

## 🔢 **Problem 16: Last Digit of 7846 × 6189 × 9172 × 4637**

### 📝 Input
- 7846 × 6189 × 9172 × 4637

### 📐 Formula
- Multiply unit digits only

### 🎯 How To Solve
1. Take unit digit of each number
2. Multiply them
3. Find unit digit of result

### ✏️ Steps
- Unit digits: 6 × 9 × 2 × 7
- 6 × 9 = 54 → 4
- 4 × 2 = 8
- 8 × 7 = 56 → **6**

### ✅ Output
**Last digit = 6**

---

## 🔢 **Problem 17: Divisible by Both 7 and 11**

### 📝 Input
- Check: 154, 88, 161, 121

### 📐 Formula
- Divisible by both = divisible by LCM(7,11) = 77

### 🎯 How To Solve
1. Find LCM of 7 and 11 = 77
2. Check each number

### ✏️ Steps
- 154 = 77 × 2 ✅
- 88 = not divisible by 77
- 161 = not divisible by 77
- 121 = not divisible by 77

### ✅ Output
**154 is divisible by both 7 and 11**

---

## 🔢 **Problem 18: Divisibility by 11**

### 📝 Input
- Check: 3178965, 70169803, 61809

### 📐 Formula
- Divisibility by 11: (Sum of odd position digits) - (Sum of even position digits) = 0 or multiple of 11

### 🎯 How To Solve
1. Sum digits at odd positions
2. Sum digits at even positions
3. Find difference

### ✏️ Steps

**3178965:**
- Odd: 5+9+7+3 = 24
- Even: 6+8+1 = 15
- Diff: 24-15 = 9 ❌

**70169803:**
- Odd: 3+8+6+0 = 17
- Even: 0+9+1+7 = 17
- Diff: 0 ✅

**61809:**
- Odd: 9+8+6 = 23
- Even: 0+1 = 1
- Diff: 22 ✅

### ✅ Output
**70169803 and 61809 are divisible by 11**

---

## 🔢 **Problem 19: Divisibility by 2**

### 📝 Input
- a) 102, b) 345, c) 890, d) 177, e) 222

### 📐 Formula
- Divisible by 2: Last digit is even (0,2,4,6,8)

### 🎯 How To Solve
- Check last digit of each number

### ✏️ Steps
- 102: last digit 2 (even) ✅
- 345: last digit 5 (odd) ❌
- 890: last digit 0 (even) ✅
- 177: last digit 7 (odd) ❌
- 222: last digit 2 (even) ✅

### ✅ Output
**102, 890, and 222 are divisible by 2**

---

## 🔢 **Problem 20: Smallest 3-Digit Number Divisible by 7**

### 📝 Input
- Options: 171, 119, 107, 383

### 📐 Formula
- Smallest 3-digit = 100
- Find next multiple of 7

### 🎯 How To Solve
1. Divide 100 by 7
2. Round up and multiply by 7

### ✏️ Steps
- 100 ÷ 7 = 14.28...
- Next multiple: 15 × 7 = **105**
- From options: check each
- 107 ÷ 7 = 15.28... ❌
- But smallest is 105 (not in options)
- From given: **None are smallest, but 119 = 7×17** ✅

### ✅ Output
**Smallest 3-digit divisible by 7 is 105 (or 119 from options)**

---

## 💰 **Problem 21: Compound Interest**

### 📝 Input
- Principal (P) = Rs 10,000
- Rate (R) = 12% p.a.
- Time (T) = 2 years

### 📐 Formula
- Amount = P(1 + R/100)^T

### 🎯 How To Solve
1. Apply compound interest formula
2. Calculate final amount

### ✏️ Steps
- A = 10000(1 + 12/100)²
- A = 10000(1.12)²
- A = 10000 × 1.2544
- A = **Rs 12,544**

### ✅ Output
**Amount = Rs 12,544**

---

## 💰 **Problem 22: CI vs SI Ratio**

### 📝 Input
- CI for 3 years : SI for 1 year = 3.64 : 1

### 📐 Formula
- CI₃ = P[(1+R/100)³ - 1]
- SI₁ = P × R/100

### 🎯 How To Solve
1. Set up ratio equation
2. Solve for R

### ✏️ Steps
- CI₃/SI₁ = 3.64
- [(1+R/100)³ - 1] / (R/100) = 3.64
- Let R/100 = x
- [(1+x)³ - 1]/x = 3.64
- (1 + 3x + 3x² + x³ - 1)/x = 3.64
- 3 + 3x + x² = 3.64
- 3x + x² = 0.64
- Solving: x = 0.20 → **R = 20%**

### ✅ Output
**Rate = 20% p.a.**

---

## 💰 **Problem 23: Compound Interest on Rs 30,000**

### 📝 Input
- P = Rs 30,000
- T = 3 years
- R = 10% p.a.

### 📐 Formula
- CI = P[(1 + R/100)^T - 1]

### 🎯 How To Solve
1. Calculate final amount
2. Subtract principal

### ✏️ Steps
- A = 30000(1.10)³
- A = 30000 × 1.331
- A = 39,930
- CI = 39,930 - 30,000 = **Rs 9,930**

### ✅ Output
**CI = Rs 9,930**

---

## 💰 **Problem 24: Difference Between CI and SI**

### 📝 Input
- P = Rs 3,000
- R = 10% p.a.
- T = 2 years

### 📐 Formula
- Difference = P(R/100)² for 2 years

### 🎯 How To Solve
1. Calculate SI = PTR/100
2. Calculate CI = P[(1+R/100)^T - 1]
3. Find difference

### ✏️ Steps
- SI = 3000 × 10 × 2 / 100 = Rs 600
- CI = 3000[(1.10)² - 1] = 3000[1.21 - 1] = Rs 630
- Difference = 630 - 600 = **Rs 30**

### ✅ Output
**Difference = Rs 30**

---

## 💰 **Problem 25: Dividing Rs 12,000 for Equal SI**

### 📝 Input
- Total = Rs 12,000
- Part 1: 3 years at 12% p.a.
- Part 2: 4.5 years at 16% p.a.
- SI on both parts equal

### 📐 Formula
- SI = PTR/100
- SI₁ = SI₂

### 🎯 How To Solve
1. Let first part = x, second = 12000-x
2. Set SI equal and solve

### ✏️ Steps
- x × 12 × 3 / 100 = (12000-x) × 16 × 4.5 / 100
- 36x = 72(12000-x)
- 36x = 864000 - 72x
- 108x = 864000
- x = 8000
- Ratio = 8000 : 4000 = **2:1**

### ✅ Output
**Ratio = 2:1**

---

## 💰 **Problem 26: Rate of Interest**

### 📝 Input
- A lent Rs 5,000 to B for 2 years
- A lent Rs 3,000 to C for 4 years
- Total interest = Rs 2,200

### 📐 Formula
- SI = PTR/100
- Total SI = SI₁ + SI₂

### 🎯 How To Solve
1. Set up equation with rate R
2. Solve for R

### ✏️ Steps
- SI₁ = 5000 × 2 × R / 100 = 100R
- SI₂ = 3000 × 4 × R / 100 = 120R
- 100R + 120R = 2200
- 220R = 2200
- R = **10%**

### ✅ Output
**Rate = 10% p.a.**

---

## 💰 **Problem 27: Difference in Interest Rates**

### 📝 Input
- Principal = Rs 1,500
- Time = 3 years
- Difference in SI = Rs 13.50

### 📐 Formula
- Difference = P × T × (R₁ - R₂) / 100

### 🎯 How To Solve
1. Use difference formula
2. Solve for rate difference

### ✏️ Steps
- 13.50 = 1500 × 3 × (R₁ - R₂) / 100
- 13.50 = 45(R₁ - R₂)
- R₁ - R₂ = 13.50 / 45
- R₁ - R₂ = **0.3% or 3/10%**

### ✅ Output
**Difference in rates = 0.3%**

---

## 💰 **Problem 28: Time to Double at 5% SI**

### 📝 Input
- Rate = 5% p.a.
- Amount = 2 × Principal

### 📐 Formula
- A = P(1 + RT/100)
- For SI: 2P = P + PTR/100

### 🎯 How To Solve
1. Set up equation for doubling
2. Solve for time

### ✏️ Steps
- 2P = P + P × 5 × T / 100
- P = P × 5T / 100
- 100 = 5T
- T = **20 years**

### ✅ Output
**Time = 20 years**

---

## 📊 **Problem 29: Average After Mark Change**

### 📝 Input
- 6 subjects, average = 80
- One subject: 70 → 90

### 📐 Formula
- New average = (Old total - Old mark + New mark) / n

### 🎯 How To Solve
1. Find original total
2. Adjust for changed mark
3. Calculate new average

### ✏️ Steps
- Original total = 80 × 6 = 480
- New total = 480 - 70 + 90 = 500
- New average = 500 / 6 = **83.33**

### ✅ Output
**New average = 83.33**

---

## 📊 **Problem 30: Average After Revaluation**

### 📝 Input
- 6 subjects, average = 75
- One subject: 50 → 80

### 📐 Formula
- New average = Old average + (Change / n)

### 🎯 How To Solve
1. Find total marks change
2. Distribute change over all subjects

### ✏️ Steps
- Original total = 75 × 6 = 450
- New total = 450 - 50 + 80 = 480
- New average = 480 / 6 = **80**

### ✅ Output
**New average = 80**

---

## 📊 **Problem 31: Average Petrol Consumption**

### 📝 Input
- First 7 months: 110 litres average
- Next 5 months: 86 litres average

### 📐 Formula
- Overall average = Total consumption / Total months

### 🎯 How To Solve
1. Calculate total for each period
2. Divide by total months

### ✏️ Steps
- Total for 7 months = 110 × 7 = 770
- Total for 5 months = 86 × 5 = 430
- Total consumption = 770 + 430 = 1200
- Average = 1200 / 12 = **100 litres**

### ✅ Output
**Average = 100 litres/month**

---

## 📊 **Problem 32: Finding Sixth Result**

### 📝 Input
- 11 results, average = 50
- First 6 results average = 49
- Last 6 results average = 52

### 📐 Formula
- 6th result counted twice
- Total = First 6 + Last 6 - 6th result

### 🎯 How To Solve
1. Calculate all totals
2. Find common element

### ✏️ Steps
- Total of 11 = 50 × 11 = 550
- Total of first 6 = 49 × 6 = 294
- Total of last 6 = 52 × 6 = 312
- 6th result = 294 + 312 - 550 = **56**

### ✅ Output
**6th result = 56**

---

## 💵 **Problem 33: Mixture Profit/Loss**

### 📝 Input
- 36 kg at Rs 45/kg
- 24 kg at Rs 60/kg
- Selling price = Rs 52/kg

### 📐 Formula
- Profit/Loss % = [(SP - CP) / CP] × 100

### 🎯 How To Solve
1. Find total cost
2. Find total selling price
3. Calculate profit/loss %

### ✏️ Steps
- Total CP = (36 × 45) + (24 × 60) = 1620 + 1440 = Rs 3060
- Total quantity = 60 kg
- Total SP = 60 × 52 = Rs 3120
- Profit = 3120 - 3060 = Rs 60
- Profit % = (60/3060) × 100 = **1.96%**

### ✅ Output
**Profit = 1.96% (approx 2%)**

---

## 💵 **Problem 34: 30% Gain and 30% Loss**

### 📝 Input
- Two phones at Rs 15,000 each
- Phone 1: 30% gain
- Phone 2: 30% loss

### 📐 Formula
- Loss % = (gain% × loss%)² / 100 when equal CP

### 🎯 How To Solve
1. Calculate SP of each phone
2. Find total profit/loss

### ✏️ Steps
- Phone 1 SP = 15000 × 1.30 = Rs 19,500
- Phone 2 SP = 15000 × 0.70 = Rs 10,500
- Total CP = Rs 30,000
- Total SP = Rs 30,000
- Net result = **No profit, No loss**
- Actually: Loss = (30²/100) = 9% on second phone dominates

### ✅ Output
**Net loss = Rs 0 (or 9% loss on investment)**

---

## 💵 **Problem 35: 40% Gain and 10% Loss**

### 📝 Input
- Two phones at Rs 12,000 each
- Phone 1: 40% gain
- Phone 2: 10% loss

### 📐 Formula
- Overall % = (Total SP - Total CP) / Total CP × 100

### 🎯 How To Solve
1. Calculate each SP
2. Find overall profit/loss

### ✏️ Steps
- Phone 1 SP = 12000 × 1.40 = Rs 16,800
- Phone 2 SP = 12000 × 0.90 = Rs 10,800
- Total CP = Rs 24,000
- Total SP = Rs 27,600
- Profit = Rs 3,600
- Profit % = (3600/24000) × 100 = **15%**

### ✅ Output
**Profit = 15%**

---

## 💵 **Problem 36: Water Mixed in Milk**

### 📝 Input
- Sells at cost price but adds water
- Gains 20%

### 📐 Formula
- If gain is x%, water = x/(100+x) of mixture

### 🎯 How To Solve
1. For 20% gain with water
2. Calculate water ratio

### ✏️ Steps
- Let milk cost = Rs 100/liter
- Sells at Rs 100/liter but gains 20%
- Actual cost should be Rs 100/1.2 = Rs 83.33
- So in 1 liter mixture: milk worth Rs 83.33
- Water = 20/120 = 1/6 liter
- **Or: 200 ml water in every 1000 ml mixture**

### ✅ Output
**200 ml water per 1000 ml (or 1/6 liter)**

---

## 📐 **Problem 37: Cube Volume Increase**

### 📝 Input
- Each side increased by 10%

### 📐 Formula
- New volume = (1.1a)³ = 1.331a³

### 🎯 How To Solve
1. If side = a, volume = a³
2. New side = 1.1a
3. New volume = (1.1)³ × a³

### ✏️ Steps
- Original volume = a³
- New volume = (1.1a)³ = 1.331a³
- Increase = 0.331a³
- Increase % = **33.1%**

### ✅ Output
**Volume increases by 33.1%**

---

## 🔢 **Problem 38: Finding Larger Number**

### 📝 Input
- Difference = 20% of larger
- Smaller number = 20

### 📐 Formula
- Larger - Smaller = 20% of Larger
- L - 20 = 0.2L

### 🎯 How To Solve
1. Set up equation
2. Solve for larger number

### ✏️ Steps
- L - 20 = 0.2L
- L - 0.2L = 20
- 0.8L = 20
- L = 20/0.8 = **25**

### ✅ Output
**Larger number = 25**

---

## 🔢 **Problem 39: If 50% of P = 25% of Q**

### 📝 Input
- 50% of P = 25% of Q
- P = x% of Q

### 📐 Formula
- 0.5P = 0.25Q
- P = ?% of Q

### 🎯 How To Solve
1. Set up equation
2. Express P in terms of Q

### ✏️ Steps
- 0.5P = 0.25Q
- P = 0.25Q/0.5
- P = 0.5Q
- P = **50% of Q**
- Therefore x = **50**

### ✅ Output
**x = 50**

---

## 📈 **Problem 40: Population Growth**

### 📝 Input
- Present population = 50,000
- Growth rate = 4% p.a.
- Time = 2 years

### 📐 Formula
- Future population = P(1 + R/100)^T

### 🎯 How To Solve
1. Apply compound growth formula
2. Calculate for 2 years

### ✏️ Steps
- Population after 2 years = 50000(1.04)²
- = 50000 × 1.0816
- = **54,080**

### ✅ Output
**Population after 2 years = 54,080**

---


*Happy Problem Solving! 🎓*
