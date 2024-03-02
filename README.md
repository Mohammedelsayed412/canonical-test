# Blog-Posts React App

Application URL ==> https://mohammedabdelraoof.github.io/canonical-task/

## How to run

You can use the deployed page from the above URL or follow these steps to run it on your local host:-

## A) Run with docker 
### 1- `docker build -t canonical-test .`

To build your docker image, make sure you are in your app home directory 

### 2- `docker run -p 3000:3000 canonical-test`

To run you docker container for image created.

## B) Run on your local machine  
### 1- `npm install`

To install required packages from package.json file

### 2- `npm run build`

To build the app 

### 3- `npm run start`

Runs the app in the development mode.

Open [http://localhost:3000](http://localhost:3000) to view it in the browser.


## How to test

#### 1- Run app first

#### 2- `npm test`
To start cypress e2e test to test this simple page, I use e2e to make simple test for this page, and this can be component testing too.

#### 3- Select E2E testing then select home_spec test and now you can see test cases runing

