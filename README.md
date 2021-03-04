# Synengco Recruitment Challenge

Recruitment challenge based on AEMO electricity demand

## Note

All the commands were tested on Ubuntu 20.04. If you use some other OS then you might need to unjust them a little

## Files

April_daily_electricity_demand.csv  - Daly electricity demand for April 2020
Predicted_QLD_demand_2020.csv       - Predicted electricity demand for 2020
README.md                           - this file
requirements.txt                    - list of python libraries
visualisation.ipynb                 - Notebook with code for the challenge


## How to run

Clone repository

git clone https://github.com/Peter7645946/recruitment-challenge-2020.git

Make sure that you have python3 installed.

Create virtual environment:

```
python3 -m venv py
```

Activate the environment

```
source ./py/bin/activate
```

Cd to the recruitment-challenge-2020

```
cd recruitment-challenge-2020
```

Install everything from requirements.txt

```
pip install -r requirements.txt
```

Start jupyter notebook
```
jupyter notebook
```

and open visualisation.ipynb. It contains Notes, comments, code and visualisation required by this coding challenge.

You can recalculate the notebook, change some parameters (see notes), etc