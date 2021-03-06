# I before E exploratory analysis
A just-for-fun exploratory analysis project presented by Chad Boschert at the inagural [Data Science After Dark](https://www.meetup.com/Data-Science-After-Dark/) meetup in Springfield, MO on August 20th, 2019.

https://youtu.be/vQo5r4MWmTg?t=2433

## Project Overview
This project includes 3 Jupyter Notebooks. Each numbered notebook digs deeper into the heuristic "I before E except after C" using an english words database borrowed from [@dwyl](https://github.com/dwyl/english-words)

## Derived Datasets
The two .csv files in the ./data/derived folder can be used to perform your own explorations in Excel or other tool of choice. These datasets include just the ie and ei words along with other helpful features. Enjoy!

## Dev Environment Setup
These instructions show how to setup a local development environment on Linux using virtualenv and python3.

$ git clone git@github.com:Data-Science-After-Dark/ib4e.git
$ cd ib4e
$ python3 -m venv venv
$ source venv/bin/activate
(venv) $ pip install -r requirements.txt
(venv) $ ipython kernel install --user --name=venv
(venv) $ jupyter notebook

This should launch a new browser window allowing you to run each of the notebooks. Syntax for other operating system (eg. Windows) will be different, but the steps should be generally the same.

1. Clone the git repository
1. Setup a virtualenv (this is optional, but recommended.)
1. Install the project requirements
1. Add your new virtualenv to Jupyter
1. Start Jupyter notebook
