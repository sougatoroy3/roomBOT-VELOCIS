# Room Kit Mini Webex Bot
This is a Webex bot that interacts with a Room Kit Mini device. It can perform various tasks by interacting with the CISCO Device and with the users. This bot has been made interactive making it engaging for the users.

## Functions
<br/>-> Can greet everyone
<br/>-> Get personal details of the user
<br/>-> Provde the details of the space it has been added to
<br/>-> Check the bookings 
<br/>-> Book a room
<br/>-> Check the room status
<br/>-> Check system diagnostics
<br/>-> Check camera details
<br/>-> Check people count
<br/>-> Check proximity services
<br/>-> Check network details
<br/>-> Check system unit details
<br/>-> Check standby state
<br/>-> Check google meet and microsoft teams availability
<br/>-> Get details of the framework used as a template
<br/>-> Generate a customizable card for the user

### Prerequisites
-> Node.js installed
<br/>-> Webex bot token
<br/>-> Room Kit Mini device with Control Hub Access or IP address and credentials

### Setup
-> Clone the repository
<br/>-> Install the dependencies
    bash

        npm install
Create a .env file and add the following variables

        WEBEX_BOT_TOKEN=<your_webex_bot_token>
        ROOM_KIT_MINI_IP=<your_room_kit_mini_ip>
        ROOM_KIT_MINI_USERNAME=<your_room_kit_mini_username>
        ROOM_KIT_MINI_PASSWORD=<your_room_kit_mini_password>
Start the bot
    bash

        node index.js
