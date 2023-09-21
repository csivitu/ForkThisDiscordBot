<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/csivitu/Template">
    <img src="https://csivit.com/images/favicon.png" alt="Logo" width="80">
  </a>

  <h3 align="center">ForkThis Discord Bot</h3>
</p>



<!-- TABLE OF CONTENTS -->
## Table of Contents
  * [Built With](#built-with)
* [Getting Started](#getting-started)
* [Issues](#issues)
* [Contributing](#contributing)
* [License](#license)



### Built With

* [discord.js](https://discord.js.org/)

<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple steps.

1. Open Discord and create a server.

2. Head over to Discord Developer Portal : https://discord.com/developers/applications

3. Go to Applications, click on New Application, and Create An Application.

4. Click on the application created by you, head over to 
Bot -> Reset Token. Copy this token. 

5.Check all three intents under Privileged Gateway Intents. Select the necessary Bot Permissions.

6. Next, click on OAuth2, copy the CLIENT ID.

7. Go to URL Generator (under OAuth2), select applications.commands

8. Copy the Generated URL. Open a new tab on your browser and paste this url.

9. Select the server and Authorize.

10. Voila! The bot has been added to your server.

11. To use the discord.js Library, run the following commands in your terminal
```sh
npm init -y
```
```sh
npm install discord.js
```
```sh
npm install -g nodemon
```
```sh
npm install dotenv
```

12.Create a .env file in your code editor and add the following :

BOT_TOKEN = (Token obtained in step 4)
CLIENT_ID=(Client ID obtained in step 5)
GUILD_ID= (Server ID of Discord Server)

13. To run the bot, run the following commands in your terminal

to register slash commands:
```sh
node src/register-commands.js
```

to run the bot:
```sh
node src/index.js
```


<!-- ISSUES -->
## List of Issues
Easy: 
1. 'resources' message: links haven't been added properly, some unclickable
2. message.reply for 'help' and 'resources' : adding the embed : syntax error

Medium:
1. prize pool embed : syntax error in footer
2. repos list embed : syntax error in footer
3. joke api: joke doesn't appear on the screen

Hard:
1. socials button not working
2. react button not working




<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork this repository.
2. Create a new branch: git checkout -b feature/new-feature
3. Make your changes and commit them: git commit -m 'Add a new feature'
4. Push to the branch: git push origin feature/new-feature
5. Submit a pull request.

<!-- LICENSE -->
## License

Distributed under the MIT License.

