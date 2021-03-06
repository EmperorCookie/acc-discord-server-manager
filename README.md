# acc-discord-server-manager
A Discord bot that manages your ACC servers.

# Work in progress
This software is currently under development. I estimate that the MVP will be ready around mid April 2021 and will include everything listed in the features below. Follow this github repository to receive updates. Issues will be used to track feedback and provide support.

# Features
- Manage individual ACC servers through Discord `/` commands
- Runs on your existing ACC server
- All configuration is done through json

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
    1. To add a channel where the bot will listen for community commands, type `/public #channel-name` in the admin channel

# How to use
Use the Discord `/` command context menu as guidance on how to use the bot.

# Licensing
There is currently no license. The plan is to provide a free for non-commercial use license. If your usage of this software is in any way connected to something that makes money, contact me for licensing options, I'm very reasonable.

# Feature wishlist
The following features are in the order they will be implemented in. If you want to request a feature, please do so by creating an issue.

1. Automatically updates itself when a new version is released
1. Manage drivers and entry lists
1. Schedule future events that start and stop servers, and save the results
1. Live weather matching for scheduled events
1. Option to post race results to a Discord channel
1. Championships
1. Public commands system to give more control to the community
1. Custom liveries for managed drivers
    1. Public commands for self management by drivers
1. Public commands to get driver info (cup, category, standings)
1. Public commands to get servers info (name, password, status)
1. Public commands to get event info (schedule, weather, entry list)
1. Ephemeral/temporary ACC servers
    1. Public commands to allow the community to create the servers
1. Secondary agent to manage more than one server with a single bot
1. Fantasy championships where the community gets points based on a championship
