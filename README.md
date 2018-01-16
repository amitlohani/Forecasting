# Tractor Sales Forecast

PowerHorse, a tractor and farm equipment manufacturing company, was established a few years after World War II. The company has shown a consistent growth in its revenue from tractor sales since its inception. However, over the years the company has struggled to keep it’s inventory and production cost down because of variability in sales and tractor demand. The management at PowerHorse is under enormous pressure from the shareholders and board to reduce the production cost. In the same effort, as a data science and predictive analytics consultant I will start investigation of this problem in the next part of this series using the concept discussed in this article. Eventually, I will develop an ARIMA model to forecast sale / demand for next year, to manage their inventories and suppliers.  

## Overview of the Framework  
**Step 0:** Problem Definition  
**Step 1:** Data Exploration  
**Step 2:** Stationarize the Series  
**Step 3:** Find Optimal Parameters  
**Step 4:** Build ARIMA Model  
**Step 5:** Check for White Noise  
**Step 6:** Investigate Test Error  
**Step 7:** Make Predictions  

## Fundamental Idea
The fundamental idea for time series analysis is to decompose the original time series (sales, stock market trends, etc.) into several independent components. Typically, business time series are divided into the following four components:  
**Trend** - Overall direction of the series i.e. upwards, downwards etc.  
**Seasonality** - Monthly or quarterly patterns. (e.g. the quarter, month, or day of the week)  
**Cycle** - Long-term business cycles or pattern exists where the data exhibits rises and falls that are not of fixed period (duration usually of at least 2 years)  
**Irregular remainder** - Random noise left after extraction of all the components  

### Difference Between Seasonal & Cyclic
1. Seasonal pattern constant length vs. cyclic pattern variable length
2. Average length of cycle longer than length of seasonal pattern
3. Magnitude of cycle more variable than magnitude of seasonal pattern.
The timing of peaks and troughs is predictable with seasonal data, but unpredictable in the long term with cyclic data.

## Detail Explanation & Code
Just download Sales_Forecast.Rmd and run it in your local RStudio. Here You will get every details of HOW TO and WHY while dealing problems of forecasting using ARIMA model.

I will be very thankful to you if you've something to correct in this analysis or you can add something to make it more reliable, please let me know (lohani.18@gmail.com). 

Thanks,  
Amit Kumar
