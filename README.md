# neue fische EDA Project - Max Langer

## Introduction into this repository

This is my first project in EDA at new fish. In this project we are working with data that contains information about houses in King County (Washington, USA). The dataset contains houses that were sold in 2014 and 2015. It includes information on location, price, number of rooms, square footage, and King County's grade and condition ratings, among other information. The dataset is not included in the repository. The column names of the data set can be found in this [file](column_names.md). 
Here is a link to the [assignment](assignment.md) and the [workflow](workflow.md). The Jupyter notebook we created and used in this assignment can be accessed [here](EDA.ipynb). And all graphs that were created in the notebook were save in the [images](images) folder. Finally if you are interested in the Googles slides presentation, with the results of this assignment, you can find it [here](EDA_presentation.pdf).

If you want to use this repository, your system must meet the following requirements. 

## Requirements

- pyenv
- python==3.9.8

The rest of requirements can be found in the requirement file and is installed if you follow the setup.

## Setup

You will need to create/activate your virtual environment, updating pip and then installing all the required packages via:

```bash
pyenv local 3.9.8
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
```

After this step you can start and explore the notebook. I wish you a great time with it!
