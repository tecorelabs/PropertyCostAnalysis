# Property Cost Prediction/Analysis
    This model is based on analysis of property cost according to location and size of property Scikit learn.

# Goal of The Model
    The main goal to develop this model is to predict cost of property according location, area, size and availability of bathrooms. The dataset contains a sample of 13321 records of Bengaluru House Price Data.
    
# Descriptions of File
   In Bengaluru House Data file every entity has several fields such as area types, availability, location, size, society, total_Sqft,        price etc. 

# Dataset
    Data set can be download from [https://www.kaggle.com/amitabhajoy/bengaluru-house-price-data] 
 
# Dataset Mount From
    from google.colab import drive
    drive.mount('/content/drive')
   
# DataSet Train:
    from sklearn.model_selection import train_test_split
    from sklearn.linear_model import LinearRegression
    from sklearn.model_selection import ShuffleSplit
    from sklearn.model_selection import cross_val_score

# Algo Used
    Algorithm Used 
    GridSearchCV
    Lasso
    sklearn.tree 
    DecisionTreeRegressor


# Requirements
    Python 3.5 and above version (I build it in google colab Jupyter Notebook 3)
# Python Libraries/Package Needed:
    Pandas 0.25.0
    Numpy 1.8
    Scikit-learn 0.22.1
    Matplotlib 3.1.2
    
