INSTRUCTIONS TO RUN THE CODE
============================

1. PREREQUISITES
----------------
Ensure you have Python 3.8+ installed.
The code requires the following data files to be present in a 'data' directory relative to the notebook:
- data/office_train.csv
- data/office_test.csv

2. INSTALLATION
---------------
Install the required packages using pip:

    pip install -r requirements.txt

3. RUNNING THE CODE
-------------------
The solution is provided as a Jupyter Notebook (sol_0885.ipynb).

To run it:
1. Open a terminal or command prompt.
2. Navigate to this directory.
3. Launch Jupyter Notebook:
    
    jupyter notebook

4. Open 'sol_0885.ipynb' from the Jupyter interface.
5. Click "Cell" -> "Run All" to execute the entire pipeline.

4. OUTPUT
---------
The notebook will:
- Load and preprocess the data.
- Perform feature engineering and selection.
- Train a Stacking Ensemble model (CatBoost, XGBoost, LightGBM).
- Generate predictions for the test set.
- Save the submission file to 'data/submission.csv'.
