
markdown
Copy

# **Healthcare Risk Prediction using SVM**
*A **Semester 1 MSc. Data Analytics** project at **Berlin School of Business & Innovation (BSBI)**, where I applied **machine learning (SVM)** and **data preprocessing techniques** to predict health risks based on patient data. This project directly aligns with my professional experience at **Sakon (GSG)**, where I optimized data workflows and reduced errors by **11%**, and my academic focus on **predictive modeling for real-world applications**.

---

## **📌 Project Overview**
This project analyzes a **healthcare dataset** (with attributes like age, BMI, blood pressure, smoking habits, and exercise frequency) to predict **health risk levels** (Normal, Moderate High, High, Critical) using a **Linear Support Vector Machine (SVM)**. The goal was to build a model that could help medical centers **identify high-risk patients** and recommend preventive measures—mirroring my work at **Sakon**, where I translated complex datasets into actionable insights for **1,200+ customer accounts**.

### **Key Achievements**
✅ **Data Preprocessing**: Cleaned and structured raw healthcare data using **Pandas** and **KNN Imputer** for missing values.
✅ **Exploratory Data Analysis (EDA)**: Generated **pair plots** and **correlation heatmaps** to identify trends (e.g., BMI vs. health risk).
✅ **Model Training**: Implemented a **Linear SVM** with **One-Hot Encoding** for categorical variables and **StandardScaler** for feature scaling.
✅ **Evaluation**: Achieved **67% accuracy** (with room for improvement via class balancing or hyperparameter tuning).
✅ **Actionable Insights**: Identified **BMI, stress levels, and exercise frequency** as key predictors of health risk—aligning with my **MBA in Supply Chain Management**, where I analyzed how operational factors impact outcomes.

---

## **🔧 Technologies & Tools**
   **Tool/Technique**       | **Purpose**                                                                 | **Relevance to My CV**                                  |
 |--------------------------|-----------------------------------------------------------------------------|--------------------------------------------------------|
 | **Python**               | Data cleaning, visualization, and model training (Pandas, Seaborn, Scikit-learn). | Used at **Sakon** for automating data workflows.       |
 | **Jupyter Notebook**      | End-to-end analysis in a single interface.                              | Mirrors my **ETL automation** projects.               |
 | **SVM (Linear Kernel)**  | Classification of health risk levels.                                      | Validates my **predictive modeling** skills.           |
 | **One-Hot Encoding**     | Handling categorical data (e.g., gender, occupation).                     | Applied at **Mercedes-Benz** for time-series analysis. |
 | **KNN Imputer**          | Filling missing values in healthcare data.                                | Reflects my **data quality** focus at Sakon.           |
 | **Pair Plots/Heatmaps**  | Visualizing relationships between variables (e.g., BMI vs. weight).       | Aligns with my **Power BI dashboard** experience.      |

---

## **📂 Project Structure**

healthcare-risk-prediction-svm/
│
├── data/
│   ├── raw/                  # Original dataset (Healthcare.xlsx)
│   └── processed/            # Cleaned data after preprocessing
│
├── notebooks/
│   └── Healthcare_Risk_Prediction.ipynb  # Jupyter Notebook with full analysis
│
├── outputs/
│   ├── pairplot.png          # EDA: Relationships between variables
│   ├── heatmap.png           # Correlation matrix
│   └── confusion_matrix.png  # Model evaluation
│
├── reports/
│   └── Healthcare_Risk_Analysis.pdf  # Full project report (from BSBI)
│
└── README.md
Copy

---

## **🚀 Key Insights & CV Parallels**
### **1. Data Preprocessing = Real-World Data Cleaning**
- **Project**: Handled missing values, duplicates, and outliers in healthcare data.
- **CV Validation**:
  - At **Sakon**, I reduced data errors by **11%** through similar cleaning techniques.
  - Used **KNN Imputer** (a skill I later applied to **automate ETL processes**).

### **2. SVM Model = Predictive Analytics in Action**
- **Project**: Trained a Linear SVM to classify health risks (67% accuracy).
- **CV Validation**:
  - At **Mercedes-Benz**, I built **time-series models (LSTM/XGBoost)** to predict production data—showcasing my ability to **translate algorithms into business insights**.
  - The **feature importance analysis** (e.g., BMI, stress levels) mirrors how I identified **key drivers of customer behavior** at Sakon.

### **3. Visualizations = Storytelling with Data**
- **Project**: Created **pair plots** and **heatmaps** to communicate trends.
- **CV Validation**:
  - Designed **Power BI dashboards** at Sakon to visualize KPIs—proving I can **turn data into decisions**.

### **4. Class Imbalance = Problem-Solving Mindset**
- **Project**: Identified that the model struggled with minority classes ("High"/"Critical" risk).
- **CV Validation**:
  - Proposed solutions like **oversampling** or **algorithm tuning**, reflecting my **proactive approach** to challenges (e.g., optimizing SQL queries at Sakon for **35% faster performance**).

---

## **📊 Model Performance & Lessons**
| **Metric**               | **Score** | **Interpretation**                                                                 | **How I’d Improve It**                          |
|--------------------------|-----------|------------------------------------------------------------------------------------|------------------------------------------------|
| **Accuracy**             | 67%       | Model performs well on majority class ("Moderate High") but misses minority classes. | **Class balancing** (SMOTE) or **hyperparameter tuning**. |
| **Precision (Critical)**  | 0%        | Failed to predict "Critical" risk due to imbalanced data.                          | **Collect more data** or use **ensemble methods**. |
| **Recall (Moderate High)**| 100%      | Perfectly identified all "Moderate High" cases.                                  | **Feature engineering** to improve other classes. |
| **F1-Score (Macro Avg)**  | 0.22      | Low due to poor performance on minority classes.                                  | **Try Random Forest or XGBoost** for better handling. |

**Key Takeaway**:
This project taught me how to **diagnose model biases**—a skill I’ve since applied at work to **audit data pipelines** for fairness and accuracy.

---

## **🔍 How This Validates My CV**
| **CV Claim**                          | **Project Proof**                                                                 |
|---------------------------------------|----------------------------------------------------------------------------------|
| Reduced data errors by **11%** (Sakon) | Applied **KNN Imputer** and **data cleaning** to ensure high-quality inputs.     |
| Optimized ETL by **20%** (Sakon)       | Automated data preprocessing in **Python/Pandas**, mirroring my ETL work.       |
| Built predictive models (Mercedes)    | Trained **SVM** to classify health risks—directly transferable to business cases. |
| Power BI dashboards (Sakon)            | Created **visualizations** (pair plots, heatmaps) to communicate insights.      |
| MBA in Supply Chain Management        | Analyzed **operational factors** (e.g., exercise, stress) impacting health risks. |

---

## **🛠 How to Run This Project**
1. **Prerequisites**:
   - Python 3.8+
   - Libraries: `pandas`, `seaborn`, `matplotlib`, `scikit-learn`
     ```bash
     pip install pandas seaborn matplotlib scikit-learn
     ```

2. **Steps**:
   ```bash
   git clone https://github.com/yourusername/healthcare-risk-prediction-svm.git
   cd healthcare-risk-prediction-svm/notebooks
   jupyter notebook Healthcare_Risk_Prediction.ipynb


Follow the notebook to preprocess data, train the SVM, and evaluate results.

Expected Output:

Pair plot visualizations (e.g., BMI vs. health risk).
Confusion matrix and classification report.
Feature importance rankings.


🌟 Future Enhancements

Deploy as a Web App: Use Flask/Streamlit to let users input their health metrics and get risk predictions.
Expand Dataset: Include more features (e.g., genetic markers) for higher accuracy.
Try Deep Learning: Experiment with neural networks for complex pattern recognition.

📄 License
This project is open-source under the MIT License. Feel free to fork, modify, or build upon it!

---
For a visual walkthrough of the project outputs, check out the OutputSnaps folder—I’ve compiled chronologically arranged snapshots of all key visualizations and results for easy reference! 📸📂
---
