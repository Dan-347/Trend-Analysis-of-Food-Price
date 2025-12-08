# Trend analysis of food prices in Singaraja City from 2020 to 2023

This analysis was conducted to understand the dynamics and patterns of price changes for key food commodities in Singaraja City during the period 2020–2023. The commodities analyzed include rice, chicken eggs, granulated sugar, chicken meat, and garlic, as these five items are basic necessities for the community and are sensitive to economic and distribution changes.

The dataset contains daily prices for each commodity. Analysis was conducted using an exploratory approach to examine price developments over time, identify seasonal patterns, calculate descriptive statistics, and assess which commodities were the most stable and which were the most volatile.

## Background
Food prices are an important indicator of economic stability in a region. Significant price fluctuations can affect people's purchasing power, especially in the context of basic necessities. Local governments, businesses, and the general public need to understand how food prices move over time in order to make informed decisions. However, food price data is often only presented in tables or periodic reports without in-depth analysis of patterns, trends, and significant changes. This makes it difficult to see the big picture regarding price stability and factors that may influence it.

Therefore, exploratory analysis is needed to understand how food price trends change, whether there are certain seasons or periods that show increases/decreases, and which commodities are most sensitive to fluctuations.

## Objective
The purpose of this analysis is to provide a comprehensive overview of food price dynamics in Singaraja City during 2020–2023, including:
1. Analyzing price trends for each commodity over time.
2. Identifying seasonal patterns or significant changes, such as price spikes or declines.
3. Calculate descriptive statistics such as the average, maximum price, minimum price, and price frequency.
4. Assess the price stability of each commodity based on the level of fluctuation.
5. Compare price movements between commodities to see which ones are the most volatile.
6. Provide relevant insights into the local economic context and potential factors affecting price changes.
7. Analyzing correlations between commodities to determine whether price changes in one commodity are related to other commodities.

## Why This Analysis Matter
Food price trend analysis is important in:
- Monitoring regional inflation, especially in the basic necessities sector.
- Predicting potential price increases, for example ahead of major holidays, weather changes, or distribution disruptions.
- Identifying vulnerable commodities that require special attention from local governments.
- Providing data-driven recommendations for stock preparation, subsidy policies, and market interventions.

By understanding price dynamics over four consecutive years, this analysis can serve as a basis for future policy planning or decision-making.

## Analysis Steps
This section describes the steps taken to analyze food price dynamics in Singaraja City during the period 2020–2023. The steps taken include:
1. **Data Collection** <br>
Collecting food commodity price data (rice, chicken eggs, granulated sugar, chicken meat, garlic) for the period 2020–2023. The data is stored in CSV format and processed using Python.
2. **Data Cleaning & Preprocessing** <br>
This step is done to ensure data quality before further analysis. The process involved deleting or handling missing values and creating derived variables
3. **Exploratory Data Analysis (EDA)** <br>
The EDA stage is conducted to understand basic patterns and data structures. The activities carried out are examine the price distribution of each commodity, analyze annual and monthly trends, examine correlations between commodities, observe price volatility and the most volatile commodities, identify price anomalies, such as sudden spikes or significant declines, and compare patterns between commodities to see similarities or differences in trends.
4. **Data Visualization** <br>
Visualization is used to aid interpretation and present findings more intuitively.

## Insights
During the period from 2020 to early 2023, the price movements of five food commodities in Singaraja City showed quite complex dynamics and were influenced by various economic factors and market conditions. Based on the correlation between variables, rice, chicken eggs, and granulated sugar appear to have a relatively direct relationship, where an increase in the price of one commodity is often followed by an increase in the price of other commodities. Meanwhile, garlic and chicken meat show a much more independent pattern with a low level of correlation with other commodities. 

The trend over time shows that rice prices tended to be stable throughout 2020 to 2021, then experienced a sharper increase from 2022 to 2023. A similar condition was also seen in chicken eggs, although this commodity showed much higher fluctuations over time. Granulated sugar experienced a huge surge in early 2020 as a result of the pandemic, but then subsided and moved relatively stable at a lower range until 2022, before increasing again towards 2023. Chicken meat and garlic were the two commodities with the most extreme volatility, with prices fluctuating sharply throughout the analysis period. In the case of garlic, the very high price surge in 2020 was most likely related to import disruptions during the pandemic, followed by a drastic decline once supplies improved.

When prices are averaged annually, it is clear that most commodities have experienced an upward trend from year to year, especially entering 2022–2023. This increase confirms the strong pressure of food inflation after the pandemic. An analysis of price distribution using histograms also shows that rice and granulated sugar have relatively stable price ranges with values concentrated around a certain point, while chicken eggs, chicken meat, and especially garlic show a more dispersed price distribution, reflecting more intense fluctuations. This condition confirms that commodities that depend on imports or have production costs that are sensitive to changes in feed costs tend to experience higher price instability.

Overall, the results of this analysis show that although some food commodities in Singaraja City follow the general inflation trend, several other commodities are greatly influenced by specific supply chain dynamics. The upward price movement since 2022 indicates new pressures in food distribution, which are likely related to rising energy prices, transportation costs, and the recovery of economic activity after the pandemic. These insights can be used as a basis for consideration in planning food pricing policies and stock management strategies in the future.

## Conclusion
Based on analysis trends during the 2020–2023 period, food prices in Singaraja City showed a gradual increase in most commodities, especially entering 2022. Rice, sugar, and eggs moved in a relatively similar direction, indicating the influence of macro factors such as inflation and distribution dynamics. Meanwhile, chicken meat and garlic experienced the greatest fluctuations due to their sensitivity to production costs and dependence on imported supplies. The price surge in early 2020 showed the strong impact of the pandemic on the supply chain, followed by recovery and a resurgence in 2022–2023 due to pressure from logistics and transportation costs. These findings indicate that food price stability is greatly influenced by supply chain conditions and external factors outside the region.
