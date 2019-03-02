# Dark Souls 3 PVP Helper v0.1

This is a pre-release version to fulfill the wishes of those that requested it, it has missing features and is not as refined as I would like it to be. This means it currently only works properly if YOU are the host and it only displays YOUR frame data and not other players. (If you invade with this script enabled it will change the host's colors relative to your own frame data)


### What is it?
The Dark Souls 3 PVP Helper is an open source tool which allows you to view frame data visually and on the fly while you are playing. This allows you to view things like active Super Armor frames, i-Frames from rolling, as well as block and parry frames. The tool is meant for learning and data gathering as well as visual feedback on the fly during gameplay to better grasp what goes on inside the game's data. It is open source so you can make your own changes and improvements to it as you see fit. I consider this a personal hobby project, updates may not come frequently.


### How do I use it?
You will need Cheat Engine version 6.6 or higher.
1. Open the .CT file you downloaded
2. Attach the table (.CT file) to the DarkSoulsIII.exe process
3. Click the boxes next to the script you'd like to use in the section below to activate

For color, 0 is none. You can choose colors 1-100 as a value to change the visual of each frame type. (will add dropdown list later)


### Current Features:
- Customizable colors for displaying frame data (#1-100 are valid values for color)
- i-Frames Indicator
- Super Armor Indicator
- Blocking Indicator
- Parrying Indicator


### Planned Features:
- Counter Damage Indicator
- Instability Frames Indicator
- Active Attack Frame Indicator
- Fight Log (E.G. "Malcolm used 1HR1 Attack with Long Sword, Grim took 345 damage")
- Ingame Unit Measurement
- Visual Player Hitboxes
- Visual Weapon Hitboxes
- Map hitbox visualizer - (I already have this)
- Indicating frames regardless of the role of your character
- Indicating other player's frame data (may only work partially)
- Convert to assembly (maybe)


### Known issues:
- Colors flicker occasionally due to the way the game updates values. Technically the most accurate depiction of when flags are active or not.
- Allegedly the super armor indicator doesn't always work, like on some attacks that have super armor it wont recognize it idk tho cuz I gotta test that
