# Iris Flower Classification Using SVM

## Project Overview
This project implements an Iris flower classification model using Support Vector Machines (SVM). The Iris dataset contains 150 samples with four features — Sepal Length, Sepal Width, Petal Length, and Petal Width — across three species: *Iris-setosa*, *Iris-versicolor*, and *Iris-virginica*.

The goal is to train an SVM model to classify iris flowers based on these features.

## Dataset
- **Source:** Iris Flower Dataset
- **Features:**
  - Sepal Length (cm)
  - Sepal Width (cm)
  - Petal Length (cm)
  - Petal Width (cm)
- **Target:** Species (Setosa, Versicolor, Virginica)

## Project Structure
```
├── iris_flower_details.csv          # Dataset
├── iris_classification.ipynb        # Jupyter Notebook with code
├── requirements.txt                 # List of required libraries
└── README.md                        # Project documentation
```

## Data Preprocessing
- Dropped the 'Id' column
- Checked for and handled duplicate entries
- Addressed outliers using the Interquartile Range (IQR)
- Scaled features using StandardScaler

## Exploratory Data Analysis
- Correlation heatmap
- Pairplots and boxplots to visualize feature distributions
- Computed class-wise average feature values

## Model Training & Evaluation
- Split data into training (70%) and testing (30%) sets
- Trained an SVM model using `sklearn`
- Evaluated with accuracy score and confusion matrix

### Results:
- High accuracy in classifying iris species
- Visualized performance with a confusion matrix

## Visualizations
- Feature distributions
- Average feature values per species

## How to Run the Project
1. Clone the repository:
   ```bash
   git clone <repo-url>
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook iris_classification.ipynb
   ```

## Future Improvements
- Try other classifiers (Random Forest, KNN)
- Fine-tune SVM hyperparameters using GridSearchCV
- Expand EDA with more feature engineering

---
Feel free to customize this further! Want me to add more sections or polish anything? Let me know! 

