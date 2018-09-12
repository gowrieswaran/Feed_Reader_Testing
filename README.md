# Feed_Reader_Testing

## About

Feed Reader Testing is a web-based application that reads RSS feeds.

## Jasmine - Overview

Jasmine is a behavior-driven development framework for testing JavaScript code. It does not depend on any other JavaScript frameworks. It does not require a DOM. And it has a clean, obvious syntax so that you can easily write tests.

`*Jasmine Documentation:*` <https://jasmine.github.io/>

## How to use Jasmine

Jasmine is very easy to implement in any kind of development methodology. All you need to download is the standalone library files from the official website <http://jasmine.github.io/> and implement the same in your application.

## Jasmine for Feed Reader

Jasmine has a spec file which contains all the test suites, that will be run against the application.

### Test suite

A Test suite is a group of test cases that can be used to test a specific behavior of the JS code.

### A sample test suite

```javascript
describe("A suite", () => {
  it("works", () => {
    expect(true).toBe(true);
  });
});
```

### Test Suite for Feed Reader

    * RSS Feeds - Tests to make sure that all Feed variables are defined and not empty.

    * The Menu - Test to ensure that menu element is hidden by default.

    * Initial Entries - Test to ensure that loadFeed function is called and there is a entry element within each feed.

    * New Feed Selection - Test to ensure that the content changes when new Feed gets loaded.

## How to Run

Click on the link < >

- When the page loads, all of the test should pass.

- All the test suites with the results can be found at the end of the page.

### How to Run locally

- Click on the link : https://github.com/gowrieswaran/Feed_Reader_Testing.git

- Clone or Download (ZIP) the repository to your local machine.

- Navigate to the folder and look for index.html.

- Double click index.html to load feed reader in the browser.

- All the test suites with the specs and test results can be found at the end of the page.
