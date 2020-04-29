# Druid Macros


## Caster

Cancel Form
```
/cancelform [noform:1/3]
/cast [form:1] Dire Bear Form
/cast [form:3] Cat Form
```
Note: the above will only let you leave form when you are off the GCD.  The general idea is that leaving bear/cat should only be done when you can do somthing else on the same GCD.

Abolish Poison
```
#showtooltip Abolish Poison
/stand
/dismount
/cancelform [noform:1/3]
/cast [form:1] Dire Bear Form
/cast [form:3] Cat Form
/cast [@mouseover, help][@target, help][@targettarget, help][@player] Abolish Poison
```

Remove Curse
```
#showtooltip Remove Curse
/stand
/dismount
/cancelform [noform:1/3]
/cast [form:1] Dire Bear Form
/cast [form:3] Cat Form
/cast [@mouseover, help][@target, help][@targettarget, help][@player] Remove Curse
```

Rebirth
```
#showtooltip Rebirth
/stand
/dismount
/cancelform [noform:1/3]
/cast [form:1] Dire Bear Form
/cast [form:3] Cat Form
/cast [@mouseover, help][@target, help][@targettarget, help] Rebirth
```

Innervate
```
#showtooltip Innervate
/stand
/dismount
/cancelform [noform:1/3]
/cast [form:1] Dire Bear Form
/cast [form:3] Cat Form
/cast [@mouseover,help][] Innervate
```

Hurricane
```
#showtooltip Hurricane
/stand
/dismount
/cancelform [noform:1/3]
/cast [form:1] Dire Bear Form
/cast [form:3] Cat Form
/cast [@cursor] Hurricane
```

Tranquility
```
#showtooltip Tranquility
/stand
/dismount
/cancelform [noform:1/3]
/cast [form:1] Dire Bear Form
/cast [form:3] Cat Form
/cast Tranquility
```

Faerie Fire (any form)
```
#showtooltip Faerie Fire (Feral)
/stand
/dismount
/cast [form:1/3, @mouseover, harm][form:1/3, @target, harm] Faerie Fire (Feral); [noform, @mouseover, harm][noform, @target, harm] Faerie Fire
```

Mark of the Wild
```
#showtooltip Mark of the Wild
/stand
/dismount
/cancelform [noform:1/3]
/cast [form:1] Dire Bear Form
/cast [form:3] Cat Form
/cast [@mouseover, help][@target, help][@targettarget, help][@player] Mark of the Wild
```

Gift of the Wild
```
#showtooltip Mark of the Wild
/stand
/dismount
/cancelform [noform:1/3]
/cast [form:1] Dire Bear Form
/cast [form:3] Cat Form
/cast [@mouseover, help][@target, help][@targettarget, help][@player] Gift of the Wild
```

Thorns
```
#showtooltip Thorns
/stand
/dismount
/cancelform [noform:1/3]
/cast [form:1] Dire Bear Form
/cast [form:3] Cat Form
/cast [@mouseover, help][@target, help][@targettarget, help][@player] Thorns
```

Nature's Grasp
```
#showtooltip Nature's Grasp
/stand
/dismount
/cancelform [noform:1/3]
/cast [form:1] Dire Bear Form
/cast [form:3] Cat Form
/cast Nature's Grasp
```

Nature's Swiftnes
```
#showtooltip Nature's Swiftnes
/stand
/dismount
/cancelform [noform:1/3]
/cast [form:1] Dire Bear Form
/cast [form:3] Cat Form
/cast Nature's Swiftness
```

Travel Form OR Aquatic Form
```
#showtooltip Travel Form
/stand
/dismount
/cast [form:3] Cat Form
/cast [form:1] Dire Bear Form
/cast [swimming] Aquatic Form; [noswimming] Travel Form
```

Shadowmeld
```
#showtooltip Shadowmeld(Racial)
/stand
/dismount
/cancelform [noform:1/3]
/cast [form:1] Dire Bear Form
/cast [form:3] Cat Form
/cast Shadowmeld(Racial)
```

R4  Healing Touch
```
#showtooltip
/stand
/dismount
/cancelform [noform:1/3]
/cast [form:1] Dire Bear Form
/cast [form:3] Cat Form
/cast [@mouseover, help][@target, help][@targettarget, help][@player]  Healing Touch(Rank 4)
```

HELP Regrowth or HARM Starfire
```
#showtooltip
/stand
/dismount
/cancelform
/cast [@mouseover,help,nodead] Regrowth; [@mouseover,harm,nodead] [harm] Starfire; Regrowth
```

HELP R4 Regrowth or HARM Wrath
```
#showtooltip
/stand
/dismount
/cancelform [noform:1/3]
/cast [form:1] Dire Bear Form
/cast [form:3] Cat Form
/cast [@mouseover,help,nodead] Regrowth(Rank 4); [@mouseover,harm,nodead] [harm] Wrath; Regrowth(Rank 4)
```

Max Rank Rejuvenation
```
#showtooltip
/stand
/dismount
/cancelform [noform:1/3]
/cast [form:1] Dire Bear Form
/cast [form:3] Cat Form
/cast [@mouseover,help,nodead] Rejuvenation; Rejuvenation
```

HELP R4 Rejuvenation or HARM Insect Swarm
```
#showtooltip
/stand
/dismount
/cancelform [noform:1/3]
/cast [form:1] Dire Bear Form
/cast [form:3] Cat Form
/cast [@mouseover,help,nodead] Rejuvenation(Rank 4); [@mouseover,harm,nodead] [harm] Insect Swarm; Rejuvenation
```

HELP R6 Rejuvenation or HARM Moonfire
```
#showtooltip
/stand
/dismount
/cancelform [noform:1/3]
/cast [form:1] Dire Bear Form
/cast [form:3] Cat Form
/cast [@mouseover,help,nodead] Rejuvenation(Rank 4); [@mouseover,harm,nodead] [harm] Moonfire; Rejuvenation(Rank 4)
```


## Cat

Cat Form with Powershift
```
#showtooltip Cat Form
/dismount
/stand
/cancelform [noform:1/3]
/cast [form:1] Dire Bear Form
/cast [form:3] Cat Form
/cast [noform:3] Cat Form
```

Dash
```
#showtooltip Dash
/stand
/dismount
/cancelform [noform:1/3]
/cast [form:1] Dire Bear Form
/cast [noform:3] Cat Form
/cast Dash
```

Prowl
```
#showtooltip Prowl
/stand
/dismount
/cancelform [noform:1/3]
/cast [form:1] Dire Bear Form
/cast [noform:3] Cat Form
/cast !Prowl
```

Ravage & Shred
```
#showtooltip
/stand
/dismount
/startattack [nostealth]
/cast [stealth] Ravage; [nostealth] Shred
```

Claw
```
#showtooltip
/stand
/dismount
/startattack
/cast Claw
```

100% Safe Cat Consumable or Item Use Macro Example
```
#showtooltip
/dismount
/stand
/cancelform [noform:1/3]
/cast [form:1] Dire Bear Form
/cast [form:3] Cat Form
/use Major Mana Potion
/cast [noform:3] Cat Form
```

## Bear Form

Dire Bear Form with Powershift
```
#showtooltip Dire Bear Form
/dismount
/stand
/cancelform [noform:1/3]
/cast [form:1] Dire Bear Form
/cast [form:3] Cat Form
/cast [noform:1] Dire Bear Form
```

Challenging Roar
```
#showtooltip Challenging Roar
/stand
/dismount
/cancelform [noform:1/3]
/cast [form:3] Cat Form
/cast [noform:1] Dire Bear Form
/cast Challenging Roar
```

Growl
```
#showtooltip Growl
/stand
/dismount
/cancelform [noform:1/3]
/cast [form:3] Cat Form
/cast [noform:1] Dire Bear Form
/cast [@mouseover, harm, nodead, form:1][@target, harm, nodead, form:1] Growl
```

Feral Charge
```
#showtooltip Feral Charge
/stand
/dismount
/cancelform [noform:1/3]
/cast [form:3] Cat Form
/cast [noform:1] Dire Bear Form
/cast [@mouseover, harm, nodead, form:1][@target, harm, nodead, form:1] Feral Charge
```

Frenzied Regeneration
```
#showtooltip Frenzied Regeneration
/stand
/dismount
/cancelform [noform:1/3]
/cast [form:3] Cat Form
/cast [noform:1] Dire Bear Form
/cast Frenzied Regeneration
```

Bash
```
#showtooltip Bash
/stand
/dismount
/cancelform [noform:1/3]
/cast [form:3] Cat Form
/cast [noform:1] Dire Bear Form
/cast [@mouseover, harm, nodead, form:1][@target, harm, nodead, form:1] Bash
```

Maul
```
#showtooltip Maul
/stand
/dismount
/startattack [@mouseover, harm, nodead, form:1][@target, harm, nodead, form:1]
/cast !Maul
```

Swipe
```
#showtooltip Swipe
/stand
/dismount
/cast [@mouseover, harm, nodead, form:1][@target, harm, nodead, form:1] Swipe
/startattack [@mouseover, harm, nodead, form:1][@target, harm, nodead, form:1]
```

Safe(ish) Bear Consumable or Item Use Macro Example (Make sure you  are off the GCD to use)
```
#showtooltip
/stand
/dismount
/cancelform [noform:1/3]
/cast [form:1] Dire Bear Form
/cast [form:3] Cat Form
/use Greater Stoneshield Potion
/cast [noform:1] Dire Bear Form
```

Safe holywater/dynamite  macro 
```
#showtooltip
/stand
/dismount
/cancelform [noform:1/3]
/cast [form:1] Dire Bear Form
/cast [form:3] Cat Form
/use  [@cursor] Stratholme Holy Water
/cast [noform:1] Dire Bear Form
```
