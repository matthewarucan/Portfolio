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


### Example SQL Query Output

The following table shows the output of the SQL query that retrieves data for users who have taken more than 10,000 steps in a day:

| ID   | ActivityDate | TotalSteps | TotalDistance | Calories |
|------|--------------|------------|---------------|----------|
| 1501 | 2025-01-01   | 12000      | 8.5 km        | 350      |
| 1502 | 2025-01-02   | 15000      | 10 km         | 400      |
| 1503 | 2025-01-03   | 17000      | 11.5 km       | 450      |

### Explanation:

- **ID**: The unique identifier for each user.
- **ActivityDate**: The date of the activity.
- **TotalSteps**: The total number of steps taken by the user on that date.
- **TotalDistance**: The total distance covered, typically measured in kilometers or miles.
- **Calories**: The number of calories burned.

You can add more rows to the table as needed to display additional output from the SQL query.
