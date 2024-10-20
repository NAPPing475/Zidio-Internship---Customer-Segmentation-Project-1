

# **CUSTOMER SEGMENTATION USING K-Means CLUSTERING**

This project aims to categorize customers into distinct segments based on their purchasing patterns and search behaviors. By leveraging **K-Means Clustering**, we can uncover patterns in customer interactions, helping to optimize marketing strategies and improve customer engagement.

---

## **Project Objective:**

The goal of this project is to analyze customer data, perform clustering to segment customers into meaningful groups, and derive insights for targeted marketing and personalized offerings. **K-Means Clustering** is used to group customers based on various factors such as **Orders**, **Product Searches**, and **Gender**.

---

## **Data Fields:**

- **Cust_ID:** Unique identifier for each customer.
- **Gender:** Customer’s gender.
- **Orders:** Total number of orders placed by the customer.
- **Search Features:** Includes the number of times the customer searched for products, and other search-related metrics.

---

## **Clustering Approach:**

### **1. Data Preprocessing:**
   - **Missing Data Handling:**
     - **Action:** Fill missing values in the **Gender** column using mode.
   - **Duplicate Check:**
     - **Action:** Remove any duplicate records for cleaner data analysis.

### **2. Data Visualization:**
   - **Overall Orders vs Gender Distribution:**
     - **Visualization:** Bar plot showcasing the distribution of orders between male and female customers.
   - **Brand Searches by Gender:**
     - **Visualization:** Compare the number of product searches made by different genders using bar and count plots.
    
     ![CSG](https://github.com/user-attachments/assets/1cd33aad-81d4-4c55-8948-c43cde856b28)
      ![sge](https://github.com/user-attachments/assets/deadfd14-7fe9-40db-922c-668ee4138060)
      


### **3. Feature Scaling:**
   - **Scaling Technique:** Apply **MinMaxScaler** to normalize the features before clustering to ensure that the algorithm performs efficiently.

---

## **K-Means Clustering:**

### **1. Optimal Number of Clusters:**
   - **Method:** Use the **Elbow Method** and **Silhouette Score** to determine the optimal number of clusters.
   - **Visualization:** Generate an **Elbow Plot** and **Silhouette Score Plot** to analyze the results.

  ![image](https://github.com/user-attachments/assets/6b4235c3-f75b-4374-8442-446f3354b4e9)
  ![image](https://github.com/user-attachments/assets/8b976ab0-5f49-438b-8c78-5f9898a5f2f8)

  
### **2. Clustering Execution:**
   - **Algorithm:** Apply **K-Means** clustering on the dataset to segment customers into optimal clusters.
   - **Number of Clusters:** Experiment with different values of **K** based on the elbow and silhouette analysis.

---

## **Cluster Analysis:**

### **1. Cluster 0 Analysis:**
   - **Description:** 
     - Customers in **Cluster 0** exhibit a high number of product searches and moderate order frequency.
   - **Visualization:**
     - **Gender Distribution:** Bar plot showcasing the gender distribution within this cluster.
     - **Total Searches:** Bar plot comparing the total number of searches made by each gender within this cluster.

### **2. Cluster 2 Analysis:**
   - **Description:**
     - **Cluster 2** is characterized by customers with lower search activity but a higher conversion rate in terms of orders.
   - **Visualization:**
     - **Customer Count:** Gender-wise distribution of customers.
     - **Total Searches:** A bar plot highlighting the total searches by each gender in this cluster.

### **3. Overall Cluster Comparison:**
   - **Description:**
     - Compare the behavior across all clusters to understand customer segments that search more but buy less, and those that buy frequently with fewer searches.
   - **Visualization:**
     - **Cluster Comparison:** Bar charts showing the number of customers, total searches, and total orders across different clusters.

---

## **Business Insights and Applications:**

### **1. Personalized Marketing:**
   - Use segmentation insights to craft targeted marketing strategies aimed at high-search, low-order customers to boost conversion rates.

### **2. Product Recommendations:**
   - Provide personalized product recommendations for customers in **Cluster 0** based on their search behavior.

### **3. Customer Retention Strategies:**
   - Design loyalty programs for customers in **Cluster 2** to maintain their high-order frequency and encourage further engagement.

![image](https://github.com/user-attachments/assets/81ef24e0-d559-4ca0-b4a3-90458e6e01b6)

![image](https://github.com/user-attachments/assets/bde4c2a5-baea-41ac-9515-63c33918ef90)


---

## **Key Performance Indicators (KPIs):**

- **Average Orders per Cluster:** Track the average number of orders placed by customers within each cluster.
- **Search-to-Order Conversion Rate:** Measure the effectiveness of product searches leading to orders.
- **Gender Distribution in Clusters:** Monitor gender-based behavioral patterns to inform marketing campaigns.

---

## **Tools and Technologies:**

- **Python:** For data manipulation, preprocessing, and clustering.
- **Seaborn and Matplotlib:** For creating insightful visualizations.
- **Scikit-learn:** For implementing **K-Means Clustering** and evaluating the model using the **Elbow Method** and **Silhouette Score**.
- **Pandas:** For handling the dataset and performing exploratory data analysis (EDA).

---

## **Summary:**

This **Customer Segmentation** analysis helps in identifying distinct customer groups based on their interaction data, enabling businesses to implement more targeted marketing efforts. By understanding the behaviors of different clusters, strategies like personalized marketing, better product recommendations, and customer retention programs can be implemented for improved business outcomes.

---

