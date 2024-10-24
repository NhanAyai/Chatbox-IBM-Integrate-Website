# Chatbox-IBM-Integrate-Website
The project using Chatbox IBM Watson from Kommunication platform and integrate into website with Db2 Cloud-Database.

# IBM Db2 Cloud Integration Tutorial
This guide will walk you through the process of creating an IBM Db2 database on IBM Cloud and integrating it with your project.

# Prerequisites
- IBM Cloud account (Free trials available)
- Basic understanding of Python and working with databases
  
# Step 1: Create an IBM Cloud Account
1. Go to IBM Cloud and sign up for a free trial account.
2. Verify your email and log in to your IBM Cloud dashboard.

# Step 2: Create a Db2 Database
1. On the left side panel, click Resource List.
2. Click Create a Resource.

# Step 3: Search and Create Db2 Database
1. In the search bar, type db2.
2. Click on the Db2 option that appears.
3. Change the region to London (or your preferred region).
4. Choose the Lite plan (this is the free version).
5. Click Create to deploy the Db2 database.
   
# Step 4: Access the Created Database
1. Go back to the Resource List.
2. Under Databases, find your new Db2 instance and click on it to open the details page.
   
# Step 5: Copy Service Credentials
1. In your Db2 instance, click on the Service Credentials tab.
2. Copy the username, password, Database ID, and Port information to use in your code.
   
# Step 6: Create a Schema and Table
1. Navigate to the Manage tab in your Db2 instance.
2. Click on Go to UI to access the web-based Db2 console.
3. Create a schema and a table for loading your data. For detailed instructions, you can search for tutorials on the IBM Cloud documentation or from other resources online.

# Step 7: Clone the Project Repository
git clone https://github.com/NhanAyai/Chatbox-IBM-Integrate-Website.git

# Step 8: Adjust the Code in app.ipynb
1. Open the app.ipynb file in a Jupyter notebook or your preferred environment.
2. Modify the database connection code to use your Db2 username, password, Database ID, and Port.
3. Adjust the table name and column names to match the schema and table you created.
4. The notebook includes functions to interact directly with your Db2 database, such as adding and deleting data.
   
# Step 9: Good Luck!
You’re all set! Good luck with integrating your Db2 database on IBM Cloud.
