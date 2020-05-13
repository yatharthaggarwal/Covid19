# Covid19 

The following Python Jupyter Notebook based scripts help in analysing and visualing the current Covid-19 outbreak scenario. These are very simple Python code for anyone to run and analyse. Best thing is dataset is on 'github' and is directly imported.

#### 1. Country_Active_Cases_Analysis_Plot.ipynb [Single country]
This script plots 2 graph for a particular country. First graph shows the cumulative Confirmed cases of that country with days, the graph begins when these cases have crossed 100. Also predictive lines of cases doubling every 3/5/10 days has been plotted. Second graph shows the cumulative Active cases of the same country, it also provides the growth rate of the pandemic for past 5 days and corresponding doubling days. 

#### 2. Country_Confirmed_Cases_Moving_Average_Plot.ipynb	[Single country]
This script plots 7-day moving average of confirmed cases (daily coronavirus positive cases) for a particular country. It also shows daily confirmed cases as deviations from the moving average.

#### 3. World_Active_Death_Recovered_Cases_Plot.ipynb [Multiple countries]
This script plots stacked bar for multile countries with their Active, Death and Recovered (ADR) cases over all this time. One could see how each country has tackled this Coronavirus outbreak and which countries have flattened the curve. 

#### 4. World_Confirmed_Cases_Plot.ipynb [Multiple countries]
This script plots Country-wise cumulative confirmed cases data over number of days in a single graph. The data takes in days since the countries got their first 100 cases. One can focus how each country responded to the pandemic since. 

#### 5. World_Deaths_ per_Million_Plot.ipynb [Multiple countries]
This script plots horizontal lines graph for multiple countries showing their Death per Million(DPM) data. The graph also shows 3 markers for last day and last 5th, 10th day DPM data. 

#### 6. World_Fatality_Rate_Plot.ipynb [Multiple countries]
This script plots Case Fatality Rate (CFR) for multiple countries over these number of days. One could analyze that the probability of someone dying from Coronavirus across time.

Current uploaded scripts have graph(s) showing the output. One can download the file and run the script and change country's name(s) as required. Country names to be passed in the function parameter should be same as in the 'global' datasets column of 'Country/Region'

The dataset being used is a Repository by the Center for Systems Science and Engineering (CSSE) at Johns Hopkins University given on their github page [https://github.com/CSSEGISandData/COVID-19], the dataset is currently updated everyday. They have also created a dashboard [https://coronavirus.jhu.edu/map.html] using the same. 

The population data has been taken from World Bank dataset: https://data.worldbank.org/indicator/SP.POP.TOTL. The data has been dowloaded and filtered. The same has now been uploaded above.

The visualizations are inspired from https://twitter.com/ShamikaRavi daily Covid-19 updates.
