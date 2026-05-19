# Lab 7 - Unit & E2E Testing

**Name:** Zachary Huang

## Check Your Understanding

**1) Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.**
- **<u>Within a Github action that runs whenever code is pushed</u>**
- Manually run them locally before pushing code
- Run them all after all development is completed

This is the best place to include the automated test in your project pipeline because it catches functionality regressions without requiring anyone to manually run tests. It also fits cleanly into code review, since broken tests block bad PRs.

**2) Would you use an end to end test to check if a function is returning the correct output? (yes/no)**\
No. E2E tests simulate user interactions with the full UI from start to finish. If you wanted to verify a single function's return value, a unit test would be more appropriate.

**3) What is the difference between navigation and snapshot mode?**\
Navigation mode analyzes the page right as it loads and produces overall performance metrics, but it cannot capture interactions or dynamic content changes. Snapshot mode analyzes the page in its current state, but cannot measure JS performance or DOM changes over time.

**4) Name three things we could do to improve the CSE 110 shop site based on the Lighthouse results.**
- Add alt text to product images.
- Compress and resize images.
- Add a <meta name="description"> tag.






