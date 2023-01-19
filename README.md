# ozell-web-scraping-app
### This web Application scrapes the PAO site and gets details of the given parcel number.

## To install in your local machine
* ### Open your Terminal.
* ### Navigate to a drive where you want to clone your repository.
* ### Create a directory.
### Run the below command after navigating to the created directory.
```
git clone git@github.com:fun-book/ozell-web-scraping-app.git
```
### After cloning, open the folder in VS code.
* ### Create a virtual Environment
## For Linux
### If pip is not in your system
```
sudo apt-get install python-pip
```
### Then install virtualenv
```
$ pip install virtualenv
```
### To Create a virtual environment,
```
$ virtualenv <your_virtualenv_name>
```
> ### After this command, a folder named <your_virtualenv_name> will be created. You can name anything to it. 

### To activate the virtual environment,
```
$ source <your_virtualenv_name>/bin/activate
```
### To Deactivate,
```
$ deactivate
```
## For Windows
### To Install virtualenv,
```
> pip install virtualenv
```
### Now in which ever directory you are, this line below will create a virtualenv there,
```
> virtualenv <your_virtualenv_name>
```
> ### After this command, a folder named <your_virtualenv_name> will be created. You can name anything to it. 

### To activate the virtual environment,
```
> <your_virtualenv_name>\Scripts\activate
```
### To deactivate,
```
$ deactivate 
```
### After activating the environment install the requirements using below command,
```
> pip install -r requirements.txt
```
## To run the app,
``` 
> flask run 
```
### Then click on the link to open the app in browser

### To run the Flask in debug mode
* ### create a file named ``` .flaskenv ``` and include the lines below,
```
FLASK_APP=app
FLASK_ENV=development
FLASK_DEBUG=True
```






