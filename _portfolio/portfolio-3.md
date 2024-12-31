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

#### **HIV Test Results**
\begin{table}[H]
\caption{Répartition des résultats de tests au VIH}
\label{stat}
\centering
\begin{tabular}{lrr}
\hline
Recent HIV Test Result & Frequency & Percent \\
\hline
Negative & 5,417 & 86.31\% \\
Positive & 859 & 13.69\% \\
\hline
Total & 6,276 & 100.00\% \\
\hline
\end{tabular}
\end{table}

---

#### **Variable Descriptions**
\begin{table}[H]
\scriptsize
\centering
\caption{Description des variables}
\label{descvar}
\begin{tblr}{
  vline{-} = {1}{},
  hline{1-2} = {-}{},
}
~Nom    & ~Description                                                                                             \\
~v012   & Âge~                                                                                                     \\
~v025   & Type de place de résidence                                                                               \\
~v106   & Niveau d'éducation                                                                                       \\
~v130   & Religion                                                                                                 \\
~v501   & Statut Matrimonial                                                                                       \\
~v503   & Nombre d'unions                                                                                          \\
~v525   & Age auquel est survenu le premier rapport sexuel                                                         \\
~v701   & Niveau d'éducation du partenaire                                                                         \\
~v730   & Âge du partenaire                                                                                        \\
v717    & Profession du répondant                                                                                  \\
~v750   & Entendu parler des Maladies sexuellement transmissibles                                                  \\
~v751   & Entendu parler du SIDA                                                                                   \\
~v754cp & Réduire le risque de contracter le VIH : utilisez toujours des préservatifs pendant les rapports sexuels \\
~v754dp & Réduire le risque de contracter le VIH : n'avoir qu'un seul partenaire sexuel                            \\
~v761   & Préservatif utilisé lors du dernier rapport sexuel avec le partenaire le plus récent                     \\
~v769   & Peut obtenir un préservatif                                                                              \\
~v769a  & Peut obtenir un préservatif féminin                                                                      \\
~v836   & Nombre total de partenaires sexuels au cours d'une vie                                                   \\
~s928b  & Résultat récent du test VIH                                                                              
\end{tblr}
\end{table}

---

#### **Descriptive Statistics**
\begin{table}[H]
\centering
\caption{Statistiques Descriptives}
\label{statdesc}
\begin{tabular}{llllll}
\hline
Variable     & Obs  & Mean   & Std. Dev. & Min & Max \\ \hline
v012         & 6276 & 33.044 & 10.986    & 15  & 64  \\
v025         & 6276 & 1.46   & .498      & 1   & 2   \\
v106         & 6276 & 1.771  & .681      & 0   & 3   \\
v130         & 6259 & 9.943  & 25.512    & 1   & 96  \\
v501         & 6276 & .989   & 1.299     & 0   & 5   \\
v531         & 6246 & 22.427 & 19.68     & 0   & 98  \\
v536         & 6224 & 1.899  & 1.029     & 0   & 3   \\
v701         & 3161 & 1.947  & 1.609     & 0   & 8   \\
v705         & 2599 & 5.365  & 3.85      & 0   & 96  \\
v717         & 6259 & 2.09   & 3.556     & 0   & 96  \\
v730         & 2507 & 42.166 & 11.444    & 17  & 95  \\
v750         & 6276 & 1      & 0         & 1   & 1   \\
v754cp       & 6273 & .916   & .277      & 0   & 1   \\
v754dp       & 6272 & .961   & .194      & 0   & 1   \\
v761         & 4903 & .447   & .497      & 0   & 1   \\
v763a recode & 6258 & .042   & .201      & 0   & 1   \\
v769 recode  & 6061 & .911   & .285      & 0   & 1   \\
v769a recode & 4935 & .865   & .342      & 0   & 1   \\
v836         & 5964 & 3.926  & 11.066    & 1   & 98  \\ \hline
\end{tabular}
\end{table}
