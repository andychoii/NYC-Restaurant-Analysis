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

