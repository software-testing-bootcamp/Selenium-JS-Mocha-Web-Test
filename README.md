# Selenium-JS-Mocha-Web-Test

**Requirements:**

Download Selenium Grid JAR file -> https://www.selenium.dev/ 

Install NodeJS -> https://nodejs.org/en/download/ 

Install Mocha -> https://mochajs.org/#installation 

Install ChromeDriver -> https://www.npmjs.com/package/chromedriver 

Downlaod VS Code -> https://code.visualstudio.com/


**Sample web application:**

https://www.testrelic.com/bugshop/


**How to start test?**
1. Open project folder with VS Code
2. Open terminal window within VS Code
3. Run this command to install dependencies -> Npm install
4. Run this command to start test -> mocha test/sepeteEkleCikarTest.spec.js

**How to start Selenium Grid on your computer?**
1. Run this command on a new terminal window ->.    java -jar selenium-server-4.0.0-beta-4.jar hub
1. Run this command on a new terminal window ->.    java -jar selenium-server-4.0.0-beta-4.jar node --detect-drivers true
2. Open URL and  check if you could see the browsers on your Grid. -> http://192.168.1.39:5555
