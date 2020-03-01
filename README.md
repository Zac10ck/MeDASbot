# Bot with Google's Dialogflow
### A BotUI app connected to Google's Dialogflow
Update : This repo was made at the time when Dialogflow was known as API.AI. You will have to use Dialogflow APIs V1 in the console to make it work, that said. this repo is no longer maintained by the creators.
###### FEEL FREE TO MAKE PULL REQUESTS

##### How to Use?

You can simply chose to
Build it yourself from scratch using this [Tutorial](https://chatbotslife.com/custom-api-ai-chatbot-using-botui-58d673155c7d).

OR...

Follow these steps below

1. Go to [Dialogflow](https://dialogflow.com/) and get a key!
2. Clone the Repo,
  `
  git clone https://github.com/Zac10ck/MeDASbot.git
  `
3. `cd bot_api.ai`
4. Place your Key in config/api.js
5. `npm install`
6. `node bin/www`
7. Open Browser , go to "localhost:3000"

  Edit the Chat Flow from public/javascripts/convo.js

UI Design by [BotUI](https://github.com/moinism/botui).
NLP Used [API.AI](https://www.api.ai).
# MeDASbot


## Ubuntu FireWall Rules 

   Usage: ufw COMMAND

Commands:
 enable                          enables the firewall
 disable                         disables the firewall
 default ARG                     set default policy
 logging LEVEL                   set logging to LEVEL
 allow ARGS                      add allow rule
 deny ARGS                       add deny rule
 reject ARGS                     add reject rule
 limit ARGS                      add limit rule
 delete RULE|NUM                 delete RULE
 insert NUM RULE                 insert RULE at NUM
 route RULE                      add route RULE
 route delete RULE|NUM           delete route RULE
 route insert NUM RULE           insert route RULE at NUM
 reload                          reload firewall
 reset                           reset firewall
 status                          show firewall status
 status numbered                 show firewall status as numbered list of RULES
 status verbose                  show verbose firewall status
 show ARG                        show firewall report
 version                         display version information

Application profile commands:
 app list                        list application profiles
 app info PROFILE                show information on PROFILE
 app update PROFILE              update PROFILE
 app default ARG                 set default application policy

