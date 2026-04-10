## DS2500 Final Project
#### Ethan McGeever & Matthew Lam
######  Deahan Yu Section 1 

Research Question: *“During the 2008 crisis, the 2020 COVID shock, and the 2021-2023 inflation period, which indicators moved first and had the strongest relationship with delinquencies?”*


This is the final submission for Ethan McGeever & Matthew Lam for Data Science 2500. Our project utilizes lagged correlation analysis to better understand the relationship between macroeconomic indicators (unemployment, PCE, energy prices, food prices, healthcare costs) and delinquency types (credit card, consumer loans, mortgages) at lags of a quarter, half, three quarters, and a full year.

#### Data Dictionary
##### Indicator Dataframes
DFXARG3M086SBEA => Represents the Personal consumption expenditures: Food (chain-type price index), published by the U.S. Bureau of Economic Analysis (BEA)

DHLCRG3Q086SBEA => Represents the Personal Consumption Expenditures: Services: Health Care (chain-type price index), published by the U.S. Bureau of Economic Analysis (BEA)

DNRGRG3M086SBEA => Represents the Personal Consumption Expenditures: Energy Goods and Services (Chain-Type Price Index), published by the U.S. Bureau of Economic Analysis (BEA)

PCEPILFE => Represents the Personal Consumption Expenditures Excluding Food and Energy (Chain-Type Price Index), published by the U.S. Bureau of Economic Analysis (BEA)

U6RATE => Refers to the Total Unemployed, Plus All Persons Marginally Attached to the Labor Force, Plus Total Employed Part Time for Economic Reasons, as a Percent of the Civilian Labor Force Plus All Persons Marginally Attached to the Labor Force. It is the most comprehensive measure of labor underutilization, published by the U.S. Bureau of Labor Statistics (BLS)

##### Delinquency Dataframes
DRCCLACBS => Represents the "Delinquency Rate on Credit Card Loans, All Commercial Banks" in the United States, measured as a percentage. It tracks the percentage of credit card loans that are past due at U.S. commercial banks.

DRCLACBS => Represents the "Delinquency Rate on Consumer Loans, All Commercial Banks," measures the percentage of consumer loans (such as credit cards, auto loans, and other consumer loans) that are delinquent at all commercial banks in the U.S.

DRSFRMACBS => Represents the "Delinquency Rate on Single-Family Residential Mortgages, Booked in Domestic Offices, All Commercial Banks" in the United States.

##### Additional Macro Dataframes
PERMIT => Refers to the New Privately-Owned Housing Units Authorized in Permit-Issuing Places: Total Units data series

VIXCLS => Is the daily closing value of the CBOE Volatility Index, known as the "fear gauge". It measures the market's expectation of 30-day forward-looking volatility based on S&P 500 index options.