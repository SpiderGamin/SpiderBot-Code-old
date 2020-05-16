# SpiderBot-Code
The bot is still being developed, and has a long way till its done. A lot of the components of this bot are made specifically for my [discord server](https://discord.gg/gRMbZyU), however as time goes on I will work on making it more usable usable elsewhere.

Invite the bot to your server! (link coming soon)

# Setup
<br>Check your version of nodejs by typing `node -v` in the terminal
<br>Make sure you have nodejs v12.0.0 or newer installed
<br>Install discordjs using `npm install discord.js`
<br>Go into the `config.json` file and replace `TOKEN` with your token. Save the file
<br>To run SpiderBot, type `node SpiderBot.js` in the teminal. It should dispay a message saying ``Logged in as <your_bots_username>``

# Bot Usage
<br>The prefix is `&` by default and can be changed in the `config.json` file

## Commands
<br>Key: \<required> [optional]
<br>`botconfig` - Configure the bot using commands (not implemented yet)
<br>`calculate` - Calculate something.
<br>`embed` - Create or use a preconfigured embed.
<br>`info` - Get user or server info
<br>`kick` - Kick a user (the kick part is to be added)
<br>`ping` - Sends 'Pong' in return (soon to have the milliseconds)
<br>`purge` - Bulk delete messages
<br>`sendterm` - Sends the text after the command to the hosts console/terminal

# To Do
* Clean up code
* Add more comments
* Add help command

# Future Plans
Here are some of the future plans
* [ ] Add moderation commands
* [ ] Add configuration commands
* [ ] Add ranking system, out roles, reaction roles, and possibly a verification role system
* [ ] Add economy game
* [ ] Make a documentation (user manuel)

# Done
* Reduced the amount of code
* Combined `embed` and `savedembed` commands into one file.

# Resurces Used
<br>The base code of the bot (largely modifyed by me) - https://discordjs.guide/
<br>I used this to learn JavaScript - [w3.schools.com](w3.schools.com)
<br>[Discord.js Documentation](https://discord.js.org/?source=post_page---------------------------#/docs/main/stable/general/welcome)
<br>Discord.js discord server - https://discord.gg/bRCvFy9

# Credits
[AbacabaTheAbacus](https://github.com/AbacabaTheAbacus) - helped with some of the code (and told me to use `switch` rather than `if`'s)
