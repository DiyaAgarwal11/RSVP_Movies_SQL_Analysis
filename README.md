# **RSVP Movies Data Analysis Project**

### **Project Overview**
This project analyzes data from the IMDb database, focusing on past movie performance to help RSVP Movies, an Indian production company, make informed decisions for an upcoming global release. By leveraging SQL, the analysis uncovers key insights into genres, actor performance, and production strategies, providing actionable recommendations to guide their project.

### **Objectives**
- **Movie Data Analysis:** Use SQL to extract critical insights from IMDb data, covering metrics like genre popularity, actor and director performance, and production success.
- **Recommendations:** Provide strategic advice on genre selection, release timing, casting, and potential partnerships for the upcoming project.
- **Executive Summary:** Compile findings into a concise report to inform RSVP Movies’ global release strategy.

### **Dataset**
The dataset includes IMDb movie information spanning the last three years. Key details such as movie titles, genres, ratings, directors, and actors are used for in-depth analysis. The relationships between tables are defined in the provided Entity-Relationship Diagram (ERD).

### **Repository Contents**
- **SQL Script:** `IMDB+solution.sql` – Contains the SQL queries used for analysis.
- **Dataset & ER Diagram:** `IMDb+movies+Data+and+ERD+final.xlsx` – The dataset and a detailed ERD for better understanding of the database structure.
- **Executive Summary:** `Executive Summary.pdf` – A PDF report summarizing the analysis results and recommendations.

### **Steps for Analysis**
1. **Database Setup:** Import the SQL script `IMDB+dataset+import.sql` into MySQL to create and populate the necessary tables.
2. **Run SQL Queries:** Execute the queries in `IMDB+solution.sql` to generate insights.
3. **Analyze Results:** Review query outputs to derive actionable insights for RSVP Movies’ upcoming release.
4. **Compile Executive Summary:** Based on the results, the executive summary outlines the optimal strategy for the project.

### **Insights & Recommendations**
- **Optimal Release Period:** Avoid high-competition months like March for better visibility and profitability.
- **Genre Preference:** Focus on the 'Drama' genre, with an ideal movie length of **107 minutes**, as this has shown to be highly popular.
- **Partnerships:** Consider collaborations with production houses like **Dream Warrior Pictures**.
- **Casting:** Actors like **Mammootty and Mohanlal** have delivered high ratings, making them ideal candidates for the lead roles.
- **Directors:** **James Mangold**’s strong track record across genres makes him a top director choice.
- **Global Partnerships:** Collaborate with companies like **Marvel Studios** to expand market reach.

### **How to Run**
1. Download and set up a SQL IDE (e.g., MySQL Workbench).
2. Load and run the `IMDB+dataset+import.sql` to set up the database.
3. Execute the `IMDB+solution.sql` script to analyze the data and review results.
