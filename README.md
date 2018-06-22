# Simplify - Logistic Regression

This repository contains the code for building Logistic Regression from scratch.



## Workshop Outline


__Section 1:  Understanding - Logistic Regression__

            1.1 Intorduction to Machine Learning

            1.2 Intuition behind the Logistic Regression (LR)

            1.3 Math behind the LR

            1.4 Summary

__Section 2:  Building - Logistic Regression from scratch__

     Section 2.1: Apply LR using API of Scikit-Learn 

                  Step 2.1.1: Import dependencies

                  Step 2.1.2: Load data

                  Step 2.1.3: Preprocessing

                  Step 2.1.4: Split data set into training and testing
            
                  Step 2.1.5: Train model using Scikit-learn's Logistic Regression
            
                  Step 2.1.6: Visualize the Dataset


     Section 2.2: Apply LR from scratch

                  Step 2.2.1: Define sigmoid or logistic function
            
                  Step 2.2.2: Define hypothesis function
            
                  Step 2.2.3: Define cost function 
            
                  Step 2.2.4: Define cost function derivative as well as calculating error
            
                  Step 2.2.5: Get the updated theta value by calculating gradient descent
            
                  Step 2.2.6: Define helper function to run Logistic Regression
            
                  Step 2.2.7: Compare our Implementation with Scikit-Learn API
            
                  Step 2.2.8: Run our own LR implementation

__Section 3:  Classify emails into Spam and Ham__

     Step 1: Import dependencies

     Step 2: Load data

     Step 3: Exploratory Data Analysis

     Step 4: Transforming labels

     Step 5: Split data set into training and testing

     Step 6: Generating Features using CountVectorizer

     Step 7: Train model

     Step 8: Test model 

            Step 8.1: Measure Accuracy

            Step 8.2: Confusion Matrix 

            Step 8.3 Area Under Curve



## Dependencies 
* Python 3.3+
* math
* numpy
* pandas
* scikit-learn
* matplotlib
* seaborn
* jupyter notebook


## Installation Instructions

### Windows OS

__Install Python3 (install python 3.6.4)__
    
* Step 1: Download python form [this link](https://www.python.org/downloads/)

* Step 2: Refer [this link](http://www.openbookproject.net/courses/webappdev/units/softwaredesign/resources/install_python_win7.html) or [this link](https://www.youtube.com/watch?v=V_ACbv4329E) in oreder to install python

__Install anaconda__

* Step 1: Download Anaconda 5.1 (python 3.6 version) using [this link](https://www.anaconda.com/download/#windows)

* Step 2: See the installation instruction given on [this link](https://conda.io/docs/user-guide/install/windows.html#install-win-silent)

Note: If you have any other version of python then install anaconda which supports that particular version of python

__Install dependencies using conda__
```
    numpy:            In-built installed with anaconda
    scipy:            In-built installed with anaconda
    scikit-learn:     In-built installed with anaconda
    Pandas:           In-built installed with anaconda
    matplotlib:       In-built installed with anaconda 
    seaborn:          In-built installed with anaconda
    jupyter notebook: In-built installed with anaconda
    jupyter lab:      In-built installed with anaconda
```

* In order to start jupyter notebook execute the given command on cmd/terminal

  `$ jupyter notebook`

### Linux OS

__Python and pip setup__

* Python 3 is already installed on linux OS
* Install pip for Linux from [here](https://github.com/jalajthanaki/NLPython/blob/master/ch1/installation_guide/NLTK%2BSetup.md)

__Command for installing dependencies__
```
numpy:            $ sudo pip install numpy
scipy:            $ sudo pip install scipy
scikit-learn:     $ sudo pip install -U scikit-learn
Pandas:           $ sudo pip install pandas
matplotlib: 
                  $ sudo apt-get install libfreetype6-dev libpng-dev
                  $ sudo pip install matplotlib 
seaborn:          $ sudo pip install seaborn
jupyter notebook: $ sudo apt-get -y install ipython ipython-notebook
                  $ sudo -H pip install jupyter
jupyter lab       $ sudo pip install jupyterlab

```
## Usage

* For section 1: use `Understand_LR.ipynb` ipython notebook

* For section 2: use `LR_from_Scratch.ipynb` ipython notebook

* For section 3: use `Spam_ham_Classifier.ipynb` ipython notebook

## Special Thanks

Thanks IIT-Bombay analytics club for hosting this event.