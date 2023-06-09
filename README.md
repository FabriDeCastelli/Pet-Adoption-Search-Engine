# Pet Adoption
Information Retrieval Project, USI Fall Semester

## Project Instructions:

You need to build a system that gathers a large collection of samples associated
with the topic and enable the search over this collection. To build the collections, you need
to crawl multiple sources (websites), similar in content and topic to the website suggested.
The system must provide an interface for searching, browsing, and presentation of the data
to the user.
The system should also have two additional features. Additional features are described in
the document on iCorsi and categorized into two groups: complex and simple features. You
can choose which features you want to implement yourself, provided there is at least one
feature from each of the groups (two in total). 

## How to run the application
It is required to have installed flask (in a python environment is also fine)

* Start solr server;
* Open the terminal on the directory where app.py is located;
* Activate the environment;
* Type **set FLASK_APP=app**;
* Type **set FLASK_ENV=development**, to enable debugging (not mandatory);
* Run the program by typing **flask run**;
* Open suggested url and use the app.
