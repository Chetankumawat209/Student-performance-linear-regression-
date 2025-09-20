# Student Performance — Regression Models

I Created two Jupyter notebooks that explore a student performance dataset and train tree-based regression models to predict students performance

## Files / Notebooks
  ### Analysis dataset.ipynb  
   1. Exploratory Data Analysis (EDA)
   2. Visualizations: boxplots 
 
### Train Model.ipynb  

  Prepares features and target: <br>
        X = df.drop("Performance Index", axis=1) <br>
        y = df["Performance Index"]
  Train/test split
  
### Models trained and compared:
  1. DecisionTreeRegressor() (default)
  2. DecisionTreeRegressor(max_depth=4) with plot_tree(...)
  to visualize the tree RandomForestRegressor()
    
  Evaluate models

## Dataset (columns observed)
  1. Hours Studied (numeric)
  2. Previous Scores (numeric)
  3. Extracurricular Activities (categorical: Yes/No)
  4. Sleep Hours (numeric)
  5. Sample Question Papers Practiced (numeric)
  6. Performance Index (numeric — target)

## Tech Stack
  1. Python
  2. Pandas
  3. Scikit-learn
  4. Matplotlib / Seaborn

## How to run
# Clone the repo
    git clone https://github.com/Chetankumawat209/Student-performance-linear-regression-.git
