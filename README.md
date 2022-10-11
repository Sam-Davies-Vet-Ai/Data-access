# Big Query access using a service account key


## Description
This script will allow create a connection in python to bigquery, list all datasets, tables and gives a snapshot of the first 5 rows of each table

This script needs to be used with a json file containing the details of the service account key, the data returned will be limited to the access granted to the service account key

This is an example script to access data, this can be used as a base to develop a script to 

## Usage

* Open the file you wish to run e.g BQ_Access.ipynb
* Select 'Open in Colab'
* This will create a new Colab instance
* Any changes you make will not be saved to github
* Select the folder icon on the left-hand side of the screen in Colab
* Drag and drop the json service account key into this area
* This uploads the file to the Colab sessions storage
* change the xxxxx.json to the name of the file uploaded inclusive of the .json
* Select 'Runtime' in the top menu bar and 'Run all'
* This will run the script and give you the desired formatted output


