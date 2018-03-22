# udacity_ml_project
Udacity Capstone project

## Synopsis

Investment and Trading Project is my submission for the Udacity capstone project. As part of this project, I will attempt to use a deep neural network (specifically LSTM) to predict closing-price of a stock.

## Libraries used

Apart from the standard deep neural network libraries of Keras, Pandas, Numpy, Sklearn, matplotlib I use

quandl - to download stock data

stockstats - tool to readily create statistics from stock data frame

seaborn - statistical data visulization

## Installation
conda install -c anaconda quandl

pip install seaborn

pip install stockstats

## File description
### Files to review for final submission
ProjectProposal.pdf - Capstone project proposal

ProjectReport.pdf - Capstone project report

capstone_ipython_notebook.ipynb - IPython notebook used to implement the model

capstone_support.py - Python module imported to the main notebook

### Additional files for development
capstone_parameter_tuning.ipynb - Used to generate the consolidated_exp.csv

### Other Artifacts used for the project
stock_data/*.csv -> contains all processed stock data

capstone_evaluation_history.csv -> model evaluation loss history results

capstone_evaluation_scores.csv -> model evaluation score results

consolidated_exp.csv -> These are results from my parameter tuning exercise. Please avoid having to run them all as they take considerable amount of time.

### Redundant and Not needed to be reviewed
capstone_report_and_code.ipynb -> Contains both code and report together

## Steps to download and run
git clone the project

Run the Ipython Notebook: capstone_ipython_notebook.ipynb

Note:
I have already saved off results of the runs locally (see Other artifacts section above)

If you do want to run those code cells, delete/modify the files/folder names so that the python notebook
will actually execute (download/process) them.