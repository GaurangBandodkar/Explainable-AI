**SVM Kernel Comparison with LIME Explanation (Iris Dataset)**



This project demonstrates how different Support Vector Machine (SVM) kernels classify the Iris dataset and how we can interpret individual predictions using LIME (Local Interpretable Model-Agnostic Explanations).



📌 Objective



1. Train SVM models using multiple kernels: linear, polynomial, and RBF (Radial Basis Function)

2\. Compare their prediction accuracy

3\. Explain a single prediction using LIME



**What LIME Does**



Most ML models are black boxes.

LIME explains predictions locally:

It approximates the complex model near a single data point using a simple linear model.

So instead of: "Model predicts Virginica"

We get: "Because petal width is large and petal length is large → Virginica"



**Workflow**



1. Load dataset
2. Train-test split
3. Standardize features
4. Train SVM models
5. Compare accuracy
6. Predict the class of one flower
7. Explain prediction using LIME
