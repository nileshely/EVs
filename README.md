# Report on Electric Vehicle Data

#### Introduction
Electric vehicles (EVs) are increasingly becoming a vital part of the modern transportation landscape. This report analyzes a dataset of Battery Electric Vehicles (BEVs) and Plug-in Hybrid Electric Vehicles (PHEVs) registered through the Washington State Department of Licensing (DOL). The dataset provides various details, including vehicle identification, geographic location, manufacturing information, and specifications. This analysis aims to provide insights into the distribution, trends, and characteristics of electric vehicles in Washington State.

#### Dataset Overview
The dataset consists of 181,458 records with 17 columns. The columns include:
- **VIN (1-10)**: Vehicle Identification Number
- **County**: County of registration
- **City**: City of registration
- **State**: State of registration
- **Postal Code**: Postal code of registration
- **Model Year**: Manufacturing year
- **Make**: Manufacturer
- **Model**: Model name
- **Electric Vehicle Type**: Type of electric vehicle
- **CAFV Eligibility**: Clean Alternative Fuel Vehicle eligibility
- **Electric Range**: Range in miles
- **Base MSRP**: Manufacturer's suggested retail price
- **Legislative District**: Legislative district
- **DOL Vehicle ID**: Department of Licensing vehicle ID
- **Vehicle Location**: Geographic coordinates
- **Electric Utility**: Electricity provider
- **2020 Census Tract**: Census tract

#### Data Visualizations

1. **Distribution of Electric Vehicle Types**
   ![Distribution of Electric Vehicle Types](path_to_image)
   The dataset shows a higher count of Battery Electric Vehicles (BEVs) compared to Plug-in Hybrid Electric Vehicles (PHEVs), indicating a preference for fully electric vehicles among registrants in Washington State.

2. **Electric Range Distribution**
   ![Electric Range Distribution](path_to_image)
   The electric range of vehicles shows a diverse distribution with most vehicles offering a range between 50 to 300 miles. The histogram with a kernel density estimate highlights the central tendency around 200 miles.

3. **Average Base MSRP by Electric Vehicle Type**
   ![Average Base MSRP by Electric Vehicle Type](path_to_image)
   BEVs generally have a higher average MSRP compared to PHEVs. This is indicative of the technological and battery cost differences between the two types.

4. **Count of Vehicles by Model Year**
   ![Count of Vehicles by Model Year](path_to_image)
   Vehicle registration counts increase steadily over recent years, peaking in the latest model years, reflecting the growing adoption of electric vehicles.

5. **Electric Range vs Base MSRP**
   ![Electric Range vs Base MSRP](path_to_image)
   There is a positive correlation between electric range and base MSRP, with luxury brands typically providing higher range vehicles at a higher cost.

6. **Distribution of Clean Alternative Fuel Vehicle (CAFV) Eligibility**
   ![Distribution of CAFV Eligibility](path_to_image)
   The majority of the vehicles in the dataset are eligible for clean alternative fuel vehicle benefits, which suggests strong compliance with environmental standards.

7. **Number of Vehicles by County**
   ![Number of Vehicles by County](path_to_image)
   King County has the highest number of registered electric vehicles, followed by Pierce and Snohomish counties, indicating a higher adoption rate in urban and suburban areas.

8. **Average Electric Range by Make**
   ![Average Electric Range by Make](path_to_image)
   Tesla stands out with the highest average electric range among the top 10 makes, showcasing its market leadership in long-range electric vehicles.

9. **Vehicle Counts by Legislative District**
   ![Vehicle Counts by Legislative District](path_to_image)
   Legislative districts with urban centers show higher counts of registered electric vehicles, reflecting urban adoption trends.

10. **Base MSRP Distribution by Make for Top 10 Makes**
    ![Base MSRP Distribution by Make for Top 10 Makes](path_to_image)
    The boxplot shows a wide range of MSRP values across different makes, with Tesla and luxury brands having higher median MSRPs compared to other makes.

#### Conclusion
This analysis of the electric vehicle dataset reveals several key trends and insights:
- BEVs are more prevalent than PHEVs.
- The electric range of vehicles generally correlates with the vehicle's base MSRP.
- There is a growing trend in the adoption of electric vehicles, particularly in urban and suburban areas.
- Tesla dominates the market in terms of average electric range and higher MSRP vehicles.
- Legislative districts with higher urban populations have a higher number of electric vehicle registrations.

These insights can help policymakers, manufacturers, and consumers understand the current state of electric vehicle adoption in Washington State, guiding future decisions and policies to support the growth of electric mobility.

Dataset Link: https://www.kaggle.com/datasets/jainaru/electric-vehicle-population/data
