# Moneyball V2
### Description
A repositroy to contain all code related to the micro internship project at Vela Partners.<br> The repository will contain key data loading, feature engineering, and modelling for the Moneyball V2 project.
### Contributors
Jirko
### Dependencies
To install all relevant dependencies use conda. Make sure to have conda installed and clone the repo. Open the terminal and navigate to the folder which contains the cloned files.
Then you can run: <br>

    conda env create -f dependecies.yml

To create the relevant conda environemnt. If you already have an evironemnt you wish to update run activate the environment and run: 

    conda env update -f  dependecies.yml

Finally to activate the environment run:

    conda activate VelaMoneyball

Alternatively activate the environemtn in your favourite IDE
### Usage
The project is split into three key .ipynb workbooks. dataLoading.ipynb loads the basic data and saves it, feature_exploration.ipynb gives the results relating to feature engineering and exploration presented in the paper Make sure to set the correct data path. LogRegmodelling.ipynb gives the key results on logistic regression. Finally Network.ipynb give the Neural network training results.