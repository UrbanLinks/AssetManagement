---
sidebar_position: 3
---


# 3. Determine Residual Life

The residual life of an asset is the remaining period of time during which the asset can be in service before being replaced or decommissioning. The residual life may be influenced by different aspects, such as:
* **Financial**: The asset is considered fully depreciated in accounting terms, meaning it has no remaining book value, even if it still functions.
* **Physical**: The asset has deteriorated to the point where it is no longer operational or functional.
* **Service Level**: The asset no longer meets the performance or quality requirements of stakeholders, even if it still operates.
* **Capacity**: The asset's original design capacity has been exceeded, rendering it insufficient for current demands.
* **Economic**: The asset is no longer the most cost-effective option, and continuing to operate it is more expensive than alternatives.

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
| Construction      | Reconstruction                          | Rebuild entire pavement structure, improve drainage       | 30 for flexible pavement <br /> 30 for rigid pavement |
| Construction      | Partial Pavement Reconstruction         | Rebuild flexible/rigid pavement layers                    | 25 for flexible <br /> 30 for rigid          |
| Rehabilitation    | Cold Recycling (Flexible Pavements on local roads) | Recycle in-place Hot Mix Asphalt (HMA) layers (full depth)               | 20-25+                                     |
| Rehabilitation    | Resurfacing                             | Replace 2 lifts HMA and base repairs                      | 20 - 25                                    |
| Rehabilitation    | 'Mill and Pave' (1 lift)                | Replace 1 lift of HMA                                     | 18 - 22                                    |
| Rehabilitation    | Overlay (1 lift)                        | Place 1 lift HMA over existing surface                    | 10 - 20                                    |


The [City of Toronto](https://www.toronto.ca/legdocs/mmis/2008/ex/bgrd/backgroundfile-16566.pdf) also analysed the life expectancies of water and sewer pipes of different materials, to establish EUL, as summarized below. 

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

Deterioration models can generally be categorised as physical or statistical. Physical (or mechanistic) models use equations for stress or strain of the asset, whereas statistical (or empirical) models use historical data to establish new empirical equations. Physical, or models are generally more complex as they required detailed measurements and information on the characteristics and conditions of single assets. Thus, they are more commonly applied to critical assets. Statistical models, on the other hand, can predict deterioration based on the performance of similar assets under similar conditions. Each of these types of models and their variations is further described in the following subsections.

### Physical Models - Mechanistic and Mechanistic-Empirical

Particularly in the domain of pavement design and deterioration, two types of physical (mechanistic) based models are defined, purely mechanistic and mechanistic-empirical. Purely mechanistic models predict a primary response, i.e. stress or strain of the asset. Mechanistic-emprirical models apply these mechanistic concepts to predict a measured structural or functional deterioration, such as cracking. They employ empirical coefficients to relate the mechanistic equations to deterioration. 

#### Mechanistic Models

Stress and strain are fundamental concepts used to describe the behavior of assets in physical models. Stress is defined as the force applied per unit area:

$$
Stress = \frac{Load}{Area}
$$

Strain is the deformation or displacement of material relative to its original length:

$$
Strain = \frac{Change \ in \ Length}{Original \ Length}
$$

Early [mechanistic models](https://doi.org/10.1680/dmp.41141.245) for pavement design were initially developed by considering stress and strain within a single material layer. Boussinesq pioneered this approach in 1885 by analyzing a cylindrical load applied to soil, assuming a homogeneous, isotropic, and linearly elastic space. In 1949, Odemark extended these ideas to layered systems, making a key assumption that the response beneath any given layer is influenced solely by the stiffness of that layer. This was also extended upon by many studies. While purely mechanistic models serve as a valuable foundation, pavement deterioration models generally use mechanistic-empirical approaches. More detailed mechanistis analyses, such as finite element analyses are restricted to specialized studies and research, where a deep understanding of stress distribution and material behaviour is required.

A common mechanistic emprirical approach for pavement is that developed by the American Association of State Highway and Transportation Officials (AASHTO). AASHTO's Mechanistic-Empirical Pavement Design Guide (MEPDG) predicts several key pavement performance indicators, including rutting, cracking, and roughness.
As an example, the rutting equations applied by MEPDG are presented here. 
rutting by considering the permanent vertical deformation across various pavement layers, including Hot Mix Asphalt (HMA), unbound layers, and the foundation soil. The approach involves calculating incremental rutting within each sublayer for different sub-seasonal conditions.

For HMA layers, the accumulated permanent deformation is given by:
​
$$
\Delta p_{(HMA)} = \beta_{r1} \cdot k_z \cdot \epsilon_r(HMA) \cdot 10^{k_{1r}} \cdot n^{k_{2r} \beta_{r2}} \cdot T^{k_{3r} \beta_{r3}}
$$
 
Where:
$\Delta p_{(HMA)}$ = Accumulated permanent vertical deformation in the HMA layer/sublayer (in inches)
$\epsilon_{p(HMA)}$ = Accumulated permanent axial strain in the HMA layer/sublayer (in/in)
$\epsilon_{r(HMA)}$ = Resilient (elastic) strain at the mid-depth of each HMA sublayer (in/in)
$h_{HMA}$ = Thickness of the HMA layer/sublayer (in inches)
$n$ = Number of axle-load repetitions
$T$ = Mix or pavement temperature (°F)
$k_{1r}, k_{2r}, k_{3r}$ = Global field calibration parameters

For unbound layers, i.e. layers with no binding agent, such as base, subbase and soil layers, the rutting model is expressed as:

$$
\Delta p_{(Soil)} = \beta_{s1} \cdot k_{s1} \cdot \epsilon_v \cdot h_{soil} \cdot \left(\frac{\epsilon_o}{\epsilon_r}\right) \cdot \exp \left(-\left(\frac{n}{\rho}\right)^{\beta}\right)
$$

Where:
$\Delta p_{(Soil)}$ = Permanent vertical deformation in the soil layer/sublayer (in inches)
$\epsilon_o$ = Intercept from laboratory repeated load permanent deformation tests (in/in)
$\epsilon_r$ = Resilient strain from the laboratory test (in/in)
$\epsilon_v$ = Average vertical resilient strain in the soil layer (in/in)
$h_{Soil}$ = Thickness of the unbound layer/sublayer (in inches)
$k_{s1}$ = Global calibration coefficients

From these equations it is clear that the approach relies heavily on the mechanistic properties of the material, and  is calibrated empirically by finding the relevant field parameters. Other equations are also defined for cracking. And the change in roughness is calculated based on the resulting predictions of rutting and cracking. Furthermore, while the equations were developed by AASHTO in the US, they can be calibrated to other locations.

In Canada, a [long term pavement performance](https://doi.org/10.1139/l03-023) study was conducted to investigate pavement deterioration across the country, in 65 sections at 24 sites. Different from the MEPDG, in this approach roughness is directly estimated. A general equation for pavement deterioration is suggested as follows.

$$
PD = 0.137 - 0.000998OT + 0.000504PC + 0.0354DR - 0.0266OM + 0.0380FDE - 0.0000827FI + 0.00117DP + 0.0000000223ESAL8
$$

Where:
- **PD** = Pavement Deterioration Rate (IRI/year)
- **OT** = Overlay Thickness (mm)
- **PC** = Prior Cracking (m/150 m)
- **DR** = Deflection Ratio, measured using a falling-weight deflectometer, comparing the maximum pavement deflection under load to the average summer deflection
- **OM** = Type of Overlay Material (0 for virgin, 1 for recycled)
- **FDE** = Fatigue Damage Estimate (% of design ESALs)
- **FI** = Freezing Index (°C·d), cumulative sum of sub-freezing temperatures over a year
- **DP** = Days with Precipitation (per year)
- **ESAL8** = Accumulated Equivalent Single Axle Loads (ESALs) after 8 years. ESALs are standardized traffic loads, expressed in the number of 18,000-pound single axle loads.

Pipe deterioration models, like those used for pavements, are rarely purely mechanistic either due to the complex environmental interactions involved. Water pipes are subjected to various stresses that can lead to different types of failures. Axial stress, caused by soil movement or thermal expansion, often results in circumferential breaks, where the pipe cracks around its circumference. Bending stress, induced by external loads such as heavy traffic, can also contribute to circumferential breaks. Hoop stress, generated by internal water pressure, typically causes longitudinal splits along the length of the pipe, especially if there are pre-existing defects. Additionally, corrosion, which weakens the pipe wall over time, combined with radial forces, can lead to the formation of holes, including both blowouts and pinhole leaks. An early approach to model loads on water mains was developed by [Zhan and Rajani (1997)](https://doi.org/10.1139/cgj-34-4-568). They defined an equation for frost load in a typical trench considering factors such as frost depth, frost heave, trench width, soil stiffness, and used the same type of Boussinesq function to determine the influence of stress. 


### Statistical Models

Statistical/Empirical models rely on historical data to predict asset deterioration. They are generally more commonly applied as the data collection is simpler than that for mechanistic models, as it uses the best available data and relies on proxies or related factors, rather then specific physical properties. For example, in a statistical model a coefficient for each type of material may be assumed rather than measured. Statistical models can be largely classified into two groups Deterministic or Probabilistic. 
**Deterministic** models predict a single deterioration result and ignore uncertainty, such as an asset's condition index within 5 years. Whereas **Probabilistic models** predict the probability of various states, such as the likelihood of an asset to reach a certain condition index within 5 years.

#### Deterministic Models

One of the simplest types of deterministic deterioration models is the linear temporal regression, i.e. the deterioration is assumed to increase linearly with time.
For example, [Kettler and Goulter (1985)](https://doi.org/10.1139/l85-030) defined the following equation to predict pipe breaks.

$$
N = k \cdot \text{Age}
$$

Where:
- **N** is the number of breaks per year.
- **k** is a regression coefficient.
- **Age** refers to the time since the pipe was installed.
Note that this is a very simple equation, which assumes the same number of breaks would happen each year for a group of pipes (e.g., all cast-iron pipes in the system), and no other factors are accounted for.

A linear equation such as this can easily be defined with two points. 
For example, let's consider the following two data points:

| Number of Breaks (N) | Age (Years) |
|----------------------|-------------|
| 0                    | 0           |
| 270                  | 22          |

With these two points, the slope **k**** of the line can be calculated as:

$$
k = \frac{270 - 0}{22 - 0} = 12.27
$$

Thus, the equation **N = k × Age** becomes:

$$
N = 12.27 \cdot Age
$$

However, in reality, there would be multiple data points, and the best-fit line would need to be determined to capture the overall trend. Consider the following data set:

| Number of Breaks (N) | Age (Years) |
|----------------------|-------------|
| 0                    | 0           |
| 165                  | 16          |
| 200                  | 18          |
| 190                  | 20          |
| 270                  | 22          |

To find the line that best fits this data, the difference between the predicted breaks using the line equation and the actual observed breaks would have to be minimized. For each data point, the predicted number of breaks is compared to the actual observed number of breaks, and the difference between them is squared to avoid negative differences cancelling out positive ones. To minimize this difference, one common approach is the **least squares method**, which minimizes the sum of squared differences between the observed and predicted values:

$$
\text{Sum of Squares} = \sum (N_{\text{observed}} - N_{\text{predicted}})^2
$$

While for a simple linear regression like this, **k** can be calculated directly, for more complex equations or when additional variables are involved, an iterative process may be needed. In such cases, the coefficients in the equation are adjusted iteratively to minimize the error until the best-fit line is found. This approach is often used in non-linear regressions or when multiple variables affect the outcome.

:::tip **Regression with Solver in MS Excel**

Microsoft Excel's **Solver** tool can be used to find the best-fit equation for a given dataset by minimizing the sum of squared errors. The main steps are as follows:

1. **Define the k Coefficient**: Set aside a single cell in the spreadsheet to hold the value of the `k` coefficient. If your equation has more coefficients, set one cell for each. At this points you should provide an initial guess of the value of each coefficient.
   
2. **Create Predicted Values**: Assuming you already have the input data in a spreadsheet, add a column next to your existing data for the target (in this case, "N_predicted", predicted number of breaks). Insert the formula, e.g., `N = k * Age`, where `k` is the coefficient assumed in the first step and Age is the actual age from the dataset.

3. **Calculate Squared Differences**: In another column, compute the squared differences between the actual and predicted target, e.g., `(N_observed - N_predicted)^2`.

4. **Sum of Squared Differences**: Select a new cell and calculate the total sum of squared differences.

5. **Use Solver**: Open Excel’s **Solver** tool. Set the objective to minimize the sum of squared differences by changing the value of the coefficient(s), e.g., `k`.

6. **Run Solver**: Solver will adjust the value of the coefficient(s) iteratively until it finds the value that minimizes the total error, providing the best-fit line for the data.

:::


Because assets usually deteriorate more rapidly as they age, nonlinear regressions for deterioration, such as assuming exponential deterioration, are commonly applied.

For example, the [Highway Pavement Management Application developed by Stantec and used by Alberta Transportation](https://doi.org/10.6135/ijprt.org.tw/2013.6(6).714) uses the following model to predict the International Roughness Index (IRI) of pavement sections

$$
IRI = IRI_0 + e^{A - B \times C^{\ln(Age)}}
$$

Where:
- **IRI₀** is the IRI at age zero.
- **Age** is the life in years since the last rehabilitation or construction activity.
- **A**, **B**, and **C** are coefficients defined based on the treatment type.

Given a dataset containing IRI and age observations the parameters **IRI₀** and **Age** can be found with the same least square approach in Excel mentioned before. As an alternative a curve fitting function could also be used in python.  

:::tip **Regression with Python**

A curve fitting function in python can be defined as follows:

1. **Import Required Libraries**: Load the necessary Python libraries for handling arrays, mathematical operations, curve fitting, and plotting graphs.

2. **Define the IRI Model**: Create a custom function to represent the mathematical model for predicting IRI based on age and parameters.

3. **Load Example Data**: Provide the observed age and IRI data as `numpy` arrays.

4. **Perform Curve Fitting**: Use the `curve_fit` function to estimate the parameters of the IRI model by fitting it to the observed data.

5. **Extract the Fitted Parameters**: Retrieve the optimized values of the parameters from the curve fitting.

6. **Plot the Data and Fitted Curve**: Plot both the observed data and the fitted curve to visually compare the model's prediction with actual data.

An example code is provided below

```python
import numpy as np
import matplotlib.pyplot as plt
from scipy.optimize import curve_fit

# Define the equation
def iri_model(age, IRI_0, A, B, C):
    return IRI_0 + np.exp(A - B * C ** np.log(age))

# Load example data
age_data = np.array([1, 5, 10, 15, 20])  
iri_data = np.array([2, 2.25, 2.6, 4, 5.1]) 

# Use curve fitting to find the coefficients
initial_guess = [1, 1, 1, 1]  # Initial guess for IRI_0, A, B, C
params, covariance = curve_fit(iri_model, age_data, iri_data, p0=initial_guess, maxfev=1000)

# Extract the fitted parameters
IRI_0, A, B, C = params

# Print the fitted parameters
print(f"Fitted Parameters:\nIRI_0 = {IRI_0}\nA = {A}\nB = {B}\nC = {C}")

# Plotting the data and the fitted curve
age_range = np.linspace(min(age_data), max(age_data), 100)
fitted_iri = iri_model(age_range, IRI_0, A, B, C)

plt.scatter(age_data, iri_data, label='Observed Data', color='red')
plt.plot(age_range, fitted_iri, label='Fitted Curve', color='blue')
plt.xlabel('Age')
plt.ylabel('IRI')
plt.legend()
plt.title('IRI Curve')
plt.show()
```
You can copy and run this code in a google colab notebook

:::

<!--
#### Probabilistic Models

explain probability distribution
mean time to failure

explain modelling of failure time, survival time
hu table 7

explain weibull distribution


explain condition/state modelling

explain markov transition matrix

example for facilities - bring paper from final

Hu recent review study
table 6 

nishiyama fuzzy markov
-->