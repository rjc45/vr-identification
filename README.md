# vr-identification

Download Jupyter notebook
Navigate to folder
Call one of the following command to open up browser UI
```
jupyter notebook
python3 -m notebook
```

At the top of every ipynb there should be a path to the summer database
```
con = sqlite3.connect('../summer')
```
Point this relative path to the database to connect



* baseline_nn.ipynb - basic neural network (~31% accuracy)
* baseline_nn_visualizations.ipynb - visualizations for baseline nn models
* feature_engineering.ipynb - feature engineering for neural network (sliding windows, etc)
* feature_engineering.txt - list of current 144 features and notes for future features
* data_processing.ipynb - sandbox for building features, pulling data
