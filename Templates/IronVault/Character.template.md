```iron-vault-character-info
```

# Sections

```table-of-contents
title: 
style: nestedList # TOC style (nestedList|nestedOrderedList|inlineFirstLevel)
minLevel: 0 # Include headings from the specified level
maxLevel: 0 # Include headings up to the specified level
include: 
exclude: 
includeLinks: true # Make headings clickable
hideWhenEmpty: false # Hide TOC if no headings are found
debugInConsole: false # Print debug info in Obsidian console
```

# --- Iron Vault Mechanics

## Stats
[[#Sections|Top]]
```iron-vault-character-stats
```
```iron-vault-character-meters
```

## Progress
[[#Sections|Top]]

### Combat table
[[#Sections|Top]]
```base
formulas:
  Progress %: progress*100/40
views:
  - type: table
    name: Table
    filters:
      and:
        - file.folder == "Progress"
        - note["track-type"] == "Combat"
        - character == this.file
        - file.tags.contains("incomplete")
    order:
      - file.name
      - rank
      - formula.Progress %

```

---

### Connections table
[[#Sections|Top]]
```base
formulas:
  Progress %: progress*100/40
views:
  - type: table
    name: Table
    filters:
      and:
        - file.folder == "Progress"
        - note["track-type"] == "Connection"
        - character == this.file
        - file.tags.contains("incomplete")
    order:
      - file.name
      - rank
      - formula.Progress %

```

---

### Delve table
[[#Sections|Top]]
```base
formulas:
  Progress %: progress*100/40
views:
  - type: table
    name: Table
    filters:
      and:
        - file.folder == "Progress"
        - note["track-type"] == "Delve"
        - character == this.file
        - file.tags.contains("incomplete")
    order:
      - file.name
      - rank
      - formula.Progress %

```

---

### Explore table
[[#Sections|Top]]
```base
formulas:
  Progress %: progress*100/40
views:
  - type: table
    name: Table
    filters:
      and:
        - file.folder == "Progress"
        - note["track-type"] == "Explore"
        - character == this.file
        - file.tags.contains("incomplete")
    order:
      - file.name
      - rank
      - formula.Progress %

```

---

### Scene Challenges table
[[#Sections|Top]]
```base
formulas:
  Progress %: progress*100/40
views:
  - type: table
    name: Table
    filters:
      and:
        - file.folder == "Progress"
        - note["track-type"] == "Scene Challenge"
        - character == this.file
        - file.tags.contains("incomplete")
    order:
      - file.name
      - rank
      - formula.Progress %

```

---

### Vows table
[[#Sections|Top]]
```base
formulas:
  Progress %: progress*100/40
views:
  - type: table
    name: Table
    filters:
      and:
        - file.folder == "Progress"
        - note["track-type"] == "Vow"
        - character == this.file
        - file.tags.contains("incomplete")
    order:
      - file.name
      - rank
      - formula.Progress %

```

---

## Clocks
[[#Sections|Top]]

###### Open Clocks
[[#Sections|Top]]
```base
formulas:
  Progress %: progress*100/segments
views:
  - type: table
    name: Table
    filters:
      and:
        - file.folder == "Clocks"
        - file.tags.contains("incomplete")
    order:
      - file.name
      - rank
      - formula.Progress %

```

---

## Impacts
[[#Sections|Top]]
```iron-vault-character-impacts
```

---

## Specials
[[#Sections|Top]]
```iron-vault-character-special-tracks
```

---

## Assets
[[#Sections|Top]]
```iron-vault-character-assets
```

---

## Inventory
[[#Sections|Top]]

- Item 1
- Item 2

---

# --- Narrative
[[#Sections|Top]]

> [!multi-column|no-title]
> 
>> [!cite|no-title] 
>> Insert photo here.
>
>> [!cite|no-title clean]
>> ![[#General Info|no-title clean]]

## General Info
**Name:** ==`=this.name`==
**Height:** ==1.8m==
**Weight:** ==80kg==
**Eye color:** ==Blue==
**Hair color:** ==Sandy brown==
**Affiliation:** ==Pirate==
**Rank:** ==rank, or n/a==
**Species:** ==Human==
**Era:** ==n/a==
**Gender:** ==Male==

%%---%%

## Appearance
%% 
> [!note]- Appearance 
> Essentially a boxed text description that you can use when the PCs meet the the NPC for the first time. Get it pithy. 1-2 sentences is the sweet spot. Three sentences is pretty much the maximum length you should use unless there is something truly and outrageously unusual about the character. Remember that you don’t need to describe every single thing about them: Pick out their most interesting and unique features and let your players’ imaginations paint in the rest. 
%% 



---

## First Impression
%%
> [!note]- First Impressions
> Nothing at this time.
%%

First Impression.

---

## Quote 
%%
>[!info]- Quote
>I don’t always use this entry, but a properly crafted quote can be a very effective way to quickly capture the NPC’s unique voice. Generally speaking, though, all you want is a single sentence. You should be able to basically glance at it and grok the voice. (Special exception if the character’s voice is “rambling old man”.) 
%% 
Quote. (or two)

---

## Motivations
%%
> [!note]- Motivations
> Nothing at this time.
%%



---

## Roleplaying
%%
> [!note]- Roleplaying
> This is the heart of the template, but it should also be the shortest section. Two or three brief bullet points at most. You’re looking to identify the essential elements which will “unlock” the character for you.
> 
> There are no firm rules here, but I will always try to include at least one simple, physical action that you can perform while playing the character at the table. For example, maybe they tap their ear. Or are constantly wearing a creepy smile. Or they arch their eyebrow. Or they speak with a particular accent or affectation. Or they clap their hands and rub them together. Or snap their fingers and point at the person they’re talking to. Or make a point of taking a slow sip from their drink before responding to questions.
> 
> You don’t have to make a big deal of it and it usually won’t be something that you do constantly (that gets annoying), but this mannerism is your hook: You’ll find that you can quickly get back into the character by simply performing the mannerism. It will make your players remember the NPC as a distinct individual. And it can even make playing scenes with multiple NPCs easier to run (because you can use the mannerisms to clearly distinguish the characters you’re swapping between).
> 
> You’ll generally only need one mannerism. Maybe two. More than that and you lose the simple utility of the mannerism in unnecessary complexity. It’s not that the character’s entire personality is this one thing; it’s that the rest of the character’s personality will flow out of you whenever you hit that touchstone.
> 
> Round this out with personality traits and general attitude. Are they friendly? Hostile? Greedy? Ruthless? Is there a particular negotiating tactic they like? Will they always offer you a drink? Will they fly into a rage if insulted? But, again, keep it simple and to the point. You want to be able to glance at this section, process the information almost instantaneously, and start playing the character. You don’t need a full-blown psychological profile and, in fact, that would be counterproductive. 
%%



---

## Background
%%
> [!note]- Background
> This section is narrative in nature. You can let it breathe a bit more than the other sections if you’d like, but a little will still go a long way. I tend to think of this in terms of essential context and interesting anecdotes. Is it something that will directly influence the decisions they make? Is it information that the PCs are likely to discover about them? Is it an interesting story that the NPC might tell about themselves or (better yet) use as context for explaining something? Great. If it’s just a short story about some random person’s life that you’re writing for an audience of one, refocus your attention on prepping material that’s relevant to the players.
%%



---

## Key Info
%% 
> [!note]- Key Info
> In bullet point format, lay out the essential interaction or information that the PCs are supposed to get from the NPC. The nature of this section will vary depending on the scenario and the NPC’s role in it, but the most obvious example is a mystery scenario in which the NPC has a clue. Rather than burying that clue in the narrative of the NPC’s background, you’re yanking it and placing it in a list to make sure you don’t lose track of it during play. (The Three Clue Rule applies, of course, so just because something appears in this section it doesn’t mean that the PCs are automatically going to get it.)
>
> You could also use this section to lay out the terms of employment being offered by the Mysterious Man in the Tavern. Or to list the discounts offered by a shopkeeper. It’s a flexible tool. In some cases, it might get quite long. But try to keep it well-organized (using the bullet points will help with that). If it just becomes a giant wall of text, its purpose has been lost.
%%

- Key Info

---

# --- Bookkeeping

## Open Items
```base
formulas:
  Progress %: progress*100/40
views:
  - type: table
    name: Table
    filters:
      and:
        - file.folder == "Progress"
        - character == this.file
    order:
      - file.name
      - rank
      - formula.Progress %
      - track-type
    sort:
      - property: track-type
        direction: ASC
      - property: progress
        direction: ASC
      - property: file.name
        direction: ASC

```
[[#Sections|Top]]

---

## All Clocks
```base
formulas:
  Progress %: progress*100/segments
views:
  - type: table
    name: Table
    filters:
      and:
        - file.folder == "Clocks"
    order:
      - file.name
      - rank
      - formula.Progress %
    sort:
      - property: track-type
        direction: ASC
      - property: progress
        direction: ASC
      - property: file.name
        direction: ASC

```
[[#Sections|Top]]

---

# --- Notes
## Note 1
