## Summary
  * [Events](#events)
  * [Conditions](#conditions)
  * [Effects](#effects)
  * [Expressions](#expressions)
  * [Types](#types)
  * [Functions](#functions)
 
## Events
 
### At Time
An event that occurs at a given minecraft time in every world or only in specific worlds.
 
```java
at 18:00
at 7am in "world"
```
<details><summary>Syntaxes</summary><p>
 
```java
at %time% [in %worlds%]
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.3.4</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>false</td>
</table>
 
---
 
### On ([item] anvil prepare|prepare [item] anvil)
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] [skellett] ([item] anvil prepare|prepare [item] anvil)
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-itemstack
event-string
event-number
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>false</td>
</table>
 
---
 
### On ([un]hang[ing]|[un]hung) [entity] (remove|break|destroy|damage)
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] [skellett] ([un]hang[ing]|[un]hung) [entity] (remove|break|destroy|damage)
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-entity
event-entity
event-location
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On (block|crop) grow[ing]
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] [skellett] (block|crop) grow[ing]
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
past event-block
event-world
event-block
event-location
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On (hang|[entity] hung)
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] [skellett] (hang|[entity] hung)
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-player
event-entity
event-entity
event-block
event-location
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On (hotbar|held [(item|slot)]|inventory slot) (switch|change)
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] [skellett] (hotbar|held [(item|slot)]|inventory slot) (switch|change)
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-player
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On (multi[ple]|double)[ ][block][ ]place
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] [skellett] (multi[ple]|double)[ ][block][ ]place
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
past event-block
event-world
event-player
event-direction
event-block
event-location
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On (skellett[ ][(cord|proxy)]|bungee[ ][cord]) [player] (switch server[s]|server[s] switch)
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] [skellett] (skellett[ ][(cord|proxy)]|bungee[ ][cord]) [player] (switch server[s]|server[s] switch)
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-offlineplayer
event-uuid
event-string
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>false</td>
</table>
 
---
 
### On (skellett[ ][(cord|proxy)]|bungee[ ][cord]) player (disconnect|leave)
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] [skellett] (skellett[ ][(cord|proxy)]|bungee[ ][cord]) player (disconnect|leave)
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-offlineplayer
event-uuid
event-string
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>false</td>
</table>
 
---
 
### On (unhang|[entity] unhung)
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] [skellett] (unhang|[entity] unhung)
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-entity
event-entity
event-location
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On (vehicle|minecart|boat) move
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] [skellett] (vehicle|minecart|boat) move
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
past event-location
event-world
event-entity
event-entity
future event-location
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>false</td>
</table>
 
---
 
### On AoE Cloud Effect
Called when area effect cloud applies it's potion effect. This happens every 5 ticks by default.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] (area|AoE) [cloud] effect
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-potioneffecttype
event-entity
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev21</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>false</td>
</table>
 
---
 
### On Bed Enter
Called when a player starts sleeping.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] bed enter[ing]
[on] [player] enter[ing] [a] bed
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-player
event-block
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On Bed Leave
Called when a player leaves a bed.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] bed leav(e|ing)
[on] [player] leav(e|ing) [a] bed
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-player
event-block
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>false</td>
</table>
 
---
 
### On Block Damage
Called when a player starts to break a block. You can usually just use the leftclick event for this.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] block damag(ing|e)
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-player
event-block
event-location
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On Block Growth
Called when a crop grows. Alternative to new form of generic grow event.
 
```java
on crop growth
```
<details><summary>Syntaxes</summary><p>
 
```java
[on] (plant|crop|block) grow[(th|ing)] [[of] %itemtypes%]
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
past event-block
event-world
event-block
event-location
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-Fixes-V10</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On Book Edit
Called when a player edits a book
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] book (edit|change|write)
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-player
event-itemstack
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev31</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On Book Sign
Called when a player signs a book
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] book sign[ing]
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-player
event-itemstack
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev31</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On Break / Mine
Called when a block is broken by a player. If you use 'on mine', only events where the broken block dropped something will call the trigger.
 
```java
on mine
on break of stone
on mine of any ore
```
<details><summary>Syntaxes</summary><p>
 
```java
[on] [block] (break[ing]|min(e|ing)) [[of] %itemtypes%]
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
past event-block
event-world
event-player
event-entity
event-entity
event-block
event-location
future event-block
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0 (break), <i>unknown</i> (mine)</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On Bucket Empty
Called when a player empties a bucket. You can also use the place event with a check for water or lava.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] bucket empty[ing]
[on] [player] empty[ing] [a] bucket
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
past event-block
event-world
event-player
event-block
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On Bucket fill
Called when a player fills a bucket.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] bucket fill[ing]
[on] [player] fill[ing] [a] bucket
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-player
event-block
future event-block
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On Burn
Called when a block is destroyed by fire.
 
```java
on burn
on burn of wood, fences, or chests
```
<details><summary>Syntaxes</summary><p>
 
```java
[on] [block] burn[ing] [[of] %itemtypes%]
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-block
event-location
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On Can Build Check
Called when a player rightclicks on a block while holding a block or a placeable item. You can either cancel the event to prevent the block from being built, or uncancel it to allow it.
Please note that the data value of the block to be placed is not available in this event, only its ID.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] [block] can build check
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
past event-block
event-world
event-block
event-location
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0 (basic), 2.0 ([un]cancellable)</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>false</td>
</table>
 
---
 
### On Chat
Called whenever a player chats. Use chat format to change message format, use chat recipients to edit chat recipients.
 
```java
on chat:
	if player has permission "owner":
		set chat format to "<red>[player]<light gray>: <light red>[message]"
	else if player has permission "admin":
		set chat format to "<light red>[player]<light gray>: <orange>[message]"
	else: #default message format
		set chat format to "<orange>[player]<light gray>: <white>[message]"
```
<details><summary>Syntaxes</summary><p>
 
```java
[on] chat
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-player
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.4.1</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On Chunk Generate
Called after a new chunk was generated.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] chunk (generat|populat)(e|ing)
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-chunk
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>false</td>
</table>
 
---
 
### On Chunk Load
Called when a chunk loads. The chunk might or might not contain mobs when it's loaded.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] chunk load[ing]
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-chunk
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>false</td>
</table>
 
---
 
### On Chunk Unload
Called when a chunk is unloaded due to not being near any player. Cancel the event to force the server to keep the chunk loaded and thus keep simulating the chunk (e.g. physics, plant growth, minecarts, etc. will keep working and won't freeze).
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] chunk unload[ing]
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-chunk
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On Click
Called when a user clicks on a block, an entity or air with or without an item in their hand.
Please note that rightclick events with an empty hand while not looking at a block are not sent to the server, so there's no way to detect them.
 
```java
on click
on rightclick holding a fishing rod
on leftclick on a stone or obsidian
on rightclick on a creeper
on click with a sword
```
<details><summary>Syntaxes</summary><p>
 
```java
[on] [(right|left)(| |-)][mouse(| |-)]click[ing] [on %-entitydata/itemtype%] [(with|using|holding) %itemtype%]
[on] [(right|left)(| |-)][mouse(| |-)]click[ing] (with|using|holding) %itemtype% on %entitydata/itemtype%
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-player
event-entity
event-itemstack
event-block
event-direction
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On Combust
Called when an entity is set on fire, e.g. by fire or lava, a fireball, or by standing in direct sunlight (zombies, skeletons).
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] combust[ing]
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-entity
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On Command
Called when a player enters a command (not neccessarily a Skript command).
 
```java
on command
on command "/stop"
on command "pm Njol "
```
<details><summary>Syntaxes</summary><p>
 
```java
[on] command [%-string%]
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-player
event-commandsender
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On Connect
Called when the player connects to the server. This event is called before the player actually joins the server, so if you want to prevent players from joining you should prefer this event over on join.
 
```java
on connect:
	player doesn't have permission "VIP"
	number of players is larger than 20,	kick the player due to "The last 5 slots are reserved for VIP players."
```
<details><summary>Syntaxes</summary><p>
 
```java
[on] [player] connect[ing]
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-player
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>false</td>
</table>
 
---
 
### On Consume
Called when a player is done eating/drinking something, e.g. an apple, bread, meat, milk or a potion.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] [player] ((eat|drink)[ing]|consum(e|ing)) [[of] %itemtypes%]
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-player
event-itemstack
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On Craft
Called when a player crafts an item.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] [player] craft[ing] [[of] %itemtypes%]
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-inventory
event-slot
event-player
event-recipe
event-itemstack
event-clicktype
event-inventoryaction
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td><i>unknown</i> (before 2.1)</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On Creeper Power
Called when a creeper is struck by lighting and gets powered. Cancel the event to prevent the creeper from being powered.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] creeper power
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-entity
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On Damage
Called when an entity receives damage, e.g. by an attack from another entity, lava, fire, drowning, fall, suffocation, etc.
 
```java
on damage
on damage of a player
```
<details><summary>Syntaxes</summary><p>
 
```java
[on] damag(e|ing) [of %entitydata%]
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-projectile
event-damagecause
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On Death
Called when a living entity (including players) dies.
 
```java
on death
on death of player
on death of a wither or ender dragon:
	broadcast "A %entity% has been slain in %world%!"
```
<details><summary>Syntaxes</summary><p>
 
```java
[on] death [of %entitydatas%]
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-entity
event-projectile
event-damagecause
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On Dispense
Called when a dispenser dispenses an item.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] dispens(e|ing) [[of] %itemtypes%]
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-itemstack
event-block
event-location
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td><i>unknown</i> (before 2.1)</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On DownloadFile
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] [skutil[ities] ]file download
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-object
event-string
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On Drop
Called when a player drops an item from his inventory.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] [player] drop[ing] [[of] %itemtypes%]
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-player
event-itementity
event-itemstack
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td><i>unknown</i> (before 2.1)</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On Enderman/Sheep/Silverfish
Called when an enderman places or picks up a block, a sheep eats grass or a silverfish boops into/out of a block respectively.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] enderman place
[on] enderman pickup
[on] sheep eat
[on] silverfish enter
[on] silverfish exit
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-entity
event-block
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On Entity Dismount
Called when an entity dismounts.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] dismount[ing]
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-entity
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev13b</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On Entity Mount
Called when entity starts riding another.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] mount[ing]
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-entity
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev13b</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On Experience Spawn
Called whenever experience is about to spawn. This is a helper event for easily being able to stop xp from spawning, as all you can currently do is cancel the event.
Please note that it's impossible to detect xp orbs spawned by plugins (including Skript) with Bukkit, thus make sure that you have no such plugins if you don't want any xp orbs to spawn. (Many plugins that only change the experience dropped by blocks or entities will be detected without problems though)
 
```java
on xp spawn:
	world is "minigame_world"
	cancel event
```
<details><summary>Syntaxes</summary><p>
 
```java
[on] [e]xp[erience] [orb] spawn
[on] spawn of [a[n]] [e]xp[erience] [orb]
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-experience
event-location
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On Explode
Called when an entity (a primed TNT or a creeper) explodes.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] explo(d(e|ing)|sion)
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-entity
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On Explosion Prime
Called when an explosive is primed, i.e. an entity will explode shortly. Creepers can abort the explosion if the player gets too far away, while TNT will explode for sure after a short time.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] explosion prime
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-entity
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On Fade
Called when a block 'fades away', e.g. ice or snow melts.
 
```java
on fade of snow or ice
```
<details><summary>Syntaxes</summary><p>
 
```java
[on] [block] fad(e|ing) [[of] %itemtypes%]
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
past event-block
event-world
event-block
event-location
future event-block
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On FileCopy
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] [skutil[ities] ]file copy
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-object
event-string
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On FileCreation
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] [skutil[ities] ]file creat(ion|e)
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-object
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On FileDeletion
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] [skutil[ities] ]file delet(ion|e)
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-object
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On FileMove
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] [skutil[ities] ]file move
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-object
event-string
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On FileRename
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] [skutil[ities] ]file rename
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-object
event-string
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On FileWipe
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] [skutil[ities] ]file (wipe|reset|clear)
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-object
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On FileWrite
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] [skutil[ities] ]file write
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-object
event-string
event-number
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On FileZip
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] [skutil[ities] ]file zip
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-object
event-string
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On First Join
Called when a player joins the server for the first time.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] first (join|login)
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-player
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.3.7</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>false</td>
</table>
 
---
 
### On Fishing
Called when a player fishes something. This is not of much use yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] [player] fish[ing]
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-player
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On Flight Toggle
Called when a players stops/starts flying.
 
```java
on flight toggle:
	if {game::%player%::playing} exists:
		cancel event
```
<details><summary>Syntaxes</summary><p>
 
```java
[on] [player] flight togg(e|ing)
[on] [player] toggl(e|ing) flight
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-player
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev36</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On Flow
Called when a blocks flows or teleports to another block. This not only applies to water and lava, but teleporting dragon eggs as well.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] [block] flow[ing]
[on] block mov(e|ing)
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-block
event-location
future event-block
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On Form
Called when a block is created, but not by a player, e.g. snow forms due to snowfall, water freezes in cold biomes. This isn't called when block spreads (mushroom growth, water physics etc.), as it has its own event (see spread event).
 
```java
on form of snow
on form of a mushroom
```
<details><summary>Syntaxes</summary><p>
 
```java
[on] [block] form[ing] [[of] %itemtypes%]
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
past event-block
event-world
event-block
event-location
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On Fuel Burn
Called when a furnace burns an item from its fuel slot.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] fuel burn[ing]
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-block
event-location
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On Gamemode Change
Called when a player's gamemode changes.
 
```java
on gamemode change
on gamemode change to adventure
```
<details><summary>Syntaxes</summary><p>
 
```java
[on] game[ ]mode change [to %gamemode%]
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-player
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On Gliding State Change
Called when an entity toggles glider on or off, or when server toggles gliding state of an entity forcibly.
 
```java
on toggling gliding:
	cancel the event # bad idea, but you CAN do it!
```
<details><summary>Syntaxes</summary><p>
 
```java
[on] (gliding state change|toggl(e|ing) gliding)
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-entity
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev21</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On Grow
Called when a tree, giant mushroom or plant grows to next stage.
 
```java
on grow
on grow of a tree
on grow of a huge jungle tree
```
<details><summary>Syntaxes</summary><p>
 
```java
[on] grow [of (%-structuretype%|%-itemtype%)]
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
past event-block
event-world
event-block
event-location
future event-block
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0 (2.2-dev20 for plants)</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On Heal
Called when an entity is healed, e.g. by eating (players), being fed (pets), or by the effect of a potion of healing (overworld mobs) or harm (nether mobs).
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] heal[ing]
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-entity
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On Hunger Meter Change
Called when the hunger bar of a player changes, i.e. either increases by eating or decreases over time.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] (food|hunger) (level|met(er|re)|bar) chang(e|ing)
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-entity
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.4.4</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On Ignition
Called when a block starts burning, i.e. a fire block is placed next to it and this block is flammable.
The burn event will be called when the block is about do be destroyed by the fire.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] [block] ignit(e|ion)
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-player
event-block
event-location
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On Inventory Click
Called when clicking on inventory slot.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] [player] inventory(-| )click[ing] [[at] %itemtypes%]
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-inventory
event-slot
event-player
event-recipe
event-itemstack
event-clicktype
event-inventoryaction
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-Fixes-V10</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On Inventory Close
Called when player's currently viewed inventory is closed.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] inventory clos(ing|e[d])
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-inventory
event-player
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev21</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>false</td>
</table>
 
---
 
### On Inventory Open
Called when an inventory is opened for player.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] inventory open[ed]
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-inventory
event-player
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev21</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On Item Break
Called when a player breaks his tool because its damage reached the maximum value.
This event cannot be cancelled.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] [player] tool break[ing]
[on] [player] break[ing] (a|the|) tool
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-player
event-itemstack
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.1.1</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>false</td>
</table>
 
---
 
### On Item Despawn
Called when an item is about to be despawned from the world, usually 5 minutes after it was dropped.
 
```java
on item despawn of diamond:
	send "Not my precious!"
	cancel event
```
<details><summary>Syntaxes</summary><p>
 
```java
[on] (item[ ][stack]|[item] %-itemtypes%) despawn[ing]
[on] [item[ ][stack]] despawn[ing] [[of] %-itemtypes%]
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-entity
event-itementity
event-itemstack
event-location
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev35</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On Item Merge
Called when dropped items merge into a single stack.
 
```java
on item merge of gold blocks:
	cancel event
```
<details><summary>Syntaxes</summary><p>
 
```java
[on] (item[ ][stack]|[item] %-itemtypes%) merg(e|ing)
[on] item[ ][stack] merg(e|ing) [[of] %-itemtypes%]
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-entity
event-itementity
event-itemstack
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev35</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On Item Spawn
Called whenever an item stack is spawned in a world, e.g. as drop of a block or mob, a player throwing items out of his inventory, or a dispenser dispensing an item (not shooting it).
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] item spawn[ing] [[of] %itemtypes%]
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-entity
event-itemstack
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td><i>unknown</i> (before 2.1)</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On Join
Called when the player joins the server. The player is already in a world when this event is called, so if you want to prevent players from joining you should prefer on connect over this event.
 
```java
on join:
	message "Welcome on our awesome server!"
	broadcast "%player% just joined the server!"
```
<details><summary>Syntaxes</summary><p>
 
```java
[on] [player] (login|logging in|join[ing])
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-player
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>false</td>
</table>
 
---
 
### On Kick
Called when a player is kicked from the server. You can change the kick message or cancel the event entirely.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] [player] (kick|being kicked)
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-player
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On Language Change
Called after a player changed their language in the game settings. You can use the language expression to get the current language of the player.
This event requires Minecraft 1.12+.
 
```java
on language change:
	if player's language starts with "en":
		send "Hello!"
```
<details><summary>Syntaxes</summary><p>
 
```java
[on] [player] (language|locale) chang(e|ing)
[on] [player] chang(e|ing) (language|locale)
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-player
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev37</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>false</td>
</table>
 
---
 
### On Leaves Decay
Called when a leaf block decays due to not being connected to a tree.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] leaves decay[ing]
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-block
event-location
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On Level Change
Called when a player's level changes, e.g. by gathering experience or by enchanting something.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] [player] level [change]
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-player
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>false</td>
</table>
 
---
 
### On Lightning Strike
Called when lightning strikes.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] lightning [strike]
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On Move On
Called when a player moves onto a certain type of block. Please note that using this event can cause lag if there are many players online.
 
```java
on walking on dirt or grass
on stepping on stone
```
<details><summary>Syntaxes</summary><p>
 
```java
[on] (step|walk)[ing] (on|over) %*itemtypes%
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-player
event-teleportcause
event-block
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On Physics
Called when a physics check is done on a block. By cancelling this event you can prevent some things from happening, e.g. sand falling, dirt turning into grass, torches dropping if their supporting block is destroyed, etc.Please note that using this event might cause quite some lag since it gets called extremely often.
 
```java
# prevents sand from falling
on block physics:
	block is sand
	cancel event
```
<details><summary>Syntaxes</summary><p>
 
```java
[on] [block] physics
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-block
event-location
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.4.6</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On Pick Up
Called when a player picks up an item. Please note that the item is still on the ground when this event is called.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] [player] (pick[ ]up|picking up) [[of] %itemtypes%]
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-player
event-itementity
event-itemstack
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td><i>unknown</i> (before 2.1)</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On Pig Zap
Called when a pig is stroke by lightning and transformed into a zombie pigman. Cancel the event to prevent the transformation.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] pig[ ]zap
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-entity
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On Piston Extend
Called when a piston is about to extend.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] piston extend[ing]
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-block
event-location
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On Piston Retract
Called when a piston is about to retract.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] piston retract[ing]
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-block
event-location
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On Place
Called when a player places a block.
 
```java
on place
on place of a furnace, workbench or chest
```
<details><summary>Syntaxes</summary><p>
 
```java
[on] [block] (plac(e|ing)|build[ing]) [[of] %itemtypes%]
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
past event-block
event-world
event-player
event-entity
event-entity
event-direction
event-block
event-location
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On Player World Change
Called when a player enters a world. Does not work with other entities!
 
```java
on player world change:
	world is "city"
	send "Welcome to the City!"
```
<details><summary>Syntaxes</summary><p>
 
```java
[on] [player] world chang(ing|e[d])
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-player
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev28</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>false</td>
</table>
 
---
 
### On Portal
Called when a player uses a nether or end portal. Cancel the event to prevent the player from teleporting.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] [player] portal
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-player
event-teleportcause
event-block
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On Portal Create
Called when a portal is created, either by a player or mob lighting an obsidian frame on fire, or by a nether portal creating its teleportation target in the nether/overworld.
Please note that it's not possible to use the player in this event.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] portal creat(e|ion)
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On Portal Enter
Called when a player enters a nether portal and the swirly animation starts to play.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] portal enter[ing]
[on] entering [a] portal
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-entity
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>false</td>
</table>
 
---
 
### On Prepare Craft
Called just before displaying crafting result to player. Note that setting the result item might or might not work due to Bukkit bugs.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] [player] (preparing|beginning) craft[ing] [[of] %itemtypes%]
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-inventory
event-slot
event-player
event-recipe
event-itemstack
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-Fixes-V10</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>false</td>
</table>
 
---
 
### On Pressure Plate / Trip
Called when a player steps on a pressure plate or tripwire respectively.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] [step[ping] on] [a] [pressure] plate
[on] (trip|[step[ping] on] [a] tripwire)
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-player
event-itemstack
event-block
event-direction
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0 (pressure plate), 1.4.4 (tripwire)</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On Projectile Hit
Called when a projectile hits an entity or a block.
Use the damage event with a check for a projectile to be able to use the entity that got hit in the case when the projectile hit a living entity.
A damage event will even be fired if the damage is 0, e.g. when throwing snowballs at non-nether mobs.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] projectile hit
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-projectile
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>false</td>
</table>
 
---
 
### On Quit
Called when a player leaves the server. Starting with Skript 2.0 this also includes kicked players.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] (quit[ting]|disconnect[ing]|log[ ]out|logging out)
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-player
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>false</td>
</table>
 
---
 
### On Redstone
Called when the redstone current of a block changes. This event is of not much use yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] redstone [current] [chang(e|ing)]
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-block
event-location
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>false</td>
</table>
 
---
 
### On Respawn
Called when a player respawns. You should prefer this event over the death event as the player is technically alive when this event is called.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] [player] respawn[ing]
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-player
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>false</td>
</table>
 
---
 
### On Resurrect Attempt
Called when an entity dies, always. If they are not holding a totem, this is calcelled - you can, however, uncancel it.
 
```java
on resurrect attempt:
	entity is player
	entity has permission "admin.undying"
	uncancel the event
```
<details><summary>Syntaxes</summary><p>
 
```java
[on] [entity] resurrect[ion] [attempt]
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-entity
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev28</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On RunApp
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] [skutil[ities] ](file|app|script) (run|execute)
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-object
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On RunCode
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] [skutil[ities] ](bash|batch|sh) (command|cmd) (run|execute)
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-string
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On Script Load/Unload
Called directly after the trigger is loaded, or directly before the whole script is unloaded.
 
```java
on load:
	set {running.%script%} to true
on unload:
	set {running.%script%} to false
```
<details><summary>Syntaxes</summary><p>
 
```java
[on] [script] (load|init|enable)
[on] [script] (unload|stop|disable)
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
none
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>false</td>
</table>
 
---
 
### On Server Start/Stop
Called when the server starts or stops (actually, when Skript starts or stops, so a /reload will trigger these events as well).
 
```java
on Skript start
on server stop
```
<details><summary>Syntaxes</summary><p>
 
```java
[on] (server|skript) (start|load|enable)
[on] (server|skript) (stop|unload|disable)
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
none
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>false</td>
</table>
 
---
 
### On Sheep Regrow Wool
Called when sheep regrows it's sheared wool back.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] sheep [re]grow[ing] wool
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-entity
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev21</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On Shoot
Called whenever a projectile is shot. Use the shooter expression to get who shot the projectile.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] [projectile] shoot
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-projectile
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On Sign Change
As signs are placed empty, this event is called when a player is done editing a sign.
 
```java
on sign change:
	line 2 is empty
	set line 1 to "<red>%line 1%"
```
<details><summary>Syntaxes</summary><p>
 
```java
[on] sign (chang[e]|edit)[ing]
[on] [player] (chang[e]|edit)[ing] [a] sign
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-player
event-block
event-location
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On Slime Split
Called when a slime splits. Usually this happens when a big slime dies.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] slime split[ting]
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-entity
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev26</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On Smelt
Called when a furnace smelts an item in its ore slot.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] [ore] smelt[ing]
[on] smelt[ing] of ore
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-block
event-location
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On Sneak Toggle
Called when a player starts or stops sneaking. Use is sneaking to get whether the player was sneaking before the event was called.
 
```java
# make players that stop sneaking jump
on sneak toggle:
	player was sneaking
	push the player upwards at speed 0.5
```
<details><summary>Syntaxes</summary><p>
 
```java
[on] [player] toggl(e|ing) sneak
[on] [player] sneak toggl(e|ing)
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-player
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On Spawn
Called when an creature spawns.
 
```java
on spawn of a zombie
on spawn of an ender dragon:
	broadcast "A dragon has been sighted in %world%!"
```
<details><summary>Syntaxes</summary><p>
 
```java
[on] spawn[ing] [of %entitydatas%]
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-entity
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On Spawn Change
Called when the spawn point of a world changes.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] [world] spawn change
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>false</td>
</table>
 
---
 
### On Spread
Called when a new block forms as a result of a block that can spread, e.g. water or mushrooms.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] spread[ing]
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
past event-block
event-world
event-block
event-location
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On Sprint Toggle
Called when a player starts or stops sprinting. Use is sprinting to get whether the player was sprinting before the event was called.
 
```java
on sprint toggle:
	player is not sprinting
	send "Run!"
```
<details><summary>Syntaxes</summary><p>
 
```java
[on] [player] toggl(e|ing) sprint
[on] [player] sprint toggl(e|ing)
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-player
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On Tame
Called when a player tames a wolf or ocelot. Can be cancelled to prevent the entity from being tamed.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] [entity] tam(e|ing)
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-entity
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On Target
Called when a mob starts/stops following/attacking another entity, usually a player.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] [entity] target
[on] [entity] un[-]target
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-entity
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On Teleport
Called whenever a player is teleported, either by a nether/end portal or other means (e.g. by plugins).
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] [player] teleport[ing]
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-player
event-teleportcause
event-block
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On Throwing of an Egg
Called when a player throws an egg. You can just use the shoot event in most cases, as this event is intended to support changing the hatched mob and its chance to hatch, but Skript does not yet support that.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] throw[ing] [of] [an] egg
[on] [player] egg throw
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-player
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>false</td>
</table>
 
---
 
### On Tool Change
Called whenever a player changes his held item by selecting a different slot (e.g. the keys 1-9 or the mouse wheel), not by dropping or replacing the item in the current slot.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] [player['s]] (tool|item held|held item) chang(e|ing)
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-player
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On Unzip
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] [skutil[ities] ]unzip
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-object
event-string
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On Vehicle Create
Called when a new vehicle is created, e.g. when a player places a boat or minecart.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] vehicle create
[on] creat(e|ing|ion of) [a] vehicle
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-entity
event-entity
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On Vehicle Damage
Called when a vehicle gets damage. Too much damage will destroy the vehicle.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] vehicle damage
[on] damag(e|ing) [a] vehicle
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-entity
event-entity
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On Vehicle Destroy
Called when a vehicle is destroyed. Any passenger will be ejected and the vehicle might drop some item(s).
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] vehicle destroy
[on] destr(oy[ing]|uction of) [a] vehicle
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-entity
event-entity
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On Vehicle Enter
Called when an entity enters a vehicle, either deliberately (players) or by falling into them (mobs).
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] vehicle enter
[on] enter[ing] [a] vehicle
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-entity
event-entity
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On Vehicle Exit
Called when an entity exits a vehicle.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] vehicle exit
[on] exit[ing] [a] vehicle
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-entity
event-entity
event-livingentity
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On Weather Change
Called when a world's weather changes.
 
```java
on weather change
on weather change to sunny
```
<details><summary>Syntaxes</summary><p>
 
```java
[on] weather change [to %weathertypes%]
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On World Init
Called when a world is initialised. As all default worlds are initialised before any scripts are loaded, this event is only called for newly created worlds.
World management plugins might change the behaviour of this event though.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] world init[zation)]
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>false</td>
</table>
 
---
 
### On World Load
Called when a world is loaded. As with the world init event, this event will not be called for the server's default world(s).
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] world load[ing]
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>false</td>
</table>
 
---
 
### On World Save
Called when a world is saved to disk. Usually all worlds are saved simultaneously, but world management plugins could change this.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] world sav(e|ing)
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>false</td>
</table>
 
---
 
### On World Unload
Called when a world is unloaded. This event might never be called if you don't have a world management plugin.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] world unload[ing]
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On Zombie Break Door
Called when a zombie is done breaking a wooden door. Can be cancelled to prevent the zombie from breaking the door.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] zombie break[ing] [a] [wood[en]] door
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-entity
event-block
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On [entity] (elytra|glide) [toggle]
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] [skellett] [entity] (elytra|glide) [toggle]
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-entity
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On [entity] (resurrect|revive)
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] [skellett] [entity] (resurrect|revive)
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-entity
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On [entity] (un(leash|lead)|(leash|lead) break)
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] [skellett] [entity] (un(leash|lead)|(leash|lead) break)
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-entity
event-block
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>false</td>
</table>
 
---
 
### On [on] ([item] enchant prepare|prepare [item] enchant):
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] [on] ([item] enchant prepare|prepare [item] enchant)
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-player
event-itemstack
event-block
event-number
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On [on] [player] map [(initialize|open)]:
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] [on] [player] map [(initialize|open)]
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
none
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>false</td>
</table>
 
---
 
### On [on] [skellett] brew[ing]:
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] [on] [skellett] brew[ing]
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-block
event-number
event-location
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On [on] entity sho[o]t:
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] [on] entity sho[o]t
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-entity
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On [player] world change
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] [skellett] [player] world change
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-player
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>false</td>
</table>
 
---
 
### On block [break] (xp|exp|experience) [drop]
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] [skellett] block [break] (xp|exp|experience) [drop]
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
past event-block
event-world
event-player
event-block
event-location
future event-block
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>false</td>
</table>
 
---
 
### On bre[e]d[ing]
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] [skellett] bre[e]d[ing]
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-entity
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On brew[ing] [stand] fuel [increase]
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] [skellett] brew[ing] [stand] fuel [increase]
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-itemstack
event-block
event-number
event-location
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On creative inventory click
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] [skellett] creative inventory click
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-inventory
event-slot
event-player
event-itemstack
event-clicktype
event-inventoryaction
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On entity block (change|modify)
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] [skellett] entity block (change|modify)
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-entity
event-block
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On entity teleport
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] [skellett] entity teleport
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-entity
event-location
future event-location
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On entity teleport
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] [skellett] entity teleport
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-entity
event-location
future event-location
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On firework explo(de|sion)
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] [skellett] firework explo(de|sion)
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-entity
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On item[ ][stack] (despawn|remove|delete)
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] [skellett] item[ ][stack] (despawn|remove|delete)
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-entity
event-itementity
event-itemstack
event-location
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On item[ ][stack] (merge|combine[d])
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] [skellett] item[ ][stack] (merge|combine[d])
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-entity
event-itementity
event-itemstack
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On off[ ]hand (switch|move)
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] [skellett] off[ ]hand (switch|move)
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-player
event-itemstack
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On packet [(send|sent|recieve)]
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] [skellett] packet [(send|sent|recieve)]
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-player
event-string
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On slime split
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] [skellett] slime split
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-entity
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On spawner spawn
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] [skellett] spawner spawn
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
event-entity
event-block
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### Periodical
An event that is called periodically.
 
```java
every 2 seconds
every minecraft hour
every ticks #can cause lag (depends on the code in this trigger)
every minecraft days
```
<details><summary>Syntaxes</summary><p>
 
```java
every %timespan%
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
none
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>false</td>
</table>
 
---
 
### Periodical
An event that is called periodically.
 
```java
every 2 seconds in "world"
every minecraft hour in "flatworld"
every ticks in "world" #can cause lag (depends on the code in this trigger)
every minecraft days in "plots"
```
<details><summary>Syntaxes</summary><p>
 
```java
every %timespan% in [world[s]] %worlds%
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-world
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>false</td>
</table>
## Conditions
 
### Can Hold
Tests whether a player or a chest can hold the given item.
 
```java
block can hold 200 cobblestone
player has enough space for 64 feathers
```
<details><summary>Syntaxes</summary><p>
 
```java
%inventories% (can hold|ha(s|ve) [enough] space (for|to hold)) %itemtypes%
%inventories% (can(no|')t hold|(ha(s|ve) not|ha(s|ve)n't|do[es]n't have) [enough] space (for|to hold)) %itemtypes%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### Can See
Checks whether the given players can see another players.
 
```java
if the player can't see the player-argument:
	message "<light red>The player %player-argument% is not online!"
```
<details><summary>Syntaxes</summary><p>
 
```java
%players% (is|are) [(in)]visible for %players%
%players% can see %players%
%players% (is|are)(n't| not) [(in)]visible for %players%
%players% can('t| not) see %players%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>INSERT VERSION</td>
</table>
 
---
 
### Chance
A condition that randomly succeeds or fails.
Valid values are between 0% and 100%, or if the percent sign is omitted between 0 and 1.
 
```java
chance of 50%:
	drop a diamond
chance of {var}% # {var} between 0 and 100
chance of {var} # {var} between 0 and 1
```
<details><summary>Syntaxes</summary><p>
 
```java
chance of %number%(\%|)
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### Comparison
A very general condition, it simply compares two values. Usually you can only compare for equality (e.g. block is/isn't of &lt;type&gt;), but some values can also be compared using greater than/less than. In that case you can also test for whether an object is between two others.
Note: This is the only element where not all patterns are shown. It has actually another two sets of similar patters, but with (was|were) or will be instead of (is|are) respectively, which check different time states of the first expression.
 
```java
the clicked block is a stone slab or a double stone slab
time in the player's world is greater than 8:00
the creature is not an enderman or an ender dragon
```
<details><summary>Syntaxes</summary><p>
 
```java
(neither|) %objects% ((is|are)(|(n't| not| neither)) ((greater|more|higher|bigger|larger) than|above)|\>) %objects%
(neither|) %objects% ((is|are)(|(n't| not| neither)) (greater|more|higher|bigger|larger|above) [than] or (equal to|the same as)|\>=) %objects%
(neither|) %objects% ((is|are)(|(n't| not| neither)) ((less|smaller) than|below)|\<) %objects%
(neither|) %objects% ((is|are)(|(n't| not| neither)) (less|smaller|below) [than] or (equal to|the same as)|\<=) %objects%
(neither|) %objects% ()((is|are) (not|neither)|isn't|aren't|!=) [equal to] %objects%
(neither|) %objects% (is|are|=) [(equal to|the same as)] %objects%
(neither|) %objects% (is|are) between %objects% and %objects%
(neither|) %objects% ()(is not|are not|isn't|aren't) between %objects% and %objects%
(neither|) %objects@-1% (was|were)(|(n't| not| neither)) ((greater|more|higher|bigger|larger) than|above) %objects%
(neither|) %objects@-1% (was|were)(|(n't| not| neither)) (greater|more|higher|bigger|larger|above) [than] or (equal to|the same as) %objects%
(neither|) %objects@-1% (was|were)(|(n't| not| neither)) ((less|smaller) than|below) %objects%
(neither|) %objects@-1% (was|were)(|(n't| not| neither)) (less|smaller|below) [than] or (equal to|the same as) %objects%
(neither|) %objects@-1% ()((was|were) (not|neither)|wasn't|weren't) [equal to] %objects%
(neither|) %objects@-1% (was|were) [(equal to|the same as)] %objects%
(neither|) %objects@-1% (was|were) between %objects% and %objects%
(neither|) %objects@-1% ()(was not|were not|wasn't|weren't) between %objects% and %objects%
(neither|) %objects@1% (will be|(will (not|neither) be|won't be)) ((greater|more|higher|bigger|larger) than|above) %objects%
(neither|) %objects@1% (will be|(will (not|neither) be|won't be)) (greater|more|higher|bigger|larger|above) [than] or (equal to|the same as) %objects%
(neither|) %objects@1% (will be|(will (not|neither) be|won't be)) ((less|smaller) than|below) %objects%
(neither|) %objects@1% (will be|(will (not|neither) be|won't be)) (less|smaller|below) [than] or (equal to|the same as) %objects%
(neither|) %objects@1% ()((will (not|neither) be|won't be)|(isn't|aren't|is not|are not) (turning|changing) [in]to) [equal to] %objects%
(neither|) %objects@1% (will be [(equal to|the same as)]|(is|are) (turning|changing) [in]to) %objects%
(neither|) %objects@1% will be between %objects% and %objects%
(neither|) %objects@1% ()(will not be|won't be) between %objects% and %objects%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### Contains
Checks whether an inventory contains the given item, a text contains another piece of text, or a list of objects (e.g. a {list variable::*}) contains another object.
 
```java
block contains 20 cobblestone
player has 4 flint and 2 iron ingots
```
<details><summary>Syntaxes</summary><p>
 
```java
%inventories% ha(s|ve) %itemtypes% [in [(the[ir]|his|her|its)] inventory]
%inventories/strings/objects% contain[s] %itemtypes/strings/objects%
%inventories% do[es](n't| not) have %itemtypes% [in [(the[ir]|his|her|its)] inventory]
%inventories/strings/objects% do[es](n't| not) contain %itemtypes/strings/objects%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### Damage Cause
Tests what kind of damage caused a damage event. Refer to the Damage Cause type for a list of all possible causes.
 
```java
# make players use their potions of fire resistance whenever they take any kind of fire damage
on damage:
	damage was caused by lava, fire or burning
	victim is a player
	victim has a potion of fire resistance
	cancel event
	apply fire resistance to the victim for 30 seconds
	remove 1 potion of fire resistance from the victim
# prevent mobs from dropping items under certain circumstances
on death:
	entity is not a player
	damage wasn't caused by a block explosion, an attack, a projectile, a potion, fire, burning, thorns or poison
	clear drops
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] damage (was|is|has)(|n('|o)t) [been] (caused|done|made) by %damagecause%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.0</td>
</table>
 
---
 
### Event Cancelled
Checks whether or not the event is cancelled
 
```java
on click:
	if event is cancelled:
		broadcast "no clicks allowed!"
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] event is cancel[l]ed
[the] event (is not|isn't) cancel[l]ed
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev36</td>
</table>
 
---
 
### Exists/Is Set
Checks whether a given expression or variable is set.
 
```java
{teams::%player's uuid%::preferred-team} is not set
on damage:
	projectile exists
	broadcast "%attacker% used a %projectile% to attack %victim%!"
```
<details><summary>Syntaxes</summary><p>
 
```java
%~objects% (exist[s]|(is|are) set)
%~objects% (do[es](n't| not) exist|(is|are)(n't| not) set)
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.2</td>
</table>
 
---
 
### Has Metadata
Checks whether a metadata holder has a metadata tag.
 
```java
if player has metadata value "healer":
```
<details><summary>Syntaxes</summary><p>
 
```java
%metadataholders% (has|have) metadata [(value|tag)[s]] %strings%
%metadataholders% (doesn't|does not|do not|don't) have metadata [(value|tag)[s]] %strings%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev36</td>
</table>
 
---
 
### Has Permission
Test whether a player has a certain permission.
 
```java
player has permission "skript.tree"
victim has the permission "admin":
	send "You're attacking an admin!" to attacker
```
<details><summary>Syntaxes</summary><p>
 
```java
[%commandsenders%] (do[es]n't|don't|do[es] not) have [the] permission[s] %strings%
[%commandsenders%] ha(s|ve) [the] permission[s] %strings%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### Has Played Before
Checks whether a player has played on this server before. You can also use on first join if you want to make triggers for new players.
 
```java
player has played on this server before
player hasn't played before
```
<details><summary>Syntaxes</summary><p>
 
```java
%offlineplayer% [(has|did)] [already] play[ed] [on (this|the) server] (before|already)
%offlineplayer% (has not|hasn't|did not|didn't) [(already|yet)] play[ed] [on (this|the) server] (before|already|yet)
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.4</td>
</table>
 
---
 
### Is Alive
Checks whether an entity is alive. This is mostly useful to check whether an entity stored in a variable does still exist.
 
```java
{villager-buddy::%player's uuid%} is dead
```
<details><summary>Syntaxes</summary><p>
 
```java
%livingentities% (is|are) (alive|dead)
%livingentities% (isn't|is not|aren't|are not) (alive|dead)
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.0</td>
</table>
 
---
 
### Is Banned
Checks whether a player or IP is banned.
 
```java
player is banned
victim is not IP-banned
"127.0.0.1" is banned
```
<details><summary>Syntaxes</summary><p>
 
```java
%offlineplayers/strings% (is|are) banned
%players/strings% (is|are) IP(-| |)banned
%offlineplayers/strings% (isn't|is not|aren't|are not) banned
%players/strings% (isn't|is not|aren't|are not) IP(-| |)banned
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.4</td>
</table>
 
---
 
### Is Blocking
Checks whether a player is blocking with his shield.
 
```java
on damage of player:
	victim is blocking
	damage attacker by 0.5 hearts
```
<details><summary>Syntaxes</summary><p>
 
```java
%players% (is|are) (blocking|defending)
%players% (isn't|is not|aren't|are not) (blocking|defending)
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td><i>unknown</i> (before 2.1)</td>
</table>
 
---
 
### Is Burning
Checks whether an entity is on fire, e.g. a zombie due to being in sunlight, or any entity after falling into lava.
 
```java
# increased attack against burning targets
victim is burning:
	increase damage by 2
```
<details><summary>Syntaxes</summary><p>
 
```java
%entities% (is|are) (burning|ignited|on fire)
%entities% (isn't|is not|aren't|are not) (burning|ignited|on fire)
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.4.4</td>
</table>
 
---
 
### Is Edible
Checks whether an item is edible.
 
```java
steak is edible
player's tool is edible
```
<details><summary>Syntaxes</summary><p>
 
```java
%itemstacks% (is|are) edible
%itemstacks% (isn't|is not|aren't|are not) edible
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev36</td>
</table>
 
---
 
### Is Empty
Checks whether an inventory, an inventory slot, or a text is empty.
 
```java
player's inventory is empty
```
<details><summary>Syntaxes</summary><p>
 
```java
%inventories/slots/strings% (is|are) empty
%inventories/slots/strings% (isn't|is not|aren't|are not) empty
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td><i>unknown</i> (before 2.1)</td>
</table>
 
---
 
### Is Enchanted
Checks whether an item is enchanted.
 
```java
tool of the player is enchanted with efficiency 2
helm, chestplate, leggings or boots are enchanted
```
<details><summary>Syntaxes</summary><p>
 
```java
%itemtypes% (is|are) enchanted [with %-enchantmenttype%]
%itemtypes% (isn't|is not|aren't|are not) enchanted [with %-enchantmenttype%]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.4.6</td>
</table>
 
---
 
### Is Flammable
Checks whether an item is flammable.
 
```java
wood is flammable
player's tool is flammable
```
<details><summary>Syntaxes</summary><p>
 
```java
%itemstacks% (is|are) flammable
%itemstacks% (isn't|is not|aren't|are not) flammable
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev36</td>
</table>
 
---
 
### Is Flying
Checks whether a player is flying.
 
```java
player is not flying
```
<details><summary>Syntaxes</summary><p>
 
```java
%players% (is|are) flying
%players% (isn't|is not|aren't|are not) flying
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.4.4</td>
</table>
 
---
 
### Is Holding
Checks whether a player is holding a specific item. Cannot be used with endermen, use 'entity is [not] an enderman holding &lt;item type&gt;' instead.
 
```java
player is holding a stick
victim isn't holding a sword of sharpness
```
<details><summary>Syntaxes</summary><p>
 
```java
[%livingentities%] ha(s|ve) %itemtypes% in [main] hand
[%livingentities%] (is|are) holding %itemtypes% [in main hand]
[%livingentities%] ha(s|ve) %itemtypes% in off[(-| )]hand
[%livingentities%] (is|are) holding %itemtypes% in off[(-| )]hand
[%livingentities%] (ha(s|ve) not|do[es]n't have) %itemtypes% in [main] hand
[%livingentities%] (is not|isn't) holding %itemtypes% [in main hand]
[%livingentities%] (ha(s|ve) not|do[es]n't have) %itemtypes% in off[(-| )]hand
[%livingentities%] (is not|isn't) holding %itemtypes% in off[(-| )]hand
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### Is Loaded
Checks whether or not a chunk/world is loaded
 
```java
if chunk at {home::%player's uuid%} is loaded:
```
<details><summary>Syntaxes</summary><p>
 
```java
%worlds/chunks% (is|are) loaded
%worlds/chunks% (isn't|is not|aren't|are not) loaded
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev37</td>
</table>
 
---
 
### Is Online
Checks whether a player is online.
 
```java
player is online
player-argument is offline
```
<details><summary>Syntaxes</summary><p>
 
```java
%offlineplayers% ((is|are) online|(is not|isn't|are not|aren't) offline)
%offlineplayers% ((is|are) offline|(is not|isn't|are not|aren't) online)
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.4</td>
</table>
 
---
 
### Is Poisoned
Checks whether an entity is poisoned.
 
```java
player is poisoned:
	cure the player from poison
	message "You have been cured!"
```
<details><summary>Syntaxes</summary><p>
 
```java
%livingentities% (is|are) poisoned
%livingentities% (isn't|is not|aren't|are not) poisoned
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.4.4</td>
</table>
 
---
 
### Is Riding
Tests whether an entity is riding another or is in a vehicle.
 
```java
player is riding a saddled pig
```
<details><summary>Syntaxes</summary><p>
 
```java
%entities% (is|are) riding [%entitydatas%]
%entities% (isn't|is not|aren't|are not) riding [%entitydatas%]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.0</td>
</table>
 
---
 
### Is Script Loaded
Check if the current script or another script, is current loaded.
 
```java
script is loaded
script "example.sk" is loaded
```
<details><summary>Syntaxes</summary><p>
 
```java
script[s] [%-strings%] (is|are) loaded
script[s] [%-strings%] (isn't|is not|aren't|are not) loaded
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev31</td>
</table>
 
---
 
### Is Sleeping
Checks whether a player is sleeping.
 
```java
# cut your enemies' throats in their sleep >=)
on attack:
	attacker is holding a sword
	victim is sleeping
	increase the damage by 1000
```
<details><summary>Syntaxes</summary><p>
 
```java
%players% (is|are) sleeping
%players% (isn't|is not|aren't|are not) sleeping
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.4.4</td>
</table>
 
---
 
### Is Sneaking
Checks whether a player is sneaking.
 
```java
# prevent mobs from seeing sneaking players if they are at least 4 meters apart
on target:
	target is sneaking
	distance of target and the entity is bigger than 4
	cancel the event
```
<details><summary>Syntaxes</summary><p>
 
```java
%players% (is|are) sneaking
%players% (isn't|is not|aren't|are not) sneaking
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.4.4</td>
</table>
 
---
 
### Is Solid
Checks whether an item is solid.
 
```java
grass block is solid
player's tool isn't solid
```
<details><summary>Syntaxes</summary><p>
 
```java
%itemstacks% (is|are) solid
%itemstacks% (isn't|is not|aren't|are not) solid
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev36</td>
</table>
 
---
 
### Is Sprinting
Checks whether a player is sprinting.
 
```java
player is not sprinting
```
<details><summary>Syntaxes</summary><p>
 
```java
%players% (is|are) sprinting
%players% (isn't|is not|aren't|are not) sprinting
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.4.4</td>
</table>
 
---
 
### Is Transparent
Checks whether an item is transparent.
 
```java
glass is transparent
player's tool is transparent.
```
<details><summary>Syntaxes</summary><p>
 
```java
%itemstacks% (is|are) transparent
%itemstacks% (isn't|is not|aren't|are not) transparent
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev36</td>
</table>
 
---
 
### Is Wearing
Checks whether a player is wearing some armour.
 
```java
player is wearing an iron chestplate and iron leggings
player is wearing all diamond armour
```
<details><summary>Syntaxes</summary><p>
 
```java
%livingentities% (is|are) wearing %itemtypes%
%livingentities% (isn't|is not|aren't|are not) wearing %itemtypes%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### Is in World
Checks whether an entity is in a specific world.
 
```java
player is in "world"
argument isn't in world "world_nether"
the player is in the world of the victim
```
<details><summary>Syntaxes</summary><p>
 
```java
%entities% (is|are) in [[the] world[s]] %worlds%
%entities% (is not|isn't|are not|aren't) in [[the] world[s]] %worlds%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.4</td>
</table>
 
---
 
### Is of Type
Checks whether an item of entity is of the given type. This is mostly useful for variables, as you can use the general 'is' condition otherwise (e.g. 'victim is a creeper').
 
```java
tool is of type {*selected type}
victim is of type {villager type}
```
<details><summary>Syntaxes</summary><p>
 
```java
%itemstacks/entities% (is|are) of type[s] %itemtypes/entitydatas%
%itemstacks/entities% (isn't|is not|aren't|are not) of type[s] %itemtypes/entitydatas%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.4</td>
</table>
 
---
 
### Is on Ground
Checks whether an entity is on ground.
 
```java
player is not on ground
```
<details><summary>Syntaxes</summary><p>
 
```java
%entities% (is|are) on ground
%entities% (isn't|is not|aren't|are not) on ground
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev26</td>
</table>
 
---
 
### PvP
Checks the PvP state of a world.
 
```java
PvP is enabled
PvP is disabled in "world"
```
<details><summary>Syntaxes</summary><p>
 
```java
(is PvP|PvP is) enabled [in %worlds%]
(is PvP|PvP is) disabled [in %worlds%]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.3.4</td>
</table>
 
---
 
### Starts/Ends With
Checks if a text starts or ends with another.
 
```java
if the argument starts with "test":
	send "Stop!"
```
<details><summary>Syntaxes</summary><p>
 
```java
%strings% (start|end)[s] with %string%
%strings% do[es](n't| not) (start|end) with %string%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev36</td>
</table>
 
---
 
### Time
Tests whether a given real time was more or less than some time span ago.
 
```java
command /command-with-cooldown:
	trigger:
		{command::%player's uuid%::last-usage} was less than a minute ago:
			message "Please wait a minute between uses of this command."
			stop
		set {command::%player's uuid%::last-usage} to now
		# ... actual command trigger here ...
```
<details><summary>Syntaxes</summary><p>
 
```java
%date% (was|were)( more|(n't| not) less) than %timespan% [ago]
%date% (was|were)((n't| not) more| less) than %timespan% [ago]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.0</td>
</table>
 
---
 
### Weather
Checks whether the weather in a world is of a specific type.
I welcome any ideas how to write this condition differently.
 
```java
is thundering
is raining in "world" or "world2"
```
<details><summary>Syntaxes</summary><p>
 
```java
is %weathertypes% [in %worlds%]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
## Effects
 
### Ban
Bans/unbans a player or IP.
Starting with Skript 2.1.1 and Bukkit 1.7.2 R0.4, one can also ban players with a reason.
 
```java
unban player
ban "127.0.0.1"
IP-ban the player because "he is an idiot"
```
<details><summary>Syntaxes</summary><p>
 
```java
ban %strings/offlineplayers% [(by reason of|because [of]|on account of|due to) %-string%]
unban %strings/offlineplayers%
ban %players% by IP [(by reason of|because [of]|on account of|due to) %-string%]
unban %players% by IP
IP(-| )ban %players% [(by reason of|because [of]|on account of|due to) %-string%]
(IP(-| )unban|un[-]IP[-]ban) %players%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.4, 2.1.1 (ban reason)</td>
</table>
 
---
 
### Broadcast
Broadcasts a message to the server.
 
```java
broadcast "Welcome %player% to the server!"
broadcast "Woah! It's a message!"
```
<details><summary>Syntaxes</summary><p>
 
```java
broadcast %strings% [(to|in) %-worlds%]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### Cancel Command Cooldown
Only usable in command events. Makes it so the current command usage isn't counted towards the cooldown.
 
```java
command /nick <text>:
	executable by: players
	cooldown: 10 seconds
	trigger:
		if length of arg-1 is more than 16:
			# Makes it so that invalid arguments don't make you wait for the cooldown again
			cancel the cooldown
			send "Your nickname may be at most 16 characters."
			stop
		set the player's display name to arg-1
```
<details><summary>Syntaxes</summary><p>
 
```java
(cancel|ignore) [the] [current] [command] cooldown
un(cancel|ignore) [the] [current] [command] cooldown
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev34</td>
</table>
 
---
 
### Cancel Event
Cancels the event (e.g. prevent blocks from being placed, or damage being taken).
 
```java
on damage:
	victim is a player
	victim has the permission "skript.god"
	cancel the event
```
<details><summary>Syntaxes</summary><p>
 
```java
cancel [the] event
uncancel [the] event
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### Change: Set/Add/Remove/Delete/Reset
A very general effect that can change many expressions. Many expressions can only be set and/or deleted, while some can have things added to or removed from them.
 
```java
# set:
Set the player's display name to "<red>%name of player%"
set the block above the victim to lava
# add:
add 2 to the player's health # preferably use '<a href='#heal'>heal</a>' for this
add argument to {blacklist::*}
give a diamond pickaxe of efficiency 5 to the player
increase the data value of the clicked block by 1
# remove:
remove 2 pickaxes from the victim
subtract 2.5 from {points.%player%}
# remove all:
remove every iron tool from the player
remove all minecarts from {entitylist::*}
# delete:
delete the block below the player
clear drops
delete {variable}
# reset:
reset walk speed of player
reset chunk at the targeted block
```
<details><summary>Syntaxes</summary><p>
 
```java
(add|give) %objects% to %~objects%
increase %~objects% by %objects%
give %~objects% %objects%
set %~objects% to %objects%
remove (all|every) %objects% from %~objects%
(remove|subtract) %objects% from %~objects%
reduce %~objects% by %objects%
(delete|clear) %~objects%
reset %~objects%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0 (set, add, remove, delete), 2.0 (remove all)</td>
</table>
 
---
 
### Colour Items
Colours items in a given colour. You can also use RGB codes if you feel limited with the 16 default colours. RGB codes are three numbers from 0 to 255 in the order (red, green, blue), where (0,0,0) is black and (255,255,255) is white. Armor is colourable for all Minecraft versions. With Minecraft 1.11 or newer you can also colour potions and maps. Note that the colours might not look exactly how you'd expect.
 
```java
dye player's helmet blue
colour the player's tool red
```
<details><summary>Syntaxes</summary><p>
 
```java
(dye|colo[u]r|paint) %slots/itemstack% %color%
(dye|colo[u]r|paint) %slots/itemstack% (%number%, %number%, %number%)
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.0, 2.2-dev26 (maps and potions)</td>
</table>
 
---
 
### Command
Executes a command. This can be useful to use other plugins in triggers.
 
```java
make player execute command "/suicide"
execute console command "/say Hello everyone!"
```
<details><summary>Syntaxes</summary><p>
 
```java
[execute] [the] command %strings% [by %-commandsenders%]
[execute] [the] %commandsenders% command %strings%
(let|make) %commandsenders% execute [[the] command] %strings%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### Continue
Skips the value currently being looped, moving on to the next value if it exists.
 
```java
loop all players:
	if loop-value does not have permission "moderator":
		continue # filter out non moderators
	broadcast "%loop-player% is a moderator!" # only moderators get broadcast
```
<details><summary>Syntaxes</summary><p>
 
```java
continue [loop]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev37</td>
</table>
 
---
 
### Damage/Heal/Repair
Damage/Heal/Repair an entity, or item stack.
 
```java
damage player by 5 hearts
heal the player
repair tool of player
```
<details><summary>Syntaxes</summary><p>
 
```java
damage %slots/livingentities/itemstack% by %number% [heart[s]][ with fake cause %-damagecause%]
heal %livingentities% [by %-number% [heart[s]]]
repair %slots/itemstack% [by %-number%]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### Delay
Delays the script's execution by a given timespan. Please note that delays are not persistent, e.g. trying to create a tempban script with ban player → wait 7 days → unban player will not work if you restart your server anytime within these 7 days. You also have to be careful even when using small delays!
 
```java
wait 2 minutes
halt for 5 minecraft hours
wait a tick
```
<details><summary>Syntaxes</summary><p>
 
```java
(wait|halt) [for] %timespan%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.4</td>
</table>
 
---
 
### Drop
Drops one or more items.
 
```java
on death of creeper:
	drop 1 TNT
```
<details><summary>Syntaxes</summary><p>
 
```java
drop %itemtypes/experience% [%directions% %locations%]
drop %itemtypes/experience% [%directions% %locations%] without velocity
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### Enchant/Disenchant
Enchant or disenchant an existing item
 
```java
enchant the player's tool with sharpness 5
disenchant the player's tool
```
<details><summary>Syntaxes</summary><p>
 
```java
enchant %~itemstack% with %enchantmenttypes%
disenchant %~itemstack%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.0</td>
</table>
 
---
 
### Equip
Equips a player with some given armor. This will replace any armor that the player is wearing.
 
```java
equip player with diamond helmet
equip player with all diamond armor
```
<details><summary>Syntaxes</summary><p>
 
```java
equip [%livingentity%] with %itemtypes%
make %livingentity% wear %itemtypes%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### Exit
Exits a given amount of loops and conditionals, or the entire trigger.
 
```java
if player has any ore:
	stop
message "%player% has no ores!"
loop blocks above the player:
	loop-block is not air:
		exit 2 sections
	set loop-block to water
```
<details><summary>Syntaxes</summary><p>
 
```java
(exit|stop) [trigger]
(exit|stop) [(1|a|the|this)] (section|loop|conditional)
(exit|stop) <\d+> (section|loop|conditional)s
(exit|stop) all (section|loop|conditional)s
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td><i>unknown</i> (before 2.1)</td>
</table>
 
---
 
### Explosion
Creates an explosion of a given force. The Minecraft Wiki has an article on explosions which lists the explosion forces of TNT, creepers, etc.
Hint: use a force of 0 to create a fake explosion that does no damage whatsoever, or use the explosion effect introduced in Skript 2.0.
Starting with Bukkit 1.4.5 and Skript 2.0 you can use safe explosions which will damage entities but won't destroy any blocks.
 
```java
create an explosion of force 10 at the player
create an explosion of force 0 at the victim
```
<details><summary>Syntaxes</summary><p>
 
```java
[(create|make)] [an] explosion (of|with) (force|strength|power) %number% [%directions% %locations%]
[(create|make)] [a] safe explosion (of|with) (force|strength|power) %number% [%directions% %locations%]
[(create|make)] [a] fake explosion [%directions% %locations%]
[(create|make)] [an] explosion[ ]effect [%directions% %locations%]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### Feed
Feeds the specified players.
 
```java
feed all players
feed the player by 5 beefs
```
<details><summary>Syntaxes</summary><p>
 
```java
feed [the] %players% [by %-number% [beef[s]]]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev34</td>
</table>
 
---
 
### Force Respawn
Forces player(s) to respawn if they are dead. If this is called without delay from death event, one tick is waited before respawn attempt.
 
```java
on death of player:
	force event-player to respawn
```
<details><summary>Syntaxes</summary><p>
 
```java
force %players% to respawn
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev21</td>
</table>
 
---
 
### Ignite/Extinguish
Lights entities on fire or extinguishes them.
 
```java
ignite the player
extinguish the player
```
<details><summary>Syntaxes</summary><p>
 
```java
(ignite|set fire to) %entities% [for %-timespan%]
(set|light) %entities% on fire [for %-timespan%]
extinguish %entities%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.4</td>
</table>
 
---
 
### Kick
Kicks a player from the server.
 
```java
on place of TNT, lava, or obsidian:
	kick the player due to "You may not place %block%!"
	cancel the event
```
<details><summary>Syntaxes</summary><p>
 
```java
kick %players% [(by reason of|because [of]|on account of|due to) %-string%]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### Kill
Kills an entity.
Note: This effect does not set the entitie's health to 0 (which causes issues), but damages the entity by 100 times its maximum health.
 
```java
kill the player
kill all creepers in the player's world
kill all endermen, witches and bats
```
<details><summary>Syntaxes</summary><p>
 
```java
kill %entities%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### Lightning
Strike lightning at a given location. Can use 'ligning effect' to create a lightning that does not harm entities or start fires.
 
```java
strike lightning at the player
strike lightning effect at the victim
```
<details><summary>Syntaxes</summary><p>
 
```java
(create|strike) lightning([ ]effect|) %directions% %locations%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.4</td>
</table>
 
---
 
### Log
Writes text into a .log file. Skript will write these files to /plugins/Skript/logs.
NB: Using 'server.log' as the log file will write to the default server log. Omitting the log file altogether will log the message as '[Skript] [&lt;script&gt;.sk] &lt;message&gt;' in the server log.
 
```java
on place of TNT:
	log "%player% placed TNT in %world% at %location of block%" to "tnt/placement.log"
```
<details><summary>Syntaxes</summary><p>
 
```java
log %strings% [(to|in) [file[s]] %-strings%]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.0</td>
</table>
 
---
 
### Loop Version
Changes loops to emulate given Skript version's behaviour.
 
```java
use old loops
use new loops
```
<details><summary>Syntaxes</summary><p>
 
```java
use[s] (old|new|2.1.2|2.2) loops
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td><i>unknown</i> (2.2)</td>
</table>
 
---
 
### Make Fly
Forces a player to start/stop flying.
Be aware that this also changes the flight mode of the player.
 
```java
make player fly
force all players to stop flying
```
<details><summary>Syntaxes</summary><p>
 
```java
force %players% to [(start|stop)] fly[ing]
make %players% (start|stop) flying
make %players% fly
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev34</td>
</table>
 
---
 
### Make Say
Forces a player to send a message to the chat. If the message starts with a slash it will force the player to use command.
 
```java
make the player say "Hello."
force all players to send the message "I love this server"
```
<details><summary>Syntaxes</summary><p>
 
```java
make %players% (say|send [the] message[s]) %strings%
force %players% to (say|send [the] message[s]) %strings%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>INSERT VERSION</td>
</table>
 
---
 
### Message
Sends a message to the given player.
 
```java
message "A wild %player% appeared!"
message "This message is a distraction. Mwahaha!"
send "Your kill streak is %{kill streak.%player%}%." to player
if the targeted entity exists:
	message "You're currently looking at a %type of the targeted entity%!"
```
<details><summary>Syntaxes</summary><p>
 
```java
(message|send [message[s]]) %strings% [to %commandsenders%]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0, 2.2-dev26 (advanced features)</td>
</table>
 
---
 
### Open/Close Inventory
Opens an inventory to a player. The player can then access and modify the inventory as if it was a chest that he just opened.
Please note that currently 'show' and 'open' have the same effect, but 'show' will eventually show an unmodifiable view of the inventory in the future.
 
```java
show the victim's inventory to the player
open the player's inventory for the player
```
<details><summary>Syntaxes</summary><p>
 
```java
(open|show) (((crafting [table]|workbench)|chest|anvil) (view|window|inventory|)|%-inventory%) (to|for) %players%
close [the] inventory [view] (to|of|for) %players%
close %players%'[s] inventory [view]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.0, 2.1.1 (closing), 2.2-Fixes-V10 (anvil)</td>
</table>
 
---
 
### Play Effect
Plays a visual effect at a given location or on a given entity.
Please note that some effects can only be played on entities, e..g wolf hearts or the hurt effect, and that these are always visible to all players.
 
```java
play wolf hearts on the clicked wolf
show mob spawner flames at the targeted block to the player
```
<details><summary>Syntaxes</summary><p>
 
```java
(play|show) %visualeffects% (on|%directions%) %entities/locations% [(to %-players%|in (radius|range) of %number%)]
(play|show) %number% %visualeffects% (on|%directions%) %locations% [(to %-players%|in (radius|range) of %number%)]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.1</td>
</table>
 
---
 
### Play Sound
Plays a sound at given location for everyone or just for given players. Playing sounds from resource packs is supported.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
play sound %string% [with volume %number%] [(and|with) pitch %number%] at %location% [for %players%]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev28</td>
</table>
 
---
 
### Player Visibility
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
hide %players% [(from|for) %-players%]
reveal %players% [(to|for|from) %-players%]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>INSERT VERSION</td>
</table>
 
---
 
### Poison/Cure
Poison or cure a creature.
 
```java
poison the player
poison the victim for 20 seconds
cure the player from poison
```
<details><summary>Syntaxes</summary><p>
 
```java
poison %livingentities% [for %-timespan%]
(cure|unpoison) %livingentities% [(from|of) poison]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.3.2</td>
</table>
 
---
 
### Potion Effects
Apply or remove potion effects to/from entities.
 
```java
apply swiftness 2 to the player
remove haste from the victim
on join:
	apply potion of strength of tier {strength.%player%} to the player for 999 days
```
<details><summary>Syntaxes</summary><p>
 
```java
apply [potion of] %potioneffecttypes% [potion] [[[of] tier] %-number%] to %livingentities% [for %-timespan%]
apply ambient [potion of] %potioneffecttypes% [potion] [[[of] tier] %-number%] to %livingentities% [for %-timespan%]
apply [potion of] %potioneffecttypes% [potion] [[[of] tier] %-number%] without [any] particles to %livingentities% [for %-timespan%]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.0, 2.2-dev27 (ambient and particle-less potion effects)</td>
</table>
 
---
 
### Push
Push entities around.
 
```java
push the player upwards
push the victim downwards at speed 0.5
```
<details><summary>Syntaxes</summary><p>
 
```java
(push|thrust) %entities% %direction% [(at|with) (speed|velocity|force) %-number%]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.4.6</td>
</table>
 
---
 
### PvP
Set the PvP state for a given world.
 
```java
enable PvP #(current world only)
disable PvP in all worlds
```
<details><summary>Syntaxes</summary><p>
 
```java
enable PvP [in %worlds%]
disable PVP [in %worlds%]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.3.4</td>
</table>
 
---
 
### Replace
Replaces all occurrences of a given text with another text. Please note that you can only change variables and a few expressions, e.g. a message or a line of a sign.
Starting with 2.2-dev24, you can replace items in a inventory too.
 
```java
replace "<item>" in {textvar} with "%item%"
replace every "&" with "§" in line 1
# The following acts as a simple chat censor, but it will e.g. censor mass, hassle, assassin, etc. as well:
on chat:
	replace all "fuck", "bitch" and "ass" with "****" in the message
 
replace all stone and dirt in player's inventory and player's top inventory with diamond
```
<details><summary>Syntaxes</summary><p>
 
```java
replace (all|every|) %strings% in %strings% with %string%
replace (all|every|) %strings% with %string% in %strings%
replace (all|every|) %itemstacks% in %inventories% with %itemstack%
replace (all|every|) %itemstacks% with %itemstack% in %inventories%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.0, 2.2-dev24 (replace in muliple strings and replace items in inventory)</td>
</table>
 
---
 
### Return
Makes a function return a value
 
```java
function double(i: number) :: number:
	return 2 * {_i}
```
<details><summary>Syntaxes</summary><p>
 
```java
return %objects%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2</td>
</table>
 
---
 
### Send Block Change
Makes a player see a block as something it really isn't
 
```java
make player see block at player as dirt
```
<details><summary>Syntaxes</summary><p>
 
```java
make %players% see %blocks% as %itemtype%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev37</td>
</table>
 
---
 
### Shear
Shears or 'un-shears' a sheep. Please note that no wool is dropped, this only sets the 'sheared' state of the sheep.
 
```java
on rightclick on a sheep holding a sword:
	shear the clicked sheep
```
<details><summary>Syntaxes</summary><p>
 
```java
shear %livingentities%
un[-]shear %livingentities%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.0</td>
</table>
 
---
 
### Shoot
Shoots a projectile (or any other entity) from a given entity.
 
```java
shoot an arrow
make the player shoot a creeper at speed 10
shoot a pig from the creeper
```
<details><summary>Syntaxes</summary><p>
 
```java
shoot %entitydatas% [from %livingentities/locations%] [(at|with) (speed|velocity) %-number%] [%-direction%]
(make|let) %livingentities/locations% shoot %entitydatas% [(at|with) (speed|velocity) %-number%] [%-direction%]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.4</td>
</table>
 
---
 
### Spawn
Spawn a creature.
 
```java
spawn 3 creepers at the targeted block
spawn a ghast 5 meters above the player
```
<details><summary>Syntaxes</summary><p>
 
```java
spawn %entitytypes% [%directions% %locations%]
spawn %number% of %entitytypes% [%directions% %locations%]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### Teleport
Teleport an entity to a specific location.
 
```java
teleport the player to {homes.%player%}
teleport the attacker to the victim
```
<details><summary>Syntaxes</summary><p>
 
```java
teleport %entities% (to|%direction%) %location%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### Toggle
Toggle the state of a block.
 
```java
# use arrows to toggle switches, doors, etc.
on projectile hit:
    projectile is arrow
    toggle the block at the arrow
```
<details><summary>Syntaxes</summary><p>
 
```java
(close|turn off|de[-]activate) %blocks%
(toggle|switch) [[the] state of] %blocks%
(open|turn on|activate) %blocks%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.4</td>
</table>
 
---
 
### Tree
Creates a tree.
This may require that there is enough space above the given location and that the block below is dirt/grass, but it is possible that the tree will just grow anyways, possibly replacing every block in its path.
 
```java
grow a tall redwood tree above the clicked block
```
<details><summary>Syntaxes</summary><p>
 
```java
(grow|create|generate) tree [of type %structuretype%] %directions% %locations%
(grow|create|generate) %structuretype% [tree] %directions% %locations%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### Vectors - Rotate around XYZ
Rotates a vector around x, y, or z axis by some degrees
 
```java
rotate {_v} around x-axis by 90
rotate {_v} around y-axis by 90
rotate {_v} around z-axis by 90
```
<details><summary>Syntaxes</summary><p>
 
```java
rotate %vectors% around (x|y|z)(-| )axis by %number% [degrees]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev28</td>
</table>
 
---
 
### Vectors - Rotate around vector
Rotates a vector around another vector
 
```java
rotate {_v} around vector 1, 0, 0 by 90
```
<details><summary>Syntaxes</summary><p>
 
```java
rotate %vectors% around %vector% by %number% [degrees]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev28</td>
</table>
 
---
 
### Vehicle
Makes an entity ride another entity, e.g. a minecart, a saddled pig, an arrow, etc.
 
```java
make the player ride a saddled pig
make the attacker ride the victim
```
<details><summary>Syntaxes</summary><p>
 
```java
(make|let|force) %entities% [to] (ride|mount) [(in|on)] %entities/entitydatas%
(make|let|force) %entities% [to] (dismount|(dismount|leave) (from|of|) (any|the[ir]|his|her|) vehicle[s])
(eject|dismount) (any|the|) passenger[s] (of|from) %entities%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.0</td>
</table>
 
---
 
### op/deop
Grant/revoke a user operator state.
 
```java
op the player
deop all players
```
<details><summary>Syntaxes</summary><p>
 
```java
[de[-]]op %offlineplayers%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
## Expressions
 
### All Groups
All the groups a player can have. This expression requires Vault and a compatible permissions plugin to be installed.
 
```java
command /group <text>:
   trigger:
       if argument is "list":
           send "%all groups%"
```
<details><summary>Syntaxes</summary><p>
 
```java
all groups
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev35</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Text</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### All Permissions
Returns all permissions of the defined player(s). Note that the modifications to resulting list do not actually change permissions.
 
```java
set {_permissions::*} to all permissions of the player
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] permissions of %players%
%players%'[s] permissions
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev33</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Text</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### Alphabetical Sort
Sorts given strings in alphabetical order.
 
```java
set {_list::*} to alphabetically sorted {_list::*
```
<details><summary>Syntaxes</summary><p>
 
```java
alphabetically sorted %strings%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev18b</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Text</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### Altitude
Effectively an alias of 'y-coordinate of …', it represents the height of some object above bedrock.
 
```java
on damage:
	altitude of the attacker is higher that the altitude of the victim
	set damage to damage * 1.2
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] altitude[s] of %locations%
%locations%'[s] altitude[s]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.4.3</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>double</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### Amount
The amount of something.
Please note that amount of &lt;items&gt; will not return the number of items, but the number of stacks, e.g. 1 for a stack of 64 torches.
 
```java
message "There are %number of all players% players online!"
```
<details><summary>Syntaxes</summary><p>
 
```java
(amount|number|size) of %objects%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>integer</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### Amount of Items
Counts how many of a particular item type are in a given inventory.
 
```java
message "You have %number of ores in the player's inventory% ores in your inventory."
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] (amount|number) of %itemtypes% (in|of) %inventories%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>integer</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### Argument
Only usable in command events. Holds the value of the nth argument given to the command, e.g. if the command "/tell &lt;player&gt; &lt;text&gt;" is used like "/tell Njol Hello Njol!" argument 1 is the player named "Njol" and argument 2 is "Hello Njol!".
One can also use the type of the argument instead of its index to address the argument, e.g. in the above example 'player-argument' is the same as 'argument 1'.
 
```java
give the item-argument to the player-argument
damage the player-argument by the number-argument
give a diamond pickaxe to the argument
add argument 1 to argument 2
heal the last argument
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] last arg[ument][s]
[the] arg[ument][s](-| )<(\d+)>
[the] <(\d*1)st|(\d*2)nd|(\d*3)rd|(\d*[4-90])th> arg[ument][s]
[the] arg[ument][s]
[the] %*classinfo%( |-)arg[ument][( |-)<\d+>]
[the] arg[ument]( |-)%*classinfo%[( |-)<\d+>]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Object</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>unknown</td>
</table>
 
---
 
### Arithmetic
Arithmetic expressions, e.g. 1+2, (2 - health of player)/3, etc.
 
```java
set the player's health to 10 - the player's health
loop (argument + 2)/5 times:
	message "Two useless numbers: %loop-num*2 - 5%, %2^loop-num - 1%"
message "You have %health of player * 2% half hearts of HP!"
```
<details><summary>Syntaxes</summary><p>
 
```java
%number%[ ]+[ ]%number%
%number%[ ]-[ ]%number%
%number%[ ]*[ ]%number%
%number%[ ]/[ ]%number%
%number%[ ]^[ ]%number%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.4.2</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Number</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>unknown</td>
</table>
 
---
 
### Armour Slot
A part of a player's armour, i.e. the boots, leggings, chestplate or helmet.
 
```java
set chestplate of the player to a diamond chestplate
helmet of player is neither a helmet nor air # player is wearing a block, e.g. from another plugin
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] (boot[s]|shoe[s]|leg[ging][s]|chestplate[s]|helm[et][s]) [(item|slot)] of %livingentities%
%livingentities%'[s] (boot[s]|shoe[s]|leg[ging][s]|chestplate[s]|helm[et][s]) [(item|slot)]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Inventory Slot</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>add, set, remove, remove all and delete</td>
</table>
 
---
 
### Attacked
The victim of a damage event, e.g. when a player attacks a zombie this expression represents the zombie.
 
```java
on damage:
	victim is a creeper
	damage the attacked by 1 heart
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] (attacked|damaged|victim) [<(.+)>]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.3</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Entity</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>unknown</td>
</table>
 
---
 
### Attacker
The attacker of a damage event, e.g. when a player attacks a zombie this expression represents the player.
Please note that the attacker can also be a block, e.g. a cactus or lava, but this expression will not be set in these cases.
 
```java
on damage:
	attacker is a player
	health of attacker is less than or equal to 2
	damage victim by 1 heart
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] (attacker|damager)
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.3</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Entity</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>add, remove and remove all</td>
</table>
 
---
 
### Bed
The bed location of a player, i.e. the spawn point of a player if he ever slept in a bed and the bed still exists and is unobstructed.
 
```java
bed of player exists:
	teleport player the the player's bed
else:
	teleport the player to the world's spawn point
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] bed[s] [location[s]] of %players%
%players%'[s] bed[s] [location[s]]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Location</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>set and delete</td>
</table>
 
---
 
### Biome
The biome at a certain location. Please note that biomes are only defined for x/z-columns, i.e. the altitude (y-coordinate) doesn't matter. 
 
```java
# damage player in deserts constantly
every real minute:
	loop all players:
		biome at loop-player is desert
		damage the loop-player by 1
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] biome (of|%direction%) %location%
%location%'[s] biome
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.4.4</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Biome</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>set</td>
</table>
 
---
 
### Block
The block involved in the event, e.g. the clicked block or the placed block.
Can optionally include a direction as well, e.g. 'block above' or 'block in front of the player'.
 
```java
block is ore
set block below to air
spawn a creeper above the block
loop blocks in radius 4:
	loop-block is obsidian
	set loop-block to water
block is a chest:
	clear the inventory of the block
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] [event-]block
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Block</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>unknown</td>
</table>
 
---
 
### Block
The block involved in the event, e.g. the clicked block or the placed block.
Can optionally include a direction as well, e.g. 'block above' or 'block in front of the player'.
 
```java
block is ore
set block below to air
spawn a creeper above the block
loop blocks in radius 4:
	loop-block is obsidian
	set loop-block to water
block is a chest:
	clear the inventory of the block
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] block %direction% [%location%]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Block</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>unknown</td>
</table>
 
---
 
### Block Sphere
All blocks in a sphere around a center, mostly useful for looping.
 
```java
loop blocks in radius 5 around the player:
```
<details><summary>Syntaxes</summary><p>
 
```java
[(all [[of] the]|the)] blocks in radius %number% [(of|around) %location%]
[(all [[of] the]|the)] blocks around %location% in radius %number%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Block</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>add, set, remove, remove all and delete</td>
</table>
 
---
 
### Blocks
Blocks relative to other blocks or between other blocks. Can be used to get blocks relative to other blocks or for looping.
 
```java
loop blocks above the player:
loop blocks between the block below the player and the targeted block:
set the blocks below the player, the victim and the targeted block to air
```
<details><summary>Syntaxes</summary><p>
 
```java
[(all [[of] the]|the)] blocks %direction% [%locations%]
[(all [[of] the]|the)] blocks from %location% [on] %direction%
[(all [[of] the]|the)] blocks from %block% to %block%
[(all [[of] the]|the)] blocks (within|between) %block% and %block%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Block</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>add, set, remove, remove all and delete</td>
</table>
 
---
 
### Book Author
The author of a book
 
```java
on book sign:
	message "Book Title: %author of event-item%"
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] [book] (author|writer|publisher) of %itemstack%
%itemstack%'[s] [book] (author|writer|publisher)
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev31</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Text</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>set, delete and reset</td>
</table>
 
---
 
### Book Pages
The pages of a book
 
```java
on book sign:
	message "Book Pages: %pages of event-item%"
   message "Book Page 1: %page 1 of event-item%"
```
<details><summary>Syntaxes</summary><p>
 
```java
[all] [the] [book] (pages|content) of %itemstack%
%itemstack%'s [book] (pages|content)
[book] page %number% of %itemstack%
%itemstack%'s [book] page %number%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev31</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Text</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### Book Title
The title of a book
 
```java
on book sign:
	message "Book Title: %title of event-item%"
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] (book name|title) of %itemstack%
%itemstack%'[s] (book name|title)
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev31</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Text</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>set, delete and reset</td>
</table>
 
---
 
### Burn/Cook Time
The time a furnace takes to burn an item in a fuel burn event.
Can also be used to change the burn/cook time of a placed furnace.
 
```java
on fuel burn:
	if fuel slot is coal:
		set burning time to 1 tick
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] burn[ing] time
[the] (burn|cook)[ing] time of %blocks%
%blocks%'[s] (burn|cook)[ing] time
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev37</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Timespan</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>add, set and remove</td>
</table>
 
---
 
### Chat Format
Can be used to get/retrieve the chat format. The sender of a message is represented by [player] or [sender], and the message by [message] or [msg].
 
```java
set the chat format to "<yellow>[player]<light gray>: <green>[message]"
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] (message|chat) format[ting]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev31</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Text</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>set and reset</td>
</table>
 
---
 
### Chat Recipients
Recipients of chat events where this is called.
 
```java
chat recipients
```
<details><summary>Syntaxes</summary><p>
 
```java
[chat][( |-)]recipients
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-Fixes-v7, 2.2-dev35 (clearing recipients)</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Player</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>add, set, remove, remove all, delete and reset</td>
</table>
 
---
 
### Chunk
The chunk a block, location or entity is in
 
```java
add the chunk at the player to {protected chunks::*}
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] chunk[s] (of|%-directions%) %locations%
%locations%'[s] chunk[s]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Chunk</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### Clicked Block/Entity/Inventory/Slot
The clicked block, entity, inventory slot, inventory, type or action.
 
```java
message "You clicked on a %type of clicked entity%!"
clicked block is a chest:
	show the inventory of the clicked block to the player
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] ( clicked (block|%-*itemtype/entitydata%)|clicked slot|clicked inventory|click (type|action)|inventory action)
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0, 2.2-dev35 (more clickable things)</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Object</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>add, set, remove, remove all and delete</td>
</table>
 
---
 
### Colour of
The colour of an item, can also be used to colour chat messages with "&lt;%colour of ...%&gt;this text is coloured!".
 
```java
on click on wool:
	message "This wool block is <%colour of block%>%colour of block%<reset>!"
	set the colour of the block to black
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] colo[u]r[s] of %itemstacks/entities%
%itemstacks/entities%'[s] colo[u]r[s]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.2</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Colour</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>unknown</td>
</table>
 
---
 
### Coloured / Uncoloured
Parses &lt;colour&gt;s (including chat styles) in a message or removes any colours & chat styles from the message.
 
```java
on chat:
	set message to coloured message
command /fade <player>:
	trigger:
		set display name of the player-argument to uncoloured display name of the player-argument
```
<details><summary>Syntaxes</summary><p>
 
```java
(colo[u]r-|colo[u]red )%strings%
(un|non)[-](colo[u]r-|colo[u]red )%strings%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Text</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### Command
The command that caused an 'on command' event (excluding the leading slash and all arguments)
 
```java
# prevent any commands except for the /exit command during some game
on command:
{game.%player%.is playing} is true
command is not "exit"
message "You're not allowed to use commands during the game"
cancel the event
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] (full|complete|whole) command
[the] command [label]
[the] arguments
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Text</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### Command Sender
The player or the console who sent a command. Mostly useful in commands and command events.
 
```java
make the command sender execute "/say hi!"
on command:
	log "%executor% used command /%command% %arguments%" to "commands.log"
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] [command['s]] (sender|executor)
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Command Sender</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### Compass Target
The location a player's compass is pointing at.
 
```java
# make all player's compasses target a player stored in {compass target.%player%}
every 5 seconds:
	loop all players:
		set the loop-player's compass target to location of {compass target.%loop-player%}
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] compass target of %players%
%players%'[s] compass target
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Location</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>set and reset</td>
</table>
 
---
 
### Console
Represents the server's console which can receive messages and execute commands
 
```java
execute console command "/stop"
send "message to console" to the console
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] (console|server)
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.3.1</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Command Sender</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### Cooldown Time/Remaining Time/Elapsed Time/Last Usage Date/Cooldown Bypass Permission
Only usable in command events. Represents the cooldown time, the remaining time, or the elapsed time, or the last usage date, or the cooldown bypass permission.
 
```java
command /home:
	cooldown: 10 seconds
	cooldown message: You last teleported home %elapsed time% ago, you may teleport home again in %remaining time%
	trigger:
		teleport player to {home::%player%}
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] (remaining [time]|elapsed [time]|cooldown [time] [length]|last usage [date]|cooldown bypass perm[ission]) [of] [the] [(cooldown|wait)] [((of|for)[the] [current] command)]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev33</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Object</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>add, set, remove, remove all and reset</td>
</table>
 
---
 
### Coordinate
Represents a given coordinate of a location. 
 
```java
player's y-coordinate is smaller than 40:
	message "Watch out for lava!"
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] (x|y|z)(-| )(coord[inate]|pos[ition]|loc[ation])[s] of %locations%
%locations%'[s] (x|y|z)(-| )(coord[inate]|pos[ition]|loc[ation])[s]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.4.3</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>double</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>unknown</td>
</table>
 
---
 
### Creature/Entity/Player/Projectile/Villager/Powered Creeper/etc.
The entity involved in an event (an entity is a player, a creature or an inanimate object like ignited TNT, a dropped item or an arrow).
You can use the specific type of the entity that's involved in the event, e.g. in a 'death of a creeper' event you can use 'the creeper' instead of 'the entity'.
 
```java
give a diamond sword of sharpness 3 to the player
kill the creeper
kill all powered creepers in the wolf's world
projectile is an arrow
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] [event-]<.+>
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Entity</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>unknown</td>
</table>
 
---
 
### Cursor Slot
The item which player has on their cursor. This slot is always empty if player has no inventories open.
 
```java
cursor slot of player is dirt
set cursor slot of player to 64 diamonds
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] cursor slot of %players%
%players%'[s] cursor slot
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev17</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Inventory Slot</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>add, set, remove, remove all and delete</td>
</table>
 
---
 
### Custom Chest Inventory
Returns a chest inventory with the given amount of rows and the name. Use the open inventoryeffect to open it.
 
```java
open chest inventory with 1 rows named "test"
set {_inventory} to chest inventory with 1 row
```
<details><summary>Syntaxes</summary><p>
 
```java
[a [new]] chest inventory (named|with name) %string% [with %-number% row[s]]
[a [new]] chest inventory with %number% row[s] [(named|with name) %-string%]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev34</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Inventory</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>add, set, remove, remove all and delete</td>
</table>
 
---
 
### Damage
How much damage is done in a damage event, possibly ignoring armour, criticals and/or enchantments. Can be changed (remember that in Skript '1' is one full heart, not half a heart).
 
```java
increase the damage by 2
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] damage
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.3.5</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>double</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### Damage Cause
The damage cause of a damage event. Please click on the link for more information.
 
```java
damage cause is lava, fire or burning
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] damage (cause|type)
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Damage Cause</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### Data Value
The data value of an item.
You usually don't need this expression as you can check and set items with aliases easily, but this expression can e.g. be used to "add 1 to data of &lt;item&gt;", e.g. for cycling through all wool colours.
 
```java
add 1 to the data value of the clicked block
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] ((data|damage)[s] [value[s]]|durabilit(y|ies)) of %itemstacks/slots%
%itemstacks/slots%'[s] ((data|damage)[s] [value[s]]|durabilit(y|ies))
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.2</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>short</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>unknown</td>
</table>
 
---
 
### Date Ago/Later
A date the specified timespan before/after another date.
 
```java
set {_yesterday} to 1 day ago
```
<details><summary>Syntaxes</summary><p>
 
```java
%timespan% (ago|in the past|before [the] [date] %-date%)
%timespan% (later|(from|after) [the] [date] %-date%)
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev33</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Date</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### Default Value
A shorthand expression for giving things a default value. If the first thing isn't set, the second thing will be returned.
 
```java
broadcast {score::%player's uuid%} otherwise "%player% has no score!"
```
<details><summary>Syntaxes</summary><p>
 
```java
%objects% (otherwise|?) %objects%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev36</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Object</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### Difference
The difference between two values, e.g. numbers, dates or times.
 
```java
difference between {command.%player%.lastuse} and now is smaller than a minute:
  message "You have to wait a minute before using this command again!"
  stop
```
<details><summary>Syntaxes</summary><p>
 
```java
difference (between|of) %object% and %object%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.4</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Object</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>unknown</td>
</table>
 
---
 
### Direction
A helper expression for the direction type.
 
```java
thrust the player upwards
set the block behind the player to water
loop blocks above the player:
	set {_rand} to a random integer between 1 and 10
	set the block {_rand} meters south east of the loop-block to stone
block in horizontal facing of the clicked entity from the player is air
spawn a creeper 1.5 meters horizontally behind the player
spawn a TNT 5 meters above and 2 meters horizontally behind the player
thrust the last spawned TNT in the horizontal direction of the player with speed 0.2
push the player upwards and horizontally forward at speed 0.5
push the clicked entity in in the direction of the player at speed -0.5
open the inventory of the block 2 blocks below the player to the player
teleport the clicked entity behind the player
grow a regular tree 2 meters horizontally behind the player
```
<details><summary>Syntaxes</summary><p>
 
```java
[%-number% [(block|met(er|re))[s]] [to the]] (north[(-| |)(east|west)][(ward(s|ly|)|er(n|ly|))] [of]|south[(-| |)(east|west)][(ward(s|ly|)|er(n|ly|))] [of]|(east|west)[(ward(s|ly|)|er(n|ly|))] [of]|above|over|(up|down)[ward(s|ly|)]|below|under[neath]|beneath) [%-direction%]
[%-number% [(block|met(er|re))[s]]] in [the] (direction|horizontal direction|facing|horizontal facing) of %entity/block% (of|from|)
[%-number% [(block|met(er|re))[s]]] in %entity/block%'[s] (direction|horizontal direction|facing|horizontal facing) (of|from|)
[%-number% [(block|met(er|re))[s]]] (in[ ]front [of]|forward[s]|behind|backwards|[to the] (right|-left) [of])
[%-number% [(block|met(er|re))[s]]] horizontal[ly] (in[ ]front [of]|forward[s]|behind|backwards|to the (right|-left) [of])
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0 (basic), 2.0 (extended)</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Direction</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### Distance
The distance between two points.
 
```java
distance between the player and {%player%.home} is smaller than 20:
	message "You're very close to your home!"
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] distance between %location% and %location%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>double</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### Drops
Only works in death events. Holds the drops of the dying creature. Drops can be prevented by removing them with "remove ... from drops", e.g. "remove all pickaxes from the drops", or "clear drops" if you don't want any drops at all.
 
```java
clear drops
remove 4 planks from the drops
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] drops
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Item / Material</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>unknown</td>
</table>
 
---
 
### Element of
The first, last or a random element of a set, e.g. a list variable.
See also: random
 
```java
give a random element out of {free items::*} to the player
```
<details><summary>Syntaxes</summary><p>
 
```java
(-[the] first|[the] last|[a] random|%-number%(st|nd|rd|th)) element [out] of %objects%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Object</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>unknown</td>
</table>
 
---
 
### Enchantment Level
The level of a particular enchantment on an item
 
```java
player' tool is a sword of sharpness:
	message "You have a sword of sharpness %level of sharpness of the player's tool% equipped"
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] (%-enchantment% level|level of [[the] enchant[ment]] %-enchantment%) o(f|n) %itemtypes%
%itemtypes%'[s] (%-enchantment% level|level of [[the] enchant[ment]] %-enchantment%)
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>integer</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### Ender Chest
The ender chest of a player
 
```java
open the player's ender chest to the player
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] ender[ ]chest[s] of %players%
%players%'[s] ender[ ]chest[s]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Inventory</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>add, set, remove, remove all and delete</td>
</table>
 
---
 
### Entities
all entities in all world, in a specific world or in a radius around a certain location, e.g. 'all players', 'all creepers in the player's world', or 'players in radius 100 of the player'.
 
```java
kill all creepers in the player's world
send "Psst!" to all players witin 100 meters of the player
give a diamond to all ops
heal all tamed wolves in radius 2000 around {town center}
```
<details><summary>Syntaxes</summary><p>
 
```java
[(all [[of] the]|the)] %*entitydatas% [(in|of) [world[s]] %-worlds%]
[(all [[of] the]|the)] entities of type[s] %entitydatas% [(in|of) [world[s]] %-worlds%]
[(all [[of] the]|the)] %*entitydatas% (within|[with]in radius) %number% [(block[s]|met(er|re)[s])] (of|around) %location%
[(all [[of] the]|the)] entities of type[s] %entitydatas% in radius %number% (of|around) %location%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.2.1</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Entity</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>add, remove and remove all</td>
</table>
 
---
 
### Exhaustion
The exhaustion of a player. This is mainly used to determine the rate of hunger depletion.
 
```java
set exhaustion of all players to 1
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] exhaustion of %players%
%players%'[s] exhaustion
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev35</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Number</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>add, set, remove, remove all, delete and reset</td>
</table>
 
---
 
### Experience
How much experience was spawned in an experience spawn event. Can be changed.
 
```java
on experience spawn:
	add 5 to the spawned experience
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] (spawned|dropped|) [e]xp[erience] [orb[s]]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.1</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Experience</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>add, set, remove, remove all and delete</td>
</table>
 
---
 
### Facing
The facing of an entity or block, i.e. exactly north, south, east, west, up or down (unlike direction which is the exact direction, e.g. '0.5 south and 0.7 east')
 
```java
# makes a bridge
loop blocks from the block below the player in the horizontal facing of the player:
	set block to cobblestone
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] (horizontal|) facing of %livingentities/blocks%
%livingentities/blocks%'[s] (horizontal|) facing
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.4</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Direction</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>unknown</td>
</table>
 
---
 
### Filter
Filters a list based on a condition. For example, if you ran 'broadcast "something" and "something else" where [string input is "something"]only "something" would be broadcast as it is the only string that matched the condition.
 
```java
send "congrats on being staff!" to all players where [player input has permission "staff"]
```
<details><summary>Syntaxes</summary><p>
 
```java
%objects% (where|that match) \[<.+>\]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev36</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Object</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>unknown</td>
</table>
 
---
 
### Filter Input
Represents the input in a filter expression. For example, if you ran 'broadcast "something" and "something else" where [input is "something"]the condition would be checked twice, using "something" and "something else" as the inputs.
 
```java
send "congrats on being staff!" to all players where [input has permission "staff"]
```
<details><summary>Syntaxes</summary><p>
 
```java
input
%*classinfo% input
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev36</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Object</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### Final Damage
How much damage is done in a damage event, considering all types of damage reduction. Can NOT be changed.
 
```java
send "%final damage%" to victim
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] final damage
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev19</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>double</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### Flight Mode
Whether the player(s) are allowed to fly. Use Make Fly effect to force player(s) to fly.
 
```java
set flight mode of player to true
send "%flying state of all players%"
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] fl(y[ing]|ight) (mode|state) of %players%
%players%'[s] fl(y[ing]|ight) (mode|state)
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev34</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Boolean</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>set and reset</td>
</table>
 
---
 
### Food Level
The food level of a player from 0 to 10. Has several aliases: food/hunger level/meter/bar. 
 
```java
set the player's food level to 10
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] (food|hunger)[[ ](level|met(er|re)|bar)] [of %player%]
%player%'[s] (food|hunger)[[ ](level|met(er|re)|bar)]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>float</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>add, set, remove, delete and reset</td>
</table>
 
---
 
### Formatted time
Converts date to human-readable text format. By default, yyyy-MM-dd HH:mm:ss z will be used. For reference, see this Wikipedia article.
 
```java
now formatted human-readable
```
<details><summary>Syntaxes</summary><p>
 
```java
%dates% formatted [human-readable] [(with|as) %-string%]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev31</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Text</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### Former/Future State
Represents the value of an expression before an event happened or the value it will have directly after the event, e.g. the old or new level respectively in a level change event.
Note: The past, future and present states of an expression are sometimes called 'time states' of an expression.
Note 2: If you don't specify whether to use the past or future state of an expression that has different values, its default value will be used which is usually the value after the event.
 
```java
on teleport:
	former world was "world_nether" # or 'world was'
	world will be "world" # or 'world after the event is'
on tool change:
	past tool is an axe
	the tool after the event will be air
on weather change:
	set {weather.%world%.old} to past weather
	set {weather.%world%.current} to the new weather
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] (former|past|old) [state] [of] %~object%
%~object% before [the event]
[the] (future|to-be|new) [state] [of] %~object%
%~object%(-to-be| after[(wards| the event)])
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.1</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Object</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>unknown</td>
</table>
 
---
 
### Furnace Slot
A slot of a furnace, i.e. either the ore, fuel or result slot.
Remember to use 'block' and not 'furnace', as 'furnace' is not an existing expression.
 
```java
set the fuel slot of the clicked block to a lava bucket
set the block's ore slot to 64 iron ore
give the result of the block to the player
clear the result slot of the block
```
<details><summary>Syntaxes</summary><p>
 
```java
(fuel|result) [slot]
(ore|fuel|result)[s] [slot[s]] of %blocks%
%blocks%'[s] (ore|fuel|result)[s] [slot[s]]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Inventory Slot</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>add, set, remove, remove all and delete</td>
</table>
 
---
 
### Game Mode
The gamemode of a player.
 
```java
player's gamemode is survival
set the player's gamemode to creative
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] game[ ]mode of %players%
%players%'[s] game[ ]mode
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Game Mode</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>set and reset</td>
</table>
 
---
 
### Gliding State
Sets of gets gliding state of player. It allows you to set gliding state of entity even if they do not have Elytra equipped.
 
```java
set gliding of player to off
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] (gliding|glider) [state] of %entities%
%entities%'[s] (gliding|glider) [state]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev21</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Boolean</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>set and reset</td>
</table>
 
---
 
### Glowing
Indicates if targeted entity is glowing (new 1.9 effect) or not. Glowing entities can be seen through walls.
 
```java
set glowing of player on
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] glowing of %entities%
%entities%'[s] glowing
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev18</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Boolean</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>set and reset</td>
</table>
 
---
 
### Gravity
If entity is affected by gravity or not, i.e. if it has Minecraft 1.10+ NoGravity flag.
 
```java
set gravity of player off
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] gravity of %entities%
%entities%'[s] gravity
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev21</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Boolean</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>set and reset</td>
</table>
 
---
 
### Group
The primary group or all groups of a player. This expression requires Vault and a compatible permissions plugin to be installed.
 
```java
on join:
broadcast "%group of player%" # this is the player's primary group
broadcast "%groups of player%" # this is all of the player's groups
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] group[(s)] of %offlineplayers%
%offlineplayers%'[s] group[(s)]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev35</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Text</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>add, set, remove, delete and reset</td>
</table>
 
---
 
### Hash
Hashes the given text using the MD5 or SHA-256 algorithms. Each algorithm is suitable for different use cases.<p>
MD5 is provided mostly for backwards compatibility, as it is outdated and not secure. 
SHA-256 is more secure, and can used to hash somewhat confidental data like IP addresses and even passwords. 
It is not that secure out of the box, so please consider using salt when dealing with passwords! 
When hashing data, you must specify algorithms that will be used for security reasons! 
<p>Please note that a hash cannot be reversed under normal circumstanses. You will not be able to get original value from a hash with Skript.
 
```java
command /setpass <text>:
	trigger:
		set {password.%player%} to text-argument hashed with SHA-256
command /login <text>:
	trigger:
		{password.%player%} is text-argument hashed with SHA-256:
			message "Login successful."
		else:
			message "Wrong password!"
```
<details><summary>Syntaxes</summary><p>
 
```java
%strings% hash[ed] with (MD5|SHA-256)
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.0, 2.2-dev32 (SHA-256 algorithm)</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Text</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### Head location
The location of an entity's head, mostly useful for players and e.g. looping blocks in the player's line of sight.
Please note that this location is only accurate for entities whose head is exactly above their center, i.e. players, endermen, zombies, skeletons, etc., but not sheep, pigs or cows.
 
```java
set the block at the player's head to air
set the block in front of the player's eyes to glass
loop blocks in front of the player's head:
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] (head|eye[s]) [location[s]] of %livingentities%
%livingentities%'[s] (head|eye[s]) [location[s]]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Location</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### Health
The health of a creature, e.g. a player, mob, villager, etc. from 0 to the creature's max health, e.g. 10 for players.
 
```java
message "You have %health% HP left."
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] health of %livingentities%
%livingentities%'[s] health
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>double</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>add, set, remove, delete and reset</td>
</table>
 
---
 
### Hidden Players
The players hidden from a player that hidden using the player visibility effect.
 
```java
message "<light red>You are currently hiding: <light gray>%hidden players of the player%"
```
<details><summary>Syntaxes</summary><p>
 
```java
[(all [[of] the]|the)] hidden players (of|for) %players%
[(all [[of] the]|the)] players hidden (from|for|by) %players%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>INSERT VERSION</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Player</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>add, remove and remove all</td>
</table>
 
---
 
### Highest Solid Block
Returns the highest solid block at the x and z coordinates of the world of given location
 
```java
highest block at location of arg-player
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] highest [(solid|non-air)] block[s] at %locations%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev34</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Block</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>add, set, remove, remove all and delete</td>
</table>
 
---
 
### Hotbar Slot
The slot number of the currently selected hotbar slot.
 
```java
message "%player's current hotbar slot%"
set player's selected hotbar slot to slot 4 of player
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] [([currently] selected|current)] hotbar slot of %players%
%players%'[s] [([currently] selected|current)] hotbar slot
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev36</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Inventory Slot</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>set</td>
</table>
 
---
 
### Humidity
Humidity of given blocks
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] humidit(y|ies) of %blocks%
%blocks%'[s] humidit(y|ies)
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev35</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>double</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### IP
The IP address of a player.
 
```java
IP-ban the player # is equal to the next line
ban the IP-address of the player
broadcast "Banned the IP %IP of player%"
```
<details><summary>Syntaxes</summary><p>
 
```java
IP[s][( |-)address[es]] of %players%
%players%'[s] IP[s][( |-)address[es]]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.4, 2.2-dev26 (when used in connect event)</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Text</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### Id
The id of a specific item. You usually don't need this expression as you can likely do everything with aliases.
 
```java
message "the ID of %type of the clicked block% is %id of the clicked block%."
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] id(s|) of %itemtype%
%itemtype%'[s] id(s|)
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>integer</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>unknown</td>
</table>
 
---
 
### Index Of
The first or last index of a character (or text) in a text, or -1 if it doesn't occur in the text. Indices range from 1 to the length of the text.
 
```java
set {_@} to the first index of "@" in the text argument
if {_s} contains "abc":
	set {_s} to the first (index of "abc" in {_s} + 3) characters of {_s} # removes everything after the first "abc" from {_s}
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] (|first|last) index of %string% in %string%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.1</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>integer</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### Indices of List
Gets indices of a list variable.
 
```java
set {l::*} to "some", "cool" and "values"
broadcast "%all indices of {l::*}%" # Result is 1, 2 and 3
```
<details><summary>Syntaxes</summary><p>
 
```java
[(all [[of] the]|the)] indices of %objects%
%objects%'s indices
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev37</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Text</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### Inventory
The inventory of a block or player. You can usually omit this expression and can directly add or remove items to/from blocks or players.
 
```java
add a plank to the player's inventory
clear the player's inventory
remove 5 wool from the inventory of the clicked block
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] inventor(y|ies) of %inventoryholders%
%inventoryholders%'[s] inventor(y|ies)
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Object</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>add, set, remove, remove all and delete</td>
</table>
 
---
 
### Inventory Action
The inventory action of an inventory event. Please click on the link for more information.
 
```java
inventory action is pickup all
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] inventory action
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev16</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Inventory Action</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### Inventory Holder/Viewers/Rows
Gets the rows/size/viewers/holder of an inventory.
 
```java
event-inventory's amount of rows
holder of player's top inventory
{_inventory}'s viewers
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] (holder[s]|viewers|[amount of] rows) of %inventories%
%inventories%'[s] (holder[s]|viewers|[amount of] rows)
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev34</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Object</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>add, remove and remove all</td>
</table>
 
---
 
### Inventory Slot
Represents a slot in a inventory. It can be used to change the item in a inventory too.
 
```java
if slot 0 of player is air:
	set slot 0 of player to 2 stones
	remove 1 stone from slot 0 of player
	add 2 stones to slot 0 of player
	clear slot 1 of player
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] slot[s] %numbers% of %inventory%
%inventory%'[s] slot[s] %numbers%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev24</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Inventory Slot</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>add, set, remove, remove all and delete</td>
</table>
 
---
 
### Item
The item involved in an event, e.g. in a drop, dispense, pickup or craft event.
 
```java
on dispense:
	item is a clock
	set the time to 6:00
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] item
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td><i>unknown</i> (before 2.1)</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Item / Material</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### Item Amount
The amount of an item stack.
 
```java
send "You have got %item amount of player's tool% %player's tool% in your hand !" to player
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] item[[ ]stack] (amount|size|number) of %itemstacks%
%itemstacks%'[s] item[[ ]stack] (amount|size|number)
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev24</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Number</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>add, set, remove, delete and reset</td>
</table>
 
---
 
### Item Enchantments
All the enchantments an item type has.
 
```java
clear enchantments of event-item
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] enchantments of %itemtypes%
%itemtypes%'[s] enchantments
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev36</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Enchantment Type</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>add, set, remove, remove all, delete and reset</td>
</table>
 
---
 
### Item of an Entity
An item associated with an entity. For dropped item entities, it gets, obviously, the item that was dropped. For item frames, the item inside the frame is returned. Other entities do not have items associated with them.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] item of %entities%
%entities%'[s] item
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev35, 2.2-dev36 (improved)</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Inventory Slot</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>add, set, remove, remove all and delete</td>
</table>
 
---
 
### Items
Items or blocks of a specific type, useful for looping.
 
```java
loop items of type ore and log:
	block contains loop-item
	message "Theres at least one %loop-item% in this block"
drop all blocks at the player # drops one of every block at the player
```
<details><summary>Syntaxes</summary><p>
 
```java
[(all [[of] the]|the|every)] item(s|[ ]types)
[(all [[of] the]|the)] items of type[s] %itemtypes%
[(all [[of] the]|the|every)] block(s|[ ]types)
[(all [[of] the]|the)] blocks of type[s] %itemtypes%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td><i>unknown</i> (before 2.1)</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Item / Material</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### Items In
All items in an inventory. Useful for looping or storing in a list variable.
Please note that the positions of the items in the inventory are not saved, only their order is preserved.
 
```java
loop all items in the player's inventory:
	loop-item is enchanted
	remove loop-item from the player
set {inventory.%player%} to items in the player's inventory
```
<details><summary>Syntaxes</summary><p>
 
```java
[(all [[of] the]|the)] items ([with]in|of|contained in|out of) (|inventor(y|ies)) %inventories%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Inventory Slot</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>add, set, remove, remove all and delete</td>
</table>
 
---
 
### Join & Split
Joins several texts with a common delimiter (e.g. ", "), or splits a text into multiple texts at a given delimiter.
 
```java
message "Online players: %join all players with " | "%" # %all players% would use the default "x, y, and z"
set {_s::} to the string argument split at ","
```
<details><summary>Syntaxes</summary><p>
 
```java
(concat[enate]|join) %objects% [(with|using|by) [[the] delimiter] %-string%]
split %string% (at|using|by) [[the] delimiter] %string%
%string% split (at|using|by) [[the] delimiter] %string%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.1</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Text</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### Language
Currently selected game language of a player. The value of the language is not defined properly.
The vanilla Minecraft client will use lowercase language / country pairs separated by an underscore, but custom resource packs may use any format they wish.
 
```java
message player's current language
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] [([currently] selected|current)] [game] (language|locale) [setting] of %players%
%players%'[s] [([currently] selected|current)] [game] (language|locale) [setting]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev37</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Text</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### Last Damage Cause
Cause of last damage done to an entity
 
```java
set last damage cause of event-entity to fire tick
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] last damage (cause|reason|type) of %livingentities%
%livingentities%'[s] last damage (cause|reason|type)
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-Fixes-V10</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Damage Cause</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>add, set, remove, delete and reset</td>
</table>
 
---
 
### Last Spawned Entity
Holds the entity that was spawned most recently with the spawn effect, drop with the drop effect or shot with the shoot effect. Please note that even though you can spawn multiple mobs simultaneously (e.g. with 'spawn 5 creepers'), only the last spawned mob is saved and can be used. If you spawn an entity, shoot a projectile and drop a item you can however access all them together.
 
```java
spawn a priest
set {%spawned priest%.healer} to true
shoot an arrow from the last spawned entity
ignite the shot projectile
drop a diamond sword
push last dropped item upwards
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] [last[ly]] (spawned|shot) %*entitydata%
[the] [last[ly]] dropped (item)
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.3 (spawned entity), 2.0 (shot entity), 2.2-dev26 (dropped item)</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Entity</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>unknown</td>
</table>
 
---
 
### Length
The length of a text, in number of characters.
 
```java
set {_l} to length of the string argument
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] length of %strings%
%strings%'[s] length
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.1</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>integer</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### Level
The level of a player.
 
```java
reduce the victim's level by 1
set the player's level to 0
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] level of %players%
%players%'[s] level
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td><i>unknown</i> (before 2.1)</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>integer</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>add, set, remove, delete and reset</td>
</table>
 
---
 
### Level Progress
The progress a player has made until the next level. Remember that this value is between 0 and 1, not 0 and 100!
Changing this value can cause a player's level to change if the resulting level progess is negative or larger than 1, e.g.increase the player's level progress by 0.5 will make the player gain a level if his progress was more than 50%.
 
```java
# use the exp bar as mana
on rightclick with a blaze rod:
	player's level progress is larger than 0.2
	shoot a fireball from the player
	reduce the player's level progress by 0.2
every 2 seconds:
	loop all players:
		level progress of loop-player is smaller than 0.9:
			increase level progress of the loop-player by 0.1
		else:
			set level progress of the loop-player to 0.99
on xp spawn:
	cancel event
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] level progress of %players%
%players%'[s] level progress
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>float</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>add, set, remove, delete and reset</td>
</table>
 
---
 
### Light Level
Gets the light level at a certain location which ranges from 0 to 15.
It can be separated into sunlight (15 = direct sunlight, 1-14 = indirect) and block light (torches, glowstone, etc.). The total light level of a block is the maximum of the two different light types.
 
```java
# set vampire players standing in bright sunlight on fire
every 5 seconds:
	loop all players:
		{vampire.%loop-player%} is true
		sunlight level at the loop-player is greater than 10
		ignite the loop-player for 5 seconds
```
<details><summary>Syntaxes</summary><p>
 
```java
[(sky|sun|block)[ ]]light[ ]level [(of|%direction%) %location%]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.3.4</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>byte</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### Location
The location where an event happened (e.g. at an entity or block), or a location relative to another (e.g. 1 meter above another location).
 
```java
drop 5 apples at the event-location # exactly the same as writing 'drop 5 apples'
set {_loc} to the location 1 meter above the player
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] [event-](location|position)
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Location</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>unknown</td>
</table>
 
---
 
### Location
The location where an event happened (e.g. at an entity or block), or a location relative to another (e.g. 1 meter above another location).
 
```java
drop 5 apples at the event-location # exactly the same as writing 'drop 5 apples'
set {_loc} to the location 1 meter above the player
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] (location|position) %directions% [%location%]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Location</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>unknown</td>
</table>
 
---
 
### Location
The location of a block or entity. This not only represents the x, y and z coordinates of the location but also includes the world and the direction an entity is looking (e.g. teleporting to a saved location will make the teleported entity face the same saved direction every time).
Please note that the location of an entity is at it's feet, use head location to get the location of the head.
 
```java
set {home.%player%} to the location of the player
message "You home was set to %player's location% in %player's world%."
```
<details><summary>Syntaxes</summary><p>
 
```java
(location|position) of %location%
%location%'[s] (location|position)
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Location</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>unknown</td>
</table>
 
---
 
### Location At
Allows to create a location from three coordinates and a world.
 
```java
set {_loc} to the location at arg-1, arg-2, arg-3 of the world arg-4
distance between the player and the location (0, 0, 0) is less than 200
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] (location|position) [at] [(][x[ ][=[ ]]]%number%, [y[ ][=[ ]]]%number%, [and] [z[ ][=[ ]]]%number%[)] [[(in|of) [[the] world]] %world%]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Location</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### Loop value
The currently looped value.
 
```java
# countdown:
loop 10 times:
	message "%11 - loop-number%"
	wait a second
# generate a 10x10 floor made of randomly coloured wool below the player:
loop blocks from the block below the player to the block 10 east of the block below the player:
	loop blocks from the loop-block to the block 10 north of the loop-block:
		set loop-block-2 to any wool
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] loop-<.+>
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Object</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>unknown</td>
</table>
 
---
 
### Lore
An item's lore.
 
```java
set the 1st line of the item's lore to "<orange>Excalibur 2.0"
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] lore of %itemstack/itemtype%
%itemstack/itemtype%'[s] lore
[the] line %number% of [the] lore of %itemstack/itemtype%
[the] line %number% of %itemstack/itemtype%'[s] lore
[the] %number%(st|nd|rd|th) line of [the] lore of %itemstack/itemtype%
[the] %number%(st|nd|rd|th) line of %itemstack/itemtype%'[s] lore
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.1</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Text</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>unknown</td>
</table>
 
---
 
### Max Health
The maximum health of an entity, e.g. 10 for a player
 
```java
on join:
	set the maximum health of the player to 100
spawn a giant
set the last spawned entity's max health to 1000
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] max[imum] health of %livingentities%
%livingentities%'[s] max[imum] health
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>double</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>add, set, remove and reset</td>
</table>
 
---
 
### Maximum Stack Size
The maximum stack size of the specified material, e.g. 64 for torches, 16 for buckets, and 1 for swords.
 
```java
send "You can only pick up %max stack size of player's tool% of %type of (player's tool)%" to player
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] max[imum] stack[[ ]size] of %itemstack%
%itemstack%'[s] max[imum] stack[[ ]size]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.1</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>integer</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### Me
A 'me' expression that can be used in effect commands only.
 
```java
!heal me
!kick myself
!give a diamond axe to me
```
<details><summary>Syntaxes</summary><p>
 
```java
me
my[self]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.1.1</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Command Sender</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### Message
The (chat) message of a chat event, the join message of a join event, the quit message of a quit event, or the death message on a death event. This expression is mostly useful for being changed.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] [chat( |-)]message
[the] (join|log[ ]in)( |-)message
[the] (quit|leave|log[ ]out|kick)( |-)message
[the] death( |-)message
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.4.6 (chat message), 1.4.9 (join & quit messages), 2.0 (death message)</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Text</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>set</td>
</table>
 
---
 
### Metadata
Metadata is a way to store temporary data on entities, blocks and more thatdisappears after a server restart.
 
```java
set metadata value "healer" of player to true
broadcast "%metadata value ""healer"" of player%"
clear metadata value "healer" of player
```
<details><summary>Syntaxes</summary><p>
 
```java
metadata [(value|tag)[s]] %strings% of %metadataholders%
%metadataholders%'[s] metadata [(value|tag)[s]] %string%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev36</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Object</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>set and delete</td>
</table>
 
---
 
### Moved blocks
Blocks which are moved in piston event. Cannot be used outside of piston events.
 
```java
the moved blocks
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] moved blocks
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev27</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Block</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>add, set, remove, remove all and delete</td>
</table>
 
---
 
### Name / Display Name
Represents a player's minecraft account name, chat display name, or playerlist name, or the custom name of an item, en entity or an inventory.
The differences between the different names are:
<ul>
name: Minecraft account name of a player (unmodifiable), or the custom name of an item or mob (modifiable).
display name: The name of a player as displayed in the chat and messages, e.g. when including %player% in a message. This name can be changed freely and can include colour codes, and is shared among all plugins (e.g. chat plugins will use a changed name).
tab list name: The name of a player used in the player lists that usually opens with the tab key. Please note that this is limited to 16 characters, including colour codes which are counted as 2 characters each, and that no two players can have the same tab list name at the same time.
</ul>
 
```java
on join:
	player has permission "name.red"
	set the player's display name to "<red>[admin]<gold>%name of player%"
	set the player's tablist name to "<green>%name of player%"
set the name of the player's tool to "Legendary Sword of Awesomeness"
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] ()(player|tab)[ ]list name[s] of %players%
%players%'[s] ()(player|tab)[ ]list name[s]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.4.6 (players' name & display name), <i>unknown</i> (player list name), 2.0 (item name), 2.2-dev20 (inventory name)</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Text</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>unknown</td>
</table>
 
---
 
### Name / Display Name
Represents a player's minecraft account name, chat display name, or playerlist name, or the custom name of an item, en entity or an inventory.
The differences between the different names are:
<ul>
name: Minecraft account name of a player (unmodifiable), or the custom name of an item or mob (modifiable).
display name: The name of a player as displayed in the chat and messages, e.g. when including %player% in a message. This name can be changed freely and can include colour codes, and is shared among all plugins (e.g. chat plugins will use a changed name).
tab list name: The name of a player used in the player lists that usually opens with the tab key. Please note that this is limited to 16 characters, including colour codes which are counted as 2 characters each, and that no two players can have the same tab list name at the same time.
</ul>
 
```java
on join:
	player has permission "name.red"
	set the player's display name to "<red>[admin]<gold>%name of player%"
	set the player's tablist name to "<green>%name of player%"
set the name of the player's tool to "Legendary Sword of Awesomeness"
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] ()(display|nick|chat)[ ]name[s] of %itemstacks/slots/livingentities/players/inventories%
%itemstacks/slots/livingentities/players/inventories%'[s] ()(display|nick|chat)[ ]name[s]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.4.6 (players' name & display name), <i>unknown</i> (player list name), 2.0 (item name), 2.2-dev20 (inventory name)</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Text</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>unknown</td>
</table>
 
---
 
### Name / Display Name
Represents a player's minecraft account name, chat display name, or playerlist name, or the custom name of an item, en entity or an inventory.
The differences between the different names are:
<ul>
name: Minecraft account name of a player (unmodifiable), or the custom name of an item or mob (modifiable).
display name: The name of a player as displayed in the chat and messages, e.g. when including %player% in a message. This name can be changed freely and can include colour codes, and is shared among all plugins (e.g. chat plugins will use a changed name).
tab list name: The name of a player used in the player lists that usually opens with the tab key. Please note that this is limited to 16 characters, including colour codes which are counted as 2 characters each, and that no two players can have the same tab list name at the same time.
</ul>
 
```java
on join:
	player has permission "name.red"
	set the player's display name to "<red>[admin]<gold>%name of player%"
	set the player's tablist name to "<green>%name of player%"
set the name of the player's tool to "Legendary Sword of Awesomeness"
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] ()name[s] of %itemstacks/slots/livingentities/players/inventories%
%itemstacks/slots/livingentities/players/inventories%'[s] ()name[s]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.4.6 (players' name & display name), <i>unknown</i> (player list name), 2.0 (item name), 2.2-dev20 (inventory name)</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Text</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>unknown</td>
</table>
 
---
 
### Named Item/Inventory
Directly names an item/inventory, useful for defining a named item/inventory in a script. If you want to (re)name existing items/inventories you can either use this expression or use set <a href='#ExprName'>name of &lt;item/inventory&gt; to &lt;text&gt;</code>.
 
```java
give a diamond sword of sharpness 100 named "<gold>Excalibur" to the player
set tool of player to the player's tool named "<gold>Wand"
set the name of the player's tool to "<gold>Wand"
open hopper inventory named "Magic Hopper" to player
```
<details><summary>Syntaxes</summary><p>
 
```java
%itemtype/inventorytype% (named|with name) %string%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.0, 2.2-dev34 (inventories)</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Object</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### Now
The current system time of the server. Use time to get the Minecraft time of a world.
 
```java
broadcast "Current server time: %now%"
```
<details><summary>Syntaxes</summary><p>
 
```java
now
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.4</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Date</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### Numbers
All numbers between two given numbers, useful for looping.
Use 'numbers' if your start is not an integer and you want to keep the fractional part of the start number constant, or use 'integers' if you only want to loop integers.
An integer loop from 1 to a number x can also be written as 'loop x times'.
 
```java
loop 5 times: # loops 1, 2, 3, 4, 5
loop numbers from 2.5 to 5.5: # loops 2.5, 3.5, 4.5, 5.5
loop integers from 2.9 to 5.1: # same as '3 to 5', i.e. loops 3, 4, 5
```
<details><summary>Syntaxes</summary><p>
 
```java
[(all [[of] the]|the)] (numbers|integers) (between|from) %number% (and|to) %number%
%number% times
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.4.6</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Number</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### Offline players
All player that have ever joined the server. This includes players currently online.
 
```java
send "Size of all players who have joined the server: %size of all offline players%"
```
<details><summary>Syntaxes</summary><p>
 
```java
[(all [[of] the]|the)] offline[ ]players
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev35</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Offlineplayer</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### Opened Inventory
Return the currently opened inventory of a player.
If no inventory is open, it returns the own player's crafting inventory.
 
```java
set slot 1 of player's current inventory to diamond sword
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] (current|open|top) inventory [of %players%]
%players%'[s] (current|open|top) inventory
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev24, 2.2-dev35 (Just 'current inventory' works in player events)</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Inventory</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>add, set, remove, remove all and delete</td>
</table>
 
---
 
### Parse
Parses text as a given type, or as a given pattern.
This expression can be used in two different ways: One which parses the entire text as a single instance of a type, e.g. as a number, and one that parses the text according to a pattern.
If the given text could not be parsed, this expression will return nothing and the parse error will be set if some information is available.
Some notes about parsing with a pattern:
- The pattern must be a Skript pattern, e.g. percent signs are used to define where to parse which types, e.g. put a %number% or %items% in the pattern if you expect a number or some items there.
- You have to save the expression's value in a list variable, e.g. set {parsed::*} to message parsed as "...".
- The list variable will contain the parsed values from all %types% in the pattern in order. If a type was plural, e.g. %items%, the variable's value at the respective index will be a list variable, e.g. the values will be stored in {parsed::1::*}, not {parsed::1}.
 
```java
set {var} to line 1 parsed as number
on chat:
	set {var::*} to message parsed as "buying %items% for %money%"
	if parse error is set:
		message "%parse error%"
	else if {var::*} is set:
		cancel event
		remove {var::2} from the player's balance
		give {var::1::*} to the player
```
<details><summary>Syntaxes</summary><p>
 
```java
%string% parsed as (%-*classinfo%|"<.*>")
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Object</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### Parse Error
The error which caused the last parse operation to fail, which might not be set if a pattern was used and the pattern didn't match the provided text at all.
 
```java
set {var} to line 1 parsed as integer
if {var} is not set:
	parse error is set:
		message "<red>Line 1 is invalid: %last parse error%"
	else:
		message "<red>Please put an integer on line 1!"
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] [last] [parse] error
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Text</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### Passenger
The passenger of a vehicle, or the rider of a mob.
See also: vehicle
For 1.11.2 and above, it returns a list of passengers and you can use all changers in it.
 
```java
#for 1.11 and lower
passenger of the minecart is a creeper or a cow
the saddled pig's passenger is a player
#for 1.11.2+
passengers of the minecart contains a creeper or a cow
the boat's passenger contains a pig
add a cow and a zombie to passengers of last spawned boat
set passengers of player's vehicle to a pig and a horse
remove all pigs from player's vehicle
clear passengers of boat
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] passenger[s] of %entities%
%entities%'[s] passenger[s]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.0, 2.2-dev26 (Multiple passengers for 1.11.2+)</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Entity</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>add, set, remove, remove all, delete and reset</td>
</table>
 
---
 
### Ping
Pings of players, as Minecraft server knows them. Note that they will almost certainly be different from the ones you'd get from using ICMP echo requests. This expression is only supported on some server software.
 
```java
command /ping <player=%player%>:
	trigger:
		send "%arg-1%'s ping is %arg-1's ping%"
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] ping of %players%
%players%'[s] ping
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev36</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Number</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### Player Weather
The weather for a player.
 
```java
set weather of arg-player to rainy
reset player's weather
if arg-player's weather is rainy
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] weather of %players%
%players%'[s] weather
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev34</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Weather Type</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>set and reset</td>
</table>
 
---
 
### Potion (item)
Potion in item form, with advanced parameters.
 
```java
strong splash potion of instant damage
```
<details><summary>Syntaxes</summary><p>
 
```java
[((regular|normal)|(strong|upgraded|level 2)|(extended|long)) ][((splash|exploding)|lingering) ]potion of %potioneffecttype%
[((regular|normal)|(strong|upgraded|level 2)|(extended|long)) ][((splash|exploding)|lingering) ]%potioneffecttype% potion
(water bottle|bottle of water)
potion
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>unknown (2.2)</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Item Type</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### Random
Gets a random item out of a set, e.g. a random player out of all players online.
 
```java
give a diamond to a random player out of all players
give a random item out of all items to the player
```
<details><summary>Syntaxes</summary><p>
 
```java
[a] random %*classinfo% [out] of %objects%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.4.9</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Object</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>unknown</td>
</table>
 
---
 
### Random Number
A random number or integer between two given numbers. Use 'number' if you want any number with decimal parts, or use use 'integer' if you only want whole numbers.
Please note that the order of the numbers doesn't matter, i.e. random number between 2 and 1 will work as well as random number between 1 and 2.
 
```java
set the player's health to a random number between 5 and 10
send "You rolled a %random integer from 1 to 6%!" to the player
```
<details><summary>Syntaxes</summary><p>
 
```java
[a] random (integer|number) (from|between) %number% (to|and) %number%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.4</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Number</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### Raw Name
Raw Minecraft material name for given item. Note that this is not guaranteed to give same results on all servers.
 
```java
raw name of tool of player
```
<details><summary>Syntaxes</summary><p>
 
```java
(raw|minecraft|vanilla) name of %itemtypes%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>unknown (2.2)</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Text</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### Remaining Air
How much time a player has left underwater before starting to drown.
 
```java
player's remaining air is less than 3 seconds:
	send "hurry, get to the surface!" to the player
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] remaining air of %livingentities%
%livingentities%'[s] remaining air
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td><i>unknown</i> (before 2.1)</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Timespan</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>add, set, remove, delete and reset</td>
</table>
 
---
 
### Respawn location
The location that a player should respawn at. This is used within the respawn event.
 
```java
on respawn:
	set respawn location to {example::spawn}
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] respawn location
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev35</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Location</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>set</td>
</table>
 
---
 
### Rounding
Rounds numbers normally, up (ceiling) or down (floor) respectively
 
```java
set {var} to rounded health of player
set line 1 of the block to round(1.5 * player's level)
set {_x} to floor({_y}) - ceil({_x})
add rounded down argument to the player's health
```
<details><summary>Syntaxes</summary><p>
 
```java
(a|the|) round[ed] down %number%
(a|the|) round[ed] %number%
(a|the|) round[ed] up %number%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>long</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### Saturation
The saturation of a player. If used in a player event, it can be omitted and will default to event-player.
 
```java
set saturation of player to 20
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] saturation [of %players%]
%players%'[s] saturation
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-Fixes-v10, 2.2-dev35 (fully modifiable)</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Number</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>add, set, remove, delete and reset</td>
</table>
 
---
 
### Script Name
Holds the current script's name (the file name without '.sk').
 
```java
on script load:
	set {running.%script%} to true
on script unload:
	set {running.%script%} to false
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] script[['s] name]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Text</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### Shooter
The shooter of a projectile.
 
```java
shooter is a skeleton
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] shooter [of %projectile%]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.3.7</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Living Entity</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>add, set, remove and remove all</td>
</table>
 
---
 
### Shuffled List
Shuffles given list randomly. This is done by replacing indices by random numbers in resulting list.
 
```java
set {_list::*} to shuffled {_list::*}
```
<details><summary>Syntaxes</summary><p>
 
```java
shuffled %objects%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev32</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Object</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### Sign Text
A line of text on a sign. Can be changed, but remember that there is a 16 character limit per line (including colour codes that use 2 characters each).
 
```java
on rightclick on sign:
	line 2 of the clicked block is "[Heal]":
		heal the player
	set line 3 to "%player%"
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] line %number% [of %block%]
[the] (1st|first|2nd|second|3rd|third|4th|fourth) line [of %block%]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.3</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Text</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>set and delete</td>
</table>
 
---
 
### Skull
Gets a skull item representing a player or an entity.
 
```java
give the victim's skull to the attacker
set the block at the entity to the entity's skull
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] skull of %offlineplayers/entities/entitydatas%
%offlineplayers/entities/entitydatas%'[s] skull
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Item Type</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### Slot Index
Index of an an inventory slot. Other types of slots may or may not have indices. Note that comparing slots with numbers is also possible; if index of slot is same as the number, comparisonsucceeds. This expression is mainly for the cases where you must for some reason save the slot numbers.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] (index|indices) of %slots%
%slots%'[s] (index|indices)
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev35</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>integer</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### Sorted List
Sorts given list in natural order. All objects in list must be comparable; usually if you think you can compare it, it can be compared.
 
```java
set {_list::*} to sorted {_list::*}
```
<details><summary>Syntaxes</summary><p>
 
```java
sorted %objects%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev19</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Object</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### Spawn
The spawnpoint of a world.
 
```java
teleport all players to spawn
set the spawn point of "world" to the player's location
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] spawn[s] [(point|location)[s]] [of %worlds%]
%worlds%'[s] spawn[s] [(point|location)[s]]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.4.2</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Location</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>set</td>
</table>
 
---
 
### Special Number
Special number values, namely NaN, Infinity and -Infinity
 
```java
if {_number} is NaN value:
```
<details><summary>Syntaxes</summary><p>
 
```java
(NaN|[(-|minus)](infinity|∞)) value
value of (NaN|[(-|minus)](infinity|∞))
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev32d</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Number</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### Spectator Target
The entity a player is currently spectating. This can be set and cleared whenthe given player is in spectator mode.
 
```java
set spectator target of player to last spawned creeper
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] spectator target of %players%
%players%'[s] spectator target
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev37</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Entity</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>set, delete and reset</td>
</table>
 
---
 
### Speed
A player's walking or flying speed. Both can be changed, but values must be between -1 and 1 (excessive values will be changed to -1 or 1 respectively). Negative values reverse directions.
Please note that changing a player's speed will change his FOV just like potions do.
 
```java
set the player's walk speed to 1
increase the argument's fly speed by 0.1
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] (walk[ing]|fl(y[ing]|ight))[( |-])speed of %players%
%players%'[s] (walk[ing]|fl(y[ing]|ight))[( |-])speed
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td><i>unknown</i> (before 2.1)</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>float</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>add, set, remove and reset</td>
</table>
 
---
 
### Subtext
Extracts part of a text. You can either get the first &lt;x&gt; characters, the last &lt;x&gt; characters, or the characters between indices &lt;x&gt; and &lt;y&gt;. The indices &lt;x&gt; and &lt;y&gt; should be between 1 and the length of the text (other values will be fit into this range).
 
```java
set {_s} to the first 5 characters of the text argument
message "%subtext of {_s} from characters 2 to (the length of {_s} - 1)%" # removes the first and last character from {_s} and sends it to the player or console
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] (part|sub[ ](text|string)) of %strings% (between|from) (ind(ex|ices)|character[s]|) %number% (and|to) (index|character|) %number%
[the] (first|last) [%-number%] character[s] of %strings%
[the] %number% (first|last) characters of %strings%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.1</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Text</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### TPS (ticks per second)
Returns the 3 most recent TPS readings, like the /tps command. This expression is only supported on some server software.
 
```java
broadcast "%tps%"
```
<details><summary>Syntaxes</summary><p>
 
```java
tps from [the] last ([1] minute|1[ ]m[inute])
tps from [the] last 5[ ]m[inutes]
tps from [the] last 15[ ]m[inutes]
[the] tps
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev36</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>double</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### Tamer
The tamer of an entity. Can only be used in entity tame events. You can use 'event-entity' to refer tamed entity itself.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] tamer
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev25</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Player</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>add, remove and remove all</td>
</table>
 
---
 
### Target
For players this is the entity at the crosshair, while for mobs and experience orbs it represents the entity they are attacking/following (if any).
 
```java
on entity target:
    entity's target is a player
    send "You're being followed by an %entity%!" to target of entity
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] target[[ed] %-*entitydata%] [of %livingentities%]
%livingentities%'[s] target[[ed] %-*entitydata%]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td><i>unknown</i> (before 2.1)</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Entity</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>add, set, remove, remove all and delete</td>
</table>
 
---
 
### Targeted Block
The block at the crosshair. This regards all blocks that are not air as fully opaque, e.g. torches will be like a solid stone block for this expression.
 
```java
# A command to set the block a player looks at to a specific type:
command /setblock <material>:
    trigger:
        set targeted block to argument
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] target[ed] block[s] [of %players%]
%players%'[s] target[ed] block[s]
[the] actual[ly] target[ed] block[s] [of %players%]
%players%'[s] actual[ly] target[ed] block[s]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Block</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>add, set, remove, remove all and delete</td>
</table>
 
---
 
### Teleport Cause
The teleport cause within a player teleport event.
 
```java
teleport cause is nether portal, end portal or end gateway
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] teleport (cause|reason|type)
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev35</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>teleportcause</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### Temperature
Temperature at given block.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] temperature[s] of %blocks%
%blocks%'[s] temperature[s]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev35</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>double</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### Ternary
A shorthand expression for returning something based on a condition.
 
```java
set {points} to 500 if {admin::%player's uuid%} is set else 100
```
<details><summary>Syntaxes</summary><p>
 
```java
%objects% if <.+>[,] (otherwise|else) %objects%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev36</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Object</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### Time
The time of a world.
 
```java
time in world is between 18:00 and 6:00:
	broadcast "It's night-time, watch out for monsters!"
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] time[s] [([with]in|of) %worlds%]
%worlds%'[s] time[s]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Time</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>add, set and remove</td>
</table>
 
---
 
### Tool
The item a player is holding.
 
```java
player is holding a pickaxe
# is the same as
player's tool is a pickaxe
player's off hand tool is shield #Only for Minecraft 1.9
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] (tool|held item|weapon) [of %livingentities%]
%livingentities%'[s] (tool|held item|weapon)
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Inventory Slot</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>add, set, remove, remove all and delete</td>
</table>
 
---
 
### Type of
The type of a block/item or entity. The type of an item is only it's id and data value, i.e. it ignores the amount, enchantments etc., and the type of an entity is e.g. 'wolf' or 'player'.
 
```java
on rightclick on an entity:
	message "This is a %type of clicked entity%!"
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] type of %entitydatas/itemstacks/inventories%
%entitydatas/itemstacks/inventories%'[s] type
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.4</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Object</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>unknown</td>
</table>
 
---
 
### UUID
The UUID of a player, entity or world.
In the future there will be an option to use a player's UUID instead of the name in variable names (i.e. when %player% is used), but for now this can be used.
Please note that this expression does not work for offline players if you are under 1.8!
 
```java
# prevents people from joining the server if they use the name of a player
# who has played on this server at least once since this script has been added
on login:
	{uuids.%name of player%} exists:
		{uuids.%name of player%} is not UUID of player
		kick player due to "Someone with your name has played on this server before"
	else:
		set {uuids.%name of player%} to UUID of player
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] UUID of %offlineplayers/worlds/entities%
%offlineplayers/worlds/entities%'[s] UUID
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.1.2, 2.2 (offline players' UUIDs), 2.2-dev24 (other entities' UUIDs)</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Text</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### Unbreakable Items
Creates unbreakable copies of given items.
 
```java
unbreakable iron sword #Creates unbreakable iron sword
```
<details><summary>Syntaxes</summary><p>
 
```java
unbreakable %itemtypes%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev13b</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Item Type</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### Unix Timestamp
Converts given date to Unix timestamp. This is roughly how many seconds have elapsed since 1 January 1970.
 
```java
unix timestamp of now
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] unix timestamp of %dates%
%dates%'[s] unix timestamp
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev31</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Number</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### Upper/lower Case Text
Copy of given text in upper or lower case.
 
```java
"oops!" in upper case # OOPS!
```
<details><summary>Syntaxes</summary><p>
 
```java
%string% in (upper|lower) case
capitalized %string%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev16</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Text</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### Vectors - Angle between
Gets the angle between two vectors
 
```java
send "%angle between vector 1, 0, 0 and vector 0, 1, 1%"
```
<details><summary>Syntaxes</summary><p>
 
```java
angle between %vector% and %vector%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev28</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>float</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### Vectors - Arithmetic
Arithmetic expressions for vectors
 
```java
set {_v} to vector 1, 2, 3 // 5
set {_v} to {_v} ++ {_v}
set {_v} to {_v} ++ 5
set {_v} to {_v} -- {_v}
set {_v} to {_v} -- 5
set {_v} to {_v} ** {_v}
set {_v} to {_v} ** 5
set {_v} to {_v} // {_v}
set {_v} to {_v} // 5
```
<details><summary>Syntaxes</summary><p>
 
```java
%vector%[ ]++[ ]%vector%
%vector%[ ]--[ ]%vector%
%vector%[ ]**[ ]%vector%
%vector%[ ]//[ ]%vector%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev28</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Vector</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### Vectors - Between locations
Creates a vector between two locations
 
```java
set {_v} to vector between {_loc1} and {_loc2}
```
<details><summary>Syntaxes</summary><p>
 
```java
vector (from|between) %location% (to|and) %location%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev28</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Vector</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### Vectors - Coordinate
Gets or sets the x, y or z coordinate of a vector
 
```java
set {_v} to vector 1, 2, 3
send "%x of {_v}%, %y of {_v}%, %z of {_v}%"
add 1 to x of {_v}
add 2 to y of {_v}
add 3 to z of {_v}
send "%x of {_v}%, %y of {_v}%, %z of {_v}%"
set x of {_v} to 1
set y of {_v} to 2
set z of {_v} to 3
send "%x of {_v}%, %y of {_v}%, %z of {_v}%"
```
<details><summary>Syntaxes</summary><p>
 
```java
(x|y|z) of %vector%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev28</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Number</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>unknown</td>
</table>
 
---
 
### Vectors - Create from XYZ
Creates a vector from an x, y and z value
 
```java
set {_v} to vector 0, 1, 0
```
<details><summary>Syntaxes</summary><p>
 
```java
[new] vector [(from|at|to)] %number%,[ ]%number%(,[ ]| and )%number%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev28</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Vector</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### Vectors - Create from location
Creates a vector from a location
 
```java
set {_v} to vector of {_loc}
```
<details><summary>Syntaxes</summary><p>
 
```java
vector (of|from|to) %location%
%location%['s] vector
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev28</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Vector</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### Vectors - Create from pitch and yaw
Creates a vector from a yaw and pitch value
 
```java
set {_v} to vector from yaw 45 and pitch 45
```
<details><summary>Syntaxes</summary><p>
 
```java
[new] vector from yaw %number% and pitch %number%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev28</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Vector</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### Vectors - Cross product
Gets the cross product between two vectors
 
```java
send "%vector 1, 0, 0 cross vector 0, 1, 0%"
```
<details><summary>Syntaxes</summary><p>
 
```java
%vector% cross %vector%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev28</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Vector</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### Vectors - Cylindrical shape
Forms a 'cylindrical shaped' vector using yaw to manipulate the current point
 
```java
loop 360 times:
	set {_v} to cylindrical vector radius 1, yaw loop-value, height 2
set {_v} to cylindrical vector radius 1, yaw 90, height 2
```
<details><summary>Syntaxes</summary><p>
 
```java
[new] cylindrical vector [(from|with)] [radius] %number%, [yaw] %number%(,| and) [height] %number%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev28</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Vector</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### Vectors - Dot product
Gets the dot product between two vectors
 
```java
set {_v} to {_v2} dot {_v3}
```
<details><summary>Syntaxes</summary><p>
 
```java
%vector% dot %vector%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev28</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>double</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### Vectors - Length
Gets or sets the length of a vector
 
```java
send "%standard length of vector 1, 2, 3%"
set {_v} to vector 1, 2, 3
set standard length of {_v} to 2
send "%standard length of {_v}%"
```
<details><summary>Syntaxes</summary><p>
 
```java
(vector|standard|normal) length of %vector%
%vector%['s] (vector|standard|normal) length
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev28</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>double</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>add, set and remove</td>
</table>
 
---
 
### Vectors - Location vector offset
Offset a location by a vector
 
```java
set {_loc} to {_loc} ~ {_v}
```
<details><summary>Syntaxes</summary><p>
 
```java
%location%[ ]~[~][ ]%vectors%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev28</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Location</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### Vectors - Normalize
Normalizes a vector
 
```java
set {_v} to {_v} normalized
```
<details><summary>Syntaxes</summary><p>
 
```java
normalize %vector%
%vector% normalized
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev28</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Vector</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### Vectors - Random
Creates a random vector
 
```java
set {_v} to random vector
```
<details><summary>Syntaxes</summary><p>
 
```java
random vector
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev28</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Vector</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### Vectors - Spherical shape
Forms a 'spherical shaped' vector using yaw and pitch to manipulate the current point
 
```java
loop 360 times:
	set {_v} to spherical vector radius 1, yaw loop-value, pitch loop-value
set {_v} to spherical vector radius 1, yaw 45, pitch 90
```
<details><summary>Syntaxes</summary><p>
 
```java
[new] spherical vector [(from|with)] [radius] %number%, [yaw] %number%(,| and) [pitch] %number%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev28</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Vector</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### Vectors - Squared length
Gets the squared length of a vector
 
```java
send "%squared length of vector 1, 2, 3%"
```
<details><summary>Syntaxes</summary><p>
 
```java
squared length of %vector%
%vector%['s] squared length
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev28</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>double</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### Vectors - Velocity
Gets, sets, adds or removes velocity to/from/of an entity
 
```java
set player's velocity to {_v}
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] velocity of %entities%
%entities%'[s] velocity
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev31</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Vector</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>add, set, remove and delete</td>
</table>
 
---
 
### Vectors - Yaw and pitch
Gets or sets the yaw or pitch value of a vector
 
```java
set {_v} to vector -1, 1, 1
send "%vector yaw of {_v}%, %vector pitch of {_v}%"
add 45 to vector yaw of {_v}
subtract 45 from vector pitch of {_v}
send "%vector yaw of {_v}%, %vector pitch of {_v}%"
set vector yaw of {_v} to -45
set vector pitch of {_v} to 45
send "%vector yaw of {_v}%, %vector pitch of {_v}%"
```
<details><summary>Syntaxes</summary><p>
 
```java
vector (yaw|pitch) of %vector%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev28</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Number</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>unknown</td>
</table>
 
---
 
### Vehicle
The vehicle an entity is in, if any. This can actually be any entity, e.g. spider jockeys are skeletons that ride on a spider, so the spider is the 'vehicle' of the skeleton.
See also: passenger
 
```java
vehicle of the player is a minecart
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] vehicle[s] of %entities%
%entities%'[s] vehicle[s]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Entity</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>add, set, remove and remove all</td>
</table>
 
---
 
### Version
The version of Bukkit, Minecraft or Skript respectively.
 
```java
message "This server is running Minecraft %minecraft version% on Bukkit %bukkit version%"
message "This server is powered by Skript %skript version%"
```
<details><summary>Syntaxes</summary><p>
 
```java
([craft]bukkit|minecraft|skript)( |-)version
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Text</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### Weather
The weather in the given or the current world.
 
```java
set weather to clear
weather in "world" is rainy
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] weather [(in|of) %worlds%]
%worlds%'[s] weather
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Weather Type</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>set and delete</td>
</table>
 
---
 
### World
The world the event occurred in.
 
```java
world is "world_nether"
teleport the player to the world's spawn
set the weather in the player's world to rain
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] world [of %locations/entities%]
%locations/entities%'[s] world
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>World</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>set</td>
</table>
 
---
 
### World Seed
The seed of given world. Note that it will be returned as Minecraft internally treats seeds, not as you specified it in world configuration.
 
```java
broadcast "Seed: %seed of player's world%"
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] seed[s] (from|of) %worlds%
%worlds%'[s] seed[s]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev35</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>long</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### Worlds
All worlds of the server, useful for looping.
 
```java
loop all worlds:
	broadcast "You're in %loop-world%" to loop-world
```
<details><summary>Syntaxes</summary><p>
 
```java
[(all [[of] the]|the)] worlds
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>World</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### X of Item
An expression to be able to use a certain amount of items where the amount can be any expression. Please note that is expression is not stable and might be replaced in the future.
 
```java
give level of player of pickaxes to the player
```
<details><summary>Syntaxes</summary><p>
 
```java
%number% of %itemstacks/entitytype%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.2</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Object</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>unknown</td>
</table>
 
---
 
### Yaw / Pitch
The yaw or pitch of a location. You likely won't need this expression ever if you don't know what this means.
 
```java
log "%player%: %location of player%, %player's yaw%, %player's pitch%" to "playerlocs.log"
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] (yaw|pitch) of %locations%
%locations%'[s] (yaw|pitch)
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Number</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>add, set and remove</td>
</table>
## Types
 
### Biome
All possible biomes Minecraft uses to generate a world.
 
```java
biome at the player is desert
```
<table>
  <tr>
    <th>Pattern</th>
    <td>biome[s]<br>
    </td>
  </tr>
  <tr>
    <th>Usage</th>
    <td>Biome names; you can use F3 ingame<br>
    </td>
  </tr>
</table>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.4.4</td>
</table>
 
---
 
### Block
A block in a world. It has a location and a type, and can also have a direction (mostly a facing), an inventory, or other special properties.
 
**No examples available yet.**
<table>
  <tr>
    <th>Pattern</th>
    <td>block[s]<br>
    </td>
  </tr>
  </tr>
</table>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### Boolean
A boolean is a value that is either true or false. Other accepted names are 'on' and 'yes' for true, and 'off' and 'no' for false.
 
```java
set {config.%player%.use mod} to false
```
<table>
  <tr>
    <th>Pattern</th>
    <td>boolean[s]<br>
    </td>
  </tr>
  <tr>
    <th>Usage</th>
    <td>true/yes/on or false/no/off<br>
    </td>
  </tr>
</table>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### Chunk
A chunk is a cuboid of 16×16×128 (x×z×y) blocks. Chunks are spread on a fixed rectangular grid in their world.
 
**No examples available yet.**
<table>
  <tr>
    <th>Pattern</th>
    <td>chunk[s]<br>
    </td>
  </tr>
  </tr>
</table>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.0</td>
</table>
 
---
 
### Click Type
Click type, mostly for inventory events. Tells exactly which keys/buttons player pressed, assuming that default keybindings are used in client side.
 
**No examples available yet.**
<table>
  <tr>
    <th>Pattern</th>
    <td>click type[s]<br>
    </td>
  </tr>
  <tr>
    <th>Usage</th>
    <td>left mouse button, left mouse button with shift, right mouse button, right mouse button with shift, window border using right mouse button, window border using left mouse button, middle mouse button, number key, double click using mouse, drop key, drop key with control, creative action, unknown<br>
    </td>
  </tr>
</table>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev16b, 2.2-dev35 (renamed to click type)</td>
</table>
 
---
 
### Colour
Wool, dye and chat colours.
 
```java
color of the sheep is red or black
set the colour of the block to green
message "You're holding a <%color of tool%>%color of tool%<reset> wool block"
```
<table>
  <tr>
    <th>Pattern</th>
    <td>colo[u]r[s]<br>
    </td>
  </tr>
  <tr>
    <th>Usage</th>
    <td>black, dark grey/dark gray, grey/light grey/gray/light gray/silver, white, blue/dark blue, cyan/aqua/dark cyan/dark aqua, light blue/light cyan/light aqua, green/dark green, light green/lime/lime green, yellow/light yellow, orange/gold/dark yellow, red/dark red, pink/light red, purple/dark purple, magenta/light purple, brown/indigo<br>
    </td>
  </tr>
</table>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### Command Sender
A player or the console.
 
```java
on command /pm:
	command sender is not the console
	chance of 10%
	give coal to the player
	message "You got a piece of coal for sending that PM!"
```
<table>
  <tr>
    <th>Pattern</th>
    <td>[command[s]][ ](sender|executor)[s]<br>
    </td>
  </tr>
  <tr>
    <th>Usage</th>
    <td>use the console for the console<br>
        see player for players.<br>
    </td>
  </tr>
</table>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### Damage Cause
The cause/type of a damage event, e.g. lava, fall, fire, drowning, explosion, poison, etc.
Please note that support for this type is very rudimentary, e.g. lava, fire and burning, as well as projectile and attack are considered different types.
 
**No examples available yet.**
<table>
  <tr>
    <th>Pattern</th>
    <td>damage cause[s]<br>
    </td>
  </tr>
  <tr>
    <th>Usage</th>
    <td>contact, attack, sweep attack, projectile, suffocation, fall, fire, burning, melting, lava, drowning, block explosion, entity explosion, void, lightning, suicide, starvation, poison, potion, wither, falling block, thorns, dragon's breath, unknown, hitting wall while flying, magma, cramming<br>
    </td>
  </tr>
</table>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.0</td>
</table>
 
---
 
### Date
A date is a certain point in the real world's time which can currently only be obtained with now.
See time and timespan for the other time types of Skript.
 
```java
set {_yesterday} to now
subtract a day from {_yesterday}
# now {_yesterday} represents the date 24 hours before now
```
<table>
  <tr>
    <th>Pattern</th>
    <td>date[s]<br>
    </td>
  </tr>
  </tr>
</table>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.4</td>
</table>
 
---
 
### Direction
A direction, e.g. north, east, behind, 5 south east, 1.3 meters to the right, etc.
Locations and some blocks also have a direction, but without a length.
Please note that directions have changed extensively in the betas and might not work perfectly. They can also not be used as command arguments.
 
```java
set the block below the victim to a chest
loop blocks from the block infront of the player to the block 10 below the player:
	set the block behind the loop-block to water
```
<table>
  <tr>
    <th>Pattern</th>
    <td>direction[s]<br>
    </td>
  </tr>
  <tr>
    <th>Usage</th>
    <td>see direction (expression)<br>
    </td>
  </tr>
</table>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.0</td>
</table>
 
---
 
### Enchantment
An enchantment, e.g. 'sharpness' or 'furtune'. Unlike enchantment type this type has no level, but you usually don't need to use this type anyway.
 
**No examples available yet.**
<table>
  <tr>
    <th>Pattern</th>
    <td>enchantment[s]<br>
    </td>
  </tr>
  <tr>
    <th>Usage</th>
    <td>Protection, Fire Protection, Feather Falling, Blast Protection, Projectile Protection, Respiration, Aqua Affinity, Mending, Thorns, Curse of Vanishing, Depth Strider, Frost Walker, Curse of Binding, Sharpness, Smite, Bane of Arthropods, Knockback, Fire Aspect, Looting, Sweeping Edge, Efficiency, Silk Touch, Unbreaking, Fortune, Power, Punch, Flame, Infinity, Luck of the Sea, Lure<br>
    </td>
  </tr>
</table>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.4.6</td>
</table>
 
---
 
### Enchantment Type
An enchantment with an optional level, e.g. 'sharpness 2' or 'fortune'.
 
```java
enchant the player's tool with sharpness 5
helmet is enchanted with waterbreathing
```
<table>
  <tr>
    <th>Pattern</th>
    <td>enchant(ing|ment) type[s]<br>
    </td>
  </tr>
  <tr>
    <th>Usage</th>
    <td>&lt;enchantment&gt; [&lt;level&gt;]<br>
    </td>
  </tr>
</table>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.4.6</td>
</table>
 
---
 
### Entity
An entity is something in a world that's not a block, e.g. a player, a skeleton, or a zombie, but also projectiles like arrows, fireballs or thrown potions, or special entities like dropped items, falling blocks or paintings.
 
```java
entity is a zombie or creeper
player is an op
projectile is an arrow
shoot a fireball from the player
```
<table>
  <tr>
    <th>Pattern</th>
    <td>entit(y|ies)<br>
    </td>
  </tr>
  <tr>
    <th>Usage</th>
    <td>player, op, wolf, tamed ocelot, powered creeper, zombie, unsaddled pig, fireball, arrow, dropped item, item frame, etc.<br>
    </td>
  </tr>
</table>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### Entity Type
The type of an entity, e.g. player, wolf, powered creeper, etc.
 
```java
victim is a cow
spawn a creeper
```
<table>
  <tr>
    <th>Pattern</th>
    <td>entity[ ]type[s]<br>
    </td>
  </tr>
  <tr>
    <th>Usage</th>
    <td>Detailed usage will be added eventually<br>
    </td>
  </tr>
</table>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.3</td>
</table>
 
---
 
### Game Mode
The game modes survival, creative and adventure.
 
```java
player's gamemode is survival
set the player argument's game mode to creative
```
<table>
  <tr>
    <th>Pattern</th>
    <td>game[ ]mode[s]<br>
    </td>
  </tr>
  <tr>
    <th>Usage</th>
    <td>creative/survival/adventure<br>
    </td>
  </tr>
</table>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### Inventory
An inventory of a player or block. Inventories have many effects and conditions regarding the items contained.
An inventory has a fixed amount of slots which represent a specific place in the inventory, e.g. the helmet slot for players (Please note that slot support is still very limited but will be improved eventually).
 
**No examples available yet.**
<table>
  <tr>
    <th>Pattern</th>
    <td>inventor(y|ies)<br>
    </td>
  </tr>
  </tr>
</table>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### Inventory Action
What player just did in inventory event. Note that when in creative game mode, most actions do not work correctly.
 
**No examples available yet.**
<table>
  <tr>
    <th>Pattern</th>
    <td>inventory action[s]<br>
    </td>
  </tr>
  <tr>
    <th>Usage</th>
    <td>nothing, pickup all, pickup some, pickup half, pickup one item, place all, place some, place one, swap with cursor, drop all from cursor, drop one from cursor, drop all from slot, drop one from slot, instant move, hotbar move and readd, swap with hotbar, clone stack, collect to cursor, unknown<br>
    </td>
  </tr>
</table>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev16</td>
</table>
 
---
 
### Inventory Slot
Represents a single slot of an inventory. Notable slots are the armour slots and furnace slots. 
The most important property that distinguishes a slot from an item is its ability to be changed, e.g. it can be set, deleted, enchanted, etc. (Some item expressions can be changed as well, e.g. items stored in variables. For that matter: slots are never saved to variables, only the items they represent at the time when the variable is set).
Please note that tool can be regarded a slot, but it can actually change it's position, i.e. doesn't represent always the same slot.
 
```java
set tool of player to dirt
delete helmet of the victim
set the colour of the player's tool to green
enchant the player's chestplate with projectile protection 5
```
<table>
  <tr>
    <th>Pattern</th>
    <td>[inventory ]slot[s]<br>
    </td>
  </tr>
  </tr>
</table>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### Inventory Type
Minecraft has several different inventory types with their own use cases.
 
**No examples available yet.**
<table>
  <tr>
    <th>Pattern</th>
    <td>inventory type[s]<br>
    </td>
  </tr>
  <tr>
    <th>Usage</th>
    <td>chest inventory, dispenser inventory, dropper inventory, furnace inventory, workbench inventory, crafting table inventory, enchanting table inventory, brewing stand inventory, player inventory, creative inventory, merchant inventory, ender chest inventory, anvil inventory, beacon inventory, hopper inventory, shulker box inventory<br>
    </td>
  </tr>
</table>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev32</td>
</table>
 
---
 
### Item / Material
An item, e.g. a stack of torches, a furnace, or a wooden sword of sharpness 2. Unlike item type an item can only represent exactly one item (e.g. an upside-down cobblestone stair facing west), while an item type can represent a whole range of items (e.g. any cobble stone stairs regardless of direction).
You don't usually need this type except when you want to make a command that only accepts an exact item.
Please note that currently 'material' is exactly the same as 'item', i.e. can have an amount & enchantments.
 
```java
set {_item} to type of the targeted block
{_item} is a torch
```
<table>
  <tr>
    <th>Pattern</th>
    <td>item<br>
        material<br>
    </td>
  </tr>
  <tr>
    <th>Usage</th>
    <td>[&lt;number&gt; [of]] &lt;alias&gt; [of &lt;enchantment&gt; &lt;level&gt;], Where &lt;alias&gt; must be an alias that represents exactly one item (i.e cannot be a general alias like 'sword' or 'plant')<br>
    </td>
  </tr>
</table>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### Item Type
An item type is an alias, e.g. 'a pickaxe', 'all plants', etc., and can result in different items when added to an inventory, and unlike items they are well suited for checking whether an inventory contains a certain item or whether a certain item is of a certain type.
An item type can also have one or more enchantments with or without a specific level defined, and can optionally start with 'all' or 'every' to make this item type represent all types that the alias represents, including data ranges.
 
```java
give 4 torches to the player
add all slabs to the inventory of the block
player's tool is a diamond sword of sharpness
remove a pickaxes of fortune 4 from {stored items::*}
set {_item} to 10 of every upside-down stair
block is dirt or farmland
```
<table>
  <tr>
    <th>Pattern</th>
    <td>item[ ]type[s]<br>
        items<br>
        materials<br>
    </td>
  </tr>
  <tr>
    <th>Usage</th>
    <td>[&lt;number&gt; [of]] [all/every] &lt;alias&gt; [of &lt;enchantment&gt; [&lt;level&gt;] [,/and &lt;more enchantments...&gt;]]<br>
    </td>
  </tr>
</table>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### Living Entity
A living entity, i.e. a mob or player, not inanimate entities like projectiles or dropped items.
 
```java
spawn 5 powered creepers
shoot a zombie from the creeper
```
<table>
  <tr>
    <th>Pattern</th>
    <td>living[ ]entit(y|ies)<br>
    </td>
  </tr>
  <tr>
    <th>Usage</th>
    <td>see entity, but ignore inanimate objects<br>
    </td>
  </tr>
</table>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### Location
A location in a world. Locations are world-specific and even store a direction, e.g. if you save a location and later teleport to it you will face the exact same direction you did when you saved the location.
 
**No examples available yet.**
<table>
  <tr>
    <th>Pattern</th>
    <td>location[s]<br>
    </td>
  </tr>
  </tr>
</table>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### Metadata Holder
Something that can hold metadata (e.g. an entity or block)
 
```java
set metadata value "super cool" of player to true
```
<table>
  <tr>
    <th>Pattern</th>
    <td>metadata holder[s]<br>
    </td>
  </tr>
  </tr>
</table>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev36</td>
</table>
 
---
 
### Number
A number, e.g. 2.5, 3, or -9812454.
Please note that many expressions only need integers, i.e. will discard any frational parts of any numbers without producing an error.
 
```java
set the player's health to 5.5
set {_temp} to 2*{_temp} - 2.5
```
<table>
  <tr>
    <th>Pattern</th>
    <td>num[ber][s]<br>
    </td>
  </tr>
  <tr>
    <th>Usage</th>
    <td>[-]###[.###]</code> (any amount of digits; very large numbers will be truncated though)<br>
    </td>
  </tr>
</table>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### Object
The supertype of all types, meaning that if %object% is used in e.g. a condition it will accept all kinds of expressions.
 
**No examples available yet.**
<table>
  <tr>
    <th>Pattern</th>
    <td>object[s]<br>
    </td>
  </tr>
  </tr>
</table>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### Offlineplayer
A player that is possibly offline. See player for more information. Please note that while all effects and conditions that require a player can be used with an offline player as well, they will not work if the player is not actually online.
 
**No examples available yet.**
<table>
  <tr>
    <th>Pattern</th>
    <td>offline[ ]player[s]<br>
    </td>
  </tr>
  </tr>
</table>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### Player
A player. Depending on whether a player is online or offline several actions can be performed with them, though you won't get any errors when using effects that only work if the player is online (e.g. changing his inventory) on an offline player.
You have two possibilities to use players as command arguments: &lt;player&gt; and &lt;offline player&gt;. The first requires that the player is online and also accepts only part of the name, while the latter doesn't require that the player is online, but the player's name has to be entered exactly.
 
**No examples available yet.**
<table>
  <tr>
    <th>Pattern</th>
    <td>player[s]<br>
    </td>
  </tr>
  </tr>
</table>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### Potion Effect Type
A potion effect type, e.g. 'strength' or 'swiftness'.
 
```java
apply swiftness 5 to the player
apply potion of speed 2 to the player for 60 seconds
remove invisibility from the victim
```
<table>
  <tr>
    <th>Pattern</th>
    <td>potion[[ ]effect][[ ]type][s]<br>
    </td>
  </tr>
  <tr>
    <th>Usage</th>
    <td>null, speed, slowness, haste, mining fatigue, strength, instant health, instant damage, jump boost, nausea, regeneration, resistance, fire resistance, water breathing, invisibility, blindness, night vision, hunger, weakness, poison, wither, health boost, absorption, saturation, glowing, levitation, luck, bad luck<br>
    </td>
  </tr>
</table>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### Projectile
A projectile, e.g. an arrow, snowball or thrown potion.
 
```java
projectile is a snowball
shoot an arrow at speed 5 from the player
```
<table>
  <tr>
    <th>Pattern</th>
    <td>projectile[s]<br>
    </td>
  </tr>
  <tr>
    <th>Usage</th>
    <td>arrow, fireball, snowball, thrown potion, etc.<br>
    </td>
  </tr>
</table>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### Text
Text is simply text, i.e. a sequence of characters, which can optionally contain expressions which will be replaced with a meaningful representation (e.g. %player% will be replaced with the player's name).
Because scripts are also text, you have to put text into double quotes to tell Skript which part of the line is an effect/expression and which part is the text.
Please read the article on Texts and Variable Names to learn more.
 
```java
broadcast "Hello World!"
message "Hello %player%"
message "The id of ""%type of tool%"" is %id of tool%."
```
<table>
  <tr>
    <th>Pattern</th>
    <td>(text|string)[s]<br>
    </td>
  </tr>
  <tr>
    <th>Usage</th>
    <td>simple: "..."<br>
        quotes: "...""..."<br>
        expressions: "...%expression%..."<br>
        percent signs: "...%%..."<br>
    </td>
  </tr>
</table>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### Time
A time is a point in a minecraft day's time (i.e. ranges from 0:00 to 23:59), which can vary per world.
See date and timespan for the other time types of Skript.
 
```java
at 20:00:
	time is 8 pm
	broadcast "It's %time%"
```
<table>
  <tr>
    <th>Pattern</th>
    <td>time[s]<br>
    </td>
  </tr>
  <tr>
    <th>Usage</th>
    <td>##:##<br>
        ##[:##][ ]am/pm<br>
    </td>
  </tr>
</table>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### Timeperiod
A period of time between two times. Mostly useful since you can use this to test for whether it's day, night, dusk or dawn in a specific world.
This type might be removed in the future as you can use 'time of world is between x and y' as a replacement.
 
```java
time in world is night
```
<table>
  <tr>
    <th>Pattern</th>
    <td>time[ ]period[s]<br>
        duration[s]<br>
    </td>
  </tr>
  <tr>
    <th>Usage</th>
    <td>##:## - ##:##<br>
        dusk/day/dawn/night<br>
    </td>
  </tr>
</table>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### Timespan
A timespan is a difference of two different dates or times, e.g '10 minutes'. Timespans are always displayed as real life time, but can be defined as minecraft time, e.g. '5 minecraft days and 12 hours'.
See date and time for the other time types of Skript.
 
```java
every 5 minecraft days:
	wait a minecraft second and 5 ticks
every 10 mc days and 12 hours:
	halt for 12.7 irl minutes, 12 hours and 120.5 seconds
```
<table>
  <tr>
    <th>Pattern</th>
    <td>time[ ]span[s]<br>
    </td>
  </tr>
  <tr>
    <th>Usage</th>
    <td>&lt;number&gt; [minecraft/mc/real/rl/irl] ticks/seconds/minutes/hours/days [[,/and] &lt;more...&gt;]<br>
        [###:]##:##[.####] ([hours:]minutes:seconds[.milliseconds])<br>
    </td>
  </tr>
</table>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### Tree Type
A tree type represents a tree species or a huge mushroom species. These can be generated in a world with the generate tree effect.
 
```java
grow any regular tree at the block
grow a huge red mushroom above the block
```
<table>
  <tr>
    <th>Pattern</th>
    <td>tree[ ]type[s]<br>
        tree[s]<br>
    </td>
  </tr>
  <tr>
    <th>Usage</th>
    <td>[any] &lt;general tree/mushroom type&gt;, e.g. tree/any jungle tree/etc.<br>
        &lt;specific tree/mushroom species&gt;, e.g. red mushroom/small jungle tree/big regular tree/etc.<br>
    </td>
  </tr>
</table>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### Type
Represents a type, e.g. number, object, item type, location, block, world, entity type, etc.
This is mostly used for expressions like 'event-&lt;type&gt;', '&lt;type&gt;-argument', 'loop-&lt;type&gt;', etc., e.g. event-world, number-argument and loop-player.
 
```java
{variable} is a number # check whether the variable contains a number, e.g. -1 or 5.5
{variable} is a type # check whether the variable contains a type, e.g. number or player
{variable} is an object # will always succeed if the variable is set as everything is an object, even types.
disable PvP in the event-world
kill the loop-entity
```
<table>
  <tr>
    <th>Pattern</th>
    <td>type[s]<br>
    </td>
  </tr>
  <tr>
    <th>Usage</th>
    <td>See the type name patterns of all types - including this one<br>
    </td>
  </tr>
</table>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.0</td>
</table>
 
---
 
### Vector
Vector is a collection of numbers. In Minecraft, 3D vectors are used to express velocities of entities.
 
**No examples available yet.**
<table>
  <tr>
    <th>Pattern</th>
    <td>vector[s]<br>
    </td>
  </tr>
  <tr>
    <th>Usage</th>
    <td>vector(x, y, z)<br>
    </td>
  </tr>
</table>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev23</td>
</table>
 
---
 
### Visual Effect
A visible effect, e.g. particles.
 
```java
show wolf hearts on the clicked wolf
play mob spawner flames at the targeted block to the player
```
<table>
  <tr>
    <th>Pattern</th>
    <td>(visual|particle) effect[s]<br>
    </td>
  </tr>
  <tr>
    <th>Usage</th>
    <td>ender signal, mobspawner flames, potion break, smoke, hurt, sheep eating, wolf hearts, wolf shaking, wolf smoke, firework's spark, critical hit, magical critical hit, potion swirl, transparent potion swirl, spell, spell, witch spell, note, portal, flying glyph, flame, lava pop, footstep, water splash, smoke particle, huge explosion, large explosion, explosion, void fog, small smoke, cloud, coloured dust, snowball break, water drip, lava drip, snow shovel, slime, heart, angry villager, happy villager, large smoke, item crack, block break, block dust, totem, spit<br>
    </td>
  </tr>
</table>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.1</td>
</table>
 
---
 
### Weather Type
The weather types sunny, rainy, and thundering.
 
```java
is raining
is sunny in the player's world
message "It is %weather in the argument's world% in %world of the argument%"
```
<table>
  <tr>
    <th>Pattern</th>
    <td>weather[ ]type[s]<br>
        weather condition[s]<br>
        weather[s]<br>
    </td>
  </tr>
  <tr>
    <th>Usage</th>
    <td>clear/sun/sunny, rain/rainy/raining, and thunder/thundering/thunderstorm<br>
    </td>
  </tr>
</table>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### World
One of the server's worlds. Worlds can be put into scripts by surrounding their name with double quotes, e.g. "world_nether", but this might not work reliably as text uses the same syntax.
 
```java
broadcast "Hello!" to the world "world_nether"
```
<table>
  <tr>
    <th>Pattern</th>
    <td>world[s]<br>
    </td>
  </tr>
  <tr>
    <th>Usage</th>
    <td>"world_name", e.g. "world"<br>
    </td>
  </tr>
</table>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0, 2.2 (alternate syntax)</td>
</table>
## Functions
 
### abs
Returns the absolute value of the argument, i.e. makes the argument positive.
 
```java
abs(3) = 3
abs(-2) = 2
```
<details><summary>Syntaxes</summary><p>
 
```java
abs(n: number)
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Number</td>
</table>
 
---
 
### acos
The inverse of the cosine, also called arccos. Returns result in degrees, not radians. Only returns values from 0 to 180.
 
```java
acos(0) = 90
acos(1) = 0
acos(0.5) = 30
```
<details><summary>Syntaxes</summary><p>
 
```java
acos(n: number)
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Number</td>
</table>
 
---
 
### asin
The inverse of the sine, also called arcsin. Returns result in degrees, not radians. Only returns values from -90 to 90.
 
```java
asin(0) = 0
asin(1) = 90
asin(0.5) = 30
```
<details><summary>Syntaxes</summary><p>
 
```java
asin(n: number)
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Number</td>
</table>
 
---
 
### atan
The inverse of the tangent, also called arctan. Returns result in degrees, not radians. Only returns values from -90 to 90.
 
```java
atan(0) = 0
atan(1) = 45
atan(10000) = 89.9943
```
<details><summary>Syntaxes</summary><p>
 
```java
atan(n: number)
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Number</td>
</table>
 
---
 
### atan2
Similar to atan, but requires two coordinates and returns values from -180 to 180.
The returned angle is measured counterclockwise in a standard mathematical coordinate system (x to the right, y to the top).
 
```java
atan2(0, 1) = 0
atan2(10, 0) = 90
atan2(-10, 5) = -63.4349
```
<details><summary>Syntaxes</summary><p>
 
```java
atan2(x: number, y: number)
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Number</td>
</table>
 
---
 
### calcExperience
Calculates experience needed to achieve given level in Minecraft.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
calcExperience(level: long)
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev32</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>long</td>
</table>
 
---
 
### ceil
Rounds a number up, i.e. returns the closest integer larger than or equal to the argument.
 
```java
ceil(2.34) = 3
ceil(2) = 2
ceil(2.99) = 3
```
<details><summary>Syntaxes</summary><p>
 
```java
ceil(n: number)
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>long</td>
</table>
 
---
 
### ceiling
Alias of ceil.
 
```java
ceiling(2.34) = 3
ceiling(2) = 2
ceiling(2.99) = 3
```
<details><summary>Syntaxes</summary><p>
 
```java
ceiling(n: number)
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>long</td>
</table>
 
---
 
### cos
The cosine function. This is basically the sine shifted by 90°, i.e. cos(a) = sin(a + 90°), for any number a. Uses degrees, not radians.
 
```java
cos(0) = 1
cos(90) = 0
```
<details><summary>Syntaxes</summary><p>
 
```java
cos(n: number)
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Number</td>
</table>
 
---
 
### date
Creates a date from a year, month, and day, and optionally also from hour, minute, second and millisecond.
A time zone and DST offset can be specified as well (in minutes), if they are left out the server's time zone and DST offset are used (the created date will not retain this information).
 
```java
date(2014, 10, 1) # 0:00, 1st October 2014
date(1990, 3, 5, 14, 30) # 14:30, 5th May 1990
date(1999, 12, 31, 23, 59, 59, 999, -3*60, 0) # almost year 2000 in parts of Brazil (-3 hours offset, no DST)
```
<details><summary>Syntaxes</summary><p>
 
```java
date(year: number, month: number, day: number, hour: number = [[integer:0]], minute: number = [[integer:0]], second: number = [[integer:0]], millisecond: number = [[integer:0]], zone_offset: number = [[double:NaN]], dst_offset: number = [[double:NaN]])
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Date</td>
</table>
 
---
 
### exp
The exponential function. You probably don't need this if you don't know what this is.
 
```java
exp(0) = 1
exp(1) = 2.7183
```
<details><summary>Syntaxes</summary><p>
 
```java
exp(n: number)
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Number</td>
</table>
 
---
 
### floor
Rounds a number down, i.e. returns the closest integer smaller than or equal to the argument.
 
```java
floor(2.34) = 2
floor(2) = 2
floor(2.99) = 2
```
<details><summary>Syntaxes</summary><p>
 
```java
floor(n: number)
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>long</td>
</table>
 
---
 
### ln
The natural logarithm. You probably don't need this if you don't know what this is.
Returns NaN (not a number) if the argument is negative.
 
```java
ln(1) = 0
ln(exp(5)) = 5
ln(2) = 0.6931
```
<details><summary>Syntaxes</summary><p>
 
```java
ln(n: number)
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Number</td>
</table>
 
---
 
### location
Creates a location from a world and 3 coordinates, with an optional yaw and pitch.
 
```java
location(0, 128, 0)
location(player's x-coordinate, player's y-coordinate + 5, player's z-coordinate, player's world, 0, 90)
```
<details><summary>Syntaxes</summary><p>
 
```java
location(x: number, y: number, z: number, world: world = event-world, yaw: number = [[integer:0]], pitch: number = [[integer:0]])
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Location</td>
</table>
 
---
 
### log
A logarithm, with base 10 if none is specified. This is the inverse operation to exponentiation (for positive bases only), i.e. log(base ^ exponent, base) = exponent for any positive number 'base' and any number 'exponent'.
Another useful equation is base ^ log(a, base) = a for any numbers 'base' and 'a'.
Please note that due to how numbers are represented in computers, these equations do not hold for all numbers, as the computed values may slightly differ from the correct value.
Returns NaN (not a number) if any of the arguments are negative.
 
```java
log(100) = 2 # 10^2 = 100
log(16, 2) = 4 # 2^4 = 16
```
<details><summary>Syntaxes</summary><p>
 
```java
log(n: number, base: number = [[integer:10]])
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Number</td>
</table>
 
---
 
### max
Returns the maximum number from a list of numbers.
 
```java
max(1) = 1
max(1, 2, 3, 4) = 4
max({some list variable::*})
```
<details><summary>Syntaxes</summary><p>
 
```java
max(ns: numbers)
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Number</td>
</table>
 
---
 
### min
Returns the minimum number from a list of numbers.
 
```java
min(1) = 1
min(1, 2, 3, 4) = 1
min({some list variable::*})
```
<details><summary>Syntaxes</summary><p>
 
```java
min(ns: numbers)
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Number</td>
</table>
 
---
 
### mod
Returns the modulo of the given arguments, i.e. the remainder of the division d/m, where d and m are the arguments of this function.
The returned value is always positive. Returns NaN (not a number) if the second argument is zero.
 
```java
mod(3, 2) = 1
mod(256436, 100) = 36
mod(-1, 10) = 9
```
<details><summary>Syntaxes</summary><p>
 
```java
mod(d: number, m: number)
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Number</td>
</table>
 
---
 
### product
Calculates the product of a list of numbers.
 
```java
product(1) = 1
product(2, 3, 4) = 24
product({some list variable::*})
product(2, {_v::*}, and the player's y-coordinate)
```
<details><summary>Syntaxes</summary><p>
 
```java
product(ns: numbers)
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Number</td>
</table>
 
---
 
### round
Rounds a number, i.e. returns the closest integer to the argument.
 
```java
round(2.34) = 2
round(2) = 2
round(2.99) = 3
round(2.5) = 3
```
<details><summary>Syntaxes</summary><p>
 
```java
round(n: number)
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>long</td>
</table>
 
---
 
### sin
The sine function. It starts at 0° with a value of 0, goes to 1 at 90°, back to 0 at 180°, to -1 at 270° and then repeats every 360°. Uses degrees, not radians.
 
```java
sin(90) = 1
sin(60) = 0.866
```
<details><summary>Syntaxes</summary><p>
 
```java
sin(n: number)
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Number</td>
</table>
 
---
 
### sqrt
The square root, which is the inverse operation to squaring a number (for positive numbers only). This is the same as (argument) ^ (1/2) – other roots can be calculated via number ^ (1/root), e.g. set {_l} to {_volume}^(1/3).
Returns NaN (not a number) if the argument is negative.
 
```java
sqrt(4) = 2
sqrt(2) = 1.4142
sqrt(-1) = NaN
```
<details><summary>Syntaxes</summary><p>
 
```java
sqrt(n: number)
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Number</td>
</table>
 
---
 
### sum
Sums a list of numbers.
 
```java
sum(1) = 1
sum(2, 3, 4) = 9
sum({some list variable::*})
sum(2, {_v::*}, and the player's y-coordinate)
```
<details><summary>Syntaxes</summary><p>
 
```java
sum(ns: numbers)
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Number</td>
</table>
 
---
 
### tan
The tangent function. This is basically <a href='#sin'>sin(arg)/cos(arg)</code>. Uses degrees, not radians.
 
```java
tan(0) = 0
tan(45) = 1
tan(89.99) = 5729.5779
```
<details><summary>Syntaxes</summary><p>
 
```java
tan(n: number)
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Number</td>
</table>
 
---
 
### vector
Creates a new vector, which can be used with various expressions, effects and functions.
 
```java
vector(0, 0, 0)
```
<details><summary>Syntaxes</summary><p>
 
```java
vector(x: number, y: number, z: number)
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2-dev23</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Vector</td>
</table>
 
---
 
### world
Gets a world from its name.
 
```java
set {_nether} to world("%{_world}%_nether")
```
<details><summary>Syntaxes</summary><p>
 
```java
world(name: string)
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>2.2</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>World</td>
</table>