# botlibre_discord
The code to use your Machine learning "Botlibre bot" at discord

<h2>It uses</h2>

<li>Botkit: a handy bot building framework</li>
<li>Discord.js: a node module for connecting to the Discord API</li>
<li>Botkit Discord: A connector that allows you to use Bokit and Discord.js</li>
<li>Uptime Robot: A monitoring service that helps keep your bot running 24/7 (OPTIONAL)</li>
  </ul>
  
 <h2>How to setup a Discord bot</h2>
<p>You will need a bot token, to generate one follow these steps:</p>

<ul>
<li>Go to https://discordapp.com/developers and login</li>
<li>Create an application and give it a name and a description</li>
<li>Select "Save Changes" at the bottom right and then navigate to the "Bot" section on the left-hand side.</li>
<li>There, create a bot user by clicking on "Add Bot". After confirming, reveal the token.</li>
<li>Copy and paste this token in discord_token in .env</li>
</ul>
<h3>Invite the bot to your discord server:</h3>
<ul>
<li>Go to OAuth2 section of your developer application</li>
<li>Under SCOPES check bot</li>
<li>Under BOT PERMISSIONS check Manage Roles</li>
<li>Now go to the url generated in the SCOPES section and invite the bot to your server</li>
</ul>
<h3> How to get Bot Libre key </h3>
<ul>
<li>Go to Botlibre.com and sign in with your email and password</li>
  <li>Click on "My Bots"</li>
  <li> click on your bot name </li>
  <li> now you got something like "https://www.botlibre.com/browse?id=32723068" in your url</li>
  <li> "32723068" is your bot id. paste it in .env as botid</li>
  </ul>


<h3>Configuration steps</h3>
<ul>
<li>Install Node.JS</li>
<li>Download the latest bot version from the release tab and unzip it</li>
<li>Go to the config folder, copy and paste the config files</li>
<li>Go back to the root folder, open a terminal here and run these commands: npm install, wait for it to finish then run npm start.</li>
<li> Run "npm install discord.js" , "npm install express" and "npm install request" (if required) </li>
<li>Congratulations, if you did everything correctly you now have bot running.</li>
</ul>

