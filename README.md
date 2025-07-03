# Smart Store

**Smart Store** is a simple inventory management system for a smartphone store. It supports full CRUD (Create, Read, Update, Delete) operations, allowing users to manage product listings efficiently within a MariaDB database.

---

## 🚀 Features

- Add new product data  
- Search and view existing products  
- Update product information  
- Delete product entries  
- Export data as a CSV file  

---

## ⚙️ Getting Started

### 1. Set Up Your Database

1. Install and configure **MariaDB** on your system.
2. Run the provided `javacrud (1).sql` file to create the required database and tables.
3. *(Optional)* Import `product-data (1).csv` into the product table if you want pre-loaded dummy data.

### 2. Configure Database Connection

- Open the `connect()` method in the source code.
- Replace the placeholder credentials with your actual MariaDB **username** and **password**.

---

## 📘 User Manual

### 1. Log In

- Start the application and log in using your provided credentials.

### 2. Add New Product

1. Fill in the required product details in the form fields.
2. Click the **Add** button to save the new entry to the database.

### 3. Update Product

1. Enter the **Product ID** of the item you wish to update.
2. Edit the desired fields with new information.
3. Click the **Update** button to apply the changes.

### 4. Delete Product

1. Enter the **Product ID** of the product you want to remove.
2. Click the **Delete** button to permanently delete the record from the database.

### 5. Export to CSV

1. Click the **Export to CSV** button.
2. The system will generate a `.csv` file containing all current data in the inventory.

---

### System Images

![](System%20Images/1.png)
![](System%20Images/2.png)
