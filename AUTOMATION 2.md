# AUTOMATION #

So you want to be awesome and start running my automation tests before you commit code? :) Good call! keep reading.

## Getting started ##

1.) You have the product services repo checked out and up and running right? (Maybe you just want to run the tests.. I can appreciate that!)
https://dcstash.service.dev:8443/projects/CSP/repos/csp-java-api-productservice/browse

2.) Next up is to ensure ruby is ready to rock

   - Install rbenv - https://github.com/sstephenson/rbenv
   - Next install ruby-build - https://github.com/sstephenson/ruby-build
   - Then run ``` rbenv install 2.1.2 ```
   - finally run ``` gem install bundler ```

4.) Great! Next up you need to navigate to the e2e directory within the project and run a bundle to install all those juicy gems.

```
Cameron-Bradley-MacBook-Pro:e2e cameronbradley$ bundle
```

### AUTOMATION TESTS THROUGH TERMINAL ###

1.) If you want the tests to run via terminal/iterm simply navigate to the e2e folder within the project directory and run:

```
cucumber
```

### AUTOMATION TESTS THROUGH INTELLIJ ###

1.) Great lets set up the tests to be able to run through Intellij! First install the intellij plugins for cucumber and ruby.

2.) Then lets get started by editing configurations in Intellij.

![alt text](http://i61.tinypic.com/5306ps.png "Logo Title Text 1")

2.) Now add a new cucumber configuration

![alt text](http://i59.tinypic.com/chljt.png "Logo Title Text 1")

3.) BOOM! great work now lets add the required configuration to be able to click the green play button and watch the magic! (don't forget to edit folder paths to match yours, apply and click ok to save.)

![alt text](http://i58.tinypic.com/258uue1.png "Logo Title Text 1")

You will notice in the above screenshot I have rbenv 2.1.5 as my SDK, I recommend 2.1.5 version because it does not have any issues with the latest versions of MAC IOS. (If you have any issues with this give me a shout)

4.) WOO! Now click play and enjoy.

![alt text](http://i58.tinypic.com/5p54qw.png "Logo Title Text 1")


#### Any issues feel free to come ask for my assistance. :) ####