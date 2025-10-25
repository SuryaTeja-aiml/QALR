# Unit Digit (Last Digit)

## Core Concept
When finding the unit digit of any expression, we only care about the **last digit** of each number involved. This simplifies calculations dramatically.

---

## **Method 1: For Products (Multiplication)**

**Rule:** Multiply only the unit digits of each number. After each multiplication step, keep only the unit digit of the result.

**Formula:**
- Extract unit digits from all numbers
- Multiply them one by one
- After each multiplication, take only the last digit
- Continue until all numbers are multiplied

**Example:** For a product like 897 × 636 × 804 × 993
- Unit digits: 7, 6, 4, 3
- 7 × 6 = 42 → keep 2
- 2 × 4 = 8 → keep 8
- 8 × 3 = 24 → keep 4
- **Answer: 4**

---

## **Method 2: For Powers (Exponents)**

Powers of digits follow repeating cycles. Instead of computing huge powers, use these cycles:

**Cycles (repeating patterns):**

| Base Digit | Cycle | Cycle Length |
|------------|-------|--------------|
| 0 | 0 | 1 |
| 1 | 1 | 1 |
| 2 | 2, 4, 8, 6 | 4 |
| 3 | 3, 9, 7, 1 | 4 |
| 4 | 4, 6 | 2 |
| 5 | 5 | 1 |
| 6 | 6 | 1 |
| 7 | 7, 9, 3, 1 | 4 |
| 8 | 8, 4, 2, 6 | 4 |
| 9 | 9, 1 | 2 |

**Formula to Find Unit Digit of a^b:**
1. Find the unit digit of the base number (call it 'd')
2. Find the cycle of that digit
3. Divide the exponent by the cycle length: b ÷ (cycle length)
4. Find the remainder when dividing
5. Use the remainder to pick which element from the cycle
   - If remainder is 0, use the last element in the cycle
   - Otherwise, use the element at position = remainder

**Example:** For 142^123
- Unit digit of base: 2
- Cycle of 2: (2, 4, 8, 6) with length 4
- 123 ÷ 4 = 30 remainder **3**
- Pick 3rd element from cycle: **8**

**Example:** For 3^13758
- Unit digit of base: 3
- Cycle of 3: (3, 9, 7, 1) with length 4
- 13758 ÷ 4 = 3439 remainder **2**
- Pick 2nd element from cycle: **9**

---

## **Method 3: For Additions/Sums**

**Rule:** Find the unit digit of each term separately, then add all these unit digits together, and take the unit digit of the sum.

**Formula:**
- Find unit digit of each term
- Add all these unit digits
- Take the unit digit of this sum

**Example:** For 15^301 + 156^132564
- 15^301 has unit digit: 5 (all powers of 5 end in 5)
- 156^132564 has unit digit: 6 (all powers of 6 end in 6)
- Sum: 5 + 6 = 11 → unit digit **1**

---

## **Method 4: For Subtractions (Differences)**

**Rule:** Find the unit digit of each term, subtract them. If the result is negative, add 10 to make it positive.

**Formula:**
- Find unit digit of first term
- Find unit digit of second term
- Subtract: first − second
- If negative, add 10
- Result is the unit digit

**Example:** For 7^95 − 3^13758
- 7^95 has unit digit: 3
- 3^13758 has unit digit: 9
- Difference: 3 − 9 = −6
- Add 10: −6 + 10 = **4**

---

## **Method 5: For Complex Expressions (Mixed Operations)**

**Rule:** Follow order of operations (PEMDAS). Compute powers first, then multiplication, then addition/subtraction.

**Steps:**
1. Find unit digits of all bases
2. Calculate unit digit of each power using cycles
3. Multiply all the resulting unit digits together (keeping only unit digit after each step)
4. Add/subtract any constant terms' unit digits
5. Final answer is the unit digit of the combined result

**Example:** For 13^24 × 68^57 × 24^13 × 57^68 + 1234 + 5678
- 3^24 → 24 mod 4 = 0 → unit digit: **1**
- 8^57 → 57 mod 4 = 1 → unit digit: **8**
- 4^13 → 13 is odd → unit digit: **4**
- 7^68 → 68 mod 4 = 0 → unit digit: **1**
- Multiply: 1 × 8 = 8, then 8 × 4 = 32 → unit 2, then 2 × 1 = 2 → unit **2**
- Constants: 1234 has unit 4, 5678 has unit 8 → 4 + 8 = 12 → unit **2**
- Final: 2 + 2 = 4 → unit digit **4**

---

## **Method 6: For Series (Sum of k^k)**

**Rule:** Calculate unit digit of each term k^k separately, then sum all unit digits.

**Steps:**
1. For k = 1, 2, 3, ... up to given number
2. Calculate k^k and find its unit digit
3. Keep a running sum of these unit digits
4. After each addition, keep only the unit digit
5. Final sum's unit digit is the answer

**Example:** For 1^1 + 2^2 + 3^3 + ... + 10^10
- 1^1 → 1
- 2^2 → 4
- 3^3 → 7
- 4^4 → 6
- 5^5 → 5
- 6^6 → 6
- 7^7 → 3
- 8^8 → 6
- 9^9 → 9
- 10^10 → 0
- Sum: 1+4+7+6+5+6+3+6+9+0 = 47 → unit digit **7**

---

## **Key Shortcuts to Remember**

- **Any number ending in 0:** Unit digit is always **0**
- **Any number ending in 1:** Unit digit is always **1**
- **Any number ending in 5:** Unit digit is always **5**
- **Any number ending in 6:** Unit digit is always **6**
- **5 times any odd digit:** Result always ends in **5**
- **Even digit × 5:** Result always ends in **0**
- **6 raised to any power:** Always ends in **6**

---

## **Summary Flow Chart**

```
START with expression
↓
Identify operation type (product/sum/difference/power)
↓
Extract unit digits of all numbers
↓
For POWERS: Use cycle method
For PRODUCTS: Multiply unit digits stepwise
For SUMS: Add unit digits
For DIFFERENCES: Subtract and add 10 if negative
↓
Keep only unit digit after each operation
↓
Final unit digit is the answer
END
```
