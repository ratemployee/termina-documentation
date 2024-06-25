---
world: faerun
campaign: faerun
status: active
role: player
system: 5e
type: world
---
# The World of faerun

## Player Characters

- [[misery]]
- [[buckwheat]]
- [[calvin]]

- [[lhaer]]
- [[saturn]]
- [[eo]]
- [[legion]]
- [[tontra]]
- [[paarthurnax]]
- [[elizabeth]]

## Sessions

*Put your cursor where the session link should be. Then, from the Command Palette (CMD/CTRL+P), select either QuickAdd: Macro - Add session-player or QuickAdd: Macro - Add session-gm*.

[[005_20230916]]


```dataview
table summary as "Summary" from "ttrpgs/faerun"
where contains(type,"session")
SORT sessionNum ASC
```


## Truths about the campaign/world

*Write down some facts about this campaign or the world that the characters find themselves in.*

- 


## Factions

```dataview
TABLE description as "Description" from "ttrpgs/faerun"
WHERE contains(lower(type),"faction")
```

## Custom rules

- [[Character options]]
- [[House rules]]

## [[Safety Tools]]