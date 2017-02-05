# linux-server-config
### IP Adress: 52.25.248.125
### URL: http://ec2-52-25-248-125.us-west-2.compute.amazonaws.com/
### Software installed: apache2, postgres, git, Flask, sqlalchemy, mod_wsgi, items app
### Configurations made: 
1. Configured ufw to allow only ports needed for the app, 
1. remote connection and secure web connection, 
1. configured mod_wsgi to enable python app 'items' to run as an apache served web app, 
1. made changes to the google and facebook urls and configuration files, 
1. updated the json files to also point to the new urls,
1. updated code to support postgres and for absolute paths for json files,
1. created account grader with sudo access, 
1. disabled remote login with password and for root, 
1. created db items and created user catalog with limited access, 
1. set the timezone to utc, 
1. added authorized keys for grader user, 
1. upgraded get-apt apps and installed apps as needed.
1. validation based on provided rubric
