# Game animations

## Overview
Game animations can be configured with custom events, custom playback speed etc. if you use Rpg Tools as your game engine.

### Create a new game animation
When you select a character and an animation you can create a game animation for the selected animation by clicking on the `Create` button.

![alt text](images/CharacterEditor_GameAnimation_Create.png "Create a new animation")

### Edit an animation

TODO :
| Property | Description |
| -------------                     |:-------------:          |
| Frame duration | How long is a single frame displayed. E.g. for a 3 frame animation 0.33 means the whole animation length is one second |
| Play back and forth | When checked the animation will play back and forth. This means instead of playing frames 0 1 2 0 1 2 it will play the frames 0 1 2 1 0 1 2 |

### Edit events
You can add new events by clicking on the `+` button of the `Events` property.

You can delete or duplicate events via right click on an existing event:

![alt text](images/CharacterEditor_GameAnimation_ContextMenu.png "Event context menu")

For each event you can edit its properties.

| Property | Description |
| -------------                     |:-------------:          |
| Event Type | Here you can configure which kind of event it is, the types are described below |
| Time | The time when this event is triggered. You can drag the button horizontally to change it |

![alt text](images/CharacterEditor_GameAnimation_EventEditor.png "Edit events")

### Event types

#### Effect

| Property | Description |
| -------------                     |:-------------:          |
| Effect Type | Use none if you want to configure a custom effect or choose a special type like `Weapon Attack` to trigger the attack effect of the current weapon |
| Effect | Here you can select which kind of effect should be triggered |
| Position per direction | Here you configure the effect position for each direction either by dragging or entering the coordinates. The `X` button can be dragged and you can see a live preview in the `Sprite` window |

#### Sound
Plays a specific sound when the event is triggered

#### Attack
Trigger an attack. This checks if the attack hits a target. Only useful when you configured this animation for an attack ability.

#### Cast
Trigger casting of the currently selected spell. Only useful when you configured this animation for an ability