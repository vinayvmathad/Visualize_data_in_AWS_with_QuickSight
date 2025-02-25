# Netflix Data Visualization using Amazon S3 and QuickSight

## Overview
This project focuses on analyzing a large dataset of Netflix shows and movies using **Amazon QuickSight**. QuickSight helps in creating interactive and insightful visualizations with ease. The dataset is stored in an **Amazon S3 bucket**, and a **dashboard** is created to extract meaningful insights.

## Project Workflow
![Image](https://github.com/user-attachments/assets/31db1566-acf8-43f2-8942-1e06be28e16f)
1. 🪣 **Upload the dataset to an S3 bucket**
2. 🆕 **Create an Amazon QuickSight account**
3. 🔗 **Connect the dataset from S3 to QuickSight**
4. 📊 **Generate graphs, charts, and analysis in QuickSight**
5. 🏆 **Publish a dashboard with key insights**

## Steps to Follow

### Step 1: Store the Dataset in Amazon S3
1. Log in to your **AWS Account**.
2. Open the **S3 console**.
3. Click **Create Bucket**.
4. Upload the **CSV file** (`netflix_titles.csv`) and the **manifest.json** file into the bucket.
5. Copy the **S3 URL** of your `netflix_titles.csv` file.
6. Replace the URL in `manifest.json` with the copied S3 URL.


![Image](https://github.com/user-attachments/assets/dc2854a9-ffaf-4bb2-90d4-3e1350583a63)
----
![Image](https://github.com/user-attachments/assets/b7c12139-5987-42a5-82d2-4d870a32fd83)
---

### Step 2: Create an Amazon QuickSight Account
1. Search for **Amazon QuickSight** in AWS.
![Image](https://github.com/user-attachments/assets/994f05f3-299a-4ba5-986d-74570e10d844)
2. **Create a User ID**.
3. 🚨 **Important:** Uncheck the offer to upgrade (optional).
4. Select **Amazon S3** as the data source.
5. Click on **Select S3 Buckets**.
6. Tick the box for the **S3 bucket** where your dataset is stored.
7. Click **Create**.

![Image](https://github.com/user-attachments/assets/91c8d59c-cac8-42a1-99f8-dde9f76cfafe)

![Image](https://github.com/user-attachments/assets/380c39eb-48fc-4f96-a5b7-ce80963062fc)


---

### Step 3: Connect S3 Dataset to QuickSight
1. Open a new **AWS Management Console** tab.
2. Go to your **S3 bucket**.
3. Select the **manifest.json** file and **Copy S3 URL**.
4. Paste the **S3 URL** in QuickSight and click **Connect**.

![Image](https://github.com/user-attachments/assets/75956b1f-3e09-4f92-ab6f-feddd3858ad4)

![Image](https://github.com/user-attachments/assets/1f986e0d-7ea6-4a79-b5c5-392de06652fe)

---

### Step 4: Create Visualizations in QuickSight
1. Click on **Visualize** → **Create**.
2. Drag and drop fields to build charts and graphs.
3. Example: Drag **release_year** into the Y-Axis to analyze the release trends.
4. Experiment with different chart types like **bar charts, pie charts, and line graphs**.

![Image](https://github.com/user-attachments/assets/1dd0f1c6-a074-4e47-addf-a6e1a092aac1)

![Image](https://github.com/user-attachments/assets/6cc96378-ff0e-44a0-b7a3-0a358c1a928a)

---

### Step 5: Publish the Dashboard
1. Click on **Interactive Sheet** to start creating visualizations.
2. On the **top-right corner**, select **Publish**.
3. Give your dashboard a name and click **Publish Dashboard**.
4. Share the dashboard with your data team.

![Image](https://github.com/user-attachments/assets/a21c9f0b-f5e7-4d44-843d-decbf35327d2)


---

## Conclusion
Using **Amazon QuickSight**, we successfully analyzed Netflix data stored in **Amazon S3** and created a **dashboard** with meaningful insights. This project demonstrates how QuickSight simplifies **data visualization and analysis**.

---
