---
ns: PLAYER
---
## SET_PLAYER_WANTED_LEVEL_NO_DROP

```c
// 0x340E61DE7F471565 0xED6F44F5
void SET_PLAYER_WANTED_LEVEL_NO_DROP(Player player, int wantedLevel, BOOL delayedResponse);
```

```
p2 is always false in R* scripts  
```

## Parameters
* **player**: the target player
* **wantedLevel**: the wanted level 1-5
* **delayedResponse**: false = 0-5sec police spawn response time, true = 10-20sec police spawn response time

## Examples
```lua
local player = PlayerId()
SetPlayerWantedLevelNoDrop(player, 5, false) -- 5 star wanted level
```
