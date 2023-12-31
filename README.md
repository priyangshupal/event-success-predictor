# event-success-predictor

Course Project for CS-GY 6513 Big Data

Given a past event, we will gather its reviews from major social media websites (like [X](https://twitter.com/), [Reddit](https://www.reddit.com/), [Eventbrite](https://www.eventbrite.com/), etc.) and classify the event as successful or unsuccessful. It will involve sentiment analysis on the gathered data corpus - for example: we will have to identify whether people have positively or negatively reacted to the event and how effectively the event involved its target audience. A successful event will have a lot more positive reviews and ratings. Negative reviews, on the other hand, will be ridiculed on social media posts and might even receive hate at times.

## Workflow & Technologies

![Workflow](/docs/workflow.png)

## Why is this a Big Data problem?

Our project would involve scraping event reviews from different social media websites and training a sentiment analysis model with it that will classify new events as success or failure. Event success classification using sentiment analysis is a big data problem because of the large volume of ever changing data involved including different languages, slangs, emoji usages, etc.. With neologisms being coined and used frequently, the dataset is continuously growing requiring real-time or near-real time processing for accurate analysis.

One of the major challenges is scaling the processing to efficiently handle such immense volumes of data. Conventional systems cannot effectively process such large datasets, demanding the use of distributed technologies such as MongoDB, Spark. These technologies distribute the data and processing tasks across multiple machines, allowing for faster and more efficient processing while highlighting the Big Data aspect of the Event success classification problem.

## Setup

References

- [Installation - PySpark](https://spark.apache.org/docs/latest/api/python/getting_started/install.html)
- [Project Jupyter - Installing Jupyter](https://jupyter.org/install)

## Technologies

- Python
- Jupyter Notebook
- MongoDB
- PySpark
- Dask
- Matplotlib
- scikit-learn
- PRAW - [The Python Reddit API Wrapper](https://praw.readthedocs.io/en/stable/)

## Team

1. Jai Kumar Joshi - jkj9358@nyu.edu
2. Priyangshu Pal - pp2833@nyu.edu
3. Sarthak Umarani - snu2006@nyu.edu
