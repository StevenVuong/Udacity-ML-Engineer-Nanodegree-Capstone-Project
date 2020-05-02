# Capstone Project: Kaggle Competition - Predict Future Sales

## Overview
This capstone project is the final project as part of Udacity's Online Machine 
Learning Engineering nanodegree. The chosen project is Kaggle's 'Predict Future
Sales' competition: https://www.kaggle.com/c/competitive-data-science-predict-future-sales.

As the title suggests, we will try to predict future sales. Specifically, we predict future sales 
using the data provided by Russian software firm, 1C Company. The data is taken from 2013 - 2015 
and contains information about shops and their items amongst other features.

We have done all of our work in Jupyter Notebooks, with Python 3 as the backbone
language. To get started, please follow the **Quickstart** steps below.

Note: To run locally, the following pre-requisites should be met:
-  Python 3 should be installed: https://www.anaconda.com/products/individual
-  Jupyter Notebook should be installed: https://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/install.html

Recommendations:
-  To run locally, we recommend using a virtual environment: https://docs.python.org/3/library/venv.html
-  To help follow along the code, we also suggest having a base level understanding of Python. To 
get up to speed, you can sign up and follow along https://www.udacity.com/course/introduction-to-python--ud1110  
for free!

If you do not wish to run this code locally, that is not a problem. Thanks to cloud service providers, 
you can launch jupyter notebook instances and run them on cloud computing platforms. Two that stand 
out are:
- Google Colab: https://colab.research.google.com/ (free)
- Amazon Web Services Sagemaker: https://aws.amazon.com/sagemaker/ 


Which have notebook instances with all the required packages pre-installed, so all that is required to run
them is to import the necessary packages. For this project, I have ran my code in Google Colab (ran out of AWS credits) and saved the .ipynb's and outputs to this repository.


Last Edited: 29-04-2020

## Quickstart

Note: The code base is in the form of Jupyter Notebooks and based on Python 3. These
were run on Google Colab's free, learning/research platform (and so in the notebooks are
snippets mounting folder directory to the notebook.). In order to replicate, one may
have to adjust the folder pathing within the code or mimic my folder structure as below.

- jupyter_notebook1.ipynb
- jupyter_notebook2.ipynb
- ..
- data/
  - competition_files/
    - kaggle_data1.csv
    - kaggle_data2.csv
    - ..
  - output/
    - processsed_data1.csv
    - test_X.csv
    - etc..
    - model/
      - model_0.pickle
      - model_1.pickle
      - ..



1. Download Data
The competition is hosted by Kaggle and the data provided by Russian software company 1C. 
It is available to download at: https://www.kaggle.com/c/competitive-data-science-predict-future-sales/data 
by signing into Kaggle and entering the competition. Then you can download the data and 
if you choose to replicate my folder structure, re-name the downloaded folder to `competition_files` and 
move it into `data/`.

2. Install Requiremments
For running locally, you can install requirements by running:
`python3 -m pip install -r ./requirements.txt`. It is recommended to run inside a 
virtual environment, however that is up to you. This covers all the libraries and 
packages necessary to replicate the code within this repository.

    -  Alternatively, if you are using a cloud based notebook (such as AWS Sagemaker or Google Colab), this step
can be omitted as they come pre-installed with the requirements.

3. Follow along the notebooks! The outputs are saved so you can also compare your outputs to mine and there are comments within the code cells as well as mark down cells to help explain methodology and thought process underlying my steps. 
By following the notebooks in order, we can see the journey of data exploration to modelling and finally predicting
a solution. The order of the notebooks to follow in is:
    1.  `./feature_engineering_pt1.ipynb`
    2.  `./feature_engineering_pt2.ipynb`
    3.  `./train_pt1.ipynb`
    4.  `./train_pt2.ipynb`


## License
MIT License. See `./license.txt` for details.


### Last Notes: Hope you Enjoy working through this as much as I did! Feel free to reach out at stevenvuong96@gmail.com for any questions, or fork, improve and make a Pull Request should you wish to contribute :).
