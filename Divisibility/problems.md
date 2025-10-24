# Division Rule and Divisibility Rules

## **Question 1: Difference Between Squares**

The square of the sum of two given natural numbers is 784, while the product of the two given numbers is 192. Find the positive difference between the squares of these two numbers.

**Options:**
- [ ] 112
- [ ] 122
- [ ] 400
- [ ] 512

### Solution:

**Given:**
- $(a + b)^2 = 784$
- $ab = 192$

**Step 1:** Find $(a + b)$
$$a + b = \sqrt{784} = 28$$

**Step 2:** Find $(a - b)$ using the identity
$$(a - b)^2 = (a + b)^2 - 4ab = 784 - 4(192) = 784 - 768 = 16$$
$$a - b = 4$$

**Step 3:** Find $a^2 - b^2$
$$a^2 - b^2 = (a + b)(a - b) = 28 \times 4 = \boxed{112}$$

**Correct Answer: 112**

---

## **Question 2: Divisibility of Sum of Powers**

$6^{25} + 6^{26} + 6^{27} + 6^{28}$ is divisible by:

**Options:**
- [ ] 259
- [ ] 254
- [ ] 255
- [ ] 256

### Solution:

**Step 1:** Factor out the common term
$$6^{25}(1 + 6 + 6^2 + 6^3)$$

**Step 2:** Simplify the bracket
$$1 + 6 + 36 + 216 = 259$$

**Step 3:** Final expression
$$6^{25} \times 259$$

The expression is divisible by $\boxed{259}$

**Correct Answer: 259**

---

## **Question 3: Largest 5-Digit Number Divisible by 88**

The largest five digit number exactly divisible by 88 is:

**Options:**
- [ ] 99984
- [ ] 99990
- [ ] 99968
- [ ] 99978

### Solution:

**Step 1:** Check divisibility by 8 (last 3 digits)
- 99984 → 984 ÷ 8 = 123 ✓
- 99990 → 990 ÷ 8 = 123.75 ✗
- 99968 → 968 ÷ 8 = 121 ✓
- 99978 → 978 ÷ 8 = 122.25 ✗

**Step 2:** Check divisibility by 11 (alternating digit sum)
- 99984 → (9+9+4) - (9+8) = 22 - 17 = 5 ✗
- 99968 → (9+9+8) - (9+6) = 26 - 15 = 11 ✓

**Answer:** $\boxed{99968}$

**Correct Answer: 99968**

---

## **Question 4: Number Divisible by 7**

Which number among 24963, 24973, 24983 and 24993 is divisible by 7?

**Options:**
- [ ] 24973
- [ ] 24963
- [ ] 24993
- [ ] 24983

### Solution:

Using the **divisibility rule for 7**: Double the last digit and subtract from the rest.

**Testing 24983:**
- Last digit 3 → double = 6, remaining 2498 → 2498 - 6 = 2492
- Last digit 2 → double = 4, remaining 249 → 249 - 4 = 245
- $245 ÷ 7 = 35$ ✓

**Answer:** $\boxed{24983}$

**Correct Answer: 24983**

---

## **Question 5: Missing Digit for Divisibility by 18**

An 11-digit number 7823326867X is divisible by 18. What is the value of X?

**Options:**
- [ ] 2
- [ ] 6
- [ ] 8
- [ ] 4

### Solution:

**Rule:** A number is divisible by 18 if divisible by both 2 AND 9.

**Step 1:** Divisible by 2
- Last digit must be even → X ∈ {0, 2, 4, 6, 8}

**Step 2:** Divisible by 9
- Sum of digits: $7 + 8 + 2 + 3 + 3 + 2 + 6 + 8 + 6 + 7 = 52$
- For divisibility by 9: $52 + X ≡ 0 \pmod{9}$
- $52 ÷ 9$ leaves remainder 7
- Need: $9 - 7 = 2$

**Answer:** $\boxed{2}$

**Correct Answer: 2**

---

## **Question 6: Finding the Dividend**

In a division sum, the divisor is 13 times the quotient and 6 times the remainder. If the remainder is 39, then the dividend is:

**Options:**
- [ ] 4800
- [ ] 4576
- [ ] 4251
- [ ] 4240

### Solution:

**Step 1:** Find the divisor
$$\text{Divisor} = 6 \times 39 = 234$$

**Step 2:** Find the quotient
$$234 = 13 \times \text{quotient} \Rightarrow \text{quotient} = 18$$

**Step 3:** Apply dividend formula
$$\text{Dividend} = \text{Divisor} \times \text{Quotient} + \text{Remainder}$$
$$= 234 \times 18 + 39 = 4212 + 39 = \boxed{4251}$$

**Correct Answer: 4251**

---

## **Question 7: Finding Digits for Divisibility by 72**

If the 8-digit number 789x531y is divisible by 72, then the value of (5x - 3y) is:

**Options:**
- [ ] 0
- [ ] 2
- [ ] -1
- [ ] 1

### Solution:

**Rule:** Divisible by 72 → divisible by 8 AND 9

**Step 1:** Divisible by 8 (check last 3 digits)
- Last 3 digits: 31y → 312 ÷ 8 = 39 ✓
- Therefore, $y = 2$

**Step 2:** Divisible by 9 (sum of digits)
- Known digits sum: $7 + 8 + 9 + 5 + 3 + 1 + 2 = 35 + x$
- For divisibility by 9: $35 + x ≡ 0 \pmod{9}$
- $35 ÷ 9$ leaves remainder 8
- Therefore, $x = 1$

**Step 3:** Calculate $(5x - 3y)$
$$5(1) - 3(2) = 5 - 6 = \boxed{-1}$$

**Correct Answer: -1**

---

## **Question 8: Remainder After Multiplication**

A integer n is divided by 7 leaves remainder 3. When the 6 times of the number is divided by 7, the remainder is:

**Options:**
- [ ] 1
- [ ] 2
- [ ] 4
- [ ] 0

### Solution:

**Step 1:** Original remainder = 3

**Step 2:** Multiply the remainder by 6
$$3 \times 6 = 18$$

**Step 3:** Find remainder when 18 is divided by 7
$$18 ÷ 7 = 2 \text{ remainder } 4$$

**Answer:** $\boxed{4}$

**Correct Answer: 4**

---

## **Question 9: Count of Numbers Divisible by 13**

How many numbers 800 to 2000 are divisible by 13?

**Options:**
- [ ] 90
- [ ] 92
- [ ] 93
- [ ] 91

### Solution:

**Step 1:** Find first number ≥ 800 divisible by 13
$$800 ÷ 13 ≈ 61.53 \Rightarrow \text{First} = 13 \times 62 = 806$$

**Step 2:** Find last number ≤ 2000 divisible by 13
$$2000 ÷ 13 ≈ 153.84 \Rightarrow \text{Last} = 13 \times 153 = 1989$$

**Step 3:** Count using formula
$$\text{Count} = \frac{1989 - 806}{13} + 1 = \frac{1183}{13} + 1 = 91 + 1 = \boxed{92}$$

**Correct Answer: 92**

---

## **Question 10: Finding a Fraction**

By adding 3 and 5 in numerator and denominator of a fraction it becomes 2/3. If 1 and 3 are subtracted and added from numerator and denominator respectively it becomes 2/5 find the fraction?

**Options:**
- [ ] 5/7
- [ ] 6/7
- [ ] 7/6
- [ ] 7/5

### Solution:

Let the fraction be $\frac{x}{y}$.

**Step 1:** First condition
$$\frac{x + 3}{y + 5} = \frac{2}{3}$$
$$3(x + 3) = 2(y + 5)$$
$$3x - 2y = 1 \quad \text{...(1)}$$

**Step 2:** Second condition
$$\frac{x - 1}{y + 3} = \frac{2}{5}$$
$$5(x - 1) = 2(y + 3)$$
$$5x - 2y = 11 \quad \text{...(2)}$$

**Step 3:** Solve by subtraction
$$(2) - (1): 2x = 10 \Rightarrow x = 5$$
$$\text{From (1): } 15 - 2y = 1 \Rightarrow y = 7$$

**Answer:** $\boxed{\frac{5}{7}}$

**Correct Answer: 5/7**

---

## **Question 11: Sum of Numbers in a Ratio**

Two positive numbers are in the ratio 8 : 13. If the sum of their squares is 2097, then the sum of the two numbers is:

**Options:**
- [ ] 63
- [ ] 64
- [ ] 65
- [ ] 53

### Solution:

**Step 1:** Express numbers in ratio
- Let the numbers be $8k$ and $13k$

**Step 2:** Use the condition
$$(8k)^2 + (13k)^2 = 2097$$
$$64k^2 + 169k^2 = 2097$$
$$233k^2 = 2097$$
$$k^2 = 9 \Rightarrow k = 3$$

**Step 3:** Find the numbers
- First number: $8 \times 3 = 24$
- Second number: $13 \times 3 = 39$

**Step 4:** Sum
$$24 + 39 = \boxed{63}$$

**Correct Answer: 63**

---

## **Question 12: Count Two-Digit Numbers**

How many two digit numbers are divisible by 3 or 5?

**Options:**
- [ ] 41
- [ ] 48
- [ ] 42
- [ ] 40

### Solution:

**Step 1:** Divisible by 3
- Count = $\frac{99 - 12}{3} + 1 = 30$

**Step 2:** Divisible by 5
- Count = $\frac{95 - 10}{5} + 1 = 18$

**Step 3:** Divisible by both 3 and 5 (i.e., by 15)
- Count = $\frac{90 - 15}{15} + 1 = 6$

**Step 4:** Inclusion-Exclusion Principle
$$30 + 18 - 6 = \boxed{42}$$

**Correct Answer: 42**

---

## **Question 13: Number NOT Divisible by 150**

Which of the following numbers is not divisible by 150?

**Options:**
- [ ] 320550
- [ ] 201300
- [ ] 463750
- [ ] 333300

### Solution:

**Rule:** Divisible by 150 requires divisibility by 2, 3, and 25.

**Testing 463750:**
- Divisible by 2? Last digit 0 ✓
- Divisible by 3? Sum = 4+6+3+7+5+0 = 25 ✗ (not divisible by 3)
- Therefore, NOT divisible by 150

**Answer:** $\boxed{463750}$

**Correct Answer: 463750**

---

## **Question 14: Finding Digits for Divisibility by 72**

If a 10-digit number 5432y1749x is divisible by 72, then what is the value of (5x - 4y)?

**Options:**
- [ ] 14
- [ ] 9
- [ ] 15
- [ ] 10

### Solution:

**Rule:** Divisible by 72 → divisible by 8 AND 9

**Step 1:** Divisible by 8 (check last 3 digits)
- Last 3 digits: 49x → 496 ÷ 8 = 62 ✓
- Therefore, $x = 6$

**Step 2:** Divisible by 9 (sum of digits)
- Known digits sum: $5+4+3+2+1+7+4+9+6 = 41 + y$
- $41 ÷ 9$ leaves remainder 5
- Need: $y = 4$

**Step 3:** Calculate $(5x - 4y)$
$$5(6) - 4(4) = 30 - 16 = \boxed{14}$$

**Correct Answer: 14**

---

## **Question 15: Two-Digit Number with Inverted Property**

There is a number of two digits the sum of whose digits is 5, and if 10 times the digit in the place of tens be added to 4 times the digit in the place of units, the number will be inverted. Then the number is:

**Options:**
- [ ] 43
- [ ] 41
- [ ] 23
- [ ] 32

### Solution:

Let tens digit = $x$, units digit = $y$

**Step 1:** Sum condition
$$x + y = 5 \quad \text{...(1)}$$

**Step 2:** Inversion condition
$$10x + 4y = 10y + x$$
$$9x - 6y = 0$$
$$y = 1.5x \quad \text{...(2)}$$

**Step 3:** Solve
$$x + 1.5x = 5$$
$$2.5x = 5 \Rightarrow x = 2$$
$$y = 3$$

**Answer:** $\boxed{23}$

**Correct Answer: 23**

---

## **Question 16: Society Subscription Problem**

I collected some money by raising subscription for opening a society. If the whole amount collected by 720 currency notes of Rs. 1000 denomination and each person subscribed as many rupees as twice the number of subscribers, then find the number of subscribers.

**Options:**
- [ ] 650
- [ ] 550
- [ ] 500
- [ ] 600

### Solution:

**Step 1:** Total amount
$$\text{Total} = 720 \times 1000 = 720,000 \text{ Rs.}$$

**Step 2:** Set up equation
- Number of subscribers = $x$
- Each person subscribes = $2x$ rupees

**Step 3:** Form equation
$$x \times 2x = 720,000$$
$$2x^2 = 720,000$$
$$x^2 = 360,000$$
$$x = \sqrt{360,000} = \boxed{600}$$

**Correct Answer: 600**

---

## **Question 17: Simplify Complex Expression**

Simplify: $264 - [ 142 - \{ 75 + ( 38 - ( \frac{5}{4} + \frac{11}{4} ) ) \} ]$

**Options:**
- [ ] 234
- [ ] 230
- [ ] 232
- [ ] 231

### Solution:

**Step 1:** Innermost brackets
$$\frac{5}{4} + \frac{11}{4} = \frac{16}{4} = 4$$

**Step 2:** Next level
$$38 - 4 = 34$$

**Step 3:** Continue outward
$$75 + 34 = 109$$

**Step 4:** Next
$$142 - 109 = 33$$

**Step 5:** Final
$$264 - 33 = \boxed{231}$$

**Correct Answer: 231**

---

## **Question 18: Remainder Transfer**

A number when divided by 221, leaves a remainder 30. If the same number is divided by 13, the remainder will be:

**Options:**
- [ ] 2
- [ ] 3
- [ ] 1
- [ ] 4

### Solution:

**Step 1:** Express the number
$$\text{Number} = 221k + 30$$

**Step 2:** Divide by 13
$$\frac{221k + 30}{13}$$

**Step 3:** Check if 221 is divisible by 13
$$221 = 13 \times 17 \text{ (exactly)}$$

**Step 4:** Find remainder of 30 by 13
$$30 = 13 \times 2 + 4$$

**Answer:** $\boxed{4}$

**Correct Answer: 4**

---

## **Question 19: Working Backward from Result**

7 is added to a certain number and the sum is multiplied by 5. The product is then divided by 3 and 4 is subtracted from the quotient. If the result comes to 16, then what is the original number?

**Options:**
- [ ] 5
- [ ] 3
- [ ] 4
- [ ] 1

### Solution:

Let the number = $x$

**Step 1:** Build the equation
$$\frac{5(x + 7)}{3} - 4 = 16$$

**Step 2:** Solve
$$\frac{5(x + 7)}{3} = 20$$
$$5(x + 7) = 60$$
$$x + 7 = 12$$
$$x = \boxed{5}$$

**Correct Answer: 5**

---

## **Question 20: Multiple Divisibility Conditions**

If the 6-digit numbers x35624 and 1257y4 are divisible by 11 and 72, respectively, then what is the value of (5x - 2y)?

**Options:**
- [ ] 14
- [ ] 12
- [ ] 10
- [ ] 13

### Solution:

**Step 1:** Find x (divisibility by 11)
- Odd positions: $x + 5 + 2 = x + 7$
- Even positions: $3 + 6 + 4 = 13$
- Difference: $(x + 7) - 13 = x - 6$ must be divisible by 11
- Therefore, $x = 6$

**Step 2:** Find y (divisibility by 72 = 8 × 9)
- Last 3 digits (31y): 704 ÷ 8 = 88, 784 ÷ 8 = 98 → possible y: 0, 4, 8
- Sum of digits: $1 + 2 + 5 + 7 + y + 4 = 19 + y$
- For divisibility by 9: $19 + 8 = 27$ ✓
- Therefore, $y = 8$

**Step 3:** Calculate $(5x - 2y)$
$$5(6) - 2(8) = 30 - 16 = \boxed{14}$$

**Correct Answer: 14**
