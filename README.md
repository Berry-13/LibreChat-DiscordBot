# LibreChat-DiscordBot
The LibreChat-DiscordBot is a versatile and user-friendly Discord bot designed to streamline interactions with your LibreChat server. With this bot, you can effortlessly manage the LibreChat server directly from your Discord server, eliminating the need for direct server access. It offers an array of functionalities to enhance your LibreChat experience.

**Bot Capabilities:**

- **/ping**
   
   📞 Ping the bot
   - Quickly assess the bot's latency, displayed in milliseconds.

- **/librechat**
   
   🌐 Explore LibreChat URLs
   - Instantly access key LibreChat resources, including GitHub, Documentation, Discord, and YouTube.

- **/path**

   📂 Configure the LibreChat path
   - Set the path for the LibreChat folder.
   - Utilize either an absolute path format (e.g., `C:\LibreChat`) or a relative path format (relative to the bot folder, e.g., `../LibreChat`).

- **/env**

   ⚙️ Manage the .env file
   - **Download**: Retrieve a copy of the `.env` file from the LibreChat folder.
   - **Upload**: Replace the current `.env` file with a new one. **A backup of the current file will be created**.
   - **Restore**: Restore the backup of the `.env` file and delete the current one.
   - **Example**: Obtain the `.env.example` from the LibreChat folder.

- **/docker**

   🐳 Regular Docker commands
   - **Start**: Start the Docker container.
   - **Stop**: Stop the Docker container.
   - **Update**: Update the LibreChat server.
   - **Status**: Display the status of all Docker containers.

- **/docker-single**

  🐳 Docker commands for `single-compose.yml`
   - Similar to regular Docker commands but specific to the `single-compose.yml` configuration.

- **/local**

  💻 Commands for local LibreChat install
   - **Start**: Start the LibreChat server locally.
   - **Stop**: Stop the local LibreChat server.
   - **Update**: Update the local LibreChat server.

## [Installation](https://github.com/Berry-13/LibreChat-DiscordBot/wiki)
☝️ **Please visit the [Wiki](https://github.com/Berry-13/LibreChat-DiscordBot/wiki) for detailled instruction on how to install and use the bot!**

---

### TL;DR
- Clone or download the repo
- Install the requirements with: `pip install -r requirements.txt`
- Rename `bot_config.py.example` to `bot_config.py`
- Go to the [Discord Developer Portal](https://discord.com/developers/applications) and create an application
- Add your **Bot Token** and **Client ID** to the `bot_config.py` file
- Start the bot with: `python bot.py`
