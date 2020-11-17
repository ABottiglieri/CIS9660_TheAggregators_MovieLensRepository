## CIS9660_TheAggregators_MovieLensRepository

### Using Data Mining to Increase User Engagement on an Online Movie Streaming Website: An Unsupervised Learning Model to Provide Personalized Movie Recommendations 

#### 1. Team Members
Deepa Rajareddy – Deepa.rajareddy@baruchmail.cuny.edu
Sera Ahmed – Sera.ahmed@baruchmail.cuny.edu
Shani Batat – Shani.batat@baruchmail.cuny.edu
Janani Ravichandran – Janani.ravichandran@baruchmail.cuny.edu
Alexandria Bottiglieri – Alexandria.bottiglieri@baruchmail.cuny.edu

#### 2. Description of the Project
MovieLens is a streaming service that offers a variety of award winning movies on hundreds of internet connected devices. You can watch as much as you want and whenever you want. 

#### 3. Identifying The Business Problem
In the last couple of years, MovieLens has seen a drastic decrease in user engagement as well as record high percentages of user churn. The company’s user base went from 1,000 users down to 700 users, and movies watched decreased from 20+ movies watched per month to less than 10 movies watched per month per user.

To keep the company from losing viewership and profits, they have hired a team of data scientists to find ways to increase user engagement.

By analyzing the available data, our team intends to identify the clusters of users and create a recommendation engine that makes personalized recommendations to users based on the user’s historical movie watching and ratings data, as well as the historical movie watching and ratings data of similar users. We will also make movie recommendations based on movies with similar traits as those previously watched (i.e. genre, production company, or actors).

#### 4a. Number of Instances
The complete data contains ~20 million instances. For this project, our team will select a random sample of 100,000 instances from this dataset. 

#### 4b. Number of Features
The dataset has 6 features. We might further derive variables/dummy variables during the EDA phase. 

Tag: userId,movieId,tag,timestamp
Movies: movieId,title,genres
Rating: userId,movieId,rating,timestamp
Link: movieId,imdbId,tmdbId
Genome_tags: tagId,tag
Genome_scores: movieId,tagId,relevance
	
#### 4c. Missing Values?
Tag: 16
Movies: 0
Rating: 0
Link: 0
Genome_tags: 0
Genome_scores: 0

#### 5. Target variable? Classification Task or Regression? 
For this project, we will be working a hybrid recommendation model. We will primarily focus on two aspects -  

Content-based recommendation: How can we recommend movies based on the current type of content that the user consumes?
Collaborative recommendation: Identify clusters or lookalike customers and recommend content based on the lookalike customer’s movie consumption. 
