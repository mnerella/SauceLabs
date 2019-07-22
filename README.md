# SauceLabs

Saucelabs is an open source automation tool to run your automation test in the cloud

It allows users to run thier automation tests in the cloud using different browsers , operating systems .

It provides an infrastructure for both manual and automation testing of desktop and mobile applications.

It also provides automating testing for continuos integration and continuous delivery

# How to Run Selenium Tests with Sauce Labs

1)Create SauceLab Account.

2)Login to your Account

3)Then create a function in your script to run Saucelabs
  public static final String USERNAME = "YOUR_USERNAME";
  public static final String ACCESS_KEY = "YOUR_ACCESS_KEY";
  public static final String URL = "https://" + USERNAME + ":" + ACCESS_KEY + "@ondemand.saucelabs.com:443/wd/hub";
  
4)To connect Saucelab to your script we need to use username and Access Key 

5)Got to UserSettings Tab in Sauce LAb where we can find the Access Key .

6)Click on show button then re enter your password to re genrate Access key.

7)Copy the Access key and paste in your script along with the username .

8)Run your Test Case  in IDE

9)Then go to SauceLab Dasboard and select AUTOMATED TESTS where you can see a job in progress

10)You can click on the job and navigate to the test history window.In test history window Sauce Labs will provide a video of your test also it provides you an option to download it.
