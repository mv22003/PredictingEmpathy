# Predicting empathy score using eye-tracker data
In this repository you will find the following:


1. test_rawdata --> Zip file with the raw data of 30 participants, this data was collected from the [EyeT4Empathy dataset](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9719458/).
2. control_rawdata --> Zip file with the raw data of 30 participants, this data was collected from the [EyeT4Empathy dataset](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9719458/).
3. questionnaries --> Zip file with two questionnaries before and after the task performed by the participants. This data contains the empathy scores we are predicting.

This datasets can be found [here](https://drive.google.com/drive/folders/1SlvDzPxx-vHP3nCmTyEXrUPao6pRYPcA?usp=share_link).

4. feature_extraction.py --> Python function to preprocess the data and create a matrix to predict the empathy score using regression models.
5. regression_models.ipynb --> Jupyter Notebook were we call our matrix and perform several regression models and compare them to a dummy regressor to understand the performance of each. 
