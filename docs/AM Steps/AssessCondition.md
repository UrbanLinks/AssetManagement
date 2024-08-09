---
sidebar_position: 2
---

# 2. Assess Condition

Once assets are identified and located, assessing their condition is essential to planning current and future investment needs. The accuracy and frequency of the condition assessments can also follow a risk-based hierarchy as suggested for the inventory. It is important that decision-makers are aware of the types of assessment techniques, costs, as well as the results and accuracy they provide, as this will shape their applicability. Age can provide an initial estimate of condition. Maintenance and repair records, such as number of breaks or pothole repairs, provide more detailed feedback on specific asset condition. Visual assessment can be a low-cost, however subjective, solution for accessible assets. Methods for more detailed condition assessment will depend on the type of asset. Newer technologies apply artificial intelligence to automatically collect data and rate condition. Examples of assessment techniques, both common place and novel are discussed below.

Assessing the condition of assets is essential because even assets of the same type can deteriorate at different rates. It is important to consider various aspects beyond just the physical condition. [Hokstad et al. (2010)](https://www.sintef.no/globalassets/upload/teknologi_og_samfunn/sikkerhet-og-palitelighet/rapporter/sintef-a15322-ageing-and-life-extension-for-offshore-facilities-in-general-and-for-specific-systems.pdf) identified three types of ageing: material degradation, obsolescence, and organizational issues. Material degradation can be influenced by factors such as material properties, operating conditions, and environmental conditions. Obsolescence includes aspects such as outdated equipment, the emergence of new technologies, changes in requirements or regulations, and evolving needs. Organizational issues encompass challenges like knowledge transfer, reorganization, and personnel ageing. Despite the multifaceted nature of asset condition, many organizations and utilities still consider only physical condition, and rely solely on the age of the asset.

## Bias in Condition Ratings

 [Canadian water and wastewater utilities](http://canadianinfrastructure.ca/downloads/Canadian_Infrastructure_Report_2016.pdf) have indicated that the most common source of condition information for linear assets is proxy information such as age and pipe material. For non-linear assets, the opinion of municipal staff is the most common source of condition information.  The latter clearly leads to subjective condition assessments, where a motivational bias towards greater local investment can skew results. To avoid this bias, a third party could conduct assessments instead. However, even if a consultant is hired, they are being remunerated by the municipality, and the success of their work is determined by the satisfaction of the client.

The availability bias, whereby the assessor’s estimation of condition is more dependent on memory than an evaluation of possible events, can also affect results. An objective analysis based on visual inspections and relevant data, regardless of the memory of issues arising in the past, could provide more impartial results.  However, availability of data is still an issue for many utilities. For most municipalities embarking on asset management, this is the first time an asset inventory is created. This means the install date of the asset might even be unknown, and previous maintenance has likely not been recorded digitally.

Furthermore, the push for asset management has already generated a public discourse that suggests the state of infrastructure is dire and billions of dollars are needed to rehabilitate and replace it. The age of the infrastructure clearly supports this notion, but the exact condition and need for reinvestment is difficult to ascertain. Moreover, the utilities themselves are responsible for conducting or paying for condition assessments and have an incentive to inflate the size of the deficit. Similarly, some estimates are based on standards set by associations that also benefit from [inflated deficits](https://ogca.ca/wp-content/uploads/2016/05/OSWCA_MAY2016_REPORT_WEB.pdf). 


## Condition Assessment of Facility Assets

Facility assets are commonly assessed through visual inspection. Generally, a rating scale with qualitative indicators is defined. For example, the 1-5 rating scale used by the [US Department of Transportation (DOT)](https://www.transit.dot.gov/sites/fta.dot.gov/files/docs/Facility%20Performance%20Assessment%20Guidebook.pdf) is shown below. An asset is deemed to be in good repair if it has a rating of 3, 4, or 5 on this scale. Conversely, an asset is considered not in good repair if it has a rating of 1 or 2.

| Rating | Condition | Description |
|--------|-----------|-------------|
| 5      | Excellent | No visible defects, new or near new condition, may still be under warranty if applicable |
| 4      | Good      | Good condition, but no longer new, may have some slightly defective or deteriorated component(s), but is overall functional |
| 3      | Adequate  | Moderately deteriorated or defective components; but has not exceeded useful life |
| 2      | Marginal  | Defective or deteriorated component(s) in need of replacement; exceeded useful life |
| 1      | Poor      | Critically damaged component(s) or in need of immediate repair; well past useful life |

This rating scale is quite generic and could be applied to any type of asset. Since this can create more space for subjectivity, condition ratings for specific asset types are useful. As another example, the condition rating for shell assets, also defined by the [US DOT](https://www.transit.dot.gov/sites/fta.dot.gov/files/docs/Facility%20Performance%20Assessment%20Guidebook.pdf), is shown below. Here, the types of defects are clearly defined, as are different facets of conditions, including health and safety concerns.

| Rating | Condition | Description |
|--------|-----------|-------------|
| 5      | Excellent | New construction, no visible defects or damage. |
| 4      | Good      | Minor improvement needed; sub-components are more than five years old but are functioning without issue under routine maintenance. Only minor superficial damage or defect. No sagging, corrosion, cracking, shifting, or leaks. |
| 3      | Adequate  | Repairs are needed. Component or sub-components show signs of minor cracking, drainage issues, sagging, corrosion, or shifting. They are cosmetically “fair”, but functioning as designed. |
| 2      | Marginal  | Component or sub-components show signs of significant cracking, sagging, swelling, corrosion, leaks, or shifting. Significant repairs are needed, but there currently does not appear to be a safety issue on any single sub-component. |
| 1      | Poor      | Component or sub-components have critical defects affecting function, health, or safety. They are in visibly poor condition and must be replaced rather than repaired. They have exceeded their useful life and warrant structural review. |

In some cases, when assets are rated as poor, further structural review is required. This is outside the scope of these notes. These reviews may include examination of field inspection results, review of as-built plans, and/or supplemental structural analysis.

To compile all of the asset ratings in a facility and understand the condition of its systems and the facility as a whole, an overall rating or condition index can be calculated.

A simple approach is to average the ratings of each component (e.g., according to UNIFORMAT, this would include substructure, shell, interiors, etc.) and then determine a facility rating weighted by the replacement cost of the component assets.

A more common and detailed approach is the Facility Condition Index (FCI). 

The original and simpler definition of [FCI](https://www.researchgate.net/publication/331207006_Measuring_the_performance_of_assets_a_review_of_the_Facility_Condition_Index) is as follows:
$$
FCI = \frac{Deferred \ Maintenance \ (DM)}{Current \ Replacement \ Value \ (CRV)}
$$
This ratio, expressed as a percentage, ranges from 0 to 100, where a lower FCI indicates a facility in better condition. Deferred maintenance refers to the cost of maintenance activities that have been delayed and are necessary to bring the asset to its expected condition. 
 The current replacement value is the total cost required to replace the asset at its current level of service.

 The FCI result is usually categorised in three or four levels, depending on the type of facility. [Common thresholds](https://www.researchgate.net/publication/331207006_Measuring_the_performance_of_assets_a_review_of_the_Facility_Condition_Index) are:
* good: 0−5%;
* fair: 5−10%;
* poor: 10−30%;
* critical: 30−100%.

A more recent definition of [FCI](https://www.researchgate.net/publication/331207006_Measuring_the_performance_of_assets_a_review_of_the_Facility_Condition_Index) expands on the first by including additional factors:
$$
FCI = \frac{Deferred \ Maintenance + Major \ Rehabilitation \ and \ Replacement + Maintenance \ Recommendations}{Current \ Replacement \ Value \ (CRV)}
$$
In this approach, major rehabilitation and replacement costs, along with maintenance recommendations, are added to the deferred maintenance costs. This provides a more comprehensive view of the facility's overall condition.

Establishing all of these costs can be a complex task. So in some cases only major rehabilitation and replacement is considered. And, as a rule of thumb, all assets in poor or marginal condition may be considered to be requiring rehabilitation or replacement.


## Condition Assessment of Pavement

Pavement condition assessment can have different focuses depending on the [level of detail required](https://www.fhwa.dot.gov/pavement/management/qm/data_qm_guide.pdf
). Project-Level Assessments are more detailed, structural evaluations aimed at understanding the specific conditions of a pavement segment. They can include, detailed crack mapping and other surface distresses, structural capacity assessment, as well as base and soils characterization. Network-Level Assessments focus on overall deficiencies and broader condition measures, such as roughness, rut depth, cracking, etc. The focus herein is on network assessments, particularly of asphalt pavements.

The **International Roughness Index (IRI)** is a globally recognized metric used to assess the smoothness of pavements. It is typically expressed in meters per kilometer (m/km) and is adopted in accordance with ASTM E1926, *Standard Practice for Computing International Roughness Index of Roads from Longitudinal Profile Measurements,* and AASHTO R 43, *Standard Practice for Quantifying Roughness of Pavements.* The IRI is calculated automatically using profile-measuring sensors—such as laser, acoustic, or infrared—mounted on vehicles that typically travel at 80 km/h. These sensors capture the longitudinal profile of the road, providing an accurate and reliable measure of pavement roughness, essential for evaluating road conditions and guiding maintenance planning.

**Rut depth** is another surface distress measure. However, unlike the IRI, there is no universal consensus on the method of measuring rut depth. The process typically involves using 3 to 5 sensors that scan the transverse profile of the pavement. These sensors are often mounted on a "rut bar," which spans the width of the lane to capture accurate measurements across the pavement surface.  The measurement of rut depth is guided by AASHTO PP 38, *Standard Practice for Determining Maximum Rut Depth in Asphalt Pavements* .

Pavement condition can also be visually assessed by idenitfying various types of surface distresses. And there are standardized indices to quantify these conditions into an overall pavement rating. The most widely used method is the **Pavement Condition Index (PCI)**, defined by ASTM D 6433-07: *Standard Practice for Roads and Parking Lots Pavement Condition Index Surveys* . The PCI method involves identifying and measuring the types of distresses present on the pavement, their severity, and quantity. Each distress type is assigned a deduct value, which is subtracted from a perfect score of 100 to calculate the overall PCI. The final PCI is a numerical rating that ranges from 0 to 100, with higher values indicating better pavement condition. Overall, the PCI considers 19 types of distresses, defined as follows:

1. **Alligator Cracking**: Interconnecting cracks caused by fatigue from repeated traffic loading, typically found only within the wheel paths.

2. **Bleeding**: A shiny film of bituminous material on the pavement surface, resulting from excess asphaltic cement, tar, or sealant. This issue usually occurs during hot weather conditions.

3. **Block Cracking**: Interconnecting cracks that divide the pavement into rectangular blocks, caused by shrinkage and daily temperature cycling.

4. **Bumps and Sags**: Bumps are upward displacements of the pavement, while sags are downward displacements. Both are small, localized issues often caused by the buckling of underlying slabs or the infiltration and buildup of material.

5. **Corrugation**: A series of ridges and valleys appearing at regular intervals (less than 3 meters), running perpendicular to traffic flow. This is caused by a combination of traffic load and an unstable pavement surface.

6. **Depression**: Localized lower areas of the pavement surface, often resulting from the settlement of the soil foundation or improper construction practices.

7. **Edge Cracking**: Cracks that run parallel to the outer edge of the pavement, typically within 0.3 to 0.5 meters of the edge, often caused by a frost-weakened base or subgrade.

8. **Joint Reflection Cracking**: Cracks that occur due to movement of the underlying Portland Cement Concrete (PCC) slab beneath Asphalt Concrete (AC), typically induced by thermal or moisture changes.

9. **Lane/Shoulder Drop Off**: A difference in elevation between the pavement edge and the shoulder, often due to shoulder erosion or settlement.

10. **Longitudinal and Transverse Cracking**: Cracks that run along or across the pavement. These can include reflective cracking, which may originate from cracks in the underlying PCC slab, but does not include PCC joints.

11. **Patching and Utility Cut Patching**: Areas of pavement that have been replaced with new material. Distress in a patched area is recorded separately and not as a new deficiency.

12. **Polished Aggregate**: A condition where the aggregate has become smooth due to repeated traffic, reducing skid resistance.

13. **Potholes**: Small, bowl-shaped depressions with sharp edges, often associated with high-severity alligator cracking.

14. **Railroad Crossing**: Specific distress caused by the interaction of pavement with railroad tracks.

15. **Rutting**: Surface depressions that form in the wheel paths due to repeated traffic loads.

16. **Shoving**: The longitudinal displacement of a localized area of pavement, typically occurring where asphalt meets PCC, and caused by an unstable liquid asphalt mix.

17. **Slippage Cracking**: Crescent-shaped or half-moon cracks caused by the braking or turning of wheels.

18. **Swell**: An upward bulge in the pavement, characterized by a long, gradual wave (greater than 3 meters), often resulting from frost action or swelling soils.

19. **Weathering or Raveling**: The wearing away of the pavement surface due to the loss of asphalt or tar binder and the dislodging of aggregate, often caused by hardened binder or a poor-quality mixture.


## Condition Assessment of Underground Assets

Underground condition assessment presents unique challenges due to the inaccessibility of the assets involved. Common underground assets include water and sewer pipes, gas lines, telecommunication cables, and electrical lines. This discussion focuses on municipally owned assets, i.e. water and sewer pipes. Some of the techniques mentioned earlier for asset localization can also be used for assessing these assets, such as Ground Penetrating Radar (GPR), acoustics, and electromagnetic methods. When selecting these methods, not only shoudl their costs and applicability be considered, but also the operational characteristics of these systems.

Water systems, for example, are pressurized, typically operating between 60-80 psi, with a minimum pressure requirement around 20 psi. Maintaining water quality is also a critical concern during assessments. Sewer systems, on the other hand, generally consist of gravity mains, though forcemains may also be present, with a minimum pressure of around 10 psi. The presence of gases generated within the sewer system adds an additional layer of complexity to the assessment process.

Logistical planning for these assessments must account for various factors, including the potential shutdown, isolation, and dewatering of the pipeline, as well as access points and the operating conditions of the system, i.e. pressure and flow. The configuration of the pipeline—its size, bends, slope, length, and potential obstructions—must also be considered in planning the assessment, closing lines and lateral valves and implementing potential bypass systems. This ensures service disruption is minimized and avoids equipment getting stuck and/or lost. Health and safety precautions are also important, including traffic control, barricading, shoring, and ensuring worker protection through confined space entry procedures, as needed. Additionally, tools, materials, and the pipe itself may need to be disinfected.

Prioritization in underground condition assessment is crucial due to the varying risk levels of different assets as well as the range of costs and types of results provided by the assessment techniques. The AWWA *Manual M77* recommends that four key variables be considered, as follows:
* Degree of Inspection: Ranging from assessing general conditions to detecting single defects.
* Inspection Coverage: Ranging from assessing single pipes to the whole network.
* Pipeline Access: Considering the ease of access and the potential for shutdowns.
* Cost of Assessment: Balancing the cost of the assessment with the asset’s risk and value.

The same manual suggests a progressive approach to condition assessment
1. **Desktop Study:** Gather existing data for initial insights.
2. **Survey-Level Inspection:** Conduct broad assessments to identify areas of concern.
3. **External NDT Inspection:** Use non-destructive techniques (NDTs) to assess the pipe from the outside.
4. **Internal NDT Inspection:** Apply NDTs internally for detailed analysis.
5. **Material Testing:** Analyze pipe materials through coupons.

A summary of common underground condition assessment techniques is provided in the table below, based on information compiled from the [Water Research Foundation](https://www.waterrf.org/research/projects/condition-assessment-strategies-and-protocols-water-and-wastewater-utility-assets) and [HDR](https://delivr.com/2hqfk)


### Soil Characterization, Corrosion Sensing, and Thermographic Testing

| Type                      | Soil Characterization | Corrosion Sensing               | Pitting Depth Measurement     | Thermographic Testing           |
|---------------------------|-----------------------|---------------------------------|-------------------------------|---------------------------------|
| **Location**              | Outside               | On pipe                         | On pipe                       | Outside                         |
| **Tool or Technique**     | Soil resistivity      | Corrosion rate sensor           | Pit depth measurement         | Passive infrared thermography   |
| **Principle**             | Electrodes measure drop in electrical potential | Compares corrosion of an exposed pipe ferric element with a sealed reference coupon | Measures the depth of pits developed through corrosion | Detect thermal anomalies through infrared imaging |
| **Service Type**          | Water and Sewer       | Water and Sewer                 | Water and Sewer               | Water and Sewer                 |
| **Material**              | Ferrous               | Ductile Iron                    | Ferrous                       | Any                             |
| **Type of Results**       | Soil corrosion potential | Predicts corrosion rate       | Pit depth to infer corrosion  | Detection of leaks and voids    |
| **Service Interruption**  | NA                    | NA                              | On line when done in-situ     | On line                         |
| **Access**                | NA                    | Direct access to pipe wall      | Direct access to pipe wall    | NA                              |
| **Skills Required**       | Operator training     | Operator training               | Basic                         | Operator training               |
| **Limitations**           | Indicative of corrosion rate, further analysis needed | Point measurement, multiple sensors required | Need to expose pipe or cut coupon, coating needs to be removed | Requires temperature difference to identify anomalies |
| **Cost**                  | $                     | $$                              | $                             | $                               |

### Ultrasonic and Acoustic Inspections

| Type                      | Ultrasonic Testing (Guided Wave) | Ultrasonic Testing (Discrete Measurement) | Acoustic Inspection (On Pipe) | Acoustic Inspection (In Pipe)  |
|---------------------------|----------------------------------|-------------------------------------------|--------------------------------|--------------------------------|
| **Location**              | On pipe                          | On pipe                                   | On pipe                        | In pipe                        |
| **Tool or Technique**     | Guided wave ultrasonic testing   | Ultrasonic discrete measurement           | Acoustic emission              | Acoustic leak detection - Smart Ball® |
| **Principle**             | Transducers emit waves reflected by anomalies | High-frequency wave propagation       | Detection of sound waves generated from within the material | Ball emits acoustic pulse tracked by receiver |
| **Service Type**          | Water and Sewer                  | Water and Sewer                           | Water and Sewer                | Water and Sewer                |
| **Material**              | Iron and steel                   | Iron and steel                            | Any                            | Any                            |
| **Type of Results**       | Wall thickness, corrosion pit depth | Wall thickness, corrosion pit depth      | Detection and location of defects | Detection of leaks, air pockets |
| **Service Interruption**  | On line                          | On line                                   | On line (sensor installation might require interruption) | On line                         |
| **Access**                | Direct contact with pipe required | Direct contact with pipe required         | NA                             | Man entry                      |
| **Skills Required**       | Basic operation, advanced analysis | Trained technician                        | Operator training              | Specialist service             |
| **Limitations**           | Limited inspection range, not for heavily coated pipes | Difficult to inspect rough, irregular, or heterogeneous materials | Can only detect what happens during monitoring, only qualitative info | Pressures between 15 and 400 psi, qualitative estimation |
| **Cost**                  | $                                | $                                         | $$                             | $$                             |


### Electromagnetic and Visual Inspections

| Type                      | Electromagnetic Inspection (Remote Field Eddy Current) | Electromagnetic Inspection (Broadband) | Electromagnetic Inspection (Magnetic Flux Leakage) | Visual Inspection (CCTV)          |
|---------------------------|--------------------------------------------------------|----------------------------------------|----------------------------------------------------|-----------------------------------|
| **Location**              | In pipe                                                 | In pipe                                | In pipe                                            | In pipe                           |
| **Tool or Technique**     | Remote field eddy current                               | Broadband electromagnetic              | Magnetic flux leakage                              | CCTV                              |
| **Principle**             | Exciter coil driven by low-frequency alternating current | Transmits broad frequency spectrum     | Large magnets induce a magnetic field              | Records close-up observation of pipe surface |
| **Service Type**          | Water and Sewer                                         | Water                                  | Water and Sewer                                    | Mostly Sewer                     |
| **Material**              | Iron, steel, PCCP                                       | Steel, cast iron, ductile iron         | Iron and steel                                     | Any (less useful for plastics)     |
| **Type of Results**       | Internal or external defects                            | Remaining wall thickness               | Metal loss                                         | Structural condition (qualitative) |
| **Service Interruption**  | Off line (pipe needs depressurization)                  | Off line (pipe needs depressurization) | On line (external) or off line (internal)          | Low flow or offline for pressurized pipes |
| **Access**                | Cut-ins required for some tools; pipes >150 mm diameter | Exposure of pipe surface               | Direct access to pipe wall                         | Internal use, mostly for pipes>90 mm |
| **Skills Required**       | Specialist service                                     | Specialist service                     | Specialist service                                 | Specialist skills                  |
| **Limitations**           | Tools may require cleaning and dewatering              | Scanning is time-consuming             | Requires direct contact with the wall              | Only detects defects on the pipe's inner surface, limited speed |
| **Cost**                  | $$$$                                                   | $$$                                    | $$$$                                               | $                                 |


The results of underground condition assessments can be subjective and challenging to compile, especially when data comes from different sources. This is where standardization becomes crucial, particularly for visual inspections using Closed Circuit Television (CCTV). The National Association of Sewer Service Companies (NASSCO) developed the [Pipeline Assessment Certification Program (PACP)](https://nassco.org/education-and-training/pacp-lacp-macp/?scLang=en) to address this need. PACP provides a standardized coding system for assessing sewer pipelines, encompassing structural defects, operational and maintenance issues, construction features, and other miscellaneous characteristics. The benefits of this standardization include consistency, reliable data, condition grades, enhanced communication, standardized training, broad support, actionable recommendations, potential reduction in inspection costs, fair competition among suppliers and contractors, and widespread industry acceptance. 