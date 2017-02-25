# Seaborn-Visualization-introduction
Here we will create commonly used graphs using Python's Seaborn library

Following things are visualized in this notebook

    Univariate continuous distributions
    Multivariate continuous distribution
    Categorical distributions

Important functions and their use
For continuous variables

    distplot: plots single continuous variable
    jointplot : plots 2 continuous variables
    pairplot : pairs every variable(scatterplot matrix)

For categorical + continuous variables

    countplot: histogram , Frequency distribution of single variable
    countplot: 'hue' parameter can be used to add one more variable and create stacked bars
    swarmplot: plot 1 cat and 1 cont variables
    swarmplot: plot 2 cat and 1 cont variables using hue
    boxplot: plots 2 cat and 1 cont variable
    barplot: 2 cat and 1 cont
    factorplot: plot 4 variables at a time; can recreate above plots using 'kind' parameter

For plotting linear relationships in variables

    regplot : less commonly used
    lmplot : requires 'tidy' data
        Parameters:
            order: to set higher order poly functions
            hue, row, col: to add additional features
            size: to control size of individual plots
            kind: used in other plots to put linear relationship
            robust: used to ignore outliers
            markers and palette: to control visual features

