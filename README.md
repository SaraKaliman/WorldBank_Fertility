# How to predict female fertility rates 
Here I analyse data on female fertility rates among different countries at different years. I am using an approach that culture does not play the crucial role but the development which can be measured in different ways but mostly through health and education. This idea I adopted from Hans Rosling's book "Factfulness". According to this approach countries are just shifted in time and, for example, in terms of fertility Arab world today is what U.S. was in the 60s. 
Therefore, I have build a linear regression model where fertility depends only life expectancy, literacy and percentage of urban population and not on time or the countries "culture". This model explains 85% of the fertility variation.

Data is available at the World Bank web page, but I have also made it available in this repository. 
Jupiter Notebook files are using Python 3 and Numpy, Pandas, Statsmodels, Matplotlib and Seaborn packages.

