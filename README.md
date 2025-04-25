                                                       DAY - 2
## Noise Complaint Insights from Urban Data

---

# Problem Statement
Understanding urban noise complaints is crucial for improving city life.  
This EDA explores a synthetic yet realistic dataset to:

- Extract valuable patterns, trends, and anomalies
- Guide predictive modeling and policy decisions

---

# Objective

Perform insightful, visually-driven EDA to uncover:
- Key trends and correlations  
- Potential anomalies  
- Feature-level inferences for ML readiness  

---

# Dataset Overview

- **Zone_Type**: Residential, Commercial, Industrial etc.  
- **Time_of_Day**: Morning, Afternoon, Evening, Night  
- **Day_of_Week**: Monday to Sunday  
- **Noise_Source**: Traffic, Construction, Humans, Mixed  
- **Population_Density**: People per square km  
- **Nearby_Roads**: Count of roads in a 200m radius  
- **Green_Cover_%**: Percentage of green area  
- **Noise_dB**: Decibel noise level  
- **Noise_Complaints**: Number of complaints received  

---

# Histograms + Boxplots GRAPHS :Overview Throgh the Graph**

![Screenshot (61)](https://github.com/user-attachments/assets/c192c808-d76f-422a-a4e9-5da77fff2ee1)

# The data shows patterns of noise, population, and roads. Most complaints and noise levels are low to moderate, population density varies greatly, and roads are mostly few but occasionally clustered.

# Pairplot + Correlation Matrix
![Screenshot (60)](https://github.com/user-attachments/assets/58dea8b1-21af-43b9-84a0-67d36c211843)

![Screenshot (59)](https://github.com/user-attachments/assets/8c3d3f1a-9eaf-4975-9f7a-e9c6bb78bede)

# Final Insight:Only Noise Levels (Noise_dB) have a clear influence on the number of complaints.Other features (roads, population, greenery) do not strongly impact complaints directly.


