# HelpOther web app 
Developed 3 tier web application using MEAN Technologies where a volunteer can choose volunteering work of your interest and also create/post new volunteering work for others. Social login is also supported. Implemented state mechanism for managing a task status.  
On New available task volunteers of the interested category would be notify using sendgrid mail API. Also used WebSocket library Socket.io to notify users, who are engaged with the task, on status change. Gamification is implemented by allowing users to share the earned badge, which is given on successfully performing a task, on the Facebook.

## Requirements

This application requires installation of NodeJS.

## Installation

- Install all dependencies in package.json file. This can be done by navigating to the root directory in the command prompt/terminal/console (I will refer to it as command prompt) and running the following command:

```
$ npm install
```
##  Using Docker 

##### It will pull the image from Docker hub .
```
$ docker run -p 8080:8080 --name myapp -d akhilesh1312/helpother
```

