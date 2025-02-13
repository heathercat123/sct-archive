# SCTv2 level format
This is the level format used by most versions of the Scratch Cat Tales engine. It is based on Griffpatch's Tile Scrolling tutorial's `1` level format

## Header:
- The string `SCTv2_` which stands for Scratch Cat Tales \[engine\] Version 2 (v1 was griffpatch's)
- The music id (#): M_#_ (default is id 4, 'Cedar Woods 1')
- The level's name (#): N_#_
- Grid width followed by an underscore
- Grid height followed by an underscore

## Tile data (bottom to top, left to right):
- Tile ID
- How many in a row using letters from a-z (a is 1, b is 2...)

## Object data:
- Object index followed by an underscore
- Object type followed by an underscore
- Attached text string followed by an underscore (used for things like signs and cat unlocks)