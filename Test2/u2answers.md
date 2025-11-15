## Problem 1: Odd Factors of 1800

**Input**
* Find the number of odd factors of 1800

**📐 Formula**
* Prime factorization: N = p₁^a × p₂^b × p₃^c
* Total divisors = (a+1)(b+1)(c+1)
* For odd factors: exclude all powers of 2

**🎯 How To Solve**
1. Find prime factorization of 1800
2. Remove the power of 2
3. Use divisor formula on remaining odd primes

**✏️ Steps**
* 1800 = 2³ × 3² × 5²
* For odd factors, ignore 2³
* Odd part = 3² × 5²
* Number of odd factors = (2+1)(2+1) = 3 × 3 = 9

**✅ Output**
9 odd factors **(D)**

---

## Problem 2: Even Factors of 3600

**Input**
* Find the number of even factors of 3600

**📐 Formula**
* Even factors = Total factors - Odd factors
* OR: At least one factor of 2 must be present

**🎯 How To Solve**
1. Find prime factorization
2. Calculate total factors
3. Calculate odd factors
4. Subtract to get even factors

**✏️ Steps**
* 3600 = 2⁴ × 3² × 5²
* Total factors = (4+1)(2+1)(2+1) = 5 × 3 × 3 = 45
* Odd factors (no 2's) = (2+1)(2+1) = 3 × 3 = 9
* Even factors = 45 - 9 = 36

**✅ Output**
36 even factors **(C)**

---

## Problem 3: HCF and LCM

**Input**
* HCF = 12, LCM = 420
* One number is between 70 and 90
* Find that number

**📐 Formula**
* Product of two numbers = HCF × LCM
* Number₁ × Number₂ = 12 × 420 = 5040

**🎯 How To Solve**
1. Both numbers must be multiples of HCF (12)
2. Use the product formula
3. Check which number falls in the given range

**✏️ Steps**
* Number₁ × Number₂ = 5040
* Multiples of 12 between 70-90: 72, 84
* If Number₁ = 84, then Number₂ = 5040/84 = 60
* Check: HCF(84, 60) = 12 ✓, LCM(84, 60) = 420 ✓

**✅ Output**
84 **(C)**

---

## Problem 4: Greatest Divisor with Remainders

**Input**
* A number divides 1020 leaving remainder 4
* Same number divides 1487 leaving remainder 7
* Find the greatest such number

**📐 Formula**
* The number divides (1020-4) and (1487-7) completely
* Answer = HCF(1016, 1480)

**🎯 How To Solve**
1. Subtract remainders from given numbers
2. Find HCF of the results

**✏️ Steps**
* 1020 - 4 = 1016
* 1487 - 7 = 1480
* HCF(1016, 1480) = HCF(1016, 464) = HCF(88, 464) = 8

**✅ Output**
8 **(B)**

---

## Problem 5: HCF of Three Numbers

**Input**
* Find HCF of 72, 108, and 180

**📐 Formula**
* HCF(a, b, c) = HCF(HCF(a, b), c)
* Or use prime factorization method

**🎯 How To Solve**
1. Find prime factorization of each number
2. Take minimum power of each common prime

**✏️ Steps**
* 72 = 2³ × 3²
* 108 = 2² × 3³
* 180 = 2² × 3² × 5
* Common primes: 2 and 3
* HCF = 2² × 3² = 4 × 9 = 36

**✅ Output**
36 **(C)**

---

## Problem 6: Least Perfect Square

**Input**
* Find least perfect square divisible by 8, 18, 24, and 36

**📐 Formula**
* First find LCM of all numbers
* Make each prime's power even for perfect square

**🎯 How To Solve**
1. Find LCM of the numbers
2. Check if LCM is a perfect square
3. If not, multiply by necessary factors

**✏️ Steps**
* 8 = 2³, 18 = 2 × 3², 24 = 2³ × 3, 36 = 2² × 3²
* LCM = 2³ × 3² = 72
* For perfect square, all powers must be even
* 72 = 2³ × 3² (power of 2 is odd)
* Multiply by 2: 72 × 2 = 144 = 2⁴ × 3²

**✅ Output**
144 **(A)**

---

## Problem 7: Remainder of Power

**Input**
* Find remainder when 2³³³ is divided by 9

**📐 Formula**
* Use pattern of remainders
* 2ⁿ mod 9 has a cycle

**🎯 How To Solve**
1. Find the pattern of 2ⁿ mod 9
2. Use the cycle to find 2³³³ mod 9

**✏️ Steps**
* 2¹ mod 9 = 2
* 2² mod 9 = 4
* 2³ mod 9 = 8
* 2⁴ mod 9 = 16 mod 9 = 7
* 2⁵ mod 9 = 32 mod 9 = 5
* 2⁶ mod 9 = 64 mod 9 = 1
* Pattern repeats every 6 powers
* 333 = 6 × 55 + 3
* 2³³³ mod 9 = 2³ mod 9 = 8

**✅ Output**
8 **(C)**

---

## Problem 8: Remainder of Large Power

**Input**
* Find remainder when 19¹⁰⁰⁷ is divided by 18

**📐 Formula**
* 19 ≡ 1 (mod 18)
* Therefore 19ⁿ ≡ 1ⁿ (mod 18)

**🎯 How To Solve**
1. Simplify 19 modulo 18
2. Apply power property

**✏️ Steps**
* 19 = 18 + 1
* 19 ≡ 1 (mod 18)
* 19¹⁰⁰⁷ ≡ 1¹⁰⁰⁷ ≡ 1 (mod 18)

**✅ Output**
1 **(C)**

---

## Problem 9: Sum of Powers Remainder

**Input**
* Find remainder when 11⁹³ + 12⁹³ + ... + 69⁹³ is divided by 80

**📐 Formula**
* Use symmetry: (a)⁹³ + (80-a)⁹³ mod 80
* For odd powers: aⁿ + (m-a)ⁿ ≡ 0 (mod m) when n is odd

**🎯 How To Solve**
1. Pair terms symmetrically around 40
2. Use the property that pairs sum to 0 mod 80

**✏️ Steps**
* Sum = 11⁹³ + 12⁹³ + ... + 69⁹³
* Pair: (11⁹³ + 69⁹³), (12⁹³ + 68⁹³), ... (39⁹³ + 41⁹³), 40⁹³
* For odd power: a⁹³ + (80-a)⁹³ ≡ 0 (mod 80)
* Only 40⁹³ remains
* 40⁹³ mod 80 = (40)⁹³ mod 80 = 0 (since 40 × 2 = 80)

**✅ Output**
0 **(C)**

---

## Problem 10: Power Modulo Prime

**Input**
* Find remainder when 25¹⁰⁰⁰ is divided by 13

**📐 Formula**
* Fermat's Little Theorem: If p is prime, aᵖ⁻¹ ≡ 1 (mod p)
* Here: 25¹² ≡ 1 (mod 13)

**🎯 How To Solve**
1. Simplify base: 25 ≡ 12 ≡ -1 (mod 13)
2. Apply power

**✏️ Steps**
* 25 = 13 × 1 + 12
* 25 ≡ 12 ≡ -1 (mod 13)
* 25¹⁰⁰⁰ ≡ (-1)¹⁰⁰⁰ ≡ 1 (mod 13)

**✅ Output**
1 **(D)**

---

## Problem 11: Trailing Zeros

**Input**
* Find trailing zeros in (5³ × 2²)!

**📐 Formula**
* Trailing zeros = min(count of 2's, count of 5's) in n!
* Count of 5's in n! = ⌊n/5⌋ + ⌊n/25⌋ + ⌊n/125⌋ + ...

```
Why count 5's?
Trailing zeros come from 10's = 2 × 5
In n!, there are always more 2's than 5's
So we count 5's only
```

**🎯 How To Solve**
1. Calculate (5³ × 2²) = 125 × 4 = 500
2. Find 500!
3. Count factors of 5 in 500!

**✏️ Steps**
* n = 500
* ⌊500/5⌋ = 100
* ⌊500/25⌋ = 20
* ⌊500/125⌋ = 4
* ⌊500/625⌋ = 0
* Total = 100 + 20 + 4 = 124

**✅ Output**
124 trailing zeros **(B)**

---

## Problem 12: Highest Power Divisor

**Input**
* Highest power of 20 dividing 200 × 800 × 1600

**📐 Formula**
* 20 = 2² × 5
* Count min(powers of 2²/powers of 5) in the product

**🎯 How To Solve**
1. Factorize each number
2. Count total powers of 2 and 5
3. Find how many times 20 divides

**✏️ Steps**
* 200 = 2³ × 5²
* 800 = 2⁵ × 5²
* 1600 = 2⁶ × 5²
* Product = 2¹⁴ × 5⁶
* 20ⁿ = (2² × 5)ⁿ = 2²ⁿ × 5ⁿ
* For powers of 2: 2n ≤ 14, so n ≤ 7
* For powers of 5: n ≤ 6
* Minimum: n = 6

**✅ Output**
6 **(A)**

---

## Problem 13: Last Digit of Product

**Input**
* Find last digit of 515³⁶⁰ × 833¹⁷² × 836⁹⁹⁹ × 99⁴⁴⁴

**📐 Formula**
* Last digit = unit digit of product
* Only consider unit digits of each term

**🎯 How To Solve**
1. Find unit digit of each term
2. Multiply unit digits

**✏️ Steps**
* 515³⁶⁰: unit digit of 5^any power = 5
* 833¹⁷²: unit digit of 3¹⁷² (pattern: 3,9,7,1) = 3⁴ pattern, 172/4 = 43, so 3⁴ = 1
* 836⁹⁹⁹: unit digit of 6^any power = 6
* 99⁴⁴⁴: unit digit of 9⁴⁴⁴ (pattern: 9,1) = 9² = 1, 444/2 = 222, so 1
* Product = 5 × 1 × 6 × 1 = 30, unit digit = 0

**✅ Output**
0 **(C)**

---

## Problem 14: Unit Digit of Expression

**Input**
* Find unit digit of 46³⁵ + 19⁷⁸ - 28³⁵

**📐 Formula**
* Find unit digit of each term separately
* Then add/subtract

```
Unit digit patterns:
6^n always ends in 6
9^even ends in 1, 9^odd ends in 9
8: cycle of 8,4,2,6
```

**🎯 How To Solve**
1. Find unit digit of each power
2. Add and subtract

**✏️ Steps**
* 46³⁵: unit digit of 6^any = 6
* 19⁷⁸: unit digit of 9⁷⁸ (even power) = 1
* 28³⁵: unit digit of 8³⁵ (cycle: 8,4,2,6), 35 mod 4 = 3, so 2
* Expression = 6 + 1 - 2 = 5

**✅ Output**
5 **(B)**

---

## Problem 15: Unit Digit of Expression

**Input**
* Find unit digit of 4⁶⁵ × 5⁶⁹ × 9⁷¹

**📐 Formula**
* When multiplying by 5 and even number, result ends in 0

**🎯 How To Solve**
1. Find unit digit of each term
2. Multiply

**✏️ Steps**
* 4⁶⁵: cycle (4,6), 65 is odd, so 4
* 5⁶⁹: always 5
* 9⁷¹: cycle (9,1), 71 is odd, so 9
* Product = 4 × 5 × 9 = 180, unit digit = 0

**✅ Output**
0 **(A)**

---

## Problem 16: Unit Digit of Product

**Input**
* Find unit digit of 784 × 618 × 917 × 463

**📐 Formula**
* Multiply unit digits only

**🎯 How To Solve**
1. Take unit digit of each number
2. Multiply

**✏️ Steps**
* Unit digits: 4, 8, 7, 3
* Product = 4 × 8 × 7 × 3 = 672
* Unit digit = 2

**✅ Output**
2 **(A)**

---

## Problem 17: Divisibility by 10

**Input**
* Which number is NOT divisible by 10?

**📐 Formula**
* A number is divisible by 10 if it ends in 0

**🎯 How To Solve**
1. Check last digit of each option

**✏️ Steps**
* (A) 2015 - ends in 5 ✗
* (B) 4170 - ends in 0 ✓
* (C) 3000 - ends in 0 ✓
* (D) 8990 - ends in 0 ✓

**✅ Output**
2015 **(A)**

---

## Problem 18: Divisibility Check

**Input**
* 1170 is NOT divisible by which number?

**📐 Formula**
* Divisibility by 2: last digit even
* Divisibility by 3: sum of digits divisible by 3
* Divisibility by 5: last digit 0 or 5
* Divisibility by 8: last 3 digits divisible by 8

**🎯 How To Solve**
1. Apply divisibility rules

**✏️ Steps**
* By 2: 1170 ends in 0 (even) ✓
* By 3: 1+1+7+0 = 9, divisible by 3 ✓
* By 5: ends in 0 ✓
* By 8: 170 ÷ 8 = 21.25 ✗

**✅ Output**
8 **(D)**

---

## Problem 19: Divisibility by 5

**Input**
* A number ends in 7. What to add to make it divisible by 5?

**📐 Formula**
* Number divisible by 5 ends in 0 or 5

**🎯 How To Solve**
1. Ending is 7, need 0 or 5
2. 7 + 3 = 10 (ends in 0)

**✏️ Steps**
* Current: ...7
* Need: ...0 or ...5
* 7 + 3 = 10 (ends in 0) ✓

**✅ Output**
3 **(C)**

---

## Problem 20: Divisibility by 11

**Input**
* Which number is NOT divisible by 11?

**📐 Formula**
* Divisibility by 11: (sum of odd position digits) - (sum of even position digits) is 0 or multiple of 11

```
Example: 7162
Odd positions: 7 + 6 = 13
Even positions: 1 + 2 = 3
Difference: 13 - 3 = 10 (not divisible by 11)
```

**🎯 How To Solve**
1. Apply alternating sum rule for each option

**✏️ Steps**
* (A) 7162: (7+6)-(1+2) = 13-3 = 10 ✗
* (B) 4543: (4+4)-(5+3) = 8-8 = 0 ✓
* (C) 3311: (3+1)-(3+1) = 4-4 = 0 ✓
* (D) 2189: (2+8)-(1+9) = 10-10 = 0 ✓

**✅ Output**
7,162 **(A)**

---

## Problem 21: Compound Interest

**Input**
* Principal = Rs. 10,000
* Time = 2 years
* Rate = 4% per annum (yearly compounding)

**📐 Formula**
* Compound Interest = P(1 + r/100)ⁿ - P
* OR CI = P[(1 + r/100)ⁿ - 1]

**🎯 How To Solve**
1. Apply compound interest formula
2. Subtract principal

**✏️ Steps**
* A = 10000(1 + 4/100)²
* A = 10000(1.04)²
* A = 10000 × 1.0816 = 10816
* CI = 10816 - 10000 = 816

**✅ Output**
Rs. 816 **(D)**

---

## Problem 22: Simple vs Compound Interest

**Input**
* Difference between SI and CI for 2 years at 5% = Rs. 63
* Find the principal

**📐 Formula**
* Difference for 2 years = P(r/100)²
* Where r is rate and P is principal

```
Why this formula?
CI for 2 years = P[(1+r)² - 1]
SI for 2 years = P × 2r
Difference = Pr² (this comes from expansion)
```

**🎯 How To Solve**
1. Use difference formula
2. Solve for P

**✏️ Steps**
* P(r/100)² = 63
* P(5/100)² = 63
* P(0.05)² = 63
* P × 0.0025 = 63
* P = 63/0.0025 = 25,200

**✅ Output**
Rs. 25,200 **(B)**

---

## Problem 23: Time Period for Compound Interest

**Input**
* Principal = Rs. 8000
* Compound Interest = Rs. 2648
* Rate = 20% per annum, compounded semi-annually

**📐 Formula**
* A = P(1 + r/200)²ⁿ (for semi-annual)
* Where n is number of years

**🎯 How To Solve**
1. Amount = 8000 + 2648 = 10648
2. Use semi-annual compounding formula
3. Solve for n

**✏️ Steps**
* A = 10648, P = 8000
* 10648 = 8000(1 + 20/200)²ⁿ
* 10648/8000 = (1.1)²ⁿ
* 1.331 = (1.1)²ⁿ
* (1.1)³ = (1.1)²ⁿ
* 2n = 3, n = 1.5 years = 18 months

**✅ Output**
18 months **(D)**

---

## Problem 24: Compound vs Simple Interest

**Input**
* CI for 3 years at 16⅔% = Rs. 12,700
* Find SI for same sum, rate, and period

**📐 Formula**
* For 3 years at r%: CI = P[(1+r)³-1], SI = P×3r
* Rate = 16⅔% = 50/3% = 1/6

**🎯 How To Solve**
1. Find P using CI formula
2. Calculate SI using P

**✏️ Steps**
* r = 16⅔% = 1/6
* CI = P[(7/6)³ - 1] = P[343/216 - 1] = P(127/216)
* 12700 = P(127/216)
* P = 12700 × 216/127 = 21600
* SI = 21600 × 1/6 × 3 = 10800

**✅ Output**
Rs. 10,800 **(D)**

---

## Problem 25: Time Comparison

**Input**
* Rs. 8000 at 3% produces same interest as Rs. 6000 at 4% for 5 years
* Find time for Rs. 8000

**📐 Formula**
* Simple Interest = P × R × T / 100
* Set both interests equal

**🎯 How To Solve**
1. Calculate SI for Rs. 6000
2. Set equal to SI for Rs. 8000
3. Solve for time

**✏️ Steps**
* SI₁ = 6000 × 4 × 5 / 100 = 1200
* SI₂ = 8000 × 3 × T / 100
* 1200 = 240T
* T = 5 years

**✅ Output**
5 years **(C)**

---

## Problem 26: Interest Rate Calculation

**Input**
* Initially: P : A = 4 : 5
* After 3 more years: P : A = 5 : 7
* Find rate of interest

**📐 Formula**
* A = P + SI = P + PRT/100 = P(1 + RT/100)

**🎯 How To Solve**
1. Set up equations from both ratios
2. Find initial time
3. Calculate rate

**✏️ Steps**
* Let P = 4x, then A₁ = 5x, so SI₁ = x
* x = 4x × R × T / 100, so RT = 25
* After 3 years: A₂ = 7x/5 × 4x = 28x/5, SI₂ = 28x/5 - 4x = 8x/5
* 8x/5 = 4x × R × (T+3) / 100
* 40 = R(T+3)
* RT = 25, so 25 + 3R = 40
* 3R = 15, R = 5%

**✅ Output**
5% **(C)**

---

## Problem 27: Doubling Time

**Input**
* Sum doubles in 7 years at SI
* When will it become 4 times?

**📐 Formula**
* If sum doubles in T years, SI = P
* Rate = 100/T %

**🎯 How To Solve**
1. If doubles in 7 years, rate = 100/7%
2. For 4 times, SI = 3P
3. Calculate time

**✏️ Steps**
* Doubles in 7 years: P = P × R × 7 / 100
* R = 100/7%
* For 4 times: 3P = P × (100/7) × T / 100
* 3 = T/7
* T = 21 years

**✅ Output**
21 years **(D)**

---

## Problem 28: Multiple Growth Time

**Input**
* Sum becomes 5 times in 15 years at SI
* When will it become 12 times?

**📐 Formula**
* If sum becomes n times in T years: SI = (n-1)P
* Rate = (n-1) × 100 / T %

**🎯 How To Solve**
1. Find rate from first condition
2. Use rate to find time for 12 times

**✏️ Steps**
* 5 times in 15 years: 4P = P × R × 15 / 100
* R = 400/15 = 80/3%
* For 12 times: 11P = P × (80/3) × T / 100
* 11 = 80T/300
* T = 3300/80 = 41.25 years = 41 years 3 months

**✅ Output**
41 years 3 months **(C)**

---

## Problem 29: Average Earning

**Input**
* First 4 days average = Rs. 18
* Last 4 days average = Rs. 22
* 4th day earning = Rs. 20
* Find weekly average

**📐 Formula**
* Total = Sum of all earnings
* Average = Total / 7

**🎯 How To Solve**
1. Calculate total for first 4 days
2. Calculate total for last 4 days
3. Subtract double-counted 4th day
4. Find average

**✏️ Steps**
* First 4 days total = 18 × 4 = 72
* Last 4 days total = 22 × 4 = 88
* Sum = 72 + 88 - 20 = 140 (subtracting 4th day counted twice)
* Average = 140/7 = 20

**✅ Output**
Rs. 20 **(D)**

---

## Problem 30: Average Salary with Manager

**Input**
* 20 workers, average = Rs. 1900
* With manager, average = Rs. 2000
* Find manager's annual salary

**📐 Formula**
* New average = (Old total + Manager salary) / (n+1)

**🎯 How To Solve**
1. Calculate total salary of 20 workers
2. Calculate total with manager
3. Find manager's monthly then annual salary

**✏️ Steps**
* Total of 20 workers = 20 × 1900 = 38,000
* Total of 21 people = 21 × 2000 = 42,000
* Manager's monthly = 42,000 - 38,000 = 4,000
* Manager's annual = 4,000 × 12 = 48,000

**✅ Output**
None of these **(D)** [Answer should be Rs. 48,000]

---

## Problem 31: Average Age Problem

**Input**
* 90 students, total age = 2700 years
* 50 students average = 30 years
* 30 students average = 28 years
* Find average of remaining students

**📐 Formula**
* Remaining = Total - Group1 - Group2
* Average = Sum / Count

**🎯 How To Solve**
1. Calculate total age of known groups
2. Subtract from total
3. Divide by remaining students

**✏️ Steps**
* Total age = 2700
* 50 students total = 50 × 30 = 1500
* 30 students total = 30 × 28 = 840
* Remaining students = 90 - 50 - 30 = 10
* Remaining age = 2700 - 1500 - 840 = 360
* Average = 360/10 = 36

**✅ Output**
36 **(D)**

---

## Problem 32: Consecutive Integers

**Input**
* Average of 5 consecutive integers = 18
* Find 2B + 4D - 75, where B is 2nd and D is 4th

**📐 Formula**
* For consecutive integers with average n: middle number = n
* Numbers: (n-2), (n-1), n, (n+1), (n+2)

**🎯 How To Solve**
1. Find middle number from average
2. List all 5 numbers
3. Calculate expression

**✏️ Steps**
* Average = 18, so middle (3rd) number = 18
* Numbers: 16, 17, 18, 19, 20
* B (2nd) = 17, D (4th) = 19
* 2B + 4D - 75 = 2(17) + 4(19) - 75 = 34 + 76 - 75 = 35

**✅ Output**
35 **(A)**

---

## Problem 33: Profit and Loss

**Input**
* 20% loss on selling
* Selling Rs. 240 more gives 10% profit
* Find SP at 25% profit

**📐 Formula**
* SP at loss = CP × (100-loss%)/100
* SP at profit = CP × (100+profit%)/100
* Difference = 30% of CP

**🎯 How To Solve**
1. Use difference to find CP
2. Calculate SP at 25% profit

**✏️ Steps**
* Let CP = x
* SP at 20% loss = 0.8x
* SP at 10% profit = 1.1x
* Difference: 1.1x - 0.8x = 240
* 0.3x = 240
* x = 800
* SP at 25% profit = 800 × 1.25 = 1000

**✅ Output**
Rs. 1000 **(D)**

---

## Problem 34: Mixture Problem

**Input**
* 50 kg tea at Rs. 80/kg
* 30 kg tea at Rs. 100/kg
* Sells mixture at Rs. 90/kg

**📐 Formula**
* Total CP = Sum of individual costs
* Total SP = Quantity × Selling price
* Profit% = (SP - CP)/CP × 100

**🎯 How To Solve**
1. Calculate total cost price
2. Calculate total selling price
3. Find profit/loss percentage

**✏️ Steps**
* Total CP = 50(80) + 30(100) = 4000 + 3000 = 7000
* Total quantity = 80 kg
* Total SP = 80 × 90 = 7200
* Profit = 7200 - 7000 = 200
* Profit% = 200/7000 × 100 = 2.857% ≈ 2.86%

**✅ Output**
2.86% **(B)**

---

## Problem 35: Cost Price Calculation

**Input**
* Selling Rs. 750 more changes -5% loss to +15% profit
* Find cost price

**📐 Formula**
* Difference between two SPs = 20% of CP
* (15% - (-5%)) = 20% of CP = Rs. 750

**🎯 How To Solve**
1. Find what percentage difference Rs. 750 represents
2. Calculate CP

**✏️ Steps**
* SP₁ at 5% loss = 0.95 × CP
* SP₂ at 15% profit = 1.15 × CP
* Difference = 1.15CP - 0.95CP = 0.20CP
* 0.20CP = 750
* CP = 750/0.20 = 3750

**✅ Output**
Rs. 3750 **(A)**

---

## Problem 36: Mixture Profit/Loss

**Input**
* 36 kg pulses at Rs. 45/kg
* 24 kg pulses at Rs. 60/kg
* Sells at Rs. 52/kg

**📐 Formula**
* Total CP = Sum of costs
* Total SP = Total quantity × SP per kg
* Gain% = (SP - CP)/CP × 100

**🎯 How To Solve**
1. Calculate total cost
2. Calculate total selling price
3. Find percentage

**✏️ Steps**
* Total CP = 36(45) + 24(60) = 1620 + 1440 = 3060
* Total quantity = 60 kg
* Total SP = 60 × 52 = 3120
* Gain = 3120 - 3060 = 60
* Gain% = 60/3060 × 100 = 1.96%

**✅ Output**
1.96% **(A)**

---

## Problem 37: Salary Comparison

**Input**
* 2007 salary = Rs. 8,80,000
* This is 10% more than 2006 salary
* Find 2006 salary

**📐 Formula**
* 2007 salary = 2006 salary × 1.10
* 2006 salary = 2007 salary / 1.10

**🎯 How To Solve**
1. Set up equation
2. Divide by 1.10

**✏️ Steps**
* Let 2006 salary = x
* x × 1.10 = 8,80,000
* x = 8,80,000 / 1.10
* x = 8,00,000

**✅ Output**
Rs. 8,00,000 **(D)**

---

## Problem 38: Percentage Relationship

**Input**
* 15% of (A + B) = 25% of (A - B)
* Find what % of B is A

**📐 Formula**
* Set up equation and solve for A in terms of B

**🎯 How To Solve**
1. Write the equation
2. Expand and simplify
3. Express A as percentage of B

**✏️ Steps**
* 0.15(A + B) = 0.25(A - B)
* 0.15A + 0.15B = 0.25A - 0.25B
* 0.15B + 0.25B = 0.25A - 0.15A
* 0.40B = 0.10A
* A = 4B
* A = 400% of B

**✅ Output**
400% **(C)**

---

## Problem 39: Election Problem

**Input**
* 10% didn't vote
* 60 voted blank
* Winner got 47% of total voters
* Winner got 308 more votes than rival
* Find total voters

**📐 Formula**
* Valid votes = Total - Non-voters - Blank votes
* Winner + Loser = Valid votes
* Winner - Loser = 308

**🎯 How To Solve**
1. Let total voters = x
2. Set up equations for winner and loser
3. Solve for x

**✏️ Steps**
* Total voters = x
* Non-voters = 0.10x
* Blank = 60
* Valid votes = 0.90x - 60
* Winner = 0.47x
* Loser = 0.90x - 60 - 0.47x = 0.43x - 60
* Winner - Loser = 308
* 0.47x - (0.43x - 60) = 308
* 0.04x + 60 = 308
* 0.04x = 248
* x = 6200

**✅ Output**
6200 **(A)**

---

## Problem 40: Percentage Equation

**Input**
* 50% of P = 25% of Q
* Find x where P = x% of Q

**📐 Formula**
* Convert to equation and solve

**🎯 How To Solve**
1. Write equation
2. Express P in terms of Q
3. Find percentage

**✏️ Steps**
* 0.50P = 0.25Q
* P = 0.25Q / 0.50
* P = 0.50Q
* P = 50% of Q
* x = 50

**✅ Output**
50 **(C)**
