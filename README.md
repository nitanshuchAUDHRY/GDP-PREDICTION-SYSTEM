# 🇰🇪 Kenya GDP Prediction Using LSTM

This project uses Long Short-Term Memory (LSTM), a type of recurrent neural network (RNN), to predict Kenya’s GDP based on historical trends. The model is well-suited for time series data and helps forecast future economic performance.

---

## 🎯 Objective

To build an LSTM-based deep learning model to accurately forecast Kenya’s GDP using past data.

---



## 🧰 Tools & Technologies

- Python
- Pandas, NumPy (Data processing)
- Matplotlib, Seaborn (Visualization)
- Scikit-learn (Preprocessing & Evaluation)
- TensorFlow / Keras (LSTM Modeling)
- Jupyter Notebook

---

## 🧠 Model: LSTM (Long Short-Term Memory)

LSTM networks are used because:
- They are effective for time series prediction
- They retain long-term dependencies
- They avoid vanishing gradient issues

---

## 🛠️ Workflow

1. **Data Loading & Cleaning**  
   Load historical GDP data for Kenya and preprocess it.

2. **Normalization**  
   Scaled GDP values using MinMaxScaler for better model performance.

3. **Data Framing**  
   Reshaped data into sequences of time steps for LSTM input.

4. **Model Building**  
   Constructed a sequential LSTM model with:
   - Input Layer
   - One or more LSTM layers
   - Dense output layer

5. **Training & Evaluation**  
   Trained model on historical data and evaluated using RMSE, MAE.

6. **Prediction**  
   Forecasted Kenya’s GDP for upcoming years.

---

## 📊 Results

- **Training Loss:** ~ (example) 0.0023  
- **Test RMSE:** ~ (example) $1.5 Billion  
- **Model Performance:** Captured GDP trend effectively.

---
