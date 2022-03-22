# Experimental Liquid Rocket Engine Design Calculations

This jupyter notebook is intended to aid in the rapid design and redesign of a liquid rocket engine for a UBCO Capstone Project in collaboration with the UBCO Aerospace Club.  These calculations are only meant to be baseline values to be expanded upon.  

## How to use this for designing your rocket
Read the Documentation for [RocketCEA](https://rocketcea.readthedocs.io/en/latest/) first

Install RocketCEA via python pip with 
```python3
python3 -m pip install rocketcea
```
### Select a Propellant Mixture and generate combustion data for it
1. open combustion-analysis.py and adjust the fuel or ox string to a propellant of your choice 
2. run the program with python

### Analyze Results in combusion.csv
1. open analyze.ipynb
2. filter and sort using desired criteria

### Copy input values to a Design Calculation.ipynb file
1. copy or open and edit a Design Calculation.ipynb file with a jupyter notebook viewer
2. change values as needed according to analyzed results and click run
3. Congrats!  Your rough sizing and dimensions should be ready for further scrutiny and manufacturing