# Predicting diamond prices with machine learning-kaggle competition

![Ironhack logo](https://www.fundacionuniversia.net/wp-content/uploads/2017/09/ironhack_logo.jpg)

This project is developed at the scope of Ironhack's Data Analytics Full-time Bootcamp.



## Resume
![Ranking ](src/ranking.jpg)

The aim of this project is to predict as best as possible the price of a dataset. 
The competition is released at https://www.kaggle.com/c/diamonds-datamad0820/overview though it is just a private one.



https://www.kaggle.com/c/diamonds-datamad0820/overview



## Structure

1) README.txt: As a resume for the content of the project an its development

2) data_to_json.py: This file imports the information needed from Github API and exports it to a locally saved bash file

3) server.py:  It defines the local server where the self-done API will be executed.

4) src: It contains relevant files so that the script can be runned. These are .py files:
    4a) data_exportation.py-> It contains every function that the data_to_bash needs so as to clean and fix up the requested data from Github API.
    4b) data_toMongo.py-> This script generates two new collections in MongoDB (students and labs) from the bash file exported in the file above
    4c) database.py-> It defines the new database in MongoDB that will be created and used to export the previously commented collections
    4d) api_gen.py-> It defines the endpoints of the self-created API

