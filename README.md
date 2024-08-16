<h1 align="center">Carbon dioxide (CO2) emission prediction challenge 🌨️ </h1>

## About

The objective of this challenge is to create machine learning and deep learning models that use open-source CO2 emissions data (from satellite observations) to predict carbon emissions.

The predictors for this challenge are from Sentinel-5P, an ESA satellite dedicated to monitoring air pollution. The target for this challenge is ground truth CO2 emissions collected from GRACED and EDGAR.

Approximately 800 locations were selected from 20 areas in South Africa, with a distribution around farm lands, cities and power plants.

The train set contains 361 locations and the test contains 137 locations. The test set is from a different province to the train set, to ensure your model is generalisable to different regions.

Seven main features were extracted weekly from Sentinel-5P from January 2019 to November 2022. Each feature (Sulphur Dioxide, Carbon Monoxide, etc) contain sub features such as column_number_density which is the vertical column density at ground level, calculated using the DOAS technique. You can read more about each feature in the below links, including how they are measured and variable definitions.

The sentinel 5p data provided was extracted from google earth engine. The following pollutants were extracted from their respective images.

## Resources

- [SulphurDioxide](https://developers.google.com/earth-engine/datasets/catalog/COPERNICUS_S5P_NRTI_L3_SO2?hl=en)
- [CarbonMonoxide](https://developers.google.com/earth-engine/datasets/catalog/COPERNICUS_S5P_NRTI_L3_CO?hl=en)
- [NitrogenDioxide](https://developers.google.com/earth-engine/datasets/catalog/COPERNICUS_S5P_NRTI_L3_NO2?hl=en)
- [Formaldehyde](https://developers.google.com/earth-engine/datasets/catalog/COPERNICUS_S5P_NRTI_L3_HCHO?hl=en)
- [UvAerosolIndex](https://developers.google.com/earth-engine/datasets/catalog/COPERNICUS_S5P_NRTI_L3_AER_AI?hl=en)
- [Ozone](https://developers.google.com/earth-engine/datasets/catalog/COPERNICUS_S5P_NRTI_L3_O3?hl=en)
- [Cloud](https://developers.google.com/earth-engine/datasets/catalog/COPERNICUS_S5P_OFFL_L3_CLOUD?hl=en)

More info on Sentinel 5p data can be found [here](https://developers.google.com/earth-engine/datasets/catalog/sentinel-5p).
