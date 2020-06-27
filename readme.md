# liri  <a id="top"></a>

In this assignment, LIRI is like iPhone’s SIRI. However, LIRI is a Language Interpretation and Recognition Interface. LIRI will be a command line node app that takes in parameters and gives you back data.

Expected Outcomes
The LIRI Bot was designed to produce search results based on the following commands:

## Each command produced different search results as listed below:

## node liri.js concert-this "Arist/ Band name"

Will retrived data from API and it display the name of the venue, location and date of event.

![concert-this](https://raw.githubusercontent.com/Jrubi89/liri-bot/master/images/concert-this.PNG)

## node liri.js spotify-this-song "Song title"

Will retrived data from API and it display the Artist name, song, URL and album name.

![spotify-this-song](https://raw.githubusercontent.com/Jrubi89/liri-bot/master/images/spotify-this-song.PNG)

## node liri.js movie-this "Movie Title"

Will retrived data from API and it display the Movie title, year released, reating, country and language. This infomation will also display on log.txt.

![movie-this](https://raw.githubusercontent.com/Jrubi89/liri-bot/master/images/movie-this.PNG)

## node liri.js do-what-it-says

Will retrived data from random.txt.

![do-what-it-says](https://raw.githubusercontent.com/Jrubi89/liri-bot/master/images/do-what-it-says.PNG)



## Technologies used

* NodeJS
* JavaScript
* Spotify API
* Twitter API
* OMDB API

## NPM packages used:

* dotenv.
* request (omdb api).
* node-spotify-api.
* figlet.
* fs.
