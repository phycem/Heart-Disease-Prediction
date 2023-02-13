
# Heart Disease Prediction

This is the folder for Heart Disease Prediction modeling and data analysis.

It contains 
* requirements.txt
* Heart Disease Prediction.ipynb where there are data analysis and model comparisons (with the code changed to save the new model, it is called Heart Disease Prediction_small_edit.ipynb)
* heart_disease_production.py 
* finalized model.csv where model is saved 
* deploy.py for production code NOTE: the production code needs some fixes to work well which I am currently working on.

To run the production code:

Dataset should have these column names: 'age', 'trtbps', 'thalachh', 'oldpeak','sex', 'cp', 'restecg', 'exng', 'slp', 'caa', 'thall','o2Saturation'
It should be csv file , otherwise this code will be crushed.


* Download this folder. 
* please name the csv file as demo.csv
* Upload your csv file for data input. 
* run pip install -r requirements.txt in your shell and download all libraries in requirements.txt
* Get predictions from prediction.csv



NOTE:  I noticed the model I saved on finalized_model.sav is an old version I found in my Heart_Disease_Prediction_small_edit.ipynb .
 

* Please use the correct_finalized_model.sav for production code. Before you do, change its name to finalized_model.sav .
NOTE: the production code needs some fixes to work well which I am currently working on.
