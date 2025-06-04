# Hospital Resource Optimization & Disease Prediction

## Overview

Healthcare management involves critical challenges such as accurately diagnosing diseases based on symptoms and efficiently managing limited hospital resources like doctors, beds, and medical equipment. This project integrates **Disease Prediction** and **Hospital Resource Optimization** to address these challenges through intelligent machine learning and data-driven techniques.

The **Disease Prediction** feature assists patients or healthcare workers by analyzing reported symptoms to predict the most probable disease. The **Resource Optimization** feature aids hospital administrators in effectively allocating and managing hospital resources to meet patient needs, reduce waste, and improve service quality.

---

## Features

### 1. Disease Prediction

- **Symptom Normalization:** Handles variations in symptom descriptions by mapping synonymous terms to a standard set of symptoms.
- **Machine Learning Model:** Uses a Decision Tree classifier trained on labeled data to predict diseases based on binary symptom inputs.
- **Interactive User Input:** Allows users to input symptoms as a comma-separated list which the system processes and analyzes.
- **Output:** Provides the most likely disease corresponding to the provided symptoms, assisting in early diagnosis and care planning.

### 2. Hospital Resource Optimization

- **Resource Tracking:** Monitors available hospital resources such as beds, staff, and equipment.
- **Demand Forecasting:** Uses predicted disease incidence and severity to estimate resource requirements.
- **Allocation Strategy:** Implements algorithms to distribute resources optimally, minimizing shortages and idle capacity.
- **Decision Support:** Helps hospital managers plan staffing, procurement, and capacity expansion dynamically.

---

## Motivation

- **Patient Care:** Early and accurate disease prediction improves patient outcomes by facilitating timely treatment.
- **Efficiency:** Optimizing resource use reduces costs and ensures availability during peak demand.
- **Scalability:** Automating these tasks supports better healthcare delivery in large or resource-constrained facilities.
- **Data-Driven:** Leverages historical data and machine learning to make informed decisions rather than relying on intuition alone.

---

## Technologies & Tools

| Technology          | Purpose                                 |
|---------------------|-----------------------------------------|
| Python 3            | Core programming language                |
| scikit-learn        | Machine learning model implementation   |
| NumPy               | Numerical data processing                |
| pandas              | Data handling and preprocessing (optional) |
| Jupyter Notebook    | Interactive development and testing     |
| Git & GitHub        | Version control and project hosting     |

---

## Project Structure

