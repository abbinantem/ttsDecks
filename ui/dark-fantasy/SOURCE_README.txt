DARK FANTASY STATUS BAR GRAPHICS - REVISION 2

Approved design: health is out of 3; no skull beneath any level badge.

CONTENTS
31 named portrait medallions
12 individual icons (including the skull used for the kills counter)
4 blank skull-free level badges: blue, yellow, orange, red
5 blank bar / parchment / counter panels
6 colored splashes
4 three-heart health states: 0_of_3, 1_of_3, 2_of_3, 3_of_3
4 separate parchment header labels: HEALTH, LEVEL, KILLS, MOVE
1 full assembled Berin design example
Total: 66 reusable PNG graphics plus 1 example. All have alpha transparency.

ASSEMBLY (BACK TO FRONT)
1. Colored splashes and blank panels.
2. Hero portrait / medallion (name ribbon is baked into each portrait).
3. Choose one health_states overlay. Every overlay shows exactly 3 hearts.
   Alternatively place three icons/heart_full or icons/heart_empty sprites.
4. Choose one skull-free badge from badges/.
5. Place icons/skull on the kills panel and icons/movement on the move panel.
6. Place the four labels above their respective panels.
7. Overlay dynamic numeric text: health N / 3, level, kills, movement.

Blank badge centers and counter panels intentionally have no numbers.
The skull icon remains for KILLS; it is absent from all four level badges.
The half-heart icon is retained as an optional asset, not used by the
standard integer health states.

The example shows Berin with health 3/3, level 3, kills 12, movement 4.
It is an AI-composited design reference, not a pixel-exact render of the
separate sprites. The individual sprites have independent canvases;
position and scale them in your UI while preserving aspect ratios.

This is a graphics package, not a scripted Tabletop Simulator mod.
No Lua/XML or automatic counter behavior is included.
The manifest gives the actual dimensions of every exported PNG.

ARTWORK
Built-in image generation used your supplied references. Revision 2
removes skulls from all level badges and adds the three-heart state
overlays and header labels. Unaffected portraits, panels and icons
are retained. AI-edited artwork can differ in fine details.
Some weapons reach their original sheet edges.
