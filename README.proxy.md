# arcadia-proxy

A proxy server allowing connection to official Battlefield 1943's backend services via RPCS3.

**Note**: This project is not affiliated with EA or DICE.

## Notice

**Using this tool could be a violation of Battlefield 1943's terms of service and lead to account penalties, including bans. We accept no liability for any repercussions of its use.**

## Setup

### PS3

1. Start Battlefield 1943 and register an EA account, note down the credentials
1. Dump your Battlefield 1943 game and license files [as described here](https://wiki.rpcs3.net/index.php?title=Help%3ADumping_PlayStation_3_games)

### RPCS3

1. Install your dumped Battlefield 1943 game and license files
1. Register/Login to [RPCN](https://wiki.rpcs3.net/index.php?title=Help:Netplay)
1. Right click on Battlefield 1943 in RPCS3 and select `Change Custom Configuration`
1. In network tab, set Network Status to `Connected` and set PSN Status to `RPCN`
1. Set IP/Hosts switches to `beach-ps3.fesl.ea.com=127.0.0.1`

## Usage

1. Download and extract the latest proxy release
1. Open `appsettings.json` and update `ProxyOverrideAccountEmail` & `ProxyOverrideAccountPassword` to your **EA account credentials**, the ones you created on your Playstation 3
1. Start the server executable
1. Start Battlefield 1943 in RPCS3

## Known Issues

* Sometimes login fails, just hit retry. If it still fails, restart RPCS3 and try again
* Some menus may display your RPCN nickname instead of PSN
* Friends list may not work properly