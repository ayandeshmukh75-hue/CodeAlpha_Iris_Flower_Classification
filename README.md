
# Iris Flower Classification Using Machine Learning

 1. Introduction

This is one of my machine learning projects, where I have built a model to classify Iris flowers into different species based on their measurements.

The Iris flower dataset contains information about three species: Iris-setosa, Iris-versicolor, and Iris-virginica. Each flower has four important measurements: sepal length, sepal width, petal length, and petal width.

In this project, I used Python and machine learning libraries to understand the dataset, visualize the measurements, train a classification model, and predict the species of a flower using its measurements.

I worked on this project to improve my understanding of machine learning and learn how a model makes predictions from data.

 2. Project Objectives

The main objectives of this project are:

- To understand and explore the Iris flower dataset.
- To learn how to work with CSV files using Python.
- To analyze flower measurements using graphs and visualizations.
- To divide the dataset into training and testing data.
- To build a machine learning classification model.
- To evaluate the model using different performance metrics.
- To predict the species of a new flower using its measurements.

 3. Dataset Description

For this project, I used the Iris dataset stored in a CSV file named `Iris.csv`.

The dataset contains 150 records and 6 columns. It includes measurements of flowers belonging to three different Iris species.

The columns in the dataset are:

| Column Name | Description |
|---|---|
| Id | Unique identifier for each record |
| SepalLengthCm | Length of the sepal in centimetres |
| SepalWidthCm | Width of the sepal in centimetres |
| PetalLengthCm | Length of the petal in centimetres |
| PetalWidthCm | Width of the petal in centimetres |
| Species | Name of the Iris flower species |

The `Id` column is not used for training because it only identifies each record. The four measurement columns are used as input features, and the `Species` column is used as the target variable.

 4. Technologies and Libraries Used

I used the following technologies and libraries to complete this project:

- **Python:** Used to write the program and implement the machine learning model.
- **Pandas:** Used to load, organize, and analyze the dataset.
- **NumPy:** Used for numerical operations.
- **Matplotlib:** Used to create graphs and visualize data.
- **Seaborn:** Used to create statistical visualizations.
- **Scikit-learn:** Used for splitting the dataset, training the model, and evaluating its performance.
- **Google Colab:** Used as the environment to write and run Python code without installing everything locally.

 5. Project Workflow

I followed these steps while building the project:

1. Loaded the Iris dataset from the CSV file.
2. Checked the dataset structure, column names, and missing values.
3. Explored the data using statistical summaries.
4. Created graphs to compare flower measurements and species.
5. Selected the input features and target variable.
6. Divided the dataset into training and testing sets.
7. Trained the Random Forest classification model.
8. Evaluated the model using accuracy, precision, recall, F1-score, and a confusion matrix.
9. Tested the model by entering measurements of a new flower.

This workflow helped me understand the basic process of building a machine learning classification model.

 6. Data Visualization

I created different graphs to understand the dataset better.

### Species Distribution

This graph shows the number of records belonging to each Iris species. It helps in understanding the distribution of classes in the dataset.

### Petal Length vs Petal Width

This scatter plot compares petal length and petal width for the three species. It helps visualize how their measurements differ.

### Measurement Comparison

I also used box plots to compare sepal length, sepal width, petal length, and petal width across the three species.

These visualizations helped me explore the data before training the model.

 7. Machine Learning Algorithm

For classification, I used the Random Forest Classifier provided by Scikit-learn.

Random Forest is a machine learning algorithm that combines multiple decision trees to make a prediction. Each tree makes a prediction, and the final class is selected based on the trees' votes.

I selected this algorithm to learn how an ensemble-based classification model works.

The model uses the four flower measurements to predict one of the following species:

- Iris-setosa
- Iris-versicolor
- Iris-virginica

 8. Training and Testing

Before training the model, I divided the dataset into two parts:

- **Training data:** 80% of the dataset, used to train the model.
- **Testing data:** 20% of the dataset, used to evaluate the trained model on records it did not see during training.

The dataset contains 150 records, so 120 records are used for training and 30 records for testing.

I used `train_test_split()` from Scikit-learn to perform this division.

 9. Model Evaluation

After training the model, I used the testing data to check its performance.

The following metrics were used:

- **Accuracy:** Measures the proportion of correct predictions.
- **Precision:** Measures how many predictions for a particular species were correct.
- **Recall:** Measures how many actual examples of a species were correctly identified.
- **F1-score:** Combines precision and recall into a single metric.
- **Confusion Matrix:** Shows the relationship between actual species and predicted species.

The actual evaluation results are generated when the notebook is executed. The accuracy value and other results can be added here after running the code.

 10. Prediction on New Data

One of the useful features of this project is that the trained model can predict the species of a new flower.

The user enters four measurements:

- Sepal length
- Sepal width
- Petal length
- Petal width

The model processes these values and predicts the most likely Iris species.

For example, measurements of 5.1 cm sepal length, 3.5 cm sepal width, 1.4 cm petal length, and 0.2 cm petal width are expected to be classified as Iris-setosa.

This demonstrates how a trained machine learning model can be used to make predictions on new input data.

 11. How to Run the Project

Follow these steps to run the project:

1. Open Google Colab in your browser.
2. Create a new notebook or open the project notebook.
3. Upload the `Iris.csv` dataset.
4. Run the code cells in the correct order.
5. View the dataset information and visualizations.
6. Train the Random Forest model.
7. Check the accuracy and confusion matrix.
8. Enter new flower measurements to test the prediction.

Make sure the CSV file is uploaded before running the cell that loads the dataset.

 12. Learning Outcomes

While working on this project, I learned several important concepts:

- How to load and analyze a dataset using Pandas.
- How to identify input features and a target variable.
- How to visualize data using Matplotlib and Seaborn.
- How training and testing data are used in machine learning.
- How a Random Forest Classifier works at a basic level.
- How to evaluate a classification model.
- How to use a trained model to predict new data.

This project gave me practical experience with Python and introduced me to the basic workflow used in machine learning projects.

 13. Future Improvements

There are several ways this project can be improved in the future:

- Compare Random Forest with Logistic Regression, Decision Tree, K-Nearest Neighbors, and Support Vector Machine.
- Build a simple web interface where users can enter flower measurements.
- Add more visualizations to understand the dataset.
- Save the trained model so it can be reused without training it every time.
- Improve the user interface and make predictions easier to understand.

These improvements would help extend the project beyond a basic notebook.

 14. Conclusion

Through this project, I explored how machine learning can be used to classify Iris flowers based on their physical measurements.

I worked with the dataset, created visualizations, trained a Random Forest Classifier, and evaluated its predictions using different performance metrics. I also implemented a way to predict the species of a new flower by entering its measurements.

Overall, this project helped me understand the practical steps involved in a machine learning classification problem and gave me a foundation for working on more advanced data science projects in the future.

