# Udacity Front-end Nanodegree Project - Feed Reader Testing

This project tested ability to use a testing suite, like
Jasmine, to validate code. Started with a Feed Reader App
and were required to write test spec in Jasmine.

## Why this Project?

Testing is an important part of the development process and many organizations practice a standard of development known as "test-driven development". This is when developers write tests first, before they ever start developing their application. All the tests initially fail and then they start writing application code to make these tests pass.

Whether you work in an organization that uses test-driven development or in an organization that uses tests to make sure future feature development doesn't break existing features, it's an important skill to have!

## Getting Started
To run the application: download and open index.html in the browser.
The jasmine tests should automatically run and will appear at the bottom of the page.

_The file for the jasmine tests are located in jasmine/spec/feedreader.js_

Tests that are **green** have passed and **red** have failed. **That's called Red-green Refactor**


## The tests:

1. tests to make sure that the allFeeds variable has been defined and that it is not empty.
2. loops through each feed and determines if the URL is defined and not empty.
3. loops through each feed and determines that each feed has a name and not empty.
4. ensures the menu element is hidden by default.
5. validates proper functioning of the hamburger menu toggle.
6. tests that there is at least one entry element in feed container.
7. tests for ensure that new content is loaded by loadFeed().


## How to launch this project ?
1. Download this project & open in the browser.
2. scroll down and check the jasmine specs test.
