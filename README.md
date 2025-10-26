=========================================
#CROP YIELD PREDICTION (INTERACTIVE MODEL)
=========================================

PROJECT TITLE:
Crop Yield Prediction for Smart Farming using Machine Learning and Data Analytics

-----------------------------------------
PROJECT DESCRIPTION
-----------------------------------------
This project predicts crop yield based on environmental and soil parameters using
a trained machine learning model. It allows users to input various conditions such
as temperature, rainfall, humidity, and soil nutrients, and then provides a 
predicted yield value along with a yield classification (High or Low).

-----------------------------------------
REQUIREMENTS
-----------------------------------------
1. Python 3.8 or above
2. Required Python Libraries:
   - pandas
   - joblib
   - scikit-learn
3. Model File:
   - crop_yield_stacking_model.pkl (trained ML model)

-----------------------------------------
SETUP INSTRUCTIONS
-----------------------------------------
1. Open Google Colab or Visual Studio Code.
2. Make sure Python is installed on your system.
3. Install required packages if not already available by typing:
   pip install pandas joblib scikit-learn
4. Place your trained model file:
   crop_yield_stacking_model.pkl
   inside your project directory or upload it to Colab.

-----------------------------------------
STEPS TO EXECUTE
-----------------------------------------
1. Open the project script file:
   interactive_crop_yield_prediction.py
2. Edit the model_path variable in the script:
   Example:
   model_path = "/content/crop_yield_stacking_model.pkl"
   (Make sure the file name matches your uploaded model)
3. Modify input values if needed:
   Example:
   temperature = 41.2
   rainfall = 12.5
   humidity = 18.3
   soil_ph = 4.2
   nitrogen = 8
   phosphorus = 5
   potassium = 7
   crop_type = "maize"
   irrigation = "no"
   pesticide_use = "medium"
   soil_type = "sandy"
   season = "summer"
4. Run the script:
   - In Google Colab: Click ▶ Run cell
   - In VS Code or terminal: type
     python interactive_crop_yield_prediction.py
5. Wait for the output in the console.

-----------------------------------------
OUTPUT
-----------------------------------------
The program will display:
✅ Predicted Yield: <value> kg/ha
Yield Classification: High or Low

Example Output:
✅ Predicted Yield: 62.45 kg/ha
Yield Classification: High

-----------------------------------------
NOTES
-----------------------------------------
- Make sure the model file path is correct.
- If an error occurs, check that all required columns and data types
  match the training data used for the model.
- You can change the threshold value (default = 50) to classify High or Low yield
  based on your dataset's median yield.

-----------------------------------------
PROJECT DEVELOPED BY:
Your Name Here
-----------------------------------------
