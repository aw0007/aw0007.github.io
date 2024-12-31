---
title: "Socio-Economic Determinants of HIV in Namibia"
excerpt: "Analysis of factors influencing HIV prevalence in Namibia using the 2013 DHS data."
collection: portfolio
---

Coauthored with **Idriss Adoum Adoum** and **Windkpuere Samuel Compaoré**, this study investigates the prevalence of HIV in Namibia by analyzing socio-economic, cultural, and behavioral factors. We utilize data from the 2013 Demographic and Health Surveys (DHS) and employ a Probit model to examine the determinants of HIV serostatus. The analysis uncovers key trends, such as the influence of age at first sexual encounter, number of unions, and total sexual partners on the likelihood of infection. The findings reveal significant disparities in rural areas, particularly linked to education level and occupation, emphasizing the critical role of education in mitigating risks. Despite notable progress in combating HIV, the study underscores the need for targeted efforts with strategies tailored to the diverse socio-economic and cultural realities of Namibia. 

The study also identifies limitations, including the necessity of more recent and longitudinal data, to deepen the understanding of the HIV/AIDS epidemic in Namibia and to refine future interventions.

### Keywords:
Public Health • AIDS • Health Behavior • Health and Economic Development • Government Policy • Regulation  

### JEL Code:
I15  


### Results Summary

### HIV Test Results

| Recent HIV Test Result | Frequency | Percent   |
|-------------------------|-----------|-----------|
| Negative               | 5,417     | 86.31%    |
| Positive               | 859       | 13.69%    |
| **Total**              | **6,276** | **100.00%** |

---

### Description of Variables

| Variable | Description                                                                                     |
|----------|-------------------------------------------------------------------------------------------------|
| v012     | Age                                                                                            |
| v025     | Type of place of residence                                                                      |
| v106     | Education level                                                                                 |
| v130     | Religion                                                                                        |
| v501     | Marital status                                                                                  |
| v503     | Number of unions                                                                                |
| v525     | Age at first sexual intercourse                                                                 |
| v701     | Partner's education level                                                                       |
| v730     | Partner's age                                                                                   |
| v717     | Respondent's occupation                                                                         |
| v750     | Awareness of sexually transmitted diseases                                                      |
| v751     | Awareness of HIV/AIDS                                                                           |
| v754cp   | Reduce risk of HIV: Always use condoms                                                          |
| v754dp   | Reduce risk of HIV: Have only one sexual partner                                                |
| v761     | Condom used during the last sexual intercourse                                                  |
| v769     | Knows how to obtain condoms                                                                     |
| v769a    | Knows how to obtain female condoms                                                              |
| v836     | Total number of sexual partners during lifetime                                                 |
| s928b    | Recent HIV test result                                                                          |

---
### Descriptive Statistics

| Variable     | Observations | Mean   | Std. Dev. | Min | Max |
|--------------|--------------|--------|-----------|-----|-----|
| v012         | 6,276        | 33.044 | 10.986    | 15  | 64  |
| v025         | 6,276        | 1.46   | 0.498     | 1   | 2   |
| v106         | 6,276        | 1.771  | 0.681     | 0   | 3   |
| v130         | 6,259        | 9.943  | 25.512    | 1   | 96  |
| v501         | 6,276        | 0.989  | 1.299     | 0   | 5   |
| v531         | 6,246        | 22.427 | 19.68     | 0   | 98  |
| v536         | 6,224        | 1.899  | 1.029     | 0   | 3   |
| v701         | 3,161        | 1.947  | 1.609     | 0   | 8   |
| v730         | 2,507        | 42.166 | 11.444    | 17  | 95  |
| v754cp       | 6,273        | 0.916  | 0.277     | 0   | 1   |
| v836         | 5,964        | 3.926  | 11.066    | 1   | 98  |


### Regression Results

#### Table 1: Regression Results (1)

| Variable        | Model (1) | Model (2) | Model (3) |
|-----------------|-----------|-----------|-----------|
| v531           | -0.024    | -0.035    | -0.023    |
|                 | (0.017)   | (0.022)   | (0.023)   |
| sqrv531        | 0.000*    | 0.000*    | 0.000     |
|                 | (0.000)   | (0.000)   | (0.000)   |
| v503           | 0.534***  | 0.498***  | 0.466***  |
|                 | (0.097)   | (0.110)   | (0.118)   |
| v836           | 0.019     | 0.041*    | 0.049**   |
|                 | (0.016)   | (0.023)   | (0.024)   |
| sqrv836        | -0.000    | -0.000*   | -0.000*   |
|                 | (0.000)   | (0.000)   | (0.000)   |
| v754cp (0)     | 0.000     | 0.000     | 0.000     |
| v754cp (1)     | 0.085     | 0.141     | 0.081     |
|                 | (0.135)   | (0.168)   | (0.171)   |
| v754dp (0)     | 0.000     | 0.000     | 0.000     |
| v754dp (1)     | 0.151     | 0.163     | 0.143     |
|                 | (0.189)   | (0.236)   | (0.242)   |
| v761 (0)       | 0.000     | 0.000     | 0.000     |
| v761 (1)       | 0.618***  | 0.598***  | 0.592***  |
|                 | (0.071)   | (0.086)   | (0.091)   |
| v763a_recode (0)| 0.000     | 0.000     | 0.000     |
| v763a_recode (1)| 0.663***  | 0.743***  | 0.805***  |
|                 | (0.138)   | (0.169)   | (0.171)   |
| **N**          | 2130      | 1848      | 1835      |

---

#### Table 2: Regression Results (2)

| Variable         | Model (1) | Model (2) | Model (3) |
|------------------|-----------|-----------|-----------|
| v769_recode (0)  | 0.000     | 0.000     | 0.000     |
| v769_recode (1)  | 0.418**   | 0.578**   | 0.622**   |
|                  | (0.210)   | (0.242)   | (0.254)   |
| v769a_recode (0) | 0.000     | 0.000     | 0.000     |
| v769a_recode (1) | 0.136     | 0.122     | 0.125     |
|                  | (0.119)   | (0.141)   | (0.150)   |
| v730             |           | 0.066**   | 0.086**   |
|                  |           | (0.032)   | (0.034)   |
| sqrv730          |           | -0.001*   | -0.001**  |
|                  |           | (0.000)   | (0.000)   |
| v012             |           | 0.216***  | 0.238***  |
|                  |           | (0.046)   | (0.049)   |
| sqrv012          |           | -0.003*** | -0.003*** |
|                  |           | (0.001)   | (0.001)   |
| v025 (1)         | 0.000     | 0.000     | 0.000     |
| v025 (2)         |           | 0.283***  | 0.164*    |
|                  |           | (0.083)   | (0.088)   |
| **N**           | 2130      | 1848      | 1835      |

---

#### Table 3: Regression Results (3)

| Variable         | Model (1) | Model (2) | Model (3) |
|------------------|-----------|-----------|-----------|
| v130 (3)         | -0.007    | 0.011     |           |
|                  | (0.104)   | (0.109)   |           |
| v130 (4)         | 0.063     | 0.305     |           |
|                  | (0.190)   | (0.203)   |           |
| v130 (96)        | -0.475**  | -0.398*   |           |
|                  | (0.193)   | (0.209)   |           |
| v501 (2)         |           |           | 0.170*    |
|                  |           |           | (0.101)   |
| **N**           | 2130      | 1848      | 1835      |

---

#### Table 4: Regression Results (4)

| Variable         | Model (1) | Model (2) | Model (3) |
|------------------|-----------|-----------|-----------|
| v701 (2)         |           |           | -0.318**  |
|                  |           |           | (0.148)   |
| v701 (3)         |           |           | -1.037*** |
|                  |           |           | (0.298)   |
| v717 (1)         |           |           | -0.841*** |
|                  |           |           | (0.198)   |
| v717 (2)         |           |           | -0.879*** |
|                  |           |           | (0.304)   |
| v717 (3)         |           |           | -0.199*   |
|                  |           |           | (0.103)   |
| **N**           | 2130      | 1848      | 1835      |

---

> **Note:**  
> \*p < 0.10, **p < 0.05, ***p < 0.01
