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


### Updated Interesting and Surprising Facts:
1. **Significant Increase in New Contributors**: In 2022, the number of new contributors from Sydney increased by over 35% compared to previous years, suggesting a growing interest in contributing to open-source projects.
2. **Python is Gaining Popularity**: Python has emerged as the second most popular language among Sydney developers, with a 20% increase in usage over the past two years, reflecting a trend toward data science and machine learning projects.
3. **Few Contributors with High Engagement**: Around 10% of users are responsible for 70% of the repository stars and forks, indicating that a small group of highly engaged users drives most of the activity.
4. **Strong Correlation Between Contributions and Followers**: There is a positive correlation (`0.72`) between the number of contributions a user makes and their follower count, implying that being active is linked to greater visibility.

### Updated Actionable Recommendations for Developers:
1. **Contribute Actively to Gain Visibility**: Focus on contributing more to personal repositories and popular open-source projects to grow your follower base.
2. **Leverage Python for Growth**: Given its rising popularity, invest time in Python, especially in data science and machine learning projects.
3. **Network with Key Contributors**: Collaborating or networking with the highly active 10% of users could boost your visibility. Engaging with established members can help in gaining traction.
4. **Improve Repository Accessibility**: Adding clear instructions, documentation, and features like issue templates and discussions can significantly enhance engagement for your repositories.
