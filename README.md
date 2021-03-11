## The purpose of this project is as follows:
This is the base HCM class that allows other CUNYfirst automations in this module to run. 
## Here's some back story on why I needed to build this:
Each module in CUNYfirst works somewhat uniquely and has a number of unique fieldsa nd features. I've created this base class to store widely used methods and data to the child classes for individual areas and functions (such as position management, job data, the CJR, etc).
## This project leverages the following libraries:
pandas, fuzzywuzzy, selenium, webdriver_manager, xlrd
## In order to use this, you'll first need do the following:
The user won't ever need to run this file. It's meant as a static resource only. 
## The expected frequency for running this code is as follows:
As Needed