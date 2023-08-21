# Correlation analysis between population and average rent in Berlin between 2012 and 2022

## Research Question
To what extent does the population of Berlin correlate with its average rent between the years 2012 and 2022?

## Region and Domain
- Region: Berlin, Germany
- Domain: Real estate

## Data Sources
- [Average rent price of residential property in selected cities in Germany from 2013 to 2022](https://www.statista.com/statistics/801560/average-rent-price-of-residential-property-in-germany-by-city/)
- [Population: Länder, reference date](https://www-genesis.destatis.de/genesis/online?sequenz=statistikTabellen&selectionname=12411&language=en#abreadcrumb)

## Data Visualization
### Time-Series Chart for Trend Analysis
This chart will effectively depict the trends of 'Berlin population' and 'Average rent in Berlin' over time.
![Trend analysis_Sehun](https://github.com/littlerock-jung/data-viz/assets/142711020/9da94e47-e881-4f8e-b183-b17ddd5485b6)
The time-series chart reveals that both 'Berlin population' and 'Average rent in Berlin' exhibit similar trends. This observation suggests a potential correlation between these two variables.

### Correlation Analysis Using Scatter Plot and R-Square
To delve deeper, we will utilize a scatter plot and calculate the R square value to quantitatively assess the correlation between the two variables.
![Correlation analysis_Sehun](https://github.com/littlerock-jung/data-viz/assets/142711020/459fd8a7-0c91-4e14-bc85-1c6df3c46cba)

## Discussion
The two plots illustrate the correlation between the population and average rent in Berlin. The first chart depicts the trends of both variables from 2012 to 2022. Notably, in 2019 and 2020, the trends of these variables diverge. The population saw an increase in 2019 compared to 2018, while the rent witnessed a decrease. However, this pattern was reversed in 2020, with a decrease in population accompanied by a rise in rent. Throughout the rest of the time series, both variables exhibit consistent upward trends.

The scatter plot further emphasizes the strong correlation between these two factors. The calculated R squared value of 90.2% highlights that the population in Berlin can account for approximately 90% of the variations in increased rent. Interestingly, there is a noticeable outlier in 2022, indicated by a larger residual as its data point deviates significantly from the regression line.
