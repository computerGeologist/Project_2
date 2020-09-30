# Project_2
How Long Will A Movie Last?
Description: Theaters rent the rights to use movies from producers for blocks of four weeks at a time, but movies tend to drop in popularity over time, roughly approximating exponential decay in terms of normalized per-theater revenue. I wish to determine the 'half-life' of a movie's popularity.
Data: Target variable is "log(Box office on week N)/log(Box office on week 1)", i.e. the half-life of the movie. Features are actors, genre, budget, initial box office (possibly nonlinear relationship between week N and week 1), date of release, and Metacritic ratings.
Data Used: In order from lowest scope to largest, BoxOfficeMojo, IMDB, and Metacritic.
Tools Used: Linear regression from sklearn. Seaborn to show data plots.
Possible Impacts: Theaters will make more money due to showing higher-popularity movies at the appropriate times. Well-loved movies will stay in theaters longer. 
