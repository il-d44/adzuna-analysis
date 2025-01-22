 ## Outline
 This project contains a python script for extracting data on Data Engineer jobs from Adzuma's (website that lists jobs) Api. The data is then added to a Postgres database for analysis.

 ## Extraction Script Instructions
- Please install the packages from requirements.txt
- Please execute run_extraction **once** to populate the database
- Please execute run_update every 4 hours to update database

## Project Plan 
### Goals
1. Successfully extract and regularly update a database with new job listings via Azuma API.
2. Once the database is populated, ensure data is clean and transformed.
3. Analyse the job description field and aggregate data on most desired technologies.
4. Analyse the impact of location on salary
5. Create streamlit app to display findings

### Methods
1.
- Create function to request from API and store data in dictionary
- Wite function to connect to pagila database and create table
- Write function to insert data from the dictionary into created table.

  
2.
- Remove duplicates, handle missing values, and standardise formats.
- Validate the cleaned data to ensure consistency and accuracy.

3.
- Extract key technology-related terms from job descriptions using natural language processing (NLP).
- Group and count the occurrence of technologies to identify trends.
- Visualize the results to highlight the most in-demand technologies.

4.
- Conduct statistical analysis to identify correlation patterns between location and salary.
- Present findings with visualizations to compare salary ranges across locations.

5.
- Create markdown to tell story of the project
- Display visualisations on the page
- Create markdown to tell story of analysis





