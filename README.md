# Final_year_project
Crop Yield Prediction System using Machine Learning

Crop Yield Prediction is the methodology to predict the yield of the crops using different parameters like rainfall, temperature, fertilizers, pesticides, ph level, and other atmospheric conditions and parameters. 

Methodology: 
•	The proposed system will check soil quality and predict the cop yield accordingly along with it provide fertilizer recommendation if needed depending upon the quality of soil.
•	The system takes inputs, pH value (based on percentage of nutrient) and location from the user. Result processing is done by two controllers. 
•	Location is used as an input to controller 1, along with the use of third party applications like APIs for weather and temperature, type of soil, nutrient value of the soil in that region, amount of rainfall in the region, soil composition can be determined. 
•	pH value is given as an input to controller 2, from which alkalinity of the soil is determined. Along with it, percentage of nutrients like Nitrogen(N), Phosphorous(P), Potassium(K), Sulphur (S), Magnesium (Mg), Calcium (Ca), Iron (Fe), Manganese, Boron and Zinc and Organic matter can be obtained. 
•	The result of the controller 1 and controller 2 are compared with a predefined “nutrients” data store. These compared results are supplied to controller 3 wherein the combination of the above results and the predefined data set present in the crop data store is compared. 
•	Finally, the results are displayed in the form of bar graphs along with accuracy percentage. 
