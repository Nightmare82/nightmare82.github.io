# Custom animations

## Overview
Rpg Tools offers a couple of options to add your own animations.

### Rpg Tools naming scheme
One way is to use a special naming scheme for your animated sprite sheets which will be automatically identified by the tool.
There are two types of animations:

#### Single animations

This type can be used if you have a single animation in a sprite sheet.
It can consist of X*Y frames(for example 3x4 frames which results in a 12 frame animation)

To use this animation you can use this naming scheme:
`Animation_[FramesX]x[FramesY]_[Name].png`

For example:
`Animation_4x3_Fireplace_01.png`

This can be used for a sprite sheet consisting of 4x3 frames, the name will be `Fireplace_01`.

#### Row animations

This type can be used if you have multiple animations in a single sprite sheet.
It can consist of X*Y frames(for example 3x4 frames which results in a 4 animations with 4 frames)

To use this animation you can use this naming scheme:
`RowAnimation_[FramesX]x[FramesY]_[Name].png`

For example:
`RowAnimation_4x3_Fireplace_01.png`

This can be used for a sprite sheet consisting of three fireplace animations consisting of 4 frames, the name will be `Fireplace_01`.
