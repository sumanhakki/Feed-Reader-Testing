# Feed Reader Testing

### Project Objective

This is an Udacity project designed to practice unit testing in JavaScript

### Project set-up and features
  - Copy the repo and open the index.html
  - Once open, RSS feeds are loaded using the Google Feed Reader API to grab RSS feeds
  - Hamburger icon displays a menu for specific topics
  - Below the RSS feeds, Jasmine test suite is displayed
  - All the tests that were created in feedreader.js are displayed in Jasmine with a passing result

### Tests that were required by the project
  - Write a test that loops through each feed in the allFeeds object and ensures it has a URL defined and that the URL is not empty.
  - Write a test that loops through each feed in the allFeeds object and ensures it has a name defined and that the name is not empty.
  - Write a new test suite named "The menu".
  - Write a test that ensures the menu element is hidden by default. 
  - Write a test that ensures the menu changes visibility when the menu icon is clicked. This test should have two expectations: does the 
    menu display when clicked and does it hide when clicked again.
  - Write a test suite named "Initial Entries".
  - Write a test that ensures when the loadFeed function is called and completes its work, there is at least a single .entry element within the 
    .feed container.
  - Write a test suite named "New Feed Selection".
  - Write a test that ensures when a new feed is loaded by the loadFeed function that the content actually changes.