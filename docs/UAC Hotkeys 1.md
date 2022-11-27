## FSS
### Key Usage

>[!multi-column]
>
>>[!note]+ Work
>>asdfasdfasdfasdf
>
>>[!warning]+ Personal
>>asdfgasdgas
>
>>[!summary]+ Lore
>>asdfasdf

Q: Jump
A: Attack

P: Patrol 
S: Stop
T: Sprint
D: Bino
E: Laser Desig
W: OSR
F: CFF
O: Level Up
Z: Menu
V: Wille Pete
X: Immediate Smoke
C: Immediate Flare
R: Suppressive Barrage
Z+Z: Nook
Z+X: Rail














asdfasdf

Q: Jump
A: Attack
P: Patrol 
S: Stop
T: Sprint
D: Bino
E: Laser Desig
W: OSR
F: CFF
O: Level Up
Z: Menu
V: Wille Pete
X: Immediate Smoke
C: Immediate Flare
R: Suppressive Barrage
Z+Z: Nook
Z+X: Rail
*Visual Guide to the Above*
![[Key Usage 1]]

### Ideas: 
- ~~GUI for angle direction~~ probably unnecessary since the hotkeys are directional 
- Timer for shells
- Press key to engage num key presets
	I.e. w would turn on shell presets
	1-5 would be shell count
	Pressing w again cancels
- ~~Press a button to enter unit movespeed, script will give you i/r to match speed (prob not needed,  since even with radius 2 an inteval of 0.2 could theoretically match a movespeed of 10!)~~ Kind of unnecesary, the interval tooltips are good enough.
- ~~Only refeshgui when a change is made
- ~~Use `#if` context hotkeys to eliminate hotkey overlap so I can use shells during inventory mode~~
- ~~TL ping mouse tied to shell mode~~
- ~~When shells count = 1, set distribution 0, interval lowest poss. and save actual angle for when shell increases~~
-~~Korean Mode (ctrl-shift-k?``)
	- Send out a -a and -c command everytime -d is sent~~
- Add additional hotkeys for 10 shells (double tapping s for next 5? (copy paste from KR)
- Directional for clearing linears 
	- Directional will just control the direction. The actual radius/interval/shell count will be a preset probably on another keyset

### Issues: 
1. ~~Overlap on shell and directional on inventory (W)~~ Fixed using conditional shells
	1. Adjust length limit?
	2. Hotstrings?
		1. Hotstrings would let the first character through, meaning I would stop if shell is s
		2. Benefits of hotstrings
			1. ~~-Hotstrings would fix issue of overlapping keys (i.e. pressing ``:*:gs::)
				1. Apparently not correct, still overlapped
		3. Drawbacks
			1. We couldn't use them over the keys which already have uses (i.e. pressing ``:*:s2::`` to shell would use stop and select control group 2)
2. ~~Sprint Key is invisible to the game
	1. ~~Make other keys visible to the game when not recording
	2. ~~Have a 1 second timeout

Math Behind Shells:
Within a radius of 1, full damage
Within a radius of 2, 60% damage
Within a radius of 4, 40% damage
Enemy Movespeed = Radius * 1 / Interval



## General
### Key Usage
- MButton 1: TL Ping
- Copy Paste Text
- MButton 2: Swap between control groups and inventory

### Ideas: 
- 

### Issues: 
- 
