# elabordemo
API test using Postman

## Usage
To run tests , follow below instructions:

- Clone this repo
- Install node.js
- Install newman node module


## Run following commands in terminal to execute two test cases
```console
$ npm install -g newman 
$ newman run GetDetails.postman_collection.json -e AssgnmentEnv.postman_environment.json -r cli,json 
$ newman run Assignment.postman_collection.json -r cli,html -e AssgnmentEnv.postman_environment.json -d DatasetNew.csv

```

