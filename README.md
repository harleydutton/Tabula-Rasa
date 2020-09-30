# Tabula-Rasa
## About
This README is not intended to be part of Tabula Rasa. Instead it is a meta-document for tracking design, philosophy, formatting, and tasks. Created by Harley Dutton.

Tabula Rasa is a worldbuilding framework and a rules-light, generic roleplaying game that lets players create their own skills.

The worldbuilding framework produces a Setting. Settings are short, standardized, and easily sharable descriptions of a single place within a world. The intent is that Settings can be used to quickly understand a part of the world such that a player can create a Character or the Storyteller can create an Adventure.

The roleplaying system is generic so it will work with any Setting produced by the worldbuilding framework. The rules are minimal meaning you and your group should be able to create any character imaginable within the setting and start playing very quickly!

## Philosophy
- plays fast
- players make skills
- generic
- low entry barrier
- short
- not preachy
- fun > balance/realism
- avoid math/book-keeping
- DRY using links; otherwise printable
- avoid charts/tables (source material. illustrations okay)

| In Scope           | Out of Scope                                      |
| ------------------ | ------------------------------------------------- |
| character creation | story/adventure template                          |
| rolling checks     | probability charts                                |
| settings           | source material                                   |
| combat mechanics   | forming the PC party                              |
| setting creation   | tips sections (single, tabula-specific tips okay) |
|                    |                                                   |
|                    |                                                   |

### Outstanding problems
DEATH BY FLAVOR: When does a character die? (when they gain a flavor that would kill them. use DTMS checks) When they have a certain number of bad flavors? (no, not by number) Who determines what flavor can be added to a character? (called shots, the player) Perhaps we should just have health? (no) How do you determine when a character has accumulated enough flavor that they are unconscious or dead? (DTMS check) This can probably be solved by saying the difficulty for giving immediately lethal flavor will usually be high against non-mooks unless you have silver bullets. Unconscious, sleeping, incapacitated, downed, etc. characters can be killed outright. When a character achieves the downed status from wounds is based on a DTMS check I guess? Not having source material makes combat messy... When moving is non-trivial (on the trivial, easy, normal, hard, impossible subjective check difficulty scale) a character is downed? When attacking is impossible a character can be considered impotent/incapacitated and initiative can be dropped.

## To Do
- **Thoughts**
  - is the map section in distance useful?
  - do I need an equipment bulk system?
  - do I need a fatigue system?
  - the character and character creations settings are largely redundant. make them different or remove one.
    - maybe to complement "systems" have another top level section called "definitions". split the parts out of character and setting but still include character and setting and have them reference the smaller sections now. To some degree this is a bad idea because it implies that I should move the things I have defined in each subsection into it and that is crappy organization.
- **Distance**
  - rename battlefields to something less combat oriented
  - switch the distance and movement sections. make it clear in the distance section that the system does not determine weapon ranges or the like
- **Timing**
- **Hidden Information**
  - rename unsuspicious to oblivious
  - rename undetected to hidden
  - I should make it clear that undetectable is not a state but rather a difficulty modifier in this system. context: invisible rogue and guard who may or may not have true sight.
- **skills?**
  - On the subject of ordering, all actions must be able to be reacted to. Do they though? Shooting?
- **combat**
  - actions
    - In addition all reactions occur after the action that caused them.
    - add running to actions (by converting a major to a move)
    - define more free actions. possibly convert some to minor actions
    - consider renaming move action minor action and defining some minor actions
    - extended (multiple turn) actions?
  - damage
    - characters cannot deal flavor amounting to instant death to anyone except mooks. 
    - does the attacking section need subsections?
    - characters can deal "dying" at typical difficulty of hard. 
    - Stripping defences is normal difficulty. 
    - Making an attack hard to evade is difficulty hard. 
    - after defences are stripped dealing dying/death can be done at normal difficulty.
    - Anyway, I suppose I should give some suggestions on how to create compelling puzzle bosses much the same way I give suggestions on how to create skills in the player section. Zelda bosses are good sources of inspiration and I recently saw an episode of critical role with ghosts who had their souls in breakable jars around the room.
- **influence**
  - try to combine mental and social influence.
- **setting**
  - add an example image/table for the store
  - add an example image for a whole setting doc
- **Character Creation**
  - reduce the "character creation" section and add sections to "character" (really just move them and refine both) (at this point just double check that character has definitions for everything it needs to have defs for.)
  - flavor cannot point to a specific skill. If a flavor boils down to "+1 to a skill" or "X skill is easy for me" it isn't really flavor. Instead it should have many ups and downs and they should be situational.
  - at skill/flavor creation, discuss power level as a limiting factor. it should be a consideration at the least.
  - at skill/flavor creation, discuss the typical use case and difficulty.
  - add an example to scope: fireball, fire magic, magic
- **feedback**
  - which terms need to go in the glossary. does the glossary need to exist?
  - where do we need example images, charts, or descriptions?
  - define skills better. Heuristic: skills allow you to *do*
  - define flavor better. Heuristic: flavor represents thing you *are* or *have*
- **formatting**
  - format things using legend
  - put headings in title case
  - hyperlink the first reference to a section in every section
- **polish**
  - make the voice consistent ie. always speak to player
  - link things
  - add grammar check plugin (or just run a grammar check?)
  - make the images non-shit
  - export as PDF

## formatting options
<!--html style comment-->
_italics_  
__bold__  
___both___  
~~strikethrough~~  
`monospace`  
```
monospace blocks
```
> block quotes
>> are nestable  
***
[Links](#formatting-options)
1. ordered
2. list   
- unordered
- list   
