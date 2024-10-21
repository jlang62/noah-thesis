# Hypothesis Results Document

## Hypothesis 1:
**Viewing live footage significantly influences the choice of ski resort.**
This hypothesis tests whether the availability of live footage impacts the decision-making process of potential visitors.
**Results (Chi-squared):**
- Chi-squared Statistic: **0.0254**
- p-value: **0.8733**
A p-value greater than 0.05 suggests that there is not enough evidence to reject the null hypothesis, indicating that live footage may not significantly influence choice.
**Conclusion:** The findings indicate that live footage does not play a significant role in influencing the choice of ski resort among visitors, suggesting that other factors may be more decisive in their decision-making process.

## Hypothesis 2:
**Frequent visitors to ski resorts are more likely to rely on live footage.**
This hypothesis examines the correlation between how often respondents visit ski resorts and their usage of live footage to aid in their decision-making.
**Correlation (Visit Frequency vs. Live Footage Usage):**
|    | Visit Frequency   |   Live Footage Usage |
|---:|:------------------|---------------------:|
|  0 |                   |                  nan |
|  1 |                   |                    1 |
**Conclusion:** Further analysis is needed to understand the nature of this correlation. While frequent visitors may engage with live footage, the exact impact on decision-making requires additional research.

## Hypothesis 3:
**Specific factors seen on live footage have a stronger impact on ski resort choice.**
This hypothesis focuses on identifying which factors from live footage most influence the choice of ski resort.
**Factor Counts:**
- Results:
  Series([], dtype: float64)
**Conclusion:** More data is required to determine the specific factors influencing choice from live footage, as current results are inconclusive.

## Hypothesis 4:
**Ski resort visitors who find live footage accurate are more satisfied with their overall experience.**
This hypothesis investigates the relationship between the accuracy of live footage and visitor satisfaction after their visit.
**Satisfaction Correlation:**
|    |   After visiting how often has your experience matched your expectations set by live footage? |   Overall satisfaction with visit |
|---:|----------------------------------------------------------------------------------------------:|----------------------------------:|
|  0 |                                                                                        1      |                            0.5048 |
|  1 |                                                                                        0.5048 |                            1      |
**Conclusion:** There appears to be a positive correlation between satisfaction and the accuracy of live footage. This suggests that enhancing the quality and reliability of live footage could improve visitor satisfaction.
## Hypothesis 5:
**Age groups have different preferences for live footage usage.**
This hypothesis analyzes whether different age demographics exhibit varying levels of preference for using live footage when choosing a ski resort.
**Results (Chi-squared):**
- Chi-squared Statistic: **5.3352**
- p-value: **0.5016**
A p-value greater than 0.05 indicates insufficient evidence to reject the null hypothesis.
**Conclusion:** The results suggest that age does not significantly influence preferences for live footage usage, but further exploration is needed to understand the nuances across different age groups.

## Hypothesis 6:
**Visitors who find live footage to be reliable are more likely to revisit the ski resort.**
This hypothesis tests whether the reliability of live footage correlates with a visitor's likelihood of returning to the ski resort.
**Correlation (Reliability vs. Revisiting):**
|    |   Are you more likely to revisit a ski resort if they provide reliable and satisfactory live footage? |   After visiting how often has your experience matched your expectations set by live footage? |
|---:|------------------------------------------------------------------------------------------------------:|----------------------------------------------------------------------------------------------:|
|  0 |                                                                                                1      |                                                                                        0.3552 |
|  1 |                                                                                                0.3552 |                                                                                        1      |
**Conclusion:** Reliability of live footage does seem to play a role in the likelihood of revisiting. Enhancing the quality and consistency of live footage could encourage repeat visits.
## Hypothesis 7:
**Locals are more likely to base their decision on live footage than tourists.**
This hypothesis looks at how the residency status of visitors (local vs. tourist) affects their reliance on live footage when choosing ski resorts.
**Decision Influence:**
|   Are you a local or tourist? |   Has live footage ever led you to choose one ski resort over another? |
|------------------------------:|-----------------------------------------------------------------------:|
|                             1 |                                                                 0.2947 |
|                             2 |                                                                 0.7302 |
**Conclusion:** The results indicate that locals might rely more on live footage when making their choices compared to tourists. This could reflect a greater familiarity with the local conditions showcased in the footage.
