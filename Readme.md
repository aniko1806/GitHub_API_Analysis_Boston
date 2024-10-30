Data Collection: Using Python in Google Colab, I accessed the GitHub API to gather data on Boston-based GitHub users with over 100 followers. Through requests and pandas, we retrieved, cleaned, and stored user profiles and repositories. We applied pagination to collect up to 500 repositories per user efficiently.


Interesting Findings: Interestingly, repositories without wikis or project boards have a slightly higher average star count. This could imply that simpler repositories, which focus more on core code and functionality, may attract more stars or that the community favors streamlined projects without additional documentation features.


Recommendation for Developers:For developers aiming to increase engagement, focusing on the quality of the code and core project features may be more beneficial than adding supplementary elements like wikis or project boards. Ensuring the main repository content is impactful can draw more attention.
