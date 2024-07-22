# data-sourcing-challenge
#### Danielle Dejean 
AI Bootcamp - Module Challenge #5,
21 July 2024
## Overview
This code extracts data from two different sources - The New York Times API and The Movie Database API -  merges the data together, then prepares it for future use with natural language processing methods, outputting a .csv file.

## Python Functionality Implemented
* Jupyter Lab
* Installs and library imports: python-dotenv, requests, time, load_dotenv from dotenv, os, pandas and json
* Functions: os.getenv, requests.get, time.sleep, append, json.dumps, pd.json_normalize, apply(lambda), def, astype, pd.DataFrame, to_list, pd.merge, str.replace, drop, drop_duplicates, reset_index, to_csv
* Other code: buidling url queries, loops and list comprehension, slicing json strings, sleep counters, removing characters from a string


## Set Up
* To call the APIs, you will need to have an API key issued from [The New York Times](https://developer.nytimes.com) and [The Movie Database](https://www.themoviedb.org). To get the key, you'll need to create an account, and then create an app. Those keys will need to be saved in a .env file within the folder. An example .env file has been provided; however, the keys will need to be entered and the file will need to be saved as ".env" (without "example"). Do not share your API keys.
* The files wihtin the retrieve_movie_data repo were updated using Python version 3.10.14, in Jupyter Lab. To run it, please download the most recent version of [Python](https://www.python.org/downloads/), as well as a code editor that runs Python ([Visual Studio Code](https://code.visualstudio.com/download), [PyCharm](https://www.jetbrains.com/pycharm/download/?section=mac), etc.).
* Copy the file link from GitHub (Click the Code dropdown button and copy the HTTPS URL to clipboard)
* Clone the file from GitHub into the desired folder on your computer (type: "git clone <link to file>" and press enter)
## Run Instructions:
In Terminal (Mac) or GitBash (Windows):
* Ensure that you're running the correct version of Python (see Set Up above)
* Ensure that you're in the directory containing the file before running
* In Jupyter Lab, open "retrieve_movie_data.ipynb" and click "Run All"
* The program will output the .csv file.  
## References
* The retrieve_movie_data.ipynb starter files wer downloaded from the AI-PT-WEST-MAY-052824_MTTH Module 6 Challenge files and edited to analyze the data.
* Data provided by [The New York Times](https://developer.nytimes.com) and [The Movie Database](https://www.themoviedb.org).
![Banner Image](poweredby_nytimes_200a.png)     ![Banner Image](TMDB_logo.png)
