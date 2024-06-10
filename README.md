echo "# 📊 Advanced Customer Segmentation

This project uses k-Means clustering and Logistic Regression to perform customer segmentation based on shopping data. The goal is to identify distinct customer groups to enhance targeted marketing strategies.

---

## 🎯 Project Overview

### Goal
Implement, train, and evaluate machine learning models on customer data to achieve accurate predictions and determine the best-performing model.

---

## 🛠️ Steps and Implementation

#### 1. Download and Load Dataset
- **Libraries Used:**
  - `pandas` for data manipulation and analysis
  - `numpy` for numerical operations
  - `scikit-learn` for machine learning models and preprocessing
  - `matplotlib.pyplot` and `seaborn` for data visualization

#### 2. Visualize Data Distribution
- **Graphs:**
  - ![Age Distribution](age_distribution.png)
  - ![Income vs. Spending Score](income_vs_spending.png)

#### 3. Data Preparation and Scaling
- Selected necessary columns (age, annual income, spending score)
- Scaled data using `StandardScaler`

#### 4. Determine Optimal Number of Clusters
- Used Silhouette Score to find optimal clusters (2-10)
- **Graph:** ![Silhouette Score Plot](silhouette_scores.png)

#### 5. k-Means Clustering
- Applied k-Means with 6 clusters to scaled data

#### 6. Logistic Regression and Performance Metrics
- 5-fold cross-validation with Logistic Regression
- **Results:**
  - Accuracy: 99.5%

---

## 📊 Results

### Visuals and Performance
- Silhouette score plot indicates 6 optimal clusters
- Logistic Regression model validated clusters with high performance (99.5% accuracy)

### Conclusion
Combining k-Means clustering and Logistic Regression effectively segmented customers, achieving high accuracy and well-defined clusters. This approach is valuable for targeted marketing strategies.

---

## 🛠️ Usage

1. Clone the repository:
   \`\`\`bash
   git clone https://github.com/MarawanEldeib/Advanced_Customer_Segmentation.git
   \`\`\`

2. Navigate to the project directory:
   \`\`\`bash
   cd Advanced_Customer_Segmentation
   \`\`\`

3. Run the Jupyter Notebook:
   \`\`\`bash
   jupyter notebook Assignment_1_Clustering.ipynb
   \`\`\`

---

## 📂 File Structure

\`\`\`bash
Advanced-Customer-Segmentation/
├── age_distribution.png
├── income_vs_spending.png
├── silhouette_scores.png
├── performance_metrics.txt
├── README.md
├── Assignment_1_Clustering.ipynb
├── clustered_data.csv
\`\`\`

---

## 🛠️ Libraries

To replicate this project, ensure you have the following libraries installed:

\`\`\`bash
pip install pandas numpy scikit-learn matplotlib seaborn
\`\`\`" > README.md
