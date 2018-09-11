# bot-acceptance-tests

### Work in progress
This repo will eventually maintain an end to end bot acceptance test framework.  

The framework should be able to track a bot repo under development and automate CI testing by programatically doing the following:
- Set up a new user and channel on the [RocketChat bots playground](https://botkit.rocket.chat/home)
- Configure a new instance of the bot which is connected to the bot playground
- Run an automated set of tests against the bot to test platform functionality and bot logic.

### Richmessage platform functionality tests
- A set of tests using Selenium to drive chrome, interact with a bot on a Rocket.Chat server, and verify rich message content [Here](./richmessagebot-automated-tests)
