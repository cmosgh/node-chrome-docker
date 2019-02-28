# node-chrome-docker

## How to build this image

`docker build . -t you/yourImage:yourTag`

## Why created

While trying to run [Cypress](https://www.cypress.io/) or [TestCafe](https://devexpress.github.io/testcafe/) on our CI, I have to make sure we're running the fixed 10.13 version of nodejs so I can start both server and UI testing  
