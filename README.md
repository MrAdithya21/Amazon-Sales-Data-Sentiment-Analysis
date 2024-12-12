# 🛒 **Customer Sentiment Analysis and Insights**

![Python](https://img.shields.io/badge/Python-3.8%2B-blue) ![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange) ![Visualization](https://img.shields.io/badge/Data%20Visualization-Seaborn%20%7C%20Matplotlib-green)

<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/a/a9/Amazon_logo.svg" alt="Amazon Logo" width="300"/>
</p>

This project analyzes customer reviews from Amazon to uncover trends in sentiment, review patterns, and ratings. Using Python and statistical methods, the analysis provides actionable insights into customer behavior, product performance, and potential areas for improvement.

---

## 📜 **Project Overview**

### **Objectives**
- Perform **sentiment analysis** on customer reviews to classify them as positive, neutral, or negative.
- Explore relationships between customer **ratings** and variables like discount percentages.
- Use **statistical tests** (Chi-Square, ANOVA, Pearson Correlation, T-Test) to validate findings.
- Visualize key insights through word clouds, scatter plots, and boxplots.

### **Key Findings**
1. **Positive reviews** are generally longer than negative ones, reflecting more detailed praise from satisfied customers.
2. A weak **negative correlation** exists between discount percentages and customer ratings, suggesting higher discounts may raise customer expectations.
3. **Negative reviews** often highlight detailed product issues, while positive reviews tend to be concise and focus on overall satisfaction.
4. Statistical tests confirm significant differences in review lengths and average ratings across sentiment categories.

---

## 🌟 **Highlights of the Analysis**

### **1. Sentiment Distribution**
- The majority of reviews are **positive**, reflecting high customer satisfaction.
- Categories with mixed sentiments are flagged for further analysis.

![image](https://github.com/user-attachments/assets/8cba60f8-a611-40ea-ac79-ac2a342c2551)

---

### **2. Word Clouds**
Visual representations of frequent words in each sentiment category:

#### 🌞 **Positive Sentiments**:
Keywords like "good," "quality," and "value" dominate.

![image](https://github.com/user-attachments/assets/c6809390-4d3c-43aa-b649-e7169b34fdbd)

#### 😐 **Neutral Sentiments**:
Neutral reviews are brief, with terms like "okay" and "size."

![image](https://github.com/user-attachments/assets/3427f5c9-fd0d-44dc-aae1-1b043e39cf27)

#### 😠 **Negative Sentiments**:
Complaints focus on issues like "working," "poor," and "bad."

![image](https://github.com/user-attachments/assets/226e1979-ef47-4c40-b089-44cd1b94e044)

---

### **3. Statistical Analysis**
- **Chi-Square Test**: No significant difference in sentiment distribution across categories.
- **ANOVA**: Significant differences in average ratings across sentiments.
- **T-Test**: Negative reviews are significantly longer than positive reviews.
- **Pearson Correlation**: A weak but significant negative correlation between discount percentages and ratings.

---

## 📊 **Visualizations**

### **Scatter Plot: Discount Percentage vs Rating**
A weak negative correlation is observed, with higher discounts sometimes leading to slightly lower ratings.

![image](https://github.com/user-attachments/assets/69eb9964-337d-4c32-b397-1d85a0e78254)

---

### **Boxplot: Review Length by Sentiment**
Positive reviews show higher variability and length compared to negative reviews.

![image](https://github.com/user-attachments/assets/49111c60-823b-4f01-9bb2-4dc6aacd8828)

---

## 🚀 **How to Use**

### **1. Run the Notebook**
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repo.git
