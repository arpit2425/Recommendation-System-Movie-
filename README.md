# Movie-Recommendation-System

### Motivation for the project:

Learning about Recommendation system during the ND025 course, something pops up into my mind. How about recommending hollywood movies?

I am not so into hollywood movies but definately have watched famous movies. Sometime you like a particular movie and you want to see more of similar kind. But you don't know which are the movies similar to this one. Well, in that case recommending similar movies of your choice through an accessible web app would be a great idea. 

So, I am going to use cosine similarity recommendation approach to recommend similar hollywood movies based on your choice. I will be using flask to make app and Heroku p-a-a-s to deploy on web. This will be end to end project from data collection to deployment. I am really excited to go ahead.

[web app link](https://rajeevranjan-recommendingmovie.herokuapp.com/)

### Data set:

I used IMDB 5000 Movie Dataset which is collected from below link.
dataset :- https://www.kaggle.com/carolzhangdc/imdb-5000-movie-dataset


### Platform used:

1. Web framework: Flask
2. web: Heroku cloud
3. Language: Python, HTML, CSS, Java script


### Approach taken:

1. Train your model
2. Create web app
3. Commit the code into github repository and add configuration files required
4. Create account on Heroku
5. Link the github repo to Heroku
6. Deploy the model
7. Web app is ready

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

![Home page](https://github.com/RajeevRanjan2015/Recommendation-System-Movie-/blob/master/home%20page.PNG)
