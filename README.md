# Phase.1.Project
Phase 1 Project

# Business Understanding
-This Project analyzes the Aviation Accident Database from the National Transportation Safety Board which includes accident data from 1962-2023.
-We are determining if the Personal and Public airline industry is a viable business option for expansion.
-Analysis shows that while all planes crash, certain Models are safer and therefore reduce liability and risk. Analysis of Weather, severity of damage to the plane, phase of flight, and total fatal injuries can be used to determine the best options for the business.
Data Understanding
-This Project analyzes the Aviation Accident Database from the National Transportation Safety Board which includes accident data from 1962-2023.
The CSV file was donwloaded from Kaggle. This is a public website with various datasets. This is effectively all US crash data since the 60's.
There are 88889 entries with 30 different attributes for each entry. Attributes include Make and Model of plane, purpose of flight, aircraft damage, location of crash, and arcraft damage to name a few.

# Data Preperation
-Imputing values
-Cleaning up missing or NaN values
-removing irrelevant rows

# Data Analysis
-Analyzing to see which planes have the: 
-most fatal injuries
-most uninjured passengers
-most amount of engines
-specific engine types


# Conclusions
-1-We should target Models with more engines as the more engines on a plane, the less likely Fatal Injuries are to occur. More Engines means the plane is larger. We can tell by the frequency of crashes with the BOEING 737 and the amount of 'TotalUninjured' and 'Total.Fatal.Injuries' that the **BOEING 737 is one of the largest planes in our dataset.**
-2-There is a **negative correlation between Turbo engines and Fatal Injuries** as well, indicating that Turbo Engines are much safer than Reciprocating. BOEING and AIRBUS largely use Turbo fans and CESSNA uses Reciprocating.
-3-Based on the data we have present and a simple review of popularity of Models, the **Cessna 172 has one of the best safety record of planes in this dataset.** It ranks 25th in most uninjured passengers of all planes.

# Limitations
-This is only crash data, so if a plane theoretically has never crashed before, it would not be in this dataset.
-The majority of the rows were not used in final calculations due to so many NaN/missing values.
-This data is US based which limits international analysis.

# Conclusions
-Make a deeper analysis of Boeing 737 and Cessna 172.
-Analyze cost of maintenence for these 2 planes