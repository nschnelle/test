# AUTOMATION #

So you want to be awesome and start running my automation tests before you commit code? :) Good call! keep reading.

When you run the suite you will be running all tests labeled @smoke as defined my me.. this suite will run in under 10 minutes and provide some confidence that your commit will leave the system in a solid state as it will test key functionality across the whole bankers desktop application.

## Getting started ##

1.) You have the Bankers Desktop App checked out and up and running right? (Maybe you just want to run the tests.. I can appreciate that!)
https://dcstash.service.dev:8443/projects/BD/repos/csp-angular-ui-bd/browse

2.) Then lets get webdriver running, start by running the below (in your project directory) to get the latest webdriver-manager.

```
./node_modules/protractor/bin/webdriver-manager update
```
3.) Once that has finished installing lets get webdriver started.

```
./node_modules/protractor/bin/webdriver-manager start
```

### AUTOMATION TESTS THROUGH TERMINAL ###

1.) If you want the tests to run via terminal/iterm simply navigate to the project directory and run:

```
protractor config/protractor/protractor_conf.js
```

### AUTOMATION TESTS THROUGH INTELLIJ ###

1.) Great lets set up the tests to be able to run through Intellij! Start by editing configurations in Intellij.

![alt text](http://i61.tinypic.com/5306ps.png "Logo Title Text 1")

2.) Now add a new node.js configuration. (Please note you may need the Node plugin for intellij)

![alt text](http://i62.tinypic.com/n6z28z.png "Logo Title Text 1")

3.) BOOM! great work now lets add the required configuration to be able to click the green play button and watch the magic! (don't forget to edit folder paths to match yours, apply and click ok to save.)

![alt text](http://i59.tinypic.com/ehddw4.jpg "Logo Title Text 1")

4.) WOO! Now click play and enjoy.

![alt text](http://i58.tinypic.com/2d0b8dy.png "Logo Title Text 1")


#### Any issues feel free to come ask for my assistance. :) ####