# covidtitletest - API Testing with Newman


### What is this repo for? 

- This is a sample practise about running Newman API script in Shippable CI. 
- It is checking all returned articles have COVID as titles on [newsapi.org](https://newsapi.org/).
- Version 1.0 



### Dependencies

- node.js: 13.12.0 (above version 10）
- newman: 5.0.0
- newman-report-html: 1.0.5 


### Set up

- npm install
- npm test



### How to run test?

##### Run tests:

- Way1: Run `npm test` to execute all test cases (json format) under `test` folder. 
- Way2: Run `newman run test/YOUR_TEST_FILE_NAME.json -r html` to execute one specific test file


##### Test reports:

- Each report in HTML format is under `newman` folder


### Tools:

- node.js
- Postman/Newman
- Shippable CI


### Contact: 

- Author: Li Yu





