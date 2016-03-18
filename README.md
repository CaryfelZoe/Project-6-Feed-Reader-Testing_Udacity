#Project 7: Feed Reader Testing

1. Open index.html in your browser
2. Review the Project of Feed Reader Testing.
3. Explore the Tests that are written using Jasmine to make sure the udacity blog RSS feed works correctly.

----------------------------

##How I completed this Project?

1. Reviewed course JavaScript Testig.

2. Downloaded the [required project assets]

3. Reviewed the functionality of the application within your browser.

4. Explored the application's HTML (*./index.html*), CSS
(*./css/style.css*) and JavaScript (*./js/app.js*) to gain an understanding of how it works.

4. Explored the Jasmine spec file in *./jasmine/spec/feedreader.js*

5. Edited the allFeeds variable in *./js/app.js* to make the provided test fail and see how Jasmine visualizes this failure in the application.

6. Returned the allFeeds variable to a passing state.

7. Wrote a test that loops through each feed in the allFeeds object and ensures it has a URL defined and that the URL is not empty.

8. Wrote a test that loops through each feed in the allFeeds object and ensures it has a name defined and that the name is not empty.

9. Wrote a new test suite named "The menu".

10. Wrote a test that ensures the menu element is hidden by default. 

11. Wrote a test that ensures the menu changes visibility when the menu icon is clicked, and it has two expectations: does the menu display when clicked and does it hide when clicked again.

12. Wrote a test that ensures when the loadFeed function is called and completes its work, there is at least a single .entry element within the .feed container. 

13. Wrote a test that ensures when a new feed is loaded by the loadFeed function that the content actually changes.

14. All of the tests should pass.