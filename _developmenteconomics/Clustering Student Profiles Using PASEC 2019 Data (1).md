---
title: "Clustering Student Profiles Using PASEC 2019 Data"
excerpt: "Dimensionality reduction and unsupervised clustering (DBSCAN + PCA) applied to education data from 14 African countries, revealing student profiles across performance, SES, and school context.<br/><img src='https://aw0007.github.io/images/passec/pca_grid_part_1.png'>"
collection: developmenteconomics
authors:
  - Abdoul Wahid Massaoudou Namata
---

🌌 **The Curse of Dimensionality in Education Data Analysis**

When developing effective education policies, it's not enough to focus solely on student scores. Socioeconomic conditions, home environment, and school infrastructure all play a crucial role in shaping academic outcomes. But as the number of variables increases, the data space becomes too complex—this is the **curse of dimensionality**.

To address this, I used **unsupervised machine learning techniques** to cluster students into meaningful profiles based on:
- Academic performance (reading & math)
- Household conditions (electricity, books, hunger)
- School environment (infrastructure, meals)

---

### 🧠 Methodology

- **Clustering algorithm**: DBSCAN (Density-Based Spatial Clustering of Applications with Noise)
- **Dimensionality reduction**: PCA (Principal Component Analysis)
- **Data**: PASEC 2019 standardized student assessment datasets
- **Tools**: Python (`sklearn`, `matplotlib`, `seaborn`, `pandas`)

---

### 📊 Key Visualizations

#### PCA Projection with Clusters – Part 1
<img src='https://aw0007.github.io/images/passec/pca_grid_part_1.png' style='width:90%;' alt='PCA Cluster Plot 1' />

#### PCA Projection with Clusters – Part 2
<img src='https://aw0007.github.io/images/passec/pca_grid_part_2.png' style='width:90%;' alt='PCA Cluster Plot 2' />

#### Radar Charts – Cluster 0
<img src='https://aw0007.github.io/images/passec/radar_grid_cluster_0_part_1.png' style='width:90%;' />
<img src='https://aw0007.github.io/images/passec/radar_grid_cluster_0_part_2.png' style='width:90%;' />

#### Radar Charts – Cluster 1
<img src='https://aw0007.github.io/images/passec/radar_grid_cluster_1_part_1.png' style='width:90%;' />
<img src='https://aw0007.github.io/images/passec/radar_grid_cluster_1_part_2.png' style='width:90%;' />

#### Radar Charts – Cluster 2
<img src='https://aw0007.github.io/images/passec/radar_grid_cluster_2_part_1.png' style='width:90%;' />
<img src='https://aw0007.github.io/images/passec/radar_grid_cluster_2_part_2.png' style='width:90%;' />

#### Radar Charts – Cluster 3
<img src='https://aw0007.github.io/images/passec/radar_grid_cluster_3_part_1.png' style='width:90%;' />

---

### 🎯 Applications

- Identify **at-risk students** with both low performance and difficult living conditions
- Tailor **targeted education interventions** by cluster
- Support **evidence-based education policy design** at national and regional levels

---

### 🌐 Resources

- 📄 **Data**: [PASEC 2019 – CONFEMEN](https://www.pasec.confemen.org/)
- 💻 **Code & Analysis**: [My GitHub](https://github.com/aw0007)

---

### 📌 Broader Implications

The **curse of dimensionality** is not unique to education. It's a core challenge in:
- Public health
- Energy access
- Financial inclusion
- Labor market segmentation

As big data grows in complexity, **machine learning methods like clustering** become essential for unlocking actionable insights.

---

### 🏷️ Tags

`#MachineLearning`, `#DBSCAN`, `#PCA`, `#Python`, `#EducationPolicy`, `#DataScience`, `#Clustering`, `#PASEC`, `#PublicPolicy`, `#Africa`, `#UnsupervisedLearning`
