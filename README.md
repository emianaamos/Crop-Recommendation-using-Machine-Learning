# Crop-Recommendation-using-Machine-Learning

Digital Farming and Precision Agriculture allow precise utilization of inputs like seed, water, pesticides, and fertilizers at the right time to the crop for maximizing productivity, quality and yields. By deploying sensors for data collection and mapping fields, farmers can understand their field in a better way conserve the resources being used and reduce adverse effects on the environment. Most of the farmers practice traditional farming patterns to decide crops to be cultivated in a field. However, the farmers do not perceive crop yield is interdependent on soil characteristics and climatic conditions. Thus, our Digital Farming solution can propose a crop recommendation system that helps farmers to decide the right crop to sow in their field based on the weather condition, moisture and season. Machine learning techniques provide an efficient framework for data-driven decision making. This Application also helps in determining the best pesticide, seed spacing and seed depth using the ML recommendation engine.


# Data collection
The data relating to the soil nutrition are collected from soil testing historical data which provides general crop data. The major crops like wheat, rice, bajra, maize and jowar and minor crops like pulses, gram, jute, cotton, groundnut, barley, ragi, mustard, sugarcane, sesame, and sunflower are considered in the model.
The important features of the dataset are of soil type Sandy, Silt, Clay and Loamy Soil, pH value of the Soil is a measure of the acidity and alkalinity in soils, NPK content of the soil which is nitrogen, phosphorus and potassium are the three nutrients used by plants, Permeability of the soil is the property to transmit water and air, the water content in the soil, average rainfall, temperature and previously harvested crop. All these parameters are really important to determine the best crop for current weather, market demand and availability of market infrastructure, expected profit and risk.


# Machine Learning Techniques

Using datasets from multiple sources, large non-linear problems could be easily solved by machine learning techniques. ML enables better decision making with minimal human intuition in real-world scenarios. It provides a powerful framework for historical data-driven decision making.
For this solution we have used the Decision Tree Classifier  and KNeighbors Classifier (KNN) Machine Learning algorithm, it is highly preferred by many as it produces significant accuracy with less computation power.  Here classification of crop type and crop weed can be achieved by using both KNN and DTC.
