Detecting Covert Bots in Political Subreddits Project

'Data' folder includes some data that we used in the project.
The data is retrived from 'reddit_crawler.ipynb' file.

There are seven .ipynb files we leveraged.

We used python 3.10, and requried packages are on the first cells, which are:
numpy
pandas
networkx
matplotlib
seaborn

praw
prawcore

sklearn
transformers
spacy

other trivial python packages (tqdm, os, re, etc...)

For .ipynb files,
reddit_crawler.ipynb: Parsing Reddit userdata
toxicity_analysis.ipynb: Analyzed toxicity based on the transformers
network_analysis.ipynb: Network analysis of user connection
bot_feature_extraction.ipynb: Extracted userdata of known bots
user_feature_extraction.ipynb: Extracted userdata of suspected bots
network_user_feature_extraction.ipynb: Extracted userdata of users in the network from network_analysis.ipynb
classifier.ipynb: Building classifier based on what we've found.
