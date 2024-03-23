# Dissecting-Spotify-Valence-ML-Analysis 

## Purpose
The aim of this project is to untangle the mystery behind Spotify's *valence* and propose how this is derived.

Spotify uses the metric called *valence* to measure the happiness of a track. The metric itself, however, was not developed by Spotify. It was originally developed by Echo Nest, a company that was bought by Spotify in 2014. We don't know exactly how valence is calculated. Some details are given by a blog post, which you can find here:

https://web.archive.org/web/20170422195736/http://blog.echonest.com/post/66097438564/plotting-musics-emotional-valence-1950-2013

## Data
The dataset was created with the help of the [Spotify's Web API](https://developer.spotify.com/documentation/web-api/reference/#/) and contains information for both the track and the audio features of song. 
