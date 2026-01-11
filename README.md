# 📊 RN-KNN: Classification Model Comparison

**RN-KNN** is a supervised learning project that combines the implementation of **k‑Nearest Neighbors (k‑NN)** with **Neural Networks (NN)** for data classification. The main goal is to **compare the performance of both approaches** and analyze their results using evaluation metrics, providing a clear view of which model performs better on different types of data.

---

## 🎯 Project Objective

- Implement the classic **k-NN** algorithm for data classification.
- Develop a simple **Neural Network** for the same problem.
- Compare the results of both models using metrics such as **precision, accuracy, and error**.
- Evaluate the advantages and limitations of each approach for different datasets.

---

## 🧠 Algorithms Used

### k‑Nearest Neighbors (k‑NN)
- An **instance-based** method that classifies a new observation according to its *k* nearest neighbors.
- Does not require explicit training; it relies directly on the training data.
- Ideal for small to medium-sized problems where the distance between points is significant.

### Neural Networks (NN)
- A **parametric** model that learns complex patterns through layers of neurons and activation functions.
- Can capture non-linear relationships that k-NN cannot directly model.
- Requires **supervised training** and hyperparameter tuning.

---

## 🗂 Project Structure

RN-KNN/ <br>
├── Fase1/ # Data preparation and initial exploration <br>
├── Fase2-KNN/ # k-NN algorithm implementation and testing <br>
├── Fase2-RN/ # Neural Network implementation and training <br>
├── Fase3/ # Results comparison and metrics analysis <br>
└── Other files # Experiment notebooks, graphs, and results <br>

## 🚀 Requirements and Execution

### Requirements
- Python 3.8 or higher
- Jupyter Notebook / JupyterLab
- Main libraries:
pip install numpy pandas scikit-learn matplotlib tensorflow

## 📊 Project Benefits

- Allows visualizing and comparing the performance of k‑NN and Neural Networks in classification tasks.

- Serves as an educational resource to understand the differences between instance-based models and parametric models.

- Helps make informed decisions about which model to use depending on dataset size and data complexity.

## Contributions

- Improve internal documentation.
- Add more datasets for experiments.
- Implement advanced visualizations and additional metrics.
- Optimize the models and compare new classification algorithms.
