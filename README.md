# liri-node-app

liri-node-app
#Liri Search Bot#

This node application at it's core is a simple SWITCH CASE statement. From the command line run the liri.js file as you would any other Node.js & enter the following commands.

Commands & corresponding images showing an example:

1. `node liri.js concert-this <artist/band name here>`
Will call the Bands In Town API and return the first result of a concert of your artist that is playing in a town.

![bands](\images\bands.png)

2. `node liri.js spotify-this-song '<song name here>'`
Will call the Spotify API and return the first result matching the song you entered.
![spotify](\images\spotify.png)

3. `node liri.js movie-this '<movie name here>'`
Will call the IMBD API and display the details of the movie you searched for.
![movie](\images\movie.png)

4. `node liri.js do-what-it-says`
No search filter accepted, just call liri.js with this command and it will read in a search term from the file "random.txt" and search Spotify for the term that was read into the file. 
![doit](\images\doit.png)

Dependancies:

* fs
* axios
* node-spotify-api