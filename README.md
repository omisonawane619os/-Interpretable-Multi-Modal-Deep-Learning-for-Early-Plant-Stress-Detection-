# 🌱 Interpretable Multi-Modal Deep Learning for Early Plant Stress Detection

## 📌 Overview
This project focuses on early detection of plant stress using multi-modal IoT sensor data and deep learning models. It combines environmental, soil, and system-level data to identify stress conditions in plants before visible symptoms appear.

The goal is to build an interpretable AI system that helps improve crop health monitoring and supports smart agriculture.

---

## 🎯 Objectives
- Detect plant stress at an early stage  
- Use time-series IoT sensor data for prediction  
- Build a hybrid Transformer + LSTM model  
- Provide interpretable results using explainable AI techniques  
- Improve decision-making in precision agriculture  

---

## 📊 Input Features

### 🌤️ Environmental Data
- Air Temperature  
- Humidity  
- Light Intensity (Lux)  

### 🌱 Soil Data
- Soil Moisture  
- Soil pH  
- Soil Temperature  

### 💧 Water/Nutrient Data
- Total Dissolved Solids (TDS)  

### 🔋 System Data
- Solar Panel Battery Voltage  

### ⏱️ Temporal Data
- Time-of-day encoding  

---

## 🧠 Model Architecture
- LSTM (Long Short-Term Memory) → captures time-based patterns  
- Transformer → captures long-range dependencies using attention  
- Fusion Layer → combines multi-modal sensor data  

---

## 🎯 Output Classes
- Healthy  
- Hydraulic Stress  
- Nutrient/Chemical Stress  
- High Disease Risk  

---

## 📈 Evaluation Metrics
- F1-Score  
- Precision  
- Recall  
- Precision-Recall Curve  
- Inference Latency  
- Interpretability (SHAP / Attention Maps)  

---

## 🛠️ Tech Stack
- Python  
- PyTorch  
- Pandas & NumPy  
- Scikit-learn  
- SHAP & Captum  
- Seaborn & Plotly  

---

## 🔄 Workflow
1. Data collection from IoT sensors  
2. Data preprocessing and normalization  
3. Time-series window creation  
4. Model training (Transformer + LSTM)  
5. Model evaluation  
6. Interpretability analysis  
7. Visualization of results  

---

## 🚀 Future Improvements
- Real-time deployment using edge devices  
- Integration with mobile/web dashboard  
- Advanced anomaly detection  
- Larger datasets  

---

## 📚 Applications
- Smart agriculture  
- Precision farming  
- Crop monitoring  
- Early disease detection  

---

## 🤝 Contribution
Contributions are welcome! Feel free to fork the repository and submit a pull request.

---

## 📄 License
This project is for academic and research purposes.

---

## 👤 Author
Omkar Jaywant Sonawane  
Master’s Thesis Project  
