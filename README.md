Employee Bonus Prediction using Gradient Descent Variants

This project demonstrates the implementation of core optimization algorithms:

Gradient Descent (GD)
Stochastic Gradient Descent (SGD)
Mini-Batch Gradient Descent

The goal is to predict employee bonus based on performance-related features.

📌 Problem Statement

Given employee data such as:

Performance rating
Years of experience
Projects completed

We aim to predict the bonus amount using a regression model optimized with different Gradient Descent techniques.

📊 Dataset

The dataset consists of 32 employee records with the following features:

Feature	Description
employee_id	Unique employee identifier
performance	Performance rating (1–10)
years_of_experience	Total years of experience
projects_completed	Number of completed projects
bonus	Target variable (to predict)
Sample Data
EMP_001   7   2   4   124
EMP_002   4   1   4   82
EMP_003   8   7   10  178
...
EMP_032   3   7   9   116
🧠 Model Approach

We implemented a Linear Regression model trained using three optimization techniques:

GD → Uses full dataset
SGD → Updates per data point
Mini-Batch GD → Updates per batch
📐 Mathematical Formula

θ=θ−η⋅∇J(θ)

Where:

θ = model weights
η = learning rate
J(θ) = loss function (Mean Squared Error)
⚙️ Features Used

Input Features:

performance
years_of_experience
projects_completed

Target: Bonus

🛠️ Tech Stack
Language: Python / Java (update based on your implementation)
Libraries: NumPy / Pandas (if used)
Tools: VS Code / IntelliJ
📂 Project Structure
├── data/
│   └── employee_data.csv
├── src/
│   ├── gradient_descent.py
│   ├── stochastic_gd.py
│   ├── mini_batch_gd.py
├── model/
├── utils/
├── README.md
