# Project_music_library_backend
Week 6 Backend Dev Code Camp

Music Library - Backend 
Project

Tech Stack
Python, Git/GitHub, Flask, Postman
Starter Code Repository
https://github.com/dCC-Online/FlaskRestAPI_PY_Starter

User Stories
Total Unweighted Project Points: / 65
Total Weighted Project Points: / 5





Main Stories

(5 points): As a developer, I want to make good, consistent commits.   

(5 points): As a developer, I want to create an ERD for the Song Model, showing proper datatypes.   

(2.5 points): As a developer, I want to create a Song model with the following properties.

Property names must be in snake_case and match the following exactly!  
    id - Integer
    title - String  
    artist - String  
    album - String  
    release_date - Date  
    genre - String  

(5 points): As a developer, I want to create a SongSchema with a create_song() method so I can validate Posted songs.

(2.5 points): As a developer, I want my API to serve content on the following URLs paths:  
    Paths must match these exactly!  
    ‘api/songs'  
    ‘api/songs/<int:pk>’  
(15 points): As a developer, I want to build a REST web API in Flask, so that I can make HTTP requests interact with the data set.   

(5 points): As a developer, I want to create a GET endpoint that responds with a 200 success status code and all of the songs within the Song table.  

(5 points): As a developer, I want to create a GET by id endpoint that does the following:  
    Accepts a value from the request’s URL (The id of the song to retrieve).  
    Returns a 200 status code.  
    Responds with the song in the database that has the id that was sent through the URL.  

(5 points): As a developer, I want to create a POST endpoint that does the following:  
    Accepts a body object from the request in the form of a Song model.  
    Validates the body object.
    Adds the new song to the database.  
    Returns a 201 status code.  
    Responds with the newly created song object.  

(5 points): As a developer, I want to create a PUT endpoint that does the following:  
    Accepts a value from the request’s URL (The id of the song to be updated).  
    Accepts a body object from the request in the form of a Song model.  
    Finds the song in the Song table and updates that song with any properties that were sent in the request’s body.  
    Returns a 200 status code.  
    Responds with the newly updated song object.  

(5 points): As a developer, I want to create a DELETE endpoint that does the following:  
    Accepts a value from the request’s URL.  
    Deletes the object from the database.
    Returns a 204 (NO CONTENT) status code.  

(5 points): As a developer, I want to use Postman to make a POST, PUT, DELETE, and both GET requests (get by id and get all) request to my REST web API, save it to 
    a collection, and then export it as a JSON file from Postman.  Include this file in your repo! 
 
Bonus Stories
(5 points): As a developer, I want to add the ability to “like” a song through the web API and have the number of likes saved in the database with the song. 
