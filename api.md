## Economy Endpoints

### [/api/economy/data/{state}/{indicator}](https://chartify.in/api/economy/data/India/literacy-rate)

> Gets data for one state for all years

### [/api/economy/choropleth/{year}/{indicator}](https://chartify.in/api/economy/choropleth/2018/urban-unemployment-rate/total)

> Gets data for one year for all states

Below are all the indicators:

* sex-ratio
* birth rate
* death rate
* literacy-rate
* infant mortality rate
* density-of-population
* total-population
* rural-population
* urban-population
* rural-unemployment-rate
* urban-unemployment-rate
* decadal-growth-of-population


## NFHS 5 Endpoints

### [/nfhs/5/api/get/indicators](https://statsindia.herokuapp.com/nfhs/5/api/get/indicators)

> Gets all indicators neatly arranged with categories 

### <a href='https://statsindia.herokuapp.com/nfhs/5/api/get/data/Tobacco%20Use%20and%20Alcohol%20Consumption%20among%20Adults%20(age%2015%20years%20and%20above)/Women%20age%2015%20years%20and%20above%20who%20consume%20alcohol%20(%)/urban'>/nfhs/5/api/get/data/{category}/{indicator}/{typology}</a>

> Gets data for an indicator neatly arranged in states

## Population By Religion Endpoints

### [/population_by_religion/api/get/all](https://statsindia.herokuapp.com/population_by_religion/api/get/all)

> Gets all rows in one go (not recommended)

### [/population_by_religion/api/get/regions](https://statsindia.herokuapp.com/population_by_religion/api/get/regions)

> Get all regions for which data is available (as per latest census)

### <a href="https://statsindia.herokuapp.com/population_by_religion/api/get/data/Madhya Pradesh/Indore">/population_by_religion/api/get/data/{state}/{district}</a>

> Get all data for particular region (*`district`='' implies state*)
  
