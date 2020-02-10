# Movie-Recommendation-System

### Description:
This is a hollywood movie recommender system built with Python. I used IMDB 5000 Movie Dataset to built this. This is basically a POC project which is developed end to end from data collection to deployment.

### Data set:

dataset :- https://www.kaggle.com/carolzhangdc/imdb-5000-movie-dataset


### Platform used:

I used Flask web API framework to put the application on the web using Heroku.

### Working web model:

https://rajeevranjan-recommendingmovie.herokuapp.com/

### Approach taken:

1. Data collection
2. Data preprocessing : can be found preprocessing.ipynb file.
3. Data modeling: Countvectorizer , Cosine similarity
4. Model deployment

This is content based reccomendation system which uses similarity score means bases on the user's liking recommending similar items to the users.

### How to use the project:

1. Download the repository.
2. open anaconda command prompt and go to the stored folder and run python app.py
3. After running app.py, the flask framework will get created on to your system locally and it will produce you a url by which you can access the application home page.

4. For deployment of the app on the web i.e., Heroku you need to connect you git by heroku. You can create new app there and store this repo there. All the further steps will be there which is very easy to tackle in order to deploy the model on web. This is user friendlt framework so anyone can easily follow each steps.
 
### About the files:

1. In the create.py file I created two files for future uses one data.csv and other a numpy matrix.
2. The application is run from the main.py file.
3. In the template folder, there are home.html page from which you will ask your query and the result will be directed on recommend.html page.
4. You need to have procfile where we initialize the app.
5. You need to import all the libraries which are necessary for running the application that needs to be installed in heroku. All the necessary libraries are kept in requirement.txt file.


### Result showing on web:

![Home page](link-to-image)
