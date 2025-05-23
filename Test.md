# Unit II: Overview of Analog Circuits - Operational Amplifiers  

## 1. Introduction to Operational Amplifiers (Op-Amps)  
An **Operational Amplifier (Op-Amp)** is a high-gain voltage amplifier with a differential input and a single-ended output. It is widely used in analog circuits for amplification, filtering, and mathematical operations.  

### Key Features of an Op-Amp:  
- **High open-loop gain (A<sub>OL</sub>)** (typically 10<sup>5</sup> or more).  
- **High input impedance** (draws minimal current from the input source).  
- **Low output impedance** (can drive loads effectively).  
- **Wide bandwidth** (works for a range of frequencies).  

---

## 2. Ideal vs Practical Op-Amp  

### **Ideal Op-Amp Characteristics:**  
- **Infinite open-loop gain (A<sub>OL</sub> = ∞).**  
- **Infinite input impedance (Z<sub>in</sub> = ∞).**  
- **Zero output impedance (Z<sub>out</sub> = 0).**  
- **Infinite bandwidth (no frequency limitations).**  
- **Zero offset voltage (V<sub>os</sub> = 0).**  

### **Practical Op-Amp Limitations:**  
- **Finite gain (A<sub>OL</sub> ≈ 10<sup>5</sup>–10<sup>6</sup>).**  
- **Finite input impedance (Z<sub>in</sub> ≈ 1MΩ–10MΩ).**  
- **Non-zero output impedance (Z<sub>out</sub> ≈ 50Ω–200Ω).**  
- **Limited bandwidth (affected by frequency).**  
- **Small input offset voltage (V<sub>os</sub> ≈ 1mV–5mV).**  

---

## 3. Open-Loop vs Closed-Loop Configurations  

### **Open-Loop Configuration:**  
- No feedback is applied.  
- Output is **saturated (V<sub>out</sub> = ±V<sub>sat</sub>)** due to extremely high gain.  
- Used in **comparators** (e.g., comparing two voltages).  

### **Closed-Loop Configuration:**  
- Feedback is applied (output connected back to input).  
- Gain is controlled and stabilized.  
- Two types:  
  - **Negative Feedback** → Stabilizes gain (used in amplifiers).  
  - **Positive Feedback** → Causes saturation (used in oscillators).  

---

## 4. Applications of Op-Amps  

### **1. Inverting Amplifier**  
- **Amplifies and inverts** the input signal.  
- Gain formula:  
  \[
  A_v = -\frac{R_f}{R_{in}}
  \]  

### **2. Non-Inverting Amplifier**  
- **Amplifies without inverting** the input.  
- Gain formula:  
  \[
  A_v = 1 + \frac{R_f}{R_{in}}
  \]  

### **3. Adder (Summing Amplifier)**  
- **Sums multiple input signals.**  
- Output formula:  
  \[
  V_{out} = -R_f \left( \frac{V_1}{R_1} + \frac{V_2}{R_2} + \dots \right)
  \]  

### **4. Differentiator**  
- **Output is the derivative of the input.**  
- Formula:  
  \[
  V_{out} = -RC \frac{dV_{in}}{dt}
  \]  

### **5. Integrator**  
- **Output is the integral of the input.**  
- Formula:  
  \[
  V_{out} = -\frac{1}{RC} \int V_{in} \, dt
  \]  

---

## 5. Summary  
- **Ideal Op-Amps** have infinite gain and bandwidth, but **practical Op-Amps** have limitations.  
- **Open-loop** mode is used in comparators, while **closed-loop** mode stabilizes gain.  
- Op-Amps can be used as **amplifiers, adders, differentiators, and integrators** in analog circuits.  
