Abdirahman Mohamed
## 1) Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.
Answer: Within a Github action that runs whenever code is pushed because automated tests should be triggered every time code is pushed to ensure new changes don’t break existing functionality.
## 2) Would you use an end to end test to check if a function is returning the correct output? (yes/no)
Answer: No becase E2E tests simulate user interaction with the entire system, not individual functions.
## 3) What is the difference between navigation and snapshot mode?
Answer: Navigation mode loads the full page to test performance from start to finish. Snapshot mode captures the current page state without reloading.
## 4) Name three things we could do to improve the CSE 110 shop site based on the Lighthouse results.
Answer: We could properly size the product images to save 800 KB and improve load performance. We should also add a <meta name="viewport"> tag to make the page responsive for mobile users. Lastly, we could add a [lang] attribute to the <html> tag to improve accessibility for screen readers and users in different locales.





