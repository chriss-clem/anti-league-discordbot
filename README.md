# anti-league-discordbot
harrasses imbeciles for playing league of legends

Note: venv is only compatible with unix right now
ill make one for windows soon

## Running

First set TOKEN and GUILD_ID in the .env file<br>
Ensure that Presence Intent and Server Members Intent are enabled
in the bot page of your discord developer portal

Then execute <code>run.bat</code> or <code>run.sh</code>


On startup, the bot will create a channel called "channel-of-shame" if not
already created. In that channel, the bot will harrass anyone who
is playing league and has Activity Status enabled.
(By default, bot will @ the league player with a message insulting
them for playing league)


## Commands 
*You need server administrator to run commands*<br>
**$zeroTolerance** enable/disable - if enabled, anyone who plays league
will be permanently banned from the server. Disabled by default.

