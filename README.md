# ![qw-scripts Banner](https://i.imgur.com/68jLFg3.png)

## qw-scripts discord

<https://dsc.gg/qw-scripts>

# qw-crafting
QBCore Customizable Crafting System

# Preview
[https://images-ext-1.discordapp.net/external/hCbD6-O4drzSm7uvaUOWQBWTi7NZOWDcXoFfuiOyUeU/https/i.imgur.com/UxvLsFE.jpg?width=1248&height=676)](https://i.imgur.com/UxvLsFE.jpg)

# Install
- setup your inventory resource in the config under `Config.Inventory`
- also update the inventory config in `html/script.js`
- If you are going to be using [mz-skills](https://github.com/MrZainRP/mz-skills) then you need to add the following config to the mz-skills config file...

```lua
["Crafting"] = {
    ["Current"] = 0,
    ["RemoveAmount"] = 0,
    ["Stat"] = "CRAFTING_ABILITY",
    ['icon'] = 'fas fa-crate-empty', 
 },
```
- follow the rest of the config to setup all of your crafting locations and items
