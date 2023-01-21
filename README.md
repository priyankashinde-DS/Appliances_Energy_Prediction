# Appliances Energy Prediction

![image](https://user-images.githubusercontent.com/87980985/213869197-2877f179-b16e-4eaa-be59-966ad2aabdb5.png)

## **Problem Statement**
**Prediction :- The electrical energy consumption of a Appliances.**
---

## **Dataset description**
The data set is at 10 min for about 4.5 months. The house temperature and humidity conditions were monitored with a ZigBee wireless sensor network. Each wireless node transmitted the temperature and humidity conditions around 3.3 min. Then, the wireless data was averaged for 10 minutes periods. The energy data was logged every 10 minutes with m-bus energy meters. Weather from the nearest airport weather station (Chievres Airport, Belgium) was downloaded from a public data set from Reliable Prognosis (rp5.ru) and merged together with the experimental data sets using the date and time column.

The dataset contains features like:

* **date**= time year-month-day hour:minute:second


* **lights** = energy use of light fixtures in the house in Wh (Drop this column)

* **T1** = Temperature in kitchen area, in Celsius

* **RH1**= Humidity in kitchen area, in %

* **RH2** = Humidity in living room area, in %

* **T3** = Temperature in laundry room area

* **RH3** = Humidity in laundry room area, in %


* **RH4** = Humidity in office room, in %

* **T5** = Temperature in bathroom, in Celsius

* **RH5** = Humidity in bathroom, in %



* **RH6** = Humidity outside the building (north side), in %

* **T7** = Temperature in ironing room , in Celsius

* **RH7**= Humidity in ironing room, in %


* **RH8**=Humidity in teenager room 2, in %

* **T9**= Temperature in parents room, in Celsius

* **RH9** = Humidity in parents room, in %

* **Wind speed** (from Chievres weather station), in m/s

* **Visibility** (from Chievres weather station), in km

* **Tdewpoint** (from Chievres weather station), Â°C

* **rv1** = Random variable 1, nondimensional

* **rv2** = Random variable 2, nondimensional

* **T2** = Temperature in living room area, in Celsius

* **T4** = Temperature in office room, in Celsius

* **T6** = Temperature outside the building (north side), in Celsius

* **T8** = Temperature in teenager room 2, in Celsius

* **To** = Temperature outside (from Chievres weather station), in Celsius

* **Pressure** =(from Chievres weather station), in mm Hg

* **RH_out**=Humidity outside (from Chievres weather station), in %

**Target Variable :**

* **Appliances** = energy use in Wh (Dependent variable)

Where indicated, hourly data (then interpolated) from the nearest airport weather station(Chievres Airport, Belgium) was downloaded from a public data set from Reliable Prognosis,rp5.ru. Permission was obtained from Reliable Prognosis for the distribution of the 4.5 months of weather data.

---

## **Conclusion**

**Understanding the consumption of electricity in daily home appliances such as washing machines, televisions, microwaves etc., which constitutes the major part of electricity demand of a low energy household, could provide major insights in utilization of electricity. Studying this data is important in finding the key factors that could influence the electricity consumption in appliances and thereby work on those factors to decrease the consumption of electricity by appliances. The problem predicts the appliances usage of electricity based on various factors that could influence the consumption of electricity. The electricity consumption in low energy houses is determined by two main factors, the number of electrical appliances in the house and the usage of appliances by the occupants of the house. There are many factors that could influence the usage by appliances, some of the factors that could influence are the indoor environmental factors near the vicinity of the appliances such as temperature, humidity, light, vibrations etc. The occupancy level of house in different locations could also help in determining the usage of appliances. Developing prediction models for this problem can be useful for many applications such as detecting abnormal energy usage patterns, determining energy demand, to use in building performance simulation etc.**
