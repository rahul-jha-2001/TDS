
Used the GitHub API:

Get a List of Users:

Fetch users located in Mumbai with more than 50 followers:
GET https://api.github.com/search/users?q=location:Mumbai+followers:>{min_followers}&page={page}&per_page={per_page}
Get Details of Individual User:

Retrieve detailed information about a specific user:

GET https://api.github.com/users/{USERNAME}
Get a List of Repositories of a User:

Fetch the repositories for a specific user:
GET https://api.github.com/users/{USERNAME}/repos
Script to Scrape Data:

Wrote a script to scrape data from the above endpoints and implement a simple disk cache. This was done by saving the scraped data in a JSON file, allowing for retrieval of data if it has already been scraped.


Observation:

A significant number of users ranking in the top 10 of the leadership metric are tech YouTubers.

Top 5 used licenses are :'mit', 'apache-2.0', 'other', 'gpl-3.0', 'bsd-3-clause'

Top 5 Languages as per the percentage of stars of the given language:
Python 30.07680692007979
JavaScript 12.97608172852855
TypeScript 6.674465427564736
Jupyter Notebook 5.498592494547082
C# 4.640573441956712

Creation of User and repos are mostly uniform across different time intervals except year as a large number of accounts have been created after 2020

Recommendation: