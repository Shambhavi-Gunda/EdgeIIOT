# Intrusion Detection in Smart IoT Environments

## Overview
This project presents an online intrusion detection framework for IoT and edge computing environments. 
It tackles class imbalance, high dimensionality, and dynamic data streams using data balancing, feature optimization, and online machine learning models.

## Key Features
- SMOTE for handling class imbalance
- Feature selection using metaheuristic algorithms: GWO, HHO, DA
- Online machine learning models: ARF, Hoeffding Tree, HAT, EFDT, AMF, SRP
- Model ranking using UCB-Tuned algorithm

## Datasets
- Farm-Flow: Smart agriculture IoT intrusion dataset  
- Edge-IIoT: Industrial IoT cyber-attack dataset  

## Best Models
Farm-Flow:
- Binary: Adaptive Random Forest (ARF)
- Multiclass: Adaptive Random Forest (ARF)

Edge-IIoT:
- Binary: Adaptive Random Forest (ARF)
- Multiclass: Hoeffding Tree

## Tools & Technologies
Python, River, Scikit-learn, Imbalanced-learn, NumPy, Pandas, Matplotlib, Jupyter Notebook

## Future Work
Hybrid ensemble models, Explainable AI integration, lightweight deployment for IoT edge devices.

## Reference
Based on the research paper: *Intrusion Detection in Smart Environments Using Online Machine Learning Models*
