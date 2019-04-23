
# log_analysis_udacity
# M.Sai Teja
A Reporting page that prints out reports in a plain text format based on the data in the database.This reporting tool is a python program using the psycopg2 module to connect to the database

# Project Content
This project consists of the following files:
log_analysis_udacity.py - main file to run this Logs Analysis Reporting tool
README.md - install this reporting tool by step-by-step
newsdata.sql - database file
output.txt - executed Project output file

# Requirements
Python ---->(Programming Language)
Vagrant ---->(A Virtual Environment)
VirtualBox ---->(An Open Source Virtualization Product)
Installation Process
There are some dependencies and few instructions on how to run the application.

# Dependencies
Vagrant --->[https://www.vagrantup.com/]
Udacity Vagrantfile --->[https://github.com/udacity/fullstack-nanodegree-vm]
VirtualBox --->[https://www.virtualbox.org/wiki/Downloads]
How to Run Project
Step1--> Launch the Vagrant VM inside Vagrant sub-directory in the downloaded fullstack-nanodegree-vm repository using command:

 $ vagrant up

Step2 --> Then Login by using this command:

 $ vagrant ssh

Step3 --> Change Directory to vagrant --> $cd /vagrant

Step4 --> Change Directory to project folder --> $cd logsanlysis

Step5 --> Download database from [this link](https://d17h27t6h515a5.cloudfront.net/topher/2016/August/57b5f748_newsdata/newsdata.zip)

Step6 --> Unzip this(newsdata.zip) file after downloading. The file inside is called newsdata.sql.

Step7 --> Copy the newsdata.sql file and place inside logsanalysis folder.

Step8 --> Load the data in local database using this command:

  $ psql -d news -f newsdata.sql
Step9 --> Run python file by using below command:

Step-10--> Connect news data to database --> $psql -d news

  $ python log_analysis_udacity.py

Note: queries will take sometime to execute
