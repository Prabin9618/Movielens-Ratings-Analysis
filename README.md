# Movielens-Ratings-Analysis

### Problem Background:
The GroupLens Research Project is a research group in the Department of Computer Science and Engineering at the University of Minnesota. Members of the GroupLens Research Project are involved in many research projects related to the fields of information filtering, collaborative filtering, and recommender systems. The project is led by professors John Riedl and Joseph Konstan. The project began to explore automated collaborative filtering in 1992 but is most well known for its worldwide trial of an automated collaborative filtering system for Usenet news in 1996. Since then the project has expanded its scope to research overall information by filtering solutions, integrating into content-based methods, as well as, improving current collaborative filtering technology.

### Problem Objective:
Performing analysis using the Exploratory Data Analysis technique and finding features affecting the ratings of any particular movie and build a model to predict the movie ratings.

### Domain:
Entertainment

### Data Dictionary:

#### Movies.dat:

Field	| Description
--- | --- 
MovieID	| Unique identification for each movie
Title	| A title for each movie
Genres | Category of each movie

#### Ratings.dat:
Field	| Description
--- | ---
UserID | Unique identification for each user
MovieID	| Unique identification for each movie
Rating	| User rating for each movie
Timestamp	| Timestamp generated while adding user review

#### Users.dat
Field	| Description
--- | ---
UserID | Unique identification for each user
Genere | Category of each movie
Age | User’s age
Occupation | User’s Occupation
Zip-code | Zip Code for the user’s location

Age is chosen from the following ranges:
Value	| Description
--- | ---
1|"Under 18"
18|"18-24"
25|"25-34"
35|"35-44"
45|"45-49"
50|"50-55"
56|"56+"

Occupation is chosen from the following choices:
Value	| Description
--- | ---
0|"other" or not specified
1|"academic/educator"
2|"artist”
3|"clerical/admin"
4|"college/grad student"
5|"customer service"
6|"doctor/health care"
7|"executive/managerial"
8|"farmer"
9|"homemaker"
10|"K-12 student"
11|"lawyer"
12|"programmer"
13|"retired"
14|"sales/marketing"
15|"scientist"
16|"self-employed"
17|"technician/engineer"
18|"tradesman/craftsman"
19|"unemployed"
20|"writer”

### Steps performed:
1. EDA, statistical analysis, correlation and hypothesis tests performed
2. Finding out the features affecting the ratings of movies
3. Finding out which type of movies are popular within which category of people
4. Building a model using Logistic regression, Decision Tree, Random Forest and XGBoost classifiers to predict the ratings of movies
5. Evaluation using different metrics
