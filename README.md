# All Synapse Z Custom Functions & How to use it!!

## All Functions
##      \\/

## syn.toast_notification
### Creates a custom notification, Arguments:
```lua
Type -- Icon types
Name -- Title name
Text -- Description Text
Duration -- the name explains itself
```

## -- syn.rpc --

## -- syn.rpc.set --
### Custom rich presence for your discord (only works on bloxstrap uhh i think!!!), Arguments:

```lua

syn.rpc.set({
    ApplicationId = "", -- most important yet, you need to create an application on discord.dev then get the app id
    State = "", -- displays what are you doing currently
    Details = "", -- more detail about the stuff you are doing.
    StartTimestamp = 1, -- useless
    EndTimestamp = 0, -- useless
    LargeImageKey = "", -- useless
    LargeImageText = "", -- useless
    SmallImageKey = "", -- useless
    SmallImageText = "", -- useless
    PartyId = "", -- idk how tto use this zzzzzzz
    PartySize = 0, -- useless
    PartyMax = 0, -- useless
    MatchSecret = "", -- useless
    JoinSecret = "", -- useless
    SpectateSecret = "", -- useless
    Instance = 0 -- roblox instances i thinK!!!!!!!
})

```

## -- syn.rpc.remove --
### Removes ur rich presence on the discord (if you have one), Arguments
```lua
No Arguments
```
# \\/

## -- syn.killprocess --

### Kills your roblox process, Arguements:
```lua
No Arguments
```

## -- syn.protect_gui --
### Protects your gui from findfirstchild attacks yap yap yap yap
```lua
syn.protect_gui(
    --> Instance <--
)
```

## -- syn.clear_teleport_queue --
### the name explains itself
```lua
syn.clear_teleport_queue(
    --> string <--
)
```
