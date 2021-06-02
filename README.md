# RFM-Analysis and Project Recommender System in R 
Project recommendation system for DonorsChoose.org in R based on RFM analysis and K-Means Clustering

* * *

## Background and Objective
DonorsChoose.org is a US based non-profit organisation founded in the year 2000, that helps public school classroom projects get funded directly by helpful donors. Through charity, they make it easy for anyone to help a classroom in need. The organisation wants to inspire active donors to donate again towards projects they feel strong about. In order to do that, the organisation wants to pair the donors with related classrooms based on their previous donations and interests so that they are motivated to donate again. 

Sometimes there are chances that some projects may not come into light but are desperate for donations. Therefore, we build a recommendation system that recommends categories of projects to teachers across based on previous donations or interests through RFM (Recency, Frequency, Monetory value) clustering analysis to group similar types of donors mapped with the respective project category through recommendation.

* * *

## About the dataset
The dataset package provided consists of 6 files containing the details of donations, donors, schools, projects, teachers and resources.

Source: Kaggle (update - The dataset has been removed now)

* * *

## How does this analysis help?
Before making recommendations, it would be great to know the right set of donors based on their recent activities, how they actively involve themselves or stay less connected.

Helps find the right set of projects for first time donors. Since we're not usually aware of their preferences yet, its difficult to comprehend their interests right away, leading to a cold start problem. Unlike collaborative or content based filtering, we do not have to deal with the pattern of users' interests in case of first time donors. So using the RFM clustering technique can solve such problems.

