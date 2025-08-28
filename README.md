# Instacart Market Basket Analysis  

## 📌 Objective  
The **Instacart Market Basket Analysis** project aims to explore customer purchasing behavior by analyzing transaction data from the Instacart online grocery platform. Using **Exploratory Data Analysis (EDA)** and **visualizations**, this project identifies **trends, top products, popular aisles, time-based ordering patterns, and organic vs non-organic preferences**.  

The ultimate goal is to provide **data-driven insights** that can help e-commerce platforms improve **product recommendations, marketing strategies, and customer experience**.  

---

## 📂 Dataset  
The dataset used in this project is the **Instacart Online Grocery Shopping Dataset 2017**, which contains over **3 million grocery orders** from more than **200,000 Instacart users**.  

It includes:  
- **Orders** (timestamps, sequence, user-level data)  
- **Products** (item details, organic/non-organic distinction)  
- **Aisles & Departments** (hierarchical product categories)  
- **Reorders** (whether a product was reordered or newly purchased)  

---

## 🔍 Key Insights  
- 🍌 **Bananas** are the most frequently purchased product, followed by **organic bananas and strawberries**.  
- 🛒 **Fresh vegetables and fruits** dominate top-ordered aisles.  
- ⏰ Orders peak between **10 AM – 3 PM**, with significant drop-offs at night.  
- 🌱 **Non-organic products (54.8%)** slightly lead over **organic products (45.2%)**.  
- ♻️ High **reorder probability** highlights customer loyalty toward certain items.  

---

## 📊 Visualizations  
The project includes multiple insights visualized with **Matplotlib & Seaborn**, such as:  

- ✅ Top 10 most ordered products  
- ✅ Top 15 aisles ordered  
- ✅ Organic vs Non-Organic product split  
- ✅ Orders by hour of day  
- ✅ Word cloud of frequently recommended products  
- ✅ Top re-ordered products  

![Instacart Analysis Dashboard](Instacart%20Analysis.png)  

---

## 🛠️ Tech Stack  
- **Python** (Pandas, NumPy)  
- **Matplotlib, Seaborn** (data visualization)  
- **WordCloud** (text analysis visualization)  
- **Jupyter Notebook** (analysis & EDA)  

---

## 🚀 Results & Value  
- Provided **actionable insights** into customer behavior for online grocery shopping.  
- Identified **top-performing products and aisles** to assist in **inventory management & marketing campaigns**.  
- Built a **visual dashboard** summarizing purchasing patterns and reorder tendencies.  

---

## 📈 Future Work  
- Build a **predictive model** for next-product recommendations.  
- Apply **Market Basket Analysis (Apriori / FP-Growth)** for association rules.  
- Create an **interactive dashboard** using Power BI or Streamlit.  

---

## 📌 How to Run the Project  
1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/instacart-market-basket-analysis.git
   cd instacart-market-basket-analysis
