**🛍️ Shopper Spectrum — Customer Segmentation & Product Recommendations**

An intelligent retail analytics project that segments customers and recommends products using real-world e-commerce transaction data. It leverages RFM-based clustering and item-based collaborative filtering to uncover purchasing patterns, enhance personalization, and optimize business strategy.

**📌 Project Overview**

This project focuses on:

**🎯 Customer Segmentation:**
Analyzing Recency, Frequency, and Monetary (RFM) scores to classify customers into segments such as High-Value, Regular, Occasional, and At-Risk.

**🧾 Product Recommendation:**
Using collaborative filtering to identify and suggest similar products based on historical purchase behavior.

**📊 Interactive Visualization:**
Deploying insights and predictions in a user-friendly Streamlit dashboard for marketers, analysts, and product managers.

**🧠 Skills Gained**

🧮 RFM (Recency-Frequency-Monetary) Analysis

🤖 KMeans Clustering for customer segmentation

🎯 Item-based Collaborative Filtering

🧩 Feature Engineering & Data Preprocessing

📊 Exploratory Data Analysis (EDA)

🧱 Model Evaluation (Elbow Method, Silhouette Score)

🖥️ Streamlit Dashboard Development

🧮 Cosine Similarity & Recommendation Matrices

**🧩 Steps Involved**

**✅ Step 1: Dataset Collection**

Public e-commerce dataset from Kaggle or similar source

Key features: InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, Country

**✅ Step 2: Data Preprocessing**

Removed missing CustomerID entries

Excluded cancelled invoices (InvoiceNo starting with “C”)

Filtered out zero or negative Quantity and UnitPrice values

**✅ Step 3: Exploratory Data Analysis (EDA)**

Visualized transaction trends and revenue distribution

Identified top-selling products and customer behavior patterns

Analyzed RFM value distributions

**✅ Step 4: Customer Segmentation**

Computed:

Recency: Days since last purchase

Frequency: Number of purchases

Monetary: Total spend per customer

Scaled features using StandardScaler

Applied KMeans clustering

Determined optimal clusters using Elbow and Silhouette methods

Interpreted clusters into marketing segments

**✅ Step 5: Product Recommendation System**

Built a Customer-Product purchase matrix

Applied item-based collaborative filtering using cosine similarity

Recommended top-N similar products for a given item

**✅ Step 6: Streamlit App Integration**

Developed two interactive modules:

Product Recommendation Module:

Input: StockCode or Product Name

Output: Top 5–10 similar product recommendations

Customer Segmentation Module:

Input: Recency, Frequency, Monetary values

Output: Cluster label (High-Value / Regular / Occasional / At-Risk)

**📊 Sample Dashboard Features**
**Module                                                   	Functionality**
🧾 Product Recommendation                         	Recommends similar products based on purchase similarity

👥 Customer Segmentation	                          Predicts which segment a customer belongs to using RFM input

📦 Explore Products	                                Displays top 50 revenue-generating items

**🛠 Tech Stack Used**
**Category	                                               Tools / Libraries**
🐍 Programming	                                                Python

📊 Data Analysis	                                           Pandas, NumPy

🤖 Machine Learning	                                Scikit-learn (KMeans, Cosine Similarity)

📈 Visualization	                                        Matplotlib, Seaborn

🖥️ Web App	                                                   Streamlit

💾 Model Storage	                                               oblib

☁️ Deployment	                                           Google Colab + ngrok

**🎯 Real-World Business Use Cases**

🎯 **Targeted Marketing Campaign**s – Group customers by behavior for personalized offers

🛍️ **Personalized Recommendations** – Improve user experience and sales conversions

💰 **Customer Retention** – Identify at-risk customers for re-engagement

🏷️ **Dynamic Pricing** – Optimize discounts by customer segment

📦 **Inventory Planning** – Stock products based on demand trends

**🧠 Key Learnings**

✔️ Implementing end-to-end machine learning workflows

✔️ Performing RFM-based segmentation with real data

✔️ Building collaborative filtering recommendation systems

✔️ Deploying ML results in interactive dashboards

✔️ Applying clustering evaluation metrics (Elbow & Silhouette)

**🧾 Evaluation Metrics**

📉 Inertia (Elbow Method) – Cluster compactness

📊 Silhouette Score – Cluster separation quality

🔍 Recommendation Accuracy – Similarity score validation

**🖥️ Streamlit Dashboard Preview**

  **🧾 Product Recommendation**

        Enter a product name or StockCode → Get 5 most similar products.

  **👥 Customer Segmentation**

        Input Recency, Frequency, and Monetary values → Predict the customer cluster.

  **📦 Explore Products**

        View top 50 revenue-generating products.

**🛠 Project Deliverables**

📓 Python Notebook: Data preprocessing, EDA, clustering, and recommendation modeling

🧩 Streamlit App: Real-time segmentation and recommendations

📊 Visual Insights: EDA charts and similarity heatmaps

💾 Model Artifacts: .pkl and .csv files for Streamlit app integration

**📎 References**

Streamlit Documentation (https://docs.streamlit.io/develop/api-reference)

Scikit-learn Documentation (https://scikit-learn.org/stable/documentation.html)

KMeans Clustering Guide (https://scikit-learn.org/stable/modules/clustering.html#k-means)

Collaborative Filtering Overview (https://towardsdatascience.com/collaborative-filtering-basics-and-beyond-7a3f9e5e653f) 

Pandas User Guide (https://pandas.pydata.org/docs/user_guide/index.html)

NumPy Documentation (https://numpy.org/doc/)
