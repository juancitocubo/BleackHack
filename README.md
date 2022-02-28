# BleackHack-1.18.1

About:

BleachHack is an easy to use, free and open source Fabric Utility Mod for Minecraft 1.17 and 1.18 designed for anarchy servers. BleachHack comes with a clean GUI, a lot of powerful and customizable modules and is frequently updated to have the latest anarchy features, See below for a list of all the features.

Features:

As of 1.2.5

Modules:
AirPlace
Ambience
AntiChunkBan
AutoEXP
AntiHunger
AntiVoid
ArrowJuke
AutoArmor
AutoBedrockBreak
AutoBuild
AutoCraft
AutoEat
AutoFarm
AutoFish
AutoIStackDupe
AutoLog
AutoParkour
AutoReconnect
AutoRespawn
AutoSign
AutoSteal
AutoTool
AutoTotem
AutoWalk
BetterCamera
BetterChat
BetterPortal
BlockHighlight
BookCrash
BowBot
ClickGui
ClickTp
ColorSigns
Criticals
CrystalAura
DeathExplorer
DiscordRPC
Dispenser32k
ElytraFly
EntityControl
EntityMenu
ElytraReplace
ESP
FakeLag
FastUse
Flight
Freecam
Fullbright
Ghosthand
HandProgress
HoleESP
Jesus
Killaura
LiquidFiller
LogoutSpot
MouseFriend
Nametags
NewChunks
Nofall
NoInteract
NoKeyBlock
NoRender
NoSlow
NoSwing
Notebot
NotebotStealer
NoVelocity
Nuker
OffhandCrash
PacketFly
Peek
PlayerCrash
Reach
RotationSnap
SafeWalk
Scaffold
Search
SecretClose
ShaderRender
Sneak
Solidify
Spammer
Speed
SpeedMine
Sprint
StarGithub
Step
StorageESP
Surround
Timer
ToggleNotify
Tracers
Trail
Trajectories
UI
Xray
Zoom
Commands:
$betterchat
$bind
$ci
$clickgui
$clip
$customsign
$enchant
$entitymenu
$entitystats
$friends
$gamemode
$give
$help
$invpeek
$nbt
$notebot
$peek
$prefix
$rbook
$rename
$rpc
$say
$server
$setting
$skull
$spammer
$terrain
$toggle
$watermark
Changelog:

1.2.5:
Fixed Optifine compatibility
Fixed your modules being able to reset when restarting Minecraft
Fixed AutoFish if multiple players were fishing next to each other
Fixed Killaura Projectiles not working
Fixed AutoEat not disabling correctly
Fixed a typo in AutoEat
Moved Armor stands from StorageESP to ESP and added them to Tracers
Increased the render limit of Search to 3000
Removed the bundled Fabric api modules so the jar is now ~150kb smaller
1.2.4:
Fixed Optifine crashing your game
Fixed ChunkSize being able to crash your game
Fixed the game crashing if you had velocity enabled in meteor
Fixed the game crashing when using the --release argument in java
Fixed Xray not working with Fabric API
Prevented the game from crashing when trying to open UI on the main menu
Fixed $toggle not working correctly
Updated the description of AntiHunger to make it clearer that you slide
Added the BH version to the credits screen and updated my name/description
Moved the resource url to https://bleachhack.org/resources/
1.2.3:
Added BlockHighlight
Added ToggleNotify
Added AutoCraft
Added AutoEat
Improved Nametags
- Replaced Nametags Armor setting with Inventory to make it simpler
- Added an Inventory setting to mobs and animals
- Added a armor stands option
- Made rendering a bit cleaner
Rewritten ESP, StorageESP and BlockHighlight
- Added a new shader mode to all three
--- Shaders now don't conflict with each other or reset when you F3+T
--- Added a shader fill option
- Improved performance of ESP and StorageESP
- Removed the "Donkeys" option from ESP because donkey dupes are dead
Fixed compatibility with other utility mods on fabric loader 0.12.0+
Made the UI gui cleaner and moved the edit UI button to the top of the clickgui
Fixed lag spikes when loading chunks (kinda fixed, thanks sudofox)
Autobuild can now use your entire inventory + add multiple block support
Moved blocks a bit over in the Notebot gui to make Iron_Xylophone not lay over the block
Improved Performance by removing all reflection
1.2.2:
New Account Manager with Microsoft account support!!
Added NoInteract (thanks CUPZYY)
Replaced AutoThrow with AutoEXP
Added AutoIStackDupe (temporary)
Added $server
Improved the colors/prefix of BH chat text and some commands
Added a seconds setting to BetterChat Timestamp
Improved UI
- Split all the info things into different windows
- Added UI Durability
- Added Inventory viewer (thanks Vp)
- Made the colors between red and green smooth
- Added Vertical mode to UI Armor
- Fixed ChunkSize spamming your logs
- Fixed a crash related to ChunkSize
Improved Search
- Added a LogBlocks setting
- Fixed it being completely wack on box mode
- Made it not freeze your game if it finds too many blocks
Added a hitmarker to trajectories and made it very sexy
Fixed some watermark issues
- Fixed the game crashing if you set $watermark to one word
- Fixed "$watermark reset" not saving the watermark
Made $peek work with bundles
Fixed Peek Containers on name mode showing the entire tooltip
Fixed Ambience spamming your logs
Replaced EcmeBypass with AntiDismount in EntityControl
Removed ecme mode from Nofall
Removed motion sickness mode from Zoom
Made $enchant work without a level in the command
Fixed $notebot convert not saving the converted files
Fixed mode settings being able to load invalid modes
The command prefix now can't be set to empty
Made password textboxes less buggy
Made it more obvious that $enchant $give $gm & $skull are creative/clientside only.
All windows now use smooth mode so you don't need to double click to interact with inactive windows
1.2.1:
Fixed the game crashing when trying to run bleachhack offline
Fixed the game freezing when loading some things
- Fixed freezing when starting the game
- Fixed freezing when loading the BleachHack title screen
- Fixed freezing when loading the credits screen
Improved Notebot
- Fixed Notebot trying to tune blocks other than noteblocks
- Made it show if you're missing noteblocks in NoInstruments mode
- Made it measure distance form your eyes instead of feet
- Made it find noteblocks outwards instead of going in sequential order
Fixed a lot of modules crashing the game when toggling them in the main menu clickgui
Fixed some $watermark issues
- Fixed $watermark text throwing an error if the watermark was 1 word long
- Fixed $watermark reset not saving the watermark
Made the BleachHack settings screen accessible from mc settings
1.2:
Added $watermark
Added AutoBedrockBreak
Added SecretClose
Added AutoFish
Added Reach
Added a BleachHack Options screen
You can now see other BleachHack players in the player list
Fixed Nametags showing your own ping and gamemode for all players
Fixed Ambience being completely broken
Fixed Iris compatibility
Added a new (very sexy) update screen
Improved Avoid
- Renamed to Solidify
- Added Cobweb, Berry bushes and Honey block settings
Rewritten CustomChat
- Renamed to BetterChat
- Removed KillText
- Added Timestamp
- Added Filter
- Added ChatEncrypt and ChatDecrypt
- Improved $betterchat command
- Fixed the suffix being wrong when you reset it
- Made all the chat things work in messages
Improved NoRender
- Added NoRender Gui Background
- Split some world things into Entities and Particles categories
--- Added NoRender Fireworks in Particles
--- Added NoRender Minecarts, Snowballs & Xp Orbs in Entities
Combat module fixes
- Fixed AutoLog Player mode logging out when seeing a fake player
- Fixed BowBot, CrystalAura & Killaura trying to target some invalid/fake entities
- Fixed CrystalAura Blacklist and Raycast settings
- Optimized CrystalAura damage checks
Improved AutoReconnect
- Fixed it sometimes reconnecting to the wrong server
- Fixed the reconnect buttons not being positioned correctly when the disconnect text was multiple lines
- Removed the decimals from the reconnect countdown
Added a y offset setting to NewChunks
(somewhat) fixed Vp's sneak
Fixed nuker not being able to mine underwater plants
Added the ability to get/copy the nbt of the entity/block you're looking at in $nbt
Fixed the elapsed time on the discord rpc stuttering
Fixed bookcrash crashing the game
Fixed AirPlace and fixed AutoParkour rendering
Fixed LogoutSpot players not being removed when they log in
Fixed Nuker ruining your fps
Fixed NoRender skylight literally making skylight 1000x worse
Cleaned up and improved PacketFly with vehicles
Made friends instantly update on the tablist when you add/remove them
Made all settings save even if you're not in a world
Added proper punctuation to all module descriptions
Made the title screen tabs be smaller to fit the screen if necessary
Fixed the $bind command using uppercase in the syntax
Switched TAB to finish the current word instead of going to the next word the command suggester
Increased max speed strafe value in Speed to 0.55
Fixed several IO memory leaks
Removed all default binds except clickgui
Removed the server scraper and server cleanup
Slightly changed the BleachHack title screen colors
1.1:
Added DeathExplorer
Added NoSwing
Added Avoid
Added AutoFarm
Added AutoCraftDupe (1.17)
Added Sneak
Removed AutoIStackDupe and MountBypass
Removed $dupe old (removed it entirely on 1.17.1)
Improved BowBot
- Made it more accurate on moving entities
- Made it able to shoot crossbow
- Added a Raycast setting
- Added target settings for players, mobs and animals
Added Jesus Solid mode
Added a credits screen
Fixed BetterCamera distance only working when cameraclip is enabled
Fixed some modules kicking you when pulling items from your inventory
Fixed AutoParkour trying to jump into 1 block tall spaces and made it able to climb ladders
Fixed Discord rpc wasting space by unpacking to a different file on every startup
Fixed Dispenser32k reverting 32ks
Improved $clip
- Made it work with vehicles
- Merged $clip v & $clip h into $clip <x> <y> <z>
- Added $clip up and $clip down
Added a full command suggestion system
Made UI windows attached to the bottom of the screen move up when chat is open
Fixed account manager not saving correctly after deleting an account
Fixed $help not working with all command aliases
Fixed $rbook not working with more than 100 pages
Improved Ambience Weather and Time
- Fixed it always freezing time even when the time setting was off
- Fixed the sky flickering when rain was starting/ending
- Made the world weather turn back to the real weather when turning off custom weather
Fixed RotationSnap Arrow Move sometimes not working
Fixed NoVelocity mixing up horizontal and vertical velocity in explosion knockback
Fixed AntiHunger, Flight and NoFall spamming console in 1.17
Fixed spammer always sending a message when entering a new dimension
Fixed Tracers jittering when the game is paused
Improved Nuker
- Added Softest order and fixed hardest being reversed
- Added a RangeHighlight setting
- Added a Shape setting
- Added a Raycast setting
- Made the range extrude out of your eyes instead of feet
- Fixed it trying to mine cave air and void air
- Fixed it trying to mine unbreakable blocks in survival
- Fixed it calculating distances from your feet instead of eyes
Improved Peek
- Fixed it not working on 1.17
- Made it able to draw map icons in map peek
- Slightly centered contianer items
Fixed the game crashing when trying to read corrupted json files
Fixed all overlays double drawing on 1.17
Improved the default EntityMenu entry names
Fixed Nametags jittering when the game is paused
Fixed and improved Criticals
- Fixed it not working on 1.17
- Fixed it not working while sprinting
- Added a FullJump mode
- Fixed it trying to crit while climbing, having blindness or riding a vehicle
Fixed NoSlow InventoryMove making your pitch go crazy on 1.17
Added a Projectiles setting to Killaura
Improved RenderUtils performance significantly using frustum checks (1.17+)
Replaced the placeholder mod icon
Fixed EntitySpeed trying to move work with minecarts
Improved collision detection in AntiVoid Vanilla, ArrowJuke & EntityControl AntiStuck
Added respawn anchors to surround blocks
Made the clickgui windows closed by default
1.0.1:
Made the title splash slightly bigger
Reverted to the old AntiChunkBan to fix inertia compatibility
Fixed optifine compatibility with shaders
Fixed Dispenser32k not working on looking mode
Fixed UI windows not detaching from windows that were hidden
Fixed UI ChunkSize not updating when staying in the same chunk
Fixed Notebot not being able to download song due to a bad entry

Updated the 1.17 version to 1.17-pre5
1.0:
Removed Blockparty (rip)
Removed Donkey dupe buttons
Updated AntiChunkBan to bypass bookbans
Added LiquidFiller
Added NewChunks
Added movable UI
Added BetterCamera (thanks CUPZYY)
Added $terrain
Improved AutoBuild
- Added Wither, WitherH, IronGolem, SnowGolem and NomadHut
- Fixed it interacting with the world when selecting where to place the build
- Added a repeat setting
Improved Surround
- Added a option to airplace/skip instead of always placing support blocks
- It can now pull blocks from your entire inventory (including offhand)
- Added block select setting so you can use any unexplodable block
Improved Xray
- Add Opacity option
- Added HideSurface option
Improved LogoutSpot
- Added a ghost toggle in LogoutSpot (thanks FloGo)
- Fixed the logout players not spawning when re-enabling LogoutSpot
Improved ESP/StorageESP/Tracers
- Fixed StorageESP on shader mode not rendering full blocks
- Fixed StorageESP on shader mode not rendering blocks outside the tile entity render distance
- Fixed Tracers and ESP on box mode not being smooth on moving entities
- Changed ESP and StorageESP shader thickness to full numbers to prevent the outline being dark
- Fixed StorageESP with Optifine
Improved Scaffold
- Fixed Scaffold not working in certain cases if filter mode was on
- Made Scaffold able to pick blocks from your entire inventory (including offhand)
- Fixed Scaffold placing 2 support blocks when air placing
Improved CrystalAura
- Fixed CrystalAura targeting all living entities when mob target mode is on
- Fixed CrystalAura explode targeting all living entities
- Fixed several problems with AntiWeakness
Improved Nametags
- Fixed them not rendering through certain block entities
- Fixed them not drawing through walls in 1.17
- Made Nametag curse enchantments "Cv" and "Cb" in english so they are distinguishable when on items
Added $clip
Fixed flight sometimes disabling your ability to fly in creative
Removed default binds from CrystalAura, EntityControl and PacketFly
Fixed $rpc only saving the first word of the entered status
EntityControl can now control pigs and striders without food on a stick
Made commands dump the stacktrace in chat when an exception is caught
Fixed DiscordRPC still using the B15 image
Split NoRender into overlay and world categories
Improved list settings
- Fixed them not removing the default item from the item pool
- Made them show available items even if the search field is empty
Improved block placing
- Optimized the amount of inventory packets used when switching slots
- Made all block placing switch back to your previous slot
Improved the EntityMenu edit screen
- Added buttons to switch between normal, suggest and open url mode
- Fixed weird behavior when two entries had the same name
- Fixed EntityMenu using an old command in its description
Fixed AutoBuild sending 2 rotation packets when placing rotational blocks
Fixed a bug with some keyboards that caused unbound modules to toggle randomly
Fixed modules being able to be bound to escape
Fixed downloading notebot songs not working
Added a basic command suggestion system
Made portals purple in Search
Fixed fake players not copying the outer skin layer of the real player
Fixed the main menu "BleachHack" text jittering when moving the window
Fixed HandProgress removing the item swap animation and added a NoAnimation setting
Moved LogoutSpot to Render, AutoSteal to Player and Renamed PlaceInAir to AirPlace
Rounded UI Lag-Meter to 2 decimals and fixed it spazzing out
Fixed AutoLog OneHit mode not working as intended
Added $spammer and fixed spammer typo
Replaced the one unicode character in the default customchat suffix
Fixed notebot stealer sometimes not saving songs
Fixed AutoSteal showing the items backwards on project mode
Fixed shadows on world text when viewed at certain angles
Improved the output of $nbt set, fixed it not parsing nbt with spaces and made it dump the nbt error if it couldn't parse the nbt
Fixed $rename not adding spaces
Made friends appear blue in the tablist
Fixed updater not working with mc versions that had a space in them

Updated 1.17 version to 1.17-pre1
