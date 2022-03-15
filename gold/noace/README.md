Gold Any% No ACE Route v2.0 https://pastebin.com/KUKEC1mh by entrpntr

No TID manip (just find cluster that avoids FF?) -> i use NSC's so ss0 is also correct

gold_gfwait_backout4_wait337(setopt)_backout10_newgame: TID = 0xD900 (55552), LID = 0xD3EC (54252), Offset (wait): 43.297, offset(wait GBI): 42.720 Offset (NG): 58.32

Adjacent Framerules even if you miss its fine
- -3 32656
- -2 62051
- -1 65433
- 0 55552
- 1 14846
- 2 02669
- 3 51957

if you want to do rng manipulations later (they are optional), start a timer on TID hard reset and confirm minutes between 1:00.50 and 1:01.50 (todo: this doesnt consider GBP fadeout, check whats the correct time) - note: just not missing the first textbox will give ss0 from TID manip, no need for timer

Set the time to 10:00 AM, name yourself A, say Y/Y/N/Y/Y to the Yes/No textboxes from mom

**Nickname TOTO "A " with a space at the end**

(don't do this, its slower)[toto manip](https://pastebin.com/GirxGiU9)
<details>
<summary>notes for run</summary>
<br>

8. 0x89C2 (20/12/12/9/10/10)    ; npc: r
9. 0x1B43 (21/11/12/9/10/9) / (20/11/12/9/10/9)    ; npc: l
10. 0x394F (21/11/12/10/11/9) / (21/11/12/9/9/9)   ; npc: u
11. **0xFDFF (21/13/12/10/11/10)   ; npc: d**
12. 0xDECF (20/12/12/10/11/10)   ; npc: u
13. 0xC7A6 (20/12/12/10/10/10)   ; npc: u
14. 0x3501 (21/11/11/9/9/9) / (20/11/12/9/10/9)     ; npc: u
15. 0xBF79 (21/12/12/10/10/10)   ; npc: l

</details>

Take Totodile’s Berry off, reset if female

(optional)[r29 manip](https://pastebin.com/bjBqGeCQ)
<details>
 <summary>r -> l</summary>
 <br>
 <img src="https://i.imgur.com/PX1pgAr.png"/>
 </details>
  <details>
 <summary>d -> r</summary>
 <br>
 <img src="https://i.imgur.com/EOlmJpZ.png"/>
 </details>
  <details>
 <summary>l</summary>
 <br>
 <img src="https://i.imgur.com/4jNSDuf.png"/>
 </details>

Go to Mr. Pokemon

If you are doing manips, pick up the hidden potion after Mr.Pokemon, otherwise, skip and buy 11 potions

Rival 1: Leer once, spam Scratch

go back to the lab, name rival 1 char, skip the catching tutorial

(optional)[r29 manip 2nd pass](https://pastebin.com/bjBqGeCQ)
<details>
 <summary>r -> l</summary>
 <br>
 <img src="https://i.imgur.com/Bu9RQX3.png"/>
 </details>
  <details>
 <summary>d -> r</summary>
 <br>
 <img src="https://i.imgur.com/1sjG78D.png"/>
 </details>
  <details>
 <summary>l</summary>
 <br>
 <img src="https://i.imgur.com/y7Z8MBy.png"/>
 </details>

Youngster Mikey: spam Scratch

Potion if <15, equip berry (15-16 use berry), call Mom (this can be done before Don Manip or on the Start buffers while passing Don)
 <details>
 <summary>(optional)[Don Manip](https://pastebin.com/7KdSvbZG)</summary>
 <br>
 <img src="https://cdn.discordapp.com/attachments/638862200148066324/874377359611031622/don.png"/>
 </details>
U/R(slow)/R(fast)/L
Avoid Spinner Don (rage both Caterpies if you hit)

Violet Town:

Enter Falkners gym

Bird Keeper Ape: Rage spam (Scratch last turn if red bar)

Potion if below 10HP

Bird Keeper Rod: Rage spam

Potion if below 16HP, or if below 19HP if you’re already LVL 10

Gym Leader Falkner: Rage spam

get the egg in the pokèmon center (take 2 extra steps to not bonk)

You need 126 steps at the PC.
- Manipped no mart with ledgehop is at 32 steps at PC.
  - Count 9 up/down and you will be at 122, then do 4 extra
- Manipped with violet mart and no ledgehop is at 60 steps at PC.
  - Count 6 up/down and you will be at 120, then do 6 extra

Save from menu. Decrement egg cycles. Clone 1 egg.

Move egg in box to top of party. Decrement egg cycles. Clone 2 eggs.

Withdraw top egg. Decrement egg cycles. Clone 3 eggs.

(REPEAT x6) Withdraw bottom egg. Decrement egg cycles. Clone 3 eggs.

Should have 16/20 in Box 1 after this, and the bottom egg in the box should be at 1 egg cycle remaining.

Attempt bad clone (deposit top 2 eggs).
Check "Change Box" after S&Q to see if clones were made. If so, check to make sure no nickname on cloned eggs. If no nickname, assume you have a real bad clone.
(NOTE: Must be in Box 1 for the move menu swaps at the very end of the run to work. If Box 1 gets filled and you switch boxes, make sure to switch back.)

Withdraw (in this order)
   - Last egg before the attempted bad clones (16th in box)
   - Bottom bad clone (last in box)
   - Top egg in box

Reference video from this point on: https://www.youtube.com/watch?v=So_3MCF4A3k

Decrement egg cycles to hatch eggs. Nickname Togepi "A " (with a space). Don't nickname bad clone.

Move w/o mail (these swaps do lots of complicated things with HP/level/nicknames/species/etc.)
   - Egg in Box 1 to 2nd in party
   - 1 <> 1 in party
   - Egg in Box 1 to 1st in party
   - 4 <> 4 in party
   - 3 -> 1 in party
   - 3rd in party to top of Box 1

Party menu (pay attention to whether hexFF is poisoned, which is a 6/16 chance, depending on Togepi's speed stat)
   - 1 <> 5
   - 7 <> 1
   - Take Card Key off Togepi (7th)
   - 7 <> 1
   - Take Card Key off hexFF (7th)
   - 6 <> 1
   - 1 <> 7
   - Take Card Key off bad clone (7th)
   - 1 <> 3
   - 1 <> 7
   - Take Card Key off Toto (7th)
   - If hexFF (3rd poke now) is PSN'd, swap 3 <> 7 (avoids PSN ticking in overworld)

Pack             
   - Left (or Right) 2 to Key Items
   - 3 <> 4
   - 3 <> 2
   - 3 <> 5
   - 1 <> 4
   - 2 <> 1
   - 2 <> 4
   - (NOTE: order matters on a few of these swaps; 3 <> 4 is different from 4 <> 3, for instance)

Item PC, Deposit
- Right 1 to Balls
- Deposit 16 Poke Balls

Exit Menu, Withdraw 1 Poke Ball twice

Exit Menu, Deposit
- Left (or Right) 2 to Key Items
- Deposit all 4 key items

Exit Menu, Exit PC

Pack (will be in Key Items to start)
   - Swap top ? x0 (in 2nd) with ? x0 below it (in 3rd)
   - Register Bicycle
   - Swap Poke Ball x43 with Max Repel x255
   - Left 1 to Balls
   - Toss 16 from Poke Ball x255
   - Right 1 to Key Items (to hold its place next time you menu)

Exit Center.

- Sudowoodo     ::  (down 1) TM47 x1
- Route 36      ::  TM47 x1
- Route 35      ::  TM47 x1
- Goldenrod     ::  TM47 x2
- Magnet Train  ::  TM47 x1
- Cerulean      ::  TM47 x1

On Pewter tile
   - TM47 x1
   - (up 2) Max Repel

On Kanto guard tile
   - (down 2) TM47 x1
   - Open Party Menu, follow steps below

Party Menu
   - Select MOVE on 7th poke (cursor should already be on 7th)
   - Right 158, Left 2, (swap 1 <> 3), Right 8, (swap 1 <> 2)
   - Other cues if counting is too hard:
    - Once you see a poke with Constrict as only move, you are close (145)
    - When you get to Voltorb shortly after that poke, you are at 155
	  - Right 3 from the Voltorb (155+3=158) is Swift/Lovely Kiss/Acid Armor
	  - Left 2, swap 1 <> 3 (must load the poke with 3 moves first so you can swap moves)
	  - Right 8 (Tail Whip 0/30, Tail Whip 7/30, Tail Whip 0/30), swap 1 <> 2
   - (NOTE: Press Right as soon as you see each poke's sprite load)

On Silver Cave guard tile (previous repel should exactly wear out on the tile)
   - (up 2) Max Repel
   - S&Q
 
Navigate Silver Cave to Red (239 tiles on bike with perfect movement, i.e. 11 repel steps to spare).

Defeat Red in an instantaneous victory to complete the speedrun of this video game.
