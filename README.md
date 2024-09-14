<h1 align="center">CO2 emission prediction challenge 🌨️ </h1>

- The model was run as a Kaggle notebook in which datasets were saved

- Datasets: https://www.kaggle.com/datasets/ikeasamoahansah/co2-prediction-dataset/data

### 1. Setup

- Test and Train files could not be uploaded to GitHub due to their sizes
- Files can be found in the dataset link above
- Can be run straight from [kaggle](https://www.kaggle.com/code/ikeasamoahansah/test-features-emission-py)

### 2. Order

- The code should be run in the normal order (from top to bottom)
- The file to be used is the [final_submission.ipynb](final_submission.ipynb) file

### 3. Explanations of Features Used

- Missing data was imputed and Regressors were used to predict the missing values
- Log, Power and Other transformations were used to normalize the features in the training set.
- Other features were added based on location and rotated in degrees from some findings.
- Features were then gathered from all and grouped as top 50 best features
- These top 50 went further preprocessing and were trained
- Catboost and LGBM Regressors were used for final training along with some Ensemble methods

### 4. Environment

- The model was trained on kaggle with a GPU P100 by Nvidia (all free to use) can also be run on a CPU

### 5. Hardware

- A CPU or GPU is fine. GPU required for faster training time

### 6. Expected run time

- with a GPU: 2 hrs 45 mins
- only CPU: 7 hrs 30 mins
