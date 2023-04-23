# SC1015-DSAI-project
Mini project for SC1015 in NTU. Our team decided to choose a [dataset on diabetes](https://www.kaggle.com/datasets/alexteboul/diabetes-health-indicators-dataset)
## Defining the Problem
Diabetes is a medical condition where the body does not produce enough insulin to break down glucose. With over 37 million people in the US having diabetes, and 20% of that not knowing that they have diabetes.
What we want is to predict the risk of a person having diabetes based on their current lifestyle and health condition
## Flow of the Program
Read the files (Jupyter Notebook) in order for a better experience
1. [Data Preparation](https://github.com/songtian17/SC1015-DSAI-project/blob/main/Data_Preparation.ipynb)
2. [Exploratory Data Analysis](https://github.com/songtian17/SC1015-DSAI-project/blob/main/EDA.ipynb)
3. [Feature Selection](https://github.com/songtian17/SC1015-DSAI-project/blob/main/Feature_Selection.ipynb)
4. [Model Fitting for Selected Factors](https://github.com/songtian17/SC1015-DSAI-project/blob/main/Model_Fitting_Limited_Column.ipynb)
5. [Model Fitting for All Factors](https://github.com/songtian17/SC1015-DSAI-project/blob/main/Model_Fitting_All_Column.ipynb)
## Models Used
- Random Forest
- Decision Tree
- K Nearest Neighbour
- Neural Network
## Final Thoughts
- Bad lifestyle/heath conditions tend to lead to a higher risk of getting diabetes
- Neural network seems to have the best accuracy among the four models used
- Some factors can affect the risk of getting diabetes more than others
## New things we've learnt
- Using Chi-squared test to obtain Cramer’s V value
- Random Forest and how it works
- K Nearest Neighbour and how it works
- Neural Network and how it works
## Contribution
- Song Tian - Data Preparation, EDA and Feature Selection
- Khai Thung - Presentation Slides, Script Preparation and Video Recorder and Presenter
- Eugene Tan - Model Fitting (All ML models)
## References
- https://www.cdc.gov/diabetes/basics/quick-facts.html
- https://www.kaggle.com/code/bayunova/diabetes-health-indicators
- https://www.kaggle.com/datasets/alexteboul/diabetes-health-indicators-dataset
- https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html
- https://scikit-learn.org/stable/modules/generated/sklearn.neighbors.KNeighborsClassifier.html
- https://stackoverflow.com/questions/20892799/using-pandas-calculate-cram%C3%A9rs-coefficient-matrix
- https://www.tensorflow.org/guide/keras/sequential_model
