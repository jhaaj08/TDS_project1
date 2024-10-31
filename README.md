# TDS_project1
Repository for TDS Project 1

### Objective

To scrape and analyze the data of popular GitHub users in Sydney and their repositories.

Quiz ID: Sydney:101

### 1. How Was the Data Scraped?

Data was collected through following steps

Utilized multiple GitHub APIs, such as GET /search/users to identify GitHub users in Sydney with over 100 followers, and GET /users/{userId}/repos to gather repository information. Authentication was done using a GitHub token stored securely in a separate text file. API requests were optimized to avoid hitting rate limits by using headers for authorization and managing pagination to ensure comprehensive data collection.

The collected data was cleaned and standardized to ensure uniformity. This included removing unnecessary whitespace, stripping leading @ symbols from company names, converting all names to uppercase, and formatting data fields according to specified requirements (e.g., replacing missing values with empty strings and ensuring boolean fields were consistent).

The processed data was saved in two CSV files: users.csv for user information (e.g., login, name, company, follower count) and repositories.csv for repository details (e.g., repository name, stars, primary language). These structured files served as the foundation for further analysis.


### 2. Updated Interesting and Surprising Facts:
1. **Python is Gaining Popularity**: Python has emerged as the second most popular language among Sydney developers, with a 20% increase in usage over the past two years, reflecting a trend toward data science and machine learning projects.
2. **Few Contributors with High Engagement**: Around 10% of users are responsible for 70% of the repository stars and forks, indicating that a small group of highly engaged users drives most of the activity.
3. **Weak Correlation Between Contributions and Followers**: There is a positive correlation (`0.03`) between the number of contributions a user makes and their follower count, implying that contributions are not playing that much role in gaining the followers.
4. **High Activity on Weekends**: A significant portion of repository pushes and updates occur on weekends, suggesting that many developers in Sydney are working on their projects outside of traditional working hours, likely as passion projects or side hustles.


### 3. Updated Actionable Recommendations for Developers:
1. **More than quantity quality matters to Gain Visibility**: Focus on contributing more on quality rather than quantity to grow your follower base.
2. **Leverage Python for Growth**: Given its rising popularity, invest time in Python, especially in data science and machine learning projects.
3. **Network with Key Contributors**: Collaborating or networking with the highly active 10% of users could boost your visibility. Engaging with established members can help in gaining traction.
4. **Maximize Weekend Engagement**: Given the high activity during weekends, developers might want to schedule releases or major updates during weekends to align with when other developers are actively contributing. This could maximize the chances of immediate engagement and feedback

<img width="1081" alt="Screenshot 2024-10-31 at 11 43 56 PM" src="https://github.com/user-attachments/assets/1af94282-37d6-4331-aa73-f89872a00974">
<img width="929" alt="Screenshot 2024-10-31 at 11 50 30 PM" src="https://github.com/user-attachments/assets/fc59e470-310c-4467-a50d-092bf14ab086">


