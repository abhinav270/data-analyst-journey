# Comprehensive Learning Notebooks for Data Science and Python

This repository is a curated collection of Jupyter notebooks designed to provide a structured, hands-on learning path for Python programming, data science, and machine learning. The roadmaps cover everything from the fundamentals of Python to advanced topics in machine learning and data visualization.

## How to Use

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/abhinav270/data-analyst-journey.git
    cd data-analyst-journey
    ```

2.  **Create and activate a virtual environment:**
    *   This keeps project dependencies isolated.
    ```bash
    # Create the virtual environment
    python3 -m venv .venv

    # Activate it (Linux/macOS)
    source .venv/bin/activate

    # Activate it (Windows)
    # .\\.venv\\Scripts\\activate
    ```

3.  **Install the required packages:**
    *   The primary `requirements.txt` is located in the Python learning directory.
    ```bash
    pip install -r requirements.txt
    ```
    *   Note: Some notebooks, especially in the advanced sections, may have their own specific dependencies. Instructions are provided within those notebooks.

4.  **Launch Jupyter:**
    ```bash
    jupyter notebook
    ```

5.  **Start learning!**
    *   Navigate to the desired notebook series and begin.

---

## 📚 Table of Contents

*   [🐍 Python Learning Roadmap](#-python-learning-roadmap)
*   [🔬 Statistics Learning Roadmap](#-statistics-learning-roadmap)
*   [🔢 NumPy Learning Roadmap](#-numpy-learning-roadmap)
*   [🐼 Pandas Learning Roadmap](#-pandas-learning-roadmap)
*   [📊 Data Visualization Roadmap](#-data-visualization-roadmap)
*   [🤖 Machine Learning Roadmap](#-machine-learning-roadmap)
*   [💾 SQL & SQLAlchemy Roadmap](#-sql--sqlalchemy-roadmap)

---

## 🐍 Python Learning Roadmap
A complete guide to Python programming, from basic syntax to advanced features.

*   **01: Python Basics**
    *   [Getting Started](./01_python-learning/01_Python_Basics/01_Getting_Started.ipynb)
    *   [Variables and Data Types](./01_python-learning/01_Python_Basics/02_Variables_and_Data_Types.ipynb)
    *   [Operators](./01_python-learning/01_Python_Basics/03_Operators.ipynb)
    *   [Control Flow](./01_python-learning/01_Python_Basics/04_Control_Flow.ipynb)
    *   [Loops](./01_python-learning/01_Python_Basics/05_Loops.ipynb)
    *   [Strings](./01_python-learning/01_Python_Basics/06_Strings.ipynb)
    *   [Lists](./01_python-learning/01_Python_Basics/07a_Lists.ipynb)
    *   [Tuples](./01_python-learning/01_Python_Basics/07b_Tuples.ipynb)
    *   [Sets](./01_python-learning/01_Python_Basics/07c_Sets.ipynb)
    *   [Dictionaries](./01_python-learning/01_Python_Basics/07d_Dictionaries.ipynb)
*   **02: Functions and Modularity**
    *   [Functions](./01_python-learning/02_Functions_and_Modularity/08_Functions.ipynb)
    *   [Scope and Namespaces](./01_python-learning/02_Functions_and_Modularity/09_Scope_and_Namespaces.ipynb)
    *   [Built-in Functions and Modules](./01_python-learning/02_Functions_and_Modularity/10_Built-in_Functions_and_Modules.ipynb)
    *   [File Handling](./01_python-learning/02_Functions_and_Modularity/11_File_Handling.ipynb)
    *   [Error Handling](./01_python-learning/02_Functions_and_Modularity/12_Error_Handling.ipynb)
*   **03: Object-Oriented Programming**
    *   [Classes and Objects](./01_python-learning/03_Object_Oriented_Programming/13_Classes_and_Objects.ipynb)
    *   [OOP Principles](./01_python-learning/03_Object_Oriented_Programming/14_OOP_Principles.ipynb)
    *   [Special (Dunder) Methods](./01_python-learning/03_Object_Oriented_Programming/15_Special_Dunder_Methods.ipynb)
    *   [Properties](./01_python-learning/03_Object_Oriented_Programming/16_Properties.ipynb)
*   **04: Advanced Python**
    *   [Modules and Packages](./01_python-learning/04_Advanced_Python/17_Modules_and_Packages.ipynb)
    *   [Functional Programming](./01_python-learning/04_Advanced_Python/18_Functional_Programming.ipynb)
    *   [Iterators and Generators](./01_python-learning/04_Advanced_Python/19_Iterators_and_Generators.ipynb)
    *   [Decorators](./01_python-learning/04_Advanced_Python/20_Decorators.ipynb)
    *   [Context Managers](./01_python-learning/04_Advanced_Python/21_Context_Managers.ipynb)
    *   [Exception Customization](./01_python-learning/04_Advanced_Python/22_Exception_Customization.ipynb)
    *   [Working with Libraries](./01_python-learning/04_Advanced_Python/23_Working_with_Libraries.ipynb)
    *   [Packaging a Project](./01_python-learning/04_Advanced_Python/24_Packaging_a_Project.ipynb)
    *   [Virtual Environments and pip](./01_python-learning/04_Advanced_Python/25_Virtual_Environments_and_pip.ipynb)
*   **05: Next Steps**
    *   [Best Practices](./01_python-learning/05_Next_Steps/27_Best_Practices.ipynb)

---

## 🔬 Statistics Learning Roadmap
A comprehensive introduction to statistical concepts, from foundations to advanced methods.

*   [01: Foundations of Statistics](./02_statistics-notebook/01-foundations-of-statistics.ipynb)
*   [02: Descriptive Statistics](./02_statistics-notebook/02-descriptive-statistics.ipynb)
*   [03: Probability Basics](./02_statistics-notebook/03-probability-basics.ipynb)
*   [04: Probability Distributions](./02_statistics-notebook/04-probability-distributions.ipynb)
*   [05: Sampling and Sampling Distributions](./02_statistics-notebook/05-sampling-and-sampling-distributions.ipynb)
*   [06: Inferential Statistics](./02_statistics-notebook/06-inferential-statistics.ipynb)
*   [07: Correlation and Regression](./02_statistics-notebook/07-correlation-and-regression.ipynb)
*   [08: Advanced Statistical Methods](./02_statistics-notebook/08-advanced-statistical-methods.ipynb)
*   [09: Experimental Design & Causality](./02_statistics-notebook/09-experimental-design-and-causality.ipynb)
*   [10: Bayesian Statistics](./02_statistics-notebook/10-bayesian-statistics.ipynb)
*   [11: Practical Skills](./02_statistics-notebook/11-practical-skills.ipynb)

---

## 🔢 NumPy Learning Roadmap
Master the foundational library for numerical computing in Python.

*   [01: Introduction & Setup](./03_numpy-notebook/01-introduction-and-setup.ipynb)
*   [02: The ndarray](./03_numpy-notebook/02-ndarray-core-data-structure.ipynb)
*   [03: Array Indexing & Slicing](./03_numpy-notebook/03-array-indexing-and-slicing.ipynb)
*   [04: Array Manipulation](./03_numpy-notebook/04-array-manipulation.ipynb)
*   [05: Vectorization & Broadcasting](./03_numpy-notebook/05-vectorization-and-broadcasting.ipynb)
*   [06: Advanced Indexing & Selection](./03_numpy-notebook/06-advanced-indexing-and-selection.ipynb)
*   [07: Mathematical & Statistical Functions](./03_numpy-notebook/07-mathematical-and-statistical-functions.ipynb)
*   [08: Random Number Generation](./03_numpy-notebook/08-random-number-generation.ipynb)
*   [09: Structured & Record Arrays](./03_numpy-notebook/09-structured-and-record-arrays.ipynb)
*   [10: Performance & Memory](./03_numpy-notebook/10-performance-and-memory.ipynb)
*   [11: Advanced Topics](./03_numpy-notebook/11-advanced-topics.ipynb)
*   [12: Integration with Other Libraries](./03_numpy-notebook/12-integration-with-other-libraries.ipynb)
*   [13: Real-World Projects](./03_numpy-notebook/13-real-world-projects.ipynb)

---

## 🐼 Pandas Learning Roadmap
A complete guide to data manipulation and analysis with Pandas.

*   [01: Introduction & Basics](./04_pandas-notebook/01-introduction-and-basics.ipynb)
*   [02: Core Data Structures](./04_pandas-notebook/02-core-data-structures.ipynb)
*   [03: Data Loading & Exporting](./04_pandas-notebook/03-data-loading-and-exporting.ipynb)
*   [04: Data Selection & Indexing](./04_pandas-notebook/04-data-selection-and-indexing.ipynb)
*   [05: Data Cleaning](./04_pandas-notebook/05-data-cleaning.ipynb)
*   [06: Data Transformation](./04_pandas-notebook/06-data-transformation.ipynb)
*   [07: Indexing & MultiIndex](./04_pandas-notebook/07-indexing-and-multiindex.ipynb)
*   [08: Data Aggregation & GroupBy](./04_pandas-notebook/08-data-aggregation-and-groupby.ipynb)
*   [09: Merging & Reshaping Data](./04_pandas-notebook/09-merging-and-reshaping-data.ipynb)
*   [10: Time Series & Datetime](./04_pandas-notebook/10-time-series-and-datetime.ipynb)
*   [11: Performance & Optimization](./04_pandas-notebook/11-performance-and-optimization.ipynb)
*   [12: Advanced Applications](./04_pandas-notebook/12-advanced-applications.ipynb)
*   [13: Real-World Projects](./04_pandas-notebook/13-real-world-projects.ipynb)

---

## 📊 Data Visualization Roadmap
From static plots with Matplotlib and Seaborn to interactive visualizations with Plotly.

*   **Matplotlib**
    *   [01: Matplotlib Basics](./05_visualization-notebook/01-matplotlib-basics.ipynb)
    *   [02: Intermediate Matplotlib](./05_visualization-notebook/02-matplotlib-intermediate.ipynb)
    *   [03: Advanced Matplotlib](./05_visualization-notebook/03-matplotlib-advanced.ipynb)
*   **Seaborn**
    *   [04: Seaborn Basics](./05_visualization-notebook/04-seaborn-basics.ipynb)
    *   [05: Intermediate Seaborn](./05_visualization-notebook/05-seaborn-intermediate.ipynb)
    *   [06: Advanced Seaborn](./05_visualization-notebook/06-seaborn-advanced.ipynb)
*   **Plotly**
    *   [07: Plotly Basics](./05_visualization-notebook/07-plotly-basics.ipynb)
    *   [08: Intermediate Plotly](./05_visualization-notebook/08-plotly-intermediate.ipynb)
    *   [09: Advanced Plotly](./05_visualization-notebook/09-plotly-advanced.ipynb)
*   **General Skills**
    *   [10: Cross-Library Skills](./05_visualization-notebook/10-cross-library-skills.ipynb)

---

## 🤖 Machine Learning Roadmap
A structured guide from the prerequisites to deploying real-world models.

*   **Level 0: Prerequisites**
    *   [Mathematics](./06_machine-learning-roadmap/Level_0_Prerequisites/01_Mathematics/Mathematics.ipynb)
    *   [Python Libraries](./06_machine-learning-roadmap/Level_0_Prerequisites/02_Python_Libraries/Python_Libraries.ipynb)
    *   [Jupyter and Environment](./06_machine-learning-roadmap/Level_0_Prerequisites/03_Jupyter_and_Environment/Jupyter_and_Environment.ipynb)
*   **Level 1: Data Preprocessing**
    *   [Handling Missing Data](./06_machine-learning-roadmap/Level_1_Data_Preprocessing/Handling_Missing_Data/Handling_Missing_Data.ipynb)
    *   [Encoding Categorical Variables](./06_machine-learning-roadmap/Level_1_Data_Preprocessing/Encoding_Categorical_Variables/Encoding_Categorical_Variables.ipynb)
    *   [Outlier Detection and Treatment](./06_machine-learning-roadmap/Level_1_Data_Preprocessing/Outlier_Detection_and_Treatment/Outlier_Detection_and_Treatment.ipynb)
    *   [Scaling and Normalization](./06_machine-learning-roadmap/Level_1_Data_Preprocessing/Scaling_and_Normalization/Scaling_and_Normalization.ipynb)
    *   [Feature Creation and Transformation](./06_machine-learning-roadmap/Level_1_Data_Preprocessing/Feature_Creation_and_Transformation/Feature_Creation_and_Transformation.ipynb)
    *   [Binning](./06_machine-learning-roadmap/Level_1_Data_Preprocessing/Binning/Binning.ipynb)
*   **Level 2: Supervised Learning**
    *   [Linear Regression](./06_machine-learning-roadmap/Level_2_Supervised_Learning/01_Linear_Regression/Linear_Regression.ipynb)
    *   [Polynomial Regression](./06_machine-learning-roadmap/Level_2_Supervised_Learning/02_Polynomial_Regression/Polynomial_Regression.ipynb)
    *   [Regularization](./06_machine-learning-roadmap/Level_2_Supervised_Learning/03_Regularization/Regularization.ipynb)
    *   [Decision Tree Regressor](./06_machine-learning-roadmap/Level_2_Supervised_Learning/04_Decision_Tree_Regressor/Decision_Tree_Regressor.ipynb)
    *   [Random Forest Regressor](./06_machine-learning-roadmap/Level_2_Supervised_Learning/05_Random_Forest_Regressor/Random_Forest_Regressor.ipynb)
    *   [Gradient Boosting Regressor](./06_machine-learning-roadmap/Level_2_Supervised_Learning/06_Gradient_Boosting_Regressor/Gradient_Boosting_Regressor.ipynb)
    *   [Support Vector Regression](./06_machine-learning-roadmap/Level_2_Supervised_Learning/07_Support_Vector_Regression/Support_Vector_Regression.ipynb)
    *   [Logistic Regression](./06_machine-learning-roadmap/Level_2_Supervised_Learning/08_Logistic_Regression/Logistic_Regression.ipynb)
    *   [k-Nearest Neighbors](./06_machine-learning-roadmap/Level_2_Supervised_Learning/09_k_Nearest_Neighbors/k_Nearest_Neighbors.ipynb)
    *   [Support Vector Machine](./06_machine-learning-roadmap/Level_2_Supervised_Learning/10_Support_Vector_Machine/Support_Vector_Machine.ipynb)
    *   [Decision Tree Classifier](./06_machine-learning-roadmap/Level_2_Supervised_Learning/11_Decision_Tree_Classifier/Decision_Tree_Classifier.ipynb)
    *   [Random Forest Classifier](./06_machine-learning-roadmap/Level_2_Supervised_Learning/12_Random_Forest_Classifier/Random_Forest_Classifier.ipynb)
    *   [Gradient Boosting Classifier](./06_machine-learning-roadmap/Level_2_Supervised_Learning/13_Gradient_Boosting_Classifier/Gradient_Boosting_Classifier.ipynb)
    *   [Naive Bayes](./06_machine-learning-roadmap/Level_2_Supervised_Learning/14_Naive_Bayes/Naive_Bayes.ipynb)
    *   [Neural Networks (MLP)](./06_machine-learning-roadmap/Level_2_Supervised_Learning/15_Neural_Networks_MLP/Neural_Networks_MLP.ipynb)
    *   [Evaluation Metrics (Regression)](./06_machine-learning-roadmap/Level_2_Supervised_Learning/16_Evaluation_Metrics_Regression/Evaluation_Metrics_Regression.ipynb)
    *   [Evaluation Metrics (Classification)](./06_machine-learning-roadmap/Level_2_Supervised_Learning/17_Evaluation_Metrics_Classification/Evaluation_Metrics_Classification.ipynb)
    *   [Cross Validation](./06_machine-learning-roadmap/Level_2_Supervised_Learning/18_Cross_Validation/Cross_Validation.ipynb)
*   **Level 3: Unsupervised Learning**
    *   [k-Means Clustering](./06_machine-learning-roadmap/Level_3_Unsupervised_Learning/01_Clustering_k_Means/k_Means.ipynb)
    *   [Hierarchical Clustering](./06_machine-learning-roadmap/Level_3_Unsupervised_Learning/02_Clustering_Hierarchical/Hierarchical.ipynb)
    *   [DBSCAN Clustering](./06_machine-learning-roadmap/Level_3_Unsupervised_Learning/03_Clustering_DBSCAN/DBSCAN.ipynb)
    *   [GMM Clustering](./06_machine-learning-roadmap/Level_3_Unsupervised_Learning/04_Clustering_GMM/GMM.ipynb)
    *   [PCA](./06_machine-learning-roadmap/Level_3_Unsupervised_Learning/05_Dimensionality_Reduction_PCA/PCA.ipynb)
    *   [t-SNE](./06_machine-learning-roadmap/Level_3_Unsupervised_Learning/06_Dimensionality_Reduction_tSNE/tSNE.ipynb)
    *   [Anomaly Detection](./06_machine-learning-roadmap/Level_3_Unsupervised_Learning/07_Anomaly_Detection/Anomaly_Detection.ipynb)
    *   [Association Rule Learning](./06_machine-learning-roadmap/Level_3_Unsupervised_Learning/08_Association_Rule_Learning/Association_Rule_Learning.ipynb)
*   **Level 4: Reinforcement Learning**
    *   [Reinforcement Learning Concepts](./06_machine-learning-roadmap/Level_4_Reinforcement_Learning/Reinforcement_Learning_Concepts.ipynb)
*   **Level 5: Model Selection**
    *   [Train/Val/Test Split](./06_machine-learning-roadmap/Level_5_Model_Selection/01_Train_Val_Test_Split/Train_Val_Test_Split.ipynb)
    *   [Overfitting vs Underfitting](./06_machine-learning-roadmap/Level_5_Model_Selection/02_Overfitting_vs_Underfitting/Overfitting_vs_Underfitting.ipynb)
    *   [Hyperparameter Tuning](./06_machine-learning-roadmap/Level_5_Model_Selection/03_Hyperparameter_Tuning/Hyperparameter_Tuning.ipynb)
    *   [Pipelines](./06_machine-learning-roadmap/Level_5_Model_Selection/04_Pipelines/Pipelines.ipynb)
*   **Level 6: Advanced Topics**
    *   [Feature Selection](./06_machine-learning-roadmap/Level_6_Advanced_Topics/01_Feature_Selection/Feature_Selection.ipynb)
    *   [Ensemble Methods](./06_machine-learning-roadmap/Level_6_Advanced_Topics/02_Ensemble_Methods/Ensemble_Methods.ipynb)
    *   [Handling Imbalanced Data](./06_machine-learning-roadmap/Level_6_Advanced_Topics/03_Handling_Imbalanced_Data/Handling_Imbalanced_Data.ipynb)
    *   [Model Interpretability](./06_machine-learning-roadmap/Level_6_Advanced_Topics/04_Model_Interpretability/Model_Interpretability.ipynb)
    *   [Deployment Basics](./06_machine-learning-roadmap/Level_6_Advanced_Topics/05_Deployment_Basics/Deployment_Basics.ipynb)
*   **Level 7: Real-World Projects**
    *   [House Price Prediction](./06_machine-learning-roadmap/Level_7_Real_World_Projects/01_House_Price_Prediction/House_Price_Prediction.ipynb)
    *   [Spam Email Classifier](./06_machine-learning-roadmap/Level_7_Real_World_Projects/02_Spam_Email_Classifier/Spam_Email_Classifier.ipynb)
    *   [Customer Segmentation](./06_machine-learning-roadmap/Level_7_Real_World_Projects/03_Customer_Segmentation/Customer_Segmentation.ipynb)
    *   [Project Ideas](./06_machine-learning-roadmap/Level_7_Real_World_Projects/Project_Ideas.ipynb)

---

## 💾 SQL & SQLAlchemy Roadmap
Learn to query and manage databases from basic SQL to advanced ORM techniques.

*   [01: Intro to Databases & SQL](./07_sql-and-sqlalchemy-notebook/01-intro-to-databases-and-sql.ipynb)
*   [02: SQL DDL](./07_sql-and-sqlalchemy-notebook/02-sql-ddl.ipynb)
*   [03: SQL DML](./07_sql-and-sqlalchemy-notebook/03-sql-dml.ipynb)
*   [04: SQL DQL](./07_sql-and-sqlalchemy-notebook/04-sql-dql.ipynb)
*   [05: Advanced SQL Queries](./07_sql-and-sqlalchemy-notebook/05-advanced-sql-queries.ipynb)
*   [06: Database Design & Normalization](./07_sql-and-sqlalchemy-notebook/06-database-design-and-normalization.ipynb)
*   [07: SQLite in Python](./07_sql-and-sqlalchemy-notebook/07-sqlite3-in-python.ipynb)
*   [08: Intro to SQLAlchemy Core](./07_sql-and-sqlalchemy-notebook/08-intro-to-sqlalchemy-core.ipynb)
*   [09: SQLAlchemy ORM Basics](./07_sql-and-sqlalchemy-notebook/09-sqlalchemy-orm-basics.ipynb)
*   [10: ORM CRUD Operations](./07_sql-and-sqlalchemy-notebook/10-orm-crud-operations.ipynb)
*   [11: Advanced ORM Features](./07_sql-and-sqlalchemy-notebook/11-advanced-orm-features.ipynb)
*   [12: Best Practices](./07_sql-and-sqlalchemy-notebook/12-best-practices.ipynb)
*   [13: Real-World Projects](./07_sql-and-sqlalchemy-notebook/13-real-world-projects.ipynb)

---

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.
