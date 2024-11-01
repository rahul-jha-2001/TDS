
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