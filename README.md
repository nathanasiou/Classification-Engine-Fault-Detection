# Evaluating Variable Subsets and Classifiers for Engine Fault Detection

This repository contains the report describing the experimental framework and results for classifying vehicle engine faults using a combination of engine and exhaust gas-sensor measurements.

Accurate fault classification is crucial for identifying which variables are most influential to engine failure. By pinpointing these critical indicators, this project highlights the specific sensor measurements that should be prioritized in onboard diagnostic systems—ultimately helping prevent sudden failures like spontaneous combustion or electrical malfunctions.

## 🔬 Core Research Question
> **How do classification models of varying complexity perform across the three analysis tracks (engine-only, gas-only, and combined-with-selection)?**

By investigating this question across distinct sensory domains, this framework thoroughly evaluates historical performance benchmarks and investigates model architecture based on **accuracy**, **interpretability**, and viability in **real-world world deployments**.

## 🎯 Impact
* **For Manufacturers:** Provides an empirical foundation for optimizing onboard diagnostic sensor layout.
* **For Customers:** Enhances overall vehicle safety and introduces predictive maintenance capabilities to reduce unanticipated repair costs.
* **For Researchers:** Benchmarks a spectrum of model granularities to support the development of next-generation, reliable vehicle-health monitoring technologies.

## 📊 Experimental Design (The Three Analysis Tracks)
The analytics pipeline is structured into three discrete execution paths to isolate the predictive power of different sensor domains:

1. **Engine-Only Track:** Models trained exclusively on engine characteristics.
2. **Gas-Only Track:** Models trained strictly on exhaust gas characteristics.
3. **Combined-with-Selection Track:** A unified dataset leveraging feature selection methods to discover gas and engine correlations while reducing high-dimensional noise.


## 📁 Repository Structure
```text
├── evaluating-variable-subsets-engine-fault-detection.pdf # final report
└── README.md 
```

## 💡 Acknowledgement
This project could not have been completed without the existing **EngineFaultDB** dataset and corresponding paper **EngineFaultDB: A Novel Dataset for Automotive Engine Fault Classification and Baseline Results**.

## 📚 References
This project utilizes the **EngineFaultDB** dataset and benchmarks its results against the baseline findings established by the original authors. 

### Academic Paper
If you wish to reference the original study and baseline evaluations, please cite the published paper:

> Mary Vergara, Leo Ramos, Néstor Diego Rivera-Campoverde, and Francklin Rivas-Echeverría. **"Enginefaultdb: A novel dataset for automotive engine fault classification and baseline results."** Research article, 2023. Available at: (https://pure.ups.edu.ec/en/publications/enginefaultdb-a-novel-dataset-for-automotive-engine-fault-classif).

### Dataset Repository
To reference the database software repository itself:

> Leo Ramos and contributors. **"Enginefaultdb: Automotive engine fault dataset."** GitHub repository, 2023. Available at: [https://github.com/leoxthomas/EngineFaultDB](https://github.com/leoxthomas/EngineFaultDB).

---
*This project contributes to the broader, global engineering effort to build smarter, safer, and more efficient automotive systems.*

This README was written with the help of AI.
