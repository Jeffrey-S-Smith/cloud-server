# cloud-server

## AWS: Cloud Servers

[GUI cloud-server](http://cloudserver-env.eba-4jnsw2j4.us-west-2.elasticbeanstalk.com/),

[Manually	cloud-server2](http://cloud-server2.eba-nxsvi5iy.us-west-2.elasticbeanstalk.com/),

## Feature Tasks

Deploy a simple Node.js server to EC2, using Elastic Beanstalk

* Choose a server you’ve built previously
* Option 1: A simple API or Web Server
* Option 2: A socket.io event Hub
* The server should not require a database
* Check in your server to GitHub

## Task 1

* Create a new environment, using Elastic Beanstalk from the AWS Control Panel (GUI)
* Manually deploy your application to this environment by uploading a .zip file

## Task 2

* Using the same server, create a new environment using Elastic Beanstalk from your terminal
* Manually deploy your application to this environment by using eb deploy

* ## Documentation

* In your README.md include:
  * The links to both of your deployed servers (GUI deploy and CLI deploy)
  * Document your processes

## Stretch Goal

* Automatically deploy your app to either (or both) environments on check-ins to your main branch using a github action
* HINT: Explore the GitHub marketplace