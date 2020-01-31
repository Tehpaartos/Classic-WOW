# Hunter Macros

## General 

### Auto Shot
```
#showtooltip 
/stand
/dismount
/cast [@mouseover, harm] [] !Auto Shot
```

### Hunter's Mark
```
#showtooltip 
/stand
/dismount
/cast [@mouseover, harm] [] Hunter's Mark
```

### Aspect of the Hawk
```
#showtooltip 
/stand
/dismount
/cast !Aspect of the Hawk
```

### Aspect of the Monkey
```
#showtooltip 
/stand
/dismount
/cast !Aspect of the Monkey
```

## Ranged Attacks
The below Shots/Stings macros will:
 1. Cast your Shots/Stings at the MouseOverTarget, without dropping your current PlayerTarget.  This is amazing for Auto Shot uptime & you will be able to cast Shots/Stings at any target, in range.
 2. If you currently don't have a PlayerTarget, start Auto Shotting the MouseOverTarget.  The exclamation mark, !, will toggle Auto Shot ON and NOT let you toggle it OFF.
 3. If the PlayerTarget is within the hunter dead zone, Auto Shot will fail to cast, and you will begin to Melee attack the PlayerTarget.

### Arcane Shot
```
#showtooltip
/stand
/dismount
/cast [@mouseover,harm,nodead] [] Arcane Shot
/cast [@playertarget,noexists,harm][@mouseover, harm] !Auto Shot
/startattack [harm,nodead]
```

### Multi-Shot
```
#showtooltip
/stand
/dismount
/cast [@mouseover, harm] [] Multi-Shot
/cast [@playertarget,noexists,harm][@mouseover, harm] !Auto Shot
/startattack [harm,nodead]
```

### Serpent Sting
```
#showtooltip
/stand
/dismount
/cast [@mouseover, harm] [] Serpent Sting
/cast [@playertarget,noexists,harm][@mouseover, harm] !Auto Shot
/startattack [harm,nodead]
```

## Melee

### Wing Clip
```
#shottooltip 
/cast Wing Clip
/cast Wing Clip(Rank 2)
/cast Wing Clip(Rank 1)
```

### Raptor Strike & Mongoose Bite
```
#showtooltip
/stopcasting
/cast Raptor Strike
/startattack [harm,nodead]
/cast Mongoose Bite
```



## Pet



### One Button Pet Control
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
The below matrix will outline how the macro works
![OneButtonPet](/images/OneButtonPet.JPG)

### One Button Pet Control with Hunters Mark (leveling)
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

### Feed Pet
```
#showtooltip Feed Pet
/cast [pet, nodead] Feed Pet
/use [pet, nodead] Wild Hog Shank
```

### Mend Pet & Call Pet
```
#showtooltip
/cast [@pet,dead]Revive Pet
/cast [nopet] Call Pet 
/cast [@pet,nodead]Mend Pet
```

### One Button Eyes of the Beast
```
#showtooltip
/cast Eyes of the Beast
/cancelaura Eyes of the Beast
/petstay
```

## Traps

### Explosive Trap
```
#showtooltip Explosive Trap
/petpassive
/petfollow
/stopattack
/cast [combat] Feign Death
/cast Explosive Trap
```

### Immolation Trap
```
#showtooltip Immolation Trap
/petpassive
/petfollow
/stopattack
/cast [combat] Feign Death
/cast Immolation Trap
```

### Freezing Trap
```
#showtooltip Freezing Trap
/petpassive
/petfollow
/stopattack
/cast [combat] Feign Death
/cast Freezing Trap
```

### Frost Trap
```
#showtooltip Frost Trap
/petpassive
/petfollow
/stopattack
/cast [combat] Feign Death
/cast Frost Trap
```
