# Pymongo_hetio_project
# Author: Nelson Lim
# CSCI 493.71
Supposed that a drug can treat a disease if the drug or its resembled drugs up-regulate/down-regulate a gene, but the location down-regulates/up-regulates the gene in an opposite direction where the disease occurs. Find all drugs that can treat a newdisease id (i.e. the missing edges between drug and disease excluding existing drugs). Obtain and output all drugs. 

TO ACCESS FILES: un-zip the attached files and there should be 2 files(.tsv)
In this project I converted the .tsv files into .csv

TO RUN:
I am using Anaconda 3 to run my python code and MongoAtlas' server to store my data
To be able to access MongoAtlas, you must whitelist current IP and and add yourself as a user to be able to access the documents
To import code to Mongo Atlas, I use the following commands on Window's PowerShell (where the command mongoimport is installed)
To Run code use command : python project_mongodb.py

