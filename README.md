# Project2 - WELP Fusion API app

## Overview
Welp is a web application that uses the Yelp Fusion API to search for restaurants. Customers can search by type of restaurant and location. Customers can bookmark restaurants for easy lookup. There is a function to choose a restaurant at random from saved bookmarks to solve the problem of choice overload. Overall the application is stable and easy to use, with a concise UI.

## Technology:
- React Typescript
- React Bootstrap
- Rest API
- Spring Boot
- SLF4J
- MongoDB,
- Yelp fusion API
- Heroku
- Java 8
- Git
- Gradle
- Junit4

## Features: 
- Users can Sign in/ Sign up/ logout.
- Users can search for a restaurant with its name and nearby location.
- Users can see 50 results from the API query.
- Users can bookmark a particular restaurant from the search query. 
- Users can remove a particular saved restaurant from their bookmark.
- Users can press a randomly chosen restaurant button from their bookmark for a recommendation.
- Users can view details of a specific saved restaurant.
- Users can view their saved bookmarks using the navigation bar. 
- Users can view their account information using the navigation bar.

## Getting Started:
In order to run this project, you will need a couple of things:

- Must have nodejs and npx installed.
- Must have Java 8 runtime environment installed.
If the requirements are met, go ahead and clone the repo by using the command below: git clone https://gitlab.com/slaitha/project2.git

Once the repository is cloned you will need to make sure the localhost mongodb server is running. The functionalities of the frontend will not work if http://localhost:8082/ is not running. The Spring service is running at port 8082.

### To run frontend program with yarn
```yarn start```

### To run frontend program with npm
```npm start```

To run the backend
In order to run the backend, any java IDE will work as long as you have step 2 installed.

To use the yelp fusion API
In the folder yelp-api/config.ts, put your yelp Fusion API bearer Key in the between the single quotes ```'put your bearer key here'```

sign up to have access to Yelp Fusion API here: 
[https://www.yelp.com/developers/documentation/v3](https://www.yelp.com/developers/documentation/v3) 

## Contributors: 
Sam Laitha is responsible for configuring the project, implementation of the frontend, and some Unit Tests. Implemented Sign in/up, searchable search bar, displaying search results from yelp fusion API, view account info and logging out.

Xinyao Zhu is responsible for backend Structure/implementation, Unit Test for Controllers, frontend implementations with Sam Laitha on display bookmarks, and randomly choose bookmarks.

Cody Phillips is responsible for backend, testing, code review, and debugging.
