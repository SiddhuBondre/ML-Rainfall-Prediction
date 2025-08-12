# 🌧️ Rainfall Prediction using Machine Learning

# 📌 Objective

The objective of this project is to predict whether it will rain using daily recorded weather data.
We use a Random Forest Classifier to learn patterns between meteorological parameters and rainfall occurrence.

# 📂 Dataset
Source: Custom daily weather observations

Format: CSV file with the following columns:

day

pressure

maxtemp

temparature

mintemp

dewpoint

humidity

cloud

rainfall

sunshine

winddirection

windspeed

 # Workflow
 
# Data Preprocessing

Load the CSV file into Pandas DataFrame

Handle missing values (if any)

Encode categorical columns (rainfall as 0/1)

Normalize/scale features if needed

# Exploratory Data Analysis

Visualize distribution of pressure, temperature, humidity

Check correlation between features and rainfall

# Model Building

Train-test split (e.g., 80-20)

Apply Random Forest Classifier

Tune hyperparameters (n_estimators, max_depth, min_samples_split, min_samples_leaf)

# Evaluation

Accuracy

Precision, Recall, F1-score

Confusion matrix

Feature importance plot


# 🛠️ Technologies Used

Python 3.x

Libraries:

pandas, numpy → Data handling

matplotlib, seaborn → Visualization

scikit-learn → Random Forest & evaluation

# 📊 Example Results

| Metric    | Value |
| --------- | ----- |
| Accuracy  | 0.85  |
| Precision | 0.86  |
| Recall    | 0.84  |
| F1 Score  | 0.85  |

