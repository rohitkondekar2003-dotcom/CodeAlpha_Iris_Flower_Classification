# Iris Flower Classification
## About the Project
This project is part of my CodeAlpha Data Science Internship.
In this project, I used machine learning to classify Iris flowers into three species: Setosa, Versicolor and Virginica.
The classification is based on four measurements:
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width
I used the K-Nearest Neighbors (KNN) algorithm for classification.

## Dataset
The dataset contains 150 records of Iris flowers.
The columns in the dataset are:
- Id
- SepalLengthCm
- SepalWidthCm
- PetalLengthCm
- PetalWidthCm
- Species
The Id column was removed because it is only an identifier.

## Tools and Libraries
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## Project Steps
### 1. Load the Dataset
The Iris dataset was loaded using Pandas and the data was checked to understand its structure.

### 2. Data Checking
The dataset was checked for missing values and other basic information.
There were no missing values in the dataset.

### 3. Data Preprocessing
The Id column was removed because it does not help in classifying the flower species.
The four flower measurements were used as input features.

### 4. Train-Test Split
The dataset was divided into training and testing data.
- Training data: 80% (120 records)
- Testing data: 20% (30 records)

### 5. Feature Scaling
StandardScaler was used to scale the numerical features before applying the KNN algorithm.

### 6. KNN Model
K-Nearest Neighbors was used as the machine learning algorithm.
The model was created with 5 neighbors.

### 7. Prediction
The trained model was used to predict the species of the flowers in the test dataset.

### 8. Model Evaluation
The model achieved **100% accuracy** on the test dataset.
All 30 test records were classified correctly.

## Visualization
A pairplot was created to visualize the relationships between the different Iris flower measurements and species.
The visualization helps understand how the three Iris species differ based on their measurements.

## Key Findings
- The dataset contains 150 Iris flower records.
- There are three Iris species.
- Four numerical features were used for classification.
- The Id column was removed.
- StandardScaler was used for feature scaling.
- KNN was used for classification.
- The model achieved 100% accuracy.
- All 30 test records were correctly classified.

## What I Learned
Through this project, I learned how to:
- Load and inspect a dataset using Pandas
- Prepare data for machine learning
- Select features and target variables
- Split data into training and testing sets
- Apply feature scaling
- Build a KNN classification model
- Evaluate model performance
- Create visualizations

## Conclusion
The project successfully developed a K-Nearest Neighbors classification model for Iris flower classification.
The workflow included data exploration, preprocessing, feature scaling, train-test splitting, model training, prediction, model evaluation, and visualization.
The model achieved 100% accuracy on the test dataset, demonstrating successful classification of the three Iris flower species.

## Files in this Repository
- `Iristask (3).ipynb` - Jupyter Notebook containing the code, outputs and graphs
- `iris_data.csv` - Dataset used for the project
- `README.md` - Project explanation

## Internship
This project was completed as part of my CodeAlpha Data Science Internship.
