## Summary
  * [Conditions](#conditions)
  * [Effects](#effects)
  * [Expressions](#expressions)
 
## Conditions
 
### CondBarHasFlag
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] [boss[ ]][bar] %bossbar% ((ha(s|ve)|contain[s])|(do[es](n't| not) have| do[es](n't| not) contain)) [(the|a)] [boss[ ]][bar] [flag] %barflag%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### CondCanBreed
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[entity] %entity% (can|can([ ]no|')t) [be] breed
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### CondCanSeePlayer
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[player] %player% (can|can([ ]no|')t) see [player] %player%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### CondClientTimeRelative
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[client] relative time of %player% (is|is(n't| not)) relative [to server]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### CondEventCancelled
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[(the|this)] event (is|is(n't| not)) cancelled
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### CondFileExists
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[file] exist(s|ance) [(at|of)] %string% [is %-boolean%]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### CondHasAuthor
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
book %itemstack% ((ha(s[n[']t]|ve)|contain[s])|(do[es](n't| not) have| do[es](n't| not) contain)) [had] [an] [book [meta]] author
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### CondHasCooldown
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
%player% ((has|does)|(has|does)(n't| not)) [(have|got)] [a] cool[ ]down for [(item|material)] %string%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### CondHasGeneration
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
book %itemstack% ((ha(s[n[']t]|ve)|contain[s])|(do[es](n't| not) have| do[es](n't| not) contain)) [had] [a] [book [meta]] generation
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### CondHasTitle
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
book %itemstack% ((ha(s[n[']t]|ve)|contain[s])|(do[es](n't| not) have| do[es](n't| not) contain)) [had] [a] [book [meta]] title
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### CondIsAdult
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[entity] %entity% (is|is(n't| not)) [a[n]] adult
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### CondIsInWater
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[entity] %entity% (is|is(n't| not)) in water
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### CondIsOfRow
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[slot] %number% (is|is(n't| not)) (within|of|in) row %number% [(of|in|from) [inventory] %-inventory%]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### CondIsPowered
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[block] %block% ((is|has)|(is|has)(n't| not)) [got] [redstone] powered
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### CondIsSticky
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[piston] %block% (is|is(n't| not)) [a] sticky [piston]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### CondIsUnbreakable
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
%itemstack% (is|is(n't| not)) unbreakable
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### CondIsWhitelisted
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[server] (is|is(n't| not)) whitelisted
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### CondJukeboxIsPlaying
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
juke[ ]box %block% (is|is(n't| not)) playing [a] (record|track|song)
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### CondLineOfSight
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
%entity% (can|can([ ]no|')t) [visibly] see %entity%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### CondMapBeingHandled
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[map] %map% (is|is(n't| not)) being handled [by skellett]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### CondObjectiveExists
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
objective %string% [[(in|from)] (score[ ][board]|[skellett[ ]]board) [%-scoreboard%]] ((is set|[does] exist[s])|(is(n't| not) set|does(n't| not) exist[s]))
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### CondObjectiveIsModifiable
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] (score[ ][board]|[skellett[ ]]board) objective %objective% (is modifiable|is(n't| not) modifiable)
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### CondPlayerViewingCredits
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[player] %player% (is|is(n't| not)) viewing [the] credits
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### CondRegeneratorExists
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] regenerator with id %string% (does|does(n't| not)) exist
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### CondScoreboardExists
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
score[ ][board] %string% ((is set|[does] exist[s])|(is(n't| not) set|does(n't| not) exist[s]))
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### CondStylishExists
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
(stylish|style|simple) [score][ ]board %string% ((is set|[does] exist[s])|(is(n't| not) set|does(n't| not) exist[s]))
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### CondTeamHasEntry
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] (score[ ][board]|[skellett[ ]]board) ((ha(s|ve)|contain[s])|(do[es](n't| not) have| do[es](n't| not) contain)) [the] [entry] %string% [(in|within)] the [team] %team%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### CondVirtualMap
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[map] %map% (is|is(n't| not)) virtual
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
## Effects
 
### EffActionbar
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
(send|show) [a[n]] action[ ]bar [(with|from)] [string] %string% to %players%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffAddClickEvent
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
add click event with action %clickeventaction% (and|with|to) [(execute|text|link)] %string% to [text component] %textcomponent%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffAddComponentToPage
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
add text component[s] %textcomponents% to [book] %itemstack%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffAddHoverEvent
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
add hover event with action %hovereventaction% (and|with) [(value|text)] %string% to [text component] %textcomponent%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffAddPage
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
add [a] page [with] [(text|data)] [%-string%] to [book] %itemstack%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffApplyBetterPotion
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] apply [potion[s]] [of] %potioneffecttype% [potion] [[[of] tier] %-number%] to %livingentities% [for %-timespan%] [[and] ambient %-boolean% [hide [particle [effects] %-boolean% [colo[u]r %-color%]]]]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffBabyAdult
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[(make|set)] [entity] %entity% [to] [a[n]] (baby|adult)
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffBarAddFlag
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] add [boss[ ]][bar] [flag] %barflag% to [the] [boss[ ]][bar] %bossbar%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffBarAddPlayer
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] add %player% to [the] [boss[ ]]bar %bossbar%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffBarHideAndShow
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] (hide|show) [boss[ ]]bar %bossbar%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffBarRemoveAllPlayers
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] remove [(the|all)] [of] [the] player[[']s] [(in|of|from)] [the] [boss[ ]]bar %bossbar%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffBarRemoveFlag
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] remove [boss[ ]][bar] [flag] %barflag% from [the] [boss[ ]][bar] %bossbar%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffBarRemovePlayer
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] remove %player% from [the] [boss[ ]]bar %bossbar%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffBlockConstructor
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
(create|start|make|build|construct) %string% with %itemtype% at %location% [[with effect[s]] %-boolean%]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffBreakBlockNaturally
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] break %block% [naturally] [(with|using) %-itemstack%]
[skellett] [naturally] break %block% [(with|using) %-itemstack%]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffChunkLoad
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] load chunk %chunk% [[with] generat(e|ing) %-boolean%]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffChunkUnload
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] unload chunk %chunk% [[with] sav(e|ing) %-boolean%]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffClearSlot
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
(clear|empty|reset) (inventory|menu|gui) [slot %-integer%] [(of|in)] %inventory%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffClientChest
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] (open|close) [the] %block% for %players%
[skellett] make [the] %block% (appear|look) (open|closed) for %players%
[skellett] play chest (open|close) animation at %block% for %players%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffCopyFile
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] copy file [path] %string% to [path] %string%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffCreateBlockRegenerator
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
(create|make) [a] [new] [skellett] regenerator with ID %string% with %blocks%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffCreateRegenerator
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
(create|make) [a] [new] [skellett] regenerator with ID %string% (from|within) [location[s]] %location% (to|and) %location%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffCustomEffect
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
(invoke|execute|run) method %string% [(from|of) [(expression|type|class)] %*-object%] [with parameter[s] %-objects%]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffDeleteRegenerator
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
(delete|remove) [the] [skellett] regenerator with ID %string% [re[ ]build %-boolean%]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffDeleteScoreboard
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
(delete|clear|remove) (score[ ][board]|[skellett[ ]]board)) [(with|named)] [(name|id)] %string%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffDownload
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] d[ownload][l] [from] [url] %string% to %string%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffEntityEffect
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] (make|force) %entity% [to] [(perform|do)] [entity] effect %entityeffect%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffFilesCreate
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] c[reate][ ][f][ile] %string%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffFilesDelete
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
d[elete[ ]]f[ile] %string%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffFirework
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] (launch|deploy) [%-strings%] firework[s] at %locations% [with] (duration|timed|time) %number% [colo[u]r[ed] (%-strings%|%-color%)]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffForceRespawn
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] [force] respawn [of] %player%
[skellett] force [the] %player% to respawn
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffHidePlayer
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] hide [player] %player% from %player%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffJukeboxEject
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[(force|make)] [the] juke[ ]box %block% eject [[it[']s] (record|track|song)]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffLeashBlock
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
(leash|lead) %livingentities% to %block%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffLoadCreateWorld
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] (load|create) world %string% [with generator %-string%] [[and] [with] [fawe] async[hronous]]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffManageMap
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
(manage|override|overwrite|create) [skellett] map %map% [[and] [with] override %-boolean%]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffMapDrawCursor
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
draw [map] cursor %string% pointing %number% at [coordinate[s]] [x] %number%(,| and) [y] %number% on [skellett] map %map%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffMapDrawImage
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
draw [buffered] image %mapimage% [at [coordinate[s]] [x] %number%(,| and) [y] %number%] on [skellett] map %map%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffMapDrawText
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
draw text %string% at [coordinate[s]] [x] %number%(,| and) [y] %number% on [skellett] map %map%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffMessageCenter
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
(message|send [message]) center[ed] %strings% to %players% [[with[ text]] %-string%]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffMessageTextComponent
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
message text components %textcomponents% to %players%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffMoveFile
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] move file [path] %string% to [path] %string%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffMySQLConnect
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] connect [to] mysql
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffMySQLDisconnect
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] disconnect [from] mysql
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffMySQLUpdate
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] mysql update %string%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffNMSTest
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
skellett nms of %object%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffOpenBook
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
open book %itemstack% to %player%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffOpenInventory
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] open [[better] inventory [type]] %string% [with %-number% row[s]] [named %-string%] to %players%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffPlaySound
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] play [(skellett|better)] [sound] (%-sound%|%-string%) at %locations% (with|at|and) volume %number% (and|with|at) pitch %number%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffPlaySoundPlayer
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] play [(skellett|better)] [sound] (%-sound%|%-string%) (for|to) %players% (with|at|and) volume %number% (and|with|at) pitch %number%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffPlayerTeleportWorldSpawn
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
teleport %players% to [world] spawn (of|in) [world] %string%
[skellett] teleport %players% to world %string% [spawn]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffReconfigureRegenerator
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
re[ ]configure [the] [skellett] regenerator with ID %string%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffRegenerate
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
re(generate|[ ]build) [the] [skellett] regenerator with ID %string%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffRegisterObjective
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
register [new] (score[ ][board]|[skellett[ ]]board) objective %string% with [criteria] %string% [[(in|from)] %-scoreboard%]
register [new] objective %string% with [criteria] %string% [(in|from)] (score[ ][board]|[skellett[ ]]board) [%-scoreboard%]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffRegisterTeam
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
register [a] [new] (score[ ][board]|[skellett[ ]]board) team %string% [[(in|from)] (score[ ][board]|[skellett[ ]]board) [%-scoreboard%]]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffReloadWhitelist
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
reload [the] white[ ]list
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffRemoveArrows
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
remove [(the|all)] [of] [the] arrows stuck in %player%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffRemoveEffects
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
(clear|remove) [all] [potion] effects (from|of) %players%
milk %players%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffResetEntryScores
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
reset [(the|all)] [of] [the] (score[ ][board]|[skellett[ ]]board) scores of [entry] %string% [[(in|from)] (score[ ][board]|[skellett[ ]]board) [%-scoreboard%]]
reset [(the|all)] [of] [the] (score[ ][board]|[skellett[ ]]board) [entry] %string%'s scores [[(in|from)] (score[ ][board]|[skellett[ ]]board) [%-scoreboard%]]
(score[ ][board]|[skellett[ ]]board) reset [(the|all)] [of] [the] scores of [entry] %string% [[(in|from)] (score[ ][board]|[skellett[ ]]board) [%-scoreboard%]]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffScoreboardClearSlot
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
clear (score[ ][board]|board) [display] slot %string% [[(in|from)] (score[ ][board]|[skellett[ ]]board) [%-scoreboard%]]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffSendMap
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
(show|send|display) [skellett] [custom] map %map% to %players%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffSerialze
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] serialize [variable] %object%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffSetCollidable
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[set] collid(e|able) [state] [of] %entity% to %boolean%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffSetInventoryProperty
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
(set|change) %player%['s] (window|[current] inventory) property [of] %inventoryproperty% to %number%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffSetWhitelist
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[set] white[ ]list [to] %boolean%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffShowPlayer
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] (show|reveal) [player] %player% to %players%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffSpawnerForce
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
(make|force) spawner [at] %block% to spawn [[a[n]] entit(y|ies)]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffStylishCreate
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] create [a] [new] (stylish|style|simple) [score][ ]board [with] [name[d]] %string%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffStylishDelete
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] (delete|remove) [the] (stylish|style|simple) [score][ ][board] [with] [name[d]] %string%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffStylishSlotCreate
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] create [a[n]] [new] id [based] [score] [(with [id]|named)] %string% [(with|and)] [(text|string)] %string% [(in|with|for|and)] slot %number% (in|for|of) (stylish|style|simple) [score][ ]board [with] [name[d]] %string%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffStylishSlotDelete
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] (delete|remove) [the] id [based] [score] [(with [id]|named)] %string% (in|from|for|of) (stylish|style|simple) [score][ ]board [with] [name[d]] %string%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffTeamAddEntry
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
(score[ ][board]|[skellett[ ]]board) add [the] entry [(from|of)] %string% to [the] [team] %team%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffTeamRemoveEntry
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[(score[ ][board]|[skellett[ ]]board)] remove [the] entry [(from|of)] %string% from [the] [team] %team%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffTitle
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
(send|show) [a] title [from] %string% [(with|and) [subtitle] %-string%] (to|for) %players% for %timespan%(,| and| with) %timespan% [fade[ ]in](,| and| with) %timespan% [fade[ ]out]
(send|show) %players% [a] title [(with|from)] %string% [(with|and) [subtitle] %-string%] for %timespan%(,| and| with) %timespan% [fade[ ]in](,| and| with) %timespan% [fade[ ]out]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffUnZip
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] unzip %string% to %string%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffUnregisterMap
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
(erase|clear|remove|delete|unregister) [skellett] map %map%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffUnregisterObjective
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
unregister (score[ ][board]|[skellett[ ]]board) objective %objective%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffUnregisterTeam
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
unregister [the] (score[ ][board]|[skellett[ ]]board) team %team%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffUpdateInventory
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
update [the] (inventory|menu|gui) %inventory%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
## Expressions
 
### ExprAbsoluteValue
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
absolute [value] of %number%
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
 
### ExprAbsorptionHearts
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] absorption hearts of %player%
[skellett] %player%'s absorption hearts
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
  <td>add, set, remove and reset</td>
</table>
 
---
 
### ExprActivePotionEffects
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[(the|all)] [of] [the] [active] potion[s] [effects] (on|of) %entity%
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
 
### ExprAge
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] age of [entity] %entity%
[entity] %entity%'s age
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
  <td>set</td>
</table>
 
---
 
### ExprAgeLock
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] age lock of [entity] %entity%
[entity] %entity%'s age lock
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
 
### ExprAmountOfDroppedItem
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] [get] (size|number|amount) of dropped %entity%
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
  <td>add, set, remove and reset</td>
</table>
 
---
 
### ExprAmountOfItem
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] (size|number|amount) of item[[ ]stack] %itemstack%
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
  <td>add, set, remove and reset</td>
</table>
 
---
 
### ExprAmountOfVariables
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
(size|amount) of [all] variables
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
 
### ExprAnvilPrepareInventory
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] [skellett] [event] anvil[[']s] inv[entory]
event-anvilinventory
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>anvilinventory</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### ExprAnvilPrepareInventoryCost
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] [skellett] [anvil[s]] repair cost (of|from|in) [anvil] [inventory] %anvilinventory%
[skellett] [anvil] [inventory] %anvilinventory%'s [anvil] repair cost
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
  <td>add, set, remove and reset</td>
</table>
 
---
 
### ExprArmorStandItemBoots
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
armo[u]r stand boots of %entity%
armo[u]r stand %entity%'s boots
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
 
### ExprArmorStandItemChestplate
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
armo[u]r stand chest[ ][plate] of %entity%
armo[u]r stand %entity%'s chest[ ][plate]
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
 
### ExprArmorStandItemHelmet
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
armo[u]r stand (helmet|hat) of %entity%
armo[u]r stand %entity%'s (helmet|hat)
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
 
### ExprArmorStandItemLeggings
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
armo[u]r stand leg[ging][s] of %entity%
armo[u]r stand %entity%'s leg[ging][s]
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
 
### ExprBarColour
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] [skellett] colo[u]r of [boss[ ]]bar %bossbar%
[skellett] %bossbar%'s [[boss][ ]bar] colo[u]r
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>barcolour</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>set</td>
</table>
 
---
 
### ExprBarFlags
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] [(the|all)] [of] [the] flag[[']s] [(in|of)] [the] [boss[ ]]bar %bossbar%
[skellett] %bossbar%'s flag[[']s]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>barflag</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### ExprBarPlayers
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] [(the|all)] [of] [the] player[[']s] [(in|of)] [the] [boss[ ]]bar %bossbar%
[skellett] %bossbar%'s player[[']s]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Player</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>add, remove and remove all</td>
</table>
 
---
 
### ExprBarProgress
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] [skellett] progress of [boss[ ]]bar %bossbar%
[skellett] %bossbar%'s [[boss][ ]bar] progress
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
  <td>set</td>
</table>
 
---
 
### ExprBarStyle
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] [skellett] style of [boss[ ]]bar %bossbar%
[skellett] %bossbar%'s [[boss][ ]bar] style
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>barstyle</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>set</td>
</table>
 
---
 
### ExprBarTitle
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] [skellett] (title|name|header|string) of [boss[ ]]bar %bossbar%
[skellett] %bossbar%'s [boss[ ]]bar (title|name|header|string)
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
 
### ExprBarVisible
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] [skellett] visib(le|ility) [(for|of)] [boss[ ]]bar %bossbar%
[skellett] %bossbar%'s [[boss][ ]bar] visib(le|ility)
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
 
### ExprBlockFaceFromDirection
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] [block[ ]]face of [block] %block% from %direction%
[block] %block%'s [block[ ]]face from %direction%
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
 
### ExprBlockGetDrops
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[(the|all)] [of] [the] [possible] drop[(ped|s)] [items] (from|of) [block [at]] %location% [(with|using) %-itemstack%]
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
 
### ExprBlockGetPower
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[redstone] power [[being] receiv(ed|ing)] [(from|at)] %location%
%location% [redstone] power [[being] received]
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
 
### ExprBlockHardness
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] block (break delay|durability|hardness) of [all] %block%
[all] %block%'s block (break delay|durability|hardness)
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
  <td>add, set and remove</td>
</table>
 
---
 
### ExprBlockXP
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[dropped] block[[']s] (xp|experience)
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
  <td>add, set and remove</td>
</table>
 
---
 
### ExprBookAuthor
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] [book['s]] author of %itemstack%
%itemstack%'s [book] author
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
 
### ExprBookGeneration
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] [book['s]] generation %itemstack%
%itemstack%'s [book] generation
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>bookgeneration</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>set</td>
</table>
 
---
 
### ExprBookPage
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] [book['s]] page %number% (of|in) [book] %itemstack%
%itemstack%'s [book] page %number%
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
  <td>add, set, delete and reset</td>
</table>
 
---
 
### ExprBookPages
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[(the|all)] [of] [the] [book] pages [(from|of)] [book] %itemstack%
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
 
### ExprBookTitle
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] [book['s]] title of %itemstack%
%itemstack%'s [book] title
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
 
### ExprBreakable
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] [a[n]] %itemstacks% [to be] breakable
[skellett] [a[n]] break(ing|able) %itemstacks%
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
 
### ExprBreedState
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] breeding state of [entity] %entity%
[entity] %entity%'s breeding state
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
 
### ExprBreedingBreeder
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
breeder
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Living Entity</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>add, remove and remove all</td>
</table>
 
---
 
### ExprBreedingEntity
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[final] bre[e]d[ed] entity
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Living Entity</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>add, remove and remove all</td>
</table>
 
---
 
### ExprBreedingFather
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
bre[e]d[ing] father
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Living Entity</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>add, remove and remove all</td>
</table>
 
---
 
### ExprBreedingItem
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
bre[e]d[ing] (item|material) [used]
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
 
### ExprBreedingMother
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
bre[e]d[ing] mother
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Living Entity</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>add, remove and remove all</td>
</table>
 
---
 
### ExprBreedingXP
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
bre[e]d[ing] (xp|experience)
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
  <td>add, set, remove and reset</td>
</table>
 
---
 
### ExprBrewingFuelConsuming
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[(the|is)] brew[ing] [stand[s]] consuming [state]
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
 
### ExprBrewingFuelPower
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] [the] brew[ing] [stand[[']s]] fuel [power]
[skellett] [the] fuel [power] of [the] brew[ing] [stand]
[skellett] event-fuel[power]
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
  <td>add, set, remove and reset</td>
</table>
 
---
 
### ExprBrewingInventory
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] [event] brew[ing] [stand] inventory
[skellett] event-brewinginventory
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>brewerinventory</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### ExprBrewingInventoryFuel
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
(fuel|burning) [item] (of|in) [brew[ing] stand] [inventory] %brewerinventory%
[brew[ing] stand] %brewerinventory%'s (fuel|burning) [item]
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
 
### ExprBrewingInventoryFuelTime
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[brew[ing]] fuel time (of|in) [brew[ing] stand] [inventory] %brewerinventory%
[brew[ing] stand] %brewerinventory%'s [brew[ing]] fuel time
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
  <td>add, set, remove and reset</td>
</table>
 
---
 
### ExprBrewingInventoryIngredient
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
ingredient [item] (of|in) [brew[ing] stand] [inventory] %brewerinventory%
[brew[ing] stand] %brewerinventory%'s ingredient [item]
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
 
### ExprBrewingInventoryTime
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[brew[ing]] time (of|in) brew[ing] [stand] [inventory] %brewerinventory%
brew[ing] [stand] %brewerinventory%'s [brew[ing]] time
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
  <td>add, set, remove and reset</td>
</table>
 
---
 
### ExprCanvasPixel
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] map pixle [colo[u]r] at [coordinate[s]] [x] %number%(,| and) [y] %number% (on|in) [skellett] map %map%
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
  <td>set</td>
</table>
 
---
 
### ExprChunkOutlineBlocks
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[(the|all)] [of] [the] blocks [in [a[n]]] (around|outlin(e|ing)) [of] chunk %chunk% [[at] [y(-| )coordinate] %-number%]
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
 
### ExprClickedAction
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
(click[ed]|inventory) action
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Inventory Action</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### ExprClickedCursor
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] [skellett] [click[ed]] cursor
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Item Type</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### ExprClickedInventory
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
click[ed] inventory
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
 
### ExprClickedItem
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] [skellett] [click[ed]] item
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Item Type</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>set</td>
</table>
 
---
 
### ExprClickedRawSlot
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
click[ed] raw slot
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
 
### ExprClickedRow
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] click[ed] row
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
 
### ExprClickedSlot
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] click[ed] slot
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
 
### ExprClickedSlotType
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
click[ed] slot type
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>clickedslottype</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### ExprClickedType
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] [skellett] click[ed] type
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Click Type</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### ExprClickedTypeNumber
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
click[ed] type num[ber]
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
 
### ExprClientBorderCenter
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[client [side]] [world] border center [location] (for|of) %player%
%player%'s [client [side]] [world] border center [location]
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
  <td>set</td>
</table>
 
---
 
### ExprClientBorderDamageAmount
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[client [side]] [world] border damage [amount] (for|of) %player%
%player%'s [client [side]] [world] border damage [amount]
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
  <td>add, set, remove and reset</td>
</table>
 
---
 
### ExprClientBorderDamageBuffer
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[client [side]] [world] border [damage] buffer (for|of) %player%
%player%'s [client [side]] [world] border [damage] buffer
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
  <td>add, set, remove and reset</td>
</table>
 
---
 
### ExprClientBorderSize
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[client [side]] [world] border size (for|of) %player%
%player%'s [client [side]] [world] border size
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
  <td>add, set, remove and reset</td>
</table>
 
---
 
### ExprClientBorderWarningDistance
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[client [side]] [world] border warning distance (for|of) %player%
%player%'s [client [side]] [world] border warning distance
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
  <td>add, set, remove and reset</td>
</table>
 
---
 
### ExprClientBorderWarningTime
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[client [side]] [world] border warning [time] (for|of) %player%
%player%'s [client [side]] [world] border warning [time]
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
  <td>add, set, remove and reset</td>
</table>
 
---
 
### ExprClientWeather
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] [client] weather of %player%
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
  <td>set</td>
</table>
 
---
 
### ExprCollidableState
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
collid(e|able) [state] [of] %entity%
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
  <td>none</td>
</table>
 
---
 
### ExprCropState
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
crop state of %block%
%block%'s crop state
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
 
### ExprCursorCoordinate
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] map cursor (x|y)(-| )(coord[inate]|pos[ition]|loc[ation])[s] of [[map][ ]cursor] %mapcursor%
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
  <td>set</td>
</table>
 
---
 
### ExprCursorDirection
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] map cursor direction (of|for) [[map][ ]cursor] %mapcursor%
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
  <td>set</td>
</table>
 
---
 
### ExprCursorType
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] map cursor type (of|for) [[map][ ]cursor] %mapcursor%
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
 
### ExprCursorVisible
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] map cursor visibl(e|ity) [state] (of|for) [[map][ ]cursor] %mapcursor%
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
 
### ExprCustomExpression
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[event] method %string% [is [a] loop[able] %-boolean%] [(from|of) [(expression|type|class)] %-object%] [with parameter[s] %-objects%]
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
 
### ExprCustomName
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] custom name of %entity%
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
 
### ExprCustomNameVisible
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] custom name visib(le|ility) of %entity%
[skellett] visib(le|ility) of %entity%'s custom name
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
 
### ExprDataWatcher
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
data watcher value %number% from %entity%
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
 
### ExprDataWatcherType
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
data watcher type (of|from) %*object%
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
 
### ExprDyedArmour
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] [dye[d]] [colo[u]r] [of] %itemstack% [to] (colo[u]r[ed]|dyed) %color%
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
 
### ExprEnchantmentNumber
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] enchant[ment] level (from|of) %enchantment% (of|in|on) %itemstack%
[skellett] %itemstack%'s enchant[ment] level (from|of|on) %enchantment%
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
  <td>set</td>
</table>
 
---
 
### ExprEnchantmentOfferCost
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] cost of [enchant[ment]] offer %enchantmentoffer%
offer %enchantmentoffer%'s [enchant[ment]] cost
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
  <td>add, set, remove and reset</td>
</table>
 
---
 
### ExprEnchantmentOfferEnchantLevel
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] level of [enchant[ment]] offer %enchantmentoffer%
offer %enchantmentoffer%'s [enchant[ment]] level
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
  <td>add, set, remove and reset</td>
</table>
 
---
 
### ExprEnchantmentOfferEnchantment
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] enchant[ment] of [enchant[ment]] offer %enchantmentoffer%
offer %enchantmentoffer%'s [enchant[ment]] enchant[ment]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Enchantment</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>set</td>
</table>
 
---
 
### ExprEnchantmentOffers
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[(the|all)] [of] [the] enchant[ment] offers
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>enchantmentoffer</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### ExprEnchantments
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[(the|all)] [of] [the] enchant[ment]s (on|of|from) %itemstack%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Enchantment</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### ExprEnderCrystalBase
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[ender] crystal base [visib(le|ility)] [state] of %entity%
%entity%'s [ender] crystal base [visib(le|ility)] [state]
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
 
### ExprEnderCrystalBeam
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[ender] crystal (target|beam) [location] of %entity%
%entity%'s [ender] crystal (target|beam) [location]
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
  <td>set, remove, remove all, delete and reset</td>
</table>
 
---
 
### ExprEntityFarAway
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] [(despawn|remove|clear)] [get] %entity% when [it([']s| is)] far away [state]
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
 
### ExprEntityFromUUID
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] entity (from [the]|of) (uuid|[universal] unique id) %string%
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
  <td>add, remove and remove all</td>
</table>
 
---
 
### ExprEntityID
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] [entity] [number] id (of|from) %entities%
%entities%'s [entity] [number] id
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
 
### ExprEntityScoreboardTag
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[(the|all)] [of] [the] scoreboard tag[s] (of|from) %entity%
%entity%'s scoreboard tag[s]
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
  <td>add and remove</td>
</table>
 
---
 
### ExprEntityUUID
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] entity (uuid|[universal] unique id) of [entity] %entity%
[entity] %entity%'s entity (uuid|[universal] unique id)
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
 
### ExprEntries
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[(the|all)] [of] [the] (score[ ][board]|board)[[']s] entr(ies|y[[']s]) [[(in|from)] (score[ ][board]|[skellett[ ]]board) [%-scoreboard%]]
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
 
### ExprEventMap
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] [the] event[(-| )]map
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>map</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### ExprExhaustion
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
exhaustion of %player%
%player%'s exhaustion
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
  <td>add, set, remove and reset</td>
</table>
 
---
 
### ExprFallDistance
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] fall distance (from|of) %entity%
%entity%'s fall distance
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
  <td>add, set and remove</td>
</table>
 
---
 
### ExprFinalDamage
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] final damage
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
 
### ExprFishingGetCaught
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] caught (fish|item|entity)
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
  <td>add, remove and remove all</td>
</table>
 
---
 
### ExprFishingGetHook
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] [fishing] hook
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Projectile</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### ExprFishingState
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] [fish[ing]] state
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>fishingstate</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### ExprFixFishingGetXP
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] [fish[ing]] (xp|experience) [earned]
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
  <td>add, set, remove and reset</td>
</table>
 
---
 
### ExprFunctions
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[(the|all)] [of] [the] [loaded] functions
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
 
### ExprFuseTime
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] (fuse time|time until blowup) of [the] [primed] [tnt] %entity%
[skellett] [primed] [tnt] %entity%['s] (fuse time|time until blowup)
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
  <td>add, set and remove</td>
</table>
 
---
 
### ExprGetEntryScores
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[(the|all)] [of] [the] (score[ ][board]|[skellett[ ]]board) scores of [entry] %string% [[(in|from)] (score[ ][board]|[skellett[ ]]board) [%-scoreboard%]]
[(the|all)] [of] [the] (score[ ][board]|[skellett[ ]]board) [entry] %string%'s scores [[(in|from)] (score[ ][board]|[skellett[ ]]board) [%-scoreboard%]]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>scoreboard score</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### ExprGetEntryTeam
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] (score[ ][board]|board) team of [entry] %string% [[(in|from)] (score[ ][board]|[skellett[ ]]board) [%-scoreboard%]]
[the] (score[ ][board]|board) [entry] %string%'s team [[(in|from)] (score[ ][board]|[skellett[ ]]board) [%-scoreboard%]]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>scoreboard team</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### ExprGetObjective
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] (score[ ][board]|[skellett[ ]]board) objective %string% [[(in|from)] (score[ ][board]|[skellett[ ]]board) [%-scoreboard%]]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>scoreboard objective</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### ExprGetScoreboard
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[get] (score[ ][board]|[skellett[ ]]board)) [(with|named)] [(name|id)] %string%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>scoreboard</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### ExprGetTeam
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] (score[ ][board]|[skellett[ ]]board) %string% team [[(in|from)] (score[ ][board]|[skellett[ ]]board) [%-scoreboard%]]
(score[ ][board]|[skellett[ ]]board) [get] team %string% [[(in|from)] (score[ ][board]|[skellett[ ]]board) [%-scoreboard%]]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>scoreboard team</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### ExprGlideState
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
glide [state] [(of|for)] [entit(y|ies)] %entity%
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
  <td>set and reset</td>
</table>
 
---
 
### ExprGlowingSpectralArrow
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[spectral] arrow glowing time of %entity%
%entity%'s [spectral] arrow glowing time
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
  <td>add, set and remove</td>
</table>
 
---
 
### ExprGravityState
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] gravity [state[s]] [(of|for)] [entit(y|ies)] %entities%
[skellett] %entities%'s gravity [state[s]]
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
  <td>set, remove all and reset</td>
</table>
 
---
 
### ExprGroundState
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[(is|are)] [on] [the] ground [state] [of] [entity] %entity%
[entity] %entity% [(is|are)] [on] [the] ground [state]
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
  <td>none</td>
</table>
 
---
 
### ExprHangingCause
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] [un](hung|hang)[(ed|ing)] cause
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
 
### ExprHangingRemover
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] (hung|hang)[(ed|ing)] remover [entity]
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
  <td>add, remove and remove all</td>
</table>
 
---
 
### ExprHideEnchants
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
%itemstacks% with hid(den|ing) enchant[ment][s]
[skellett] (shiny|hidden enchant[ment][s]|glow|glowing) [item] %itemstack%
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
 
### ExprHitboxLength
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] hitbox length of %entity%
%entity%'s hitbox length
[the] length of %entity%'s hitbox
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
 
### ExprHitboxWidth
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] hitbox width of %entity%
%entity%'s hitbox width
[the] width of %entity%'s hitbox
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
 
### ExprHotbarSwitchSlot
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] ((past|previous)|(new|future|present)) [changed] (hotbar|held|changed) slot
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
 
### ExprImageFile
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] [the] image (of|from) [the] file [(location|path)] %string%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>mapimage</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### ExprIndexes
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[(the|all)] [of] [the] indexes (of|[with]in) %~objects%
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
 
### ExprInstaBreak
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[event] inst(ant|a) break [state]
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
  <td>set and reset</td>
</table>
 
---
 
### ExprInventoryRows
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] (gui|menu|inventory|chest|window) row[s] (of|from) %inventory%
%inventory%'s (gui|menu|inventory|chest|window) row[s]
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
  <td>set</td>
</table>
 
---
 
### ExprInventorySize
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] (gui|menu|inventory|chest|window) (size|number|slots) (of|from) %inventory%
%inventory%'s (gui|menu|inventory|chest|window) (size|number|slots)
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
  <td>set</td>
</table>
 
---
 
### ExprInventoryType
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
inventory type of %inventory%
%inventory%'s inventory type
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
 
### ExprInventoryViewers
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[(the|all)] [of] [the] [player[']s] view(er[s]|ing) [of] %inventory%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Living Entity</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>add, remove and remove all</td>
</table>
 
---
 
### ExprInvulnerableState
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
invulnerable state of %entity%
%entity%'s silent invulnerable
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
 
### ExprItemCooldown
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] cool[ ]down of [(item|material)] %string% (for|of) %players%
[(item|material)] %string%'s cool[ ]down (for|of) %players%
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
  <td>set and reset</td>
</table>
 
---
 
### ExprItemframeItem
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] item (in|inside|within|of|from) item[ ]frame %entity%
[skellett] %entity%'s item[ ]frame item
[skellett] item[ ]frame %entity%'s item
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
 
### ExprItemframeRotation
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] rotation (of|from) item[ ]frame %entity%
[skellett] %entity%'s item[ ]frame rotation
[skellett] item[ ]frame %entity%'s rotation
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>rotation</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>set</td>
</table>
 
---
 
### ExprItemsInSlots
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[items (from|of|in)] slots %numbers% (from|of|in) %inventory%
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
  <td>set, remove, remove all, delete and reset</td>
</table>
 
---
 
### ExprItemsWithinEntity
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] [get] item[s] (of|in|inside|within) entity %entity%
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
 
### ExprJavaVersion
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] server[[']s] java version
[the] java version of [the] server
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
 
### ExprLastCreatedBossBar
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] last created [boss[ ]]bar
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>bossbar</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### ExprLlamaColorType
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
Llama colo[u]r of %entity%
Llama %entity%'s colo[u]r
%entity%['s] Llama colo[u]r
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>llamacolor</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>set</td>
</table>
 
---
 
### ExprLlamaInventory
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
inventory of Llama %entity%
Llama inventory of %entity%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>llamainventory</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### ExprLlamaInventoryDecor
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[Llama] decor (of|in) [inventory] [of] [Llama] %llamainventory%
[Llama] %llamainventory%'s [inventory] decor
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
 
### ExprLongDate
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
date (from|of) [(long|milliseconds)] %number%
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
 
### ExprMapCenter
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
center (x|z)[( |-)][(position|coord[inate])] (of|from|in) [map] %map%
%map%'s center (x|z)[( |-)][(position|coord[inate])]
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
  <td>add, set and remove</td>
</table>
 
---
 
### ExprMapCursors
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] [(the|all)] [of] [the] map cursors (in|on|for) [skellett] [map] %map%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>mapcursor</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### ExprMapScale
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
map (scale|size) of %map%
map %map%'s (scale|size)
(scale|size) of map %map%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>mapscale</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>set and reset</td>
</table>
 
---
 
### ExprMapUnlimitedTracking
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
unlimited [tracking] state (of|from|in) [map] %map%
[map] %map%'s unlimited [tracking] state
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
 
### ExprMapWorld
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
world of map %map%
map %map%'s world
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
 
### ExprMaterialItemType
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] [spigot] material [name] (from|of) %itemtype%
%itemtype%'s [spigot] material [name]
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
 
### ExprMaxDamageTicks
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] [maximum] damage delay of %entity%
[skellett] %entity%'s [maximum] damage delay
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Timespan</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>add, set and remove</td>
</table>
 
---
 
### ExprMetadata
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[(skellett|fixed)] meta[ ]data [value] %string% (of|in|within) %object%
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
  <td>set, delete and reset</td>
</table>
 
---
 
### ExprMethods
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[(the|all)] [of] [the] [event] methods
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
 
### ExprMethodsOfObject
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[(the|all)] [of] [the] methods (from|of|in) [the] [expression] %object%
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
 
### ExprMySQLDatabase
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] mysql['s] database
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
 
### ExprMySQLHost
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] mysql['s] host
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
 
### ExprMySQLPort
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] mysql['s] port
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
  <td>set</td>
</table>
 
---
 
### ExprMySQLQuery
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] mysql result of query %string%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>mysql resultset</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### ExprMySQLQueryBoolean
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] mysql boolean[s] %string% (in|from|of) %resultset%
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
  <td>none</td>
</table>
 
---
 
### ExprMySQLQueryInteger
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] mysql integer[s] %string% (in|from|of) %resultset%
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
 
### ExprMySQLQueryNumber
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] mysql (number|float)[s] %string% (in|from|of) %resultset%
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
 
### ExprMySQLQueryObject
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] mysql object[s] %string% (in|from|of) %resultset%
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
 
### ExprMySQLQueryString
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] mysql string[s] %string% (in|from|of) %resultset%
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
 
### ExprMySQLUsername
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] mysql['s] username
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
 
### ExprNearbyEntities
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] [(the|all)] [of] [the] [nearby] entit(y|ies) (within|in) [a] radius [of] %number%[(,| and) %-number%(,| and) %-number%] (within|around|near) %location%
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
  <td>add, remove and remove all</td>
</table>
 
---
 
### ExprNewBook
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[a] new [written] book
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
 
### ExprNewBossBar
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] [create] [a] new [boss[ ]]bar [with flag %-barflag%]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>bossbar</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### ExprNewInventory
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[a] new inv[entory] [with type] %string% [with %-number% row[s]] [named %-string%]
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
 
### ExprNewMap
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] [a] new map[[ ]view] (for|from|with) [world] %world%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>map</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### ExprNewMaterial
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] new [changed] material
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
 
### ExprNewScoreboard
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[create] [a] new (score[ ][board]|[skellett[ ]]board) [(with|named)] [(name|id)] %string%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>scoreboard</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### ExprNewTextComponent
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[a] [new] text component [with [text]] %string%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>textcomponent</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### ExprNextEmptySlot
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
(next|first) empty slot of %inventory%
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
 
### ExprNoItemNBT
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
%itemstacks% with(out [any]| no) NBT
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
 
### ExprNumbersOfString
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[get] [the] (digit|num[ber])[s] (of|from|in) %string%
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
 
### ExprObjectiveCriteria
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] (score[ ][board]|[skellett[ ]]board) objective criteria [of] %objective%
[the] (score[ ][board]|[skellett[ ]]board) %objective%'s objective criteria
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
 
### ExprObjectiveDisplayName
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] (score[ ][board]|[skellett[ ]]board) objective display name [(for|from|of)] %objective%
[the] (score[ ][board]|[skellett[ ]]board) %objective%['s] objective['s] display name
[the] (score[ ][board]|[skellett[ ]]board) objective %objective%['s] display name
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
 
### ExprObjectiveDisplaySlot
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] (score[ ][board]|[skellett[ ]]board) objective [display] slot [(for|from|of)] %objective%
[the] (score[ ][board]|[skellett[ ]]board) %objective%['s] objective['s] [display] slot
[the] (score[ ][board]|[skellett[ ]]board) objective %objective%['s] [display] slot
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
 
### ExprObjectiveGetScore
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] (score[ ][board]|[skellett[ ]]board) [objective] %objective%['s] score [(for|from|of)] [entry] %string%
[the] (score[ ][board]|[skellett[ ]]board) %objective%['s] [objective['s]] score [(for|from|of)] [entry] %string%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>scoreboard score</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### ExprObjectiveName
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] (score[ ][board]|[skellett[ ]]board) objective name [(for|from|of)] %objective%
[the] (score[ ][board]|[skellett[ ]]board) %objective%['s] objective['s] name
[the] (score[ ][board]|[skellett[ ]]board) objective %objective%['s] name
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
 
### ExprObjectives
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[(the|all)] [of] [the] [(score[ ][board]|board)[[']s]] objectives [[(in|from)] (score[ ][board]|[skellett[ ]]board) [%-scoreboard%]]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>scoreboard objective</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### ExprObjectivesByCriteria
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[(the|all)] [of] [the] (score[ ][board]|board)[[']s] objectives (by|with) [criteria] %string% [[(in|from)] (score[ ][board]|[skellett[ ]]board) [%-scoreboard%]]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>scoreboard objective</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### ExprOfflinePlayers
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[(the|all)] [of] [the] offline[ ]player[s]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Offlineplayer</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### ExprOperators
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[(the|all)] [of] [the] Op[erator](s|ed) [players]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Offlineplayer</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### ExprPackets
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] [skellett] packet (data|value|field) %string% [[is] [a] loop[able] %-boolean%]
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
  <td>set</td>
</table>
 
---
 
### ExprParticles
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[(the|all)] [of] [the] particle[[ ]types]
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
 
### ExprPistonPower
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] piston[s] (power|toggle) [state] of %block%
%block%'s piston (power|toggle) [state]
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
 
### ExprPistonReaction
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] piston [move] reaction (of|from) %block%
%block%'s piston [move] reaction
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>pistonreaction</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### ExprPlayerInventoryCursor
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[current [inventory]] cursor of %player%
%player%'s [current [inventory]] cursor
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Item Type</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>set</td>
</table>
 
---
 
### ExprPlayerPing
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] ping of [player] %player%
[skellett] %player%'s ping
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
 
### ExprPlayerScoreboard
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
(score[ ][board]|[skellett[ ]]board) of [player] %player%
%player%'s (score[ ][board]|[skellett[ ]]board)
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>scoreboard</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>set and remove</td>
</table>
 
---
 
### ExprProjectileBounce
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] %entity%[[']s] bounc(e|ing) [state]
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
 
### ExprRedstoneCurrent
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] [skellett] ((new|future)|(old|past)) [event] [redstone] current
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
  <td>add, set, remove and reset</td>
</table>
 
---
 
### ExprRegeneratorBlocks
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
block[s] of [skellett] regenerator [[with] id] %string%
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
 
### ExprRegeneratorPos1
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
pos[ition][ ]1 of [skellett] regenerator [[with] id] %string%
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
  <td>set</td>
</table>
 
---
 
### ExprRegeneratorPos2
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
pos[ition][ ]2 of [skellett] regenerator [[with] id] %string%
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
  <td>set</td>
</table>
 
---
 
### ExprRegenerators
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[(the|all)] [of] [the] [skellett] regenerator[s] [ids]
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
 
### ExprRemoveItemNBT
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
%itemstacks% with [all] removed NBT
remove[ed] [all] NBT [from] %itemstacks%
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
 
### ExprRepeaterDelay
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] [redstone] repeater[s] [(redstone|power)] delay of %block%
[redstone] repeater %block%'s [(redstone|power)] delay
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
  <td>set</td>
</table>
 
---
 
### ExprReturnType
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[(|skript|skellett)] [the] return (type[s]|value[s]) [(from|of|in)] [the] [expression] %object%
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
 
### ExprRoundDecimal
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[Skellett] %number% round[ed] [to] [the] [nearest] %number% decimal (digit[s]|place[s])
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
 
### ExprScore
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] (score[ ][board]|[skellett[ ]]board) (score|number|slot) [(for|from|of)] %score%
(score[ ][board]|[skellett[ ]]board) %score%'s (score|number|slot)
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
  <td>add, set and remove</td>
</table>
 
---
 
### ExprScoreEntry
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] (score[ ][board]|[skellett[ ]]board) [get] entry [(for|from|of)] score %score%
(score[ ][board]|[skellett[ ]]board) %score%'s score entry
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
 
### ExprScoreObjective
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] (score[ ][board]|[skellett[ ]]board) objective [(for|from|of)] score %score%
[the] (score[ ][board]|[skellett[ ]]board) %score%'s scores objective
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>scoreboard objective</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### ExprShootArrowSpeed
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
(arrow|shot|velocity) speed [of (shot|arrow)]
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
  <td>none</td>
</table>
 
---
 
### ExprShootGetArrow
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] [skellett] [(event|get)] [the] shot (arrow|projectile)
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
  <td>set</td>
</table>
 
---
 
### ExprShootGetBow
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] [skellett] [(event|get)] bow
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
 
### ExprSilentState
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
(silent|quiet) [state] [of] [entit(y|ies)] %entities%
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
  <td>set, remove all and reset</td>
</table>
 
---
 
### ExprSkullBlockOwner
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] [skellett] skull[ ]owner of [skull] %block%
[skellett] [skull] %block%'s skull[ ]owner
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>Offlineplayer</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>set</td>
</table>
 
---
 
### ExprSkullRotation
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] [skellett] skull[ ]rotation of [skull] %block% [in (direction|blockface)]
[skellett] [skull] %block%'s skull[ ]rotation [in (direction|blockface)]
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
  <td>set</td>
</table>
 
---
 
### ExprSleepIgnored
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
ignored sleep[ing] [state] of %player%
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
  <td>set and reset</td>
</table>
 
---
 
### ExprSlimeSize
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] slime size of %entity%
[skellett] %entity%'s slime size
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
  <td>add, set and remove</td>
</table>
 
---
 
### ExprSneakState
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
sneak[ing] [state] of %player%
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
  <td>set and reset</td>
</table>
 
---
 
### ExprSpawnReason
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] spawn reason
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>spawnreason</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### ExprSpawnerDelay
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
delay (of|from) spawner [at] %block%
%block%'s spawn[er] delay
spawn[er] delay (of|from) %block%
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
  <td>add, set and remove</td>
</table>
 
---
 
### ExprSpawnerType
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
(entity|mob|creature) [type] (of|from) spawner [at] %block%
%block%'s spawn[er] (entity|mob|creature) [type]
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
 
### ExprSpectate
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
(spec[tat(e|or|ing)]|view[ing]) [(target|state)] of %player%
%player%'s (spec[tat(e|or|ing)]|view[ing]) [(target|state)]
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
  <td>set, remove, delete and reset</td>
</table>
 
---
 
### ExprSpreadSource
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[spread] source block
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
 
### ExprSprintState
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
(sprint|run)[ing] [state] of %player%
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
  <td>set and reset</td>
</table>
 
---
 
### ExprStatistics
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] stat[istic][s] %string% (of|from) %player% [[(with|from|for|of)] entity[[ ]type] %-string%] [[(with|from|for|of)] material %-string%]
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
  <td>add, set, remove, remove all, delete and reset</td>
</table>
 
---
 
### ExprStylishPlayerBoard
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] (stylish|style|simple) [score][ ][board] of %player%
%player%'s (stylish|style|simple) [score][ ][board]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>scoreboard</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>set and reset</td>
</table>
 
---
 
### ExprStylishSlotBoard
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] [(update|edit)] [the] [(stylish|style|simple)] [score][ ]board [of] id [based] [score] [(with [id]|named)] %string%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>scoreboard</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>set</td>
</table>
 
---
 
### ExprStylishSlotNumber
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] [(update|edit)] [the] slot [of] id [based] [score] [(with [id]|named)] %string%
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
  <td>set</td>
</table>
 
---
 
### ExprStylishSlotText
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] [(update|edit)] [the] (text|name|display|data|string) [of] id [based] [score] [(with [id]|named)] %string%
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
 
### ExprStylishTitle
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] [(update|edit)] [the] [display] title of (stylish|style|simple) [score][ ][board] [named] %string%
[skellett] [(update|edit)] [the] (stylish|style|simple) [score][ ][board] %string%['s] [display] title
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
 
### ExprTargetReason
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] target reason
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>targetreason</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### ExprTeamDisplayName
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] [(score[ ][board]|[skellett[ ]]board)] team display name [(for|from|of)] %team%
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
 
### ExprTeamEntries
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[(the|all)] [of] [the] (score[ ][board]|[skellett[ ]]board)[[']s] entr(ies|y[[']s]) (in|within) [the] [team] %team%
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
 
### ExprTeamFriendlyFire
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] [(score[ ][board]|[skellett[ ]]board)] friendly [fire] state [(for|of)] [team] %team%
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
 
### ExprTeamFriendlyInvisibles
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] (score[ ][board]|[skellett[ ]]board) [friendly] invisible[s] [state] [(for|of)] [team] %team%
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
 
### ExprTeamName
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] (score[ ][board]|[skellett[ ]]board)) [team] name [(for|of)] [team] %team%
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
 
### ExprTeamOptions
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] (score[ ][board]|[skellett[ ]]board) [team] option[s] [status] %teamoption% [(for|of)] [the] [team] %team%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>optionstatus</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>set</td>
</table>
 
---
 
### ExprTeamPrefix
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[(score[ ][board]|[skellett[ ]]board)] [team] prefix [(for|of)] [team] %team%
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
 
### ExprTeamSize
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[(score[ ][board]|[skellett[ ]]board)] team size [(for|of)] [team] %team%
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
 
### ExprTeamSuffix
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[(score[ ][board]|[skellett[ ]]board)] [team] suffix [(for|of)] [team] %team%
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
 
### ExprTeams
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[(the|all)] [of] [the] teams [[(in|from)] (score[ ][board]|[skellett[ ]]board) [%-scoreboard%]]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>scoreboard team</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### ExprTeleportCause
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] teleport cause
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>teleportcause</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### ExprTick
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] server tick[s]
[the] server's tick[s]
[the] tick[s] of [the] server
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
 
### ExprTicksFromTime
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] tick[s] (of|from) [time[span]] %timespan%
[time[span]] %timespan%'s tick[s]
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
 
### ExprUnbreakable
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] [a[n]] %itemstacks% [to be] unbreakable
[skellett] [a[n]] unbreak(ing|able) %itemstacks%
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
 
### ExprUnleashHitch
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
event-hitch
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
  <td>add, remove and remove all</td>
</table>
 
---
 
### ExprUnleashReason
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
(un(leash|lead)|(leash|lead) break) reason
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>unleashreason</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### ExprWorldChangeFrom
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
(previous|past) [changed] world
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
 
### ExprWorldFolder
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
world folder of %world%
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
 
### ExprWorldOfLocation
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] world (of|from) [location] %location%
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
 
### ExprYaml
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[skellett] (file|y[a]ml) [file] (value|node[s]|node[s with] keys|list) %string% (in|at|from) [file] %string%
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
  <td>delete and reset</td>
</table>