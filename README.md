# Restful-API-NodeJS
An article database with Restful-API

# databaseName 
**wikiDB**

# Schema
**title:String**

**content:String**

## Urls
get **localhost:3000/articles**
= gives all articles

post **localhost:3000/articles**
=add articles to database

delete  **localhost:3000/articles**
=delete all articles

get **localhost:3000/articles/:articleTitle**
= gives an article named "articleTitle"

put **localhost:3000/articles/:articleTitle**
=remove "articleTitle" and add a new article

patch **localhost:3000/articles/:articleTitle**
=change "articleTitle"

delete **localhost:3000/articles/:articleTitle**
=delete "articleTitle"
