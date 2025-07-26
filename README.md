# SOC-Movie-Recommendation
This project involves the construction of a movie recommendation system using python and its libraries. It involves the usage of many concepts such as cosine similarity and count vectorization.

NOTE: The files containing the data are too large and cannot be uploaded on github. Find all the files in this drive folder:
https://drive.google.com/drive/folders/1zuECIokCZ2xfniUWxDinjdmJQaGOgF6r?usp=sharing

## Week 1:
The code sorts the given data of movies, which contains the movie and different information related to it, based on genre and creates a bar graph.

## Week 2:
In this week, I merged three different datasets which contained different information about the movies into one data set. The merging was done so that only the movies present in the fourth file ('links.csv') were present in the master dataset.

## Week 3:
In this week, I refined the dataset by parsing different information of the mvoies and converting them to list from string datatype. 
Other tasks that I did were : getting the director's name(if present) from the crew, keeping only the top 3 cast members in the category cast, converting the keywords column into list (from string), handled multiple directors, handled keywords by stacking them and keeping them when there is atleast one keyword, stemmed each keyword to its root by using a stemmer object, joining all the columns into one single column 'soup' (helpful to check similarity).

## Week 4:
In this week, I refined the new dataset obtained by removing unwanted columns, checking popularity and director column for being their respective datatypes, sorting the dataset based on popularity and then dropping the column, checking the datatype of column release-date.

## Week 5:
In the final week, I finally culminated the project by first creating and using a CountVectorizer object which analyzed the column 'soup' formed earlier and created a count matrix. I then used the count matrix to calculate the cosine similarity and then using this cosine similarity, I made a function which found out the movies most similar to the given movie and returned their names along with their main-director and release dates.
