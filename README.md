# 📊 Outlier Detection and Treatment in Housing Data

This project demonstrates how to detect and treat outliers using both **statistical techniques** (IQR method and capping) and **machine learning-based methods** (Isolation Forest) in a real-world dataset. The goal is to clean the dataset and improve the quality of data for downstream analysis or modeling.

---

## 📌 Project Objectives

- Load and explore a real-world dataset.
- Detect outliers using the **Interquartile Range (IQR)** method.
- Treat outliers using **capping techniques**.
- Apply **Isolation Forest** to detect anomalies with machine learning.
- Visualize the data before and after outlier treatment.

---

## 🧠 Dataset Used

- **California Housing Dataset** (from `sklearn.datasets`)
- Features include: `MedInc`, `HouseAge`, `AveRooms`, `AveOccup`, etc.
- Target: `MedianHouseValue`

---

## 🛠️ Technologies & Libraries

- Python
- Google Colab
- Pandas & NumPy
- Matplotlib & Seaborn (for visualization)
- Scikit-learn
- PyOD (for ML-based anomaly detection)

---

## 🔍 Outlier Detection Techniques

### 1. **Statistical Method**
- **IQR (Interquartile Range)**
- Detects outliers that lie outside 1.5 * IQR from Q1 and Q3.

### 2. **Outlier Treatment**
- **Capping** extreme values to upper and lower bounds (no row deletion).

### 3. **Machine Learning Method**
- **Isolation Forest**: An unsupervised anomaly detection algorithm.

---

## 📈 Visualizations

- Boxplots to identify distribution and detect outliers.
- Comparison of datasets before and after capping.

---

## 📁 File Structure

