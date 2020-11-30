# combat_covid19
This script seek out the the possible to find out the immortallity in patients diagnosed with covid-19.  

The data is from kaggle. https://www.kaggle.com/benhamner/jhucovid19

The target value is  mortality_rate
and the feature the model use is 'country_region', 'last_update', 'lat', 'long', 'confirmed', 'deaths',
       'recovered', 'active', 'incident_rate', 'people_tested',
       'people_hospitalized', 'uid', 'iso3'
       
There is implemented two models RandomForestRegressor and xgboost. Furthermore the models have been fined tuned with different hyperprameter, afterward the bedst model was selected. 


