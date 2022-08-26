

<h1 align="center"> Netflix Movies and TV-Shows Clustering </h1>
<h3 align="center"> AlmaBetter Project - <a href="https://www.almabetter.com/"> AlmaBetter </a> </h5>

In this project, I have clustered the movies and TV shows based on the film's description, genres, cast, directors, etc. by using the various ML clustering models.
<h2> 📁: Project Files Contain</h2>

<p>    Colab notebook
<p>    Technical documentation 
<p>    Presentation</p>

<p>

<h4>Data Source:
<li><b>https://drive.google.com/file/d/1pClhjteQzq5C4vI37F8iz9vFNRAhsDhs/view?usp=sharing.</li>
<ul>


<h2> Introduction</h2>
Netflix, Inc. is an American subscription streaming service and production company based in Los Gatos, California. Founded on August 29, 1997, Netflix had 220.7 million subscribers worldwide, including 73.3 million in the United States and Canada, 73.0 million in Europe, the Middle East and Africa, 39.6 million in Latin America and 34.8 million in the Asia-Pacific region. Netflix is a subscription-based streaming service that allows our members to watch TV shows and movies without commercials on an internet-connected device. You can also download TV shows and movies to your iOS, Android, or Windows 10 device and watch without an internet connection.

<h2> Problem Statement</h2>
Netflix content varies by region and may change over time. You can watch from a wide variety of award-winning Netflix Originals, TV shows, movies, documentaries, and more. The more you watch, the better Netflix gets at recommending TV shows and movies we think you’ll enjoy.
 
  
<p>we know that, Users of the such a platform have experienced it ourselves that endless scrolling of selecting the show what to watch and users spend more time deciding what to watch than watching their movie.

<p>The goal of this project is to cluster the movies or TV shows on the netflix and build a movie recommendation system for users. Initially we are going to analyze a available data from the Netflix to get the insights to know statisticas of the data by diffrent featurewise. 
<h2> Data Summery</h2>
This dataset consists of tv shows and movies available on Netflix as of 2019. The dataset is collected from Flixable which is a third-party Netflix search engine.

<p>In 2018, they released an interesting report which shows that the number of TV shows on Netflix has nearly tripled since 2010. The streaming service’s number of movies has decreased by more than 2,000 titles since 2010, while its number of TV shows has nearly tripled. It will be interesting to explore what all other insights can be obtained from the same dataset.

<p>Attribute Information

* show_id : Unique ID for every Movie / Tv Show
* type : Identifier - A Movie or TV Show
* title : Title of the Movie / Tv Show 
* director : Director of the Movie
* cast : Actors involved in the movie / show
* country : Country where the movie / show was produced
* date_added : Date it was added on Netflix
* release_year : Actual Release Year of the movie / show
* rating : TV Rating of the movie / show
* duration : Total Duration - in minutes or number of seasons
* listed_in : Genere
* description: The Summary description


# Steps involved:
This project is implemented in Python with its different libraries being used, as well as various clustering models. The description of the general approach is as below:

* Data Overview:
<p>First I take the count of any null value present and then I understand the statistical description of the dataset. I also get to know the unique values in the different features. 
  
* Data cleaning and pre-processing: 
<p>We know that a machine can understand only numerical values and we have to cluster the data on the basis of description and genres, which are in the string format, so we have converted them into the numerical format.
  
* Exploratory Data Analysis:
<p>In this I got different insights into the dataset and its correlation with the other features, also its distribution. From this analysis, important features for the clustering are decided.
  
* Clustering:
<p>In this project, I have clustered the film data based on the description, type, i.e., genres of the film data and other given data, which are the categorical features (type, release_year, director, cast, country, duration, rating) because most of the audience choose the film based on the description and type (genres) of the movie or either the cast of the film or the availability of the time. So we have grouped them into two parts to cluster the data for a better recommendation. For clustering, I have used five models and their respective performance scores are also taken.

# Dash Web App:
In this recommendation system we have used a Natural Language Processing (NLP) model and a K-Means Clustering model to make these recommendations. These models grouped the given data on the text based i.e description and genres. 
I have created a Dash web app that utlizes used model in colab to recommendations the films based on a user's preferences .

![image](https://github.com/Mr-Premanand/Netflix-Movies-And-TV-Shows-Clustering/blob/fa530ae713cd876c7c9d5d5bb17a9d0cad141e7b/image.png)



[![LinkedIn Badge](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/premanand-gaikwad-6444a2156)
[![GitHub Badge](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Mr-Premanand)

