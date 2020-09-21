# Home Assignment

## Create the following web application

### Technologies

### Server: PHP

### Client: JS/React/Angular/Vue

### DB: MYSQL

#### Instructions

The following application will give users the ability to manage their favorites countries.

##### login page

- user name
- password

you can choose a single user and create it in the DB before.

after user authenticated he will redirected to the main page

##### main page

will present the Countries from the following API: `https://restcountries.eu/`

- All the requests will arrive from the PHP Backend that will execute the API calls.

- UI - Cards/Table

1. Country name
2. Region
3. population
4. Add to favorite - button saving the country as favorite for the current user

##### Favorites

present all the countries in the same UI as main page, without - Add to favorite, but with remove from favorites

ability to add comments under each favorite country with the following information:

- created at
- description

##### Favorites Statistics ( can be nested route)

this page will present a bar chart that contain all the favorites countries populaion of the current user, x axis - country name
y axis - number of population

### Deployment

The project must be served on github with client and server folders with all the relevant files, readme for documentations and "how to?" starting the project locally.
