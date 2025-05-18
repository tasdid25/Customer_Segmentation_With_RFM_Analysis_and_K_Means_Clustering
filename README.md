# 🛍️ Customer Segmentation Using RFM Analysis and K-Means Clustering

This project applies **RFM (Recency, Frequency, Monetary)** analysis and **K-Means clustering** to segment customers based on their purchasing behavior using real-world e-commerce transaction data.

---

## 📁 Project Structure

- `OnlineRetail.csv`: Raw transaction dataset from a UK-based online retailer.
- `Customer_Segmentation_With_RFM_Analysis_and_K_Means_Clustering.ipynb`: Jupyter Notebook containing data preprocessing, RFM scoring, clustering, and visualizations.

---

## 📊 Objectives

- Clean and preprocess e-commerce transaction data.
- Derive Recency, Frequency, and Monetary values for each customer.
- Segment customers into behavioral groups using K-Means clustering.
- Visualize clusters for actionable business insights.

---

## 🔧 Tools & Technologies

- **Python** (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)
- **Jupyter Notebook**
- **K-Means Clustering**
- **RFM Analysis (Marketing Analytics)**

---

## 📌 Key Steps

1. **Data Cleaning**
   - Removed nulls and duplicates.
   - Filtered only valid transactions (e.g., positive quantity and price).
   - Removed canceled orders.

2. **RFM Feature Engineering**
   - **Recency**: Days since last purchase.
   - **Frequency**: Total number of purchases.
   - **Monetary**: Total amount spent.

3. **RFM Scoring**
   - Used quantiles to score each RFM metric from 1 to 4.
   - Combined scores into a single segment identifier.

4. **Clustering with K-Means**
   - Normalized RFM values.
   - Applied Elbow Method to determine optimal `k`.
   - Used K-Means to cluster customers.

5. **Visualization**
   - Plotted cluster distributions using 2D scatter plots.
   - Interpreted behavior of each segment.

---

## 📈 Results & Insights

- Segmented customers into distinct behavioral clusters (e.g., high-value vs low-value).
- Identified groups for targeted marketing: VIPs, potential loyalists, at-risk customers, etc.
- Provided actionable insights for customer retention and engagement.

---

## 🚀 How to Run

1. Clone the repository or download the files.
2. Open the `.ipynb` notebook in Jupyter Lab/Notebook.
3. Run all cells step-by-step to reproduce the analysis.
4. Ensure `OnlineRetail.csv` is in the same directory.

---

## ✅ Requirements

Install the following Python libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
