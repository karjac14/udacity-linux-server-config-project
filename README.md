# udacity-linux-server-config-project
a project for a Udacity Full Stack Web Developement Nanodegree 


## Intro

This is a demonstration of deploying simple Flask-based web application on AWS Lightsail - Unubtu OS.  
  

## Configurations

The following configuations are needed for the grader:

IP: 18.216.180.137  
SSH port: 2200  
URL: http://www.18.216.180.137.xip.io/  
Grader user passwrod: 12345

## Summary of Installed Software

#### Through Advanced Package Tool (apt-get)
`apache2`  
`libapache2-mod-wsgi` - This is an Apache module that provides a WSGI (Web Server Gateway Interface, a standard interface between web server software and web applications written in Python) compliant interface for hosting Python based web applications within Apache. 
`git`  
`python-pip`  
`python-dev`  
`postgresql`  

#### Through Python Pip

`virtualenv` - One major new thing I did here, that I recently learned, is setting up a virtual environment that keeps the python application and its dependencies isolated from the main system. It keeps the dependencies easy to maintain and located. A `pip` package called `virtualenv` has been installed. 

`sqlalchemy`  
`psycopg2`  
`oauth2client`  
`requests`  
`httplib2`  

## Resources

[How To Deploy a Flask Application on an Ubuntu VPS](https://www.digitalocean.com/community/tutorials/how-to-deploy-a-flask-application-on-an-ubuntu-vps)  
[Udacity Knowledge Forums](https://knowledge.udacity.com/)
