# Covid19 Cases Tracking in Morocco in Real Time 

## about

A small package of Python to access and track the number of cases of confirmed and deaths and  recovered people
from the Coronavirus for Morocco

![COVID2](https://user-images.githubusercontent.com/28219393/78923704-50138000-7aa1-11ea-9acb-c7247cd595a8.JPG)

# Installation

```
pip install covid19_morocco
or in colab google cloud
!pip install covid19_morocco
```

## Usage

```
from covid19_morocco import covid19
country_name=Morocco #name of country 
```

```
# to get confirmed count for country in real time
confirmed_count=covid19.confirmed_people()
#to get deaths count for country in real time 
deaths_count=covid19.deaths_people()
#to get recoverd count in real time 
recoverd_count=covid19.recoverd_people()
# to get confirmed cases by regions (SoussMassa, CasaSettat, FesMeknes, MarrakechSafi,....)
confirmed_by_regions=covid19.confirmed_people_regions(regions)
#Plot cases 
covid19.plot_cases()
#Plot histogram
covid19.hist_cases()
```

![COVID](https://user-images.githubusercontent.com/28219393/78923684-4a1d9f00-7aa1-11ea-988f-f1e310e8f934.JPG)

## Checking

To verify the retrieved data within this library
go to worldmeters web site for checking for any coutry

https://www.worldometers.info/coronavirus

plot cases
https://raw.githubusercontent.com/aboullaite/Covid19-MA/master/stats/MA-times_series.csv





 

