# Short-Term-Solar-Irradiance-forecasting-using-machine-learning
**Data Extraction**:

Extract .nc format files and labeled data from the provided dataset.

**Data Cleaning**:

Clean the data by removing duplicate files from the .nc file folders to ensure accuracy and consistency.

**Feature Extraction**:

Extract relevant features from the .nc files that are essential for predicting Global Horizontal Irradiance (GHI). These features include:

Solar Radiation

Solar Angles (e.g., Sun Azimuth and Sun Elevation)

Satellite Bands (e.g., MIR)

Grey Count

**GHI Data Extraction**:

Extract the GHI values for the three months (June to August) and sep from the provided Excel sheet.

**Model Training**:

Train machine learning models using the extracted features and labels (GHI values) for the months of June, July, and August.

**Prediction**:

Use the trained models to predict GHI values for the month of September.

**Model Evaluation**:

After evaluating multiple models, Linear Regression performed the best in terms of prediction accuracy compared to other machine learning models.
