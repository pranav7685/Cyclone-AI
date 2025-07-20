# Cyclone-AI
A Web-App User Interface where the user can upload INSAT-3D IR Satellite Image of Cyclone which is then passed to our Deep Convolutional Neural Network built in PyTorch which is trained on Cyclone imagery of various intensities on our custom dataset curated from Raw INSAT-3D satellite captured images on MOSDAC server.

The CNN eliminates the need for usage of traditional methods for accurate center determination to estimate the Cyclone intensity using Satellite imagery.

The Model will return the estimated Intensity of satellite cyclone image in KNOTS instantly, the user would also have the option to upload metadata values like Datetime, latitudinal position, etc. for the Cyclonic event which will be stored in the Database pushing it in a archive of all past cyclonic events that have been inputted in the interface. User can view the past cyclonic events in the database with event-related metadata in the archive and visualize the imagery. Flask will be used to integrate the web-application together in Python.
Tech Stack Used
Front-end: HTML , CSS, Bootstrap and JavaScript

Back-end: PostgreSQL, Flask, psycopg2 and Python

Machine-learning-pipeline: PyTorch
