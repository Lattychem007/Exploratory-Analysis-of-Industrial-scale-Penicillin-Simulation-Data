
# Exploratory Analysis of the Industrial-scale Penicillin Fermentation  Simulation Dataset
![image](https://github.com/user-attachments/assets/ed0c066d-1e0f-4904-93c1-523de35da7b1)

**INTRODUCTION**

The Industrial-scale Penicillin Simulation Version model significantly advances industrial fermentation, aiding in the development of improved control strategies and contributing to research and educational studies.

This dataset is a product of advanced mathematical simulations that emulate the operations of a 100,000-litre penicillin fermentation system, known as IndPenSim. By utilizing cutting-edge computational models, it provides insights into the complexities of large-scale biopharmaceutical production.






## TABLE OF THE CONTENTS
- Objective.
- Data Understanding.
-  Identifying the Batch with Maximun Pencillin Concentarion.
-  Analysing the batch with highest penicillin concentration.
-   Summary
-   Conclusion.
## Citation
1) "The Development of an Industrial-Scale Fed-Batch Fermentation Simulation"

This paper was published in the Journal of Biotechnology, describes the development of a simulation of an industrial-scale fed-batch fermentation process. The simulation was developed using a mechanistic model and was validated using historical data collected from an industrial-scale penicillin fermentation process. The simulation can be used as a benchmark for process systems analysis and control studies.

2) "Modern day monitoring and control challenges outlined on an industrial-scale benchmark fermentation process"

This paper was published in Computers & Chemical Engineering, discusses about the challenges of monitoring and controlling an industrial-scale benchmark fermentation process. The authors identify several challenges, including the need for real-time monitoring of key process variables, the need for effective control strategies, and the need for robust and reliable sensors.
## Data Source
  https://data.mendeley.com/datasets/npt257bjxn/1
## DATA UNDERSTANDING
In this dataset, we find a multitude of data included in 113,935 rows that provide a thorough examination of inputs and outcomes over 100 different batches. Every batch is carefully recorded at different points in time, resulting in a dynamic log of industrial operations and how they change over time. This large-scale dataset offers a priceless chance to explore the complex interactions between input factors and outputs in a variety of manufacturing scenarios.

##  Identifying the Batch with Maximun Pencillin Concentarion.
#Process parameters/Information Insight from The Dataset
**Time (h):** 
The average time is roughly 227.87 hours, with time intervals ranging from 167 to 290 hours.
**Aeration rate (Fg:L/h):**
The average aeration rate is roughly 65.35 L/h, with a range of 60 to 75 L/h.
**Agitator RPM (RPM:RPM):**
For every batch, the agitator RPM remains at 100 RPM.
**Sugar feed rate (Fs:L/h):**
The average sugar feed rate is roughly 81.80 L/h, with a range of 20 to 150 L/h.
**Acid flow rate (Fa:L/h):**
The average acid flow rate is roughly 0.16 L/h, with a range of 0 to 4.15 L/h.
**Base flow rate (Fb:L/h):**
The average base flow rate is roughly 37.79 L/h, with a range of 0 to 200.30 L/h.
**Heating/Cooling Water Flow Rate (Fc:L/h):**
The average rate of the heating/cooling water flow is roughly 47.04 L/h, with a range of 0.0001 to 281.71 L/h. 
**Heating Water Flow Rate (Fh:L/h):**
The average heating water flow rate is about 42.47 L/h, with a range of 0.0001 to 444.28 L/h.
**Water for Injection/Dilution (Fw:L/h):**
The average rate of water for injection/dilution is 224 L/h, with a range of 0 to 400 L/h. 

**Air Head Pressure (pressure:bar):**
For every batch, the air head pressure stays at 0.9 bar. 

**Dumped Broth Flow (Deleted: L/h):**
The average dumped broth flow is -400 L/h, with a range of -4000 to 0 L/h. 

**Substance Concentration (S:g/L):**
The average substrate concentration is roughly 19.39 g/L, with a range of 0.0011 to 115.27 g/L. 
**Dissolved Oxygen Content (DO2:mg/L):**
The average dissolved oxygen content is around 12.72 mg/L, with a range of 8.87 to 14.77 mg/L. 
**Concentration of Penicillin (P:g/L):**
The average penicillin concentration is about 24.01 g/L, with a range of 3.16 to 36.16 g/L.
**Vessel Volume (V:L):**
The average vessel volume is roughly 76053.54 liters, with a range of 60331 to 89990 liters. 
**Vessel Weight (Wt:Kg):**
The average vessel weight is roughly 84995.10 kg, with a range of 68469 to 99491 kg. 
**pH (pH:pH):**
The average pH is roughly 6.51, with values ranging from 6.47 to 6.68. 
**Temperature (T:K):**
The average temperature is roughly 297.97 K, with a range of 297.43 to298.99 K. 
**Heat Generated (Q:kJ):**
The heat generated ranges from 4.03 to 833.80 kJ.
**Off-Gas Carbon Dioxide Percentage (CO2outgas:%):**
The average off-gas carbon dioxide percentage is roughly 1.45%, with a range of 0.64% to 2.06%. 
**PAA Flow (Fpaa:L/h):**
The average PAA flow is roughly 6.58 L/h, with a range of 3.66 to 15 L/h.
In offline mode, PAA concentration (PAA_offline:PAA (g L^{-1})): The average PAA concentration is around 3358.13 g/L, with a range of 393.1 to 11524 g/L. 
**Oil Flow (Foil: L/hr):**
For every batch, the oil flow remains constant at 23 L/hr. 
**(NH3_offline:NH3 (g L^{-1}))NH3 Concentration Off-line:**
The average NH3 content is roughly 2571.96 g/L, with a range of 1590.6 to 5170 g/L. 
**Oxygen Absorption Rate (OUR:(g min^{-1})):**
The average oxygen absorption rate is roughly 0.94 g/min, with a range of 0.0447 to 1.7044 g/min. 
**Oxygen in Percent in Off-Gas (O2:O2 (%)):**
The oxygen percentage in off-gas ranges from 0.1863% to 0.2035%, with an average of approximately 0.1942%.
**Offline Penicillin Concentration (P_offline:P(g L^{-1})):**
The offline penicillin concentration varies from 3.17 to 36.18 g/L, with an average of approximately 24.03 g/L
**Offline Biomass Concentration (X_offline:X(g L^{-1})):**
The offline biomass concentration ranges from 10.76 to 25.27 g/L, with an average of approximately 20.80 g/L.
***Carbon Evolution Rate (CER:g/h):** 
The carbon evolution rate varies from 0.49 to 1.71 g/h, with an average of approximately 1.21 g/h.
**Ammonia Shots (NH3_shots:kgs):**
The ammonia shots are constant at 0 kgs for all batches.
Viscosity (Viscosity_offline:centPoise): The viscosity ranges from 53.75 to 117.93 centipoise, with an average of approximately 71.06 centipoise.

# Maximum concentration of Penicillin
The dataset's maximum Offline Penicillin Concentration (P_offline:P(g L^{-1})) reaching 36.18 g/L indicates a significant achievement in the batch process. To gain deeper insights, we will conduct an in-depth analysis of the control parameters and conditions that contributed to this exceptional output. Understanding the factors that led to such high penicillin concentration is crucial for process optimization and quality improvement in industrial-scale fermentations.

## Analysing the batch with highest penicillin concentration
 Time (h): The time values are given in hours and range from 0.2 hours to 290 hours. It appears to be a continuous variable representing elapsed in hours.

Base Flow Rate (Fb: L/h): The base flow rate values range from approximately 29.5 L/h to 55.43 L/h. likely related to the system's base requirement of batch and it varies within a specific range.

Heating/Cooling Water Flow Rate (Fc: L/h): The heating/cooling water flow rate varies significantly, ranging from very small values (close to 0) to over 111 L/h. This variable appears to represent the flow rate of heating or cooling water in liters per hour.

Heating Water Flow Rate (Fh: L/h): The heating water flow rate shows a wide range of values, from very small values to over 460 L/h. The values also seem to be logarithmically distributed, with many small values and a few larger values. This variable appears to represent the flow rate of heating water in liters per hour.

Substrate concentration (S:g/L): The substrate concentration decreases as the batch progresses, indicating that the consumption of the substrate for growth and metabolite production.

Dissolved oxygen concentration (DO2:mg/L): The dissolved oxygen concentration shows minor fluctuations, which might be due to variations in microbial activity and oxygen demand. Toward the end of the batch, there's a significant drop in oxygen concentration, suggesting increased microbial activity.

Penicillin concentration (P:g/L): Penicillin concentration increases as the batch progresses, which could be a result of microbial production. This concentration keeps rising until the end of the batch.

Vessel Volume (V:L): The vessel volume remains relatively constant, indicating that there's no significant addition or removal the bioreactor.

Vessel Weight (Wt:Kg): The vessel weight increases during the batch, which might be due to the growth and accumulation of microbial biomass and other components in the bioreactor.

pH (pH:pH): The pH fluctuates but generally remains within a narrow range. This suggests that the pH is being well-controlled during the fermentation process.

Temperature (T:K): The temperature is maintained within a relatively narrow range, ensuring a stable environment for microbial growth and product formation.

Generated heat (Q:kJ): The generated heat increases, likely due to microbial metabolic activity producing heat. This is consistent with the increase in penicillin concentration.

Carbon dioxide percent in off-gas (CO2outgas:%): The percentage of carbon dioxide in the off-gas increases over time, indicating higher metabolic activity as the batch progresses.

Oxygen Uptake Rate (OUR: (g min^{-1})): The oxygen uptake rate varies, suggesting changing microbial activity levels. It shows an increasing trend toward the end of the batch.

Oxygen in percent in off-gas (O2: O2 (%)): The percentage of oxygen in the off-gas gradually decreases as the batch progresses, indicating that more oxygen is being consumed by the microbial culture.

Carbon evolution rate (CER: g/h): The carbon evolution rate shows a steady increase over the course of the batch, indicating increasing metabolic activity and carbon dioxide production.
