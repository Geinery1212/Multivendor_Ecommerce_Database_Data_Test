# README: Setting Up the Multivendor Ecommerce Database

This guide provides instructions to set up the MongoDB database for the Multivendor Ecommerce project.

---

## Prerequisites

1. **MongoDB Installed**: Ensure that MongoDB is installed and running on your local machine. If MongoDB is not installed, refer to the [official MongoDB installation guide](https://www.mongodb.com/docs/manual/installation/).
2. **Database Backup File**: Ensure you have the database backup folder located at:  
   `C:\Users\ADMIN\Downloads\mutivendor_ecommerce`

---

## Steps to Set Up the Database

### 1. Create the Database
First, create the MongoDB database `multivendor_ecommerce` on your local instance.

You can do this by simply running the `mongorestore` command in the next step, as MongoDB will automatically create the database if it doesn't exist.

### 2. Restore the Database Backup
Run the following command in your terminal or command prompt:

```bash
mongorestore --uri "mongodb://127.0.0.1:27017/multivendor_ecommerce" --db multivendor_ecommerce "C:\Users\ADMIN\Downloads\mutivendor_ecommerce"
