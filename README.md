# Mall Customers Segmentation  

## 📌 Introduction  

Customer segmentation is the practice of dividing a customer base into groups of individuals that are similar in specific ways relevant to marketing, such as age, gender, interests, and spending habits.  

By segmenting customers, businesses can:  
- Target specific groups with tailored marketing messages.  
- Improve customer satisfaction by understanding preferences.  
- Increase sales through personalized strategies.  

---

## 📊 Objective  

The main objective of this project is to perform **customer segmentation** using the Mall Customers dataset. This involves:  
- Exploring and analyzing customer data.  
- Applying clustering techniques (like **K-Means**).  
- Visualizing customer groups.  
- Suggesting marketing strategies for each segment.  

---

## 📂 Dataset  

The dataset contains information about mall customers, including:  
- **CustomerID**: Unique ID assigned to each customer  
- **Gender**: Male/Female  
- **Age**: Age of the customer  
- **Annual Income (k$)**: Annual income in thousands of dollars  
- **Spending Score (1–100)**: Score assigned by the mall based on customer behavior  

---

## ⚙️ Methodology  

### 🔹 Data Exploration & Cleaning  
- Checked dataset shape, null values, and summary statistics.  
- Visualized distributions (Age, Income, Spending Score).  

### 🔹 Exploratory Data Analysis (EDA)  
- Plotted age distribution, income distribution, and spending score distribution.  
- Explored relationships between features (Age vs Income, Income vs Spending Score, etc.).  

### 🔹 Clustering (K-Means)  
- Applied the **Elbow Method** to determine the optimal number of clusters.  
- Implemented **K-Means clustering** to segment customers.  

### 🔹 Visualization  
- Used scatter plots and cluster visualizations to interpret results.  
- Highlighted distinct customer groups.  

---

## 📈 Results  

The analysis revealed **5 major customer segments**, for example:  
- **Cluster 1**: Young, high-income, high spenders → Premium customers.  
- **Cluster 2**: Middle-aged, moderate income, low spenders → Occasional buyers.  
- **Cluster 3**: Low income, low spending → Budget-conscious customers.  
- **Cluster 4**: High income, low spending → Potential customers.  
- **Cluster 5**: Moderate income, high spending → Regular buyers.  

---

## 🚀 Technologies Used  

- **Python**  
- **Jupyter Notebook**  
- **Libraries**:  
  - `pandas`, `numpy` → Data handling  
  - `matplotlib`, `seaborn` → Visualization  
  - `scikit-learn` → Machine Learning (K-Means)  

---

## 📌 How to Run  

1. Clone this repository:  
   ```bash
   git clone https://github.com/Muhammad-Ishfaqch/MallCustomersSegmentation.git
   cd MallCustomersSegmentation


