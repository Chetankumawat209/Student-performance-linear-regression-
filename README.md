# Student Performance — Regression Models

I Created two Jupyter notebooks that explore a student performance dataset and train tree-based regression models to predict students performance

## Files / Notebooks
  ### Analysis dataset.ipynb  
     1. Exploratory Data Analysis (EDA)
     2. Visualizations: boxplots 
 
### Train Model.ipynb  

  Prepares features and target:
        X = df.drop("Performance Index", axis=1)
        y = df["Performance Index"]
  Train/test split
  
  Models trained and compared:
      DecisionTreeRegressor() (default)
      DecisionTreeRegressor(max_depth=4) with plot_tree(...)
      to visualize the tree RandomForestRegressor()
      
  Evaluate models

## Dataset (columns observed)
     Hours Studied (numeric)
     Previous Scores (numeric)
     Extracurricular Activities (categorical: Yes/No)
     Sleep Hours (numeric)
     Sample Question Papers Practiced (numeric)
     Performance Index (numeric — target)

## How to run
# Clone the repo
git clone https://github.com/Chetankumawat209/Student-performance-linear-regression-.git
