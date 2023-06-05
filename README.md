# IMDB Top Movies Scraper

This is a Python script that scrapes the top 250 rated movies on IMDB and saves the to a CSV file. The script uses the BeautifulSoup library to parse the HTML content of the IMDB top movies chart page and extract the movie titles, ratings, and years. It then writes the data to a CSV file named "imdb_movies.csv" and reads the file into a pandas DataFrame. Finally, it extracts the titles from the DataFrame and assigns them back to the 'title' column.
Requirements

    - Python 3.x
    - pandas
    - BeautifulSoup
    - requests
    - csv

## Usage
To use the script, simply run the imdb_top_movies_scraper.py file. The script will output the movie titles, ratings, and years to the console and save the data to a CSV file named "imdb_movies.csv" in the same directory as the script.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments
This project was inspired by a similar project on Real Python.
