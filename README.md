# 📊 Customer Churn Prediction

## 📝 Descripción
Este proyecto busca predecir qué clientes de una empresa de telecomunicaciones están en riesgo de **cancelar el servicio (churn)**.  
La predicción de churn permite a las empresas **anticiparse y tomar acciones de retención**, reduciendo pérdidas económicas.

---

## 📂 Dataset
- Fuente: [Kaggle – Telco Customer Churn](https://www.kaggle.com/blastchar/telco-customer-churn)  
- Registros: ~7,000 clientes  
- Variables: datos demográficos, servicios contratados, facturación mensual y si el cliente canceló o no.

---

## ⚙️ Proceso
1. **Exploración y limpieza de datos**
   - Manejo de valores nulos y outliers.
   - Codificación de variables categóricas.
   - Normalización de variables numéricas.

2. **Feature Engineering**
   - Creación de variable "tenure groups" (antigüedad del cliente).
   - Variables binarias (servicio de internet, contrato mensual, etc.).

3. **Modelado**
   - Modelos probados:
     - Logistic Regression
     - Random Forest
     - XGBoost
   - Validación cruzada (5 folds).
   - Balanceo de clases con **SMOTE**.

4. **Evaluación**
   - Métricas: Accuracy, Precision, Recall, F1-score, ROC-AUC.
   - Curva ROC para comparar modelos.

---

## 📊 Resultados
- **Modelo final**: XGBoost  
- **ROC-AUC**: 0.85  
- **F1-score**: 0.79  
- Variables más importantes:
  - Tipo de contrato (mensual → más riesgo de churn).
  - Antigüedad (clientes nuevos → más riesgo).
  - Facturación mensual.

---

## 🚀 Demo
- 📒 [Notebook interactivo](notebook.ipynb)  
- 🌐 [Demo en Streamlit](https://tu-streamlit-app-url)  
- ⚡ [API con FastAPI (ejemplo)](https://github.com/tu-usuario/ml-portfolio/projects/01-customer-churn/app.py)  

---

## 🛠️ Tech Stack
- Python (Pandas, NumPy, scikit-learn, XGBoost)  
- Matplotlib, Seaborn (visualización)  
- Streamlit (demo interactiva)  
- FastAPI + Docker (API de predicciones)

---

## 📸 Capturas
### Curva ROC
![ROC Curve](images/roc_curve.png)

### Demo en Streamlit
![Demo App](images/demo_streamlit.png)

---

## 📬 Contacto
👨‍💻 Autor: [Tu Nombre](https://www.linkedin.com/in/tu-usuario)  
📧 Email: tu-email@ejemplo.com
