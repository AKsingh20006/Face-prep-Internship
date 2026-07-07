Quick Basket Link
https://quick-basket-r.onrender.com  *(Initial loading may take 20–40 seconds as the application is hosted on Render's Free Plan.)*


## Problem Statement :
Small and medium-sized retail businesses often rely on manual record-keeping or spreadsheets to manage inventory, sales, customers, and suppliers. These traditional methods are time-consuming, prone to human error, and make it difficult to monitor stock levels, generate reports, and make informed business decisions. There is a need for an intelligent, centralized, and user-friendly system that automates retail operations while providing real-time insights into business performance.


## Solution:
QuickBasket AI is a cloud-based inventory and sales management system designed to simplify retail business operations through automation and intelligent analytics. The application provides a centralized platform where business owners can efficiently manage products, inventory, sales, customers, suppliers, and business reports.
The system automates essential retail processes such as inventory tracking, billing, stock updates, and report generation, reducing manual effort and minimizing human errors. It also incorporates AI-powered business insights to analyze sales trends and support data-driven decision-making.
By integrating secure user authentication, a responsive web interface, PostgreSQL database, and cloud deployment, QuickBasket AI offers a scalable, reliable, and user-friendly solution that helps retailers improve operational efficiency, maintain accurate records, and make informed business decisions.
## 🛠️ Tools & Technologies Used

- **Programming Language:** Python
- **Backend Framework:** Flask
- **Frontend:** HTML, CSS, Bootstrap 5, JavaScript
- **Database:** PostgreSQL, SQLAlchemy
- **Machine Learning:** Scikit-learn, Pandas, NumPy
- **Data Visualization:** Matplotlib
- **Authentication:** Flask-Login
- **Report Generation:** OpenPyXL, CSV
- **Deployment:** Render
- **Version Control:** Git & GitHub
- **IDE:** Visual Studio Code

- ## ✨ Key Features

- Secure User Authentication
- Smart Inventory Management
- Sales & Billing System
- Customer Management
- Supplier Management
- AI-Powered Business Insights
- Interactive Dashboard
- Sales & Inventory Reports
- Excel & CSV Export
- Low Stock Alerts
- Search & Filter Products
- PostgreSQL Database Integration
- Cloud Deployment on Render
- Responsive Bootstrap Interface
- Data Integrity & Secure Record Management

- ## 🚀 Installation & Setup

Follow these steps to run the project on your local machine.

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/AKsingh20006/Quick-Basket-R.git
cd Quick-Basket-R
```

### 2️⃣ Create a Virtual Environment

**Windows**

```bash
python -m venv venv
venv\Scripts\activate
```

**macOS/Linux**

```bash
python3 -m venv venv
source venv/bin/activate
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 4️⃣ Configure Environment Variables

Create a `.env` file or configure the following environment variables:

```text
SECRET_KEY=your_secret_key
DATABASE_URL=your_postgresql_database_url
```

For local development using SQLite, the application will automatically create a local database if `DATABASE_URL` is not provided.

### 5️⃣ Initialize the Database

If using Flask-Migrate:

```bash
flask db upgrade
```

Or, if this is the first time running the application and it creates tables automatically, simply proceed to the next step.

### 6️⃣ Run the Application

```bash
python app.py
```

or

```bash
flask run
```

### 7️⃣ Open the Application

Open your browser and visit:

```
http://127.0.0.1:5000
```

Register a new account and start using **QuickBasket AI**.

---

## 📦 Requirements

- Python 3.10 or later
- PostgreSQL (recommended for production)
- Git
- pip

---

## ☁️ Deployment

The application is deployed on **Render** with **PostgreSQL** as the production database.

---

## 🔑 Default Workflow

1. Register a new account.
2. Log in securely.
3. Add products to inventory.
4. Manage customers and suppliers.
5. Create sales and generate invoices.
6. View dashboard analytics.
7. Export reports in Excel or CSV format.
