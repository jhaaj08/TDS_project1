# TDS_project1
Repository for TDS Project 1

### Objective

To scrape and analyze the data of popular GitHub users in Sydney and their repositories.

Quiz ID: Sydney:101

### Three bullet Points for scoring 

### 1. How Was the Data Scraped?

Data was collected through following steps

- **Data Collection**: Used GitHub APIs (`GET /search/users` and `GET /users/{userId}/repos`) to gather data on Sydney users with over 100 followers. 
- **Data Processing**: Cleaned and standardized data by removing extra spaces, stripping leading `@` symbols, converting names to uppercase, and ensuring data field consistency.
- **Data Storage**: Stored cleaned data in two CSV files—`users.csv` for user details and `repositories.csv` for repository information.


### 2. Updated Interesting and Surprising Facts:

a. **Python is Gaining Popularity**: Python has emerged as the second most popular language among Sydney developers,  reflecting a trend toward data science and machine learning projects.

b. **High Activity on Weekends**: A significant portion of repository pushes and updates occur on weekends, suggesting that many developers are working on their projects outside of traditional working hours

### 3. Actionable Recommendations for Developers Based on Analysis

a. **Leverage Python for Growth**: Given Python’s growing popularity, developers should consider investing time in Python-related projects, particularly in fields such as data science, machine learning, and automation, to take advantage of emerging opportunities.

b. **Maximize Weekend Engagement**: Since many developers are highly active on weekends, it would be beneficial to schedule major releases or updates during the weekend. This approach could increase the likelihood of immediate feedback and engagement. 

<img width="1081" alt="Screenshot 2024-10-31 at 11 43 56 PM" src="https://github.com/user-attachments/assets/1af94282-37d6-4331-aa73-f89872a00974">
<img width="929" alt="Screenshot 2024-10-31 at 11 50 30 PM" src="https://github.com/user-attachments/assets/fc59e470-310c-4467-a50d-092bf14ab086">


