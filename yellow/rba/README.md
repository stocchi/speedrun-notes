# Yellow RBA (no underflow) route by entrpntr
[original guide](https://pastebin.com/XScRtwTr), credit to krazyd4n for several seconds of improvements to the route
## Intro
- [TID Manip]()
	- yellow_gfskip_intro0_title_newgame_oakreset_gfskip_intro0_title_backout_title_newgame_oakreset_gfskip_intro0_title_newgame: 0xC5E6 (50662)
  - TID manip puts HM02 and TM30 in Pewter glitch mart    
- Choose 1 char player name ("A")
- Rival name: BLUE (pre-set)
- Set options in-game to Fast/Off/Set

## Rival

- Skip PC potion
- Get Pikachu and don't nickname it
- Battle rival, spam Thundershock
  - losing is slightly faster

## Parcel quest
- Remember to hold B to walk through Pikachu
- Run from all encounters
- Go behind Oak when delivering the Parcel


## Viridian Mart
- Buy Poke Ball x5
- Backtrack to Route 1 to catch a Pidgey (run from Rattatas)
	- NOTE: Corner bonk between the ledge and Pikachu for style points
- Immediately chuck balls at L2-L4 Pidgeys
- Thundershock L5-L7 Pidgeys before catching
- Give Pidgey a 1 char nickname ("A")

## Viridian Center
- Deposit Pikachu, then heal to set warp point
- Watch Old Man catching tutorial, then head to Route 2

## Forest Manip
- [Manipulate no encounter Forest](https://www.youtube.com/watch?v=KDRDvVE3VN4)
  - 54/60 for the manip to work
- Make sure to not load the final Bug Catcher before the next manipulation
- End of manip is different from YNSC ("A" vs "ASH" affects the manip after picking up Potion)

## Deathfly Manip
- [Manipulate a L9 Pidgeotto encounter in front of the last Bug Catcher](https://www.youtube.com/watch?v=DoPt1pxHPTo)
  - 47/60 for the manip to work
  - 11/60 for a L8 Pidgey (can still 0HKO depending on your Pokemon)
- Buffer down in move menu with all Pidgeys (works even without a 2nd move)
- Buffer select in move menu with all Rattatas
  - if you don't die first turn, spam a move until you die to get the deathfly glitch
- Same as YNSC

## THE Manip
- [Manipulate a specific movement pattern from the next NPCs](https://www.youtube.com/watch?v=DonALfmjZOk)
	- 27/60 for the manip to work up to using the Town Map, hitting one of the first 4 textbox frames is ~81% for the bird to move left
- Stop Movement for ~6 frames to allow bird to start moving left, then hold right
- [Adjacent frames](http://pastebin.com/raw/qBT86ks0)
	- listed early to late, each is a 2 frame window, target = FE
	- use this to troubleshoot your failed manips
- Same as YNSC


  Backup movement: backup options for wrong [NPC](https://gunnermaniac.com/pokeworld?map=1#53/182) movement without needing to re-save:
- UP/RIGHT  = [U11, R2, U3  (A @ U8/U10/R1)](https://gunnermaniac.com/pokeworld?map=1#53/185/SRRRRRRUUUUUUUUAUUAURARUUU)
- DOWN/LEFT = [U13, R2, U1  (A @ U1/U9/R1)](https://gunnermaniac.com/pokeworld?map=1#53/185/SRRRRRRUAUUUUUUUUAUUUURARU)



## Forest Mart
- Buy
 - Max Repel x1 (slot 3)
 - Bicycle x23 (slot 2)
 - Bicycle x91 (slot 2)
 - scroll down
 - Once you see "COIN" on top, you need to get past 4 click items
   - click items require pressing B **once** whenever their name prints to continue scrolling
 - 6F x7 (2 under ultra ball)
 - ??????? (Surfboard) x1 (same slot as 6F)
 - Master Ball x99 (same slot as Surfboard)
 - TMTRAINER x1 (1 slot above Masterball)

## Route 2
- Swap Poke Ball (slot1) with bottom Bicycle (slot5), get on Bike 1 above
- Bike to [jack tile](http://extratricky.com/pokeworld/rb/1#60,142) and turn to face left, flash TMTRAINER (2 under ???)
 - moving left one tile is fine
- Unjack and pick up HP Up (skip jingle if not slow)
- Go through gate and WALK to next [jack tile](http://extratricky.com/pokeworld/rb/1#68,113)
  - this jack softlocks if on bike
- flash TMTRAINER, go up 1 tile and buffer menu
 - internal direction changes to UP if buffered
- Swap HP Up (1 down) with Potion (2 above bike)
- Use HP Up but backout on party screen ("medicine re-jack")
- Bike past Diglett's Cave to other side of r2, unjack
- Grind for an encounter in grass
- Use 6F (2 under bike), unjack, bike to Pokemon Center and heal (left flower's row)
- Walk to tile (http://extratricky.com/pokeworld/rb/1#57,78) and flash items, continue walking to Pewter Mart

## Pewter Mart
- Sell:
	- TMTRAINER x2 (2 under ???)
	- Master Ball x3
- Buy:
 - scroll down
 - Once you see "Gold Teeth" on top, you need to get past 4 click items
	- Jack x1 (2 under the second glitch item, 1 under tm05)
	- Ether x99 (2 under I. glitch item)
	- HM02 x1 (3 under Earthbadege with TM30 on bottom of screen, which ensures cost is $1000)
	- TM30 x2

Close glitched mart, then re-open unglitched mart
- Buy:
	- Burn Heal x99 (2 under Escape Rope)
	- Escape Rope x2
	- Awakening x1
	- Antidote x99
	- Antidote x99
	- Antidote x1

## Jynx
- Walk to Museum, go upstairs to Jynx tile
- Flash TMTRAINER (2 under ???), catch Jynx with Master Ball, nickname 1 char ("J")
- unjack, **swap Jynx in front**
- Exit museum and head to Brock fan jack tile (http://extratricky.com/pokeworld/rb/1#72,66)
- Use Burn Heal (2 under HM02) to heal Jynx's status
- swap Jack (2above HM02)
- with Poke Ball (2 above ???)
- use Jack
- Go to tile above Brock fan, talk to him without unjacking (!)
 - sign must be visible on last row
- Brock thru Walls to Viridian Gym (fastest to go straight down, then left at the end)

> NOTE: This particular BTW method relies on an 0F23 setup in items. Specifically, starting from an odd slot, the order must be:  [item] x15 | HP Up x1 | <Max Repel/Bicycle>

## Giovanni
- Face right and [jack on cursor](https://gunnermaniac.com/pokeworld?map=45#16/17/LUUUUUUUUUUUULLLLLLUL)
- IP, BZ, IP, IP, IP
- Before exiting gym:
 - Use Max Repel (slot3)
 - Pick up Revive  
   - ~0.2s faster than combining Max Repel and Bike menus and getting TM38 from Blaine
- After exiting gym
  - Bike to Pallet
  - Use Surfboard (2 under Jack) and [surf to Cinnabar](https://gunnermaniac.com/pokeworld?map=1#58/250/LDDDDDDDDDDDDRDDDDDDDDDDDDDDDDDDDDDDRRDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDD)
  - jack (2 above cursor) and bike to enter Blaine's gym
   - must see 1 tile of water on top

## Blaine
- Face right and [jack](https://gunnermaniac.com/pokeworld?map=166#16/17/LLUUUUUL)
- Face up and medicine [jack](https://gunnermaniac.com/pokeworld?map=166#13/12/LLLLL) (2 above cursor)
- unjack, walk up then jack again to Blaine
- BZ, BZ, BZ+IP
  - Don't Ether during fight if out of Blizzards, since that causes instant victory (b&). Use Ice Punches instead.
- Ether on Blizzard
- Teach Fly to Pidgey
- Teach Teleport to Jynx (over Thrash)
- Use Burn Heal if burned
- Escape Rope to Pewter
- Bike (2 above 6F) to house near Brock fan and enter/exit, jack (1 below) and bike again
- unjack, [Brock thru Walls to r23](https://gunnermaniac.com/pokeworld?map=1#75/69/LLLLLLLLLLLLLLLLLLLLLLLLLLLLLLLLLLLDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDLU)
- Walk up until Indigo Plateau map loads
  - until until game turns blue
- Teleport to Pewter
- Brock thru Walls to [Saffron Gym](https://gunnermaniac.com/pokeworld?map=1#53/80/RRRRRRRRRRRRRRRRRRRRUUUUUUUUUURRRRRRRUUUUUUUUULLLLLLLLL) (still in BTW state after Teleporting)
 - keep left until game turns blue, go down until orange, right to enter gym

## Sabrina
- Walk 1 right, jack to sabrina
- BS, BZ, BZ
- jack again when looking up to exit gym
- Bike and Jack, Heal in Celadon Center
- Face right, jack
- medicine jack to skip the gate

## Koga
- Face down and jack to get to Koga
- IP, IP, IP, BZ
- Jack to exit gym
- Teleport to Celadon
- Face right, bike and [jack](https://gunnermaniac.com/pokeworld?map=1#191/118/LLLLLDDDDDDDDDDDDDLLLLLLLLLLLLLLLDDDDDDDDD)

## Erika
- Face down and jack to get to Erika
- IP, BS, IP
- Jack to exit gym
- Teleport to Celadon
- Face down, bike and [jack](https://gunnermaniac.com/pokeworld?map=1#191/118/RRRRRRRRRRRRRDDDDDDRRRRDDDDDRRRRRRRRR)
- face right and medicine [rejack](https://gunnermaniac.com/pokeworld?map=1#217/129/RRRRRDDDDDDDDDDRRRRRRRRRRRRRRRRRDDDDDL)
- face left and medicine rejack
- unjack and skip trainers/grass
- [jack](https://gunnermaniac.com/pokeworld?map=1#246/164/DDDDDDDDDLLLLLLLLDDDDDDDDDDDDDDDDDDDDDDLLLLLDDDD) to get into surge's gym

##Surge
- Face left, jack to get to Surge. 1 right then up
- IP
- Jack to exit gym
- Fly to Cerulean, walk to Misty's gym

## Misty
- Use Surfboard (2 under Jack) on left side of gym to surf to Misty
- BS, BS

Fly to Pewter

## Brock
- IP, IP

## League
Fly to Indigo, skip E4+Champ, go immediately to HOF
