# API Docs - Multiquery Moviedb

## Task

Use the superagent promise library to request data from The Movie DB API and output results to the DOM.

## Problems

#### Problem 01
Get the <u>2nd best rated movie</u>.

Put your output on the DOM in:

`<mark class="problem-01">...</mark>`

#### Problem 02
Get the quantity of cast members from the credits for the 2nd best rated movie

Put your output on the DOM in:

`<mark class="problem-02">...</mark>`

#### Useful Information

- Query for the top rated movies

  `https://api.themoviedb.org/3/movie/top_rated`

- Query for movie credits (using the 2nd best rated movie id)

  `https://api.themoviedb.org/3/movie/{movie_id}/credits`

- moviedb api key parameter: `api_key=d48bf9ada30f2e8b7671d25d6160e2b6`
