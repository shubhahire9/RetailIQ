# 🛒 RetailIQ – Customer Segmentation Using K-Means

## 📌 Overview

RetailIQ is a machine learning project that segments customers based on purchasing behavior, demographics, website activity, and marketing campaign responses.

The project uses data preprocessing, EDA, feature engineering, PCA, and K-Means clustering to identify meaningful customer groups and generate actionable marketing insights.

---

## 🎯 Objectives

* Clean and preprocess customer transaction data.
* Analyze customer behavior using EDA.
* Engineer meaningful customer features.
* Apply PCA for dimensionality reduction.
* Segment customers using K-Means clustering.
* Evaluate clusters using the Elbow Method and Silhouette Score.
* Generate personalized marketing strategies.

---

## 📊 Dataset

* **Original records:** 2,240
* **Records used after preprocessing:** 2,236
* **Data includes:** demographics, product spending, purchase behavior, website activity, recency, and campaign responses.

---

## 🔄 Workflow

```text
Data Cleaning → EDA → Feature Engineering → Encoding
→ Scaling → PCA → K-Means Clustering
→ Evaluation → Cluster Profiling → Business Insights
```

---

## 🛠️ Technologies

Python • Pandas • NumPy • Matplotlib • Seaborn • Scikit-learn • Jupyter Notebook

---

## 👥 Customer Segments

- **Cluster 0 – Value-Seeking Families:** Low income (approx $39.7K), more children, high web browsing, and low spending (approx $222).  
  **Strategy:** Discounts and family coupons.

- **Cluster 1 – Premium Loyal Customers:** High income (approx $72.8K), fewer children, and the highest spending (~$1,236).  
  **Strategy:** Loyalty programs and premium products.

- **Cluster 2 – Digital Budget Browsers:** Low income (approx $37K), lowest spending (approx $166), but highest website visits (approx 6.66/month).  
  **Strategy:** Clearance sales and digital deals.

- **Cluster 3 – High-Value Campaign Responders:** High income (approx $70.7K), strong spending (approx $1,190), and highest campaign response (approx 32%).  
  **Strategy:** Direct marketing and high-ROI retention campaigns.
  
---

## 📏 Model Evaluation

* Elbow Method
* Silhouette Score
* PCA Visualization
* Cluster Profiling

---

## 🚀 Key Results

* Identified **4 distinct customer segments**.
* Processed and analyzed **2,236 customers**.
* Generated actionable insights for personalized marketing and customer retention.
* Built an end-to-end unsupervised machine learning workflow.

---

## 🏁 Conclusion

RetailIQ demonstrates how K-Means clustering can transform customer transaction data into meaningful business segments. The four identified groups have distinct income, spending, browsing, household, and campaign-response characteristics, allowing businesses to design targeted marketing strategies for each customer segment.

---

## 🔮 Future Improvements

* Compare K-Means with DBSCAN and Hierarchical Clustering.
* Build CLV prediction models.
* Develop product recommendation systems.
* Create an interactive Streamlit or Power BI dashboard.
* Automate segmentation for new customers.

---

## 📁 Project Structure

```text
RetailIQ/
│
├── RetailIQ.ipynb
├── README.md
```

---

## 👨‍💻 Author

**Shubh Ahire**
Computer Engineering Student | Machine Learning Enthusiast

⭐ If you find this project useful, consider starring the repository!
