# Feeder Reader Testing Project

This testing project utilizes the Jasmine testing framework to test various functionalities of a feed reader application. 

## Instructions

* Download all application components
* Open the index.html file. 
* The index.html file contains the feed reader application along with the test runner on the bottom of the page.  

## Tests

* Looped through allFeeds object and check that the name is defined and is not empty.
* I wrote new describe() test suite for "The menu."
* Inside "The menu" test suite, there a test that ensures the menu element is hidden by default.
* Another test in the "The menu" test suite ensures that the menu changes visibility when the menu icon is clicked. 
* I wrote a third test suite called "Initial Entries."
* The "Initial Entries" suite checks that the loadFeed function is invoked and completes all tasks successfully.
* A final "New Feed Selection" test suite which contains an it() to examine that a new feed content is changed when the loadfeed functioned is called.

## Dependencies and Acknowledgments

* Udacity for project assets
* All project assests from https://github.com/udacity/frontend-nanodegree-feedreader
* Jasmine testing framework