# Movie API

#### -- Project Status: Active

## Introduction

APIs make a great deal in the datascience industries today, and being able to render machine learning models as a microservice through RESTFUL APIs id no doubt an invaluable skillset to have!

### Objectivie

Build a RESTFUL API that serves my NLP model and recommendation engine as a microservice to my website

### Methods Used

* Object oriented programming
* RESTFUL API
* Get and Post methods
* Postman
* Unit test

### Technologies

* Python
* Flask
* Pandas
* Numpy

### Description

This project is a full implementation of a flask REST that accepts the movie title of a movie and returns in JSON movie properties of the searched movie such as the released date, the cast, comments about the movie etc. All of this metadata will be pulled through an api call to the TMDB API with the comments beign scrapped from the TMDB website and passed into the nlp model which classifies it as either 'Good' or 'Bad' review

### Geting Started

1. Clone this repository
2. Open the folder in a code editor of your choice
3. Create a python virtual environment
4. Install the requirements.txt file

### Folder Description

* Install the requirements.txt file
* conf: contains the bash script to install to setup the project if you are using mac, linux or windows-wsl
* data: contains the movie data used in this project
* notebooks: contains the notebooks used to run experiments
* references: contains the data dictionary to know what each colum represents and a link to a blog article to read more about cosine similarity and contained based filetering
* src: contains the script use to run this project in production environment and the Flask app
