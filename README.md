# PyCon Canada 2015 - Interactive Media Development with Python &amp; TouchDesigner Projects
Instructions and project files for Interactive Media Development with Python &amp; TouchDesigner tutorial at PyCon Canada 2015

##Final Product
![ScreenShot](Demo.jpg)

##Goals
The goal of this tutorial is to quickly use TouchDesigner and Python to: 

1. Get sensor inputs and create control values and triggers
2. Use the sensor triggers to scrape data from Twitter using Python Requests library
3. Analyze the incoming tweets to create a map of most used words in tweets relating to PyCon Canada 2015
4. Visualize the word cloud
5. Use sensor control values to manipulate the word cloud in real-time
 

##Pre-requisite steps
1. Download 64-bit Windows Python 3.x (3.5 will be used in this tutorial)
2. Run ```pip install requests requests-oauthlib``` in an elevated command prompt (make sure your PATH is calling Python 3 pip!)
3. Download and install [TouchDesigner](https://www.derivative.ca/088/Downloads/Default.asp)
3. In TouchDesigner, in the menu bar, go to Edit -> Preferences.
4. In the General settings, set the Python 64-bit Module Path to your site-packages folder. With Python 3.5, the default is ```C:/Program Files/Python 3.5/Lib/site-packages```
5. Go to [Twitter's Developer page](https://apps.twitter.com/) and register an application
6. Generate a set of OAuth credentials for yourself


##Attribution & Useful Tools
- [Kennith Reitz's Python Requests library](https://github.com/kennethreitz/requests)
- [Curious Concept JSON Formatter & Validator](https://jsonformatter.curiousconcept.com/)
- [Derivative TouchDesigner](http://derivative.ca)
- [Twitter API Console](https://dev.twitter.com/rest/tools/console)

##Notes
- To receivce sensor data on-site in real-time, bring a CAT5 cable to connect to our local switch. You will receive multicast OSC messages at 239.255.0.2 on port 10000.
