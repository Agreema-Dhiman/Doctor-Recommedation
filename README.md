The Doctor_Recommendation.ipynb allows training a model on the dataset containing symptoms relevant to a particular speciality doctor. 
The dataset https://www.kaggle.com/datasets/kaushil268/disease-prediction-using-machine-learning?select=Training.csv has been modified to make healthcaredoctors.csv for this model. healthcaredoctors.csv has 431 instances and 133 columns.
The prognosis column in the original dataset has been changed to the corresponding speciality. For Example, the prognosis of migraine is mapped to the speciality doctor- Physician. The model is trained using SVM algorithm. The requirements to run the file .ipynb in Google Colab:
1. Upload the Notebook to Google Colab
2. Upload healthcaredoctors.csv to the session storage.
You will be able to execute all the cells.
