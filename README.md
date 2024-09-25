# Electric_Vehicle_Population_Analysis

![](https://i.imgur.com/UD4zG1r.jpg) ![](https://i.imgur.com/gNJEyFR.jpg)

## What is Exploratory Data Analysis?
- Exploratory Data Analysis (EDA) is the process of analyzing a dataset in order to understand its main characteristics, patterns and identify anomalies. EDA is often the first step in the data analysis process.

- It involves using different graphs and plots to help visualise the data and also uses statistical methods to draw inferences from the data.

- The goal of EDA is not to arrive at a certain right answer or to confirm a pre-defined hypothesis. It is an exploratory process to draw inferences and get ideas on how the data can be further utilised to predict certain outcomes/develop ML models

- ## Introduction to the Electric Vehicles
- - An electric vehicle (EV) is a vehicle that uses one or more electric motors for propulsion. It can be powered by a collector system, with electricity from extravehicular sources, or it can be powered autonomously by a battery (sometimes charged by solar panels, or by converting fuel to electricity using fuel cells or a generator).

- EVs include, but are not limited to, road and rail vehicles, surface and underwater vessels, electric aircraft , and electric spacecraft.
- For road vehicles, together with other emerging automotive technologies such as autonomous driving, connected vehicles, and shared mobility, EVs form a future mobility vision called Connected, Autonomous, Shared, and Electric (CASE) Mobility.
- EVs first came into existence in the late 19th century, when electricity was among the preferred methods for motor vehicle propulsion, providing a level of comfort and ease of operation that could not be achieved by the gasoline cars of the time.
- Internal combustion engines were the dominant propulsion method for cars and trucks for about 100 years, but electric power remained commonplace in other vehicle types, such as trains and smaller vehicles of all types.

## About Dataset
This dataset shows the Battery Electric Vehicles (BEVs) and Plug-in Hybrid Electric Vehicles (PHEVs) that are currently registered through the Washington State Department of Licensing (DOL).

1.A Battery Electric Vehicle (BEV) is an all-electric vehicle using one or more batteries to store the electrical energy that powers the motor and is charged by plugging the vehicle into an electric power source.

2 Alternative Fuel Vehicle (CAFV) Eligibility is based on the fuel requirement and electric-only range requirement as outlined in RCW 82.08.809 and RCW 82.12.809 to be eligible for Alternative Fuel Vehicles retail sales and Washington State use tax exemptions.

3.Monthly count of vehicles for a county may change from this report and prior reports. Processes were implemented to more accurately assign county at the time of registration.

4.Electric Range is no longer maintained for Battery Electric Vehicles (BEV) because new BEVs have an electric range of 30 miles or more. Zero (0) will be entered where the electric range has not been researched.

5.Field 'Electric Utility' was added starting with the publication in March 2022.

6.Field '2020 Census Tract' was added starting with the publication in June 2022.

### PROJECT OUTINE

The steps involved in the process of Exploratory Data Analysis are.,

- Import the required libraries and its dependencies.

- Download the dataset.

- Data preparation and cleaning it.

- Exploratory Analysis.

- Ask and solve questions from the data.

- Pictorial representation of data using visualization techniques.

- # Conclusion and Insights

## Conclusion:

### The analysis of the electric vehicle (EV) dataset provided valuable insights into the EV market trends, 
### geographic distribution of Tesla vehicles, and the performance of machine learning models in predicting
### EV prices. The exploration of various features such as make, model, electric range, model year, and base MSRP
### revealed significant patterns and relationships.

## Key Insights:

### 1. **Tesla Dominance:**  Tesla stands out as the leading EV manufacturer in terms of the number of vehicles
### registered, indicating its strong market presence and popularity. The analysis of Tesla's model distribution further highlights consumer preference for specific Tesla models.

### 2. **Geographic Variation:** The analysis of Tesla's presence across different cities revealed that some cities have a higher concentration of recent Tesla models, suggesting varying levels of adoption and market maturity in different geographic regions.

### 3. **EV Market Growth:** The trend of EV sales over the years revealed a positive growth trajectory, indicating a growing demand for electric vehicles.

### 4. **CAFV Eligibility:** The analysis of Clean Alternative Fuel Vehicle (CAFV) eligibility highlighted the
### prevalence of EVs that are eligible for potential government incentives and programs.

### 5. **Model Year Influence:**  The model year of the vehicles played a significant role in predicting their base MSRP, highlighting the impact of technological advancements and product evolution on pricing.

### 6. **Machine Learning Performance:** The linear regression model demonstrated a reasonable ability to predict
### the base MSRP of EVs based on features like make, model, electric range, and model year. However, the 
### model's performance can be further improved through exploration of alternative machine learning models, feature engineering, and hyperparameter tuning.

### 7. **Outlier Handling:** Removing outliers from the dataset helped to improve the robustness and accuracy of the models trained on the data.


## Future Directions:

### 1. Explore advanced machine learning models: Implement and evaluate models like random forests, support vector
### machines, or neural networks to potentially improve prediction accuracy.
### 2. Feature Engineering: Enhance features by creating new variables from existing ones or including other
### relevant data (e.g., charging infrastructure data, fuel economy ratings, customer reviews).
### 3. Hyperparameter tuning: Optimize model hyperparameters to improve prediction accuracy.
### 4. Sentiment Analysis: Utilize natural language processing (NLP) techniques to analyze customer reviews and
### feedback to understand consumer perception of different EV brands and models.
### 5. Advanced Visualization: Develop more interactive and informative visualizations to explore relationships between different features and patterns in the dataset.


### This analysis provides a comprehensive starting point for understanding the EV market. By incorporating
### additional features and utilizing advanced analytical techniques, a more comprehensive understanding of the
### EV market can be obtained. 
