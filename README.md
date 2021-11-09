# Street-View-Classifier
Using Google StreetView API, this uses deep learning to predict where an image from a random spot in a city was taken

This project is modeled after playing the game GeoGuessr, in which the player is
shown a Google StreetView image from a random spot in the world and their objective
is to guess where they are

It works by first downloading an updated list of the largest cities within the 
US, and then will query the Google Maps StreetView API to download images from 
random spots in the largest n cities. Using a pretrained deep learning image classification model, it learns what relevant features distinguish the cities.
 
After being shown an image of a random spot in a city it tries to classify from which city the photo was taken
