# Mineflayer Minecraft Bot

A Minecraft bot built with Node.js and Mineflayer that can run on Android using Termux.

> Dành cho người dùng Việt Nam: Nếu bạn là người Việt Nam, vui lòng đọc phiên bản tiếng Việt tại đây: [README-vietnamese.md](README-vietnamese.md) 

## Requirements
- Android
- Termux
- Internet
- Node.js
- A Minecraft Server that you are authorized to let the bot join

## Installing Termux
You can install Termux from:
- [F-Droid](https://f-droid.org/packages/com.termux/)
- [Google Play](https://play.google.com/store/apps/details?id=com.termux/)

## Step 1 — Update Termux
Open Termux and run:

`pkg update && pkg upgrade`

If asked `Do you want to continue? [Y/n]`, enter `Y` and press Enter.

## Step 2 — Install Node.js
Run:

`pkg install nodejs`

Check the installation:

`node -v`

`npm -v`

## Step 3 — Install curl
Run:

`pkg install curl`

## Step 4 — Create the bot directory
Run:

`mkdir minecraft-bot`

Then:

`cd minecraft-bot`

## Step 5 — Download the bot from GitHub
Run:

`curl -L https://raw.githubusercontent.com/Moon50112344/Bot-Mineflayer-Minecraft/refs/heads/main/index.js -o index.js`

Check the files:

`ls`

If you see `index.js`, the download was successful.

## Step 6 — Set up Node.js
Run:

`npm init -y`

## Step 7 — Install dependencies
Run:

`npm install mineflayer mineflayer-pathfinder vec3 minecraft-data`

## Step 8 — Configure the bot
Open the file:

`nano index.js`

Find the server configuration section in `index.js` and enter your Minecraft Server information.

After editing:
- `CTRL + O` to save
- Press `Enter`
- `CTRL + X` to exit

## Step 9 — Run the bot
Run:

`node index.js`

The bot will start connecting to the Minecraft Server.

## Stop the bot
Press:

`CTRL + C`

## Run the bot again
Run:

`node index.js`

## Update the bot
Download the latest `index.js`:

`curl -L https://raw.githubusercontent.com/Moon50112344/Bot-Mineflayer-Minecraft/refs/heads/main/index.js -o index.js`

Then:

`npm install`

After that:

`node index.js`

## Quick Setup
If Node.js is already installed:

`mkdir minecraft-bot`

`cd minecraft-bot`

`curl -L https://raw.githubusercontent.com/Moon50112344/Bot-Mineflayer-Minecraft/refs/heads/main/index.js -o index.js`

`npm init -y`

`npm install mineflayer mineflayer-pathfinder vec3 minecraft-data`

`node index.js`

## Common Errors

### node: command not found
Run:

`pkg install nodejs`

### npm: command not found
Run:

`pkg install nodejs`

### curl: command not found
Run:

`pkg install curl`

### Cannot find module 'mineflayer'
Run:

`npm install mineflayer`

### Cannot find module 'mineflayer-pathfinder'
Run:

`npm install mineflayer-pathfinder`

### Cannot find module 'vec3'
Run:

`npm install vec3`

### Cannot find module 'minecraft-data'
Run:

`npm install minecraft-data`

### Bot cannot connect
Check:
- Server address
- Port
- Minecraft version
- Bot username
- Whether the server is online
- Internet connection

## Libraries
- [Mineflayer](https://github.com/PrismarineJS/mineflayer)
- [Mineflayer Pathfinder](https://github.com/PrismarineJS/mineflayer-pathfinder)
- [Vec3](https://github.com/PrismarineJS/node-vec3)
- [Minecraft Data](https://github.com/PrismarineJS/minecraft-data)

## Source
- [GitHub Repository](https://github.com/Moon50112344/Bot-Mineflayer-Minecraft)
- [index.js](https://raw.githubusercontent.com/Moon50112344/Bot-Mineflayer-Minecraft/refs/heads/main/index.js)

<table align="center">
  <tr>
    <td>
      <a href="https://www.tiktok.com/@moon501_vn">
        <img src="https://cdn.simpleicons.org/tiktok" width="40" alt="TikTok">
      </a>
    </td>
    <td width="25"></td>
    <td>
      <a href="https://github.com/Moon50112344">
        <img src="https://cdn.simpleicons.org/github" width="40" alt="GitHub">
      </a>
    </td>
  </tr>
</table>
