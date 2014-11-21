# Feedjira app

Fetches and parses RSS feeds and returns the data in JSON. Uses [Feedjira](http://feedjira.com/).

## Develop

    bundle
    foreman start

## Deploy

    git remote add heroku git@heroku.com:feedjira.git
    git push heroku

## Example usage

https://feedjira.herokuapp.com/?url=http://blogs.msdn.com/rss.aspx

Useful with an browser extension like [JSONView](https://chrome.google.com/webstore/detail/jsonview/chklaanhfefbnpoihckbnefhakgolnmc).
