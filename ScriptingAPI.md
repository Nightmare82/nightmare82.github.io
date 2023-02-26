- [Ability](#ability)
  - [displayName](#displayname)
  - [guid](#guid)
  - [iconPath](#iconpath)
  - [name](#name)
  - [soundPath](#soundpath)
- [AbilityEntry](#abilityentry)
  - [ability](#ability-1)
- [AbilityManager](#abilitymanager)
  - [abilities](#abilities)
  - [getAbilityByName](#getabilitybyname)
- [AbilityReference](#abilityreference)
  - [Ability](#ability-2)
  - [guid](#guid-1)
- [AnimationMode](#animationmode)
- [AnimationMode.Loop](#animationmodeloop)
- [AnimationMode.LoopBackAndForth](#animationmodeloopbackandforth)
- [AnimationMode.PlayOnce](#animationmodeplayonce)
- [Area](#area)
  - [color](#color)
  - [getRandomPositionInArea](#getrandompositioninarea)
  - [isPointInside](#ispointinside)
  - [name](#name-1)
- [CameraSettings](#camerasettings)
  - [attachToHero](#attachtohero)
  - [object](#object)
- [CharacterClass](#characterclass)
  - [abilities](#abilities-1)
  - [displayName](#displayname-1)
  - [name](#name-2)
- [CharacterClassReference](#characterclassreference)
  - [guid](#guid-2)
- [Color](#color-1)
  - [a](#a)
  - [b](#b)
  - [g](#g)
  - [r](#r)
- [ColumnAlignment](#columnalignment)
- [ColumnAlignment.center](#columnalignmentcenter)
- [ColumnAlignment.left](#columnalignmentleft)
- [ColumnAlignment.right](#columnalignmentright)
- [Container](#container)
  - [widgets](#widgets)
- [Cutscene](#cutscene)
  - [background](#background)
  - [dialogs](#dialogs)
  - [title](#title)
- [CutsceneBackground](#cutscenebackground)
  - [hasImage](#hasimage)
  - [imagePath](#imagepath)
  - [levelPath](#levelpath)
- [CutsceneDialog](#cutscenedialog)
  - [background](#background-1)
  - [hasVideo](#hasvideo)
  - [isVideoLooped](#isvideolooped)
  - [text](#text)
  - [videoPath](#videopath)
- [DamageType](#damagetype)
  - [name](#name-3)
- [DamageTypeManager](#damagetypemanager)
  - [damageTypes](#damagetypes)
  - [getDamageTypeByName](#getdamagetypebyname)
- [Dialog](#dialog)
  - [dialogs](#dialogs-1)
- [DialogManager](#dialogmanager)
  - [getDialogByGuid](#getdialogbyguid)
- [DialogOption](#dialogoption)
  - [text](#text-1)
- [Equipment](#equipment)
  - [equipItem](#equipitem)
  - [unequipItem](#unequipitem)
- [GameEvent](#gameevent)
  - [addVariable](#addvariable)
  - [findVariable](#findvariable)
  - [type](#type)
  - [userType](#usertype)
  - [variables](#variables)
- [GameSettings](#gamesettings)
  - [musicVolume](#musicvolume)
  - [soundVolume](#soundvolume)
- [Guid](#guid-3)
  - [clear](#clear)
  - [isValid](#isvalid)
  - [isZero](#iszero)
  - [toString](#tostring)
- [GuidReference](#guidreference)
  - [guid](#guid-4)
- [Hero](#hero)
  - [class](#class)
  - [name](#name-4)
- [Inventory](#inventory)
  - [items](#items)
- [Item](#item)
  - [displayName](#displayname-2)
  - [equip](#equip)
  - [imagePath](#imagepath-1)
  - [name](#name-5)
- [ItemManager](#itemmanager)
  - [getItemByName](#getitembyname)
  - [items](#items-1)
- [ItemReference](#itemreference)
  - [guid](#guid-5)
  - [item](#item-1)
- [ItemStack](#itemstack)
  - [count](#count)
  - [item](#item-2)
- [LoadingScreenData](#loadingscreendata)
  - [text](#text-2)
  - [texture](#texture)
  - [title](#title-1)
- [LocalizedTextManager](#localizedtextmanager)
  - [currentLanguage](#currentlanguage)
  - [getTextByGuid](#gettextbyguid)
- [LocalizedTextReference](#localizedtextreference)
  - [guid](#guid-6)
  - [text](#text-3)
- [LootComponent](#lootcomponent)
  - [items](#items-2)
  - [resources](#resources)
- [MapLayer](#maplayer)
  - [asObjectLayer](#asobjectlayer)
  - [asPathLayer](#aspathlayer)
  - [asTileLayer](#astilelayer)
  - [isScreenLayer](#isscreenlayer)
  - [name](#name-6)
  - [visible](#visible)
- [MeshObjectData](#meshobjectdata)
  - [animationIndex](#animationindex)
  - [rotationX](#rotationx)
  - [rotationY](#rotationy)
  - [rotationZ](#rotationz)
  - [z](#z)
- [Object](#object-1)
  - [center](#center)
  - [displayName](#displayname-3)
  - [fragmentShader](#fragmentshader)
  - [id](#id)
  - [identifier](#identifier)
  - [interactionCursor](#interactioncursor)
  - [loot](#loot)
  - [mesh](#mesh)
  - [opacity](#opacity)
  - [origin](#origin)
  - [physicsBody](#physicsbody)
  - [position](#position)
  - [rotation](#rotation)
  - [runAction](#runaction)
  - [scale](#scale)
  - [setImage](#setimage)
  - [size](#size)
  - [trader](#trader)
  - [variables](#variables-1)
  - [vertexShader](#vertexshader)
  - [x](#x)
  - [y](#y)
- [ObjectAction](#objectaction)
- [ObjectLayer](#objectlayer)
  - [addObject](#addobject)
  - [objects](#objects)
- [ObjectReference](#objectreference)
  - [objectId](#objectid)
- [PathLayer](#pathlayer)
  - [getWorldPositionAt](#getworldpositionat)
  - [isWalkable](#iswalkable)
  - [mapSizeX](#mapsizex)
  - [mapSizeY](#mapsizey)
  - [setWalkable](#setwalkable)
  - [tileSizeX](#tilesizex)
  - [tileSizeY](#tilesizey)
- [PhysicsBodyComponent](#physicsbodycomponent)
  - [angularVelocity](#angularvelocity)
  - [applyAngularImpulse](#applyangularimpulse)
  - [applyForce](#applyforce)
  - [applyLinearImpulse](#applylinearimpulse)
  - [isFixtureInCollision](#isfixtureincollision)
  - [linarVelocity](#linarvelocity)
  - [setVelocity](#setvelocity)
  - [stop](#stop)
- [PrefabObjectReference](#prefabobjectreference)
  - [guid](#guid-7)
- [Quest](#quest)
  - [autoStart](#autostart)
  - [displayName](#displayname-4)
  - [guid](#guid-8)
  - [name](#name-7)
  - [showInQuestLog](#showinquestlog)
  - [text](#text-4)
- [QuestInstance](#questinstance)
  - [objectives](#objectives)
  - [quest](#quest-1)
  - [state](#state)
- [QuestInstanceManager](#questinstancemanager)
  - [findQuest](#findquest)
  - [quests](#quests)
- [QuestObjectiveState](#questobjectivestate)
  - [count](#count-1)
  - [neededCount](#neededcount)
  - [text](#text-5)
- [QuestReference](#questreference)
  - [guid](#guid-9)
  - [quest](#quest-2)
- [QuestState](#queststate)
- [QuestState.Active](#queststateactive)
- [QuestState.Finished](#queststatefinished)
- [QuestState.Inactive](#queststateinactive)
- [QuestState.Reachable](#queststatereachable)
- [Resource](#resource)
  - [displayName](#displayname-5)
  - [guid](#guid-10)
  - [iconPath](#iconpath-1)
  - [name](#name-8)
- [ResourceContainer](#resourcecontainer)
  - [addResourceAmount](#addresourceamount)
  - [getResourceAmount](#getresourceamount)
  - [setResourceAmount](#setresourceamount)
- [ResourceManager](#resourcemanager)
  - [getResourceByGuid](#getresourcebyguid)
  - [getResourceByName](#getresourcebyname)
  - [resources](#resources-1)
- [ResourceReference](#resourcereference)
  - [guid](#guid-11)
  - [resource](#resource-1)
- [Savegame](#savegame)
  - [heroLevel](#herolevel)
  - [level](#level)
  - [name](#name-9)
  - [screenshot](#screenshot)
- [ScriptValue](#scriptvalue)
  - [description](#description)
  - [getBoolValue](#getboolvalue)
  - [getColorValue](#getcolorvalue)
  - [getDoubleValue](#getdoublevalue)
  - [getFloatValue](#getfloatvalue)
  - [getIntValue](#getintvalue)
  - [getStringValue](#getstringvalue)
  - [getVector2Value](#getvector2value)
  - [name](#name-10)
  - [objectID](#objectid-1)
  - [setFloatValue](#setfloatvalue)
  - [setValue](#setvalue)
- [ScriptValueContainer](#scriptvaluecontainer)
  - [findValue](#findvalue)
  - [setValue](#setvalue-1)
  - [values](#values)
- [ScriptValueMetaData](#scriptvaluemetadata)
  - [description](#description-1)
  - [elements](#elements)
- [ShaderReference](#shaderreference)
  - [parameters](#parameters)
- [ShowAnimationType](#showanimationtype)
- [ShowAnimationType.Fade](#showanimationtypefade)
- [ShowAnimationType.Scale](#showanimationtypescale)
- [ShowAnimationType.SlideToBottom](#showanimationtypeslidetobottom)
- [ShowAnimationType.SlideToLeft](#showanimationtypeslidetoleft)
- [ShowAnimationType.SlideToRight](#showanimationtypeslidetoright)
- [ShowAnimationType.SlideToTop](#showanimationtypeslidetotop)
- [Stat](#stat)
  - [displayName](#displayname-6)
  - [hasIcon](#hasicon)
  - [iconPath](#iconpath-2)
  - [id](#id-1)
  - [maxValueStat](#maxvaluestat)
  - [name](#name-11)
- [StatManager](#statmanager)
  - [getStatByGuid](#getstatbyguid)
  - [getStatByName](#getstatbyname)
  - [stats](#stats)
- [StatReference](#statreference)
  - [guid](#guid-12)
  - [maxStat](#maxstat)
  - [stat](#stat-1)
- [TGUI\_Vector2](#tgui_vector2)
  - [x](#x-1)
  - [y](#y-1)
- [TagReferenceList](#tagreferencelist)
  - [containsTag](#containstag)
- [Test](#test)
  - [colorados](#colorados)
- [TileLayer](#tilelayer)
  - [fill](#fill)
  - [getHeightOffset](#getheightoffset)
  - [getTile](#gettile)
  - [setHeightOffset](#setheightoffset)
  - [setTile](#settile)
  - [tileHeight](#tileheight)
  - [tileWidth](#tilewidth)
- [TileMap](#tilemap)
  - [getAreaByName](#getareabyname)
  - [getLayer](#getlayer)
  - [getLayerByName](#getlayerbyname)
  - [layers](#layers)
  - [pathLayer](#pathlayer-1)
  - [pixelSizeX](#pixelsizex)
  - [pixelSizeY](#pixelsizey)
  - [tileLayer](#tilelayer-1)
  - [tilesX](#tilesx)
  - [tilesY](#tilesy)
  - [unitLayer](#unitlayer)
- [Time](#time)
  - [isValid](#isvalid-1)
  - [isZero](#iszero-1)
- [TraderComponent](#tradercomponent)
  - [items](#items-3)
- [Unit](#unit)
  - [abortCurrentCommand](#abortcurrentcommand)
  - [addExperience](#addexperience)
  - [addItem](#additem)
  - [addItemByName](#additembyname)
  - [angle](#angle)
  - [attack](#attack)
  - [attackUnit](#attackunit)
  - [buyTraderItemAt](#buytraderitemat)
  - [canExecuteReply](#canexecutereply)
  - [canPayTraderItemAt](#canpaytraderitemat)
  - [canUnlockAbility](#canunlockability)
  - [castSpell](#castspell)
  - [class](#class-1)
  - [currentDialogOption](#currentdialogoption)
  - [dialog](#dialog-1)
  - [direction](#direction)
  - [displayColoredText](#displaycoloredtext)
  - [displayText](#displaytext)
  - [dropInventoryItem](#dropinventoryitem)
  - [equipment](#equipment-1)
  - [executeDialogReply](#executedialogreply)
  - [findNearestEnemy](#findnearestenemy)
  - [finishDialog](#finishdialog)
  - [getStat](#getstat)
  - [getStatByName](#getstatbyname-1)
  - [hasAbility](#hasability)
  - [heal](#heal)
  - [hit](#hit)
  - [increaseStat](#increasestat)
  - [interactionObject](#interactionobject)
  - [interactionUnit](#interactionunit)
  - [inventory](#inventory-1)
  - [isAlive](#isalive)
  - [isAnimationFinished](#isanimationfinished)
  - [isAttacking](#isattacking)
  - [isMoving](#ismoving)
  - [isRunning](#isrunning)
  - [isSelectedHero](#isselectedhero)
  - [lookAt](#lookat)
  - [moveBodyByWithVelocity](#movebodybywithvelocity)
  - [moveBy](#moveby)
  - [moveTo](#moveto)
  - [moveToArea](#movetoarea)
  - [object](#object-2)
  - [pauseCommands](#pausecommands)
  - [position](#position-1)
  - [resetNextDialog](#resetnextdialog)
  - [resources](#resources-2)
  - [respawn](#respawn)
  - [selectAbilityAt](#selectabilityat)
  - [selectNextAbility](#selectnextability)
  - [selectPreviousAbility](#selectpreviousability)
  - [selectedAbilityIndex](#selectedabilityindex)
  - [setPosition](#setposition)
  - [speed](#speed)
  - [startAnimation](#startanimation)
  - [startDefaultAnimation](#startdefaultanimation)
  - [startRunning](#startrunning)
  - [startWalkAnimation](#startwalkanimation)
  - [stop](#stop-1)
  - [stopCommandPause](#stopcommandpause)
  - [stopInteraction](#stopinteraction)
  - [stopRunning](#stoprunning)
  - [takeAllLootItems](#takealllootitems)
  - [takeLootItemStack](#takelootitemstack)
  - [talkWithObject](#talkwithobject)
  - [team](#team)
  - [unlockAbility](#unlockability)
  - [useAbilityAtIndex](#useabilityatindex)
  - [useInventoryItem](#useinventoryitem)
  - [useSelectedAbilityAt](#useselectedabilityat)
- [UnitEffect](#uniteffect)
  - [displayName](#displayname-7)
  - [guid](#guid-13)
  - [iconPath](#iconpath-3)
  - [name](#name-12)
- [UnitEffectManager](#uniteffectmanager)
  - [getUnitEffectByName](#getuniteffectbyname)
  - [unitEffects](#uniteffects)
- [UnitEffectReference](#uniteffectreference)
  - [UnitEffect](#uniteffect-1)
  - [guid](#guid-14)
- [UnitTeam](#unitteam)
- [UnitTeam.Enemy](#unitteamenemy)
- [UnitTeam.Neutral](#unitteamneutral)
- [UnitTeam.Player](#unitteamplayer)
- [Vector2](#vector2)
  - [angle](#angle-1)
  - [clear](#clear-1)
  - [length](#length)
  - [x](#x-2)
  - [y](#y-2)
- [Widget](#widget)
  - [addChild](#addchild)
  - [addColumn](#addcolumn)
  - [addItem](#additem-1)
  - [addLine](#addline)
  - [clearColumns](#clearcolumns)
  - [clearItems](#clearitems)
  - [clone](#clone)
  - [enabled](#enabled)
  - [findWidget](#findwidget)
  - [focusable](#focusable)
  - [focused](#focused)
  - [hideWithEffect](#hidewitheffect)
  - [isAnimationPlaying](#isanimationplaying)
  - [isContainer](#iscontainer)
  - [itemHeight](#itemheight)
  - [loadItemIcon](#loaditemicon)
  - [loadTexture](#loadtexture)
  - [maximum](#maximum)
  - [minimum](#minimum)
  - [name](#name-13)
  - [onAnimationFinished](#onanimationfinished)
  - [onClick](#onclick)
  - [onFocus](#onfocus)
  - [onMouseEnter](#onmouseenter)
  - [onMouseLeave](#onmouseleave)
  - [onRightClick](#onrightclick)
  - [onUnfocus](#onunfocus)
  - [onValueChange](#onvaluechange)
  - [opacity](#opacity-1)
  - [parent](#parent)
  - [playVideo](#playvideo)
  - [position](#position-2)
  - [removeAllWidgets](#removeallwidgets)
  - [removeChild](#removechild)
  - [renderModelAnimation](#rendermodelanimation)
  - [selectedItemIndex](#selecteditemindex)
  - [setHeight](#setheight)
  - [setIconSize](#seticonsize)
  - [setSize](#setsize)
  - [setWidth](#setwidth)
  - [showWithEffect](#showwitheffect)
  - [size](#size-1)
  - [text](#text-6)
  - [textSize](#textsize)
  - [tooltip](#tooltip)
  - [value](#value)
  - [visible](#visible-1)
- [colors](#colors)
- [colors.black](#colorsblack)
- [colors.blue](#colorsblue)
- [colors.green](#colorsgreen)
- [colors.red](#colorsred)
- [colors.white](#colorswhite)
- [colors.yellow](#colorsyellow)
- [gameEventType](#gameeventtype)
- [gameEventType.Custom](#gameeventtypecustom)
- [gameEventType.HeroSelectionChanged](#gameeventtypeheroselectionchanged)
- [gameEventType.HeroStatChanged](#gameeventtypeherostatchanged)
- [gameEventType.LoadLevelStarted](#gameeventtypeloadlevelstarted)
- [gameEventType.PlayVideo](#gameeventtypeplayvideo)
- [gameEventType.QuestObjectiveStateChanged](#gameeventtypequestobjectivestatechanged)
- [gameEventType.QuestStarted](#gameeventtypequeststarted)
- [gameEventType.QuestStateChanged](#gameeventtypequeststatechanged)
- [gameEventType.UnitDied](#gameeventtypeunitdied)
- [gameEventType.VideoFinished](#gameeventtypevideofinished)

# Ability

## displayName


```lua
string
```

Display name of the ability

## guid


```lua
Guid
```

Ability guid

## iconPath


```lua
string
```

Path to the ability icon

## name


```lua
string
```

Name of the ability

## soundPath


```lua
string
```

Path to the ability sound


---

# AbilityEntry

## ability


```lua
Ability
```

Ability of this entry


---

# AbilityManager

## abilities


```lua
Ability[]
```

All Abilities

## getAbilityByName


```lua
function AbilityManager.getAbilityByName(self: AbilityManager, name: string)
  -> Ability
```

 returns an ability by its name

@*param* `name` — Name of the ability


---

# AbilityReference

## Ability


```lua
Ability
```

Returns the Ability of this reference

## guid


```lua
Guid
```

Guid of the Ability


---

# AnimationMode

```lua
{
    Loop: integer = 0,
    LoopBackAndForth: integer = 1,
    PlayOnce: integer = 2,
}
```


---

# AnimationMode.Loop


---

# AnimationMode.LoopBackAndForth


---

# AnimationMode.PlayOnce


---

# Area

## color


```lua
Color
```

Color of the area

## getRandomPositionInArea


```lua
function Area.getRandomPositionInArea(self: Area)
  -> Vector2
```

 Returns a random position inside this area

## isPointInside


```lua
function Area.isPointInside(self: Area, x: number, y: number)
  -> boolean
```

 Returns if an area is inside a specified position

@*param* `x` — X coordinate

@*param* `y` — Y coordinate

## name


```lua
string
```

Name of the area


---

# CameraSettings

## attachToHero


```lua
boolean
```

Is the camera attached to the hero

## object


```lua
Object
```

Object attached to the camera


---

# CharacterClass

## abilities


```lua
AbilityEntry[]
```

Abilties of this class

## displayName


```lua
string
```

Display name of the character class

## name


```lua
string
```

Name of the character class


---

# CharacterClassReference

## guid


```lua
Guid
```

Guid of the character class


---

# Color

## a


```lua
integer
```

alpha value of the color(0-255)

## b


```lua
integer
```

blue value of the color(0-255)

## g


```lua
integer
```

green value of the color(0-255)

## r


```lua
integer
```

red value of the color(0-255)


---

# ColumnAlignment

```lua
{
    left: integer = 0,
    center: integer = 1,
    right: integer = 2,
}
```


---

# ColumnAlignment.center


---

# ColumnAlignment.left


---

# ColumnAlignment.right


---

# Container

## widgets


```lua
Widget[]
```

Widgets of this container


---

# Cutscene

## background


```lua
CutsceneBackground
```

Background of the cutscene

## dialogs


```lua
CutsceneDialog[]
```

Dialogs of the cutscene

## title


```lua
string
```

Title of the cutscene


---

# CutsceneBackground

## hasImage


```lua
boolean
```

Returns if the background has an image

## imagePath


```lua
string
```

Image path

## levelPath


```lua
string
```

Path to the level to be loaded


---

# CutsceneDialog

## background


```lua
CutsceneBackground
```

Background of the dialog

## hasVideo


```lua
boolean
```

Returns if this dialog contains a video

## isVideoLooped


```lua
boolean
```

Returns if the dialog video is looped

## text


```lua
string
```

Text of the dialog

## videoPath


```lua
string
```

Path to the video of this dialog


---

# DamageType

## name


```lua
string
```

Name of the stat


---

# DamageTypeManager

## damageTypes


```lua
DamageType[]
```

All damage types

## getDamageTypeByName


```lua
function DamageTypeManager.getDamageTypeByName(self: DamageTypeManager, damageTypeName: string)
  -> DamageType
```

 Returns a damage type by its name

@*param* `damageTypeName` — Name of the damage type


---

# Dialog

## dialogs


```lua
Dialog[]
```

All dialogs


---

# DialogManager

## getDialogByGuid


```lua
function DialogManager.getDialogByGuid(self: DialogManager, dialogGuid: Guid)
  -> Dialog
```

 returns a dialog by its Guid

@*param* `dialogGuid` — of the dialog


---

# DialogOption

## text


```lua
string
```

Text of this dialog option


---

# Equipment

## equipItem


```lua
function Equipment.equipItem(self: Equipment, item: Item)
  -> Returns: Item
```

 equip a specific item

@*param* `item` — to equip

@*return* `Returns` — the item now at the cursor(e.g. the item previously equipped)

## unequipItem


```lua
function Equipment.unequipItem(self: Equipment, slotIndex: integer)
  -> Returns: Item
```

 unequip a specific item

@*param* `slotIndex` — Equipment slot index

@*return* `Returns` — the item now at the cursor(the item previously at this slot)


---

# GameEvent

## addVariable


```lua
function GameEvent.addVariable(self: GameEvent, name: string, value: boolean)
```

 sets a named value to a boolean value

@*param* `name` — Name of the value

## findVariable


```lua
function GameEvent.findVariable(self: GameEvent, variableName: string)
  -> ScriptValue
```

 returns a variable by its name

@*param* `variableName` — Name of the variable

## type


```lua
gameEventType
```

Type of this event

## userType


```lua
string
```

User type of this event

## variables


```lua
ScriptValueContainer
```

Variables of this event


---

# GameSettings

## musicVolume


```lua
number
```

Music volume

## soundVolume


```lua
number
```

Sound volume


---

# Guid

## clear


```lua
function Guid.clear(self: Guid)
```

 clear Guid(Zero all values)

## isValid


```lua
boolean
```

returns if the guid is valid

## isZero


```lua
boolean
```

returns if the guid is zero

## toString


```lua
function Guid.toString(self: Guid)
  -> Guid: string
```

 returns the guid as a string

@*return* `Guid` — as string


---

# GuidReference

## guid


```lua
Guid
```

Current GUID


---

# Hero

## class


```lua
string
```

Character class name

## name


```lua
string
```

Name of the hero


---

# Inventory

## items


```lua
Item[]
```

All items in the inventory(nil-entries for empty slots)


---

# Item

## displayName


```lua
string
```

Display name of the item

## equip


```lua
function Item.equip(self: Item)
```

 Equip item

## imagePath


```lua
string
```

Path of the item image

## name


```lua
string
```

Developer name of the item


---

# ItemManager

## getItemByName


```lua
function ItemManager.getItemByName(self: ItemManager, name: string)
  -> Item
```

 returns an item by its name

@*param* `name` — Name of the item

## items


```lua
Item[]
```

Array with all items


---

# ItemReference

## guid


```lua
Guid
```

Guid of the item

## item


```lua
Item
```

Returns the item of this reference


---

# ItemStack

## count


```lua
integer
```

Amount of items in this stack

## item


```lua
Item
```

Returns the item of this reference


---

# LoadingScreenData

## text


```lua
string
```

Text of the loading screen

## texture


```lua
string
```

Path to the loading texture

## title


```lua
string
```

Title of the loading screen


---

# LocalizedTextManager

## currentLanguage


```lua
string
```

Gets/Sets the current language

## getTextByGuid


```lua
function LocalizedTextManager.getTextByGuid(self: LocalizedTextManager, guid: Guid)
  -> Localized: string
```

 Returns a localized text via Guid

@*param* `guid` — Guid of the text

@*return* `Localized` — text


---

# LocalizedTextReference

## guid


```lua
Guid
```

Guid of the stat

## text


```lua
string
```

Returns the localized text


---

# LootComponent

## items


```lua
ItemStack[]
```

Loot items

## resources


```lua
ResourceContainer
```

Loot resources


---

# MapLayer

## asObjectLayer


```lua
function MapLayer.asObjectLayer(self: MapLayer)
  -> ObjectLayer
```

 returns the layer as an ObjectLayer or nil if it is not an object layer

## asPathLayer


```lua
function MapLayer.asPathLayer(self: MapLayer)
  -> PathLayer
```

 returns the layer as an PathLayer or nil if it is not a path layer

## asTileLayer


```lua
function MapLayer.asTileLayer(self: MapLayer)
  -> TileLayer
```

 returns the layer as an TileLayer or nil if it is not an tile layer

## isScreenLayer


```lua
boolean
```

Set/Get if this layer is a screen space layer

## name


```lua
string
```

Name of the layer

## visible


```lua
boolean
```

Visible state of the layer


---

# MeshObjectData

## animationIndex


```lua
integer
```

Index of the animation

## rotationX


```lua
number
```

Rotation around the x axis

## rotationY


```lua
number
```

Rotation around the y axis

## rotationZ


```lua
number
```

Rotation around the z axis

## z


```lua
number
```

z coordinate(Depth)


---

# Object

## center


```lua
Vector2
```

Center of this object

## displayName


```lua
string
```

Display name of the object

## fragmentShader


```lua
ShaderReference
```

Fragment shader of this object

## id


```lua
integer
```

Unique ID of this object

## identifier


```lua
string
```

Identifier of this object. Can be used with special events

## interactionCursor


```lua
string
```

Interaction cursor of this object

## loot


```lua
LootComponent
```

Returns the Loot component of this object(If this object contains one)

## mesh


```lua
MeshObjectData
```

Returns the mesh of this object(If this object is a mesh)

## opacity


```lua
number
```

Opacity of this object

## origin


```lua
Vector2
```

Origin of this object

## physicsBody


```lua
PhysicsBodyComponent
```

Returns the Physics body component of this object(If this object contains one)

## position


```lua
Vector2
```

Position of this object

## rotation


```lua
number
```

Rotation of this object in degree

## runAction


```lua
function Object.runAction(self: Object, action: ObjectAction)
```

 runs an action for an object

@*param* `action` — Action that should be executed

## scale


```lua
number
```

Scale of this object

## setImage


```lua
function Object.setImage(self: Object, imageId: integer)
```

 sets the image of this object

@*param* `imageId` — Image ID

## size


```lua
Vector2
```

Size of this object

## trader


```lua
TraderComponent
```

Returns the Trader component of this object(If this object contains one)

## variables


```lua
ScriptValueContainer
```

Variables of this object

## vertexShader


```lua
ShaderReference
```

Vertext shader of this object

## x


```lua
number
```

X coordinate

## y


```lua
number
```

Y coordinate


---

# ObjectAction


---

# ObjectLayer

## addObject


```lua
function ObjectLayer.addObject(self: ObjectLayer)
  -> Object
```

 Adds a new object to the layer

## objects


```lua
Object[]
```

Objects in this layer


---

# ObjectReference

## objectId


```lua
integer
```

Object ID


---

# PathLayer

## getWorldPositionAt


```lua
function PathLayer.getWorldPositionAt(self: PathLayer, x: integer, y: integer)
  -> Vector2
```

 returns the world position for a specified path coordinate

@*param* `x` — X tile coordinate

@*param* `y` — Y tile coordinate

## isWalkable


```lua
function PathLayer.isWalkable(self: PathLayer, x: integer, y: integer)
  -> boolean
```

 returns if the specified path coordinate is walkable

@*param* `x` — X tile coordinate

@*param* `y` — Y tile coordinate

## mapSizeX


```lua
integer
```

X map size

## mapSizeY


```lua
integer
```

Y map size

## setWalkable


```lua
function PathLayer.setWalkable(self: PathLayer, x: integer, y: integer, walkable: boolean)
```

 returns if the specified path coordinate is walkable

@*param* `x` — X tile coordinate

@*param* `y` — Y tile coordinate

@*param* `walkable` — New walkable state

## tileSizeX


```lua
integer
```

X tile size

## tileSizeY


```lua
integer
```

Y tile size


---

# PhysicsBodyComponent

## angularVelocity


```lua
number
```

Set the angular velocity of the physics body

## applyAngularImpulse


```lua
function PhysicsBodyComponent.applyAngularImpulse(self: PhysicsBodyComponent, impulse: number)
```

 Applies an angular impulse to the physics body

@*param* `impulse` — Angular impulse

## applyForce


```lua
function PhysicsBodyComponent.applyForce(self: PhysicsBodyComponent, force: Vector2)
```

 Applies a force to the physics body

@*param* `force` — Applied force

## applyLinearImpulse


```lua
function PhysicsBodyComponent.applyLinearImpulse(self: PhysicsBodyComponent, impulse: Vector2)
```

 Applies a linear impulse to the physics body

@*param* `impulse` — Linear impulse

## isFixtureInCollision


```lua
function PhysicsBodyComponent.isFixtureInCollision(self: PhysicsBodyComponent, fixtureIndex: integer)
  -> boolean
```

 returns if the fixture is currently in collision

@*param* `fixtureIndex` — Index of the fixture

## linarVelocity


```lua
Vector2
```

Set the linear velocity of the physics body

## setVelocity


```lua
function PhysicsBodyComponent.setVelocity(self: PhysicsBodyComponent, velocity: Vector2)
```

 sets the velocity of the physics body

@*param* `velocity` — New velocity

## stop


```lua
function PhysicsBodyComponent.stop(self: PhysicsBodyComponent)
```

 stop the Physics body instantly


---

# PrefabObjectReference

## guid


```lua
Guid
```

Guid of the Prefab


---

# Quest

## autoStart


```lua
boolean
```

Should the quest be started automatically

## displayName


```lua
string
```

Display name of the quest

## guid


```lua
Guid
```

Guid (Unique ID) of the quest

## name


```lua
string
```

Developer name of the quest

## showInQuestLog


```lua
boolean
```

Should the quest be displayed in the quest log

## text


```lua
string
```

Text of the quest


---

# QuestInstance

## objectives


```lua
QuestObjectiveState[]
```

Objectives of this quest

## quest


```lua
Quest
```

Quest of this quest instance

## state


```lua
QuestState
```

State of this quest


---

# QuestInstanceManager

## findQuest


```lua
function QuestInstanceManager.findQuest(self: QuestInstanceManager, questReference: any)
  -> QuestInstance
```

 Returns a quest by its reference

## quests


```lua
Quest[]
```

All quest instances


---

# QuestObjectiveState

## count


```lua
integer
```

Current amount of this objective

## neededCount


```lua
integer
```

Needed amount of this objective

## text


```lua
string
```

Text of this objective


---

# QuestReference

## guid


```lua
Guid
```

Guid of the quest

## quest


```lua
Quest
```

Returns the quest of this reference


---

# QuestState

```lua
{
    Active: integer = 0,
    Reachable: integer = 1,
    Finished: integer = 2,
    Inactive: integer = 3,
}
```


---

# QuestState.Active


---

# QuestState.Finished


---

# QuestState.Inactive


---

# QuestState.Reachable


---

# Resource

## displayName


```lua
string
```

Display name of the resource

## guid


```lua
Guid
```

Guid of the item

## iconPath


```lua
string
```

Path to the resource icon

## name


```lua
string
```

Developer name of the resource


---

# ResourceContainer

## addResourceAmount


```lua
function ResourceContainer.addResourceAmount(self: ResourceContainer, resourceReference: ResourceReference, amount: integer)
```

 add a specific resource amount

@*param* `resourceReference` — Resource type

@*param* `amount` — Amount to be added

## getResourceAmount


```lua
function ResourceContainer.getResourceAmount(self: ResourceContainer, resourceReference: ResourceReference)
  -> integer
```

 Returns the resource amount of a specific type

@*param* `resourceReference` — Resource type

## setResourceAmount


```lua
function ResourceContainer.setResourceAmount(self: ResourceContainer, resourceReference: ResourceReference, amount: integer)
```

 Set a specific resource amount

@*param* `resourceReference` — Resource type

@*param* `amount` — Amount to be set of this type


---

# ResourceManager

## getResourceByGuid


```lua
function ResourceManager.getResourceByGuid(self: ResourceManager, resourceGuid: Guid)
  -> Resource
```

 returns a resource by its Guid

@*param* `resourceGuid` — Guid of the resource

## getResourceByName


```lua
function ResourceManager.getResourceByName(self: ResourceManager, resourceName: string)
  -> Resource
```

 returns a resource by its name

@*param* `resourceName` — Name of the resource

## resources


```lua
Resource[]
```

All resources


---

# ResourceReference

## guid


```lua
Guid
```

Guid of the resource

## resource


```lua
Resource
```

Returns the item of this reference


---

# Savegame

## heroLevel


```lua
number
```

Hero level of this savegame

## level


```lua
string
```

Path to the current level of this savegame

## name


```lua
string
```

Name of this savegame

## screenshot


```lua
string
```

Path to the screenshot of this savegame


---

# ScriptValue

## description


```lua
string
```

Description of this value

## getBoolValue


```lua
function ScriptValue.getBoolValue(self: ScriptValue)
  -> boolean
```

 returns the current value as a boolean

## getColorValue


```lua
function ScriptValue.getColorValue(self: ScriptValue)
  -> Color
```

 returns the current value as a Color value

## getDoubleValue


```lua
function ScriptValue.getDoubleValue(self: ScriptValue)
  -> number
```

 returns the current value as an number value

## getFloatValue


```lua
function ScriptValue.getFloatValue(self: ScriptValue)
  -> number
```

 returns the current value as a float value

## getIntValue


```lua
function ScriptValue.getIntValue(self: ScriptValue)
  -> integer
```

 returns the current value as an integer value

## getStringValue


```lua
function ScriptValue.getStringValue(self: ScriptValue)
  -> string
```

 returns the current value as a string value

## getVector2Value


```lua
function ScriptValue.getVector2Value(self: ScriptValue)
  -> Vector2
```

 returns the current value as a Vector2 value

## name


```lua
string
```

Name of this value

## objectID


```lua
integer
```

returns the value as an object id

## setFloatValue


```lua
function ScriptValue.setFloatValue(self: ScriptValue, name: string, value: number)
```

 sets a named value to a float value

@*param* `name` — Name of the value

## setValue


```lua
function ScriptValue.setValue(self: ScriptValue, value: boolean)
```

 sets the current value to a boolean value


---

# ScriptValueContainer

## findValue


```lua
function ScriptValueContainer.findValue(self: ScriptValueContainer, name: string)
  -> ScriptValue
```

 returns a script value by name

@*param* `name` — Name of the value

## setValue


```lua
function ScriptValueContainer.setValue(self: ScriptValueContainer, name: string, value: boolean)
```

 sets a named value to a boolean value

@*param* `name` — Name of the value

## values


```lua
ScriptValue[]
```

Array with all script values


---

# ScriptValueMetaData

## description


```lua
string
```

Description of this value

## elements


```lua
ScriptValueContainer
```


---

# ShaderReference

## parameters


```lua
ScriptValueContainer
```

Shader parameters


---

# ShowAnimationType

```lua
{
    Fade: integer = 0,
    Scale: integer = 1,
    SlideToRight: integer = 2,
    SlideToLeft: integer = 3,
    SlideToBottom: integer = 4,
    SlideToTop: integer = 5,
}
```


---

# ShowAnimationType.Fade


---

# ShowAnimationType.Scale


---

# ShowAnimationType.SlideToBottom


---

# ShowAnimationType.SlideToLeft


---

# ShowAnimationType.SlideToRight


---

# ShowAnimationType.SlideToTop


---

# Stat

## displayName


```lua
string
```

Display name of the stat

## hasIcon


```lua
boolean
```

Returns if this stat has an icon

## iconPath


```lua
string
```

Icon path of this stat

## id


```lua
Guid
```

ID of the stat

## maxValueStat


```lua
Stat
```

Maximum value stat of this stat

## name


```lua
string
```

Name of the stat


---

# StatManager

## getStatByGuid


```lua
function StatManager.getStatByGuid(self: StatManager, guid: Guid)
```

 Returns a stat by its name

@*param* `guid` — Guid of the stat

## getStatByName


```lua
function StatManager.getStatByName(self: StatManager, name: string)
```

 Returns a stat by its name

@*param* `name` — Name of the stat

## stats


```lua
Stat[]
```

All stats


---

# StatReference

## guid


```lua
Guid
```

Guid of the stat

## maxStat


```lua
Stat
```

Returns the max stat of this reference(if the stat has a maximum value stat assigned)

## stat


```lua
Stat
```

Returns the stat of this reference


---

# TGUI_Vector2

## x


```lua
number
```

x coordinate of the vector

## y


```lua
number
```

y coordinate of the vector


---

# TagReferenceList

## containsTag


```lua
function TagReferenceList.containsTag(self: TagReferenceList, tag: string)
  -> boolean
```

 Returns if the tag list contains a specific tag

@*param* `tag` — Tag name


---

# Test

## colorados


```lua
colors
```


---

# TileLayer

## fill


```lua
function TileLayer.fill(self: TileLayer, tileID: integer)
```

 Fills the map with a specified tile coordinate

@*param* `tileID` — New tile ID

## getHeightOffset


```lua
function TileLayer.getHeightOffset(self: TileLayer, x: integer, y: integer)
  -> integer
```

 returns the height offset for a specified tile coordinate

@*param* `x` — X tile coordinate

@*param* `y` — Y tile coordinate

## getTile


```lua
function TileLayer.getTile(self: TileLayer, x: integer, y: integer)
  -> integer
```

 returns a tile ID for a specified tile coordinate

@*param* `x` — X tile coordinate

@*param* `y` — Y tile coordinate

## setHeightOffset


```lua
function TileLayer.setHeightOffset(self: TileLayer, x: integer, y: integer, heightOffset: integer)
```

 sets the height offset for a specified tile coordinate

@*param* `x` — X tile coordinate

@*param* `y` — Y tile coordinate

@*param* `heightOffset` — New height offset

## setTile


```lua
function TileLayer.setTile(self: TileLayer, x: integer, y: integer, tileID: integer)
```

 sets a tile ID for a specified tile coordinate

@*param* `x` — X tile coordinate

@*param* `y` — Y tile coordinate

@*param* `tileID` — New tile ID

## tileHeight


```lua
integer
```

Tile height

## tileWidth


```lua
integer
```

Tile width


---

# TileMap

## getAreaByName


```lua
function TileMap.getAreaByName(self: TileMap, name: string)
  -> Area
```

 returns an area by its name

@*param* `name` — Name of the area

## getLayer


```lua
function TileMap.getLayer(self: TileMap, index: integer)
  -> MapLayer
```

 returns a layer by its index

@*param* `index` — Index of the layer

## getLayerByName


```lua
function TileMap.getLayerByName(self: TileMap, name: string)
  -> MapLayer
```

 returns a layer by its name

@*param* `name` — Name of the layer

## layers


```lua
MapLayer[]
```

Layers of the map

## pathLayer


```lua
PathLayer
```

returns the path layer

## pixelSizeX


```lua
integer
```

Map x size in pixels

## pixelSizeY


```lua
integer
```

Map y size in pixels

## tileLayer


```lua
TileLayer
```

returns the first tile layer

## tilesX


```lua
integer
```

Tiles in the x coordinate

## tilesY


```lua
integer
```

Tiles in the y coordinate

## unitLayer


```lua
ObjectLayer
```

returns the unit layer


---

# Time

## isValid


```lua
boolean
```

returns if the guid is valid

## isZero


```lua
boolean
```

returns if the guid is zero


---

# TraderComponent

## items


```lua
ItemStack[]
```

Loot items


---

# Unit

## abortCurrentCommand


```lua
function Unit.abortCurrentCommand(self: Unit)
```

## addExperience


```lua
function Unit.addExperience(self: Unit, experience: integer)
```

 Add experience to this unit

@*param* `experience` — experience points to add

## addItem


```lua
function Unit.addItem(self: Unit, item: Item)
```

 add an item to the unit

@*param* `item` — item that should be added

## addItemByName


```lua
function Unit.addItemByName(self: Unit, itemName: string)
```

 add an item to the unit

@*param* `itemName` — Name of the item that should be added

## angle


```lua
number
```

Angle of this unit

## attack


```lua
function Unit.attack(self: Unit)
```

 tell the unit to attack at the current position

## attackUnit


```lua
function Unit.attackUnit(self: Unit, unit: Unit)
```

 tell the unit to attack a unit

@*param* `unit` — Unit that should be attacked

## buyTraderItemAt


```lua
function Unit.buyTraderItemAt(self: Unit, itemIndex: integer)
  -> Returns: boolean
```

 buy an item from the curren trader

@*param* `itemIndex` — Index of the item

@*return* `Returns` — if the item was bought

## canExecuteReply


```lua
function Unit.canExecuteReply(self: Unit, replyIndex: integer)
  -> boolean
```

 Returns if the dialog reply can be executed

@*param* `replyIndex` — Index of the reply

## canPayTraderItemAt


```lua
function Unit.canPayTraderItemAt(self: Unit, itemIndex: integer)
  -> Returns: boolean
```

 Check if an item can be bought from the curren trader

@*param* `itemIndex` — Index of the item

@*return* `Returns` — if the item was bought

## canUnlockAbility


```lua
function Unit.canUnlockAbility(self: Unit, ability: Ability)
  -> boolean
```

 Returns if the specified ability can be unlocked

@*param* `ability` — Ability that should be unlocked

## castSpell


```lua
function Unit.castSpell(self: Unit, position: Vector2)
```

 Cast the currently selected spell at a target position

@*param* `position` — Target position of the spell

## class


```lua
CharacterClass
```

Character class of this unit

## currentDialogOption


```lua
DialogOption
```

returns the current dialog option

## dialog


```lua
Dialog
```

returns the current dialog

## direction


```lua
integer
```

diretion index of this unit

## displayColoredText


```lua
function Unit.displayColoredText(self: Unit, text: string, duration: number, color: Color)
```

 displays a colored text above this unit for a fixed duration

@*param* `text` — Text to display

@*param* `duration` — How long the text should be displayed

@*param* `color` — Color of the text

## displayText


```lua
function Unit.displayText(self: Unit, text: string, duration: number)
```

 displays a text above this unit for a fixed duration

@*param* `text` — Text to display

@*param* `duration` — How long the text should be displayed

## dropInventoryItem


```lua
function Unit.dropInventoryItem(self: Unit, index: integer)
```

 Drop an inventory item

@*param* `index` — index of the item

## equipment


```lua
Equipment
```

returns the equipment of this unit

## executeDialogReply


```lua
function Unit.executeDialogReply(self: Unit, replyIndex: integer)
```

 Execute a specific dialog reply

@*param* `replyIndex` — Index of the reply

## findNearestEnemy


```lua
function Unit.findNearestEnemy(self: Unit, distance: number)
  -> closest: Unit
```

@*param* `distance` — Maximum distance

@*return* `closest` — enemy

## finishDialog


```lua
function Unit.finishDialog(self: Unit, dialogOption: DialogOption)
```

 Finish a specific dialog option

@*param* `dialogOption` — Dialog option that should be finished

## getStat


```lua
function Unit.getStat(self: Unit, stat: Stat)
  -> Value: number
```

 returns a stat value of a specified stat

@*param* `stat` — Stat

@*return* `Value` — of the stat

## getStatByName


```lua
function Unit.getStatByName(self: Unit, statName: string)
  -> Value: number
```

 returns a stat value by its stat name

@*param* `statName` — name of the stat

@*return* `Value` — of the stat

## hasAbility


```lua
function Unit.hasAbility(self: Unit, ability: Ability)
  -> boolean
```

 Returns if the unit already has the specified ability

@*param* `ability` — Ability

## heal


```lua
function Unit.heal(self: Unit, health: number)
```

@*param* `health` — Hitpoints added

## hit


```lua
function Unit.hit(self: Unit, damage: number)
```

@*param* `damage` — Damage dealt

## increaseStat


```lua
function Unit.increaseStat(self: Unit, stat: StatReference, offset: number)
```

 Adds an offset to a specified stat

@*param* `stat` — Stat reference

@*param* `offset` — Offset added to the stat

## interactionObject


```lua
Object
```

returns the current interaction object

## interactionUnit


```lua
Unit
```

returns the current interaction unit

## inventory


```lua
Inventory
```

returns the inventory of this unit

## isAlive


```lua
boolean
```

is this unit alive

## isAnimationFinished


```lua
boolean
```

is the current animation finished

## isAttacking


```lua
boolean
```

is this unit currently attacking

## isMoving


```lua
boolean
```

is this unit currently moving

## isRunning


```lua
boolean
```

is this unit currently running

## isSelectedHero


```lua
boolean
```

is this unit a selected hero

## lookAt


```lua
function Unit.lookAt(self: Unit, position: Vector2)
```

 Look at a world posiiton

@*param* `position` — Posiiton to look at

## moveBodyByWithVelocity


```lua
function Unit.moveBodyByWithVelocity(self: Unit, x: number, y: number)
```

 tell the unit to move using a defined velocity

@*param* `x` — velocity (x axis)

@*param* `y` — velocity (y axis)

## moveBy


```lua
function Unit.moveBy(self: Unit, x: number, y: number)
```

 tell the unit to move by a specific position

@*param* `x` — relative x coordinate

@*param* `y` — relative y coordinate

## moveTo


```lua
function Unit.moveTo(self: Unit, x: number, y: number)
```

 tell the unit to move to a specific position

@*param* `x` — x coordinate

@*param* `y` — y coordinate

## moveToArea


```lua
function Unit.moveToArea(self: Unit, area: string)
```

 tell the unit to move to an area

@*param* `area` — area name

## object


```lua
Object
```

returns the object of this unit

## pauseCommands


```lua
function Unit.pauseCommands(self: Unit, duration: Time)
```

 pauses all commands

@*param* `duration` — How long commands should be paused

## position


```lua
Vector2
```

position of this unit

## resetNextDialog


```lua
function Unit.resetNextDialog(self: Unit)
```

 Reset the next dialog of this unit

## resources


```lua
ResourceContainer
```

returns the resources of this unit

## respawn


```lua
function Unit.respawn(self: Unit)
```

 Respawn this unit

## selectAbilityAt


```lua
function Unit.selectAbilityAt(self: Unit, index: integer)
```

 Selects an ability

@*param* `index` — index of the ability

## selectNextAbility


```lua
function Unit.selectNextAbility(self: Unit)
```

 selects the next ability in the list of abilities

## selectPreviousAbility


```lua
function Unit.selectPreviousAbility(self: Unit)
```

 selects the previous ability in the list of abilities

## selectedAbilityIndex


```lua
integer
```

the current ability index

## setPosition


```lua
function Unit.setPosition(self: Unit, x: number, y: number)
```

 set the position of this unit

@*param* `x` — X coordinate

@*param* `y` — Y coordinate

## speed


```lua
integer
```

movement speed

## startAnimation


```lua
function Unit.startAnimation(self: Unit, animation: string, mode: AnimationMode, duration: integer)
```

 starts an animation

@*param* `animation` — Name of the animation

@*param* `mode` — Animation mode

@*param* `duration` — Duration(ms)

## startDefaultAnimation


```lua
function Unit.startDefaultAnimation(self: Unit)
```

 start the default animation for this unit

## startRunning


```lua
function Unit.startRunning(self: Unit)
```

 start running mode

## startWalkAnimation


```lua
function Unit.startWalkAnimation(self: Unit)
```

 start the walk animation of this unit

## stop


```lua
function Unit.stop(self: Unit)
```

 stop movement

## stopCommandPause


```lua
function Unit.stopCommandPause(self: Unit)
```

 stops the pause of the commands 

## stopInteraction


```lua
function Unit.stopInteraction(self: Unit)
```

 Stops interaction with the current object

## stopRunning


```lua
function Unit.stopRunning(self: Unit)
```

 stop running mode

## takeAllLootItems


```lua
function Unit.takeAllLootItems(self: Unit)
```

 Take all loot items of the currently active loot object

## takeLootItemStack


```lua
function Unit.takeLootItemStack(self: Unit, stackIndex: integer)
```

 Take a single loot stack of the currently looted object

@*param* `stackIndex` — index of the stack that should be taken

## talkWithObject


```lua
function Unit.talkWithObject(self: Unit, object: Object)
```

 Talk with a specified object

@*param* `object` — Object to talk with or nil to stop talking

## team


```lua
UnitTeam
```

team of this unit

## unlockAbility


```lua
function Unit.unlockAbility(self: Unit, ability: Ability)
```

 unlock a specific ability

@*param* `ability` — Ability that should be unlocked

## useAbilityAtIndex


```lua
function Unit.useAbilityAtIndex(self: Unit, abilityIndex: integer, position: Vector2)
```

 Use an ability with a specified target position

@*param* `abilityIndex` — index of the ability

@*param* `position` — Target position of the ability

## useInventoryItem


```lua
function Unit.useInventoryItem(self: Unit, index: integer)
```

 Use an inventory item

@*param* `index` — index of the item

## useSelectedAbilityAt


```lua
function Unit.useSelectedAbilityAt(self: Unit, position: Vector2)
```

 Use the currently selected ability with a specified target position

@*param* `position` — Target position of the ability


---

# UnitEffect

## displayName


```lua
string
```

Display name of the UnitEffect

## guid


```lua
Guid
```

UnitEffect guid

## iconPath


```lua
string
```

Path to the UnitEffect icon

## name


```lua
string
```

Name of the UnitEffect


---

# UnitEffectManager

## getUnitEffectByName


```lua
function UnitEffectManager.getUnitEffectByName(self: UnitEffectManager, name: string)
  -> UnitEffect
```

 returns an UnitEffect by its name

@*param* `name` — Name of the UnitEffect

## unitEffects


```lua
UnitEffect[]
```

All Abilities


---

# UnitEffectReference

## UnitEffect


```lua
UnitEffect
```

Returns the UnitEffect of this reference

## guid


```lua
Guid
```

Guid of the UnitEffect


---

# UnitTeam

```lua
{
    Neutral: integer = 0,
    Enemy: integer = 1,
    Player: integer = 2,
}
```


---

# UnitTeam.Enemy


---

# UnitTeam.Neutral


---

# UnitTeam.Player


---

# Vector2

## angle


```lua
number
```

angle of the vector

## clear


```lua
function Vector2.clear(self: Vector2)
```

 clear vector

## length


```lua
number
```

length of the vector

## x


```lua
number
```

x coordinate of the vector

## y


```lua
number
```

y coordinate of the vector


---

# Widget

## addChild


```lua
function Widget.addChild(self: Widget, child: Widget)
```

 Adds a child to this widget

@*param* `child` — Child to be added

## addColumn


```lua
function Widget.addColumn(self: Widget, text: string)
```

 adds a column via text

@*param* `text` — Text of the new column 

## addItem


```lua
function Widget.addItem(self: Widget, itemText: string)
```

 adds an item via text

@*param* `itemText` — Text of the item to be added

## addLine


```lua
function Widget.addLine(self: Widget, text: string)
```

 adds a new text to a ChatBox widget

@*param* `text` — Text to be added

## clearColumns


```lua
function Widget.clearColumns(self: Widget)
```

 Clear all columns of the widget

## clearItems


```lua
function Widget.clearItems(self: Widget)
```

 Clears all items of the widget

## clone


```lua
function Widget.clone(self: Widget)
  -> Widget
```

 Clones this widget and returns the copy

## enabled


```lua
boolean
```

Enabled state of the widget

## findWidget


```lua
function Widget.findWidget(self: Widget, name: string)
  -> Widget
```

 Returns a widget by its name

@*param* `name` — Name of the widget

## focusable


```lua
boolean
```

Focusable state of the widget

## focused


```lua
boolean
```

Focused state of the widget

## hideWithEffect


```lua
function Widget.hideWithEffect(self: Widget, animationType: ShowAnimationType, duration: number)
```

 Hides the widget using an effect

@*param* `animationType` — animation type

@*param* `duration` — Duration of the effect(seconds)

## isAnimationPlaying


```lua
boolean
```

Is this widget currently playing an animation

## isContainer


```lua
boolean
```

Returns if the widget is a container

## itemHeight


```lua
number
```

Item height of this widget(For ListView / ListBox widgets)

## loadItemIcon


```lua
function Widget.loadItemIcon(self: Widget, index: integer, texture: string)
```

 Loads an item icon via index

@*param* `index` — Index of the item

@*param* `texture` — Path to the icon texture 

## loadTexture


```lua
function Widget.loadTexture(self: Widget, texture: string)
```

 Load a texture of a widget

@*param* `texture` — Path to the texture

## maximum


```lua
number
```

Maximum value of the widget. Implemented for ProgressBar and Slider widgets

## minimum


```lua
number
```

Minimum value of the widget. Implemented for ProgressBar and Slider widgets

## name


```lua
string
```

Name of the widget

## onAnimationFinished


```lua
function
```

Callback function called the widget animation is finished

## onClick


```lua
function
```

Callback function called when the user clicks on this widget

## onFocus


```lua
function
```

Callback function called when the widget gets focused

## onMouseEnter


```lua
function
```

Callback function called when the user enters the widget with the mouse cursor

## onMouseLeave


```lua
function
```

Callback function called when the user leaves the widget with the mouse cursor

## onRightClick


```lua
function
```

Callback function called when the user right clicks on this widget

## onUnfocus


```lua
function
```

Callback function called when the widget gets unfocused

## onValueChange


```lua
function
```

Callback function called the value of the widget was changed

## opacity


```lua
number
```

Opacity(0-1)

## parent


```lua
Widget
```

Returns the parent widget

## playVideo


```lua
function Widget.playVideo(self: Widget, video: string, loop: boolean)
```

 Play a video(For VideoWidget)

@*param* `video` — Path of the video

@*param* `loop` — Should the video be looped

## position


```lua
TGUI_Vector2
```

Position of the widget

## removeAllWidgets


```lua
function Widget.removeAllWidgets(self: Widget)
```

 Removes all children from a widget

## removeChild


```lua
function Widget.removeChild(self: Widget, child: Widget)
```

 Removes a child from this widget

@*param* `child` — Child to be added

## renderModelAnimation


```lua
function Widget.renderModelAnimation(self: Widget, unit: Unit, animation: string)
  -> Returns: boolean
```

 Renders a model animation(For Canvas or Picture widgets)

@*param* `unit` — to be rendered

@*param* `animation` — Animation name

@*return* `Returns` — if the rendering is complete

## selectedItemIndex


```lua
integer
```

Currently selected item index(For ListView / ListBox widgets)

## setHeight


```lua
function Widget.setHeight(self: Widget, height: number)
```

 Sets the height of this widget

@*param* `height` — New height of the widget(Pixels)

## setIconSize


```lua
function Widget.setIconSize(self: Widget, sizeX: integer, sizeY: integer)
```

 sets the icon size for this widget

@*param* `sizeX` — Horizontal icon size(Pixels)

@*param* `sizeY` — Vertical icon size(Pixels)

## setSize


```lua
function Widget.setSize(self: Widget, width: number, height: number)
```

 Sets the size of this widget

@*param* `width` — New width of the widget(Pixels)

@*param* `height` — New height of the widget(Pixels)

## setWidth


```lua
function Widget.setWidth(self: Widget, width: number)
```

 Sets the width of this widget

@*param* `width` — New width of the widget(Pixels)

## showWithEffect


```lua
function Widget.showWithEffect(self: Widget, animationType: ShowAnimationType, duration: number)
```

 Shows the widget using an effect

@*param* `animationType` — animation type

@*param* `duration` — Duration of the effect(seconds)

## size


```lua
TGUI_Vector2
```

size of the widget

## text


```lua
string
```

Text of the widget

## textSize


```lua
integer
```

Text size(Pixels)

## tooltip


```lua
Widget
```

Tooltip of this widget

## value


```lua
number
```

Value of the widget. Implemented for ProgressBar and Slider widgets

## visible


```lua
boolean
```

Visible state of the widget


---

# colors

```lua
{
    black: integer = 0,
    red: integer = 2,
    green: integer = 4,
    yellow: integer = 8,
    blue: integer = 16,
    white: integer = 32,
}
```


---

# colors.black


---

# colors.blue


---

# colors.green


---

# colors.red


---

# colors.white


---

# colors.yellow


---

# gameEventType

```lua
{
    Custom: integer = 0,
    QuestStarted: integer = 1,
    QuestStateChanged: integer = 2,
    QuestObjectiveStateChanged: integer = 3,
    HeroStatChanged: integer = 4,
    UnitDied: integer = 5,
    PlayVideo: integer = 6,
    VideoFinished: integer = 7,
    HeroSelectionChanged: integer = 8,
    LoadLevelStarted: integer = 9,
}
```


---

# gameEventType.Custom


---

# gameEventType.HeroSelectionChanged


---

# gameEventType.HeroStatChanged


---

# gameEventType.LoadLevelStarted


---

# gameEventType.PlayVideo


---

# gameEventType.QuestObjectiveStateChanged


---

# gameEventType.QuestStarted


---

# gameEventType.QuestStateChanged


---

# gameEventType.UnitDied


---

# gameEventType.VideoFinished