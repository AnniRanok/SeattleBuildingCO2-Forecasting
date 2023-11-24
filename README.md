# OC_Projet_4

We are working for the city of Seattle. To achieve its goal of being a carbon-neutral city by 2050, our team is closely examining the consumption and emissions of non-residential buildings.

Detailed records were taken by city agents in 2016. Here are the data and their source: https://data.seattle.gov/dataset/2016-Building-Energy-Benchmarking/2bpz-gwpy.
However, these surveys are costly to obtain, and from those already conducted, you want to try to predict the CO2 emissions and total energy consumption of non-residential buildings for which they have not yet been measured.

Our prediction will be based on the structural data of the buildings (size and use of buildings, date of construction, geographical location, ...)

We are also looking to evaluate the interest of the "ENERGY STAR Score" for the prediction of emissions, which is tedious to calculate with the approach currently used by our team.
We will integrate it into the modeling and judge its interest.

# Here is a summary of the mission:
Conduct a short exploratory analysis.
Test different prediction models to best address the issue.

# Some leads and mistakes to avoid:
The goal is to do without future annual consumption surveys (be careful of data leakage).
We will in any case make a first reference survey for any new building in the first year, so nothing prevents you from deducing structural variables to buildings, for example the nature and proportions of the energy sources used.

Pay close attention to the treatment of different variables, both to discover new insights (can we deduce interesting information from a simple address?) and to optimize performance by applying simple transformations to variables (normalization, logarithmic transformation, etc.).

Implement a rigorous evaluation of regression performance, and optimize hyperparameters and the choice of ML algorithms using cross-validation.
