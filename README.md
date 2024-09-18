# Oakland-crime

In this project, I employ SQL and Tableau to complete the following tasks:

- Prepare database (importing table with raw data, creating/altering/updating new table) using PostgreSQL
- Review, clean, reformat, and wrangle data (recategorizing rows with null values, converting text strings to usable lat-long fields, etc.)
- Export cleaned/reformatted data to CSV file for use in Tableau
- Create interactive dashboard, dynamic with filtering/daterange capabilities, displaying high-level crime report details (averages/counts over time ranges/categories and geographic mapping)

Follow along with the .sql file in your preferred RDBMS program to review the cleaning process. The data consists of Oakland, CA crime reports over 90 days (sourced from the official City of Oakland website). The data required significant wrangling, as well as some additional cleaning, before it could be rendered usable, due to a large amount of null values in the "CRIMETYPE" field. 

See dashboard image or .pdf for a snapshot of the finalized dashboard, or open the Tableau file or follow this link ([https://public.tableau.com/app/profile/ivan.sham8869/viz/OaklandCrime_17193870296240/Dashboard1](https://public.tableau.com/app/profile/x1van510/viz/OaklandCrime_17193870296240/Dashboard1)) to fully explore the interactive dashboard that adjusts itself dynamically to functional controls (functions include daterange selection, crimetype filtering, tooltip data from mouse cursor hovering, etc.). 
