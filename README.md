# API Tests (Postman)  - Julio Guerra

## Overview
This project demonstrates the usage of Postman to build API Tests 
Test cases:
- Get three countries information
- Get inexistent countries reponse
- Post Add country

## Prerequisites
Install Postman

## Setup
- Clone this repository to your local machine:

```
git clone git@github.com:juliojguerra/api-testing-pm.git
```

- Open Postman and create a new workspace
- Click on import folder
- Select postman_files folder, open
- Run each request as suggested in Usage section


## Usage
### Get three countries information
Run this collection with countries.json and add a delay of 1000ms (at least)

### Get inexisting countries response
Run this collection with invalid_countries.json and add a delay of 1000ms (at least)

### Post Add country
Run this collection alone, does not need any test data file.

Notes: 
- Test data (countries and invalid_countries json) is in /test_data folder
- To run a collection, click on the 3 dots next to the collection name, click on Run Collection, choose corresponding file and add delay.

