# Calories_Burnt_Prediction
# Calories_Burnt_Prediction
Calories Burnt Prediction Using Machine Learning.ipynb
This Jupyter Notebook contains the full workflow for building the calorie prediction model. It includes steps like loading the datasets, cleaning and merging them, performing exploratory data analysis (EDA), engineering features, training machine learning models, and evaluating their performance. The notebook serves as the main development environment where the model is built and tested.

README.md
The README file provides a summary of the project, explaining its purpose, how it works, and how users can run it locally. It typically includes instructions on installing dependencies, launching the application, and using the model. This is essential for documentation, especially if the project is shared or hosted on GitHub.

app.py
This Python script is used to deploy the machine learning model as a web application. It likely uses Flask or Streamlit to provide a user interface where users can input data such as age, gender, exercise duration, etc., and get real-time predictions of calories burned. The app loads the saved model (pipeline_model.pkl) and routes input data through it to return predictions.

archive.zip
This ZIP archive most likely contains the original or backup versions of the dataset and other files. It is useful for storage or transport of the full project but is not typically used during runtime if its contents are already extracted and present in the working directory.

calories.csv
This CSV file contains the target variable — the number of calories burned — for each record. It’s used in combination with the exercise dataset to train a supervised learning model. It includes an ID column that likely corresponds to records in the exercise.csv file.

exercise.csv
This dataset includes input features such as user demographics (age, gender, height, weight) and workout-related metrics (duration, heart rate, body temperature). These features are essential for predicting calorie burn and are merged with calories.csv during preprocessing.

pipeline_model.pkl
This file contains the serialized (pickled) version of the trained machine learning pipeline. It includes preprocessing steps and the model itself, allowing for consistent and efficient predictions during deployment. The app script uses this file to make predictions without retraining the model.

requirements.txt
This text file lists all Python libraries required to run the project, such as pandas, scikit-learn, and Flask or Streamlit. Installing the requirements ensures that the development and deployment environments are consistent and compatible with the code.

GitHub Repository Link: https://github.com/ShreyashG63/Calories-Burnt-Prediction
Overleaf Link: https://www.overleaf.com/project/6824a2f866fb242a4265a353
Recording Link: https://drive.google.com/drive/folders/1DLcZ34luWQx1obQff3YFfvF067jlmyM4?usp=drive_link 
