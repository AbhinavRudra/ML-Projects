# Network Intrusion Detection System (NIDS)

## Project Overview
This project leverages Machine Learning (Random Forest) and Deep Learning (LSTM) to detect anomalies in network traffic. Using the NSL-KDD dataset, the system classifies activity as either "Normal" or "Attack."

## Key Features
- **Data Processing:** Handling categorical features via One-Hot Encoding and normalization using StandardScaler.
- **Models Implemented:**
  - Random Forest Classifier (Class Weight Balanced)
  - LSTM (Long Short-Term Memory) Neural Network
- **Performance:** The LSTM model achieved an F1-Score of 0.79 and an accuracy of ~80%.

## Tech Stack
- Python 3.12
- TensorFlow / Keras
- Scikit-Learn
- Pandas / NumPy
- Matplotlib / Seaborn

## Performance Results
The models were evaluated on the KDDTest+ dataset. The LSTM model demonstrated superior capability in distinguishing complex attack patterns.

| Metric | Random Forest | LSTM (Deep Learning) |
| :--- | :--- | :--- |
| **Accuracy** | 78% | **79%** |
| **F1-Score** | 0.78 | **0.79** |
| **AUC Score**| 0.80 | **0.82** |

*Key Insight: The LSTM model achieved a higher Area Under Curve (0.82), indicating a better trade-off between True Positive Rate and False Positive Rate compared to the Random Forest model.*

![AUC Curve](images/auc.png)
