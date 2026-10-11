# The-Last-Stand-Aftermath-VR
Mod for The Last Stand Aftermath

<img width="448" height="442" alt="Adobe" src="https://github.com/user-attachments/assets/e9a790b9-a52c-473c-81b5-149531cf32e4" />

THE LAST STAND: AFTERMATH VR  -  VR mod
=========================================================================

INSTALL
1. Unzip this into the game folder, so you get
2. Start your OpenXR runtime (SteamVR / Oculus / Virtual Desktop), put the headset on, start the game.

THE VIEWS
* Normal (default): you stand where the game's camera is (a bit closer: [View] NormalViewZoom 0.6)
  and look down on your survivor in 3D, like a table-top. The game camera still follows the player.
* First person: you are the survivor (view at the character's head). Aim by pointing your right
  controller; the left stick walks where you look. Right stick = snap turn.
* Switch: hold B and click the right stick.
* Recentre: click both sticks together.

CONTROLS (the VR controllers are an Xbox pad, button for button)
-
  Left stick  = move
  
  Right stick = aim
  
  Right grip   = focus / aim (LT) + laser
  
  Right trigger = fire (RT)
  
  Left trigger = melee  
  
  Left grip     = antiviral (LB)

  A = sprint   B = dodge   X = reload
  
  Y = interact (hold)
  
  Left grip + Y = Start (pause menu)  
  
  Left grip + X = Back (hub: inventory, map...)
  
  Left stick click = L3 (stealth)

  D-pad = hold the left grip + push the right stick that way
  
  In menus: right stick = d-pad too, A = select, B = back.
  
Every button can be changed in BepInEx\config\tlsa.vr.cfg [Controls] (live: save the file while
playing). 

HUD / MENUS
-
The game's HUD and menus are shown on a floating screen in front of you ([UI] Distance, Width,
HeightOffset, FollowMode Lazy / Head / GunHand / OffHand).

USEFUL SETTINGS (BepInEx\config\tlsa.vr.cfg)
[View]   ViewMode Normal / FirstPerson, NormalViewZoom (1 = at the game camera, smaller = closer),
         NormalViewHeightOffset, NormalViewPitch (tilt the world up towards you, e.g. 25)
         
[Camera] WorldScale (2 = everything looks like a model / diorama), DisabledRenderFeatures,
         PostProcessing, SameImageBothEyes
         
[Aiming] AimWithHand, LaserSight Always / Aiming / Off (first person)


If the game does not go into VR: make sure the OpenXR runtime is running before the game starts, and
send the log.

