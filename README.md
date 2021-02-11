# acc-discord-server-manager
A Discord bot that manages your ACC servers.

# Features
* Runs on your existing ACC server
* Acts as a Discord bot with a `/` command interface
* All configuration is done through json

# How to setup
1. Setup the agent
    1. Upload a release to your existing ACC server
    1. Edit `config.json`
    1. Run the agent
1. Create a Discord bot
    1. Point the interactions endpoint URL to the agent
1. Add the bot to your server
    1. In the channel where you want admin commands to be sent, type `/admin`
        * To change the admin channel, type `/admin #channel-name` in the admin channel
    1. To add a channel where the bot will listen for commands, type `/public #channel-name` in the admin channel

# How to use
Use the Discord `/` command context menu as guidance on how to use the bot.

# Feature wishlist
The following features are in the order they will be implemented in. New features may creep into this list and perturb the order without notice.

1. Manage individual ACC servers
1. Automatically updates itself when a new version is released
1. Manage multiple entry lists
1. Schedule future events that start and stop servers, and save the results
1. Ephemeral ACC servers
1. Permission based public commands to give more control to the community
1. Secondary agent to manage more than one server with a single bot
