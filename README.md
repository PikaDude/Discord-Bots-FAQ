<!-- This here are links used in the document. They won't be visible in the document and can be used as follows -->  
<!-- [Link] -->  
<!-- [Other text][Link] -->

<!-- Support/Tutorial sites -->  
[Codecademy]: https://www.codecademy.com/  
[StackOverflow]: https://stackoverflow.com/  

<!-- Discords -->  
[The Coding Den]: https://discord.gg/rXMFcwk  
[Discord API]: https://discord.gg/discord-api  

<!-- Discord pages -->  
[Discord API-List]: https://discordapi.com/unofficial/comparison.html  
[Discord API-Documentation]: https://discordapp.com/developers/docs/topics/community-resources#libraries  
[Your Apps]: https://discordapp.com/developers/applications/  

<!-- Other pages -->  
[Best Discord Bot Practices]: https://github.com/meew0/discord-bot-best-practices  
[Digital ocean offer]: https://m.do.co/c/883e6bb18ff1  
[homepage]: https://discord.bots.gg  

<!-- Sections of this document -->  
[make a bot]: #how-do-i-make-a-discord-bot  
[step 2]: #2-learn-to-use-a-library  
[step 3]: #3-create-a-bot-account

<!-- Start of the visible part. -->  
# Discord Bots FAQ

Hi! This is a go-to link for questions that are often asked about Discord Bots (the server and actual bots). I know that there's a lot here and I don't expect anyone to read *all* of this, but this is more of a cheat sheet than a list of rules, mainly so I can throw links to specific sections for whenever someone asks a common question. If you have any questions about the server, about bots, or anything else, I recommend you check here first before asking.

## How do I make a Discord Bot?
First off you need to know how to code. Creating a bot is not as simple as it sounds, it's not as simple as pushing a button and being done with it. There are many tutorials out there on how to make a Discord bot, so here's another bare bones guide.

### 1. Pick a language
First off you need to choose a programming language. If you already know how to code in a language, go straight to step 2. If you do not know any, I recommend you learn from [Codecademy]. Whatever language you choose is up to you, but most people suggest starting with either Python, Javascript or Ruby. Make sure you also check to see if your language has a supported library (refer to step 2). If you have problems along your journey, refer to websites such as [StackOverflow] for help or ask in the Discord Server, [The Coding Den]

### 2. Learn to use a library
Once you've learn how to code in a programming language, find a library that suits the language you just learnt. A library is a pre-written program that will help you write code to interact with the Discord API. Join the Discord Server titled [Discord API] and choose a channel for the language you know. Please remember that **this server will not teach you how to code**, they will only help you with questions related to the library. [If you're unsure on which library to choose, you can refer to this library comparison, although I will warn you, it is very outdated.][Discord API-List].  
And finally can you find a (probably more updated) list of available Libraries in the [Discord API-Documentation].

### 3. Create a bot account
**Make sure you only do this step if you know how to code and you've found a library to use**, otherwise you'll have a bot that won't be able to do anything. Navigate to the [Your Apps] page and press "New Application". **Make sure you're signed into the right account!**. Give the application a name and click on "create". You can then give it a optional description and avatar. Once you've done that, press the text on the left that reads "Bot". Click on the button that reads "Add Bot" and confirm by pressing "Yes, do it!". Congratulations! You now have a bot account! You can now put your bots token into your code and make your bot come to life. **Please keep your bot token private. Do not share it with anyone and be careful not to push it to GitHub. This token allows anyone to use and abuse your bot so be extremely careful with this! Treat it like a password, it basically is one**.

### 4. Make your bot do stuff
Great! Your bot is now running! It probably won't do anything at this point, so it'd be wise to add some __commands__. Maybe start with something simple such as a "ping" and "pong" command, then start moving onto more complicated features. **Please remember to follow the [Best Discord Bot Practices]**. Have fun!

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
A bot can only be accepted if it is online for most of it's existance. I recommend hosting your bot on a dedicated server, however I'm not going to go into too much detail on that, sorry. But, I recommend you use Digital Ocean. They're pretty reliable, helpful, have a lot of tutorials and have reasonable prices too. Use [this link][Digital Ocean offer] to get $10 in credit on their site

### Something about a clone?
Means you copied the bot off of GitHub or another site. Making your own original bot makes this problem disappear.

### Autoresponse
Means your bot responded to an ordinary message/without prompt. Read the [Best Discord Bot Practices] or just make your bot respond only to commands.

### No description
You gotta put *something* in the description. Also make it accurate, don't lie.

### Not responding to the listed prefix
The bot wasn't responding to any commands with the listed prefix. The bot *was* online, just unresponsive. Either you got the prefix wrong or you changed it after you requested your bot to be listed.

## I've been waiting for a while, why isn't my bot verified yet?
It takes a while for your bot to get verified. From a few days to several weeks. Remember, you're not the only person in the world who wants to get their bot added to the list, there are hundreds of bots in the queue, and each one needs to be manually checked to see if it fits in the guidelines. Please be patient, asking about it or pinging Moderators or Helpers will decrease your chances of it getting verified.

## How can I add my bot to the bot list?
Go to the [homepage], press login in the top right, authorize yourself, press the plus button in the top right ("Add a Bot"), and enter the required information. The information required that is often asked about is:

### What is a client ID?
This is your bots ID. It is displayed on the bots application page. If you do not know what that is, I suggest you read [`How do I make a Discord Bot?`][make a bot], specifically [step 3].

### What is a prefix?
A prefix is a character or characters that appear before every bot command. Examples of common prefixes are `!`, `?` and `-`. If your bot does not have a prefix, then it will not be approved. You must follow the [Best Discord Bot Practices].

### What is a library?
Read [`How do I make a Discord Bot?`][make a bot], specifically [step 2].

## How do I invite my bot / How do I make an Invite URL / How do I add my bot to my server?
The simplest URL is as follows, replace `REPLACEME` with your bots client ID found on your bots application page. If you do not know what that is, I suggest you read [`How do I make a Discord Bot?`][make a bot], specifically [step 3].
`https://discordapp.com/oauth2/authorize?client_id=REPLACEME&scope=bot`

There are of course other ways to make a invite-url for your bot. Discord even offers a own OAuth link generator that you can use.  
Go to `https://discordapp.com/developers/applications/:id/oauth` (replace `:id` with your bots ID), select `Bot` and the permissions you want your bot to ask for.  
Do not just select `Administrator`. This is a very bad practice to do and should be avoided.  
When you set all permissions your bot should have, copy the link from the text-field.

# Feel free to contribute to this and add anything else that may seem important.
