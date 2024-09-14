# MALL-CUSTOMER-SEGMENTATION

Implemented a data analysis model to segment mall customers based on their transaction data using K-Means clustering and RFM (Recency, Frequency, and Monetary) models. The project aimed to help the mall management identify customer groups for targeted marketing strategies.

![23(1)](https://github.com/user-attachments/assets/659ababc-3684-469d-9426-526d60e3c4f0)
![21 (1)](https://github.com/user-attachments/assets/916d3d34-d78c-4f1a-bdab-b5f619d6ec89)


> [!IMPORTANT]
> 
**Technologies:** Python, Pandas, NumPy, Matplotlib, Seaborn, K-Means Clustering, Flask.

**Languages Used:**

➢ PYTHON

➢ MACHINE LEARNING LIBRARIES.

**ALGORITHMS AND METHODS USED:**

➢ RFM MODEL(Recency, Frequency, Monetary Analysis)

➢ K MEANS CLUSTERING ALGORITHM

➢ ELBOW CURVE METHOD

**Dataset**

➢ Source: Kaggle - Online Retail Dataset

➢ Columns/Variables: CustomerID, InvoiceDate, Quantity, UnitPrice, StockCode, InvoiceNo,Description, Country.

➢ Size:541,909 rows x 8 columns

➢ Format: CSV

➢ License: Open Database License (ODbL)

**Preprocessing Steps:** Removed missing values, and converted date strings to datetime objects.

**Relevance to the Project:**

This dataset is utilized for customer segmentation using the RFM model and K-means clustering in our project on personalized marketing strategies for online retail. The data set has attributes like- InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID and Country. But we will be mainly making use of features like CustomerID, UnitPrice, Quantity, InvoiceDate, etc, and also, we would need to make new features as well to calculate the RFM score, and those features will be used further for finding the similarity to assign each customer to a cluster using k-means.
