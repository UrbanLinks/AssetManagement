---
sidebar_position: 3
---

# 3. Determine Residual Life

The residual life of an asset is the remaining period of time during which the asset can be in service before being replaced or decommissioning. The residual life may be influenced by different aspects, such as:
* Financial: The asset is considered fully depreciated in accounting terms, meaning it has no remaining book value, even if it still functions.
* Physical: The asset has deteriorated to the point where it is no longer operational or functional.
* Service Level: The asset no longer meets the performance or quality requirements of stakeholders, even if it still operates.
* Capacity: The asset's original design capacity has been exceeded, rendering it insufficient for current demands.
* Economic: The asset is no longer the most cost-effective option, and continuing to operate it is more expensive than alternatives.

Herein the focus will be on determining physical deterioration. This deterioration is a function of the asset’s intrinsic physical characteristics, environmental factors and operational [factors](https://www.sciencedirect.com/science/article/abs/pii/S0043135419307006?via%3Dihub). Deterioration can be simplified by assuming values of "Expected Useful Life" for each asset types or it can be modeled.


## Expected Useful Life

The expected useful life (EUL), as defined by the International Infrastructure Management Manual is "the period over which an asset is expected to be available for use by an entity". To simplify asset management planning, values of EUL are often set for each type of asset.

For example, Statistics Canada collects data on average EUL for different public asset types.
The Canada-wide averages for [road assets in 2020](https://www150.statcan.gc.ca/t1/tbl1/en/tv.action?pid=3410007301) were:
- **Highways**: 33 years
- **Rural highways**: 23 years
- **Arterial roads**: 32 years
- **Collector roads**: 28 years
- **Local roads**: 29 years
- **Lanes and alleys**: 31 years
- **Sidewalks**: 32 years
Similarly, Canada-wide averages for [potable water assets in 2020](https://www150.statcan.gc.ca/t1/tbl1/en/tv.action?pid=3410019901) were:
- **Water treatment facilities**: 33 years
- **Water reservoirs (including dams) before intake**: 27 years
- **Storage tanks after intake not part of a treatment plant**: 40 years
- **Water pump stations**: 30 years
- **Local water pipes (diameter less than 416 mm)**: 63 years
- **Transmission pipes (diameter greater than or equal to 416 mm)**: 71 years
- **Pipes of unknown diameter**: 49 years
Other types of assets such as public facilities, sewer and stormwater assets, bridges and tunnels can also be found on the Statistics Canada website.

These values are useful for comparison and high-level planning, yet for planning work within a single facility or infrastructure system, assets and their EUL must be defined at a lower level. 

The [province of British Columbia](https://www2.gov.bc.ca/assets/gov/housing-and-tenancy/residential-tenancies/policy-guidelines/gl40.pdf) provides guidlines for establishing EUL of building elements. An excerpt of their guideline is provided in the table below.

| ELEMENTS                | EUL (Years) |
|-------------------------|-------|
| 1. Doors                | 20    |
| 2. Garage door and operator | 10    |
| 3. Lock replacement, building | 20    |
| 4. Windows              | 15    |
| 5. Window framing       |       |
| &nbsp;&nbsp;&nbsp;&nbsp;i. Wood     | 15    |
| &nbsp;&nbsp;&nbsp;&nbsp;ii. Aluminium | 20    |

The [City of Toronto](https://www.toronto.ca/wp-content/uploads/2019/04/9659-TS_Pavement-Design-and-Rehabilitation-Guideline.pdf) established EUL for pavement according to the current condition and type of rehabilitation performed, as shown below.
| Activity Category | Activity Name                           | Activity Description                                      | EUL (Yrs)               |
|-------------------|-----------------------------------------|----------------------------------------------------------|--------------------------------------------|
| Construction      | Reconstruction                          | Rebuild entire pavement structure, improve drainage       | 30 for flexible pavement <br> 30 for rigid pavement |
| Construction      | Partial Pavement Reconstruction         | Rebuild flexible/rigid pavement layers                    | 25 for flexible <br> 30 for rigid          |
| Rehabilitation    | Cold Recycling (Flexible Pavements on local roads) | Recycle in-place Hot Mix Asphalt (HMA) layers (full depth)               | 20-25+                                     |
| Rehabilitation    | Resurfacing                             | Replace 2 lifts HMA and base repairs                      | 20 - 25                                    |
| Rehabilitation    | 'Mill and Pave' (1 lift)                | Replace 1 lift of HMA                                     | 18 - 22                                    |
| Rehabilitation    | Overlay (1 lift)                        | Place 1 lift HMA over existing surface                    | 10 - 20                                    |

The [City of Toronto](https://www.toronto.ca/legdocs/mmis/2008/ex/bgrd/backgroundfile-16566.pdf) also analysed the life expectancies of water and sewer pipes of different materials, to establish EUL, as sumamrized below. 

| Water Pipe Description                                               | EUL (Years) |
|-----------------------------------------------------------|-------------|
| Cast Iron, Pit Cast (\<1950), Original, Diam = 150 mm      | 60-80       |
| Cast Iron, Pit Cast (\<1950), Original, Diam \> 150 mm      | 70-90       |
| Cast Iron, Pit Cast (\<1950), Cleaned & Lined, Diam = 150 mm | 15-25       |
| Cast Iron, Pit Cast (\<1950), Cleaned & Lined, Diam \> 150 mm | 25-35       |
| Cast Iron, Spun Cast (\>=1950), Original, Diam = 150 mm    | 20-40       |
| Cast Iron, Spun Cast (\>=1950), Original, Diam \> 150 mm    | 30-50       |
| Cast Iron, Spun Cast (\>=1950), Cleaned & Lined, Diam = 150 mm | 5-10        |
| Cast Iron, Spun Cast (\>=1950), Cleaned & Lined, Diam \> 150 mm | 10-15       |
| Ductile Iron, Diam = 150 mm                               | 40-60       |
| Ductile Iron, Diam \> 150 mm                               | 50-70       |
| Ductile Iron, Cathodically Protected, Diam = 150 mm       | 15-25       |
| Ductile Iron, Cathodically Protected, Diam \> 150 mm       | 25-35       |
| Polyvinyl Chloride, All Sizes                             | 70-90       |
| Metro Trunk and Steel, All Sizes                          | 80-100      |
| Other material (concrete, copper, AC, etc.), All Sizes    | 40-60       |


| Sewer Pipe Description                                       | EUL (Years) |
|---------------------------------------------------|-------------|
| Concrete, Diam \<= 450 mm                           | 50-70       |
| Concrete, Diam \> 450 mm                           | 70-90       |
| Brick, All Sizes                                  | 70-90       |
| Vitrified Clay, Diam \<= 375 mm                     | 50-70       |
| Vitrified Clay, Diam \> 375 mm                     | 60-80       |
| Polyvinylchloride, All Sizes                      | 20-30       |
| Asbestos Cement, All Sizes                        | 80-90       |
| Other material, All Sizes                         | 20-30       |

With these initial estimates of EUL, if additional information on the assets is unknown, the remaining useful life can simply be calculated according to asset age, as follows.
$$
Remaining \ Useful \ Life = Expected \ Useful \ Life - Age
$$

If the condition of the asset is known, this calculation can be improved by calculating apparent age.
$$
Apparent \ Age = Expected \ Useful \ Life \times \frac{|Current \ Condition - Best \ Condition \ Rating|}{|Best \ Condition \ Rating - Worst \ Condition \ Rating|}
$$

## Deterioration Models

Deterioration can be modelled physically or statistically, relying on estimates of loads or extending historical performance into the future, respectively. The latter does not require detailed data on all factors leading to infrastructure failure but can predict deterioration based on the performance of similar assets under similar conditions.

### Physical Models

### Statistical Models

#### Deterministic Models

#### Probabilistic Models
