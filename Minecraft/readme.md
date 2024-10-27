### RCON into the server with docker
-  docker exec -i container-name rcon-cli
-  RCON must be enabled in the server
-  docker exec -i minecraft-mc-1 rcon-cli

### Restart server with warning


### Whitelist player
## Java
- whitelist add username

## bedrock user on Java server with geyser
- Step 1: visit https://www.cxkes.me/xbox/xuid and enter the bedrock username (without the period that is added by Geyser)
- Step 2: Search for the hexidecimal result and copy it down
- Step 3: You can try just that number instead of the username, but mine was formatted like this
  - XUID Search Result: 000901F4BF5B7415
  - Minecraft XUID: 00000000-0000-0000-0009-01f4bf5b7415
- step 4 would be to add a dash after the first four digits and then paste "00000000-0000-0000-" before the search result to get #the correct format.
whitelist add 00000000-0000-0000-0009-01FBC292F6BF
