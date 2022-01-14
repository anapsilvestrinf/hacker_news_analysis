# Analysis of Hacker News Posts

### Project completed as part of Dataquest's Data Engineering path.

---------------------------------

**Hacker News** is a popular technology site that users submit posts that are voted and commented upon. This project is an analysis of **Ask HN** and **Show HN** types of posts on this popular site.

Posts whose titles begin with Ask HN are posts that ask the Hacker News community a specific question while Shows HN posts show the community a project, product, or something else.

Our goal is to determine which one receives more comments on average and if posts created at a certain time receive more comments on average.

The raw data set is located [here](https://www.kaggle.com/hacker-news/hacker-news-posts), but it has been reduced from almost 300,000 rows to approximately 20,000 rows by removing all submissions that not receive any comments, and then randomly sampling from the remaining submissions.
