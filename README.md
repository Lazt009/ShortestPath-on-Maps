# ShortestPath-on-Maps
This webpage find the shortest between two cities in India, using Dijkstra Algorithm, We have used custom data set and folium in python to display the shortest path.

## Contents - 
- **app.py** : It is the main file, that contains which function to call and page to render.
- **dijkstra.py** : It contains the function of dijkstra that finds the shortest path for a given source and destination.
- **dataRetriever.py** : It contain a utility function to reads the Distacnes.csv and arrange it it the form of graph so that it can be passed on to dijkstra.py .
- **Distances.csv** : This file has the geodesic distance from a city to every other city in the dataset, it is like a adjacency matrix(graph) for dijkstras function.
- **Lat_Long.csv** : This  file has the latitude and longitude data for every city in dataset.
- **templates** : This folder contains the html templates that are rendered on running app.py 
- **static**: This folder contains all the static styling elements like css, img, etc.

## Note -
If you are planning to run this code on your System then here are the Steps - 
1. Python(3.6 or higher).
2. These libraries installed in python.
  - Flask(type `pip install flask` ).
  - Folium( type `pip install folium` ).
  - Pandas( type `pip install pandas` ).
  - numpy( tpye `pip install numpy` ).
  - tkinterHTML (type `pip install tkinterhtml` ).
3. Download this repository.
4. Navigate to the folder where it is downloaded.
5. run app.py file(`python app.py`).
6. Open localhost on web browser [http://127.0.0.1:5000/](http://127.0.0.1:5000/).

# Requirements
1. We used html,css,bootstrap to build the frontend of our web app.
2. For the backend we used Flask Python.
3. For generating map we used folium library in Python.
4. For finding the latitudes, longitudes of cities we used geopy library in Python.

# Dataset for distances between cities and their corresponding latitudes,longitudes
We were having difficulties finding the dataset for cities to create the corresponding graph for the dijkstra's algorithm.
So we thought of creating our own dataset.
We have uploaded our dataset in kaggle.
This dataset can be used to build graph for shortest path algorithms.
We created a program which can give us the dataset of the number of cities we gave as input. This code is also uploaded in kaggle notebook.
The dataset given in this github file has data for 50 cities and it finds the shortest path between these 50 cities.
The link for kaggle is - https://www.kaggle.com/nikhillikhar01/cities-data-latitude-longitude-and-distances

# Algorithms we used
We used **dijkstra's shortest path** algorithm to find the shortest path between given cities.

# Creators
This project was completed by **Nikeshsingh Baghel**, **Mohit Shingane** and **Nikhil likhar** from computer science branch in **Shri Ramdeobaba college of engineering and management** under the guidance of **Dr. Manoj B. Chandak (Ph.D CSE)-
Head, department of Computer Science**.

