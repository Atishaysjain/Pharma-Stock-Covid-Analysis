# Assesment of the influence of the Covid-19 Pandemic on stock prices of Indian Pharmaceutical Companies

* The study has been puplished as a research paper in the International Journal of Engineering and Advanced Technology (IJEAT). Link to the paper: [IJEATPaperLink](https://www.ijeat.org/portfolio-item/f37710811622/) 

* The data considered for the study is from 15th March 2020 to 17th February 2022.

## Folder contents

### CorrelationHeatmaps (All correlation heatmaps are based on Pearson Correlation)

* MonthlyCorrelation: Shows the correlation between the stock data and the Covid data for each individual company. The data is divided into monthly timeframes and the correlation is calculated for a time period of 30 days.

* OverallCorrelation: Shows the correlation on the entire two year data between the stock data and the Covid data for each individual company. 

* OverallLoggedCorrelation: Shows the correlation on the entire two year data between the stock data and the log10 of some of the Covid variables(Covid variables with high variance like Covid cases, Covid deaths, etc) for each individual company. The intuition is that the absolute variation in some of the Covid variables like Covid deaths, Covid cases, Covid testing is not proportionate to the fear induced in the mind of the public, but rather the log to the base 10 of the above mentioned Covid variables will more accurately reflect the puplic's perception of the Covid situation.

* OverallLoggedStandardizedCorrelation: Shows the correlation on the entire two year data between the stock data and the stadardized data over log10 of some of the Covid data(Covid variables with high variance like Covid cases, Covid deaths, etc) for each individual company.

### Data

* Covid_data: Contains the data of the following covid variables:

    * Total Cases
    * New Cases 
    * New Deaths 
    * New Tests 
    * Reprodureproduction Rate
    * Pospositive Rate 
    * Total Vaccinations 
    * People People Vaccinated, 
    * People Fully Vaccinated 
    * New Vaccinations 
    * Stringency Index

* nifty_data: Contains the stock data of the companies listed in Nifty Pharma index.
