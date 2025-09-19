# 📊 Customer Churn Prediction

## 📝 Descripción
Este proyecto busca predecir qué clientes de una empresa de telecomunicaciones están en riesgo de **cancelar el servicio (churn)**.  
El objetivo es ayudar a la empresa a **anticipar la pérdida de clientes y tomar decisiones estratégicas de retención**, reduciendo pérdidas económicas.

---

## 📂 Dataset
- 📌 [Dataset en Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)  
- Registros: ~7,000 clientes  
- Variables: datos demográficos, servicios contratados, facturación mensual y si el cliente canceló o no.  

---

## ⚙️ Proceso

1. **Preprocesamiento**
   - Revisión de valores nulos y outliers.  
   - Codificación de variables categóricas mediante **One-Hot Encoding (OHE)**.  
   - Escalado de variables numéricas para modelos sensibles (Logistic Regression, SVM, KNN).  

2. **Análisis exploratorio**
   - Distribución de clientes que permanecen vs. churn.  
   - Análisis de variables categóricas y numéricas.  
   - Tablas de frecuencia y visualizaciones descriptivas.  

3. **Modelado**
   - Modelos probados:
     - Logistic Regression ✅ (modelo final)  
     - Gradient Boosting  
     - SVM  
     - Random Forest  
     - Decision Tree  
     - AdaBoost  
     - KNN  
     - Voting Classifier  
   - Validación cruzada y comparación con métricas estándar.  
   - Revisión de **balance de clases** (SMOTE y weighting).  

4. **Evaluación**
   - Métricas utilizadas:  
     - Accuracy  
     - Precision  
     - Recall  
     - F1-Score  
   - Comparación tabular entre modelos.  
   - Matriz de confusión para interpretar errores del modelo final.  

---

## 📊 Resultados
- **Mejor modelo:** Logistic Regression  
- **Métricas obtenidas:**  
  - Accuracy: **0.8071**  
  - Precision: **0.6591**  
  - Recall: **0.5686**  
  - F1-Score: **0.6105**  

📌 Observación: Logistic Regression logró un **equilibrio entre simplicidad e interpretabilidad**, mostrando mejor rendimiento que modelos más complejos.  

---

## 🚀 Recursos
- 📒 [Notebook en Kaggle](https://www.kaggle.com/code/crowwick/customer-churn-prediction-with-logistic-regression/notebook)  
- 📂 [Dataset en Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)  

---

## 🛠️ Tech Stack
- **Python** (Pandas, NumPy, scikit-learn)  
- **Matplotlib, Seaborn** (visualización)  
- **Jupyter Notebook / Kaggle Notebooks**  

---

## 🔮 Próximos pasos (Future Work)
- Incluir métricas adicionales: **ROC-AUC** y curva ROC.  
- Implementar **Streamlit app** para predicciones interactivas.  
- Desplegar un **API con FastAPI o Flask** para integrar el modelo en producción.  
- Probar técnicas avanzadas de **feature engineering** y selección de variables.  
- Explorar modelos más robustos como **XGBoost o LightGBM**.  

---

## 📬 Contacto
👨‍💻 Autor: **Miguel Arnaldo Martín Vásquez León**  
📧 Email: **m.m.a.vasquez.leon@gmail.com**
