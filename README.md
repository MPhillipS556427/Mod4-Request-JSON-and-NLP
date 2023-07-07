# Lyrics Sentiment Analysis

This repository contains code that allows you to retrieve song lyrics from the lyrics.ovh public API, store them in files, and perform sentiment analysis on the lyrics using spaCyTextBlob. The resulting polarity scores indicate the positive or negative connotation of the lyrics.

## Introduction

The purpose of this project is to provide a convenient way to access song lyrics and analyze their sentiment. It utilizes the LyricsGenius: a Python client for the Genius.com API public API to retrieve lyrics for a given artist and song, stores the lyrics in JSON files, and performs sentiment analysis using spaCyTextBlob. The sentiment analysis provides a polarity score that indicates the overall positive or negative connotation of the lyrics.

## Usage
To use this project, follow the instructions below:

Clone the repository to your local machine.
Install the required dependencies by running pip install -r requirements.txt.
Intsall lyricsgenius from the https://pypi.org/project/lyricsgenius/ site into the machine.
Run the provided code snippets in your preferred Python environment.

## Function Descriptions

### 'get_song_lyrics(artist, song, filename)' 

This function takes an artist, song, and filename as parameters. It accesses the lyrics.ovh API to retrieve the lyrics for the specified song and artist. The lyrics are then stored in the specified filename.

### 'analyze_lyrics(filename)'

This function takes the name of a file that contains song lyrics and performs sentiment analysis on the lyrics. It loads the lyrics from the file, uses spaCyTextBlob to analyze the sentiment, and returns the polarity score.

## Examples

Questions 1 to 4 will provide the following 3 examples:

1. Retrieving Lyrics and Performing Sentiment Analysis
2. Retrieving Lyrics for Multiple Songs
3. Sentiment Analysis on Multiple Song Lyrics

## Contact

If you have any questions, feedback, or inquiries regarding this project, please contact Malcolm Phillip at S556427@nwmissouri.edu.

Enjoy exploring the code and visualizations in this repository!
