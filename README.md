# RESTAPI Demo

### Prerequisite: 
1. [Python 3.x](https://www.python.org/downloads/)
2. [Pip](https://pip.pypa.io/en/stable/installing/)

### How to run

1. Clone this project.
2. Run ```pip install requirements.txt```. Requirements file has all the necessary modules that needs to be installed on your machine to run the app.
3. Server folder has the backend api code. You can refer to ```products()``` method to see how ```localhost:5000/products``` url works.
4. This method checks the the type of request(GET, POST, DELETE) made with ```/products``` url and respond accordingly. Check comments in server code for more details.
3. To run the api server open a terminal/cmd and run command ```python backend.py```
4. Now go to ```http://localhost:5000``` to access the home page.
5. Play with the app to Add, Delete and Read products from mlab test DB. You don't have to do anything specific for the db setup.
7. You can input a non empty values for ```Product name``` and ```Product price``` input boxes. Click on ```Add``` it to the test mlab db.
8. Click on ```View all``` to check the recently added content into mlab db. Similary clicking on ```Delete all``` delete the contents.

*Note To generate requirements.txt I have used ```pipreqs``` module. You can run:* 
```1, pip install pipreqs
   2. pipreqs -r <absolute-path-to-project-backend-folder> 
```

