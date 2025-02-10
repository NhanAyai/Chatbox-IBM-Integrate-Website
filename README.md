# 🌟 Chatbox-IBM-Integrate-Website 🌟

<p align="center">
  <img src="https://img.shields.io/badge/IBM%20Watson-Chatbox-blue?style=for-the-badge" alt="IBM Watson Badge"/>
  <img src="https://img.shields.io/badge/Db2%20Cloud-Database-green?style=for-the-badge" alt="Db2 Cloud Badge"/>
</p>

---

## 🎯 Overview

<p align="center">
  This project integrates an IBM Watson-powered chatbot from the Kommunication platform into a website, using IBM Db2 Cloud Database for backend storage.  
  Follow this guide to set up and integrate the database with your project. 💻📊
</p>

---

## 📚 Prerequisites

Before you begin, ensure you have the following:
- **IBM Cloud account** (Free trials available 🆓)
- Basic understanding of Python and working with databases 🐍

---

## 🛠️ IBM Db2 Cloud Integration Tutorial

### Step 1: Create an IBM Cloud Account
1. Go to [IBM Cloud](https://cloud.ibm.com/) and sign up for a free trial account.  
2. Verify your email and log in to your IBM Cloud dashboard.

### Step 2: Create a Db2 Database
1. On the left side panel, click **Resource List**.  
2. Click **Create a Resource**.

### Step 3: Search and Create Db2 Database
1. In the search bar, type **db2**.  
2. Click on the **Db2** option that appears.  
3. Change the region to **London** (or your preferred region).  
4. Choose the **Lite plan** (this is the free version).  
5. Click **Create** to deploy the Db2 database.

### Step 4: Access the Created Database
1. Go back to the **Resource List**.  
2. Under **Databases**, find your new Db2 instance and click on it to open the details page.

### Step 5: Copy Service Credentials
1. In your Db2 instance, click on the **Service Credentials** tab.  
2. Copy the **username**, **password**, **Database ID**, and **Port** information to use in your code.

### Step 6: Create a Schema and Table
1. Navigate to the **Manage** tab in your Db2 instance.  
2. Click **Go to UI** to access the web-based Db2 console.  
3. Create a schema and a table for loading your data. For detailed instructions, refer to the [IBM Cloud documentation](https://cloud.ibm.com/docs) or other resources online.

---

## 🚀 Project Setup

### Step 7: Clone the Project Repository
```bash
git clone https://github.com/NhanAyai/Chatbox-IBM-Integrate-Website.git

```

### Step 8: Adjust the Code in app.ipynb
1. Open the app.ipynb file in a Jupyter notebook or your preferred environment.
2. Modify the database connection code to use your Db2 username , password , Database ID , and Port .
3. Adjust the table name and column names to match the schema and table you created.
4. The notebook includes functions to interact directly with your Db2 database, such as adding and deleting data.

🙏 Acknowledgements
<p align="center">
Thank you for checking out this project! If you find it helpful, please give it a star ⭐.
Good luck with your IBM Watson and Db2 integration journey! 🚀
</p>

<p align="center">
Made with ❤️ by NhanAyai
</p>
