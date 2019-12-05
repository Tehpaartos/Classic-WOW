# Hunter Macros

## General 

### Hunter's Mark
```
#showtooltip 
/stand
/dismount
/cast [@mouseover, harm] Hunter's Mark;Hunter's Mark
```

## Ranged Attacks
These macros will
* Shots
    1. Cast at the MouseOverTarget.
    2. Cast at the PlayerTarget, if no MouseOverTarget.

* Auto Shot
    1. If no PlayerTarget exsists, AutoShot will be cast at the MouseOverTarget.
    2. The ! will toggle AutoShot on and NOT let you toggle AutoShot off.

* Melee
    1. If unable to cast AutoShot



### Arcane Shot
```
#showtooltip
/cast [@mouseover,harm,nodead] Arcane Shot;Arcane Shot
/cast [@playertarget,noexists,harm][@mouseover, harm] !Auto Shot
/startattack [harm,nodead]
```

### Multi-Shot
```
#showtooltip
/cast [@mouseover, harm] Multi-Shot;Multi-Shot
/cast [@playertarget,noexists,harm][@mouseover, harm] !Auto Shot
/startattack [harm,nodead]
```

### Serpent Sting
```
#showtooltip
/cast [@mouseover, harm] Serpent Sting;Serpent Sting
/cast [@playertarget,noexists,harm][@mouseover, harm] !Auto Shot
/startattack [harm,nodead]
```

## Melee

Wing Clip
```
#shottooltip 
/cast Wing Clip
/cast Wing Clip(Rank 2)
/cast Wing Clip(Rank 1)
```

Raptor Strike & Mongoose Bite
```
#showtooltip
/stopcasting
/cast Raptor Strike
/startattack [harm,nodead]
/cast Mongoose Bite
```



## Pet

One Button Pet Control
```
#showtooltip
/petfollow [nocombat]
/petattack [@pettarget,noexists]target
/petfollow [@pettarget,exists]
/petattack [@mouseover,harm,nodead]
/cast Charge
/cast Dash
/cast Dive
```

One Button Pet Control with Hunters Mark (leveling)
```
#showtooltip
/petfollow [nocombat]
/petattack [@pettarget,noexists]target
/petfollow [@pettarget,exists]
/petattack [@mouseover,harm,nodead]
/cast Charge
/cast Dash
/cast Dive
/cast [@mouseover,harm,nodead,nochanneling] Hunter's Mark
```

Feed Pet
```
#showtooltip Feed Pet
/cast [pet, nodead] Feed Pet
/use [pet, nodead] Wild Hog Shank
```

Mend Pet & Call Pet
```
#showtooltip
/cast [@pet,dead]Revive Pet
/cast [nopet] Call Pet 
/cast [@pet,nodead]Mend Pet
```

One Button Eyes of the Beast
```
#showtooltip
/cast Eyes of the Beast
/cancelaura Eyes of the Beast
/petstay
```

## Traps

Explosive Trap
```
#showtooltip Explosive Trap
/petpassive
/petfollow
/stopattack
/cast [combat] Feign Death
/cast Explosive Trap
```

Immolation Trap
```
#showtooltip Immolation Trap
/petpassive
/petfollow
/stopattack
/cast [combat] Feign Death
/cast Immolation Trap
```

Freezing Trap
```
#showtooltip Freezing Trap
/petpassive
/petfollow
/stopattack
/cast [combat] Feign Death
/cast Freezing Trap
```

Frost Trap
```
#showtooltip Frost Trap
/petpassive
/petfollow
/stopattack
/cast [combat] Feign Death
/cast Frost Trap
```
