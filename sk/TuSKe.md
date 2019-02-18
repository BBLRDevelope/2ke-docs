## Summary
  * [Events](#events)
  * [Conditions](#conditions)
  * [Effects](#effects)
  * [Expressions](#expressions)
  * [Types](#types)
 
## Events
 
### On Anvil Combine
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] anvil [item] (combine|merge)
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
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>true</td>
</table>
 
---
 
### On Anvil Rename
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] anvil [item] rename
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-inventory
event-player
event-itemstack
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
 
### On GUI click
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] gui (action|click)
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-inventory
event-player
event-integer
event-itemstack
event-clicktype
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
 
### On Inventory drag
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] inventory drag
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-inventory
event-player
event-itemstack
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
 
### On Inventory move
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] inventory move
```
 
</p></details>
<details><summary>Event values</summary><p>
 
```java
event-player
event-itemstack
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
 
### On Item craft
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] [tuske] prepare item craft
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
  <td>1.0</td>
  <th><div title="It means if you can cancel this event from happening or not."><a href ="http://bensku.github.io/Skript/effects.html#EffCancelEvent">Cancellable</a></div></th>
  <td>false</td>
</table>
 
---
 
### On Item damage
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] [player] item damage
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
 
### On Spawner spawn
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] [mob] spawner spawn
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
## Conditions
 
### CondCanEat
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
%itemtypes% is edible
%itemtypes% is(n't| not) edible
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### CondHasCustom
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
%itemstack% has [a] custom enchantment [%-customenchantment%]
%itemstack% does(n't| not) [have] custom enchantment [%-customenchantment%]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### CondHasGUI
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
%player% has [a] gui
slot %number% of %player% is a gui
%player% does(n't| not) have [a] gui
slot %number% of %player% is(n't| not) [a] gui
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### CondHasGravity
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
%itemtypes% has gravity
%itemtypes% has(n't| not) gravity
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### CondIsAgeable
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
%entities% ((is|are) ageable|can grow up)
%entities% ((is|are)(n't| not) ageable|can(n't| not) grow up)
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### CondIsBlockType
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
%itemtypes% is [a] (solid|transparent|flammable|occluding) block
%itemtypes% is(n't| not) [a] (solid|transparent|flammable|occluding) block
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### CondIsMobType
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
%livingentities% (is|are) [a] (hostile|neutral|passive) [mob]
%livingentities% (is|are)(n't| not) [a] (hostile|neutral|passive) [mob]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### CondIsTameable
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
%entities% (is|are) tameable
%entities% (is|are)(n't| not) tameable
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### CondRegexMatch
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
%strings% [regex] matches %string%
%strings% [regex] does(n't| not) match %string%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
## Effects
 
### Cancel Drops
Cancels the drops of items, experiences or both in death events, where it won't drop the **player** items (like gamerule KeepInventory), or cancel the item drop of break block event (for minecraft 1.12+ only).
 
```java
on death of player:
	cancel the drops #It won't drop the experience and items.
 
on break of diamond ore:
	cancel the drops of items #It won't drop the items only.
```
<details><summary>Syntaxes</summary><p>
 
```java
cancel [the] drops
cancel [the] drops of [e]xp[perience][s]
cancel [the] drops of (inventory|items)
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0, 1.8.1 (block break event)</td>
</table>
 
---
 
### Close GUI
It should be used in {{effects|CreateEditGUI|creating or editting a gui}}, it is just an extra option to run a code before it closes. This is optinal.
 
```java
create new gui with id "Backpack.%player%" with virtual chest:
	run when close:
		saveInventoryItems(player, gui-inventory)
open last gui to player
```
<details><summary>Syntaxes</summary><p>
 
```java
run (when|while) clos(e|ing) [[the] gui]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.7.5</td>
</table>
 
---
 
### Command with Permission
Make the player execute a command with a temporary permission, when the player finishes executing the command, the permission is removed.
 
```java
make all players execute command "example" with permissions "permission.one" and "permission.two"
```
<details><summary>Syntaxes</summary><p>
 
```java
[execute] [the] command %strings% by %players% with perm[ission][s] %strings%
[execute] [the] %players% command %strings% with perm[ission][s] %strings%
(let|make) %players% execute [[the] command] %strings% with perm[ission][s] %strings%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.6.9.7</td>
</table>
 
---
 
### Create a GUI
It creates a new gui with a given id (optional), using a base inventory, and a shape (optional)
For more info, read the [here](https://github.com/Tuke-Nuke/TuSKe/wiki/GUI-Manager)
 
```java
on skript load:
	create a gui with id "LobbySelector" with virtual chest with 4 rows named "&4Lobby Selector":
		make gui slot 2 with diamond sword named "PVP":
			execute player command "/server pvp" #'on skript load' event doesn't have a 'player', but it will recognize it as it does have.
		make gui slot 4 with grass named "SkyBlock":
			execute player command "/server skyblock"
 
command /lobby:
	trigger:
		open gui "LobbySelector" to player
```
<details><summary>Syntaxes</summary><p>
 
```java
create [a] [new] gui [[with id] %-string%] with %inventory% [and shape %-strings%]
(change|edit) %guiinventory%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.7.5</td>
</table>
 
---
 
### EffEjectRecord
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
eject record (of|from|) %block%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffEvaluateFunction
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
evaluate function %strings% [with <.+?>]
evaluate function %strings%(<.+?>)
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffFormatGUI
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
(format|create|make) [a] gui slot [%-numbers%] of %players% with %itemstack% [to [do] nothing]
(format|create|make) [a] gui slot [%-numbers%] of %players% with %itemstack% to close [(using|with) %-string/clicktype% [(button|click|action)]]
(format|create|make) [a] gui slot [%-numbers%] of %players% with %itemstack% to (run|exe[cute]) [(using|with) %-string/clicktype% [(button|click|action)]]
(format|create|make) [a] gui slot [%-numbers%] of %players% with %itemstack% to [close then] (run|exe[cute]) %commandsender% command %string% [(using|with) perm[ission] %-string%][[(,| and)] (using|with) %-string/clicktype% [(button|click|action)]][[(,| and)] (using|with) cursor [item] %-itemstack%]
(format|create|make) [a] gui slot [%-numbers%] of %players% with %itemstack% to [close then] (run|exe[cute]) function <(.+)>([<.*?>])[[(,| and)] (using|with) %-string/clicktype% [(button|click|action)]][[(,| and)] (using|with) cursor [item] %-itemstack%]
(format|create|make) [a] gui slot [%-numbers%] of %players% with %itemstack% to (run|exe[cute]) [gui [click]] event
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffGuiProperties
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
change gui inventory to name %string% and size %number%
change gui shape [of (items|actions)] to %strings%
change gui properties of inventory to name %string% [with %-number% row[s]] and shape [of (items|actions)] to %strings%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffMakeDrop
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
(make|force) %player% drop[s] %itemstack% [from (%-slot%|his inventory)]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffPushBlock
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
move %block% to %direction%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffRegisterEnchantment
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
(register|create) [a] [new] [custom] enchantment with id [name] %string%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffRegisterPermission
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
(register|create) master permission %string%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffRegisterRecipe
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
(create|register) [new] [custom] shaped recipe with (return|result) %itemstack% using [ingredients] %itemstacks% [with shape %-strings%]
(create|register) [new] [custom] shapeless recipe with (return|result) %itemstack% using [ingredients] %itemstacks%
(create|register) [new] [custom] furnace recipe with (return|result) %itemstack% using [source] %itemstack% [[and] with experience %-number%]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffSaveData
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
save [player] data of %player%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffUnformatGUI
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
(unformat|remove|clear|reset) [the] gui slot %numbers% of %players%
(unformat|remove|clear|reset) [all] [the] gui slots of %players%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffUnregisterEnchantment
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
unregister [the] [custom] enchantment %customenchantment%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### Evaluate
This effect will run any Skript effect/condition from a given string or piece of code. The difference between {{effects|EvaluateInputEffect|SkQuery effect}} and this is basically it returns all syntaxes errors instead of send them to the console, It can evaluate a long amount of code and see them easily instead of beeing in one line. 
For example, you can run a effect from a string, from a piece of code (without beeing quoted) or the entiry section of code.
Starting from 1.8, you can disallow some syntaxes when evaluating. Read more about it at config file (`TuSKe/config.yml`).
 
```java
set {_effect} to "send"
evaluate:
	%{_effect}% "This message will be sent to a player."
#Before parsing the code, it will convert all variables
#To string, basically it will interpret the code above as it
#was a whole string: "%{_effect}% ""This message will be sent to a player."""
#where Skript will replace '%{_effect}%' with the variable value and then it will parse
#The code. It is the same concept of Skript Options.
 
evaluate: kill all players #Not really needed for this but just an example
evaluate: "broadcast ""Hi everyone"""
evaluate:
	if true is true:
		give a diamond sword of %{Enchantment}% 1 to all players
evaluate logging in {_errors::*}: this is not a valid effect
if {_errors::*} is set:
	loop {_errors::*}: #If there is something wrong, it will add the errors here
		send loop-value
#It will send a string in Skript default error format:
<Error message>: <wrong expression> (TuSKe/evaluate.sk, line <line of code>, '<whole line>')
'TuSKe/evaluate.sk' is a fictitious file, it doesn't exist.
```
<details><summary>Syntaxes</summary><p>
 
```java
eval[uate][ logging [[the] error[s]] in %-objects%][ with safety]: (%-strings%|<.+?>)
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.7.5, 1.8 (filtering syntaxes)</td>
</table>
 
---
 
### Make GUI
Used to format a gui slot inside of gui creation/editing section
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
(make|format) next gui [slot] (with|to) %itemstack%
(make|format) gui [slot] %strings/numbers% (with|to) %itemstack%
(un(make|format)|remove) next gui [slot]
(un(make|format)|remove) gui [slot] %strings/numbers%
(un(make|format)|remove) all gui [slot]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
## Expressions
 
### All Recipes
Returns all server recipes. You can get the {{expressions|RecipeIngredients|ingredients}} and the {{expressions|RecipeResult|result item}}.
 
```java
command /recipes <integer=1>:
	usage: /recipes <page>
	trigger:
		set {_list::*} to page arg of all recipes with 10 lines
		loop {_list::*}:
			send "Ingredients to create %result item of loop-value%: %ingredients of loop-value%"
```
<details><summary>Syntaxes</summary><p>
 
```java
[all] [registred] (shaped|shapeless|furnace|) recipes
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.6.8, 1.7.5 (recipe type list)</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Recipe</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>remove, delete and reset</td>
</table>
 
---
 
### All commands
Returns a list containing all registered commands or scripts commands only.
 
```java
send "Current amount of script commands: %size of all script commands%
send "Current amount of non script commands: %size of commansd - size of script commands%
send "Total: %size of all commands%"
```
<details><summary>Syntaxes</summary><p>
 
```java
[all] [registered] [script] commands
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.6.9.7</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Text</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### Alphabetical Order
Will return a list of {{types|Objects|objects}} organized in alphabetic order.
 
```java
loop alphabetical order of all players:
	send "%loop-object%"
```
<details><summary>Syntaxes</summary><p>
 
```java
alphabetical order of %objects%
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
  <td>none</td>
</table>
 
---
 
### Command Info
Get informations about a command.
 
```java
if co
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] description of command %string%
command %string%'[s] description
[the] main [command] of command %string%
command %string%'[s] main [command]
[the] permission of command %string%
command %string%'[s] permission
[the] permission message of command %string%
command %string%'[s] permission message
[the] plugin [owner] of command %string%
command %string%'[s] plugin [owner]
[the] usage of command %string%
command %string%'[s] usage
[the] aliases of command %string%
command %string%'[s] aliases
[the] file [location] of command %string%
command %string%'[s] file location
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.6.9.6, 1.6.9.7</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Text</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### ExprAcceptedItems
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
accepted items for %customenchantment%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Text</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>set</td>
</table>
 
---
 
### ExprAllCustomEnchants
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] [all] custom enchantments of %itemstack%
%itemstack%'[s] [all] custom enchantments
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Custom Enchantment</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>add, set, remove, remove all, delete and reset</td>
</table>
 
---
 
### ExprCEConflicts
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
conflicts for %customenchantment%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Custom Enchantment</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>add, set, remove, delete and reset</td>
</table>
 
---
 
### ExprCatType
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] (cat|ocelot) type of %entity%
%entity%'[s] (cat|ocelot) type
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Text</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>set</td>
</table>
 
---
 
### ExprDraggedItem
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[event-][old(-| )]dragged(-| )item
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
  <td>add, set, remove, delete and reset</td>
</table>
 
---
 
### ExprDraggedSlots
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[event-]dragged(-| )(top|bottom)(-| )slots
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
 
### ExprDroppedExp
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] dropped [e]xp[erience] [orb[s]]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Experience</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>add, set, remove, delete and reset</td>
</table>
 
---
 
### ExprDropsOfBlock
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
drops of %block% [(with|using) %-itemstack%]
%block%'[s] drops [(with|using) %-itemstack%]
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
  <td>none</td>
</table>
 
---
 
### ExprEnabled
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
enabled for %customenchantment%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Boolean</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>set</td>
</table>
 
---
 
### ExprEvaluateFunction
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
result of function %string% [with <.+?>]
result of function %string(<.+?>)
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
  <td>none</td>
</table>
 
---
 
### ExprExpOf
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] [total] [e]xp of %player%
%player%'[s] [total] [e]xp
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
  <td>add, set, remove, delete and reset</td>
</table>
 
---
 
### ExprFirstLogin
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] first login of %offlineplayer%
%offlineplayer%'[s] first login
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Date</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### ExprFurnaceRecipeLevel
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] furnace level of %recipe%
%recipe%'[s] furnace level
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Number</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### ExprGUIValue
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
gui-slot
gui-raw-slot
gui-hotbar-slot
gui-inventory
gui-inventory-action
gui-click-(type|action)
gui-cursor[-item]
gui-[(clicked|current)-]item
gui-slot-type
gui-player
gui-players
gui-inventory-name
gui-slot-id
gui
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
  <td>none</td>
</table>
 
---
 
### ExprHighiestBlock
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
highest block at %location%
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
 
### ExprHorseColor
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] horse color of %entity%
%entity%'[s] horse color
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Text</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>set</td>
</table>
 
---
 
### ExprHorseStyle
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] horse style of %entity%
%entity%'[s] horse style
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Text</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>set</td>
</table>
 
---
 
### ExprInventoryMoveInv
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[event-]inventory-(one|two)
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Inventory</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>add, set, remove, remove all and delete</td>
</table>
 
---
 
### ExprInventoryMoveSlot
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[event-]slot-(one|two)
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
 
### ExprItemCustomEnchant
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
%itemstack% with custom enchantment[s] %customenchantments%
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
  <td>none</td>
</table>
 
---
 
### ExprItemDamage
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
item damage
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
  <td>delete</td>
</table>
 
---
 
### ExprItemsOfRecipe
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] [all] ingredients of %recipe%
%recipe%'[s] [all] ingredients
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
  <td>none</td>
</table>
 
---
 
### ExprJukeboxRecord
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] [jukebox] record of %block%
%block%'[s] [jukebox] record
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
  <td>set</td>
</table>
 
---
 
### ExprLanguage
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] (locale|language) of %player%
%player%'[s] (locale|language)
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Text</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### ExprLastAttacker
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] last attacker of %entity%
%entity%'[s] last attacker
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
  <td>none</td>
</table>
 
---
 
### ExprLastColor
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] last color of %string%
%string%'[s] last color
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Text</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### ExprLastDamage
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] last damage of %livingentity%
%livingentity%'[s] last damage
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Number</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### ExprLastDamageCause
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] last damage cause of %livingentity%
%livingentity%'[s] last damage cause
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Damage Cause</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### ExprLastLogin
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] last login of %offlineplayer%
%offlineplayer%'[s] last login
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Date</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### ExprLeatherColor
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] [leather] (red|green|blue) colo[u]r of %-itemstacks/colors%
%-itemstacks/colors%'[s] [leather] (red|green|blue) colo[u]r
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
  <td>add, set and remove</td>
</table>
 
---
 
### ExprLevelOfCustomEnchant
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
level of [custom enchantment] %customenchantment% of %itemstack%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Number</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### ExprListPaged
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
page %number% of %objects% with %number% lines
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
  <td>none</td>
</table>
 
---
 
### ExprLocalNameOf
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] [json] client id of %object%
%object%'[s] [json] client id
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Text</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### ExprLoreName
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] lore name of %customenchantment%
%customenchantment%'[s] lore name
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Text</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>set</td>
</table>
 
---
 
### ExprMaxLevel
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] max level of %customenchantment%
%customenchantment%'[s] max level
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Number</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>add, set, remove, delete and reset</td>
</table>
 
---
 
### ExprRarity
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] rarity of %customenchantment%
%customenchantment%'[s] rarity
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Number</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>add, set, remove, delete and reset</td>
</table>
 
---
 
### ExprRecipeFromItems
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
recipe from ingredients %itemstacks%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Recipe</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### ExprRecipesOf
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] [all] recipes of %itemstack%
%itemstack%'[s] [all] recipes
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Recipe</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### ExprRegexRandom
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
(first|random) string matching [pattern] %regex/string%
random strings matching [pattern] %regex/string%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Text</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### ExprRegexReplace
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
regex replace (all|every|first|) [pattern] %regex/string% with [group[s]] %string% in %string%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Text</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### ExprRegexSplit
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
regex split %string% (with|using) [pattern] %regex/string%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Text</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### ExprResultOfRecipe
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] result item of %itemstacks/recipe%
%itemstacks/recipe%'[s] result item
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
  <td>none</td>
</table>
 
---
 
### ExprShapeOfRecipe
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] shape of %recipe%
%recipe%'[s] shape
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Text</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### ExprVirtualInv
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
virtual <.+?> [inventory] [with size %-number%] [(named|with (name|title)) %-string%]
virtual <.+?> [inventory] [with %-number% row[s]] [(named|with (name|title)) %-string%]
virtual <.+?> [inventory] [(named|with (name|title)) %-string%] with size %-number%
virtual <.+?> [inventory] [(named|with (name|title)) %-string%] with %-number% row[s]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Inventory</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>add, set, remove, remove all and delete</td>
</table>
 
---
 
### Knowledge Book
It returns a knowledge book (1.12+ only) with given recipes.
 
```java
#Make sure you have an updated aliases containing 'knowledge book'.
give knowledge book with all recipes to player
give knowledge book with all recipes of held item to player
```
<details><summary>Syntaxes</summary><p>
 
```java
%itemstack% with [recipes] %recipes%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.8</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Item / Material</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### Knowledge Recipes
It returns a list of recipes of a knowledge book. You can either set, add and remove recipes, and clear/delete them all.
 
```java
set {_recipes::*} to knowledge recipes of held item #The held item must a be knowledge book
add all recipes to knowledges of {_book}
remove recipes of held item from knowledges of {_book}
clear knowledges of held item
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] knowledge(s| recipes) of %itemstack%
%itemstack%'[s] knowledge(s| recipes)
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.8</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Recipe</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>add, set, remove and delete</td>
</table>
 
---
 
### Last GUI/GUI from id
It is used to return the last created gui or a gui from a string id.
 
```java
on skript load:
	create new gui with id "HUB" with virtual chest:
		make gui slot 1 with diamond named "Server 1":
			execute player command "/server server1"
		make gui slot 2 with paper named "Server 2":
			execute player command "/server server2"
 
command /hub [<text>]:
	trigger:
		open gui "HUB" to player
```
<details><summary>Syntaxes</summary><p>
 
```java
last[ly] [created] gui
gui [with id] %string%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.7.5</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>GUI</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>delete</td>
</table>
 
---
 
### Max Durability
Returns the max durability of {{types|ItemStack|item stack}}. i.e. 1561 for diamond sword. You can cancel it.
 
```java
on item damage:
	if durability of event-item is more than (max durability of event-item - item damage):
		send "Your %event-item% is almost breaking!"
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] max durability of %itemstack%
%itemstack%'[s] max durability
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.1</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>integer</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### Offline Player from UUID
It get a player from a UUID. If you have Bensku's fork dev23+, you can just use {{expressions|Parse|parse expression}} using the uuid.
Also, the uuid needs to be from a player that already played on your server, else it will return null value.
 
```java
set {_player} to offline player from "4580682b-ad69-41e5-a979-6b1b3b2cf9c1"
```
<details><summary>Syntaxes</summary><p>
 
```java
offline player from [uuid] %string%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.7.1</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Offlineplayer</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### Online Time
Returns a {{types|Timespan|timespan}} of online time of {{types|Player|player}} or of the server. Only the online time of player can be edited.
 
```java
command /online:
	trigger:
		send "You're online for %online time of player% and the server is online for %online time of server%"
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] online time of %player%
%player%'[s] online time
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0 (player), 1.5.8 (server)</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Timespan</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>add, set, remove, delete and reset</td>
</table>
 
---
 
### Player Data
Returns a {{types|OfflinePlayer|offline player}} as it was a player, which means that you can get some values like money, inventory, enderchest,etc. Maybe all values doesn't work. If you want to change these values, you will have to {{effects|SavePlayerData|save player data}}.
 
```java
command /money <offlineplayer>:
	trigger:
		if arg is not online:
send "%money of player data of arg%"
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] player data of %offlineplayer%
%offlineplayer%'[s] player data
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.1</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Player</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>add, remove and remove all</td>
</table>
 
---
 
### RGB Color
Returns the rgb color of {{types|ItemStack|item stack}} or {{types|Color|color}}. You can set these values only for item stacks, in this case, leather armors.
The RGB color returns a list with 3 numbers and the other expressions returns which one separated.
 
```java
set {_PlayerEquipaments::*} to player's helmet, player's chestplate, player's leggings and player's boots #Must be leather armor
 
set rgb color of {_PlayerEquipaments::*} to rgb of color red
add 1 to red color of {_PlayerEquipaments::*}
remove 1 from green color of {_PlayerEquipaments::*}
set blue color of {_PlayerEquipaments::*} to 30
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] R[ed, ]G[reen and ]B[blue] [colo[u]r[s]] of %-itemstacks/colors%
%-itemstacks/colors%'[s] R[ed, ]G[reen and ]B[blue] [colo[u]r[s]]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.5.3 (single value of items), 1.6 (list values of items and color)</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>integer</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>set</td>
</table>
 
---
 
### Rabbit Type
Returns the type of rabbit. e.g. `black`, `black and white`, `brown`, `gold`, `salt and pepper`, `the killer bunny` and `white`.
 
```java
on spawn of rabbit:
	if rabbit type of event-entity is "the killer bunny":
		broadcast "Run, everyone, run! The Killer Bunny was spawned!"
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] rabbit type of %entity%
%entity%'[s] rabbit type
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Text</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>set</td>
</table>
 
---
 
### Recipe ID
Starting from minecraft 1.12, the recipes now has a unique id. Recipes registered by minecraft will have a id `minecraft:%the result item's name%`, an old recipe plugin will be `bukkit:%random uuid%`, while TuSKe will have its id as `tuske:%last recipe id + 1%`. Other plugins may have a different format, but always following `<plugin>:<key>`.**Only for Shaped and Shapeless recipes**
 
```java
loop recipes of held item:
	add "{recipeBook:{recipes:["%recipe id of loop-recipe%"]}}" to player's nbt
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] recipe (id|name|key) of %recipes%
%recipes%'[s] recipe (id|name|key)
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.8</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Text</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### Recipe Owner
Starting from minecraft 1.12, recipes have now the register plugin. If it is a minecraft recipe, it will return as `Minecraft`, if it is an old recipe plugin, it will return as `Bukkit` and everything else will return the plugin's name. **Only for Shaped and Shapeless recipes**
 
```java
loop recipes of held item:
	if recipe owner of loop-recipe is "Minecraft":
		send "That's a vanilla recipe!"
```
<details><summary>Syntaxes</summary><p>
 
```java
[the] recipe owner of %recipes%
%recipes%'[s] recipe owner
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.8</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Text</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### Regex Error
It contains the last error of a regex. It is setted when there is a error while parsing a string as regex, {{effects|RegexReplace|replacing}}/{{effects|RegexSplit|spliting}} a string or checking in the {{conditions|RegexMatches|condition}}
 
```java
set {_regex} to "(\d+(\.\d+)*" parsed as regex
if regex error is set: #It will case there is a missing parentheses at the end.
	send "A error occurred with the regex pattern. Details:"
	send last regex parser error
	#It will send a formatted strings like showing the errors. For example:
	#Unclosed group near index 12
	#(\d+(\.\d+)*
	#             ^
```
<details><summary>Syntaxes</summary><p>
 
```java
[last] regex [parser] error
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.7.1</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Text</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### Regex Pattern
This expression returns some regex patterns that Skript or Bukkit uses most.
 
```java
player's uuid regex matches uuid pattern #It will be always true.
"{MyVariable}" regex matches variable pattern
set {_list::*} to regex split "%{VariableList::*}%" with list pattern
```
<details><summary>Syntaxes</summary><p>
 
```java
<.+> [regex] pattern
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.7.5</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Regex</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### Split Characters
Split a text with {{types|Number|number}} amount of characters. It is used to split the message in chat (the default is 60) and to item's lore.
 
```java
set {_s::*} to split "Hi, this text will be splitted in 3 lines" by 10 characters
```
<details><summary>Syntaxes</summary><p>
 
```java
split %string% (with|by|using) %number% [char[acter][s]]
%string% [split] (with|by|using) %number% [char[acter][s]]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.6.8</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Text</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
## Types
 
### Custom Enchantment
It represents a custom enchantment. The values depends of the id name of {{effects|RegisterEnchantment|registered enchantment}}.
 
```java
if "Soulbound" parsed as custom enchantment is set: #checks if the custom enchantment exists.
```
<table>
  <tr>
    <th>Pattern</th>
    <td>custom[ ]enchantment[s]<br>
    </td>
  </tr>
  </tr>
</table>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.5.1</td>
</table>
 
---
 
### GUI
It represents a gui inventory, where the player can take items away from the inventory. It can be created only with {{effects|MakeGUI|advanced gui effect}}.
 
```java
/command gui:
	trigger:
		create new gui with virtual chest named "Hub" with 3 rows: #Create a new gui based in a inventory
			make gui slot 13 with cake named "&e&lLobby": #Format slot with a given item
				make player execute command "server Lobby" #Code to be executed when the player clicks on gui
		open last gui to player #Open the last created gui to the player
```
<table>
  <tr>
    <th>Pattern</th>
    <td>gui[ ]inventor(y|ies)<br>
    </td>
  </tr>
  </tr>
</table>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.7.5</td>
</table>
 
---
 
### Recipe
A recipe contains the the ingredients list and the result item. Can only be get by {{expressions|Recipes|recipes's expression}}.
 
```java
loop recipes of {_item}:
	if "%loop-recipe%" is "furnace recipe":
		send "You have to make this recipe in a furnace."
```
<table>
  <tr>
    <th>Pattern</th>
    <td>recipe[s]<br>
    </td>
  </tr>
  </tr>
</table>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0.7</td>
</table>
 
---
 
### Regex
Represents an regex pattern object, it can be created with `"regex here" parsed as regex` or `/regex here/`. The second option is useful cause you don't need to escape Skript characters (like double %%, ""). Obviously, you can't use Skript expression in it, so for thatyou will need the first option.
 
```java
set {_regex} to "(\d+(\.\d+)*" parsed as regex
#or
set {_regex} to /(\d+(\.\d+)*/
if regex error is set: #It will case there is a missing parentheses at the end.
	send "A error occurred with the regex pattern. Details:"
	send last regex parser error
	#It will send a formatted strings like showing the errors. For example:
	#Unclosed group near index 12
	#(\d+(\.\d+)*
	#             ^
```
<table>
  <tr>
    <th>Pattern</th>
    <td>reg[ular ]ex[pression[s]|es]<br>
    </td>
  </tr>
  <tr>
    <th>Usage</th>
    <td>/.../<br>
    </td>
  </tr>
</table>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.7.1, 1.8.3 (regex escaper)</td>
</table>