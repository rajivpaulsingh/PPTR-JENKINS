1. npm init
2. npm install puppeteer mocha chai
3. npm install prettier
4. Create .prettierrc and add stuff to it
5. Edit the test script in the package.json to meet our needs
6. Create smoke and end to end tests
7. Download jenkins war, place it in the project root directory and run the following command in the terminal to install jenkins
    - java -jar jenkins.war -httpPort=8080 --enable-future-java
8. Jenkins will be installed now, the url is localhost:8080
9. Create a new job:
    - Click advanced under General and use custom workspace (/Users/singh2_rajiv/Automation/Puppeteer/PPTR-JENKINS)
    - Goto build and select execute shell (use command from the package.json - npm run test-smoke)