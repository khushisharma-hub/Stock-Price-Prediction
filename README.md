# 📈 Stock Price Prediction using LSTM

**Domain**: Machine Learning & AI  
**Internship Program**: Tamizhan Skills Rise  
**Intern ID**: TS-RISE-MLAI-2514  
**Author**: Khushi Sharma  
**GitHub Repository**: [Stock Price Prediction](https://github.com/khushisharma-hub/Stock-Price-Prediction)  
**Notebook**: [Stock_Price_Prediction_with_LSTM.ipynb](https://github.com/khushisharma-hub/Stock-Price-Prediction/blob/main/Stock_Price_Prediction_with_LSTM.ipynb)  
**Demo Video**: [Watch Here](https://drive.google.com/file/d/1Cxz1zSJqlpX4P00f4TATpQEW3cf-BrnG/view?usp=sharing)

---

## 📚 Table of Contents

1. [🧩 Project Overview](#-project-overview)  
2. [🎯 Objective](#-objective)  
3. [🛠️ Tools & Technologies](#️-tools--technologies)  
4. [📊 Dataset](#-dataset)  
5. [🔄 Project Workflow](#-project-workflow)  
6. [🧪 Model Evaluation](#-model-evaluation)  
7. [🎥 Demo Video](#-demo-video)  
8. [✅ Conclusion](#-conclusion)  
9. [🔗 Important Links](#-important-links)

---

## 🧩 Project Overview

Stock market trends can be unpredictable, but with the right AI tools, we can uncover hidden patterns. This project uses **LSTM (Long Short-Term Memory)** neural networks to forecast stock prices based on historical trends, demonstrating a real-world application of time-series modeling.

---

## 🎯 Objective

- Predict future stock prices using past data.
- Train an LSTM model on historical `Close` prices.
- Visualize actual vs predicted prices.
- Showcase AI-driven financial forecasting for smart investment decisions.

---

## 🛠️ Tools & Technologies

- **Python** (Google Colab)
- **TensorFlow / Keras**
- **Pandas**, **NumPy**
- **Matplotlib**, **Seaborn**
- **Scikit-learn**
- **yfinance** for real-time stock data

---

## 📊 Dataset

- **Source**: Yahoo Finance via `yfinance`
- **Stock Used**: Apple Inc. (`AAPL`)
- **Features**: `Close` price
- **Date Range**: Typically past 5–10 years (can be customized)

---

## 🔄 Project Workflow

1. **Data Collection**  
   - Used `yfinance` to download Apple stock prices.

2. **Data Preprocessing**  
   - Normalized closing prices using `MinMaxScaler`.
   - Created sequential data (60 time steps).

3. **Model Architecture**  
   - LSTM layers for time dependency.
   - Dropout to prevent overfitting.

4. **Training & Validation**  
   - Model trained for multiple epochs.
   - Loss monitored using MSE.

5. **Prediction**  
   - Compared predicted vs actual prices using graphs.

---

## 🧪 Model Evaluation

- **Loss Function**: Mean Squared Error (MSE)
- **Performance**: Visual evaluation through line plots
- **Result**: Model is able to forecast future price patterns fairly accurately.

---

## 🎥 Demo Video

👉 **Watch Full Demo**: [https://drive.google.com/file/d/1Cxz1zSJqlpX4P00f4TATpQEW3cf-BrnG/view?usp=sharing](https://drive.google.com/file/d/1Cxz1zSJqlpX4P00f4TATpQEW3cf-BrnG/view?usp=sharing)

---

## ✅ Conclusion

This LSTM-based model successfully demonstrates the capability of deep learning in analyzing financial time-series data. While it's not meant for real-time trading, the project lays the foundation for future development of intelligent investment systems.

---

## 🔗 Important Links

- 🔗 **GitHub Repository**: [https://github.com/khushisharma-hub/Stock-Price-Prediction](https://github.com/khushisharma-hub/Stock-Price-Prediction)  
- 📒 **Colab Notebook**: [Stock_Price_Prediction_with_LSTM.ipynb](https://github.com/khushisharma-hub/Stock-Price-Prediction/blob/main/Stock_Price_Prediction_with_LSTM.ipynb)  
- 🎥 **Demo Video**: [https://drive.google.com/file/d/1Cxz1zSJqlpX4P00f4TATpQEW3cf-BrnG/view?usp=sharing](https://drive.google.com/file/d/1Cxz1zSJqlpX4P00f4TATpQEW3cf-BrnG/view?usp=sharing)

---

> 📌 *Created with passion during the Tamizhan Skills Rise Internship Program*
