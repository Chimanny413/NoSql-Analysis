# NoSQL Challenge: Food Hygiene Ratings Analysis
## Overview
This project involves analyzing and managing food hygiene ratings data from the UK Food Standards Agency. The goal was to update and query a MongoDB database to generate insights for a food magazine, Eat Safe, Love. Tasks included data insertion, cleaning, and exploratory analysis using Python and NoSQL techniques.

## Tools and Technologies
- **Database**: MongoDB
- **Programming** Language: Python
- **Libraries**: PyMongo, Pandas, Pretty Print (pprint)
- **Environment**: Jupyter Notebook

## Project Objectives
1. **Database Setup:**

    - Import food hygiene ratings data from a JSON file into MongoDB.
    - Validate the setup by listing databases, collections, and sample records.
2. **Database Updates:**

   - Add a new restaurant record and update its information.
   - Remove records from a specific region (e.g., Dover).
   - Standardize data types for latitude, longitude, and rating values.
3. **Exploratory Analysis:**

   - Identify establishments with poor hygiene scores.
   - Find highly-rated establishments in London.
   - Locate top-rated establishments near a specific restaurant.
   - Rank regions based on the number of establishments with hygiene scores of 0.
## Key Queries and Analyses
- Filter establishments based on hygiene scores and rating values.
- Use regular expressions to locate records by region.
- Perform geospatial analysis to find nearby establishments.
- Aggregate data to identify hygiene trends across regions.
## Results
- Identified hygiene problem areas and top-rated establishments.
- Cleaned and standardized the database for better analysis.
- Delivered actionable insights for editorial decision-making.
