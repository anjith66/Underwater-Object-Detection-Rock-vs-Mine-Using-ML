Sonar Rock vs. Mine Prediction
This project is a Machine Learning-based classification system that analyzes sonar data to distinguish between Rocks and Naval Mines. It is designed to assist in underwater object detection by processing frequency-based signal data.

🚀 Overview
The detection of underwater mines is a hazardous task where precision is critical. This project uses a Logistic Regression model to classify sonar signals reflected off various surfaces. The data consists of sonar chirps returned from either a metal cylinder (mine) or a rock.

📊 Dataset
The project uses a sonar dataset consisting of:

Total Samples: 208.

Features: 60 numerical columns representing the energy of the sonar signal at different frequency bands.

Labels: 111 Mines (M) and 97 Rocks (R).

🛠️ Technical Stack
Language: Python

Libraries:

Pandas & NumPy for data manipulation.

Scikit-learn for model building and evaluation.

🧠 Model Architecture
The project follows a standard Machine Learning pipeline:

Data Loading: Reading the sonar data from CSV format.

Statistical Analysis: Using describe() and groupby() to understand data distribution.

Data Splitting: Splitting the 208 samples into training and testing sets using train_test_split with stratify=Y to ensure balanced classes.

Model Selection: Training a Logistic Regression model.

Evaluation: Measuring success using accuracy_score.

📈 Results
The model was evaluated on both training and test data:

Training Accuracy: ~83.4%.

Test Accuracy: ~76.2%.
