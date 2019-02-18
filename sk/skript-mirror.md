## Summary
  * [Events](#events)
  * [Conditions](#conditions)
  * [Effects](#effects)
  * [Expressions](#expressions)
 
## Events
 
### Consent
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
skript-mirror, I know what I'm doing
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
</table>
 
---
 
### Define Condition
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[(local)] condition <.+>
[(local)] condition
[(local)] %*classinfos% property condition <.+>
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
</table>
 
---
 
### Define Constant
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
option <.+>
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
</table>
 
---
 
### Define Effect
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[(local)] effect <.+>
[(local)] effect
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
</table>
 
---
 
### Define Expression
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[(local)] [((plural|non(-|[ ])single))] expression <.+>
[(local)] [((plural|non(-|[ ])single))] expression
[(local)] [((plural|non(-|[ ])single))] %*classinfos% property <.+>
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
</table>
 
---
 
### Import
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
import
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
</table>
 
---
 
### On Bukkit Event
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[on] [(all)] %javatypes% [(at|on|with) priority <.+>]
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
  <td>true</td>
</table>
## Conditions
 
### CondExpressionStatement
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[(await)] %~javaobject%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### CondIsInstanceOf
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
%objects% (is|are) [a[n]] instance[s] of %javatypes%
%objects% (is not|isn't|are not|aren't) [a[n]] instance[s] of %javatypes%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### CondParseLater
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
(parse[d] later) <.+>
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### CustomCondition
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
%objects% (is|are) similar to %object% [with (tolerance %-number% [percent]|%-number% [percent] tolerance)]
%objects% (isn't|is not|aren't|are not) similar to %object% [with (tolerance %-number% [percent]|%-number% [percent] tolerance)]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
## Effects
 
### CustomEffect
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
draw [a] polygon [(outline [(with ((flat|square) (cap|(edge|corner)[s])))] [with width %-number%])][[( and|,)] [with] [(paint|gradient)] %-object%][[( and|,)] [with] [rotation] %-number% degree[s] [angle] [using origin location %-number%,[ ]%-number%]] on [(image|img)] %object% ((between|at)|using) [(corner|vertice|vertex|point)] locations %numbers% [[and] (store|save) ([[the] result]|it) (in|to) [variable] %-object%]
[(flood|bucket)] fill [on] [(image|img)] %object% at [location] %number%,[ ]%number% (with|using) [replace[ment]] %object%[[( and|,)] [with] tolerance %-number% [percent]] [[and] (store|save) ([[the] result]|it) (in|to) [variable] %-object%]
resize [(image|img)] %object% to [sizes] (width %-number%[( and|,)] height %-number%|height %-number%[( and|,)] width %-number%) [(with|using) algorithm %-number%] [[and] (store|save) ([[the] result]|it) (in|to) [variable] %-object%]
mask [(image|img)] %object% by [(image|img)] %object% [[and] (store|save) ([[the] result]|it) (in|to) [variable] %-object%]
imagesk set variable %object% to %object% in %event%
imagesk [(parse)] error %string%
get [the] (image|img) (of|from) (url %-string%|file %-string%|base[ ]64 %-string%) [[and] (store|save) ([[the] result]|it) (in|to) [variable] %-object%]
(register|install|load) [(the|new)] font[s] [famil(y|ies)] [(from|of|at|in)] [[the] (file|folder|directory)] %string%
draw [a] rectangle [(outline [with width %-number%])] with (width %-number%[( and|,)] [with] height %-number%|height %-number%[( and|,)] [with] width %-number%)[[( and|,)] [with] [(paint|gradient)] %-object%][[( and|,)] [with] [rotation] %-number% degree[s] [angle] [using origin location %-number%,[ ]%-number%]] on [(image|img)] %object% [at [location] %-number%,[ ]%-number%] [[and] (store|save) ([[the] result]|it) (in|to) [variable] %-object%]
(create|generate) [a[n]] [new] [(image|img)] (text|string) [(with (id|name)|named)] %string% [[and] [with] (content|text|string) %-string%]
make [(image|img)] %object% (circle|[fully] rounded) [[and] (store|save) ([[the] result]|it) (in|to) [variable] %-object%]
draw [a] polygon [(outline [(with (flat|square) (cap|(edge|corner)[s]))] [with width %-number%])][[( and|,)] with [paint] %-object%] (with|using) (corners|vertices|vertexes|points) %number% with radius %number%[[( and|,)] [with] angle %-number% degree[s]][[( and|,)] with [rotation] %-number% degree[s] [angle] [using origin location %-number%,[ ]%-number%]] on [(image|img)] %object% [at [[center] location] %-number%,[ ]%-number%] [[and] (store|save) ([[the] result]|it) (in|to) [variable] %-object%]
draw [a[n]] (oval|ellipse) [(outline [with width %-number%])] with (horizontal radius %-number%[( and|,)] [with] vertical radius %-number%|vertical radius %-number%[( and|,)] [with] horizontal radius %-number%)[[( and|,)] [with] [(paint|gradient)] %-object%][[( and|,)] [with] [rotation] %-number% degree[s] [angle] [using origin location %-number%,[ ]%-number%]] on [(image|img)] %object% [at [[center] location] %-number%,[ ]%-number%] [[and] (store|save) ([[the] result]|it) (in|to) [variable] %-object%]
(save|write) [(image|img)] %object% to [file] %string%
write [[(image|img)] (text|string) [(with (id|name)|named)]] %string% (on|to) [(image|img)] %object% [at [location] %-number%,[ ]%-number%] [with [rotation] %-number% degree[s] [angle] [using origin location %-number%,[ ]%-number%]] [[and] (store|save) ([[the] result]|it) (in|to) [variable] %-object%]
upload [the] [last[ly]] [(created|generated|received|taken)] (image|img) [with ([(format|file)] type|[file] format) %-string%] [with (message|embed) %-message/string%] to %user/channel% [with %bot/string%]
(draw|merge) [(image|img)] %object% (on|with) [(image|img)] %object% [at [location] %-number%,[ ]%-number%] [with [rotation] %-number% degree[s] [angle] [using origin location %-number%,[ ]%-number%]] [[and] (store|save) ([[the] result]|it) (in|to) [variable] %-object%]
draw [a] rounded rectangle [(outline [with width %-number%])] with arc[h] height %-number%[( and|,)] [with] width %-number% with [rectangle] (width %-number%[( and|,)] [with] height %-number%|height %-number%[( and|,)] [with] width %-number%)[[( and|,)] [with] [(paint|gradient)] %-object%][[( and|,)] [with] [rotation] %-number% degree[s] [angle] [using origin location %-number%,[ ]%-number%]] on [(image|img)] %object% [at [location] %-number%,[ ]%-number%] [[and] (store|save) ([[the] result]|it) (in|to) [variable] %-object%]
imagesk warning %string%
make mask on [(image|img)] %object% using [(image|img)] %object% [[and] (store|save) ([[the] result]|it) (in|to) [variable] %-object%]
(get|extract) part of [(image|img)] %object% (from [location] %-number%,[ ]%-number% to [location] %-number%,[ ]%-number%|between locations %-number%,[ ]%-number% and %-number%,[ ]%-number%) [and] (store|save) ([[the] result]|it) (in|to) [variable] %-object%
round [(image|img)] %object% with arc[h] (width %-number%[( and|,)] [with] height %-number%|height %-number%[( and|,)] [with] width %-number%) [[and] (store|save) ([[the] result]|it) (in|to) [variable] %-object%]
make [(image|img)] %object% masked by [(image|img)] %object% [[and] (store|save) ([[the] result]|it) (in|to) [variable] %-object%]
draw [a] line [(with ((flat|square) (cap|edge[s])))] [with width %-number%][[( and|,)] [with] [(paint|gradient)] %-object%][[( and|,)] [with] [rotation] %-number% degree[s] [angle] [using origin location %-number%,[ ]%-number%]] on [(image|img)] %object% (from [location] %-number%,[ ]%-number% to %-number%,[ ]%-number%|between locations %-number%,[ ]%-number% and %-number%,[ ]%-number%) [[and] (store|save) ([[the] result]|it) (in|to) [variable] %-object%]
upload (image|img) %object% [with ([(format|file)] type|[file] format) %-string%] [with (message|embed) %-message/string%] to %user/channel% [with %bot/string%]
draw [a] rounded rectangle [(outline [with width %-number%])] with arc[h] (width %-number%[( and|,)] [with] height %-number%|height %-number%[( and|,)] [with] width %-number%) with [rectangle] width %-number%[( and|,)] [with] height %-number%[[( and|,)] [with] [(paint|gradient)] %-object%][[( and|,)] [with] [rotation] %-number% degree[s] [angle] [using origin location %-number%,[ ]%-number%]] on [(image|img)] %object% [at [location] %-number%,[ ]%-number%] [[and] (store|save) ([[the] result]|it) (in|to) [variable] %-object%]
create [a[n]] [new] image with (width %-number%[( and|,)] [with] height %-number%|height %-number%[( and|,)] [with] width %-number%)[[( and|,)] [with] [b[ack]g[round]] [(paint|gradient)] %-object%] [[and] (store|save) ([[the] result]|it) (in|to) [variable] %-object%]
draw [a[n]] circle [(outline [with width %-number%])] with (radius|size) %number%[[( and|,)] [with] [(paint|gradient)] %-object%][[( and|,)] [with] [rotation] %-number% degree[s] [angle] using origin location %-number%,[ ]%-number%] on [(image|img)] %object% [at [[center] location] %-number%,[ ]%-number%] [[and] (store|save) ([[the] result]|it) (in|to) [variable] %-object%]
make [(image|img)] %object% rounded with arc[h] (width %-number%[( and|,)] [with] height %-number%|height %-number%[( and|,)] [with] width %-number%) [[and] (store|save) ([[the] result]|it) (in|to) [variable] %-object%]
[fully] round [(image|img)] %object% [[and] (store|save) ([[the] result]|it) (in|to) [variable] %-object%]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffContinue
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
continue [if (%-boolean%|<.+>)]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffDelayEffect
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
delay [the] [current] effect
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffExpressionStatement
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[(await)] %~javaobject%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffImport
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
import <((?:[_a-zA-Z$][\w$]*\.)*(?:[_a-zA-Z$][\w$]*))(?:\s+as ([_a-zA-Z$][\w$]*))?>
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffNegateCondition
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
negate [the] [current] condition
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
 
---
 
### EffReturn
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
return [%-objects%]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
## Expressions
 
### CustomExpression
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[a] [new] [(repeating|reflected)] (radial|circular) gradient with %objects%[(,| and)] [with] (horizontal radius %-number%[( and|,)] [with] vertical radius %-number%|vertical radius %-number%[( and|,)] [with] horizontal radius %-number%)[[(,| and)] [with] (fraction|distribution)s %-numbers%] at [center] [location] %-number%,[ ]%-number% [using (start|focus) location %-number%,[ ]%-number%]
([f[ore]g[round]]|b[ack]g[round]|outline) (colo[u]r|paint|gradient) of [[(image|img)] (text|string)] %string%
(copied|cloned) [image[s]] %objects%
[a] [new] [(repeating|reflected)] (radial|circular) gradient with %objects%[(,| and)] [with] radius %-number%[[(,| and)] [with] (fraction|distribution)s %-numbers%] at [center] [location] %-number%,[ ]%-number% [using (start|focus) location %-number%,[ ]%-number%]
[the] [colo[u]r of] pixel [at [location]] %number%,[ ]%number% of %objects%
[the] [last[ly]] [(created|generated|received|taken)] (image|img)
[(image|img)] colo[u]r [from] (%-color%|[hex] %-string%|[rgb[ ]][(]%-number%, %-number%, %-number%[)])[[,] [with] (opacity|transparency) %-number% [percent]))]
((content|text|string)|font[[( |-)]family]) of [[(image|img)] (text|string)] %string%
[(all [[of] the]|the)] (image|img) (text|string)s
size of [[(image|img)] (text|string)] %string%
outline (width|size) of [[(image|img)] (text|string)] %string%
%object%'s [(image|img)] [(text|string)] (width|height|ascent|descent)
[the] (opacity|transparency) of %objects%
[a] (cop(y|ies)|clone[s]) of [image[s]] %objects%
base[ ]64 encoded [(image|img)] %object% [with ([(format|file)] type|[file] format) %-string%]
%color% with (opacity|transparency) %number% [percent]
[(image|img)] [(text|string)] %object%'s (width|height|ascent|descent)
%objects%'[s] [colo[u]r of] pixel [at [location]] %number%,[ ]%number%
[the] (width|height|ascent|descent) of [(image|img)] [(text|string)] %object%
(bold|italic|underline[d]|strikethrough|outline[d]|(only|just) outline) [state] of [[(image|img)] (text|string)] %string%
[the] (image|img) (text|string) [((with|from) (id|name)|named)] %string%
[the] [(image|img)] [(text|string)] (width|height|ascent|descent) of %object%
[a] [new] [((repeating|repeated)|(reflected|reflecting))] linear gradient with %objects%[[(,| and)] [with] (fraction|distribution)s %-numbers%] (from [location] %-number%,[ ]%-number% to %-number%,[ ]%-number%|between locations %-number%,[ ]%-number% and %-number%,[ ]%-number%)
[(all [[of] the]|the)] [available] fonts
%objects%'[s] (opacity|transparency)
[(all [[of] the]|the)] [available] font (families|[family] names)
colo[u]rs %objects%
%objects%'[s] (cop(y|ies)|clone[s])
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
 
### ExprArrayAccess
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
%javaobject%\[%number%\]
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
  <td>set and delete</td>
</table>
 
---
 
### ExprBits
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] (bit %-number%|bit(s| range) [from] %-number%( to |[ ]-[ ])%-number%) of %numbers%
%numbers%'[s] (bit %-number%|bit(s| range) [from] %-number%( to |[ ]-[ ])%-number%)
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
  <td>unknown</td>
</table>
 
---
 
### ExprChangeValue
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] change value[(s)]
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
 
### ExprCollect
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
\[%objects%[ as %-javatype%[ ]]\]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>javaobject</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### ExprEvent
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] event
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>event</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### ExprEventClasses
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
event-classes
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>javatype</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### ExprExpression
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] expr[ession][(s)](-| )<\d+>
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
 
### ExprFunction
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] function(s| [reference[s]]) %strings% [called with [[the] [arg[ument][s]]] %-objects%]
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
 
### ExprJavaCall
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[(try)] %object%..%string%(!|([%-objects%]))
[(try)] %object%.<[^!(]*[^!(\s]>(!|([%-objects%]))
[(try)] [a] new %javatype%([%-objects%])
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
 
### ExprJavaError
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] [last] [java] (throwable|exception|error)
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
 
### ExprJavaType
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] [java] class %string%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>javatype</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### ExprJavaTypeOf
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] [java] class[es] of %objects%
%objects%'[s] [java] class[es]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>javatype</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### ExprMatchedPattern
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] [matched] pattern
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
 
### ExprMemberNames
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] (field|method) names of %objects%
%objects%'[s] (field|method) names
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
 
### ExprMembers
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] (fields|methods|constructors) of %objects%
%objects%'[s] (fields|methods|constructors)
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
 
### ExprParseMark
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] [parse[r]] mark
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
 
### ExprParseRegex
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] [parse[r]] (regex|regular expression)(-| )<\d+>
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
 
### ExprProxy
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[a] [new] proxy [instance] of %javatypes% (using|from) %objects%
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
 
### ExprRawExpression
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] raw %objects%
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
 
### ExprSpread
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
...%object%
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
 
### ImportHandler
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
Variable
Point
LinkedList
CycleMethod
Point2DDouble
Color
AffineTransform
RadialGradientPaint
ColorSpaceType
BasicStroke
AlphaComposite
BufferedImage
RenderingHints
EmbedBuilder
User
MessageBuilder
UpdatingMessage
ByteArrayInputStream
Vixio
VixioUtil
ByteArrayOutputStream
RateLimitedException
ImageIO
LiteralList
SimpleLiteral
Polygon
Variables
Base64
Skript
Paint
Bukkit
Math
SkriptColor
String
Font
RoundRectangle2DDouble
AttributedString
TextAttribute
JavaFile
LinearGradientPaint
Image
Path
Paths
Files
URL
Line2DFloat
GraphicsEnvironment
ScriptLoader
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>javatype</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### LitNullObject
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
null
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>null</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>