# Model Evaluation and Validation
## Project: Spam Detection

### Install

This project requires **Miniconda/Anaconda** installed on your system:

<!-- - [NumPy](http://www.numpy.org/) -->
<!-- - [Pandas](http://pandas.pydata.org/) -->
<!-- - [matplotlib](http://matplotlib.org/) -->
<!-- - [scikit-learn](http://scikit-learn.org/stable/) -->
After successfully installing **Miniconda/Anaconda** on your system.

In the base environment, install jupyter notebook using conda package number.

Clone this repository on your system.

Navigate to this folder in the **Miniconda/Anaconda** shell.

Then, run conda env create -f environment.yml. This will create the required environment.

Launch the jupyter-notebook from the base environment and then select the environment in the notebook and
run the notebook **main.ipynb**

<!-- You will also need to have software installed to run and execute a [Jupyter Notebook](http://jupyter.org/install.html). -->

<!-- If you do not have Python installed yet, it is highly recommended that you install the [Anaconda](https://www.anaconda.com/download/) distribution of Python, which already has the above packages and more included. -->

### Files

<!-- Template code is provided in the `boston_housing.ipynb` notebook file. You will also be required to use the included `visuals.py` Python file and the `housing.csv` dataset file to complete your work. While some code has already been implemented to get you started, you will need to implement additional functionality when requested to successfully complete the project. Note that the code included in `visuals.py` is meant to be used out-of-the-box and not intended for students to manipulate. If you are interested in how the visualizations are created in the notebook, please feel free to explore this Python file. -->
dataset folder contains the dataset.

main.ipynb has all the code in it.

environment.yml contains the required production environment for the project.

### Results

Performance of Logistic Regression model with count vectorizer gives the best score.

roc_auc_score for the trained model on test data is 0.98.


<!-- ### Run

In a terminal or command window, navigate to the top-level project directory `boston_housing/` (that contains this README) and run one of the following commands:

```bash
ipython notebook boston_housing.ipynb
```
or
```bash
jupyter notebook boston_housing.ipynb
```
or open with Juoyter Lab
```bash
jupyter lab
```

This will open the Jupyter Notebook software and project file in your browser. -->

### Data

This data contains the document and the target which defines whether they are spam or not.

**Features**

1. `text`: This contains the text document.


**Target Variable**
<!-- 4. `MEDV`: median value of owner-occupied homes -->

2. `positively_rated [target variable for prediction]`

        0 = Not Spam

        1 = Spam