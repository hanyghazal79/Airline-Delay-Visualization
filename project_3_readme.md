# (Airline delay causes dataset exploration)
## by (Hany Abdol-Aleem Ghazal)


## Dataset

> airline_delay_causes.csv dataset shows up the arrival delays with many of contributing factors.

> ***Vaiables:***

> arr_flights : number of flights arrived at the airport.

> arr_del15: number of flights delayed >= 15 minutes.

> carrier_ct: number of flights delayed due to carrier

> nas_ct: number of flights delayed due to nas

> weather_ct: number of flights delayed due to weather

> late_aircraft_ct: number of flights delayed due to late aircraft

> security_ct: number of flights delayed due to security issues

> arr_delay : sum of delay minutes.

> carrier_delay: number of minutes delayed due to carrier.

> nas_delay: number of minutes delayed due to nas ( Natural air services).

> weather_delay: number of minutes delayed due to weather.

> late_aircraft_delay: number of minutes delayed due to late aircraft

> security_delay: number of minutes delayed due to security issues

> arr_cancelled: number of cancelled arrivals.

> arr_diverted: number of diverted arrivals.

> ***The dataset is a structure containing 1567 rows and 21 columns after the initial cleaning process.***

> ***The main features of interest are: arr_delay, carrier_delay, weather_delay, nas_delay, security_delay, late_aircraft_delay.***

> ***The helper features as I think may be: year, month, carrier_name, airport_name, arr_flights, arr_del15, carrier_ct, weather_ct, nas_ct, security_ct and late_aircraft_ct.***

## Summary of Findings

> ***Plots are difficult to interpret and shows the presence of outliers.***

> ***The distributions of variables mostly are right skewed.***

> ***Scale transformation brought better results.***

> ***arr_del15 feature varies with variations in carrier_ct, weather_ct, nas_ct and late_aircraft_ct more than with security_ct with a higher slope indicating a more strong positive correlation.***

> ***arr_delay feature varies with variations in carrier_delay, weather_delay, nas_delay and late_aircraft_delay more than with security_delay with a higher slope indicating a more strong positive correlation.***

## Key Insights for Presentation

> ***arr_del15 feature varies with variations nas_ct with an intermediate positive correlation.

> ***As nas_ct increased arr_delay continue to increase from the starting to ending limits of the plot.***

> ***This is an indicator of being these features augmenting each other.***

