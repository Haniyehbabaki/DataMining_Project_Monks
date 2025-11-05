# Data Mining Project – MONK’s Problems

##📊 Dataset Information
The **MONK’s Problems** dataset is a classical benchmark in machine learning used to test classification algorithms on **categorical (symbolic)** data.  
**Dataset Source:** [UCI Machine Learning Repository – MONK’s Problems](https://archive.ics.uci.edu/dataset/70/monk+s+problems)
-This project was implemented using the following Python libraries:pandas,numpy,scikit-learn,matplotlib,seaborn

---
### 🧾 **Phase 1 – Dataset Selection**
- Selected dataset: **MONK’s Problems**
- The dataset link and name were uploaded and registered.
- Data type confirmed as **categorical** (no text, image, audio, or video).
---
### 📋 **Phase 2 – Data Understanding and Preprocessing**
- Created a table of **attribute names and types**.  
- Used `describe()` to generate a **statistical summary** of the dataset.  
- For numeric data (if any), performed:
  - **Correlation matrix** analysis  
  - **Box Plot** visualization and **outlier removal**  
  - Applied **PCA (Principal Component Analysis)** for dimensionality reduction.  
- For categorical data, performed **Chi-squared test** to check attribute relationships.
---

### 🌳 **Phase 3 – Classification**
- Implemented and compared three algorithms:
  1. **Decision Tree**
  2. **Random Forest**
  3. **Rule-Based Classifier**
- Used **3-Fold Cross Validation** for performance evaluation.  
- Calculated metrics:  
  **Accuracy, Precision, Recall, and F1-score (per class)**  
- Reported and compared **hyperparameters** for each model.
---

### 🔹 **Phase 4 – Clustering**
- Applied **K-Means** clustering algorithm.  
- Determined optimal number of clusters using the **Elbow Method**.  
- Calculated **Dunn Index** to evaluate cluster quality.
---
## 🧑‍💻 Author
**Haniyeh Babaki**  
Data Mining Project – 2025  
University of Damghan  
