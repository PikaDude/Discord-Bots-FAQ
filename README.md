# Discord-Bot-FAQ

Hi! This is my go-to link for questions that are often asked about Discord Bots.

## How do I make a Discord Bot?
First off you need to know how to code. Creating a bot is not as simple as it sounds. There are many tutorials out there on how to make one, so here's another bare bones one.

### 1. Pick a language
First off you need to choose a programming language. If you already know how to code in a language, go to straight to step 2. If you do not know any, I recommend you learn from [Codecademy](https://www.codecademy.com/). Whatever language you choose is up to you, but most people suggest starting with either Python, Javascript or Ruby. If you have problems along your journey, refer to websites such as StackOverflow for help or ask in the Discord Server, [The Coding Den](https://discordapp.com/invite/rXMFcwk)

### 2. Learn to use a library
Once you've learn how to code in a programming language, find a library that suits the language you just learnt. A library is a pre-written program that will help you write code to interact with the Discord API. Join the Discord Server titled [Discord API](https://discord.gg/discord-api) and choose a channel for the language you know. Please remember that **this server will not teach you how to code**, they will only help you with questions related to the library. Unsure which library to choose? [Refer to this library comparison!](https://discordapi.com/unofficial/comparison.html)

### 3. Create a bot account
**Make sure you only do this step if you know how to code and you've found the library for you!**, otherwise you'll have a bot that won't be able to do anything. Navigate to the [Your Apps](https://discordapp.com/developers/applications/me) page and press "New App". **Make sure you're signed into the right account!**. Fill out the app name with the name of your bot, app description (optional), and choose an icon for your bot (also optional). I wouldn't bother touching the part labelled "Redirect URI(s)". Once you've done that, press the "Create Application" button. Scroll down and press "Create Bot User", followed by "Yes, do it!". Congratulations! You now have a bot account! You can now put your bots token into your code and make your bot come to life. **Please keep your bot token private. Do not share it with anyone and be careful not to push it to GitHub. This token allows anyone to use and abuse your bot so be extremely careful with this! Treat it like a password, it basically is one**.

### 4. Make your bot do stuff
Great! Your bot is now running! It probably won't do anything at this point, so it'd be wise to add some __commands__. Maybe start with something simple such as a "ping" and "pong" command, then start moving onto more complicated features. **Please remember to follow the [Best Discord Bot Practices](https://github.com/meew0/discord-bot-best-practices)**. Have fun!

## That's all too complicated and hard! I want to make a bot now!!!
Sadly, that is basically the only way to make a *real* bot. It is possible to download (clone) a bot off of GitHub, however, this means that the bot isn't exactly *yours*. All you've done is copied someone elses. This means that your bot has a high chance of not being added to a bot list as it is not yours. It is possible to get it added, but if you're reading this, I'm not even going to bother explaing how, because the chances are literally a million to 1.

## Why did my bot get deleted/declined?
Refer to #bot-list-log, it'll tell you there. Common reasons for a bot getting denied are:
### Offline for too long
A bot can only be accepted if it is online for most of it's existance. I recommend hosting your bot on a dedicated server, however I'm not going to go into too much detail on that, sorry.
### Something about a clone?
Means you copied the bot off GitHub. Making your own original bot makes this problem disappear.
### Autoresponse
Means your bot responded to an ordinary message/without prompt. Read the [Best Discord Bot Practices](https://github.com/meew0/discord-bot-best-practices) or just make your bot respond only to commands.

Feel free to contribute to this and add anything else that may seem important.
