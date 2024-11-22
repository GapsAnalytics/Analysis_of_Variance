# Analysis of Variance
### Project Overview
ANOVA was carried out to investigate the effect of the time of the day on the internal and external  temperature and humidity on sweet potato.
### Data Source
Temperature , Humidity data was collected on site by physical observation and computed to spread sheets
### Tools
- MS Excel -Data Cleaning
- Python Programming Language- EDA and visualization
### Libraries
- Jupyter notebook
- Pandas
- Numpy
- SckitLearn
- Seaborne and Martplotlib
- statsmodels
- scipy
### Data Cleaning
### Data Analysis
- Splitting data into internal temperature, external temperature, internal humidity, external humidity 
- Homogeneity of variance check for all parameters
- Normality check for the independent parameters seperately
- Normality check of residuals since the pvalues from above is not greater than 0.05
- Since normality of residual still have p values less than 0.05, run posthoc test
- Perform ANOVA on internal temperature.
- Compute descriptive statistics on internal temperature when the daytime are fixed into columns respectively.
- Graphically show relationship using line plots
### Evaluation/Result
 since p<0.05 for internal temperature ANOVA, it implies there is significant different between the 3 different times of the day when the temperature is measured.
