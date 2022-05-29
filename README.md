# MUSIC-RECOMMENDATION-SYSTEM
![download](https://user-images.githubusercontent.com/106464481/170862900-f94ea208-243a-468a-809f-8345ab460295.jpg)
Listening to their favourite songs is one thing everyone likes .But How cool it could be  when the system itself recommends you the songs you prefer!!.
Music Recommendation System works exactly on the same thing.

This music recommendation System uses Content based filtering and K-means algorithnm to do so

## PROCEDURE 
1.  Installing Dependencies
2.  Datasets
3.  Analysing data
4.  Visualising data
5.  Using K-means to cluster
6.  Build recommendation system using spotify API.

## Installing Dependencies:
![image](https://user-images.githubusercontent.com/106464481/170863142-9e3088a7-e388-434c-8f64-9e07e3bde569.png)
As shown in the code part , we will import pandas,numpy,seaborn,plotly libraries which are required for execution of the project.

## Importing and Analysing Data:
The dataset obtained is from kaggle 
dataset url:https://www.kaggle.com/code/vatsalmavani/music-recommendation-system-using-spotify-dataset/data
### Importing the datasets:
![image](https://user-images.githubusercontent.com/106464481/170868351-7cf9616c-a173-4dab-92c4-32d3d64c08e3.png)

## Data Understanding by Visualization and EDA:
![image](https://user-images.githubusercontent.com/106464481/170879482-8fe0d99d-6b63-48ec-8b29-c169429621f7.png)


Our data set contains the audio songs  from various decades and they are classified accordingly with the following code .
![image](https://user-images.githubusercontent.com/106464481/170879607-218d1456-aaf3-4fe6-b6e4-7cff4bc5a69a.png)

Our dataset contains the audio features for different songs along with the audio features for different genres. We can use this information to compare different genres and understand their unique differences in sound.
![image](https://user-images.githubusercontent.com/106464481/170879631-cf5e17bc-a1d7-4b1a-9c38-b969e536d31b.png)

## Grouping data using K-means:
### Grouping genres:
![image](https://user-images.githubusercontent.com/106464481/170879687-49c7c4e3-c692-4e5c-9dda-a3a2127e96d1.png)
### Grouping songs:
![image](https://user-images.githubusercontent.com/106464481/170879712-384ca901-37fb-4fcc-a1c0-ebf1e5b84860.png)

## Connecting with SPOTIFY API:
- First we need to install the spotipy 
- Next we need to create our developer account in the dashboard and create an app https://developer.spotify.com/dashboard/
![image](https://user-images.githubusercontent.com/106464481/170879859-1863e175-6ca6-4865-bfbd-69d77537fcd9.png)
- We will be getting a Client Id and secret key which we will be using in the above code part 
- Lastly, we need to create Functions to recommend the songs in the below way.
![image](https://user-images.githubusercontent.com/106464481/170879942-bffb3ed9-f572-4926-a6fd-6c81c61cb00e.png)
![image](https://user-images.githubusercontent.com/106464481/170879974-43b73428-ae1f-4ca9-b80b-2a36fdcdc4f4.png)
OUR API is ready to use ,if needed wwe may request for an extesion file also in the SPOTIFY dashboard.



