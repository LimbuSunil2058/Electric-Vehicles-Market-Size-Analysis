# 🚗 Electric Vehicles Market Size Analysis using Python

This project explores the global adoption of electric vehicles (EVs) using real-world data. It aims to uncover how EV adoption has evolved over time, which countries are leading the charge, and how technological advancements like battery range are progressing.

## 📊 Project Overview

The analysis includes:
- Cleaning and preparing real-world EV registration data
- Understanding trends in EV adoption over the years
- Identifying top countries and cities for EV usage
- Analyzing distribution of EV types (BEV, PHEV, etc.)
- Exploring electric range progression over model years
- Finding correlation between year and EV adoption

## 📁 Dataset Description

The dataset contains detailed records about electric vehicles registered in the U.S. (primarily Washington state). Below are the key fields:

- **VIN (1-10)**: Partial Vehicle Identification Number.
- **County**: County where the vehicle is registered.
- **City**: City where the vehicle is registered.
- **State**: State where the vehicle is registered (mostly WA).
- **Postal Code**: Postal (ZIP) code of registration.
- **Model Year**: Year of the vehicle model.
- **Make**: Manufacturer of the vehicle (e.g., Tesla, Nissan).
- **Model**: Model name of the vehicle (e.g., Leaf, Model S).
- **Electric Vehicle Type**: Type of EV – e.g., Battery Electric Vehicle (BEV), Plug-in Hybrid Electric Vehicle (PHEV).
- **Clean Alternative Fuel Vehicle (CAFV) Eligibility**: Indicates if the vehicle qualifies for clean fuel programs.
- **Electric Range**: Distance the EV can travel on a full charge (in miles).
- **Base MSRP**: Manufacturer’s Suggested Retail Price.
- **Legislative District**: District of vehicle registration.
- **DOL Vehicle ID**: Washington State Department of Licensing vehicle ID.
- **Vehicle Location**: Latitude and longitude coordinates.
- **Electric Utility**: Name of the electric utility provider for the location.
- **2020 Census Tract**: Census tract code based on 2020 U.S. Census data.
## 🔗 Dataset Source

Due to its large size, the dataset is not included in this repository.  
You can access and download the full dataset from the official source below:

**[EV Market Size Dataset - statso.io](https://statso.io/market-size-of-evs-case-study/)**

Once downloaded, you can place the dataset in the root folder or a `data/` directory to run the analysis notebooks.


## 🛠️ Tools & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

## 📈 Key Findings

- EV adoption shows a **strong upward trend**, especially after 2015.
- **Dip in 2019–2020** likely due to the COVID-19 pandemic, followed by a major recovery.
- **2023** recorded the **highest EV adoption**, indicating a peak in market interest.
- **Battery Electric Vehicles (BEVs)** are more popular than Plug-in Hybrid EVs (PHEVs).
- The **correlation between year and EV count is ~0.63**, showing a moderately strong relationship.
- Electric vehicle **range has steadily increased**, thanks to improvements in battery technology and design.

## 📌 Conclusion

Electric vehicles are on a steady rise worldwide, driven by environmental concerns, policy incentives, and technological innovation. The future looks bright for EVs as range increases and infrastructure expands. The insights from this project can help governments, businesses, and consumers understand the direction of the EV market.

## 🚀 Future Work

- Forecast EV adoption using regression models or time series.
- Compare EV growth with charging station infrastructure.
- Study manufacturer trends and top-selling EV models.






