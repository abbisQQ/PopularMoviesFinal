# PopularMoviesFinal

This is a project from udacity course fast track.

Its an app that uses moviesdb API(notice that you need an api key for this app to work) to fetch movie data and present it to the user.
The main layput displays the movie posters in a recyclerview, the user may short them by popularity or rating, clicking on a poster you 
will go to the detail layout that has some additional info for the movie.
SaveInstanceState is used in order to make only the necessery calls to the moviedb server Async task use for better performance plus 
a progressbar so the user know the app is working as intended and its not broken.
