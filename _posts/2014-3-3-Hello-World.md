---
layout: post
title: Steel Sector Data: Tracking Energy and Emissions
---


This blog post introduces a dataset capturing steel industry energy consumption, selected for its rich detail on electricity usage, reactive power, power factors, and CO₂ outputs. We chose these records because steel manufacturing is among the most energy-intensive global industries, demanding reliable insights into power usage and emissions. The dataset includes continuous numerical fields (e.g., kilowatt-hours and power factors), ordinal variables like seconds since midnight, and categorical indicators for weekdays vs. weekends. Such breadth offers a multi-angle view of when and how energy is consumed, making it ideal for forecasting and efficiency studies.

Key properties of this dataset include time-series measurements at regular 15-minute intervals, along with categorical tags (e.g., load type). Researchers can identify cost-saving and eco-friendly interventions by investigating outliers and daily/weekly usage patterns. In the literature review phase, I highly recommend one article by Brownlee [1], which focuses on applying machine learning for time-series data; it provides practical guidance on handling skewed distributions and irregular consumption patterns—both common in industrial contexts.

---
**References**  
[1] Brownlee, J. *Machine Learning for Time-Series Forecasting*. Machine Learning Mastery (2020).
