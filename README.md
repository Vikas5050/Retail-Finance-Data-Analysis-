# Retail-Finance-Data-Analysis

![Retail Finance Dashboard](https://drive.google.com/file/d/1vLs_wglvYBHCsLiyxRJw1uJ4BzhP2O8f/view?usp=drive_link)

## 📌 Project Overview
This project focuses on analyzing retail financial data using Power BI to gain insights into revenue, orders, customer behavior, transaction patterns, and product performance. The objective is to enhance data-driven decision-making by visualizing key metrics.

## 🚀 Features
- **Revenue & Order Analysis**: Calculate total revenue, average order price, and order trends.
- **Customer Segmentation**: Identify new vs. returning customers and prioritize high-value customers.
- **Transaction Analysis**: Analyze payment methods and transaction success rates.
- **Product Performance**: Evaluate top-selling products, revenue contributions, and category-based sales.
- **Interactive Dashboard**: A visually rich and interactive Power BI dashboard.

## 🛠️ Technologies Used
- **Tool**: Power BI
- **Data Source**: Amazon Redshift
- **Data Processing**: DAX, Power Query (M Language)

## 📂 Data Source - Amazon Redshift
The project uses **Amazon Redshift** as the primary data source, importing structured tables:
- **Orders Table**: Contains details like `order_id`, `customer_id`, `product_id`, `order_date`, `quantity`, `total_price`, etc. A new column **customer_type** was created to classify customers as `new_customer` or `returning_customer` based on order history.
- **Transactions Table**: Includes `transaction_id`, `customer_id`, `transaction_date`, `amount`, `payment_method`, and `status` for payment analysis.
- **Customers Table**: Stores `customer_id`, `name`, `email`, `phone`, and `address`, used for segmentation and marketing targeting.
- **Products Table**: Holds `product_id`, `name`, `category`, `price`, `stock_quantity`, enabling product performance analysis.

## 🎯 Installation
To set up this project locally:

1. Clone the repository:
```bash
git clone https://github.com/your-username/retail-finance-analysis.git
cd retail-finance-analysis
```

2. Open the Power BI file (`RetailFinance.pbix`).

3. Connect to Amazon Redshift and configure the data import.

4. Refresh the dataset to load the latest insights.

## 📊 Dashboard Visualizations
1. **Daily Revenue & Order Trend** - Line chart showing revenue/order trends.
2. **Customer Segmentation** - Pie/bar chart for new vs. returning customers.
3. **Payment Method Distribution** - Pie/bar chart visualizing payment preferences.
4. **Transaction Success vs. Failure** - Bar chart comparing successful vs. failed transactions.
5. **Product Performance Analysis** - Bar charts highlighting top-performing products by revenue and quantity sold.
6. **Category-Based Sales Performance** - Sales distribution across product categories.

## 📝 Contributing
Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch: `git checkout -b feature-branch`.
3. Commit your changes: `git commit -m 'Add new feature'`.
4. Push to the branch: `git push origin feature-branch`.
5. Open a pull request.

## 🛡 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📬 Contact
For any queries or collaborations, feel free to reach out:
- **Email**: your-email@example.com
- **LinkedIn**: [Your Profile](https://linkedin.com/in/yourprofile)
- **GitHub**: [Your Username](https://github.com/your-username)

---

⭐ **If you found this project helpful, consider giving it a star!** ⭐
