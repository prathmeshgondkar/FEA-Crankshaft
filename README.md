# 🔩 Finite Element Analysis of a Crankshaft – AISI 4130 vs Cast Alloy Steel

This project presents a comparative static FEA of a crankshaft made with two different materials under identical loading and boundary conditions.

## 📌 Objective
To compare structural performance—stress, deflection, and strain—of:
- **AISI 4130 Normalized Steel** (forged)
- **Cast Alloy Steel**

## 🔧 Model Details
- **Geometry:** Single-throw crankshaft (same for both cases)
- **Load:** 16,000 N at crankpin (center)
- **Supports:** Fixed hinges on both ends
- **Software:** SolidWorks Simulation (Static Study)

## 📐 Material Properties

| Property         | AISI 4130 | Cast Steel | Difference |
|------------------|-----------|------------|------------|
| Yield Strength   | ~435 MPa  | ~241 MPa   | +81%       |
| Young’s Modulus  | 205 GPa   | 190 GPa    | +7.9%      |
| Max Displacement | ~3.2 mm   | ~3.5 mm    | -8.6%      |
| Max Strain       | 1.25e-4   | 1.34e-4    | -6.7%      |

## 📊 Results

### Von Mises Stress
[Stress - AISI 4130](images/stress_static_1.png)
[Stress - Cast Steel](images/stress_static_2.png)

### Displacement
[Displacement - AISI 4130](images/displacement_static_1.png)
[Displacement - Cast Steel](images/displacement_static_2.png)

### Strain
[Strain - AISI 4130](images/strain_static_1.png)
[Strain - Cast Steel](images/strain_static_2.png)

## 🧠 Key Insights
- Both materials showed **similar stress distribution** (~38 MPa).
- AISI 4130 had **better performance** in terms of stiffness, strain, and safety factor.
- Cast steel is lighter but reaches its material limit faster.

## 📎 Full Report
👉 [Link to PDF or DOCX version here]

## 🔗 Author
Prathmesh Deepak Gondkar  
[LinkedIn](https://www.linkedin.com/in/prathmeshgondkar)

