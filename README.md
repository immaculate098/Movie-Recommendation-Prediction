# Default Logistic Regression and Hyperparameter Tuning (Movie Recommendation)

# Problem Statement

In this task I explored the possibility of developing a Movie Recommendation System. I wanted to be able to predict whether a user will like a movie or not based on past movie ratings.

# Technologies Used

- Python

- Jupyter Notebook

- Pandas & NumPy

- Scikit-learn (Logistic Regression, preprocessing, evaluation)

- Matplotlib & Seaborn

# Key Insights/Results

# Confusion Matrix Analysis:

- True Negatives (TN): 7943 - correctly predicted class 0
- False Positives (FP): 4831 - incorrectly predicted class 1 when actual was 0
- False Negatives (FN): 4580 - incorrectly predicted class 0 when actual was 1
- True Positives (TP): 8634 - correctly predicted class 1

# How to Run This Project

- Clone the Repository: Clone this repository to your local machine or download the files.

- Open in Google Colab: https://colab.research.google.com/?authuser=1

- Select File -> Upload notebook... and choose the .ipynb file from this repository.

- Upload the Dataset: In the Colab notebook, click the folder icon on the left sidebar. Click the "Upload to session storage" button and select the CSV file.

- Run the Cells: Execute the notebook cells sequentially to see the analysis and visualizations.

# Author 

By Immaculate Nayiga associated Github: immaculate098

Conclusion:

The tuned model outperformed the default model by achieving higher accuracy and better overall performance metrics. This improvement can be attributed to the GridSearchCV optimization, which systematically explored different hyperparameter combinations to find the best configuration for the decision tree. In contrast, the default model relied on preset parameters that were not tailored to the dataset, resulting in lower predictive capability. This demonstrates the importance of hyperparameter tuning in improving model performance.
