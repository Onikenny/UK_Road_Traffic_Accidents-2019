# UK_Road_Traffic_Accidents-2019

This project investigates specific crash trends on smaller scales, including weekly and across days, the relationship between different data 
features and the rate of crash incidences in the UK in 2019. Predictive models are also developed to forecast the potential time, location and severity of accidents.


A final report on the project can be accessed here: [Accidents Analysis - UK (2019).pdf](https://github.com/Onikenny/UK_Road_Traffic_Accidents-2019/blob/d2fdcde16eba6e800d1fa6df799e6f88918d2ca3/Accidents%20Analysis%20-%20UK%20(2019).pdf)


### Data:
Annual release by Department of Transportation on GOV.UK. The data comprises three datasets.(Available in this repo.)

1. Accidents: 32 variables, detailing location, time, date, lighting, weather, road conditions and other variables. The unique accident index identifies each observation and make up one of 117,536 collisions.
2. Vehicles: Contains details of vehicles involved in the accidents.
3. Casualties: 16 columns with information about casualties involved in accidents. 


### Major Packages used (see notebook for full list): 
- Python.3.10 
- Pandas Python Data Analysis Library. V.1.3.4 for data cleaning and pre-processing. Also, to generate Statistical profiling of data.
- Sklearn for Hypothesis testing, statistical modelling and predictive analysis
- Linear Regressor, K-Nearest Neighbor regressor and classifier, Gradient Boosting regressor and classifier, Random Forest regressor and classifier and XGBoost Classifier, Stacking regressor and classifier for predictive analysis. 
- Seaborn 0.11.2, Matplotlib for data visualization
              
Run notebook on [Colab](https://colab.research.google.com/drive/1BxmV8mATjTIBNwrbUtLF-B-so5anAflh?usp=sharing)
