# Motor-Sales-Forecasting-ML
Web-based machine learning model using TensorFlow.js to forecast motor sales. Features historical analysis, neural network training, and 2025-26 predictions with interactive visualisations.

# 🚀 Interactive Motor Sales Forecasting ML Model

[![License: All Rights Reserved](https://img.shields.io/badge/License-All%20Rights%20Reserved-red.svg)](https://en.wikipedia.org/wiki/All_rights_reserved)
[![Tech Stack](https://img.shields.io/badge/tech-HTML%2C%20CSS%2C%20JS-blue.svg)]()
[![Powered by TensorFlow.js](https://img.shields.io/badge/Powered%20By-TensorFlow.js-orange)]()

**Copyright (c) 2025 [Your Name or Your Company Name]. All Rights Reserved.**

This project is a proprietary demonstration. The code contained in this repository is not licensed for any use, commercial or non-commercial. See the **License and Usage** section for more details.

### ✨ [Live Demo Here!](https://YOUR_GITHUB_USERNAME.github.io/YOUR_REPOSITORY_NAME/)
*(This link is for viewing the live functionality only.)*

---

## 📋 Project Overview

This project is a self-contained single-page web application created to demonstrate the capabilities of in-browser machine learning for business forecasting. It showcases a workflow for data analysis, model training, and forecasting for the **DSM8H 50.0HP MOTOR SS TURBO** product.

The entire machine learning process is executed on the client-side using JavaScript and TensorFlow.js.

---

## 🌟 Key Features

* **Interactive UI:** A step-by-step interface that guides a user through the forecasting process.
* **Historical Data Visualization:** Uses **Chart.js** to render responsive line charts comparing sales data.
* **In-Browser ML Model Training:** Trains a Neural Network using **TensorFlow.js** on historical data.
* **Dynamic Performance Metrics:** Calculates and displays key business and ML model metrics.
* **12-Month Sales Forecasting:** Uses the trained model to predict sales for the next 12 months.
* **Business Insights:** Automatically generates insights based on the analysis and forecast.

---

## 🛠️ Technical Workflow

The application follows a logical sequence from data preparation to forecasting.

1.  **Data Preparation:** Historical sales data is normalized using a min-max scaling function to prepare it for the neural network.
2.  **Model Architecture:** A sequential neural network is defined using `tf.sequential()` with multiple Dense and Dropout layers. It uses a sliding window of 3 months of data to predict the 4th month.
3.  **Training:** The model is compiled with the `adam` optimizer and `meanSquaredError` loss function. It is then trained for 100 epochs.
4.  **Forecasting:** The model predicts the next 12 months iteratively. The output is then denormalized and adjusted with simple business logic to produce the final forecast.

---

## 🖥️ Viewing the Project

You may view the project's live functionality by opening the `index.html` file in a web browser. **This action does not grant you any rights to the underlying code or assets.**

---

## ⚖️ License and Usage

**This is not an open-source project.**

* **Copyright:** Copyright (c) 2025 [Your Name or Your Company Name]. All Rights Reserved.
* **No License Granted:** No license, express or implied, is granted to any party under this copyright.
* **Usage Prohibited:** You are **strictly prohibited** from using, copying, modifying, merging, publishing, distributing, sublicensing, and/or selling copies of the Software.
* **Purpose:** This repository and its contents are for **demonstration and portfolio purposes only**. Any other use is a violation of copyright law.
