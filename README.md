# **Customer Sentiment Analysis and Insights**

This project analyzes customer reviews from Amazon to uncover trends in sentiment, review patterns, and ratings. Using Python and statistical methods, the analysis provides actionable insights into customer behavior, product performance, and potential areas for improvement.

---

## **Project Overview**

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

## **Highlights of the Analysis**

### **1. Sentiment Distribution**
- The majority of reviews are **positive**, reflecting high customer satisfaction.
- Categories with mixed sentiments are flagged for further analysis.

![image](https://github.com/user-attachments/assets/5a26baa6-7dfd-4507-bcb3-6199e43f23b2)


---

### **2. Word Clouds**
- **Positive Sentiments**: Keywords like "good," "quality," and "value" dominate.
- **Negative Sentiments**: Complaints focus on issues like "working," "poor," and "bad."
- **Neutral Sentiments**: Neutral reviews are brief, with terms like "okay" and "size."

#### Positive Sentiment Word Cloud:
![image](https://github.com/user-attachments/assets/5f54cc3b-573d-414a-8518-8248d0be4afe)

#### Neutral Sentiment Word Cloud:
![image](https://github.com/user-attachments/assets/21f17df5-3907-4027-876d-e287a31bc7c7)

#### Negative Sentiment Word Cloud:
![image](https://github.com/user-attachments/assets/2666eb59-57ff-4404-bc04-88fc209cab1e)

---

### **3. Statistical Analysis**
- **Chi-Square Test**: No significant difference in sentiment distribution across categories.
- **ANOVA**: Significant differences in average ratings across sentiments.
- **T-Test**: Negative reviews are significantly longer than positive reviews.
- **Pearson Correlation**: A weak but significant negative correlation between discount percentages and ratings.

---

## **Visualizations**

### **Scatter Plot: Discount Percentage vs Rating**
- A weak negative correlation is observed, with higher discounts sometimes leading to slightly lower ratings.

![image](https://github.com/user-attachments/assets/6f2e09cf-ce1b-4ad6-9171-f4e29af54677)

---

### **Boxplot: Review Length by Sentiment**
- Positive reviews show higher variability and length compared to negative reviews.

![image](https://github.com/user-attachments/assets/59f601ab-79c4-43df-b5c1-7729c20f688c)

---

## **How to Use**

### **1. Run the Notebook**
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repo.git
