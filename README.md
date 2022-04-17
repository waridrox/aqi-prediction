## AQI Prediction - pre-COVID and post-COVID era

### Motivation behind the project

Since industrialization, there has been an increasing concern about environmental pollution. As mentioned in the WHO report, 7 million premature deaths annually linked to air pollution. Air pollution is the world's largest single environmental risk. Moreover, as reported in the NY Times article, [India’s Air Pollution Rivals China’s](https://www.nytimes.com/2017/02/14/world/asia/indias-air-pollution-rivals-china-as-worlds-deadliest.html?_r=0) as World’s Deadliest.
Using this dataset, one can explore India's air pollution levels at a more granular scale.


### Dataset

This data is combined (across the years and various states of the country) and largely clean version of the [Historical Daily Ambient Air Quality Data](https://data.gov.in/catalog/historical-daily-ambient-air-quality-data) released by the Ministry of Environment and Forests and Central Pollution Control Board of India under the National Data Sharing and Accessibility Policy (NDSAP).

### Graphs

![vehicular pollution content](./graphs/vehicular%20pollution%20content.png)

![industrial pollution content - most polluted](./graphs/industrial%20pollution%20content%20-%20most%20polluted.png)

![industrial pollution content - min polluted](./graphs/industrial%20pollution%20content%20-%20min%20polluted.png)

![Pre COVID levels](./graphs/pre-covid%20satisfaction%20level.png)

![Vehicular pollution - line graph](./graphs/vehicular%20pollution%20-%20line%20graph.png)

![Industrial pollution content (most polluted) - line graph](./graphs/industrial%20pollution%20content%20-%20most%20polluted%20-%20line%20graph.png)

![Most polluted cities - industrial pollution](./graphs/most%20polluted%20cities%20-%20industrial%20pollution.png)

![Most polluted cities - Vehicular pollution](./graphs/most%20polluted%20cities%20-%20vehicular%20pollution.png)

![Minimum polluted cities - Industrial pollution](./graphs/min%20polluted%20cities%20-%20industrial%20pollution.png)

![Minimum polluted cities - Vehicular pollution](./graphs/min%20polluted%20cities%20-%20vehicular%20pollution%20cities.png)

![Post COVID levels](./graphs/post-covid%20satisfaction%20level.png)


### Conclusion

1. Vehicular pollution contents are more related to air quality index.
2. Delhi is the most polluted city in terms of vehicular pollution contents.
3. Ahmadabad is the most polluted city in terms of industrial pollution content.
4. After COVID19 pandemic there is gradual dicrease in vehicular pollution contents, industrial pollution content.
5. Extra Gradient Boost classifier 100% accurately classify the target variable.