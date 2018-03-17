---
layout: post
title: Find Similar Movies
---

EDIT: This project is no longer being maintained as RottemTomatoes have updated their API access to a paid model.

So after watching a really good movie, have you ever wanted to find similar movies?

Sure, there's services out there like NetFlix™ or IMDB™ which can help you with this. However, these services haven't exposed their APIs so use is limited to being within their website or App.

This project started off as a way to establish a simple way to look for similar movies.

RottenTomatoes™, a widely known film review aggregator, does have a public API. This API is utilized in this Android App. 
No movie-matching calculation is done in the App itself, the RottenTomatoes™ API is used to fetch all data. 
An API call is made to RottenTomatoes™ with the entered movie & a list of movies similar to this selection is displayed as a list on screen.

Known Limitations:
- As this is a public API, there are rate limits. Rates at the time of publishing are limited to 5 API calls per second and 10,000 calls per day.
- Newer movies may not yield any results, this is dependent on RottenTomatoes™ updating their databases.

This is an open source project browsable on GitHub (github.com/InViN/SimilarMovies). 
Feel free to e-mail me with feature requests, bug reports or any general suggestions.

You can try this App out on the Google Play Store.

<a href="https://play.google.com/store/apps/details?id=invin.com.similarmovies">
    <img alt="Android app on Google Play" src="https://developer.android.com/images/brand/en_app_rgb_wo_60.png" />
</a>