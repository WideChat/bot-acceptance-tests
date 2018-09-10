# bot-acceptance-tests

### Work in progress
This repo will eventually maintain an end to end bot acceptance test framework.  

The framework should be able to track a bot repo under development and automate CI testing by programatically doing the following:
- Set up a new user and channel on the [RocketChat bots playground](https://botkit.rocket.chat/home)
- Configure a new instance of the bot which is connected to the bot playground
- Run an automated set of tests against the bot to test platform functionality and bot logic.

### Installation
Google Chrome should be present on the system.

[Download Chromedriver](https://sites.google.com/a/chromium.org/chromedriver/downloads) and place executable on your system PATH.

Clone the repository.
```bash
npm install
```
In config.js, add username and password for the user acccount.
```bash
node index.js    // runs the tests
```
