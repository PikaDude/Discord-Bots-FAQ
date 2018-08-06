# Discord Bots FAQ

Hi! This is a go-to link for questions that are often asked about Discord Bots (the server and actual bots). I know that there's a lot here and I don't expect anyone to read *all* of this, but this is more of a cheat sheet than a list of rules, mainly so I can throw links to specific sections for whenever someone asks a common question. If you have any questions about the server, about bots, or anything else, I recommend you check here first before asking.

## How do I make a Discord Bot?
First off you need to know how to code. Creating a bot is not as simple as it sounds, it's not as simple as pushing a button and being done with it. There are many tutorials out there on how to make a Discord bot, so here's another bare bones guide.

### 1. Pick a language
First off you need to choose a programming language. If you already know how to code in a language, go to straight to step 2. If you do not know any, I recommend you learn from [Codecademy](https://www.codecademy.com/). Whatever language you choose is up to you, but most people suggest starting with either Python, Javascript or Ruby. Make sure you also check to see if your language has a supported library (refer to step 2). If you have problems along your journey, refer to websites such as StackOverflow for help or ask in the Discord Server, [The Coding Den](https://discordapp.com/invite/rXMFcwk)

### 2. Learn to use a library
Once you've learn how to code in a programming language, find a library that suits the language you just learnt. A library is a pre-written program that will help you write code to interact with the Discord API. Join the Discord Server titled [Discord API](https://discord.gg/discord-api) and choose a channel for the language you know. Please remember that **this server will not teach you how to code**, they will only help you with questions related to the library. [If you're unsure on which library to choose, you can refer to this library comparison, although I will warn you, it is very outdated.](https://discordapi.com/unofficial/comparison.html)

### 3. Create a bot account
**Make sure you only do this step if you know how to code and you've found a library to use**, otherwise you'll have a bot that won't be able to do anything. Navigate to the [Your Apps](https://discordapp.com/developers/applications/me) page and press "New App". **Make sure you're signed into the right account!**. Fill out the app name with the name of your bot (required), app description (optional), and choose an icon for your bot (also optional). I wouldn't bother touching the part labelled "Redirect URI(s)" if you don't know what it means or how to use it, it's not really required for anything important. Once you've done that, press the "Create Application" button. Once you've done that, scroll down and press "Create Bot User", followed by "Yes, do it!". Congratulations! You now have a bot account! You can now put your bots token into your code and make your bot come to life. **Please keep your bot token private. Do not share it with anyone and be careful not to push it to GitHub. This token allows anyone to use and abuse your bot so be extremely careful with this! Treat it like a password, it basically is one**.

### 4. Make your bot do stuff
Great! Your bot is now running! It probably won't do anything at this point, so it'd be wise to add some __commands__. Maybe start with something simple such as a "ping" and "pong" command, then start moving onto more complicated features. **Please remember to follow the [Best Discord Bot Practices](https://github.com/meew0/discord-bot-best-practices)**. Have fun!

## That's all too complicated and hard! I want to make a bot now!!!
Sadly, that is basically the only way to make a *real* bot. It is possible to download (clone) a bot off of GitHub, or a similar site, however, this means that the bot isn't exactly *yours*. All you've done is copied someone elses. This means that your bot has a high chance of not being added to a bot list (such as Discord Bots) as it is not yours. It is possible to get it added only if **you've heavily modified it to the point that you might as well have created your own bot from scratch**.
![Don't Be Like This](/img/i-made-this.jpg "Don't Be Like This")

## Why is everyone screaming at me to go to testing?
Because you most likely just executed a command in #general. This channel is used for talking and it would be nice if you did not use commands in this channel. As you probably have realised, there are thousands of bots in this server, and executing one command often makes hundreds respond. This is typically annoying and it would be really good if you did this in any of the channels marked as "testing" in their name.

## I need help regarding a specific bot.
This is not a support server for bots. Find that bots **specific** Discord Server and ask there. This server is more regarding the development of bots and of the like.

## Why did my bot get deleted/declined?
Refer to #bot-list-log, it'll tell you there. Common reasons for a bot getting denied are:
### Offline for too long
A bot can only be accepted if it is online for most of it's existance. I recommend hosting your bot on a dedicated server, however I'm not going to go into too much detail on that, sorry. But, I recommend you use Digital Ocean. They're pretty reliable, helpful, have a lot of tutorials and have reasonable prices too. Use [this link](https://m.do.co/c/883e6bb18ff1) to get $10 in credit on their site.
### Something about a clone?
Means you copied the bot off of GitHub or another site. Making your own original bot makes this problem disappear.
### Autoresponse
Means your bot responded to an ordinary message/without prompt. Read the [Best Discord Bot Practices](https://github.com/meew0/discord-bot-best-practices) or just make your bot respond only to commands.
### No description
You gotta put *something* in the description. Also make it accurate, don't lie.
### Not responding to the listed prefix
The bot wasn't responding to any commands with the listed prefix. The bot *was* online, just unresponsive. Either you got the prefix wrong or you changed it after you requested your bot to be listed.

## I've been waiting for a while, why isn't my bot verified yet?
It takes a while for your bot to get verified. From a few days to several weeks. Remember, you're not the only person in the world who wants to get their bot added to the list, there are hundreds of bots in the queue, and each one needs to be manually checked to see if it fits in the guidelines. Please be patient, asking about it or pinging Moderators or Helpers will decrease your chances of it getting verified.

## I can't edit my bots page! What do I do?
You can only edit your bots page once it is verified. If you've made a mistake, or you would like to get it changed, simply ask a Moderator or Helper nicely to delete your bot. This will allow you to re-add it and hopefully correct that mistake you made.

## How the hell does anyone get a bot verified on this list? It's impossible!
It's not impossible, over 1000 bots are on the list. Try reading through this entire FAQ. If the answer isn't here, ask in the server.

## How can I add my bot to the bot list?
Go to the [homepage](https://bots.discord.pw/), press login in the top right, authorize yourself, press "Add Bot", and enter the required information. The information required that is often asked about is:
### What is a client ID?
This is your bots ID. It is displayed on the bots application page. If you do not know what that is, I suggest you read `How do I make a Discord Bot?`, specifically step 3.
### What is a prefix?
A prefix is a character or characters that appear before every bot command. Examples of common prefixes are `!`, `?` and `-`. If your bot does not have a prefix, then it will not be approved. You must follow the [Best Discord Bot Practices](https://github.com/meew0/discord-bot-best-practices)
### What is a library?
Read `How do I make a Discord Bot?`, specifically step 2.

## How do I invite my bot / How do I make an Invite URL / How do I add my bot to my server?
The simplest URL is as follows, replace `REPLACEME` with your bots client ID found on your bots application page. If you do not know what that is, I suggest you read `How do I make a Discord Bot?`, specifically step 3.
`https://discordapp.com/oauth2/authorize?client_id=REPLACEME&scope=bot`

## Ew! An NSFW channel! How can I hide it?
Type `%roleme No NSFW` to hide it. Type it again to show it.

## Something something Discord Bot List
This isn't Discord Bot List. We do things differently here (for the better usually).

## Why is everyone rude to me?
If you do not have a bot developer role, people normally assume that you have no idea what you're doing and you just want to cheese your way into getting the Bot Developer role. Typically, people will not bully you when you join, but if you start asking questions such as questions listed on here, or you say something dumb or you do the wrong thing, people will get annoyed. Trust me, we're all like broken records at this point repeating the process of how to make a bot for the millionth time. We may make bots but in the end, we're only human.

## Is posting invite links allowed?
No. No. No. No. No. No. No. No. Also no. Do not even try.

## I got banned for something that wasn't against the rules.
There's a high chance that what you did was definitely against the rules. Whilst the rules are not explicitly stated, a general rule of "common sense" is in place. If you break a rule that does not fall under this category, people will warn you about it before taking action.


# Feel free to contribute to this and add anything else that may seem important.
