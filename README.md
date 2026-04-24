# Transfer Function

A **transfer function** is a mathematical representation that models the input–output relationship of a Linear Time-Invariant (LTI) system.

---

## 1. Transfer Function of Low-Pass Filter

The transfer function is given by:
Hw = Vout/Vin =  Zc / (Zr + Zc)

Where:

Zc = 1 / (ωC)  
Zr = R  

Substituting:

H(ω) = R / (R + ωC)

Simplifying:

H(ω) = 1 / (1 + ωRC)

For given values:

H(ω) = 1 / (1 + ω · 25 × 10⁻³`)

---

## 2. Transfer Function of Band-Pass Filter

A band-pass filter is formed by cascading a high-pass filter and a low-pass filter.

---

### Step 1: Individual Transfer Functions

#### High-Pass Filter

Hw = Vout/Vin =  Zc / (Zr + Zc)

H_HP(ω) = (ωR₁C₁) / (1 + ωR₁C₁)

---

#### Low-Pass Filter

H_LP(ω) = 1 / (1 + ωR₂C₂)

---

### Step 2: Overall Transfer Function

Since the filters are cascaded:

H(ω) = (ωR₁C₁) / [(1 + ωR₁C₁)(1 + ωR₂C₂)]
---

### Final Expression with Values

H(ω) = (ω · 0.159 × 10⁻³) / [(1 + ω · 0.159 × 10⁻³)(1 + ω · 0.159 × 10⁻⁴)]

---
