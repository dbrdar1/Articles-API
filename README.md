# Articles-API

Welcome to this REST API that offers you all the main operations of a REST web service: GET, POST, PUT, PATCH, DELETE.
It's about articles that you can create, read, update and delete. An article consists of a title and the article content.

You can see the availables routes and methods below.

## /articles route

#### GET method
- fetches all articles

#### POST method
- posts a new article

#### DELETE method
- deletes all articles

## /articles/{articleTitle} route

#### GET method
- fetches the article with the specified title {articleTitle} or returns "No articles matching that title found." if there is no article with the requested title.

#### PUT method
- replaces the article with the specified title {articleTitle} with a new one

#### PATCH method
- updates the article with the specified title {articleTitle} by only replacing the specified fields

#### DELETE method
- deletes the article with the specified title {articleTitle}
