# ThreadBot

A basic app that replies to people who should be posting in thread. 

1. Install to Workspace - https://ec2.briansboltbots.com:3007/slack/install
2. Create a custom emoji called :threadbot: - feel free to use https://emoji.slack-edge.com/TTDEQL98C/threadbot/9c2119ea0c040ee8.png
3. Add Threadbot app to any channels where you want Threadbot to reply to messages
4. React to any message with :threadbot: and then remove the reaction. Threadbot listens for the REMOVAL of the :threadbot: emoji, and replies to the message with a gentle reminder to reply in thread
