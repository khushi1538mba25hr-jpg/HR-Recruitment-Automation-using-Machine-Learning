
# HR Recruitment Automation using Machine Learning

## Project Title

Candidate Selection Prediction using Decision Tree

---

## Overview

This project demonstrates the application of Machine Learning in Human Resource Management to support recruitment decision-making.
It focuses on predicting whether a candidate is likely to be selected based on key evaluation parameters.

The solution uses a Decision Tree model to automate initial candidate screening, helping organizations improve efficiency and consistency in hiring processes.

---

## Problem Statement

Organizations receive a large volume of job applications, making manual screening time-consuming and inconsistent.
The objective of this project is to develop a predictive model that classifies candidates into:

* **1 → Selected**
* **0 → Not Selected**

This enables structured and data-driven shortlisting.

---

## Business Context

Recruitment is a critical HR function that directly impacts organizational performance.
Manual evaluation often leads to delays and subjective decisions.

This project addresses these challenges by:

* Automating initial screening
* Reducing repetitive manual effort
* Standardizing evaluation criteria
* Assisting recruiters in identifying suitable candidates faster

The system is designed to support HR teams, not replace human judgment.

---

## Dataset Description

A synthetic dataset is created to simulate real-world recruitment scenarios.

### Features

* **Experience Years** – Total years of work experience
* **Test Score** – Technical or aptitude assessment score
* **Interview Score** – Candidate performance in interviews
* **Skill Match** – Alignment with job role (Low, Medium, High)

### Target Variable

* **Selected** – Indicates whether a candidate is selected (1) or not (0)

---

## Methodology

The project follows a structured Machine Learning workflow:

1. Data generation
2. Target variable creation using hiring logic
3. Feature and target separation
4. Model training using Decision Tree
5. Prediction on new candidate data
6. Interpretation of results

---

## Model Information

* **Algorithm Used:** Decision Tree Classifier
* **Type:** Supervised Learning (Classification)

The model learns decision rules based on candidate attributes and applies them to predict selection outcomes.

---

## 📓 Google Colab Notebook

You can view and run the complete implementation using the link below:

https://colab.research.google.com/drive/16yYJR4iv-ANj-zshnF6EcMQzAUXc1ANl#scrollTo=mIhm7QqiZXcG

---

## Key Insights

* Candidates with higher experience and strong performance scores are more likely to be selected
* Skill-role alignment plays a significant role in hiring decisions
* AI can help prioritize candidates efficiently in large applicant pools

---

## Business Impact

* Reduces time spent on initial candidate screening
* Improves consistency in shortlisting decisions
* Enhances recruitment workflow efficiency
* Supports data-driven HR practices

---

## Ethical Considerations

The use of AI in recruitment must be handled responsibly:

* Avoid bias in training data
* Ensure fairness in candidate evaluation
* Maintain transparency in decision-making
* Prevent over-reliance on automated systems

AI should assist human decision-makers, not replace them.

---

## Future Enhancements

* Increase dataset size for better generalization
* Include additional features such as education level
* Compare with other models like Logistic Regression
* Integrate visualization for better interpretability
* Extend the system into a deployable application

---

## Author

khushi phogat 


