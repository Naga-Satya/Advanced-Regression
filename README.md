# Advanced-Regression
Built an advanced regression model for penalising models with larger feature count using Lasso and Ridge Regressoins

### Aim of building the Model:
 To predict the Sale Price for a household of the data with 80 different different attributes

### Analysis performed:
 1. Imputed missing values in continuous features by mean/median detection using boxplot analysis
 2. Imputed categorical missing values as follows: 
    (i) Meaningful missing imputation
    (ii)Frequent value imputation
 3. Normalised the target variable to gaussian ditribution
 4. Dropped highly Imbalanced features:
    (i) Highly skewed/imbalanced columns
    (ii)Highly missing valued columns
 5. Binning of less frequent categorical values of a respective column

### Model Built:
- Lasso regularised regression model to find the important features
- Ridge regression model to cross check the performace

#### Cross validation technique used: GridSearchCV
