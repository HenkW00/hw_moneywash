## HW Scripts - Advanced Money Wash

## Description
This Advanced Money Wash script allows for an immersive money laundering experience within FiveM, designed specifically for ESX servers. This script introduces multiple stages of money laundering, each requiring player interaction, skill checks, and strategic use of in-game resources.

## Author
- HW Development | HenkW

## :tools: Requirements
- ESX Server
- OX lib
- OX Inventory
- qtarget
- HW Utils

## :globe_with_meridians: Requirements Download links
- [ESX Server](https://github.com/esx-framework/esx_core)
- [OX Lib](https://github.com/overextended/ox_lib)
- [OX Inventory](https://github.com/overextended/ox_inventory)
- [qtarget](https://github.com/overextended/qtarget)
- [HW Utils](https://github.com/HenkW00/hw_utils)

## :white_check_mark: Features
- Multi-stage money laundering with interactive tasks.
- Configurable settings for security features such as alarms and lights. --> Currently in BETA
- Integrated skill checks to enhance player engagement and challenge.
- Support for multiple jobs, enhancing roleplay elements.
- Utilizes lib for in-game notifications and supports external logging via Discord webhooks for administrative monitoring.

## :wrench: Script Configuration
**Lang**:
- Default language for script is "en". Please ensure 'setr ox:locale "en"' is present in youre server config file.
**Debug:**
- Enable debug mode to receive detailed logs during operations.
**Whitelisted:**
- Toggle whether only specified jobs can interact with the laundering processes.
**AllowedJobs:**
- Define which jobs can launder money (e.g., 'police', 'ambulance').
**WashDuration:**
- Time in seconds that each stage of money laundering takes.
**Webhook:**
- Discord webhook URL for sending operational logs.

## :wrench: Download & Installation
Follow these steps to set up the MoneyWash script on your ESX server:

1. **Download the Files**: Download the script files from the provided source.
2. **Copy to Server Resource Directory**: Place the `hw_moneywash` folder in the server resource directory.
3. **Update `server.cfg`**: Add the following line to your `server.cfg` file:
    ```cfg
    start hw_moneywash
    ```
4. **Start Your Server**: Restart or start your ESX server to load the `hw_moneywash` resource.

If help is needed, you can contact me via discord.
Link for that you can find in console upon restarting the script, otherwise just search for HenkW00 on google/github/CFX

Enjoy the script, I hope you like it! <3
