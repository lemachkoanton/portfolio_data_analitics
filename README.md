The goal of the project was to predict student churn from the online course.

There are two datasets at the input. The first one contains data about the actions students perform with the steps. The second contains data about the times and statuses of the sabmits to the practical assignments.

The first notebook, called data_analisis_and_preparation, prepares the data for further analysis. The output is an "X" dataset, which contains the most important features about the students during the first "n" (1 to 7) days of the course and a "y" column, which tells whether the user will graduate or leave the course. This data is saved in the prepared_data_on_student_outflows folder.

The second notebook, called analisis_of_student_outflow, uses various machine learning models to predict student outflow.