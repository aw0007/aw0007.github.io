---
title: "Effect of Chinese Financial Flows on Economic Growth"
excerpt: "Analysis of Chinese financial flows and their impacts on economic growth in 147 countries between 2000 and 2021.<br/><img src='/images/chinese-financil_flow/Project_Map_Africa.png'>"
collection: portfolio
authors:
  - Abdoul Wahid Massaoudou Namata
---

This study examines the impact of Chinese financial flows on the economic growth of recipient countries, using AidData, which covers 20,985 projects in 165 low- and middle-income countries over the period 2000-2023. We employ three empirical approaches: the within-country estimator, the instrumental variable estimator using China's steel production as an instrument, and the dynamic panel model with the Arellano and Bond specification. Our results indicate a positive relationship between Chinese financial flows and the economic growth of recipient countries. The within-country estimator shows a positive impact, as does the instrumental variable approach, which produces positive and significant coefficients. However, the results of the dynamic panel model are not significant. Long-term effects are evident in five-year averages, particularly in infrastructure-related investments. The positive impact is more pronounced in America than in Africa and Asia. Additionally, our results reveal a crowding-out effect on domestic investment.

---

### Additional Visuals:

### Trends in Chinese Financial Flows
<br/><img src='/images/chinese-financil_flow/Évolution_de_la_Somme_Totale_des_Montants_par_Année_d_Engagement.png' style='width:60%;'> "Trends in Chinese Financial Flows Over Time"

### Regional Distribution
#### "Distribution of Chinese Financial Flows Across Africa"
<br/><img src='/images/chinese-financil_flow/Project_Map_Africa.png' style='width:60%;'> 

#### "Distribution of Chinese Financial Flows Across America"
<br/><img src='/images/chinese-financil_flow/Project_Map_America.png' style='width:60%;'> 

#### "Distribution of Chinese Financial Flows Across Asia"
<br/><img src='/images/chinese-financil_flow/Project_Map_Asia.png' style='width:60%;'> 

### Short-Term Dynamics

To evaluate the effect of Chinese investments on the growth of recipient countries, we estimate the following dynamic panel model (similar to \cite{acemoglu2019rents}):

\begin{equation}
Y_{i,t} = \alpha_0 + \alpha_1 BRI_{i,t} +  \lambda Y_{i,t-1} + \sum_{k=1}^{K} \beta_k X_{itk} + \mu_i + \gamma_t + \epsilon_{it}
\end{equation}

Where $Y_{i,t}$ is the logarithm of GDP per capita for country $i$ in year $t$. The term $BRI_{i,t}$ is our variable of interest, representing Chinese investments in country $i$ in year $t$. The inclusion of the lagged log GDP per capita ($Y_{i,t-1}$)\footnote{In \cite{acemoglu2019democracy}, four lags of GDP per capita are used. However, in our study, we limit it to one lag to simplify interpretations, as more than one lag can make result interpretations very complex.} captures the internal dynamics of GDP. This dynamic allows us to capture the short-term and long-term effects between Chinese flows and the growth of developing countries \cite{beck2023liquidity}.

$\alpha_1$ is our coefficient of interest, capturing the short-term effects of Chinese investments. The long-term effect is obtained by dividing the parameter $\hat{\alpha}$ by $1- \sum_{l=1}^{p} \hat{\lambda_l}$ \cite{beck2023liquidity}. $1- \sum_{l=1}^{p} \hat{\lambda_l}$ represents the cumulative effect of past GDP values on its current value. By dividing $\hat{\alpha}$ (the short-term effect) of Chinese investments by this term, we obtain the total cumulative effect over an extended period, i.e., the long-term effect.

Among the control variables ($X_{itk}$), we include the following variables based on the literature as impacting economic growth \ref{descriptionvar}. These include investment in non-financial state sectors, trade openness (measured by the sum of imports and exports), enrollment rates in primary and secondary education, and total factor productivity (TFP), according to the Penn World Tables. Additionally, we use a dichotomous measure of democracy, as defined by \cite{acemoglu2019democracy}, to capture the institutional aspects of the countries studied. Finally, national savings and foreign direct investment (FDI) variables are also included to provide a comprehensive analysis.


| Variables         | Within (1) | Within (2) | Within (3) | Within (4) | IV (5)      | IV (6)      | IV (7)      | IV (8)      | AB (9)     | AB (10)    | AB (11)    | AB (12)    |
|-------------------|------------|------------|------------|------------|-------------|-------------|-------------|-------------|------------|------------|------------|------------|
| **Chinese_Flows** | 0.018***   | 0.015***   | 0.005**    | 0.003      | 0.627***    | 0.557***    | 0.393***    | 0.356***    | -0.000     | -0.001     | -0.001     | 0.000      |
| (Std. Error)      | (0.004)    | (0.003)    | (0.002)    | (0.002)    | (0.049)     | (0.056)     | (0.068)     | (0.085)     | (0.004)    | (0.003)    | (0.002)    | (0.002)    |
| **Lag1_GDP**      |            |            |            |            |             |             |             |             | -0.940***  | -0.732***  | -0.349***  | -0.289***  |
|                   |            |            |            |            |             |             |             |             | (0.118)    | (0.111)    | (0.118)    | (0.099)    |
| **Savings**       |            | 0.202***   | 0.071***   | 0.046***   |             | 0.106***    | 0.050**     | 0.041***    |            | 0.135***   | 0.049***   | 0.037***   |
|                   |            | (0.035)    | (0.013)    | (0.010)    |             | (0.037)     | (0.025)     | (0.022)     |            | (0.030)    | (0.012)    | (0.009)    |
| **GFCF**          |            |            | 0.439***   | 0.276***   |             |             | 0.282***    | 0.229***    |            |            | 0.453***   | 0.293***   |
|                   |            |            | (0.036)    | (0.026)    |             |             | (0.067)     | (0.054)     |            |            | (0.059)    | (0.042)    |
| **FDI**           |            |            |            | 0.006      |             |             |             |             |            |            |            | 0.035***   |
|                   |            |            |            | (0.005)    |             |             |             |             |            |            |            | (0.010)    |
| **Trade**         |            |            |            | 0.305***   |             |             |             | 0.148*      |            |            |            | 0.263***   |
|                   |            |            |            | (0.036)    |             |             |             | (0.079)     |            |            |            | (0.055)    |
| **Primary_Edu**   |            |            |            | -0.059     |             |             |             | 0.033       |            |            |            | -0.107*    |
|                   |            |            |            | (0.065)    |             |             |             | (0.108)     |            |            |            | (0.057)    |
| **Inflation**     |            |            |            | -0.007     |             |             |             | -0.009      |            |            |            | -0.009     |
|                   |            |            |            | (0.007)    |             |             |             | (0.020)     |            |            |            | (0.008)    |
| **Rule_of_Law**   |            |            |            | 0.103***   |             |             |             | 0.060       |            |            |            | 0.107      |
|                   |            |            |            | (0.033)    |             |             |             | (0.065)     |            |            |            | (0.109)    |

### Notes:
- Standard errors are in parentheses.
- \* \(p<0.10\), \*\* \(p<0.05\), \*\*\* \(p<0.01\).
- Control variables include savings, gross fixed capital formation (GFCF), FDI, trade openness, primary education, inflation, and rule of law.
- \(N=2148\) in Arellano-Bond (AB) models. Missing data imputed at 10%.
- IV estimation uses China's steel production as an instrument for Chinese financial flows.
