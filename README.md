# 🔩 Finite Element Analysis of a Crankshaft – AISI 4130 vs Cast Alloy Steel

This project presents a comparative static FEA of a crankshaft made with two materials under identical loading and boundary conditions.

### 🧱 Crankshaft Model
![(images/Crank_Shaft.png)](https://github.com/prathmeshgondkar/FEA-Crankshaft/blob/31fecfc7c9b440c283ed15a93795e293a0b8ed10/Crank%20Shaft.png)

## 📌 Objective
To compare structural performance—stress, deflection, and strain—of:
- **AISI 4130 Normalized Steel** (forged)
- **Cast Alloy Steel**

## 🔧 Model Details
- **Geometry:** Single-throw crankshaft (same for both cases)
- **Load:** 16,000 N at crankpin (centre)
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

### Stress Distribution Comparison
AISI 4130- ![images/Stress Static 1.png](https://github.com/prathmeshgondkar/FEA-Crankshaft/blob/33d1415176e0d944da1a5c4545a273010d70f1fc/Stress%20Static%201.png)

Cast Alloy Steel-![imags/Stress Static 2.png](https://github.com/prathmeshgondkar/FEA-Crankshaft/blob/33d1415176e0d944da1a5c4545a273010d70f1fc/Stress%20Static%202.png)

### Displacement Comparison
AISI 4130-![images/Displacement Static 1.png](https://github.com/prathmeshgondkar/FEA-Crankshaft/blob/33d1415176e0d944da1a5c4545a273010d70f1fc/Displacement%20Static%201.png)

Cast Alloy Steel-![images/Displacement Static 2.png](https://github.com/prathmeshgondkar/FEA-Crankshaft/blob/33d1415176e0d944da1a5c4545a273010d70f1fc/Displacement%20Static%202.png)

### Strain Distribution
AISI 4130-![images/Strain_Static_1.png](https://github.com/prathmeshgondkar/FEA-Crankshaft/blob/33d1415176e0d944da1a5c4545a273010d70f1fc/Strain%20Static%201.png)

Cast Alloy Steel-![images/Strain_Static_2.png](https://github.com/prathmeshgondkar/FEA-Crankshaft/blob/33d1415176e0d944da1a5c4545a273010d70f1fc/Strain%20Static%201.png)

### Mesh Quality
AISI 4130-![images/Mesh_Static_1.png](https://github.com/prathmeshgondkar/FEA-Crankshaft/blob/33d1415176e0d944da1a5c4545a273010d70f1fc/Mesh%20Static%201.png)

Cast Alloy Steel-![images/Mesh_Static_2.png](https://github.com/prathmeshgondkar/FEA-Crankshaft/blob/33d1415176e0d944da1a5c4545a273010d70f1fc/Mesh%20Static%202.png)

## 🧠 Key Insights
- Both materials showed **similar stress distribution** (~38 MPa).
- AISI 4130 had **better performance** regarding stiffness, strain, and safety factor.
- Cast steel is lighter but reaches its material limit faster.

## 📎 Full Report
👉 [FEA Crankshaft Report.pdf](https://github.com/prathmeshgondkar/FEA-Crankshaft/blob/20789e5b9b99bb79aba3030e4ab9f673882c1790/FEA%20Crankshaft%20Report.pdf)

## 🔗 Author
Prathmesh Deepak Gondkar  
[LinkedIn](https://www.linkedin.com/in/prathmeshgondkar)

⚠️ Note on Simulation Files
Due to size limitations, the primary result files (CRANK SHAFT1-Static 1 and CRANK SHAFT1-Static 2) were too large to upload directly to GitHub.

You can download them from the links below and place them inside the main project folder to view full simulation results in SolidWorks:

🔗 [CRANK SHAFT1-Static 1.CWR](https://drive.proton.me/urls/Q65GYG4R54#60latyVkk4j1)

🔗 [CRANK SHAFT1-Static 2.CWR](https://drive.proton.me/urls/Y5HGFGM54C#dsnvPZGCi2pQ)

These files are essential for opening and exploring the results interactively within SolidWorks Simulation.
