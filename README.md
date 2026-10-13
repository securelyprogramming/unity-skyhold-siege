# Skyhold Siege

Collect materials, stack and reinforce a vertical refuge, and defend its core against escalating waves.

**Status: development.** Three authored chapters with distinct objectives, original cast and live gameplay rules. This source is being built and playtested toward a premium Steam release; it is not a certified or finished Steam game.

## Story

### Foundations in the Fog

Orin inherits a broken sky-core and a valley disappearing beneath ash.

### Above the Ash

Tala marks the approaches. Higher floors buy time, but unsupported towers will not stand.

### The Last Beacon

The last beacon needs a refuge tall and strong enough for the storm crossing.

## Play and build

Unity6000.6.0f1; project `Game/`. Native Mac: `python3 tools/playtest/build.py --platform macos --output /absolute/fresh/output`. Windows/Linux profiles require native hosts and their corresponding editor modules. Outputs remain outsideGit.

WASD/leftstick move, mouse/rightstick aim, E/A interact, LMB/RT/X attack, B/LB build, Q/RB craft, Escape/Start pause, J/Select journal. Menus accept keyboard, mouse and gamepad; Actions chooses structures, supplier goods, recipes and crafting. Audio/display/rebinding preferences and earned chapter unlocks save locally pergame.

1-4 player LAN sessions use an authoritative TCP host, optional UDP discovery and a controller-operable IP keypad. Clients cannot grant themselves resources or control host-only campaign actions. LANmenus do notpause the host; solo pause does. No internet relay, Steam SDK, host migration or online matchmaking is claimed.

Selected purchased models/textures remain private, pinned by ContentSource/Art/selection.json. Original game characters, story, simulation and view source are versioned. See Docs/VALIDATION.md for actual evidence and remaining acceptance gates.
