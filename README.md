# Netflix Audience Rating Classification

## Project Overview

This project focuses on building a Machine Learning classification model that predicts the audience rating of Netflix titles based on available content features.

It is **Task 3: Netflix Audience Rating Classification Model**, completed as part of the Machine Learning Internship at Auspify Technologies.

The project uses supervised Machine Learning techniques to classify Netflix movies and TV shows into audience rating categories.

## Objective

The main objective is to develop and evaluate classification models that predict the audience rating of a Netflix title using features such as content type, release year, duration, country, and genre.

## Dataset

The project uses a Netflix dataset stored in `Dataset.csv`.

The dataset contains information about Netflix titles, including:

* `show_id`: Unique identifier for each title.
* `type`: Whether the title is a Movie or TV Show.
* `title`: Title name.
* `director`: Director of the title.
* `country`: Country associated with the title.
* `date_added`: Date the title was added to Netflix.
* `release_year`: Original release year.
* `rating`: Audience rating category (target variable).
* `duration`: Movie duration or number of seasons.
* `listed_in`: Genres and categories.

## Technologies and Libraries

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Jupyter Notebook

## Project Workflow

### 1. Data Loading and Exploration

* Loaded the Netflix dataset using Pandas.
* Examined dataset dimensions, column names, and data types.
* Checked missing values and duplicate records.
* Analyzed the distribution of audience ratings.

### 2. Data Preprocessing

* Removed records with missing target ratings.
* Handled missing values in feature columns.
* Extracted numerical values from the duration column.
* Prepared categorical and numerical features for modeling.

### 3. Feature Engineering

Selected features for the initial model:

* Content type
* Release year
* Duration
* Genre and category information
* Country

Applied one-hot encoding to convert categorical features into numerical representations.

### 4. Model Training

Trained classification models using a training dataset:

* Random Forest Classifier
* Logistic Regression

The dataset was divided into training and testing sets using an 80/20 split.

### 5. Model Evaluation

Evaluated the models using:

* Accuracy
* Precision
* Recall
* F1-score
* Confusion matrix

Compared model accuracy to understand their classification performance.

### 6. Data Visualization

Created visualizations to explore the rating distribution, analyze classification results, and compare model performance.

## Results

Model performance is evaluated using the test dataset.

**Random Forest Accuracy:** To be added after running the notebook.

**Logistic Regression Accuracy:** To be added after running the notebook.

The final results and observations will be updated based on the actual model evaluation.

## Project Structure

```text
Task_3_Netflix_Audience_Rating_Classification/
│
├── Task_3_Netflix_Audience_Rating_Classification.ipynb
├── Dataset.csv
├── README.md
└── screenshots/
    ├── rating_distribution.png
    ├── confusion_matrix.png
    └── model_comparison.png
```

## How to Run the Project

1. Clone or download the project repository.

2. Ensure Python is installed.

3. Install the required libraries:

   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn
   ```

4. Place `Dataset.csv` in the appropriate project directory.

5. Open the notebook using Jupyter Notebook or Visual Studio Code.

6. Run the notebook cells in order to train and evaluate the models.

## Skills Demonstrated

* Data exploration and preprocessing
* Feature engineering
* Multiclass classification
* Random Forest
* Logistic Regression
* Model training and evaluation
* Classification metrics
* Data visualization
* Python and Scikit-learn

## Internship

**Program:** Machine Learning Internship
**Organization:** Auspify Technologies
**Task:** Task 3, Netflix Audience Rating Classification Model

This project helped develop practical experience with supervised Machine Learning, multiclass classification, and model evaluation.
