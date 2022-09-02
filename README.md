Welcome to Project TABZS. 
TABZS is a one stop solution to all the challenges a National Cafe Shop faces today as the it grows. We have carefully built an application that includes cutting edge technologies involving cloud solutions which will deliver valuable business insights when needed from the volumnous data generated everyday.

The extract-transform-load (ETL) pipeline has been setup to run on Amazon Web Service (AWS) using Continuous Integration Continuous Deployment (CICD) through GitHub. The Infrastructure as Code (IAC) setup uses .yaml and .yml files to implement the infrastructure in AWS via Amazon Cloud Formation.

The basic setup of the ETL pipeline itself is as follows:


To run a localised verion of the ETL pipeline (i.e. without AWS) undertake the following: 
- Clone this repository to your machine
- From the requirements file download the packages into your virtual environment
- Create a PostGresql Database using a Docker container
- Run the create_db.py script
- Run the app.py script 
