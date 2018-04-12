# Chatbot Problem Definition

## Requirements

Although it is not a requirement to use [Microsoft's Bot Framework](https://dev.botframework.com), an application shell in JavaScript has been provided to help get you started. Download the [Bot Framework Emulator](https://github.com/Microsoft/BotFramework-Emulator/releases) to debug and develop locally.

### Bot Framework

To use the Bot Framework, be sure to have [Node.JS](https://nodejs.org/en/) installed, and we recommend a text editor like [Visual Studio Code](https://code.visualstudio.com). On the command line, go into the "shell" folder and install the Node modules.

    npm install

To run the bot:

    node app.js

With the bot running, open the Bot Framework Emulator, click on the URL bar, and select `http://localhost:3978/api/messages`. The emulator will then be interfacing with your chatbot. Type "hello" to interact with it.

## Challenge

It's easy to build a bot; it's hard to build a useful bot.

Microsoft, Facebook, and Google are all working towards developing chatbots in order to take advantage of the conversational UI. Designing interfaces has become more than just designing for the web, as now you have to design for text, and even speech for voice UIs.

Medical students, meanwhile, have a very busy schedule with many lectures to attend, various labs, and an overabundance of applications to check.

The challenge is to build a chatbot that makes the medical student experience better in at least one way. Feel free to incorporate external APIs if you feel it's appropriate.

> A useful bot is one that doesn't require more steps than getting the same information elsewhere. Be careful that when designing your chatbot experience that it doesn't take more steps to do it in the chatbot than it would through an application or through email.
