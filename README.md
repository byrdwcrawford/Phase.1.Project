# Aviation Crash Data Analysis
Phase 1 Project
* By: Will Byrd
* Email: byrdwcrawford@gmail.com
* Linkedin: https://www.linkedin.com/in/will-byrd-40323863/
* Wordpress: blog33497.wordpress.com

# Business Understanding
* This Project analyzes the Aviation Accident Database from the National Transportation Safety Board which includes accident data from 1962-2023.
* We are determining if the Personal and Public airline industry is a viable business option for expansion.
* Analysis shows that while all planes crash, certain Models are safer and therefore reduce liability and risk. Analysis of Weather, severity of damage to the plane, phase of flight, and total fatal injuries can be used to determine the best options for the business.
Data Understanding
* This Project analyzes the Aviation Accident Database from the National Transportation Safety Board which includes accident data from 1962-2023.
* The CSV file was donwloaded from Kaggle. This is a public website with various datasets. This is effectively all US crash data since the 60's.
* There are 88889 entries with 30 different attributes for each entry. Attributes include Make and Model of plane, purpose of flight, aircraft damage, location of crash, and arcraft damage to name a few.

# Data Preperation
* Imputing values
* Cleaning up missing or NaN values
* Removing irrelevant rows

# Data Analysis
* Analyzing to see which planes have the: 
* most fatal injuries
* most uninjured passengers
* most amount of engines
* specific engine types
* count of fatal injuries by engine type
![Fatal Injuries by Engine Type](https://github.com/byrdwcrawford/Phase.1.Project/blob/main/Images/Engine_Type%20Injuries.png)
* count of total fatal injuries across planes
![Total Fatal Injuries](https://github.com/byrdwcrawford/Phase.1.Project/blob/main/Images/Total_Fatal_Injuries.png)
* count of fatal injuries by number of engines on a plane
![Fatal Injuries by Engine Number](https://github.com/byrdwcrawford/Phase.1.Project/blob/main/Images/Engine_Number.png)

# Interactive Dashboard
Link to Interactive Dashboard  https://public.tableau.com/app/profile/will.byrd3029/viz/WBAviationDataDashboard/Phase1Dashboard?publish=yes

# Conclusions
* BOEING 737  #1 recommendation
*     1st in most injured and Uninjured
*     Multiple Turbo Engine Plane
*     Least risk per passenger
* CESSNA 172  #2 recommendation 
*     25th in most uninjured
*     Single Reciprocating Engine
*     Least overall Risk


# Limitations
* This is only crash data, so if a plane theoretically has never crashed before, it would not be in this dataset.
* The majority of the rows were not used in final calculations due to so many NaN/missing values.
* This data is US based which limits international analysis.

# Next Steps
* Make a deeper analysis of Boeing 737 and Cessna 172.
* Analyze cost of maintenence for these 2 planes.