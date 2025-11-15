# Customer Segmentation using K-Means Clustering

This is a machine learning project. It uses unsupervised learning (K-Means) to analyze the `Mall_Customers.csv` dataset and segment customers into 5 distinct groups based on their income and spending scores.

---

## How to Run This Program

This program is designed to run in Google Colab.

**Click the badge below to open and run the program instantly:**

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1mmjgFIp7TE9YxNoRVK-rvjkRxuhMICt3?usp=sharing)

**How to use the link:**
1.  Click the "Open in Colab" badge.
2.  Once the notebook is open, click "Runtime" from the top menu.
3.  Select "Run all" to execute the entire program.
4.  The interactive prompt will appear at the bottom after the model is trained and the plot is shown.

**NOTE:** This notebook needs the Mall_Customers.csv file to work, run the code cautiosly to avoid errors.

---

## Video Demonstration

Here is a short video where I demonstrate the program, explain the code, and show the results.

**[Click here to watch the demo on DRIVE](https://drive.google.com/drive/folders/1NifMDOXQW8gAARNeKp2nPCiixg9ZxUAa?usp=sharing)**

---

## About the Model

* **Model Type:** Unsupervised Learning (K-Means Clustering)
* **Libraries Used:** `scikit-learn`, `pandas`, `matplotlib`
* **Dataset:** `Mall_Customers.csv`

### The 5 Discovered Clusters:

This plot shows the final 5 segments the model discovered:

 
<img width="854" height="551" alt="Screenshot 2025-11-15 193053" src="https://github.com/user-attachments/assets/a3a175e9-19bb-4286-9b88-ea901a09b021" />


1.  **Standard (Green):** Average income, average spending.
2.  **Target (Red):** High income, high spending.
3.  **Careless (Cyan):** Low income, high spending.
4.  **Careful (Blue):** High income, low spending.
5.  **Sensible (Magenta):** Low income, low spending.
