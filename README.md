Reddit Post Suggestions

The purpose of this project is to analyse a user’s upvoted (liked) posts, and based on them will be able to recommend posts from random popular subreddits.

The program is running on a Raspberry Pi. I am using Python3.5, SQLite3,NLTK (Natural Language Toolkit), and the Reddit API available for free. 
Depending on the already sorted and categorized upvoted posts, the new ones will receive a matching score. If the score is high enough, the post will be recommended. 



Two tips to get you started:
Inside reddit_bot.py, at the bottom, there are two lines of code.
Uncommenting them will fetch upvotes and populate database again

Inside scan_and_find.py, at the bottom, there is one object and two
methods. The estimate_recommend will provide a list of
recommendations. e update_keywords, will run NLTK
methods over the titles inside the upvotes_db.
