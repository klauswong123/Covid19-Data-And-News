# Covid19-Data-And-News

`Git clone https://github.com/klauswong123/Covid19-Data-And-New.git`


**Prerequisite:**

-	python3.6 or above

-	library to be installed:  requests, selenium, matplotlib


**How to use:**

Step1: Run the program: python covid.py. A help interface will come out like below.

```
select options:
1.help                          - show help interface. Input help can get this page as well
2.get $country                  - input the country you want to get data
3.show countries                - show available countries and Code
4.get country news              - get covid news of a country
5.get data graph                - draw data graph of data
6.exit                          - exit program. Input exit can quit
```

Step2: Type the option number to select the function you want to run. Example: if you want to show what countries are involved in this application just type ‘3’ in the command line.

Example: 

Commnad: '2' -> 'USA'

Output data:
```
Date: 5/23/20; New case: 13736; New death: 776; total: 1613476; total recovery: 0; total death:96662
Date: 5/22/20; New case: 24676; New death: 1295; total: 1599740; total recovery: 0; total death:95886
Date: 5/21/20; New case: 26012; New death: 1377; total: 1575064; total recovery: 0; total death:94591
```

Command: '4' -> 'USA'

Output data:

```
The US is facing a widening outbreak of COVID-19 that has claimed the lives of about 91,000 Americans and infected more than 1,528,000 persons across all 50 states. In response, the U.S.has implemented a range of measures including travel restrictions, social distancing, declaration of states of emergency, closure of schools, non-essential businesses, and increased testing. Reflecting the impact of the containment measures, the U.S.economy contracted at an annualized rate of 4.8 percent in the first quarter.Up to April, the economy has lost 16 percent of all jobs as a result of Covid-19 and the unemployment rate reached 14.7 percent.
```

Thanks for data provider : 

1. https://api.thevirustracker.com 

2. https://www.imf.org/en/Topics/imf-and-covid19/Policy-Responses-to-COVID-19
