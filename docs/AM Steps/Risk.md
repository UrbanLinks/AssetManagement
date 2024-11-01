---
sidebar_position: 6
---

# 6. Determine Asset Risk 


The key steps for risk management according to [ISO 3100](https://www.iso.org/iso-31000-risk-management.html) are (1) definition of scope, context and criteria; (2) risk assessment; and (3) risk treatment. Risk assessment includes risk identification, analysis and evaluation. 

In the contect of infrastructure risk management, the [Canadian InfraGuide](https://fcm.ca/sites/default/files/documents/resources/guide/infraguide-managing-risk-mamp.pdf) defines risk as the combination of the probability and consequence of an event that hinders the infrastructure assets' ability to meet required level of service.
Simply put, an asset's risk of failure is the product of probability and consequence of failure

$$
Risk = text{Probability of Failure} \cdot \text{Consequence of Failure}
$$

## Probability of Failure

The proability of failure represents how likely the asset failure event is. This could be directly calculated through the deterioration models mentioned in the Determine Residual Life section, or estimated according to categories of likelihood, ranging for example, from unlikely to frequent.

## Consequence of Failure

The consequence of failure represents the severity of a failure on that asset. Because impacts of asset failure may be felt in different spheres, consequences can be categorized, such as follows:
- **Injury**: The potential for harm or injury to people, ranging from minor injuries to fatalities.
- **Service Interruption**: The impact on the availability of the service, which may range from brief interruptions lasting seconds to prolonged outages over months.
- **Environment**: The environmental impact of a failure, from minor effects that can be corrected by the organization to more extensive damage needing intervention from multiple government levels.
- **Financial**: The direct economic impact on the organization, which compared to the organization's capital budget might range from negligible costs (e.g. less than 1%) to significant (e.g. more than 10%).
- **Reputation**: The impact on public perception, ranging from local community concern to widespread national media coverage.

To systematically evaluate the consequence of failure of each asset in an infrastructure system, quantifying the consequnces in each sphere can be quite complex. Instead a framework of criteria and indicators can be developed. 
For instance, if three general types of consequences are defined for a road system, economic, social and environmental, indicators for each of these categories can be defined.
- **Economic**: Road type, land use type and average annual daily traffic
- **Social**: Critical customers, bus route and ambulance route.
- **Environmental**: Truck route, green spaces and water bodies.
Each indicator contains information on features that would lead to lower or higher consequences of failure. For example, if the road type is local, consequences are likely lower than if the road type is highway. Similarly if the asset is next to critical customers, such as hospitals, transit stations and community centers, consequences would be higher. Based on this logic, scores can be assigned to each class within each criteria, as exemplified below. The selection of scores should follow the same range, e.g. 0 to 100, but will depend on the classes and criteria relevant to each system. Each organization will select the criteria that best represent consequence of failure and for which they have supporting data available. The criteria used in this example are all commonly available in a road asset inventory and other municipal data sources.

| Road Type                | Road Type Score | Land Use              | Land Use Score | Average Annual Daily Traffic | Traffic Score |
|--------------------------|-----------------|-----------------------|----------------|------------------------------|---------------|
| Local                    | 10              | Residential           | 10             | Low                          | 10            |
| Collector                | 50              | Mixed Use             | 50             | Medium                       | 50            |
| Highway                  | 100             | Commercial or Industry| 100            | High                         | 100           |

| Critical Customers           | Critical Customers Score | Bus Route        | Bus Route Score | Ambulance Route    | Ambulance Route Score |
|------------------------------|--------------------------|------------------|-----------------|--------------------|------------------------|
| Yes                          | 100                      | Yes              | 100             | Yes                | 100                    |
| No                           | 0                        | No               | 0               | No                 | 0                      |

| Truck Route          | Truck Route Score | Green Space        | Green Space Score | Water Bodies        | Water Bodies Score |
|----------------------|-------------------|--------------------|-------------------|----------------------|---------------------|
| Yes                  | 100               | Yes                | 100               | Yes                  | 100                 |
| No                   | 0                 | No                 | 0                 | No                   | 0                   |


The scores for each asset will depend on their characteristics. Continuing the road example, assume a road asset has the following characeristics.

| Asset ID | Road Type | Land Use   | AADT  | Critical Customers | Bus Route | Ambulance Route | Truck Route | Green Space | Water Bodies |
|----------|-----------|------------|-------|--------------------|-----------|-----------------|-------------|-------------|--------------|
| 1        | Local     | Mixed Use  | Low   | Yes                | Yes       | Yes             | No          | Yes         | No           |

Based on these characteristics and the previously defined score, the scores for thi asset would be as follows.

| Asset ID | Road Type Score | Land Use Score | AADT Score | Critical Customers Score | Bus Route Score | Ambulance Route Score | Truck Route Score | Green Space Score | Water Bodies Score |
|----------|------------------|----------------|------------|--------------------------|-----------------|-----------------------|--------------------|--------------------|---------------------|
| 1        | 10               | 50             | 10         | 100                      | 100             | 100                   | 0                  | 100                | 0                   |

To compile these scores into a single consequence score, a weighted sum of scores should be calculated. The weights should be defined by the organization based on the importance of specific criteria, as well as the overall importance of each consequence category, i.e. economic, social and environmental. This weighting can be defined through internal stakeholder surveys. One common approach for doing this is the Analytical Hierarhcy Process [(AHP)](https://www.sciencedirect.com/science/article/abs/pii/037722179090057I).

For simplicity in this example, let's assume equal weights among criteria and categories. In that case, for the asset shown in the table above, the overall consequence score would be 52.22. To calculated the final risk score, the consequence score would then be multiplied by the probability of failure score. Note that the probability of failure scores and consequence of failure scores should always be defined in the same ranges.


## Management Strategies
 
 Once the risk of failure of each asset is identified, management strategies for each should be selected.
The general approaches to risk treatment include:
- **Accept**: Choosing to take no action and accept the risk as it is.
- **Avoid**: Taking steps to eliminate the risk, such as by choosing a different solution or immediately replacing the asset.
- **Transfer**: Shifting the risk to a third party, such as using insurance to cover unexpected events.
- **Reduce**: Mitigating the risk by taking measures to minimize its impact, such as maintaining or rehabilitating the asset.

The selection of the strategy generally depends on the asset's current risk of failure. The table below exemplifies a common approach of assigning strategies within a risk matrix. 

| Consequence of Failure ↓ / Likelihood of Failure → | Rare            | Unlikely        | Possible        | Likely          | Almost Certain  |
|-----------------------------------------------------|-----------------|-----------------|-----------------|-----------------|-----------------|
| Catastrophic                                        | Monitor         | Schedule Renewal| Fix Soon         | Fix Now!        | Fix Now!        |
| Major                                               | Monitor         | Monitor         | Schedule Renewal| Fix Soon        | Fix Now!        |
| Moderate                                            | Monitor         | Monitor         | Monitor         | Schedule Renewal| Fix Soon        |
| Minor                                               | Fix on Failure  | Fix on Failure  | Fix on Failure  | Monitor         | Schedule Renewal|
| Insignificant                                       | Fix on Failure  | Fix on Failure  | Fix on Failure  | Monitor         | Monitor         |
