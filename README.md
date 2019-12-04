# DruidMacros


## Caster

Cancel Form
```
/cancelform [noform:1/3]
/cast [form:1] Dire Bear Form
/cast [form:3] Cat Form
```

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

Hurricane
```
#showtooltip Hurricane
/stand
/dismount
/cancelform [noform:1/3]
/cast [form:1] Dire Bear Form
/cast [form:3] Cat Form
/cast Hurricane
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

Faerie Fire (any form)
```
#showtooltip 
/stand
/dismount
/cast [form:1/3, @mouseover, harm][form:1/3, @target, harm] Faerie Fire (Feral); [@mouseover, harm, noform][@target, harm, noform] Faerie Fire;Faerie Fire
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

Rebirth
```
#showtooltip Rebirth
/stand
/dismount
/cancelform [noform:1/3]
/cast [form:1] Dire Bear Form
/cast [form:3] Cat Form
/cast [@mouseover, help][@target, help][@targettarget, help][@player] Rebirth
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

Regrowth OR Starfire
```
#showtooltip
/stand
/dismount
/cancelform
/cast [@mouseover,help,nodead] Regrowth; [@mouseover,harm,nodead] [harm] Starfire; Regrowth
```

Rank 4 Regrowth OR Wrath
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

Rank 4 Rejuvenation OR Insect Swarm
```
#showtooltip
/stand
/dismount
/cancelform [noform:1/3]
/cast [form:1] Dire Bear Form
/cast [form:3] Cat Form
/cast [@mouseover,help,nodead] Rejuvenation(Rank 4); [@mouseover,harm,nodead] [harm] Insect Swarm; Rejuvenation
```

Rank 6 Rejuvenation OR Moonfire
```
#showtooltip
/stand
/dismount
/cancelform [noform:1/3]
/cast [form:1] Dire Bear Form
/cast [form:3] Cat Form
/cast [@mouseover,help,nodead] Rejuvenation(Rank 4); [@mouseover,harm,nodead] [harm] Moonfire; Rejuvenation(Rank 4)
```

Rank 4  Healing Touch
```
#showtooltip
/stand
/dismount
/cancelform [noform:1/3]
/cast [form:1] Dire Bear Form
/cast [form:3] Cat Form
/cast [@mouseover, help][@target, help][@targettarget, help][@player]  Healing Touch(Rank 4)
```


## Cat

Cat Form with Powershift
```
#showtooltip Cat Form
/dismount
/stand
/cancelaura Predatory Strikes(Rank 3)
/cancelaura Leader of the Pack
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
/startattack
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



## Bear Form

Dire Bear Form with Powershift
```
#showtooltip Dire Bear Form
/dismount
/stand
/cancelaura Predatory Strikes(Rank 3)
/cancelaura Leader of the Pack
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
/cast [@mouseover, harm, form:1][@target, harm, form:1] Growl
```

Feral Charge
```
#showtooltip Feral Charge
/stand
/dismount
/cancelform [noform:1/3]
/cast [form:3] Cat Form
/cast [noform:1] Dire Bear Form
/cast [@mouseover, harm, form:1][@target, harm, form:1] Feral Charge
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
/cast [@mouseover, harm, form:1][@target, harm, form:1] Bash
```

Maul
```
#showtooltip Maul
/stand
/dismount
/cast !Maul
```

Swipe
```
#showtooltip Swipe
/stand
/dismount
/cast [@mouseover, harm, form:1][@target, harm, form:1] Swipe
/startattack [@mouseover, harm, form:1][@target, harm, form:1]
```

