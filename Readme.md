# Room Kit Mini Webex Bot
This is a Webex bot that interacts with a Room Kit Mini device. It can perform various tasks such as checking diagnostics, room status, camera details, bookings, network details, and more.

### Prerequisites
-> Node.js installed
-> Webex bot token
-> Room Kit Mini device with Control Hub Access or IP address and credentials

### Setup
-> Clone the repository
-> Install the dependencies
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
