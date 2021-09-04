# Machine Learning with Python

## Description
This course teaches an understanding and application of machine learning (ML) including when to use different ML techniques such as regression, classification, clustering and recommender systems. You learn to use different machine learning libraries in Python, mainly Scikit-learn, to generate and apply different types of ML algorithms such as decision trees, logistic regression, k-means, KNN and SVM.

## Skills
Technical skills learned (using Pandas, NumPy, Scikit-learn) in this course are:
- Regression
  - Simple Linear
  - Multiple Linear
  - Non-Linear
  - Polynomial
- Classification
  - Decision Trees 
  - KNN
  - SVM
  - Logistic Regression
- Clustering
  - K-Means
  - DBSCAN
  - Hierarchical
- Recommender Systems
  - Collaborative Filtering
  - Content-Based

## Assignments & Certificate
This course spans over multiple weeks and it has at least one or more of the following assignments:
- Coding Exercises
- Quizzes (Multiple Choice)

The coding exercises & quizzes are auto-graded by the platform. If you pass a specific threshold (e.g. 80%), you pass the course and get the certificate. If you collect all 10 course certificates within this specialization, you get the specialization certificate.

## Personal Learnings
There are a lot of algorithms out there and I can't learn them all to perfection, so it is important to know when to use which kind of algorithm and then dive deep to learn it while applying it. That's where the Foundational Methodology for Data Science (IBM's CRISP-DM) comes in, having "Analytic Approach" as their second step in the Data Science Methodology. This stage entails expressing the problem in the context of statistical and machine-learning techniques, so the organization can identify the most suitable ones for the desired outcome. For example, if the goal is to predict a response such as “yes” or “no,” then the analytic approach could be defined as building, testing and implementing a classification model.

After that it is about building a benchmark model ([sklearn.dummy](https://scikit-learn.org/stable/modules/generated/sklearn.dummy.DummyClassifier.html#sklearn.dummy.DummyClassifier)) that works with simple rules and just functions as a baseline that should be exceeded. Choosing the best real algorithm is no easy choice, but there are libraries like [lazypredict](https://lazypredict.readthedocs.io/en/latest/) or [pycaret](https://pycaret.org/compare-models/) that compare a lot of different ML models with default hyperparameters for you so it becomes easier to anchor and reason the first model that is going to be tested.

One more thing I recognized/learned is that the scale level of categorical variables is often misused, namely ordinally scaled variables and nominally scaled variables. While for nominal scale the OneHotEncoder (Scikit-learn) is applicable, but for ordinal scale it is the OrdinalEncoder (Scikit-learn) to preserve the order of the categories so the ML algorithm can learn this information too.

## Reference & more Infos
- For more Information visit [Coursera](https://www.coursera.org/learn/machine-learning-with-python?specialization=ibm-data-science)
- Or visit the [IBM website](https://www.ibm.com/training/badge/5d3833ce-2abe-43b7-aed4-fb1c6a51a553)

## 📫 Let's connect and learn from each other:

[<img src="https://github.com/kevin-goetz/kevin-goetz/blob/main/LinkedIn Logo.png" height="40em" align="center" alt="Connect with Me on LinkedIn" title="Connect with Me on LinkedIn"/>](https://linkedin.com/in/kgötz) [<img src="https://github.com/kevin-goetz/kevin-goetz/blob/main/Codewars Logo.svg" height="40em" align="center" alt="Connect with Me on Codewars" title="Connect with Me on Codewars"/>](https://www.codewars.com/users/kevin-goetz)

