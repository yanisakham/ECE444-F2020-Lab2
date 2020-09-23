# ECE444-F2020-Lab2
### This repository is for completing ECE444 Lab2
### This repository is a clone of https://github.com/miguelgrinberg/flasky

#
## Activity 1: 
#### Installation of flask in virtual environment
![activity1](https://user-images.githubusercontent.com/43483228/94021810-6dec4d00-fd82-11ea-8c2a-9ae36788df64.JPG)

#
## Activity 2: 
#### Setting up a simple web app repo with a route to print "Hello, <user_name>!" (as per activity 2-1, 2-2)
![activity2](https://user-images.githubusercontent.com/43483228/94021812-6e84e380-fd82-11ea-956c-f1b76f6f730b.JPG)

## Activity 3: 
####  Briefly summarize the Flask context globals

Contexts are used to provide view functions with globally accessible objects that might be useful in the function. There are 4 context globals: <br/>
1 - request: this context stores information about the client's HTTP request, including headers, path, arguments, etc. 
<br/>
2 - session: this context stores session information, including values that persist between requests. This is in the form of a dictionary that stores key, value pairs that you may want to keep track of throughout different requests (like cookies). 
<br/>
3 - current_app: this context details the current active application instance that is handling the current request. This object can store app configurations like SECRET_KEY or to differentiate between testing/deployed app instances. 
<br/>
4 - g: this is a namespace object used to temporarily store resources/data when handling a request. This object is cleared after the request is processed.   
