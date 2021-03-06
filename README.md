# bengalore-house-price-prediction

# Data:
  The train and test data will consist of various features that describe that property in Bengaluru.
  Each row contains fixed size object of features. There are 9 features and each feature can be accessed by its name.
  
# Features:

  Area_type – describes the area
  Availability – when it can be possessed or when it is ready(categorical and time-series)
  Location – where it is located in Bengaluru (Area name)
  Size – in BHK or Bedroom (1-10 or more)
  Society – to which society it belongs
  Total_sqft – size of the property in sq.ft
  Bath – No. of bathrooms
  Balcony – No. of the balcony

# Target variable:

  Price – Value of the property in lakhs(INR)
  
# Train dataset:

  Contains all the features and target variable.
  
# Test dataset:

  Contains all the features.
  
# Problem statement:

With the given features and after editing it a model has build to predict the price of houses in Bengaluru.

# Evaluation Metric:

Root-Mean-Squared-Error (RMSE) between the logarithm of the predicted price value and the logarithm of the observed sales price.
Taking logs means that errors in predicting expensive houses and cheap houses will affect the result equally.
