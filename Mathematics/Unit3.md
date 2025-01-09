# **UNIT - III: Algebra - Important Formulas and Top 10 RGPV Diploma Questions with Step-by-Step Solutions**

## **Key Formulas**

### **Complex Numbers**
1. **Polar and Cartesian Representation**:  
   A complex number `z = a + bi` has:
   - **Real Part**: `Re(z) = a`
   - **Imaginary Part**: `Im(z) = b`
   - **Polar Form**: `z = r(cos θ + i sin θ)` where:
     - `r = |z| = √(a² + b²)` (Modulus)
     - `θ = arg(z) = tan⁻¹(b/a)` (Argument or Amplitude)

2. **Conjugate of a Complex Number**:  
   If `z = a + bi`, then the conjugate is `z* = a - bi`.

3. **Modulus and Amplitude**:  
   - **Modulus**: `|z| = √(a² + b²)`
   - **Amplitude**: `arg(z) = tan⁻¹(b/a)`

4. **Operations on Complex Numbers**:
   - **Addition**: `(a + bi) + (c + di) = (a + c) + (b + d)i`
   - **Subtraction**: `(a + bi) - (c + di) = (a - c) + (b - d)i`
   - **Multiplication**: `(a + bi)(c + di) = (ac - bd) + (ad + bc)i`
   - **Division**:  
     `z₁ / z₂ = [(a + bi) / (c + di)] = [(a + bi)(c - di)] / (c² + d²)`

5. **De Moivre’s Theorem**:  
   For any complex number `z = r(cos θ + i sin θ)` and integer `n`,  
   - `zⁿ = rⁿ (cos(nθ) + i sin(nθ))`

---

### **Partial Fractions**
1. **Proper and Improper Fractions**:
   - **Proper Fraction**: The degree of the numerator is less than the degree of the denominator.
   - **Improper Fraction**: The degree of the numerator is equal to or greater than the degree of the denominator.

2. **Types of Partial Fractions**:
   - **Non-repeated Linear Factors**:  
     `A / (x - p) + B / (x - q)`
   - **Repeated Linear Factors**:  
     `A / (x - p) + B / (x - p)²`
   - **Irreducible Non-repeated Quadratic Factors**:  
     `Ax + B / (x² + px + q)`

3. **Resolution of Improper Fraction**:  
   First divide the numerator by the denominator to make it a proper fraction, and then apply partial fractions.

---

### **Permutations and Combinations**
1. **Permutation**:  
   `nPr = n! / (n - r)!`  
   The number of ways to arrange `r` objects from `n` distinct objects.

2. **Combination**:  
   `nCr = n! / (r! (n - r)!)`  
   The number of ways to choose `r` objects from `n` distinct objects without regard to order.

---

### **Binomial Theorem**
1. **Binomial Theorem for Positive Integral Index**:  
   For `n` a positive integer,  
   `(x + y)ⁿ = Σ (nCr * x^(n-r) * y^r)` where `r = 0 to n`.

2. **Binomial Theorem for Any Index**:  
   `(x + y)ⁿ = Σ (nCr * x^(n-r) * y^r)` (The expansion is valid for any real number `n`).

3. **Binomial Approximation**:
   - **First Binomial Approximation**: `(1 + x)^n ≈ 1 + nx` for small `x`.
   - **Second Binomial Approximation**: `(1 + x)^n ≈ 1 + nx + n(n - 1) * x² / 2!` for small `x`.

---

## **Top 10 RGPV Diploma Questions with Step-by-Step Solutions**

### 1. **Find the sum of the complex numbers `(3 + 4i)` and `(2 - 5i)`.**
   **Solution**:  
   - **Formula**: Use the formula for addition of complex numbers.  
   - Sum: `(3 + 4i) + (2 - 5i) = (3 + 2) + (4 - 5)i = 5 - i`

### 2. **Find the modulus and argument of the complex number `z = 1 + √3i`.**
   **Solution**:  
   - **Modulus**: `|z| = √(1² + (√3)²) = √(1 + 3) = √4 = 2`  
   - **Argument**: `arg(z) = tan⁻¹(√3/1) = tan⁻¹(√3) = π/3`

### 3. **Multiply the complex numbers `(2 + 3i)` and `(1 - 4i)`.**
   **Solution**:  
   - **Formula**: Use the multiplication formula for complex numbers.  
   - Multiplication:  
     `(2 + 3i)(1 - 4i) = (2*1 - 2*4i + 3i - 3*4i²) = 2 - 8i + 3i + 12 = 14 - 5i`

### 4. **Divide `(3 + 4i)` by `(1 - 2i)`.**
   **Solution**:  
   - **Formula**: Use the division formula for complex numbers.  
   - Division:  
     `(3 + 4i) / (1 - 2i) = [(3 + 4i)(1 + 2i)] / [(1 - 2i)(1 + 2i)] = (11 + 2i) / 5 = 11/5 + (2/5)i`

### 5. **Find the partial fraction decomposition of `1 / (x² - 5x + 6)`.**
   **Solution**:  
   - **Factor the denominator**:  
     `x² - 5x + 6 = (x - 2)(x - 3)`  
   - **Apply partial fractions**:  
     `1 / (x² - 5x + 6) = A / (x - 2) + B / (x - 3)`  
     Solving for `A` and `B`,  
     `A = 1` and `B = -1`.  
   - Final answer: `1 / (x² - 5x + 6) = 1 / (x - 2) - 1 / (x - 3)`

### 6. **Find the number of ways to arrange 3 objects from 5 distinct objects.**
   **Solution**:  
   - **Formula**: Use the permutation formula.  
   - `nPr = 5P3 = 5! / (5 - 3)! = 5 × 4 × 3 = 60`

### 7. **Find the number of ways to choose 2 objects from 6 distinct objects.**
   **Solution**:  
   - **Formula**: Use the combination formula.  
   - `nCr = 6C2 = 6! / (2! × 4!) = 15`

### 8. **Expand `(1 + x)⁴` using the binomial theorem.**
   **Solution**:  
   - **Formula**: Use the binomial theorem for positive integral index.  
   - Expansion:  
     `(1 + x)⁴ = 1 + 4x + 6x² + 4x³ + x⁴`

### 9. **Find the first binomial approximation for `(1 + x)ⁿ` where `n = 5` and `x = 0.1`.**
   **Solution**:  
   - **Formula**: Use the first binomial approximation formula.  
   - Approximation:  
     `(1 + x)⁵ ≈ 1 + 5x = 1 + 5(0.1) = 1.5`

### 10. **Resolve `4 / (x² - 4)` into partial fractions.**
   **Solution**:  
   - **Factor the denominator**:  
     `x² - 4 = (x - 2)(x + 2)`  
   - **Apply partial fractions**:  
     `4 / (x² - 4) = A / (x - 2) + B / (x + 2)`  
     Solving for `A` and `B`,  
     `A = 1` and `B = -1`.  
   - Final answer: `4 / (x² - 4) = 1 / (x - 2) - 1 / (x + 2)`

---

These questions cover the essential concepts of Algebra, including complex numbers, partial fractions, permutations, combinations, and the binomial theorem. The step-by-step solutions explain how to apply the formulas, making it easier for you to understand the procedures for each type of problem.
