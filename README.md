
```
This frameowrk is created using Ruby, Capybara, Cucumber and SauceLabs
This repository contains a cucumber feature file that just opens our application, 
provides invalid credentials and try to login.
You can run the test using the commands below either on SauceLabs or in your 
local box with a chromedriver available.
Please create your own branch as per your convenience and integrate Screener
in this framework

```
## To Download Ruby
https://www.ruby-lang.org/en/downloads/
https://github.com/oneclick/rubyinstaller2/releases/download/RubyInstaller-2.7.7-1/rubyinstaller-devkit-2.7.7-1-x64.exe
```

## Running Tests
To run any particular test
```
#Use the below command to run the sample test in your local browser 
cucumber features -t @login run=local

#Use the below command to run the sample test in Sauce 
cucumber features -t @login
```
