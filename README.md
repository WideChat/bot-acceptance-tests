# bot-acceptance-tests

### Work in progress
This repo will eventually maintain an end to end bot acceptance test framework.  

The framework should be able to track a bot repo under development and automate CI testing by programatically doing the following:
- set up a new user and channel on the [RocketChat bots playground](https://botkit.rocket.chat/home)
- configure a new instance of the bot which is connected to the bot playground
- run an automated set of tests to test platform functionality and bot logic.
