# Medical Data Visualizer

This is the boilerplate for the Medical Data Visualizer project. Instructions for building your project can be found at https://www.freecodecamp.org/learn/data-analysis-with-python/data-analysis-with-python-projects/medical-data-visualizer

[![author](https://img.shields.io/badge/author-pierrebomfim-red.svg)](https://www.linkedin.com/in/carlosfab) [![](https://img.shields.io/badge/python-3.7+-blue.svg)](https://www.python.org/downloads/release/python-365/) [![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/carlosfab/data_science/issues)

<p align="center">
  <img src="/medic_banner.png" >
</p>


# Medical Data Visualizer

This is a project for FreeCodeCamp.org certificate in Data Analysis w/ Python. 

## Tasks
- Create a chart similar to examples/Figure_1.png, where we show the counts of good and bad outcomes for the cholesterol, gluc, alco, active, and smoke variables for patients with cardio=1 and cardio=0 in different panels.
- Add an overweight column to the data. To determine if a person is overweight, first calculate their BMI by dividing their weight in kilograms by the square of their height in meters. If that value is > 25 then the person is overweight. Use the value 0 for NOT overweight and the value 1 for overweight.
- Normalize the data by making 0 always good and 1 always bad. If the value of cholesterol or gluc is 1, make the value 0. If the value is more than 1, make the value 1.
- Convert the data into long format and create a chart that shows the value counts of the categorical features using seaborn's catplot(). The dataset should be split by 'Cardio' so there is one chart for each cardio value. The chart should look like examples/Figure_1.png.
- Clean the data. Filter out the following patient segments that represent incorrect data:
  * diastolic pressure is higher than systolic
  * height is less than the 2.5th percentile
  * height is more than the 97.5th percentile
  * weight is less than the 2.5th percentile
 *. weight is more than the 97.5th percentile
- Create a correlation matrix using the dataset. Plot the correlation matrix using seaborn's heatmap(). Mask the upper triangle. The chart should look like examples/Figure_2.png.

## Directions

Run the Replt boilerplate by [clicking here](https://replit.com/@pierrebomfim/boilerplate-demographic-data-analyzer#main.py)

For development, you can use main.py to test the functions. Click the "run" button and main.py will run.

Unit tests are written under test_module.py. It's imported from test_module.py to main.py for your convenience. The tests will run automatically whenever you hit the "run" button.

## FreeCodeCamp instructions for the project
[Click here](https://www.freecodecamp.org/learn/data-analysis-with-python/data-analysis-with-python-projects/medical-data-visualizer
)
