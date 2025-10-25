## **CATEGORY 1: COUNTING FACTORS & DIVISORS**

### What Are Factors?
Factors (or divisors) are numbers that divide evenly into another number with no remainder.
- Example: Factors of 12 are 1, 2, 3, 4, 6, 12

### Step-by-Step Process

**Step 1: Prime Factorize the Number**
- Break the number down to its smallest prime building blocks
- Example: 48 = 2 × 2 × 2 × 2 × 3 = 2⁴ × 3¹

**Step 2: Write in Exponent Form**
- Group the same primes together
- Write as: p₁^e₁ × p₂^e₂ × p₃^e₃...
- Example: 48 = 2⁴ × 3¹

**Step 3: Add 1 to Each Exponent**
- Take each exponent and add 1
- Example: (4+1) and (1+1) = 5 and 2

**Step 4: Multiply All Results**
- Multiply all the (exponent+1) values
- Example: 5 × 2 = 10 total factors

**So 48 has 10 factors: 1, 2, 3, 4, 6, 8, 12, 16, 24, 48**

### The Core Formula
$$\text{Number of Factors} = (e_1 + 1) × (e_2 + 1) × (e_3 + 1) × ...$$

---

### Special Case 1: Excluding 1 and the Number Itself

If the question asks "how many factors excluding 1 and the number?"

**Step 1:** Calculate total factors using the formula above
**Step 2:** Subtract 2 (remove 1 and the number itself)

Example:
- 48 has 10 factors total
- Excluding 1 and 48 → 10 - 2 = **8 factors**

---

### Special Case 2: Counting Only ODD Factors

Odd factors don't contain any factor of 2.

**Step 1:** Prime factorize the number
**Step 2:** Remove ALL factors of 2 completely
**Step 3:** Apply the factor formula to what remains

Example:
- 70³ = (2 × 5 × 7)³ = 2³ × 5³ × 7³
- Remove all 2s → 5³ × 7³
- Count factors: (3+1) × (3+1) = 4 × 4 = **16 odd factors**

---

### Special Case 3: Counting Only EVEN Factors

Even factors must contain at least one factor of 2.

**Step 1:** Calculate total factors (all factors)
**Step 2:** Calculate odd factors (no 2s at all)
**Step 3:** Subtract odd from total → Even factors

Example:
- 30⁴ = 2⁴ × 3⁴ × 5⁴
- Total factors: (4+1) × (4+1) × (4+1) = 5 × 5 × 5 = 125
- Odd factors (no 2s): 1 × (4+1) × (4+1) = 1 × 5 × 5 = 25
- Even factors: 125 - 25 = **100**

---

### Special Case 4: Product of All Factors

When you multiply all factors of a number together, there's a shortcut.

**Step 1:** Find the total number of factors (call it n)
**Step 2:** Use formula: Product = (original number)^(n/2)

Example:
- 66 = 2 × 3 × 11 (exponents: 1, 1, 1)
- Total factors = (1+1) × (1+1) × (1+1) = 2 × 2 × 2 = 8
- Product of all factors = 66^(8/2) = 66⁴

---

### Special Case 5: Prime Factors WITH Multiplicity

When counting "how many prime factors?" where we count repeats:

**Step 1:** Prime factorize completely
**Step 2:** Just add up ALL the exponents

Example:
- 70³ = 2³ × 5³ × 7³
- Add exponents: 3 + 3 + 3 = **9 prime factors**
- This means if you multiplied: 2 × 2 × 2 × 5 × 5 × 5 × 7 × 7 × 7 = 9 primes total

---

## **CATEGORY 2: TRAILING ZEROES IN PRODUCTS**

### What Are Trailing Zeroes?
Trailing zeroes are the zeros at the END of a number.
- Example: 1200 has 2 trailing zeroes

### Why Do We Get Trailing Zeroes?
- Trailing zeroes come from factors of 10
- 10 = 2 × 5
- So we need pairs of 2s and 5s

### Step-by-Step Process

**Step 1: Prime Factorize EACH Number**
- Break down every base number into primes
- Remember: 10 = 2 × 5, 100 = 2² × 5², etc.

Example: 16⁶ × 70¹⁰ × 95⁶
- 16⁶ = (2⁴)⁶ = 2²⁴
- 70¹⁰ = (2 × 5 × 7)¹⁰ = 2¹⁰ × 5¹⁰ × 7¹⁰
- 95⁶ = (5 × 19)⁶ = 5⁶ × 19⁶

**Step 2: Combine All 2s**
- Add up all exponents of 2
- Example: 2²⁴ × 2¹⁰ = 2³⁴

**Step 3: Combine All 5s**
- Add up all exponents of 5
- Example: 5¹⁰ × 5⁶ = 5¹⁶

**Step 4: Take the MINIMUM**
- You need pairs of (2 × 5) for each trailing zero
- The smaller number limits how many pairs you can make
- Example: min(34, 16) = 16

**So there are 16 trailing zeroes**

### Key Insight
There are always more factors of 2 than 5 in any product, so we usually count the 5s instead.

---

## **CATEGORY 3: TRAILING ZEROES IN FACTORIALS**

### What is a Factorial?
- n! = n × (n-1) × (n-2) × ... × 2 × 1
- Example: 5! = 5 × 4 × 3 × 2 × 1 = 120

### Why Is This Different?
In factorials, we're multiplying many numbers, so factors of 5 get "hidden" in different places.

### Step-by-Step Process

**Step 1: Divide by 5**
- Count how many multiples of 5 are in the factorial
- Use: ⌊n ÷ 5⌋ (floor division = round down)

**Step 2: Divide by 25 (which is 5²)**
- Count how many multiples of 25 exist
- These contribute an EXTRA factor of 5
- Use: ⌊n ÷ 25⌋

**Step 3: Divide by 125 (which is 5³)**
- Count how many multiples of 125 exist
- These contribute another EXTRA factor of 5
- Use: ⌊n ÷ 125⌋

**Step 4: Continue with 625, 3125, etc.**
- Keep going until your answer is 0
- Then stop

**Step 5: Add All Results**
- Sum up all the quotients from Steps 1-4

### Example: 400!

- ⌊400 ÷ 5⌋ = 80
- ⌊400 ÷ 25⌋ = 16
- ⌊400 ÷ 125⌋ = 3
- ⌊400 ÷ 625⌋ = 0 (stop here)

**Total = 80 + 16 + 3 = 99 trailing zeroes**

### Why Does This Work?
- Multiples of 5 contribute one factor of 5
- Multiples of 25 contribute a second factor of 5
- Multiples of 125 contribute a third factor of 5
- By adding these separately, we count each factor of 5

---

## **CATEGORY 4: HIGHEST POWER OF A PRIME IN FACTORIAL**

### What Does This Mean?
"Find the highest power of 7 that divides 100!" means:
- What's the largest k such that 7^k divides 100!?

### Step-by-Step Process

**Step 1: Divide by the Prime**
- Count multiples of the prime in the factorial
- Use: ⌊n ÷ p⌋

**Step 2: Divide by Prime Squared**
- Count multiples of p² (bonus factor)
- Use: ⌊n ÷ p²⌋

**Step 3: Divide by Prime Cubed**
- Count multiples of p³ (another bonus)
- Use: ⌊n ÷ p³⌋

**Step 4: Continue Until You Get 0**
- Keep going with p⁴, p⁵, etc.
- Stop when the result is 0

**Step 5: Add All Results**
- Sum up all quotients

### Example: Highest power of 7 in 148!

- ⌊148 ÷ 7⌋ = 21
- ⌊148 ÷ 49⌋ = 3
- ⌊148 ÷ 343⌋ = 0 (stop)

**Answer: 21 + 3 = 24 (so 7²⁴ divides 148!)**

### Why This Works
- 148! includes 21 multiples of 7
- Among these, 3 are also multiples of 49 (contributing an extra 7)
- Total: 21 + 3 = 24 factors of 7

---

## **CATEGORY 5: HIGHEST POWER OF COMPOSITE NUMBER IN FACTORIAL**

### What Is a Composite Number?
A composite number is made of multiple primes multiplied together.
- Example: 12 = 2² × 3, or 14 = 2 × 7, or 30 = 2 × 3 × 5

### Step-by-Step Process

**Step 1: Break the Composite into Prime Factors**
- Write it in exponent form
- Example: 12 = 2² × 3¹

**Step 2: Find Highest Power of Each Prime in n!**
- For each prime factor, use the factorial formula from Category 4
- Example for 24!:
  - Highest power of 2: ⌊24/2⌋ + ⌊24/4⌋ + ⌊24/8⌋ + ⌊24/16⌋ = 12 + 6 + 3 + 1 = 22
  - Highest power of 3: ⌊24/3⌋ + ⌊24/9⌋ = 8 + 2 = 10

**Step 3: Divide by the Exponent Needed in the Composite**
- For 12 = 2² × 3¹:
  - From the 22 twos: 22 ÷ 2 = 11 (can make 11 copies of 2²)
  - From the 10 threes: 10 ÷ 1 = 10 (can make 10 copies of 3¹)

**Step 4: Take the MINIMUM**
- The limiting factor determines the answer
- min(11, 10) = 10

**Answer: Highest power of 12 in 24! is 12¹⁰**

### Key Insight
Whichever prime factor "runs out first" limits how many copies of the composite number you can make.

---

## **MASTER SUMMARY TABLE**

| What You Need | Steps | Formula |
|---------------|-------|---------|
| **Count all factors** | Prime factorize → Add 1 to each exponent → Multiply | (e₁+1) × (e₂+1) × ... |
| **Exclude 1 and number** | Count all factors → Subtract 2 | Total - 2 |
| **Odd factors only** | Remove all 2s → Count remaining factors | (e₂+1) × (e₃+1) × ... |
| **Even factors only** | Count all → Count odd → Subtract | Total - Odd |
| **Product of all factors** | Count factors (n) → Raise number to power (n/2) | number^(n/2) |
| **Prime factors w/ multiplicity** | Prime factorize → Add all exponents | e₁ + e₂ + e₃ + ... |
| **Trailing zeroes (product)** | Count 2s → Count 5s → Take minimum | min(count of 2s, count of 5s) |
| **Trailing zeroes (factorial)** | Sum ⌊n/5⌋ + ⌊n/25⌋ + ⌊n/125⌋ + ... | Σ⌊n/5^k⌋ until 0 |
| **Prime power in factorial** | Sum ⌊n/p⌋ + ⌊n/p²⌋ + ⌊n/p³⌋ + ... | Σ⌊n/p^k⌋ until 0 |
| **Composite in factorial** | Find each prime power → Divide by exponent → Min | min(power₁/exp₁, power₂/exp₂) |

---

## **QUICK DECISION TREE**

**Is it asking about a specific number?**
- YES → Use Category 1 (Factors & Divisors)

**Is it asking about trailing zeroes?**
- With a product (like 16⁶ × 70¹⁰)? → Use Category 2
- With a factorial (like 100! or 148!)? → Use Category 3

**Is it asking about highest power?**
- Of a prime (like 7)? → Use Category 4
- Of a composite (like 12 or 14)? → Use Category 5
