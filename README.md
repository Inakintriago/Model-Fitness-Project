# 💪 Model Fitness: Customer Retention Strategy

## 📊 Project Description

Model Fitness is a gym chain aiming to improve its customer retention strategy using data analysis. One of the biggest challenges for gyms is **customer churn**. This project aims to predict the likelihood of customer cancellation, identify patterns, and suggest measures to increase customer loyalty.

## 🛠️ Tools Used

- **Python**: Data analysis and predictive modeling.
- **Pandas** and **NumPy**: Data cleaning and manipulation.
- **Scikit-learn**: Classification and clustering modeling.
- **Matplotlib** and **Seaborn**: Visualization of behavioral patterns.
- **SciPy**: Statistical analysis.
- **Jupyter Notebook**: Documentation of the entire workflow.

## 🔄 Workflow

### 🔍 1. Data Exploration

- **Missing Data**: Identification and handling of null values in the columns.
- **Descriptive Analysis**: Calculation of key statistics such as averages, standard deviations, and group analysis by cancellation status.
- **Visualization**: Creation of histograms and bar charts to compare the characteristics of customers who canceled with those who stayed.
- **Correlation Matrix**: Identification of relationships between variables and their impact on cancellation.

### 🤖 2. Predictive Modeling

- **Trained Models**: Implementation of two classification models to predict the likelihood of cancellation:
  - **Logistic Regression**: To model the probability of a customer canceling.
  - **Random Forest**: To capture complex interactions between variables.
- **Model Evaluation**: Comparison of accuracy, precision, and recall to determine which model predicts customer cancellation best.

### 🧑‍🤝‍🧑 3. Customer Segmentation

- **Clustering**: Use of the K-means algorithm to segment users into clusters based on their characteristics.
- **Cluster Analysis**: Observation of cancellation rates and key characteristics in each group.
- **Dendrogram**: Visual analysis to determine the optimal number of clusters.

## 📈 Conclusions and Recommendations

### 🚨 1. Groups with High Cancellation Rates

- Clusters 0, 3, and 4 show significantly high cancellation rates.
- **Recommendation**: Apply targeted loyalty campaigns, such as discounts or access to exclusive classes, to reduce churn in these groups.

### 🏋️‍♀️ 2. Participation in Group Activities

- Users who participate in group classes are less likely to cancel their membership.
- **Recommendation**: Encourage participation in group classes through reward programs and discounts for those who attend regularly.

### 🚶‍♀️ 3. Visit Frequency

- Low visit frequency is a key indicator of imminent cancellation.
- **Recommendation**: Implement activity alerts to contact customers who haven't visited the gym in over a week, offering promotions to reactivate their attendance.

### ❤️ 4. Loyal Customers

- Users with longer membership durations tend to cancel less, but they can still benefit from personalized attention.
- **Recommendation**: Develop a reward program for the most loyal customers, offering benefits like massages or exclusive classes.

## 🎯 Overall Conclusion

Through customer segmentation and the analysis of factors influencing cancellation, Model Fitness can optimize its retention strategy. By implementing data-driven, personalized measures, the gym can significantly reduce its cancellation rate and improve overall user satisfaction.
