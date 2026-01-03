The file that has the Iron Vault commands.

(m)  = mechanic, used in mechanics notekeeping
(o) = oracle, used in questions/answers


The commands are:
- advanceclock
- ask (o)
- at (o)
- burnmom (m)
- chars (m)
- chars add (m)
- chars rename (m)
- chars reduce (m)
- chaos (m)
- chaos++ (m)
- chaos-- (m)
- chaos set (m)
- commands (m)
- occ (m)
- createadventure (m)
- createclock (m)
- createprogress (m)
- df (o)
- endprogress (m)
- endscene (m)
- event (o)
- init (m)
- markprogress (m)
- mechanic (m)
- move (m)
- note (m)
- oracle (o)
- ptp (m)
- ref (m)
- roll (o)
- suffer (m)
- take (m)
- plots (m)
- plots add (m)
- plots choose (m)
- plots rename (m)
- plots random (m)
- plots reduce (m)
- vows (m)
- vows add (t)
- yesno (o)


To list the commands available to script, open the console (shift-ctrl-i), then `app.commands.commands;`

- move: 'iron-vault:make-a-move'
- changeinit: 'iron-vault:'
- commands: 'iron-vault:show-all-commands'
- createclock: iron-vault:clock-create
- advanceclock: iron-vault:clock-advance
- resolveclock:
- createprogress:
- markprogress:
- completeprogress:
- burnmom: 'iron-vault:burn-momentum'
- suffer: 'iron-vault:suffer-meter'
- take: 'iron-vault:take-meter'
- reroll: 'iron-vault:reroll-die'
- ask: 'iron-vault:ask-the-oracle'

## advanceclock
__
```
^advanceclock$
```
__
```js
app.commands.executeCommandById('iron-vault:clock-advance');
```
__
***

## ask
__
```
^ask$
```
__
```js
app.commands.executeCommandById('iron-vault:ask-the-oracle');
```
__
***
## changeinit
__
```
^changeinit$
```
__
```js
app.commands.executeCommandById('iron-vault:character-change-initiative');
```
__
***
## createclock
__
```
^createclock$
```
__
```js
app.commands.executeCommandById('iron-vault:clock-create');
```
__
***

## commands
__
```
^commands$
```
__
```js
app.commands.executeCommandById('iron-vault:show-all-commands');
```
__
***
## createprogress
__
```
^createprogress$
```
__
```js
app.commands.executeCommandById('iron-vault:progress-create');
```
__

***


## endprogress
__
```
^endprogress$
```
__
```js
app.commands.executeCommandById('iron-vault:progress-complete');
```
__
***


## markprogress
__
```
^markprogress$
```
__
```js
app.commands.executeCommandById('iron-vault:progress-advance');
```
__
***
## move
__
```
^move$
```
__
```js
app.commands.executeCommandById('iron-vault:make-a-move');
```
__
***


## occ
__
```js
^occ$
```
__
```js
app.commands.executeById('iron-vault:insert-comment');
```
__
***

## resolveclock
__
```
^resolveclock$
```
__
```js
app.commands.executeCommandById('iron-vault:clock-resolve');
```
__
***

## suffer
__
```
^suffer$
```
__
```js
app.commands.executeCommandById('iron-vault:suffer-meter');
```
__
***

## take
__
```
^take$
```
__
```js
app.commands.executeCommandById('iron-vault:take-meter');
```
__
***
## yesno
__
```
^yesno ?(|-4|-3|-2|-1|0|1|2|3|4|5|6) (.+)$
```
__
```js
// Nothing yet.
app.ex
expand("fate $1");
question  = $2;
```
__
yesno {probability: -4 to 6} {question: text} - Ask the oracle

***

