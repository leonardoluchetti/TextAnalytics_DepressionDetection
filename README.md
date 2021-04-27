# TextAnalytics_DepressionDetection Project Overview
This depression detection ML project is based on Subreddit posts. Reddit is a social media platform where its user-generated content is organized in Subreddits, which are communities within the platform where users make posts about a specific topic. With administrators moderating such communities, hardly ever there is any content in Subreddits that do not align with its topic. Every subreddit has a feed, with thousands and thousands of public posts that were scraped and analyzed.

This machine learning tool analyzes specific features in the Subreddits' posts and look for depressive tendencies. As there are subreddits specifically dedicated to dissert about depression and related topics, we made use of them by identifying posts that belong to these communities as a dependent variable of 1 (indicating depressive tendencies). We scraped these communities as well as communities completely unrelated to depression, which in turn have a dependent variable of 0 (not indicating depressive tendencies). We trained our model on a vectorized dictionary from both types of communities (about and not about depression) to identify depressive tendencies in text. After building our optimal model, we applied it on other communities that have a gray area on their topic, such as communities based on addictions. Since these Subreddits are not necessarily directly related to depression, they will serve great value to us to put our model to use and identify which posts do and do not have depressive tendencies.

The expanded version of this project includes scientific research supporting the feature engineering used for other Machine Learning models, which are not included in this repository, as it only represents contributions solely from Luchetti in the field of Deep Learning.

This section of the project found that deep learning indeed is capable of recognizing depression in social media posts, and may be further studied to aid early detection of depression.
