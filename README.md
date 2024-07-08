# fandango_movies_ratings
Questioning Fandango's Movie Ratings Reliability with Pandas!

## Table of Contents
- General Information
- Setup
- Usage
- Project Results
- Future Data Exploration Ideas
- Acknowledgements
- Contact

## General Information
I’m uploading the code of the data I explored from Fandango's movie ratings, to check if they are reliable!🎥

The goal was to test the reliability of Fandango's movie rating system after, Walt Hickey, a data journalist, has found some discrepancies in the ratings. I extracted data of movies ratings before and after the article was published, and then analysed their differences. I also want to support other coders who are movies lovers just like me and want to learn how to analyse their data in Pandas!📈

I used two datasets: the [movie ratings](https://github.com/fivethirtyeight/data/blob/master/fandango/fandango_scrape.csv) that Hickey used for his analysis, and the [ones](https://github.com/mircealex/Movie_ratings_2016_17) made available after Hickey's article. I explored the data and checked if the sample was representative. I then plotted and compared the distributions of change between the data before and after the article was published. 

## Setup
First off, make sure you have conda🐍👀:

`conda create -n <replace-with-name-you-want> python=3.11`

`conda activate <replace-with-name-you-want>`

`pip install -r requirements.txt`

## Usage
Check out the `fandango.ipynb` file in my repo to see how I've extracted, cleansed, explored, analysed, and plotted the data! 

## Project Results
The conclusion we reached so far is that there's indeed a slight difference between Fandango's ratings for popular movies in 2015 and Fandango's ratings for popular movies in 2016. We also determined that, on average, popular movies released in 2016 were rated lower on Fandango than popular movies released in 2015. It might be that this change was caused by Fandango's representatives fixing the biased rating system following Hickey's analysis. However, we have no tangible proof of this hypothesis since the rating values are not displayed anymore in Fandango's pages' HTML.

## Future Data Exploration Ideas
The next step could be to use the two samples to compare ratings of different movie ratings aggregators. This can help us recommend what's the most reliable website that users can use to check valid movie rating!

## Contact
For any question, drop me a line at giorgiadt14@gmail.com and I'll be happy to help you out! Feel free to message me on LinkedIn too! Happy coding!💻