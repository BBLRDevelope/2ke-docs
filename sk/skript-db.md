## Summary
  * [Effects](#effects)
  * [Expressions](#expressions)
 
## Effects
 
### EffExecuteStatement
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
execute %string% (in|on) %datasource% [and store [[the] (output|result)[s]] (to|in) [the] [var[iable]] %-objects%]
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
</table>
## Expressions
 
### ExprDBError
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] [last] (sql|db|data(base|[ ]source)) error
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
 
### ExprDataSource
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
[the] data(base|[ ]source) [(of|at)] %string%
```
 
</p></details>
<p>
</p>
<table>
  <th><div title="Since which version it was added.">Since</div></th>
  <td>1.0</td>
  <th><div title="What type it returns">Return type</div</th>
  <td>datasource</td>
  <th><div title="The possible modifiers that this expression accepts."><a href="http://bensku.github.io/Skript/effects.html#EffChange">Changers</a></div></th>
  <td>none</td>
</table>
 
---
 
### ExprUnsafe
No description available yet.
 
**No examples available yet.**
<details><summary>Syntaxes</summary><p>
 
```java
unsafe %string%
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