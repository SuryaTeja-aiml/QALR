## 🔹 MOD & DIVISION

**MOD** = Find the remainder when one number divides another

Notation: `a mod m = remainder when a ÷ m`

### Division Algorithm
```
N = d × q + r
```
- **N** = Dividend (number being divided)
- **d** = Divisor (dividing by this)
- **q** = Quotient (how many times)
- **r** = Remainder (what's left)
- **Constraint:** 0 ≤ r < d

---

## 🔹 ALGEBRAIC IDENTITIES

### Difference of Squares
```
a² - b² = (a + b)(a - b)
```

### Perfect Square Expansion
```
(a + b)² = a² + 2ab + b²
(a - b)² = a² - 2ab + b²
```

### Key Identity for Differences
```
(a - b)² = (a + b)² - 4ab
```

---

## 🔹 DIVISIBILITY RULES

| Rule | Condition |
|------|-----------|
| **2** | Last digit is even |
| **3** | Sum of digits divisible by 3 |
| **5** | Last digit is 0 or 5 |
| **8** | Last 3 digits divisible by 8 |
| **9** | Sum of digits divisible by 9 |
| **11** | (Odd position sum) - (Even position sum) divisible by 11 |
| **25** | Last 2 digits: 00, 25, 50, or 75 |

### Composite Divisibility
For composite numbers, decompose into coprime factors:
- 18 = 2 × 9
- 72 = 8 × 9
- 150 = 2 × 3 × 25
- 88 = 8 × 11

---

## 🔹 COUNTING & ARITHMETIC PROGRESSIONS

### Count of Multiples in Range
```
Count = ⌊(Last - First) / d⌋ + 1
```

### First Multiple ≥ a
```
First = ⌈a / d⌉ × d
```

### Last Multiple ≤ b
```
Last = ⌊b / d⌋ × d
```

---

## 🔹 INCLUSION-EXCLUSION PRINCIPLE

```
Count(A or B) = Count(A) + Count(B) - Count(A and B)
```

For divisibility by multiple conditions

---

## 🔹 RATIO & PROPORTION

### Setup
If two numbers are in ratio a:b:
```
Numbers = ak and bk
```

### How to Solve
1. Express numbers as **ak** and **bk** (where k is constant)
2. Use given condition to form equation
3. Solve for k
4. Calculate both numbers: a×k and b×k
5. Find required answer (sum, product, etc.)

### Example
Numbers in ratio 8:13, sum of squares = 2097
- Let numbers = 8k and 13k
- (8k)² + (13k)² = 2097
- 64k² + 169k² = 2097
- 233k² = 2097
- k² = 9 → k = 3
- Numbers: 8(3) = 24 and 13(3) = 39

---

## 🔹 SYSTEM OF LINEAR EQUATIONS

Two equations in two unknowns:
```
a₁x + b₁y = c₁
a₂x + b₂y = c₂
```

### Solve by Elimination:
1. Multiply equations to eliminate one variable
2. Subtract equations
3. Solve for remaining variable
4. Substitute back

### Solve by Substitution:
1. Express one variable in terms of other
2. Substitute into second equation
3. Solve
4. Find second variable

---

## 🔹 DIGIT REPRESENTATION

### Two-digit Number
```
Number = 10a + b
```
- a = tens digit
- b = units digit

### Inverted Two-digit Number
```
Inverted = 10b + a
```
- Units digit becomes tens digit (multiply by 10)
- Tens digit becomes units digit (stays as is)

### Multi-digit Numbers
Use positional values for each digit position

---

## 🔹 QUADRATIC EQUATIONS

### From Given Conditions:
```
ax² + bx + c = 0
```

Solve using:
- Factorization
- Completing the square
- Formula (if needed)

---

## 🔹 FRACTION OPERATIONS

### Addition
```
a/b + c/d = (ad + bc)/(bd)
```

### Cross Multiplication
```
a/b = c/d  ⟹  ad = bc
```

### Simplification
```
(x + a)/(y + b) = p/q  ⟹  q(x + a) = p(y + b)
```

---

## 🔹 PRIME FACTORIZATION

Decompose numbers into prime factors to understand divisibility properties

Example: 221 = 13 × 17

---

## 🔹 MODULAR ARITHMETIC PROPERTIES

### Addition
```
(a + b) mod m = [(a mod m) + (b mod m)] mod m
```

### Multiplication
```
(a × b) mod m = [(a mod m) × (b mod m)] mod m
```

### Congruence
```
a ≡ b (mod m)  ⟹  a = mk + b
```

---

## 🔹 ALGEBRAIC FACTORIZATION

### Factor Common Terms
```
a·x + a·y = a(x + y)
```

### Geometric Series
```
1 + a + a² + a³ = (a⁴ - 1)/(a - 1)
```

---

## 🔹 ORDER OF OPERATIONS (BODMAS)

1. **B**rackets / Parentheses
2. **O**rders / Exponents
3. **D**ivision & **M**ultiplication (left to right)
4. **A**ddition & **S**ubtraction (left to right)

---

## 🔹 SQUARE ROOTS & POWERS

```
√x = y  where y² = x
```

Extract: Find prime factors and pair them

---

## 🔹 BASIC ARITHMETIC FORMULAS

### Sum of Digits in Range
Count and add digit by digit

### Average
```
Average = Sum / Count
```

### Percentage
```
x% of n = (x/100) × n
```

---

## ✅ VERIFICATION CHECKLIST

- ✓ N = d × q + r (for division)?
- ✓ 0 ≤ r < d (for remainder)?
- ✓ All arithmetic correct?
- ✓ Answer in required form?

---
