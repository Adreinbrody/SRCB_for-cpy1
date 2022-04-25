<h1 align="center">
  <b>Save restricted content Bot</b>
</h1> 

Contact: [Telegram](https://t.me/srcb_here)

A stable telegram bot to get restricted messages with custom thumbnail support ,

- works for both public and private channels
- Custom thumbnail support for Pvt medias
- supports text and webpage media messages
- Faster speed
- Forcesubscribe available 
- `/batch` - (For owner only) Use this command to save upto 1000000 files from a pvt or public restricted channel at once.
- Time delay is added to avoid FloodWait and keep user account safe. 

<h2 align="center">
  <b>Steps</b>
</h2> 

- 1 `First in readme file edit and add link of repo in place where its written ur_repo` - To do this first click and open readme file then click edit icon. Then scroll down to `Deploy` on heroku and below click button u will see ur_repo at last of link u got to remove `ur_repo` and add repo link of ur repo
- 2 `Similarly like 1 goto app.json file and add ur repo in repository after removing "ur repo" `
- 3 `Now deployment`- click on deploy to heroku button. It will open heroku page , login and then fill all variables given below then click deploy. wait and it will be deployed. Check if resources are turned on or not if not then switch on resources .Done.
- 4 `Using Bot` - start by using command /start wait might take some time for first time, if no response give command again . then for single files u can just send links and it will give files. `Note` give invite link first for private channels
- 5 `Batch command` - Give command /batch then it will ask for starting file link give that then it will ask for no. of files u want so put that i.e. if u want 10 files put 10, and like this. it will give u that.Done.


# Variables

- `API_ID`
- `API_HASH`
- `SESSION`
- `BOT_TOKEN` 
- `AUTH` - Owner user id
- `FORCESUB` - Public channel username without '@'. Don't forget to add bot in channel as administrator. And add ur bot in that channel as admin 

# Botfather commands to add
- `start`
- `batch`

# Get API & PYROGRAM string session from:
 
API: [API scrapper Bot](https://t.me/USETGSBOT) or [Telegram.org](https://my.telegram.org/auth)

PYROGRAM SESSION: [SessionGen Bot](https://t.me/SessionStringGeneratorZBot) or [![Run on Repl.it](https://replit.com/badge/github/vasusen-code/saverestrictedcontentbot)](https://replit.com/@SpEcHiDe/GenerateStringSession)

BOT TOKEN: @Botfather on telegram

# Deploy
  
Deploy your bot on `heroku`


- Fork the repo, and star it
- create app in heroku
- go to settings of app>> config vars>> add all variables
- add buildpacks
- connect to github and deploy
- turn on dynos
  
`or`

CLick Button

[![Deploy to Heroku](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy?template=https://github.com/Adreinbrody/SRCB_for-cpy1)

Changes to make
add repo link in deploy button - readme file
add repo link in repository in app.json
if want remove auth so everyone can use batch
removed limit in batch 
and edited time in batch can be edited more
😎😎 done 
original repo-[MAStER branch](https://github.com/vasusen-code/SaveRestrictedContentBot)

  
Buildpacks for manual deploy:

- `heroku/python`
- `https://github.com/jonathanong/heroku-buildpack-ffmpeg-latest.git`

Deploy your bot on `Okteto`
  
[![Develop on Okteto](https://okteto.com/develop-okteto.svg)](https://cloud.okteto.com)
