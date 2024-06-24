[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/template/xyquaG?referralCode=RDF68R)

Drag and drop 24/7 Discord bots (Discord.js) integrated with low-code no-code backend tools like Buildship, FastGen, Xano or 3rd party serverless endpoints. Hosted on Railway a 24/7 low-code no-code instant deployment plaform.

## Railway Variables

1. `GATEWAY_INTENTS`
Make a comma-separated list of these values, ie: `Guilds, GuildMembers`.

- Guilds
- GuildMembers
- GuildModeration
- GuildIntegrations
- GuildWebhooks
- GuildInvites
- GuildVoiceStates
- GuildPresences
- GuildMessages
- GuildMessageReactions
- GuildMessageTyping
- DirectMessages
- DirectMessageReactions
- DirectMessageTyping
- MessageContent
- GuildScheduledEvents
- AutoModerationConfiguration
- AutoModerationExecution
- GuildMessagePolls
- DirectMessagePolls

Source: [https://discord-api-types.dev/api/discord-api-types-v10/enum/GatewayIntentBits](https://discord-api-types.dev/api/discord-api-types-v10/enum/GatewayIntentBits)

2. `CLIENT_ID`
Go to Discord Developer Portal > Select your app > General Information > Copy Application ID.

3. `TOKEN`
Go to Discord Developer Portal > Bot > Token (Copy or Reset to copy).

4. `INTERACTION_ENDPOINT`
This is the URL for where you want to capture and process interactions.

[https://discord.com/developers/docs/interactions/receiving-and-responding#interaction-object
](https://discord.com/developers/docs/interactions/receiving-and-responding#interaction-object)   

5. `MESSAGE_ENDPOINT`
This is the URL for where you want to capture and process messages.

[https://discord.com/developers/docs/resources/channel#message-object
](https://discord.com/developers/docs/resources/channel#message-object
)

6. `PORT`
The default value is 3000 if blank. This is the port used for the server.
