# Azavea Junior Data Analyst Test

March 26, 2017

### About
This repo contains my submission for the Azavea Junior Data Analyst code test.

My part-1 answers are contained in a markdown file, `ConceptualQuestionsAnswers.md`. My part-2 answers are contained in a Jupyter Notebook, `Data-analyst-test_Part-2.ipynb`. This file contains all of my code and analyses for part 2.

Additionally, this directory contains 4 subdirectories:
- RF
- LR
- DT
- GB

These four folders contain the results from four models: Random Forest, Logistic Regression, Decision Trees, and Gradient Boosting. Each folder contains three CSV's:
- features.csv
- models.csv
- splits.csv

 `features.csv` contains the features importances for each model, `models.csv` contains performance metrics of each model averaged over three test/train splits, and `splits.csv` contains the performance for each individual split for each model. More information can be found inside of Data-analyst-test_Part-2.

The original data and instructions are contained in `Cars_mileage.csv` and `orig_README.md`, respectively. The original repo can be found [here](https://github.com/eneedham/data-analyst-data-test).

### Environment & Dependencies
#### Main Dependencies
- Python 3.X
- Pandas
- Numpy
- sci-kit learn
- matplotlib
- seaborn
- Jupyter Notebook

The full dependency list is stored in `environment.yml`.

To install, first download [Anaconda or Miniconda](https://conda.io/docs/install/quick.html).

Then download the `environment.yml` file. You can install the environment with the following command:

`conda env create -f environment.yml`

After you have installed Anaconda, you can run the jupyter notebook with:

`jupyter notebook`

More documentation [here](http://jupyter.readthedocs.io/en/latest/install.html).
