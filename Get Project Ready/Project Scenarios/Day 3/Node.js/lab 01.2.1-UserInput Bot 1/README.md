# User Input Bot 1

In this lab you will build a bot which collect information from user such as name and display back response provided by the user.

### Prerequisites
The following software environment is needed for running this bot :

```
1.Node.js
2.Microsoft BotFramework Emulator.
3.SubLimeText Editor.
```

### Collecting the keys

Over the course of this lab, we will collect various keys. It is recommended that you save all of them in a text file, so you can easily access them throughout the workshop.Keys are :
```
-Bot Framework App ID.
-Bot Framework App password.
```
Note:Please refer following link to understand how to generate Bot Framework APP ID and App password.  link :[Bot Registration](https://docs.microsoft.com/en-us/azure/bot-service/bot-service-quickstart-registration?view=azure-bot-service-3.0).

### Implementation

To check implementation of this lab please refer to the following file in this path Chat-Bot-AI-Virtual-Trail-Blazer-Series\Node.js\Day 1\lab 01.2.1-UserInput Bot 1:

```
                             userinput_1.js
```

###Check implementation through following steps

1. Open userinput_1.js file in SubLimeText Editor and provide Bot Framework App ID and Bot Framework App password in this section of code. (note : If you are working on local then there is no need to specify Bot Framework App ID and Bot Framework App password  ).

![adaptivecardbot_0](https://user-images.githubusercontent.com/31923904/39426232-aeab6f22-4c9c-11e8-9255-b1ab41b1f3f6.jpg)


2.Open command prompt (cmd) then set path to lab 01.2.1-UserInput Bot 1 folder then run userinput_1.js file using command below:

                               node userinput_1.js

3.Start the Bot Framework Emulator and connect your bot and type http://localhost:3978/api/messages into the address bar.(This is the default end point that your bot listens to when hosted locally).Click on �Connect� button.(note : If you are working on local then no need to specify Microsoft App ID and Microsoft App Password ).  

![adaptivecardbot_1](https://user-images.githubusercontent.com/31923904/39426248-c4a8f204-4c9c-11e8-8bce-08e1ab5751b4.jpg)

  -The following screen-shot shows the result of this chat bot running in the Bot Framework Channel Emulator.
![userinput1](https://user-images.githubusercontent.com/31923904/40771530-32804b3c-64db-11e8-938b-46921f2c7ff6.png)



