---
ns: PED
---
## SET_PED_MAX_HEALTH

```c
// 0xF5F6378C4F3419D3 0x5533F60B
void SET_PED_MAX_HEALTH(Ped ped, int value);
```

```
sets the maximum health of a ped (can be more than 100) 
```

```
Example:
local ped = PlayerPedId()

AddEventHandler('onPlayerSpawn', fucntion()
  SetPedMaxHealth(ped, 200) -- Now the normal HP (The green bar) can be 200
  SetEntityHealtH(ped, 200) -- Now the ped spawns with 200 HP
end)

```

## Parameters
* **ped**: 
* **value**: 

