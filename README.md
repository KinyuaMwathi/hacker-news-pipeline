# **Hacker News Pipeline**

###
This is a hacker news pipeline created using JSON data of the top stories in 2014.

Hacker News is a link aggregator website that users vote up stories that are interesting to the community.

The JSON file in zip file contains a single key stories, which contains a list of stories (posts). Each post has a set of keys, but we will deal only with the following keys:

* **created_at** : A timestamp of the story's creation time.
* **created_at_i** : A unix epoch timestamp.
* **url** : The URL of the story link.
* **objectID** : The ID of the story.
* **author** : The story's author (username on HN).
* **points** : The number of upvotes the story had.
* **title** : The headline of the post.
* **num_comments** : The number of a comments a post has.

###
The goal is to find the top 100 keywords of Hacker News posts in 2014. Because Hacker News is the most popular technology social media site, this will give us an understanding of the most talked about tech topics in 2014!