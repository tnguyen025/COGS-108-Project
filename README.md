# COGS-108-Project
“A Little Bird Told Me” - Fake News, Twitter, and Society
TEAM NAME: Data Dawgs


TEAM MEMBERS: Jason Nideffer, David Alexander, Tuan Nguyen, Cuong Lai, Zizhen Wang


TEAM MEMBER GITHUB IDS: jasonnideffer, davidalexander3986, tnguyen025, cuongnt94,
roam55


DATA SCIENCE QUESTION(S) & HYPOTHESIS:
We plan on addressing one or more of the following:
1) Do fake or real news stories reach a broader audience?
- This entails looking at the number of people who tweet real vs. fake news stories, the
number of followers of each “sharing” account, and as well, additional story exposure
that might occur due to retweets.
2) Is there any social connection (follower/following relationships) between tweeters of fake
news? Is this an isolated community?
3) Is there some observable societal response to fake news stories? (ie. changes in google
search trends, occurence of events, etc.)
4) Is there a reliable way of determining if a news article is fake news?
- What parameters?
- Keywords
- Source
- Data from profiles of twitter users that tweet it (ie. followers, following, comments,
tweet text, etc.)


BACKGROUND:
Fake news is a scourge of modern society. Some have even likened it to a virulent strain,
spreading deceit as it propagates through the innocent public. This bold claim has inspired us
to examine for ourselves the extent to which fake news impacts our modern society. Our
approach to answering this question will use data science and modeling to analyze a dataset of
over 1,000 real and fake news stories and their dissemination throughout the Twitter
community.


ETHICAL CONSIDERATIONS:
Our dataset includes information that facilitates the identification of individuals that perpetuate
real and fake news. This information includes twitter handles and social media connections.
While these data are crucial to our study, sharing specifics pertaining to a single profile is
unnecessary. This will be considered when we publish our findings.


DATA:
Data sets include real and fake news articles with the following information documented:
- Headline, URL, Provider, Twitter ID’s of individuals who shared these stories
- https://www.kaggle.com/antmarakis/fake-news-data#fnn_politics_real.csv
The following data will also be scraped from Twitter using their API:
- User identification, followers/following, tweet text
We may later acquire additional datasets in order to answer questions related to the observable
effects of fake news.
