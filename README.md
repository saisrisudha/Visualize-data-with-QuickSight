# Visualize-data-with-QuickSight
Beginner project demonstrating how to visualize data using Amazon QuickSight and Amazon S3 with step-by-step setup and dashboard creation.


# 📊 Visualizing Data with Amazon QuickSight

This beginner-friendly project demonstrates how to visualize data using **Amazon QuickSight**, a cloud-based business intelligence tool by AWS. The project guides you through steps such as uploading data to Amazon S3, connecting it with QuickSight using a `manifest.json` file, creating visualizations, and publishing dashboards.

---

## 🚀 What You’ll Learn

- Creating and configuring an Amazon S3 bucket
- Uploading CSV and JSON files
- Understanding and using `manifest.json`
- Connecting S3 data to Amazon QuickSight
- Creating and customizing data visualizations
- Refreshing datasets and updating dashboards
- Publishing and exporting dashboards
- Cleaning up AWS resources after use

---

## 🧰 Tools Used

- **Amazon S3** – To store dataset files (CSV and JSON)
- **Amazon QuickSight** – For visual analytics and dashboard creation
- **manifest.json** – A configuration file to define data location and structure for QuickSight

---

## 📂 Project Steps Overview

### 1️⃣ Amazon S3 Setup
- Create a new S3 bucket
- Upload your dataset file (CSV)
- Modify and upload the `manifest.json` file containing the S3 URI of your dataset

### 2️⃣ Amazon QuickSight Setup
- Sign up for QuickSight
- Create a new dataset and connect to the S3 bucket using the manifest file
- Visualize the data by creating charts (e.g., a pie chart of release years)
- Add filters, groups, and titles to improve visualization

### 3️⃣ Handling Data Issues
- If your dataset has missing or duplicate values:
  - Clean the data
  - Re-upload the cleaned CSV file
  - Update the URI in `manifest.json`
  - Refresh the dataset in QuickSight

### 4️⃣ Finalizing the Dashboard
- Rearrange and rename visuals as needed
- Click **Publish** to finalize your dashboard
- Download the dashboard as a PDF if required

---

## 🧹 Cleanup Steps

### Delete QuickSight Account
- Go to **Manage QuickSight** → **Account Settings**
- Turn off termination protection and confirm deletion

### Delete S3 Bucket
- Empty the bucket contents
- Delete the bucket permanently

---

## 📌 Key Concepts

- **Amazon S3**: Cloud storage for datasets
- **Amazon QuickSight**: BI tool to visualize and analyze data
- **manifest.json**: A helper file that tells QuickSight where and how to read your data
- **Data Refresh**: QuickSight allows reloading updated data without recreating visuals
