# Circular-Saw-Mechanical-Failure-Analysis
Mechanical design audit and fatigue analysis of a 7-1/4" corded circular saw. Features FMEA and shaft geometry optimization using Goodman and Gerber failure criteria.

## Project Overview
This repository documents a detailed mechanical design audit of a 7-1/4" corded circular saw. The analysis focuses on the power transmission and safety-critical components, evaluating the drive shaft, driving gear, and blade retention system under operational load cycles. 

## Technical Deep-Dive

### 1. Fatigue and Stress Analysis
Calculated the fatigue life and Factor of Safety (Nf) for the drive shaft under combined loading (bending from cutting forces and torsion from motor torque).
* **Failure Theories:** Applied both **Goodman** and **Gerber** criteria to evaluate material endurance limits.
* **Optimization:** Identified that the current shaft design was over-engineered with a safety factor of 4.27. I proposed a reduction in maximum shaft diameter from 0.5" to 0.4", which maintains a safety factor of 2.0 while significantly reducing material volume and cost.

### 2. Failure Mode and Effects Analysis (FMEA)
Conducted a systematic FMEA to identify high-risk failure modes for the following components:
* **Driving Gear:** Evaluated tooth shear and wear under high-torque startup.
* **Blade Guard Return Spring:** Analyzed fatigue failure risks that could lead to exposed blade hazards.
* **Blade Retention Bolt:** Assessed the risk of loosening due to vibrational harmonics during operation.

### 3. Material Trade Study
Performed a cost-benefit analysis between **1018 Cold Finish Carbon Steel** and **1045 Cold Finish Carbon Steel** for the drive shaft.
* **1018 Steel:** $10.56 per unit.
* **1045 Steel:** $12.54 per unit.
* **Result:** Determined that 1018 Steel provided the optimal balance of fatigue resistance and cost for a "low usage frequency" DIY market niche.

## Key Engineering Results
* **Calculated Fatigue Safety Factor:** 4.27 (Current Design).
* **Optimized Design Safety Factor:** 2.10 (Proposed 0.4" Diameter).
* **Standards Compliance:** Analysis adhered to **AGMA** standards for gear geometry and material endurance limits.

## Repository Contents
* **Circular_Saw_Mechanical_Failure_Analysis.pdf**: Full technical report including stress concentration factor (Kt) derivations, modified Goodman diagrams, and FMEA tables.
