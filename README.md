# Wildfire Risk Prediction Model

This repository contains the project for CMPE 257: Wildfire Risk Prediction Model developed by Group 03. The project focuses on predicting wildfire risk in California using machine learning techniques by analyzing real-time environmental conditions and historical data.
---

## Table of Contents

- [Overview](#overview)
- [Project Description](#project-description)
  - [Background](#background)
  - [Solution Description](#solution-description)
  - [Objectives](#objectives)
  - [Challenges](#challenges)
- [Example Input & Output](#example-input--output)
- [Project Management](#project-management)
  - [Team Members](#team-members)
  - [Task Distribution](#task-distribution)
  - [Milestones](#milestones)
  - [Communication & Tools](#communication--tools)
- [References](#references)

---

## Overview

Wildfires have become a major concern in California due to increasing temperatures, drought conditions, and the resultant environmental stress. This project aims to leverage machine learning to predict the risk of wildfire outbreaks based on current environmental and meteorological data, thereby aiding in better resource allocation and risk management.

---

## Project Description

### Background

Recent events, such as the Palisades Fire, underscore the severe economic, environmental, and societal impacts wildfires can have on California. With climate change driving increased temperatures and water scarcity, wildfire risks are becoming unprecedented. Current assessment procedures struggle to rapidly and accurately predict wildfire occurrences due to the dynamic nature of influencing factors like climate, vegetation, and human activity.

### Solution Description

Our proposed solution is a machine learning model trained on historical wildfire data and real-time environmental conditions. The model integrates multiple data sources such as:
- Meteorological data
- Recorded drought and fire conditions
- Human activity and infrastructure data

This model predicts the wildfire risk in a given region of California and outputs a continuous probability score, which can be classified into risk categories such as low, moderate, high, or extreme.

### Objectives

- **Risk Prediction:** Provide a probability-based risk assessment of wildfire occurrence given environmental inputs.
- **Dataset Construction:** Build a comprehensive dataset incorporating regional environmental factors and historical wildfire events.
- **Accuracy Goal:** Achieve a model accuracy of over 80% for reliable predictions.
- **Outcome Benefits:**
  - Enhanced risk management for high-risk regions.
  - Better understanding of the environmental factors influencing wildfire occurrences.
  - Optimized allocation of resources and emergency response efforts.

### Challenges

- **Data Availability:** Limited and imbalanced historical wildfire data.
- **Feature Engineering:** Integrating multiple data sources may lead to the exclusion of key features or even incompatible data relations.
- **Model Performance & Bias:** Variability in data quality across different regions may impact generalizability.
- **Computational Complexity:** High operational costs due to the large volume of data processed.

---

## Example Input & Output
> [!NOTE]  
> The following inputs/outouts are just to give a general idea of how the model would work and is not in any way, shape, or form the final input that the model would recieve/produce 
**Input:**
- Temperature: 38°C (to be processed)
- Humidity: 15% (to be processed)
- Wind Speed: 20 mph (to be processed)
- Precipitation: 0 mm (to be processed)
- Drought Index: Severe (to be processed/hot encoded)
- Population Density: 500 people/km² (to be processed)
- Proximity to Roadways: 2 km (to be processed)

**Output:**
- Wildfire Risk: 85% (High Risk)

---

## Project Management

### Team Members

- **Rodrigo Chen** - MSSE Student (Plans to change to MSAI)  
  Email: rodrigo.chen@sjsu.edu | [LinkedIn](#)

- **Chen Kai Zhang** - MSAI Student  
  Email: chenkai.zhang@sjsu.edu | [[LinkedIn](https://www.linkedin.com/in/rodrigo-chen-73070123a/)](#)

- **Su Hyun Kim** - MSAI Student  
  Email: suhyun.kim@sjsu.edu | [[LinkedIn](https://www.linkedin.com/in/shawn-kim96/)](#)

- **Anthony Luu** - MSAI Student  
  Email: anthony.luu@sjsu.edu | [[LinkedIn](https://www.linkedin.com/in/anthony-luu-761973174/)](#)

### Task Distribution

All team members are engaged in every phase of the project, including:
- **Data Preparation:** Automating data extraction, handling missing values, and performing exploratory analysis.
- **Model Design & Training:** Experimenting with various regression and tree-based models and tuning hyperparameters.
- **Implementation & Validation:** Developing validation tests and setting up the project environment.
- **Evaluation & Visualization:** Assessing model performance and visualizing the results.
- **Final Report & Presentation:** Collaboratively preparing documentation and presenting the project outcomes.

### Milestones

- **Initial Project Report:** Completed by **February 19, 2025**. Introduces the project objectives, initial plans, and datasets.
- **Check-Up Presentation:** Scheduled for the week of March 5, 2025. A progress update focused on data collection and organization.
- **Case-Study Presentation:** Scheduled for the week of August 7, 2025. Presentation of the first version of the working model with initial performance evaluations.
- **Final Presentation & Report:** Scheduled for the week of April 28, 2025. Includes a fully working model, performance analysis, and a demonstration of wildfire prediction capabilities.
![cmpe257_2025-02-19_02 38pm](https://github.com/user-attachments/assets/3f8c57fd-f889-420f-ba5c-a1a1d424c1be)

### Communication & Tools

- **Collaboration Tools:** Google Workspace, Discord
- **Project Tracking:** Jira (with Gantt Chart and Agile board)
- **Version Control:** GitHub
- **Development Environment:** Visual Studio Code (VSCode)
- **Programming Language:** Python (Numpy, Sklearn, Pandas, matplot, etc)

---

## References

1. **CAL FIRE**, "Fire statistics." Available: [https://www.fire.ca.gov/our-impact/statistics](https://www.fire.ca.gov/our-impact/statistics) (Accessed: Feb. 16, 2025).
2. **Legislative Analyst’s Office (LAO)**, "Wildfires and forest resilience," Report No. 4886, Nov. 2023. Available: [https://lao.ca.gov/Publications/Report/4886](https://lao.ca.gov/Publications/Report/4886) (Accessed: Feb. 16, 2025).
3. **California Department of Water Resources**, "California water watch." Available: [http://cww.water.ca.gov/](http://cww.water.ca.gov/) (Accessed: Feb. 16, 2025).
4. **National Centers for Environmental Information**
5. **US Drought Monitor**
6. **Centers for Disease Control and Prevention**


