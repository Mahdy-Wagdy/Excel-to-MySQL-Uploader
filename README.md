# 📊 Excel to MySQL Uploader

A simple web application built with **Flask** that allows users to upload Excel or CSV files and automatically insert the data into a MySQL database.
This tool solves common issues like datatype mismatches, NULL values, and table creation — without needing to use the terminal or command line.

---

## 🚀 Features

* Upload `.csv`, `.xls`, or `.xlsx` files via a browser
* Automatically creates a table in your MySQL database based on the file structure
* Cleans column names and handles missing values
* Supports `VARCHAR`, `FLOAT`, `BOOLEAN`, and `DATETIME` types
* No need for command-line tools — just run and use from your browser

---

## 🛠️ Technologies Used

* Python
* Flask
* Pandas
* MySQL Connector
* Numpy
* OpenPyXL (for Excel file support)

---

## 🛆 Installation & Setup

1. **Download the project folder**

   If you're not using Git, just download or clone the project files.

2. **Install the required libraries**

   Make sure you have Python installed (preferably Python 3.9+), then run:

   ```bash
   pip install -r requirements.txt
   ```

3. **Run the app**

   ```bash
   python app.py
   ```

4. Open your browser and go to:
   `http://127.0.0.1:5000`

---

## 🧪 How to Use

1. Enter your MySQL database connection details on the home page.
2. Upload a `.csv` or `.xlsx` file using the form.
3. Specify a table name where the data will be inserted.




