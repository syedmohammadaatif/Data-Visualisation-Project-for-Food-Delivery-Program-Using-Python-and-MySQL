# Data Visualisation Project for Food Delivery Program using Python and MySQL

## Project Overview
This project demonstrates a **Food Delivery Data Visualisation System** developed using **Python (Front End)** and **MySQL (Back End)**. The system stores and manages food delivery related data such as users, restaurants, menu items, and orders in a MySQL database. Python is used to retrieve the data from the database and generate meaningful **data visualizations and insights**.

The goal of the project is to analyze food delivery data and present it in a clear and visual form to better understand trends such as order patterns, restaurant performance, and user activity.

---

## Technologies Used

- **Python** – Used as the front end for data processing and visualization  
- **MySQL** – Used as the back end database for storing and managing data  
- **MySQL Connector for Python** – For connecting Python with the MySQL database  
- **Data Visualization Libraries** – Used to generate charts and graphs

---

## System Architecture

**Front End:** Python  
**Back End:** MySQL Database

Workflow:
1. Data is stored and managed in the MySQL database.
2. Python connects to the database using a MySQL connector.
3. Queries are executed to retrieve relevant data.
4. The retrieved data is processed and visualized using Python.

---

## Database Structure

The database contains tables related to the food delivery system, such as:

- **Users** – Stores customer information
- **Restaurants** – Contains restaurant details
- **Menu / Food Items** – Stores available food items
- **Orders** – Contains order details and transactions
- **Delivery Information** – Tracks delivery related data

These tables help simulate a real-world food delivery platform database.

---

## Features

- Food delivery database management using MySQL
- Integration of Python with MySQL
- Data retrieval using SQL queries
- Data visualization of food delivery trends
- Analysis of orders, restaurants, and users
- Graphical representation of food delivery data

---

## Visualizations Included

Examples of visual insights generated in the project may include:

- Number of orders per restaurant
- Popular food items
- Order distribution
- Customer activity analysis
- Restaurant performance comparison

---

## How to Run the Project

### 1. Install Required Software
- Install **Python**
- Install **MySQL Server**
- Install required Python libraries

### 2. Install Python Dependencies
```bash
pip install mysql-connector-python
pip install matplotlib
pip install pandas
```

### 3. Set Up the Database
1. Open MySQL.
2. Create the required database and tables.
3. Import or insert the project dataset.

### 4. Run the Python Program
Run the Python script that connects to the MySQL database and generates the visualizations.

```bash
python main.py
```

---

## Project Purpose

This project was developed as an **academic project** to demonstrate:

- Database management using MySQL
- Integration of Python with relational databases
- Data analysis and visualization techniques
- Practical implementation of a food delivery system dataset

---

## Future Improvements

- Add a graphical user interface (GUI)
- Implement real-time order tracking
- Include more advanced data analytics
- Deploy the system as a web application

---

## Author

**Syed Mohammad Aatif**

---

## License

This project is created for **educational purposes**.
