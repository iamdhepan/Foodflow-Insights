# Foodflow Insights

## **Description**
This project analyzes user behavior, cooking preferences, and order trends using three datasets: **UserDetails**, **CookingSessions**, and **OrderDetails**. The goal is to explore the relationships between cooking sessions and user orders, identify popular dishes, and analyze demographic influences on user behavior.

## **Technologies Used**
- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook
# **Report on User Behavior, Cooking Preferences, and Order Trends**

---

## **1. Introduction**

This analysis aims to explore and understand key insights into user behavior, cooking preferences, and order trends. The analysis uses three datasets: **UserDetails**, **CookingSessions**, and **OrderDetails**. The goal is to clean, merge, and analyze these datasets to identify correlations, popular dishes, and demographic factors influencing user behavior.

---

## **2. Data Cleaning & Preprocessing**

- **Merging Data:**  
  The datasets were merged based on common attributes such as `user_id` to create a consolidated dataset for analysis.

- **Data Cleaning:**  
  We cleaned the datasets by handling missing values, correcting any data discrepancies, and ensuring that all relevant columns were in the correct format for analysis.

---

## **3. Relationship Between Cooking Sessions and User Orders**

### **Analysis:**
- **Correlation Analysis:**  
  A strong positive correlation of **1.00** was observed between cooking sessions and total orders. This indicates that as the number of cooking sessions increases, the number of orders also increases proportionally. This could suggest that users who engage more with cooking sessions are more likely to place orders.

### **Visual Representation:**  
- A **scatter plot** was created to visualize the relationship between the total number of cooking sessions and total orders. This confirmed the direct relationship between the two variables.

#### **Insight:**  
Users who participate in more cooking sessions are more likely to place orders, indicating that engagement with the cooking platform directly influences order activity.

---

## **4. Popular Dishes**

### **Analysis:**
- The most popular dishes were identified based on frequency of orders. The top dishes include:
  - **Spaghetti** and **Grilled Chicken** (most popular, each with 4 occurrences).
  - **Caesar Salad** followed with 3 occurrences.
  - **Pancakes** and **Veggie Burger** also showed moderate popularity.

### **Visual Representation:**  
- A **bar chart** was created to show the top 10 most popular dishes based on order occurrences.

#### **Insight:**  
Spaghetti and Grilled Chicken emerge as the top dishes ordered by users, suggesting that these items could be prioritized in marketing efforts or featured more prominently on the platform.

---

## **5. Demographic Factors Influencing User Behavior**

### **Analysis:**
- **Age vs. Average Order Amount:**
  - Younger age groups (e.g., 25-28 years) typically spent less per order (around $10–$12 USD).
  - Older age groups (e.g., 35 years and above) showed higher median order amounts (around $14 USD or more).
  
### **Visual Representation:**  
- A **box plot** was used to show the distribution of average order amounts across different age groups.

#### **Insight:**  
Older users tend to spend more on their orders, indicating that they may have higher disposable incomes or a preference for premium products. This information can help tailor targeted promotions.

---

## **6. Meal Preferences by Location**

### **Analysis:**
- **Order Distribution by Meal Type and Location:**
  - **Dinner** was the most popular meal type across locations like **New York**, **San Francisco**, and **Seattle**.
  - **Breakfast** was more popular in **Miami**, while **Lunch** was predominantly ordered in **Los Angeles** and **Chicago**.

### **Visual Representation:**  
- A **stacked bar chart** was used to visualize the distribution of meal types by location.

#### **Insight:**  
Location-specific trends suggest that users in different regions have distinct meal preferences. This can guide inventory management and targeted marketing campaigns.

---

## **7. Business Recommendations**

Based on the analysis, the following business recommendations can be made:

1. **Increase Engagement through Cooking Sessions:**  
   Since there is a strong correlation between cooking sessions and orders, the platform could focus on increasing user engagement by offering more interactive cooking sessions, tutorials, and promotions for users who actively participate.

2. **Promote Popular Dishes:**  
   Focus on promoting dishes like **Spaghetti**, **Grilled Chicken**, and **Caesar Salad**, which have high popularity. These dishes can be highlighted in special promotions or meal kits to increase user orders.

3. **Target Marketing Based on Age:**  
   Since older users tend to spend more on orders, targeted campaigns could be created for this demographic, offering them premium dishes, meal plans, or discounts on larger orders.

4. **Regional Customization:**  
   Considering regional meal preferences, the platform can introduce location-based promotions. For example, users in **Miami** could be offered discounts or meal packages focused on **Breakfast**, while **San Francisco** users might appreciate more **Dinner** options.

5. **Use Data for Personalization:**  
   Leveraging user data (e.g., age, cooking preferences) to create personalized meal plans or special offers could help improve customer satisfaction and increase order frequency.

---

## **8. Conclusion**

This analysis sheds light on key factors influencing user behavior and order trends. By identifying relationships between cooking sessions and orders, as well as understanding popular dishes and demographic preferences, businesses can take data-driven steps to improve customer engagement, marketing strategies, and overall business growth.


