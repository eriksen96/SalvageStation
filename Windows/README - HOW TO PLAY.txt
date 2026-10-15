SALVAGE STATION  -  test build v0.3 (work in progress)

HOW TO START
  1. Unzip this whole folder anywhere (keep everything together).
  2. Double-click MyGame.exe.
  If Windows warns about an unknown app: "More info" -> "Run anyway".
  If it won't start: run Engine\Extras\Redist\en-us\UEPrereqSetup_x64.exe once, then try again.
  Needs 64-bit Windows 10/11 and a DirectX 12 graphics card.

NEW? Press TRAINING on the start screen for a 2-minute walkthrough.
WANT TO TRY EVERYTHING? Press SANDBOX on the start screen (see SANDBOX below).

GOAL
  Your robot crew salvages derelict station sectors. Carry battery and fuel loot into the airlock
  (the glowing room by the start) to meet the quota, then press the LAUNCH button.
  Valuables become credits. Loot lies on tables, shelves, racks and crates as well as the floor.
  After each sector the shuttle docks at the TRADING POST: walk up to an item and press E to buy it,
  then press the big launch console to go on. If the whole crew goes down, the run starts over.

TRADING POST AND THE CREW'S GEAR
  Credits belong to the whole crew - anyone can spend them. Upgrades go on YOUR robot only.
  Gear you buy doesn't go into your hands: it goes into the crew's stash and waits on the
  GEAR COUNTER in the corner of the dock when the next sector starts. Pick it up there with E.
  Whatever the crew carries home - and anything left in the dock - is there again next sector.
  Gear dropped elsewhere in a sector is lost. Each piece of equipment is limited to one per crew member;
  when the crew has as much as it may, the item is gone from the shop.
  Gear: pulse pistol (+ pulse cells), rollerblades, health packs, flare pack (+ energy), noise makers,
  revive kits, grapple (+ energy), airlock beacon (+ uplinks), stun baton, cargo sled.
  A robot that went down and wasn't revived comes back next sector with 1 hp.

MAP (bottom right)
  Rooms appear once someone in the crew has been in them. Loot shows once anyone has seen it
  (orange = fuel, blue = batteries, gold = valuables), hazards in red, crewmates in blue.
  The airlock shows in green when it's near. A robot carrying a live AIRLOCK BEACON sees it from
  anywhere, with an arrow and the distance (one uplink is used each sector).

HANDS AND INVENTORY (1 2 3 4)
  Your HANDS (the box left of the slots) and four slots. Whatever you pick up goes into your hands.
  A number key swaps your hands with that slot: it puts away what you hold, takes out what's there,
  or trades the two. Only what's in your hands can be dropped or thrown.
  With an item in your hands, left mouse uses it: fire, throw a flare or noise maker, fire the grapple,
  swing the stun baton, use a health pack. Rollerblades in your hands are on your feet.
  Revive kits: hold one, look at a fallen crewmate's wreck and press E.
  Loot: left mouse picks it up and again puts it down. Small loot (up to 6 kg) fits in a slot;
  anything bigger needs both hands. What you carry sways with your moves - heavy things the most.
  Fridges and cabinets open and close with E - sometimes there's loot inside. Loot also lies on
  tables, shelves and the upper decks of two-storey rooms (take the stairs).

CONTROLS (rebindable in Settings, Esc)
  WASD move, Shift sprint, Ctrl crouch (sprint + Ctrl = slide), Space jump (hold Ctrl first = high jump;
  while on the grapple line, Space lets go)
  Left mouse  pick up / put down, or use the item in your hands       Right mouse  throw / drop
  Mouse wheel  carried loot nearer / further
  1-4  swap your hands with a slot
  E use (launch button, buy, pick up, revive)   F head lamp   V look at yourself   Esc / P pause

SANDBOX
  A sector with one of every item on the gear counter, no quota and no game over: if you go down,
  you're rebuilt at the dock. F1 Wanderer, F2 Hunter, F3 Watcher, F4 Shade (they appear in front of you),
  F5 every item in front of you, F6 clear all monsters, F7 full health. Leave from the pause menu.

TIPS
  It's dark. Keep your head lamp on to see - but the Shade hunts light, and the Hunter spots you sooner.
  The Hunter HEARS you: sprinting is loud, walking is quieter, crouching is silent. Gunshots are very loud.
  The Wanderer just roams - but if it walks into you, it pounces, hits hard and knocks you away.
  The Hunter needs a second to be sure it sees you (three if you crouch). Crouch to crawl under tables,
  workbenches and catwalks and hide - your robot squeezes down to fit.
  The Watcher only moves when nobody looks at it.
  Hazards switch on and off: wait for the warning sound to stop and cross while they're dormant.

CO-OP (up to 4 players)
  One player presses HOST CO-OP on the start screen; the others press FIND GAMES and JOIN.
  - Over the internet: everyone runs Steam with their own account. The game uses Valve's free test app
    "Spacewar", so Steam will say you're playing Spacewar - that's normal. The host can also press
    INVITE FRIENDS to invite through the Steam overlay.
  - Same network, no Steam: just HOST / FIND GAMES / JOIN.
  The host's game runs the session; only the host can launch from the start screen.
  Hold T to talk (proximity voice - teammates hear you from nearby). When you die, you spectate
  your crew (click to switch) until they finish, someone revives you, or everyone is down.
  If co-op goes wrong, both players can send the file
    %LOCALAPPDATA%\MyGame\Saved\Logs\CoopLog.txt
  (paste that path into the Windows Explorer address bar) - it records joining, level changes and disconnects.
