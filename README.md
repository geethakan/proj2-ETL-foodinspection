<div><img align=left width=200px height=120px src="https://github.com/geethakan/proj2-ETL-foodinspection/blob/main/Images/inspections.jpg">
  
# ETL Mini Project - Food Inspections
  
This is a mini project done as a group and purposed to practice teamwork and collaborativeVio;a problem-solving. Timeframe was very limited and division of labor made it possible to accomplish the task.</div>


## Contributors
  
- Heather Robson
- Enrique Bouche
- Camille Jensen
- Geetha Kandukuri
  
  
## DataSets

<div> Source: <a href="https://data.cityofchicago.org/Health-Human-Services/Food-Inspections/4ijn-s7e5" target="_blank">Chicago Data Portal - Food Inspections.</a> 
Dataset #1 - Inspections of restaurants and food establishments in Chicago from January 2010 thru Jun 2018. Downloaded as csv</div>
  
  | Column Name   | Type    | Description              |
  | ------------- | ------- | ------------------------ |
  | Inspection Id | Int     | Unique Id per inspection 
  | DBA Name      | String  | Business Name            
  | AKA Name      | String  | Also Known As Name
  | License #     | Integer | License number for Business
  | Facility Type | String  | Business Type
  | Risk          | String  | Risk# and Category
  | Address       | String  | Strett address
  | City          | String  | City
  | State         | String  | 2 alpha State
  | Zip           | Int     | 5 digit zip
  | Inspection Date | Date  | date in USA format
  | Inspection Type | String | Nature of inspection
  | Results         | String | Pass/Fail/Conditional
  | Violations      | String | Violation number followed by description followed by comments
  | Latitude        | Float  | Latitude 
  | Longitude       | Float  | Longitude
  | Location        | String | Latitude and Longitude in dictionary format
