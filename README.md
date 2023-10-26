# Sentiment Analysis with Named Entity Recognition

## Overview

This project performs sentiment analysis with named entity recognition (NER) on threads extracted from the Investing subreddit using the OldReddit API. The goal is to gain insights into the sentiment of user comments and to identify named entities (such as company names, stock tickers, etc.) mentioned in those comments.

## Table of Contents

- [Project Description](#project-description)
- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Technologies Used](#technologies-used)

## Project Description

### Sentiment Analysis

The project uses a sentiment analysis model to determine whether user comments are positive or negative in sentiment. The sentiment is expressed as a score, and the analysis is performed on the comments extracted from the Investing subreddit threads.

### Named Entity Recognition (NER)

Named Entity Recognition is used to identify and extract named entities from the comments. This helps in identifying companies, stock tickers, and other entities of interest within the comments.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Python 3.7 or higher installed.
- Required Python libraries and packages. You can install them using `pip`:


## Getting Started

To get started with this project, follow these steps:

1. Clone the repository to your local machine:


2. Configure your Reddit API credentials:
- Create a Reddit API application and obtain your `CLIENT_ID` and `SECRET_TOKEN`. Update the configuration in the code accordingly.

3. Run the project:
- Execute the Python scripts to extract threads, perform sentiment analysis, and named entity recognition.

## Usage

- The project can be used to analyze user comments on the Investing subreddit for sentiment and named entities.
- Modify the code as needed to analyze other subreddits or gather different types of insights.

## Project Structure

The project structure is organized as follows:

- `Import Libraries and Load Model`
- `Getting Reddit Data`
- `Extracting organizations`
- `Sentiment Analysis`
- `Entities with Sentiment Scores`
- `Visualising`

## Technologies Used

- Python
- Reddit API
- Requests library
- Pandas
- Spacy for NER
- Flair for sentiment analysis
- Matplotlib for data visualization

## Contact:

Email: manavisrani07@gmail.com

