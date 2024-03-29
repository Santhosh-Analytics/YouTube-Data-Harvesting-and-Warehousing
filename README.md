<div align="center">
    <img alt="Static Badge" src="https://img.shields.io/badge/You_Tube_Data-Harvesting_Warehousing-blue?style=for-the-badge&labelColor=green&logo=Python&logoColor=%233776AB">

</div>

# <div align="center">YouTube Data Harvesting and Warehousing</div>

This project focuses on harvesting data from YouTube and storing it in a data warehouse. It utilizes tools like SQL, MongoDB, and Streamlit for creating an interactive platform to view and manage the harvested YouTube data.

## Table of Contents

- [Introduction](#introduction)
- [Problem Statement](#problem-statement)
- [Features](#features)
- [Setup](#setup)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [References](#references)
- [Demo video](#demo-video-link)
- [Conclusion](#conclusion)

## Introduction

In this project, we harvest data from YouTube using the YouTube API. The harvested data includes channel, playlist information, video details, and related statistics. This data is then stored and managed using SQL databases and MongoDB. Streamlit is used to create a user-friendly interface for interacting with the data.

## Problem Statement

The problem statement is to create a Streamlit application that allows users to access and analyze data from multiple YouTube channels. The application should have the following features:
  1. Ability to input a YouTube channel ID and retrieve all the relevant data (Channel name, subscribers, total video count, playlist ID, video ID, likes, dislikes, comments of each video) using Google API.
  2. Option to store the data in a MongoDB database as a data lake.
  3. Ability to collect data for up to 10 different YouTube channels and store them in the data lake by clicking a button.
  4. Option to select a channel name and migrate its data from the data lake to a SQL database as tables.
  5. Ability to search and retrieve data from the SQL database using different search options, including joining tables to get channel details.


## Features

- YouTube Data Harvesting: Utilizes the YouTube Data API to extract channel details, playlists, and videos.
- Storage with MongoDB & MySQL Databases: Illustrates how to store YouTube data in a  MongoDB & My SQL database for added flexibility.
- Present the data in an interactive and user-friendly way using Streamlit.
- Querying data using MySQL with the predefined questions

## Setup

### Prerequisites

- Python 3.11.0 or higher.
- Jupyter notebook.
- MySQL.
- MongoDB.
- Youtube API key.
- Necessary Python packages (specified in [`requirements.txt`](https://github.com/Santhosh-Analytics/Capstone/blob/main/requirements.txt))

### Installation

To run the YouTube Data Harvesting and Warehousing project, follow these steps:

1. Install Python 3.11.0 or higher: Install the Python programming language on your machine.
2. Install Required Libraries: Install the necessary Python libraries using pip or conda package manager. Required libraries (specified in [`requirements.txt`](https://github.com/Santhosh-Analytics/Capstone/blob/main/requirements.txt)).
3. Set Up Google API: Set up a Google API project and obtain the necessary API credentials for accessing the YouTube API. Click [here](https://developers.google.com/youtube/v3/getting-started) for more guides & references.
4. Configure Database: Set up a MongoDB database and SQL database (MySQL).
5. Configure Application: Update the configuration file or environment variables with the necessary API credentials and database connection details.
6. Run the Application: Launch the Streamlit application using the command-line interface. Clone this repository in your local machine. Open terminal /cmd and navigate to the directory and run this command 'streamlit run Main_mod.py'.

## Usage

Once the project is setup and running, users can access the Streamlit application through a web browser. The application will provide a user interface where users can perform the following actions:
<h7 style='text-align: left; color: black;'><ol> <li> Please make sure to adjust the module names to match the actual names of the uploaded modules.</li> <li > To access and analyze data from multiple YouTube channels. </li> <li> To retrive YouTube channel details by using the YouTube channel ID (Channel name, subscribers, total video count, playlist ID, video ID, likes, dislikes, comments of each video)  </li> <li >To store the data in a MongoDB database as a data lake. </li><li >To collect data for up to 10 different YouTube channels and store them in the data lake by clicking a button. </li><li >To select a channel name and migrate its data from the data lake to a SQL database as tables.</li><li >To search and retrieve data from the SQL database using different search options, including joining tables to get channel details.</li></ol><h7>

## Contributing 

We welcome contributions to improve this project. Feel free to open issues and pull requests.

## References

- Streamlit Documentation: https://docs.streamlit.io/
- YouTube API Documentation: https://developers.google.com/youtube
- MongoDB Documentation: https://docs.mongodb.com/
- SQLAlchemy Documentation: https://docs.sqlalchemy.org/
- Python Documentation: https://docs.python.org/
- Matplotlib Documentation: https://matplotlib.org/

## Demo video link

- [Demo video link]([https://github.com/Santhosh-Analytics/YouTube-Data-Harvesting-and-Warehousing](https://clipchamp.com/watch/K925TFFfYAS))


## Conclusion

This project successfully demonstrates the seamless integration of YouTube data harvesting, storage, and visualization. Through efficient use of APIs, databases, and interactive interfaces, we've showcased how to enrich and manage YouTube data for various analytical and informational purposes. 


