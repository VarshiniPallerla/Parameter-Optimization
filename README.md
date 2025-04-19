# Parameter-Optimization

This project is to implement and evaluate **Support Vector Machine (SVM)** classifiers using optimized parameters on a multi-class dataset from the **UCI Machine Learning Repository**.

## Description
- Choose any dataset from UCI with **5,000 to 30,000 rows**.
- Perform **SVM parameter optimization** using **100 iterations** for **10 different random train-test splits (70:30)**.
- Evaluate and report the best accuracy and corresponding SVM parameters (Kernel, Nu, Epsilon).
- Plot the **convergence graph** for the sample that achieves the **maximum accuracy**.
- Provide basic data analytics and visualization for the chosen dataset.

## Dataset Description
**Dataset:** [Predict students dropout and academic success](https://archive.ics.uci.edu/dataset/697/predict+students+dropout+and+academic+success)  
**Source:** UCI Machine Learning Repository  
**Size:** 36 features, 885 records  
**Target Variables:**  
- `Target_Dropout` (Whether the student dropped out)  
- `Target_Enrolled` (Whether the student is still enrolled)  
- `Target_Graduate` (Whether the student graduated)  
**Objective:** Predict and classify the academic outcome (Dropout, Enrolled, Graduate) based on socio-demographic, economic, and academic attributes.

## Optimization Approach
- Performed a **Grid Search** over SVM parameters (`C`, `gamma`, `kernel`) for each sample.
- Recorded best parameters and accuracy from each iteration.
- Used the sample with **highest accuracy** to generate a convergence plot.

## Result Table
![image](https://github.com/user-attachments/assets/a119fb46-38b4-4595-9fb7-ab9da401a325)

## Result Graph
![image](https://github.com/user-attachments/assets/36c7fe30-5255-4537-bc3e-361042ac9654)

