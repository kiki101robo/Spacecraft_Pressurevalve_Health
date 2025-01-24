# Spacecraft Pressure Valve Health

View the full project report here: [Industrial AI Final Report.pdf](https://github.com/user-attachments/files/18400934/Industrial.AI.Final.Report.pdf)

## Visualizations

### Schematic Diagram of the Valve System
![Schematic Diagram](https://github.com/user-attachments/assets/0fa931c0-4d6b-4ee3-8cd9-e81f527537e9)

### Pressure Profile Over Time
![Pressure Profile](https://github.com/user-attachments/assets/86f3bb31-bfa3-43e3-aa20-d980be7f5ed8)

### Regime Separation
![Regime Separation](https://github.com/user-attachments/assets/b0847870-9943-4aaa-b4dd-2cd41562eef2)

### Classification of Valves
![Valve Classification](https://github.com/user-attachments/assets/c3a0d493-528f-4a81-87b6-c36b6303813d)

### Valve Opening Ratio Prediction
![Valve Opening Ratio](https://github.com/user-attachments/assets/f8b38f34-ee83-4e6d-9144-d831e68eef7a)

### Valve Opening Prediction vs True Values
![Valve Opening Prediction](https://github.com/user-attachments/assets/06d66707-1af6-411e-85a7-c7821dc027e1)

### Confusion Matrix of Classification
![Confusion Matrix](https://github.com/user-attachments/assets/5609eaba-3fb5-493c-bb20-4550db996a1a)

# Vibration Data Analysis with DTW and SVM

## Project Overview
This project analyzes vibration data using Dynamic Time Warping (DTW) and Support Vector Machines (SVM) to classify mechanical states of equipment, focusing on conditions categorized as Healthy, Unbalanced Level 1, and Unbalanced Level 2.

## Features
- **Dynamic Time Warping (DTW)**: Applied to measure similarities between time series data.
- **Support Vector Machines (SVM)**: Used for classifying mechanical states from vibration data.
- **Data Preprocessing**: Includes handling and preparing time series data from CSV files.
- **Feature Extraction**: Extracts meaningful features for the SVM classifier.
- **Visualization**: Provides training and test result visualizations for analysis.

## Getting Started

### Prerequisites
- Python 3.8+
- Required libraries: NumPy, Pandas, SciPy, Matplotlib, Scikit-learn, fastdtw

### Installation
Clone the repository and install the required dependencies:
```bash
git clone https://github.com/your-repository/vibration-analysis-dtw-svm.git
cd vibration-analysis-dtw-svm
pip install numpy pandas scipy matplotlib scikit-learn fastdtw
