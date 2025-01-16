# Data & Business Analytics

#### Skills: SQL, R, Python, MS Excel, Tableau

## Education
- Bachelor of Science, Business Economics | University of California, San Diego
(_June 2024_)

## Certifications
- Google: Google Data Analytics Professional Certificate (_October 2024_)
- Udemy: The Ultimate MySQL Bootcamp (_November 2024_)

## Projects
### FitBit Analysis
[Github Read Me File](https://github.com/matthewarucan/Google-Data-Analytics-Case-Study)

### Example SQL Query

The following SQL query retrieves data from the `daily_activity` table for users who have taken more than 10,000 steps in a day and orders the results by the number of steps in descending order:

```sql
SELECT 
    ID, 
    ActivityDate, 
    TotalSteps, 
    TotalDistance, 
    Calories
FROM 
    daily_activity
WHERE 
    TotalSteps > 10000
ORDER BY 
    TotalSteps DESC;
