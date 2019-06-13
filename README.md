# 2019-python-pandas
NYC PyLadies Python Pandas Workshop at Flatiron Health (May 2019)

# Meetup Event
https://www.meetup.com/NYC-PyLadies/events/259310784/

# Pre-requirements for the workshop
We expect a working knowledge of Python in order to be able to follow along with the workshop. If you are an absolute beginner in Python and aren't familiar with Python syntax, this workshop might not be suited for you.

# Option A: Binder link to run remote notebook
Binder is a web-based hub for Jupyter notebook. If your local setup does not work or if you prefer not to install anything locally, you can use the link here to work in a notebook on Binder. **Please note** that Binder will not save your notebook. You can download the notebook to your local machine at the end to have your own copy.
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/nyc-pyladies/2019-python-pandas/master)

# Option B: Pre-workshop prep instructions to run locally
**We strongly recommend using a machine with up-to-date versions of the libraries we use.**

## Step 1: Make sure you are running a recent version of Python
Either Python 2.7.12 and upwards, or any Python 3.

## Step 2: Install the necessary libraries for the workshop
Install these libraries by running `pip install` on your laptop:

**Ideal - the versions I run locally:** 
- Pandas 0.24.x and above
- Seaborn 0.9.x and above
- Matplotlib 3.0.x and above
- Jupyter 1.0.x and above
 
**Works for most of the tutorial:**
- Pandas 0.12.x and above
- Seaborn 0.5.x and above
- Matplotlib 2.1.x and above
- Jupyter 1.0.x and above

## Step 3: Make sure Jupyter Notebook runs
- Run in a terminal: `jupyter notebook`
- This should open a browser window, or go to http://localhost:8888/notebooks/
- Create a new notebook
- Try importing the newly installed libraries in a cell and execute the cell to test
- Please *debug* any issues that occur so you're ready to start the workshop!

## Step 4: Download the data file
Download the mock_treatment_starts_2016.csv file from this repo. **NOTE** The data is entirely made up and is in no way related to any real patient data we use at Flatiron. 
