# Transfer Function

A **transfer function** is a mathematical representation that models the input–output relationship of a Linear Time-Invariant (LTI) system.

---

## 1. Transfer Function of Low-Pass Filter

The transfer function is given by:

\[
H(\omega) = \frac{V_{\text{out}}}{V_{\text{in}}} = \frac{Z_C}{Z_R + Z_C}
\]

Where:

- \( Z_C = \frac{1}{\omega C} \)
- \( Z_R = R \)

Substituting:

\[
H(\omega) = \frac{\frac{1}{\omega C}}{R + \frac{1}{\omega C}}
\]

Simplifying:

\[
H(\omega) = \frac{1}{1 + \omega RC}
\]

For given values:

\[
H(\omega) = \frac{1}{1 + \omega \cdot 0.159 \times 10^{-3}}
\]

---

## 2. Transfer Function of Band-Pass Filter

A band-pass filter is formed by cascading a high-pass filter and a low-pass filter.

---

### Step 1: Individual Transfer Functions

#### High-Pass Filter

\[
H_{\text{HP}}(\omega) = \frac{Z_R}{Z_R + Z_C}
\]

\[
H_{\text{HP}}(\omega) = \frac{\omega R_1 C_1}{1 + \omega R_1 C_1}
\]

---

#### Low-Pass Filter

\[
H_{\text{LP}}(\omega) = \frac{1}{1 + \omega R_2 C_2}
\]

---

### Step 2: Overall Transfer Function

Since the filters are cascaded:

\[
H(\omega) = H_{\text{HP}}(\omega) \cdot H_{\text{LP}}(\omega)
\]

\[
H(\omega) = \frac{\omega R_1 C_1}{(1 + \omega R_1 C_1)(1 + \omega R_2 C_2)}
\]

---

### Final Expression with Values

\[
H(\omega) = \frac{\omega \cdot 0.159 \times 10^{-3}}{\left(1 + \omega \cdot 0.159 \times 10^{-3}\right)\left(1 + \omega \cdot 0.159 \times 10^{-4}\right)}
\]

---
