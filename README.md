# Fe Universal Tool Orbit

hello skids, ts make ur tools float n orbit around u n stuff yh. got like 20+ patterns, commands u can type, lil notifs in the corner. pretty clean ngl

---

## wat it do

- tools just float n spin around u every frame
- works on other players too if u wanna orbit someone else
- auto picks up tools when u equip em, drops em when u dont
- lil popup notifs tell u whats happening
- command bar w tab autocomplete so u aint typin the whole thing
- got a resync thing so if a tool drifts too far it snaps back
- cleans itself up when u respawn, no weird leftovers

---

## commands

just type in the bar that shows up, tab to autocomplete btw

| command | wat it do |
|---|---|
| `offset [num]` | how far the tools float from u |
| `speed [num]` | how fast they go around |
| `rot [num]` | how fast the tools spin on themselves |
| `mode [num]` | changes the pattern, 1 to 20+ |
| `lerp [num]` | smoothness of the movement |
| `target [name]` | orbit around someone else, partial name works |
| `unorbit` | come back to urself |
| `equip` | equips everything in ur backpack |
| `unequip` | dumps it all back |
| `help` | shows the command list |
| `stop` | kills the script |

---

## patterns

modes 1-6 r set ones:

- **1** - basic flat circle
- **2** - circle w a up down wave
- **3** - dual axis spin
- **4** - world space circle, doesnt follow ur rotation
- **5** - 3d sphere path
- **6** - rolling tilt thing

7+ cycles thru like 8 different sub patterns. figure 8s, petal waves, spirals, spike orbits, banded rings etc. past mode 20 everything gets an extra slow wobble on top

---

## misc

- only runs one at a time, rerunning does nothing
- shuts down on respawn
- bumps sim radius if ur executor supports it
