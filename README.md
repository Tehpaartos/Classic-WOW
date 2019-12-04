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
