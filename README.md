# Machine Learning-Driven Analysis of Low-Carbon Technology Trade and Its Economic Impact in the USA

## Project Overview:
This project focuses on analyzing the trade data of low-carbon technologies in the United States, leveraging **machine learning** to uncover trends and predict economic impacts. By applying various classification models, including **Logistic Regression**, **Support Vector Machine (SVM)**, and **K-Nearest Neighbors (KNN)**, the project explores how trade flows of low-carbon technologies relate to economic factors like market demand and international trade policies.

## Key Models Used:
1. **Logistic Regression**
2. **Support Vector Machine (SVM)**
3. **K-Nearest Neighbors (KNN)**

Each model was evaluated using accuracy, precision, recall, and F1-score. Here's a summary of their performance:

## Model Performance:

### **1. Logistic Regression**
- **Accuracy**: 0.8521
- **Classification Report**:
  - **Precision**: 0.85 (class 0), 0.84 (class 1), 0.87 (class 2)
  - **Recall**: 1.00 (class 0), 0.91 (class 1), 0.65 (class 2)
  - **F1-Score**: 0.92 (class 0), 0.87 (class 1), 0.74 (class 2)
- **Cross-validated Accuracy**: 0.7849

Logistic Regression performed well with an overall accuracy of **85.21%**, with notable precision and recall in class 0, though recall for class 2 (with lower economic impact) could be improved.

### **2. Support Vector Machine (SVM)**
- **Accuracy**: 0.9954
- **Classification Report**:
  - **Precision**: 1.00 (class 0), 1.00 (class 1), 0.99 (class 2)
  - **Recall**: 1.00 (class 0), 0.99 (class 1), 1.00 (class 2)
  - **F1-Score**: 1.00 (class 0), 1.00 (class 1), 0.99 (class 2)

SVM performed exceptionally well, achieving near-perfect **99.54%** accuracy with consistent performance across all classes, making it the top-performing model.

### **3. K-Nearest Neighbors (KNN)**
- **Accuracy**: 0.9885
- **Classification Report**:
  - **Precision**: 0.98 (class 0), 0.99 (class 1), 0.99 (class 2)
  - **Recall**: 0.99 (class 0), 0.98 (class 1), 1.00 (class 2)
  - **F1-Score**: 0.99 (class 0), 0.98 (class 1), 1.00 (class 2)

KNN also delivered strong results with an accuracy of **98.85%**, performing very well across all metrics, especially for class 2.

## Business Impact:

The insights generated from this analysis can significantly impact businesses, policymakers, and environmental organizations by providing a data-driven foundation for making informed decisions:

1. **Trade Policy Development**: Helps shape policies that encourage low-carbon technology trade, which can foster both economic and environmental sustainability.
2. **Investment Decisions**: Assists businesses in identifying market opportunities in low-carbon sectors, offering strategic insights into potential high-growth regions.
3. **Economic Planning**: Supports national and regional economic plans focused on sustainable trade and technologies by forecasting trends in low-carbon technology adoption.
4. **Sustainability Reporting**: Provides valuable metrics for organizations looking to meet sustainability goals, offering data-driven insights into the impact of low-carbon technologies on trade.
5. **Strategic Market Expansion**: Aids businesses in identifying markets with high trade potential for low-carbon technologies, facilitating effective market entry strategies.

## Conclusion:
This project highlights the power of **machine learning** in the field of **sustainable trade** and **economic analysis**. By combining **classification models** with economic trade data, the analysis provides actionable insights that can drive the adoption of low-carbon technologies and contribute to global sustainability efforts. The exceptional performance of **SVM** and **KNN** demonstrates the potential of predictive models in driving policy and business decisions that positively impact both the environment and the economy.
