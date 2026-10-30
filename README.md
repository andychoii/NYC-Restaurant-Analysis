# NYC-Restaurant-Analysis

Restaurant inspections are a cornerstone of public health in NYC. With more than 26,000 establishments inspected each year, even minor food-safety lapses can have city-wide effects. Using inspection data from 2020-2022, I've analyzed violation types, locations, and enforcement actions to uncover trends that can guide the Department of Health to implement targeted interventions. Before analysis, the dataset was cleaned and standardized - removing duplicates, filling in missing ZIP codes and violation codes, and grouping violations into categories to ensure accuracy and consistency across all visuals.

# Objective

The key focus was to analyze NYC restaurant inspection data to identify violation patterns and closure risks. Also, to uncover geographic, seasonal, and category-based trends in health vode violations. Then, to identify most common violations driving enforcement. actions and closures. Finally, target high-risk areas and establishments to inform smarter resource allocation and public health interventions in NYC DOH.


# Data Cleaning

Inspected the dataset checking for IDs, irrelevant data, and narrowing the years to 2020-2022. Also, removed duplicate rows/values and trimmed white space/double spaces in cell values. Moreover, removed Null values, filled in missing values for zip codes, violation codes, actions, and no violations code. Last but not least grouped violations together according to DOH Health Code for better comprehension and formatting.

# Key Findings
## Which Boroughs and Neighborhoods Experience the Most Violations?

<img width="694" height="627" alt="Screenshot 2026-10-30 at 11 43 01 AM" src="https://github.com/user-attachments/assets/9e74585b-9c7c-4b99-b084-08d4a17e3668" />

Total Count of Restaurant Violations in NYC
- Most health code violations are located in Manhattan, Northern Queens, and Western Brooklyn
- Manhattan
  - East Village, Union Sq. (10003): 1,715 violations
  - Tribeca (10013): 1,648 violations
  - Upper West Side (10019): 1,623 violations
- Queens
  - Flushing (11354): 1,404 violations
  - Jackson Heights (11372): 1,337 violations
- Brooklyn
  - Sunset Park (11220): 1,322 violations
  - Downtown Brooklyn (11201): 1,139 violations

<img width="661" height="549" alt="Screenshot 2026-10-30 at 11 47 29 AM" src="https://github.com/user-attachments/assets/71d3841e-8972-42c7-b619-88eb3fe2aef8" />

Critical Counts by Borough
- Manhattan, Brooklyn, Queens with highest violations (9,948 - 15,388)
- Bronx & Staten Island with lower violations (1,408 - 3,795)

<img width="654" height="602" alt="Screenshot 2026-10-30 at 11 48 39 AM" src="https://github.com/user-attachments/assets/1d123658-c38a-45a2-98e8-2e4f69238bfa" />

Critical Violations by Zip Code
- Zip code analysis reveals clear hotspots in Manhattan, Brooklyn, and Queens where public health risks are highest
- Manhattan: Concentrated in Midtown and Lower Manhattan (Zip Code: 10003, 10013, and 10019)
- Brooklyn: Clusters in Downtown Brooklyn and Sunset Park (Zip Code: 11220 and 11201)
- Queens: Primarily concentrated in Flushing (Zip Code: 11354)

## What are the most prominent violations?

<img width="1328" height="555" alt="Screenshot 2026-10-30 at 11 51 02 AM" src="https://github.com/user-attachments/assets/561e856b-e649-40e1-81b6-d0859485b6d2" />

Top Violation Categories
- Pest problem was ranked first with over 21,000 recorded violations from NYC restaurants, which is a drastic jump from the second top category (Facility/Maintenance) with a little over 12,000 violations
- Because the top 5 highlighted in color mostly relates to food safety and facility cleanliness, it emphasizes the need for better pest control and hygience practices at restaurants

<img width="1278" height="633" alt="Screenshot 2026-10-30 at 11 52 16 AM" src="https://github.com/user-attachments/assets/912e86a5-ee33-428c-bc7f-f49850e0a410" />

Percentage Breakdown of Top Violation Categories and Codes
- Code 04L in pest problem accounts for about 16% of the critical violations. And this code means there was evidence of live mice present in the restaurant.
- For the code 02G, it's related to not storing cold food properly, which accounts for around 12% of the critical violations
- Another very prominent code was 06D that involves food contact surfaces not properly sanitized after each use
- As a result, these violations could lead to serious health issues for customers. So we wanted to highlight this to show to the DOH

<img width="837" height="322" alt="Screenshot 2026-10-30 at 12 02 05 PM" src="https://github.com/user-attachments/assets/ec29e01c-7846-4e46-99a9-eeb03228b558" />

Top Critical Violation per Zip Code
- This highlight table focus mainly on Manhattan and Brooklyn because earlier we noted that these two boroughs has the most critical violations
- From the table, Manhattan zipcodes like 10003 and 10013 show pretty high counts for pest and food handling (244 and 234 respectively). These trends are pretty similar in Brooklyn.
- Suggest that DOH should focus their funding on tackling these severe issues that are prominent in high density zipcodes located in dense boroughs like Manhattan and Brooklyn


## Do Violations Fluctuate with the Seasons?

<img width="1079" height="493" alt="Screenshot 2026-10-30 at 12 05 44 PM" src="https://github.com/user-attachments/assets/5d70ef26-e9b1-4443-a2f2-fad16b3e1c1d" />

Top Critical Violations Over Time
- The timeline demonstrates spikes in violations during the colder monghts, particularly around December through February, with drop offs happening around March and April. This pattern suggests that issues tend to worsen during winter, possibly because colder temperatures drive pests indoors and restuarants operate in more enclosed environments
- Clear drop around early 2020, which aligns with the pause in inspection during COVID, followed by a sharp rise once inspections resumed in the summer of 2021
- Overall, this trend shows that violations aren't random meaning they increase during the months with extreme temperature, implying the DOH may need to focus more resources on inspections and prevention efforts during the winter and summer seasons when risk factors are higher

## Do High-Violation Areas Overlap with Closure Hotspots?

<img width="611" height="452" alt="Screenshot 2026-10-30 at 12 10 29 PM" src="https://github.com/user-attachments/assets/bb572975-d4d3-4319-8cd7-ff4a43b7d733" />

Actions Taken Based on Violation
- Violation categories tied to closures persist year over year in an upwards trends, despite pandemic recovery
- Spike in 2021 reflects post-pandemic reopening inspections, yet violations remained elevated in 2022 instead of stabilizing
- Suggests systemic/managerial issues, not seasonal


<img width="683" height="491" alt="Screenshot 2026-10-30 at 12 12 21 PM" src="https://github.com/user-attachments/assets/60524c16-2b77-4253-9a17-c70bbd219234" />

Critical Violation Closures
- Manhattan
  - Tribeca (10013): 66 restaurants
  - East Village, Union Sq. (10003): 54 restaurants
- Brooklyn (11214)
  - Bensonhurst: 64 restaurants

# Recommendations

Recommend hosting mandatory pest preventions workshops specifically zip codes like 10013 and 10003 in lower Manhattan. These workshops would review food storage, waste disposal, and cleaning routines to ensure the Restaurants follow best practices to prevent pest issues. Additionally, within these areas the DOH should provide funding for sanitation supplies which would help include cleaning chemicals, proper trash containers, and pest traps to help businesses maintain compliance with health code more consistently. Finally, based on timeline analysis, there were seasonal spikes in critical violations during winter monthds. To address this, we recommend increasing inspecting frequency during those high-risk periods.


## Tools and Technologies
Tableau and Excel

# Limitations and Next Steps




