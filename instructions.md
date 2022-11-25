# Assessment

You are given a dataset to predict cognitive test scores of preschoolers given characteristics of their mothers.

Data dictionary:

* i - mother's IQ
* a - mother's age at child's birth
* h - indicator showing whether mother completed high school (1=True, 0=False)
* w = 1: mother did not work in first three years of child’s life
* w = 2: mother worked in second or third year of child’s life
* w = 3: mother worked part-time in first year of child’s life
* w = 4: mother worked full-time in first year of child’s life
* score - child's IQ (regressand)

**Tasks:**
1. Prepare the data, rename variables as you see fit and justify. Propose the types of data for each variable (python data types).
2. Transform the data so it's easy to analyze - describe what you did and why
3. Perform the exploratory data analysis
4. Perform a linear regression where the regressand is child's IQ
    1. using a single predictor
    2. using multiple predictors
    3. using multiple predictors with an interaction term
    
    For each case, explain your model, model assumptions and how to interpret the regression coefficients.
    
For each task please provide suitable markdown comments and visualizations supporting your work including model diagnostics and evaluation.

You may use any openly available software you need. Present you work in a form of a Jupyter notebook with comments in the markdown cells.
Please upload your ready work to your public github repository and share the link to it with the HR representative.