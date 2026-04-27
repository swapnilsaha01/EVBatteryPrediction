# EV Battery Intelligence Platform

**Machine Learning platform for real-time EV Li-Ion battery status classification**

An automated system that predicts whether an EV battery is **Fully Charged**, **Partially Charged**, or **Needs Charging** using 6 sensor readings. Built as a group project at Madras School of Economics (2026).

## Key Results
- **Model**: K-Nearest Neighbors (KNN, k=9)
- **Test Accuracy**: **91.91%**
- Native **confidence scores** for every prediction
- Automated **technician dispatch system** (routes low-confidence cases to humans)
- Only **11 errors** on the 136-sample test set

## Dataset
- 452 labeled Li-Ion battery sensor readings
- Features (all normalized [0,1]):
  - Voltage
  - Current
  - Temperature
  - AverageVoltage
  - AverageCurrent
  - SOC (State of Charge)

