Aakash Choudhari

E&TC-A2

24070123031

# 🧪 Experiment 3 - Bitwise Operators in C++

## 🎯 Aim:
To understand and implement various bitwise operations in C++ and analyze how they manipulate individual bits of integer values.

---

## 🧠 Theory:

In C++, **bitwise operators** are used to perform operations at the binary level — directly manipulating the bits of integer data types. These operations are extremely fast and useful in systems programming, embedded systems, and performance-critical applications.

Bitwise operations can only be applied to **integral types** (e.g., `int`, `char`, `long`).

---

### ➤ Bitwise Operators in C++

| Operator | Symbol | Description                                      | Example (a = 5, b = 3) |
|----------|--------|--------------------------------------------------|------------------------|
| AND      | `&`    | Sets bit to 1 if both bits are 1                | `a & b` → `5 & 3 = 1`  |
| OR       | `|`    | Sets bit to 1 if at least one bit is 1          | `a | b` → `5 | 3 = 7`  |
| XOR      | `^`    | Sets bit to 1 if only one of the bits is 1      | `a ^ b` → `5 ^ 3 = 6`  |
| NOT      | `~`    | Inverts all bits (1’s complement)               | `~a` → `~5 = -6`       |
| Left Shift  | `<<` | Shifts bits to the left, filling 0s on right    | `a << 1` → `10`        |
| Right Shift | `>>` | Shifts bits to the right, discards right bits   | `a >> 1` → `2`         |

### 🔍 Binary Example:
For integers `a = 5` and `b = 3`:
a = 5 → 0101
b = 3 → 0011

a & b = 0001 → 1
a | b = 0111 → 7
a ^ b = 0110 → 6
~a    = 1010 → -6 (due to two’s complement)

---

## ⚙️ Procedure:

1. Open your C++ environment and create a new program file.
2. Declare integer variables (e.g., `int a = 5, b = 3;`).
3. Apply each bitwise operator:
   - AND `&`, OR `|`, XOR `^`, NOT `~`, Left Shift `<<`, Right Shift `>>`
4. Use `cout` to display the results of each operation.
5. Observe and verify the outputs based on the binary representations.

---

## 🔍 Learning Outcomes:

- Gained a clear understanding of how bits are manipulated in memory.
- Explored the difference between logical and bitwise operations.
- Understood shift operations and how they affect the magnitude of numbers.
- Observed the behavior of negative numbers with bitwise NOT.

---

## 📌 Key Concepts Covered:

- Binary representation of integers
- Bitwise logical operations (`&`, `|`, `^`, `~`)
- Bit shifting (`<<`, `>>`)
- Application of bitwise operations in low-level computing

---

## 📝 Experiment Summary:

This experiment explored **bitwise operators**, which work directly on the binary bits of data. Understanding these operations is crucial for low-level programming, optimization, cryptography, and embedded systems development. Bitwise manipulation gives a deeper appreciation of how computers interpret and store data at the hardware level.

---
