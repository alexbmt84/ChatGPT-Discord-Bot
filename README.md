# ChatGPT-Discord-Bot
Just a fun ChatGPT bot created using OpenAI API.

<h1>How to use the bot ?</h1>

<h2>First of all, you'll need to initialize a project and create a ".env" file in the root folder.</h2>

<h3>You can as well install discord.js and an openai dotenv by typping this command in the terminal :</h3>

```bash
npm install discord.js openai dotenv
```

This is how your .env file needs to look like :

```javascript
DISCORD_TOKEN = // Your Token
OPENAI_ORG = // Your OpenAI Organisation ID 
OPENAI_KEY = // Your OpenAI API Key
```

Then, you'll need to : 

- Create a Discord server.
- Login into your Discord account following this URL : https://discord.com/developers/applications.
- Create an application and a new bot token.
- Login into your OpenAI account to get your API Key and Organisation Key.
- Link the Discord token and OpenAI Keys into your .env file.
- Start the server by typing the command : 

```bash
node .\index.js
```

<b>Enjoy...!</b>
