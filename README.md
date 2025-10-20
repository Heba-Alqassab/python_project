# python_project
# Real drinking-water quality in Germany
# Project Overview

TFW is a major public water supplier In Germany. Faced several challenges in detecting changes in drinking water quality. and enables water supply companies to counteract the effects of time. To deal with the Scenario. The Provision of clean water is an essential task for water supply companies alle over the world. The objective of the TFW idea to beat the competitors and develop an online monitoring tool to default the changers in water. The challenge encourages robust modeling of Senser Behavior, early fault selection, and adaptive strategies for maintaining water safety and regulatory compliance.
# Problem Statement
Between August and November 2016, sensor data from a water distribution system in Germany indicated 1726 anomalies events. Which may reflect a contamination risk, a sensor malfunction, or a chemical imbalance.
# Approach 
- How does the system detect anomalies?
- How does the flowrate (sensors 1 and 2) vary over time?
- Do chlorine dioxide (ClO2) levels show consistent readings?
- How does redox potential change over time?
- Are pH values within the safe range?
- How do the parameters affect each other?
# Dataset
The Datset size: 12 columns - 139567 Rows

Source: [Dataset](https://zenodo.org/records/3884398/files/1_gecco2018_water_quality.csv?download=1)

Source: [Zenodo](https://zenodo.org/records/3884398)

Main Columns: pH, Event, Cl1,Cl_2, Redox
# Analysis
The Dataset was cleaned and contains 12 columns about the public water supplier In Germany. The idea of TFW is to beat the competitors and develop an online monitoring tool to default the changers in water. The challenge encourages robust modeling of Senser Behavior,During 2016, sensor data from a water distribution system in Germany anomalies events. Which may reflect a contamination risk, a sensor malfunction, or a chemical imbalance.  multiple library was used in python including matplotlib, seaborn and pandas.
# How to Run
Open the file in the jupyter Notebook

Then Run this code in python

    water_df=pd.read_csv('water.csv')
# Dependencies
- Library Used:
- import matplotlib.pyplot as plt
- import seaborn as sns
- import pandas as pd
  ## Findings
- Add more measurements (minerals content)
- Include water source
- Standardize sensor 2 
