# 🍽️ Zomato-Style Food Ordering & Analytics Application

Welcome! This is a demonstration project that recreates a food ordering platform experience—similar to Zomato—using Flask and MySQL with modern frontend design. This project enables customers to place orders, and allows the system owner to generate powerful business analytics using SQL.

## 📌 Project Structure

- **Frontend:** Modern HTML/CSS/JS UI for menu, cart, and order form. (`templates/index.html`)
- **Backend:** RESTful API server built with Flask (`app_index.py`)
- **Database:** Well-organized MySQL schema supporting users, items, categories, orders, payments, and analytics (`schema.sql`, `sample_data.sql`)
- **Analytics:** Business & operational SQL queries for revenue, customer trends, and item/category analysis (`analytics_queries.sql`)
- **Documentation:** This README and (optionally) screenshots/diagrams

## 💡 What We Built

### Process Highlights

1. **Database Design:**  
   - Defined an extensible schema for food items, categories, customers, orders, payments, and order-items.
   - Added sample data, enabling instant testing and analytics.
   - Linked all data via foreign keys, following normalization best practices.

2. **API and Backend Logic:**  
   - Developed a Flask application that serves both the interactive menu and the API endpoints required for order placement and retrieval.
   - Used clear separation of concerns for connection handling and error checking.

3. **Frontend Implementation:**  
   - Designed a visually rich, responsive user interface with HTML, CSS, and JavaScript.
   - Created interactive components: menu dish cards, animated cart, order confirmation, and modern visual effects.
   
4. **Order Workflow:**  
   - User selects items, adds them to cart, enters their address, and places an order.
   - Orders are stored in the database, associating the user, items, quantities, and delivery info.

5. **Analytics & Data Insights:**  
   - Provided a collection of SQL queries for quick analysis, such as total revenue, revenue by item/category, customer order history, payment breakdowns, and more.
   - These can be used directly in MySQL clients or to power charts, dashboards, or business insights tools.

## 🔗 Key Files and Directories

- **`app_index.py`** - Flask backend API and view logic
- **`templates/index.html`** - Main HTML frontend (modern, interactive)
- **`schema.sql`** - SQL file with all table definitions
- **`sample_data.sql`** - Sample data to initialize and test your app quickly
- **`analytics_queries.sql`** - Collection of advanced SQL queries for reporting and analytics

## 👨‍🍳 How the System Works

- The app launches a home page where users see a menu of dishes.
- Customers interactively add items to their cart and provide a delivery address.
- When placing an order, the frontend communicates with the Flask backend via a RESTful API.
- The backend records orders in the MySQL database, keeping relationships between users, items, addresses, and payments.
- The system owner can run the provided SQL queries to analyze revenue, popular dishes, category trends, customer histories, and payment details.

## 📊 Analytics Features

- **Total revenue for all time and by date**
- **Top-selling items and most popular categories**
- **Order and revenue stats per customer or payment method**
- **Detailed order breakdowns by status or item**
- **Customer order history and engagement leaderboard**

(See `analytics_queries.sql` for the full set of SQL analytics.)

## 🛠️ How to Use

1. **Set up the database:**  
   Import `schema.sql` and `sample_data.sql` into your MySQL server.

2. **Configure and run the backend:**  
   Edit database credentials in `app_index.py` if needed.  
   Start the server with `python app_index.py`.

3. **Browse and interact:**  
   Open the browser at `http://localhost:5000` to use the app.

4. **Analyze data:**  
   Run queries from `analytics_queries.sql` in your MySQL client.

**supported by Gowtham YT
