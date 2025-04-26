# 🛒 E-commerce Product Analysis Project

A detailed exploratory data analysis (EDA) and Power BI dashboard project based on multi-website product listings.  
The goal is to analyze pricing trends, discounts, and product categories to extract meaningful insights and create an interactive business dashboard.

---

## 📂 About the Dataset

This dataset contains product information collected from three major e-commerce platforms: **Amazon**, **Flipkart**, and **eBay**.  
Each product entry includes the following details:

- **Website** (Amazon, Flipkart, or eBay)  
- **Category** (e.g., Electronics, Clothing, Accessories)  
- **Sub-Category** (e.g., Smartphones, Laptops)  
- **Product Name**  
- **Specifications** (Features, Technical Details)  
- **Color**  
- **Price** (in INR)  
- **Discount** (in %)  
- **Brand**  
- **Type** (Product Type)

> 🔎 **Note**:  
> - Missing values in the `SPECIFICATIONS` column were handled carefully by replacing them with 'N/A'.  
> - Minor inconsistencies (e.g., duplicate website names like "FLIPKART ") were corrected during data cleaning.

---

## 📊 Exploratory Data Analysis (EDA)

A full EDA was conducted to understand the structure and patterns within the dataset.

### Key EDA Steps:

- **Data Cleaning**:  
  - Filling missing values.
  - Correcting spelling inconsistencies.
  - Removing unnecessary whitespaces.

- **Basic Analysis**:
  - Website-wise product distribution.
  - Price and discount distributions.
  - Brand and category analysis.

- **Visualization**:
  - Histograms for price and discount analysis.
  - Bar charts for average price and discount trends.
  - Top 10 most expensive and cheapest products.

---

## 📈 Power BI Dashboard

An interactive Power BI dashboard was created to highlight major KPIs, price trends, discount patterns, and product performance.

---

### 🎛️ Slicers (Filters) Available:

- **Website**: Amazon / Flipkart / eBay  
- **Category**: Selectable product categories (e.g., Electronics, Clothing, Accessories)

---

### 📌 Dashboard Visualizations

| Visualization | Description |
|:--------------|:------------|
| **Top 10 Expensive Products** | Table showcasing products with the highest prices. |
| **Top 10 Cheap Products** | Table listing the least expensive products. |
| **Average Price by Sub-Category** | Bar chart showing average pricing across different sub-categories. |
| **Average Discount by Product Name** | Bar chart highlighting product-specific average discounts. |
| **Average Discount by Brand** | Column chart showing brand-wise average discounts. |

---

## 📊 Key Metrics (KPIs) Covered

- **Average Price per Website**
- **Average Discount per Brand**
- **Product-wise Discount Analysis**
- **Top 10 Expensive and Cheapest Products**
- **Sub-Category Price Trends**

---

## 🚀 Project Highlights

✅ Completed full EDA and preprocessing of the dataset.  
✅ Cleaned and standardized the data for better analysis.  
✅ Designed and published an interactive Power BI dashboard.  
✅ Implemented user-friendly slicers for dynamic filtering.  
✅ Generated deep insights into product pricing and discount behavior.

---

## 📎 Dataset Summary

| Column | Description |
|:-------|:------------|
| **Websites** | Source website (Amazon, Flipkart, or eBay) |
| **Category** | Broad classification (e.g., Electronics) |
| **Sub-Category** | Detailed product classification (e.g., Smartphones) |
| **Product Name** | Name of the listed product |
| **Specifications** | Features and technical details |
| **Color** | Product color |
| **Price** | Selling price (in INR) |
| **Discount** | Discount offered (in %) |
| **Brand** | Brand name |
| **Type** | Product type |

---

## 🔥 Future Enhancements

- 📈 Add **Time-Series Analysis** (if historical product price data becomes available).
- 🛒 Build a **Product Recommendation System** based on product categories and discounts.
- 🎯 Perform **Sentiment Analysis** if customer review data is available.
- 🌍 Introduce **cross-country comparisons** if international data is gathered.
- 🚀 Deploy the dashboard publicly for **live online access** using Power BI Service or a website.

---

## 📬 Contact

If you have any questions about this project, or would like to collaborate, feel free to reach out!

**👨‍💻 Pritam Mohanta**  
📩 Email: [samratmohanta7001@gmail.com](mailto:samratmohanta7001@gmail.com)  
🔗 GitHub: [pritam-mohanta](https://github.com/pritam-mohanta?tab=repositories)

---

## 📝 License

This project is open-sourced under the [MIT License](LICENSE).

You are free to use, modify, and distribute this project for personal or commercial use, but please provide appropriate credit to the author.

---

## 🙌 Acknowledgements

- 📚 Dataset compiled from multiple e-commerce platforms: Amazon, Flipkart, and eBay.
- 📊 Dashboard developed using [Microsoft Power BI](https://powerbi.microsoft.com/).
- 🐍 EDA performed using:
  - [Pandas](https://pandas.pydata.org/)
  - [NumPy](https://numpy.org/)
  - [Matplotlib](https://matplotlib.org/)
  - [Seaborn](https://seaborn.pydata.org/)

Special thanks to the open-source community for providing fantastic learning resources and tools!

---

## ⭐ How to Support

If you found this project helpful or interesting, please consider giving the repository a ⭐!  
It encourages me to build and share more awesome projects with the community.

---

🌟 Thank you for visiting and exploring this project! 🌟
