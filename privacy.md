# Privacy Policy

**Effective Date:** October 18, 2026

### 1. Data we collect
The bot mostly collects User IDs, Message IDs, Server IDs and Channel IDs to perform its functions, we never collects any sensitive data.

### 2. How we use the data we collect
 **Moderation features - Ghost ping detector and Reaction Logging:**
the ghost ping feature collects user IDs(to know who ghost pinged who), Message IDs(To know which message was edited/deleted the reason ghost ping triggered), Server IDs(to know in which server it happened) and Channel IDs(To know where to send the Ghost ping logs). The collected user ids and message ids are deleted after 15 mins, server ids and channel ids are kept so that it can remember where to send logs even after its memory is cleared when the bot restarts, but they are also removed upon running **/ghost ping logremove**. 
the reaction logging feature also collects User IDs(To know who reacted), Message IDs(On which message they reacted), Server IDs(To know in which server they reacted), Channel IDs(To send the logs in the specified channel) AND Emoji IDs(To show the emoji visually in the logs). The collected user ids is automatically deleted once the logs are sent but administrator id is stored seperately that runs the command to enable reaction logging, because to announce who enabled the reaction logs but the admin id is deleted after the announcement. The server IDs and channel IDs are kept  so bot remembers where to send upcoming logs even if its memory is cleared after the bot restarts, but they are also removed upon running **/reaction logging remove**. 

  **Fun & Games - Pokemon Hangman, Guess the Pokemon and Pokemon Mafia:**
Pokemon Hangman collects User IDs(To know who are guessing and calculating their points), Message IDs(so that bot can know its own message to edit whenever a right guess is made), Server IDs(To know in which server the game is going in) and Channel IDs(To send message in the channel where the game is going). The collected data is automatically deleted when the game ends.
Guess the Pokemon feature collects User IDs(To know who created guess the pokemon), Message IDs(To send and pin the message once someone creates a guess the pokemon[the game message is automatically unpinned once the game ends]), Server IDs(To know in which server the game is going) and Channel IDs(To send logs in the specified channel if enabled by Server Administrator, and to know where to send the game embed). The data is deleted once the game ends.
Pokemon Mafia is a mafia game if you seen mafia games in other bots, but if you dont; it collects User IDs(To know the participants and to DM them their role), Message IDs(To keep record of users command and the message they chat with others via other evil teammates in bot's DMs), Server IDs(To know in which server the game is going), Channel IDs(To know where it needs to send messages when people perform actions, victory/defeat embeds). The collected data is deleted when the game ends.

### 3. Data Sharing
We never sell, trade, rent or share your data. We only share data with trusted third party services **Required** to host and run the bot.

**We may update this Privacy Policy any time, when we do, we will announce it in our [Official Server](https://discord.gg/cWj2Mdu8PS)**.