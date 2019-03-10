[![Uptime Robot ratio (30 days)](https://img.shields.io/uptimerobot/ratio/m780846363-08d14293cee3e89eed3f2ca5.svg)](https://stats.uptimerobot.com/M1oVZip6q)
[![GitHub release](https://img.shields.io/github/release/jeppevinkel/SCP-Server-List.svg)](https://github.com/jeppevinkel/SCP-Server-List/releases/latest)

# SCP-Server-List
Plugin for SCP:SL server to add them to a list of SCP servers regardless of being verified or not

The latest release can be found here: [Latest release](https://github.com/jeppevinkel/SCP-Server-List/releases/latest)

## Requirements
* [ServerMod2](https://github.com/Grover-c13/Smod2)

## Installation

### Method 1 (Installing plugin)
1. Download the [Latest release](https://github.com/jeppevinkel/SCP-Server-List/releases/latest) of the .dll file
2. Place SCPServerList.dll in your sm_plugins folder
2. Launch the server
3. The server will now add itself to the [server list](https://scpserv.jeppdev.com/) immediately after first server launch

### Method 2 (Without installing plugin)
1. Add `secondary_servers_to_contact: http://scpserv.jeppdev.com/server_auth.php` to your config.txt
2. Make sure you have a verkey.txt in the %appdata% SCP folder. It doesn't matter what the file contains, but at least a single letter
3. Launch the server
4. (Optional) Add `print_mainserver_authentication_error: false` to your config.txt if not verified, to avoid spam in console
5. (Optional) Add `master_server_to_contact: http://scpserv.jeppdev.com/server_auth.php` to your config.txt if it didn't work with the secondary_servers_to_contact

## Debugging
* To enable debugging info in the console add `scpserverlist_debug: true` to your config.txt

## Usage
All server can be seen on [scpserv.jeppdev.com](https://scpserv.jeppdev.com/)



*This update is for Laserman*