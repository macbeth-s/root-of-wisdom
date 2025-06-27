---
tags:
  - faculty
---
# Sister Oxiacantha
A nun, an Edge-long, an incessant locker of doors. 
## Aspects
- Interest: Knock 7
- Interest: Edge 7
- Interest: Winter 7
- Understands Killasimi
- Understands Phrygian
- Understands Hyksos
- [[faculty|Faculty]]
## Talk
### An Unimpressed Academic?
`talk.faculty.oxiacantha.sceptical.intro`  
**Requirements:** oxiacantha, sceptical  
**Start Description:** 'You do not seem like the kind of person who will last long here.' \[The academic culture at the Haustorium is generally unfriendly. It takes effort to be worth the faculty’s time.]

### Impressing an Academic
`talk.faculty.oxiacantha.sceptical`  
**Requirements:** oxiacantha, sceptical, interest=mystery  
**Start Description:** 'A book? I have wrestled with almost every mystery of this damned place...'  
**Description:** 'Yet, in seeking a rematch I may find wisdom. Leave it there. I will read it when I am finished sealing this room.'  
**Effect:** Spintria.bronze  
**Effect:** Oxiacantha -> -1 sceptical

### A Conversation with Sister Oxiacantha
`talk.faculty.intro.oxiacantha`  
**Requirements:** oxiacantha, -1 sceptical  
**Start Description:** 'You stand at a crossroads. Succumb, or resist.' \[The faculty can tutor you in a language and comment on incidents, or you can assist them with their ongoing research by offering a soul-element.]

### Assisting Sister Oxiacantha
`talk.faculty.assist.oxiacantha`  
**Requirements:** oxiacantha, ability  
**Start Description:** 'I have long been at work here, but I am persistently distracted by the opening of doors and the infiltration of molds through mortar. Skillful assistance may aid me in my struggle.' \[The faculty's needs can be exacting, but academic work is slow. If you can't find exactly what you need, they'll ignore you until you have something to offer.]

### Assisting Sister Oxiacantha
`talk.faculty.failure1.oxiacantha`  
**Requirements:** oxiacantha, ability, -1 research  
**Start Description:** 'I require a battle map, for my most specific war. It must not be in words: my enemy twists those too easily.'

### Assisting Sister Oxiacantha
`talk.faculty.success1.oxiacantha.sign.salt`  
**Requirements:** oxiacantha, ability, sign.salt  
**Start Description:** 'Salt dessicates; it also exterminates. I have always found that my enemy recoils from places that are not suitably fecund. I will draw up my plans in a medium loathsome even to it. You have beeen useful.'  
**Research Aspect Description:** '\[I provided Oxiacantha with a battle-map for her 'most specific war.']'  
**Effect:** [[permission.oxiacantha|Oxiacantha's Permission]]
**Mutation Effect:** Oxiacantha -> +1 research1

### Assisting Sister Oxiacantha
`talk.faculty.success1.oxiacantha.midnight.mark`  
**Requirements:** oxiacantha, ability, midnight.mark  
**Start Description:** 'Under cover of night, I have always found it safest to strike. The force against which I struggle is vast, but its loathsome corpulence is not all-seeing. This map will guide me without letting my enemy reconnoitre my plans. You have been useful.'  
**Research Aspect Description:** '\[I provided Oxiacantha with a battle-map for her 'most specific war.']'  
**Effect:** [[permission.oxiacantha|Oxiacantha's Permission]]
**Mutation Effect:** Oxiacantha -> +1 research1
### Assisting Sister Oxiacantha
`talk.faculty.failure2.oxiacantha`  
**Requirements:** oxiacantha, ability, research1
**Start Description:** 'My current focus is on the rubble outside of the Nave. When the Brotherhood last visited, I am sure they did not properly clean their feet, and some infections from the fields of their battlefields have seeped their way through the cracks. I need to consult techniques of Carving and Stoneworking, or perhaps I might just figure out exactly what kinds of contaminants the Brotherhood might be dragging in.'
### Assisting Sister Oxiacantha
`talk.faculty.success2.oxiacantha.carving`  
**Requirements:** oxiacantha, ability, research1, r.carving.stoneworking, soph:4  
**Start Description:** 'The stones, it seems, are likely impermeable. It is through the mortar that these Nowhere-influences have managed to infiltrate. One understands for security's sake why the Fourfold are so revered for their stonework; this part of the stair was built by Bahamonde's men. I'll rejoin the whole mess together, and this time the wall will last, even against Nowhere.'  
**Research Aspect Description:** '\[I provided Oxiacantha with the knowledge she needed to seal the Nowhere-influences she is fighting behind a wall.]'  
**Effect:** x.door.wall  
**Mutation Effect:** Oxiacantha -> +1 research2

### Assisting Sister Oxiacantha
`talk.faculty.success2.oxiacantha.wheel`  
**Requirements:** oxiacantha, ability, research1, a.stcatherineswheel  
**Start Description:** 'The Brotherhood and I share a quality--we wage our war on every front. It seems they had returned from a row in the Wood and somehow brought some root-clinging Nowhere-influences along. I have often found myself wishing that the Mansus had a proper wall around it. I will make do by sealing this whole mess together into a wall that will last, even against Nowhere.'  
**Research Aspect Description:** '\[I provided Oxiacantha with the knowledge she needed to seal the Nowhere-influences she is fighting behind a wall.]'  
**Effect:** x.door.wall  
**Mutation Effect:** Oxiacantha -> +1 research2

### Assisting Sister Oxiacantha
`talk.faculty.success2.oxiacantha.eclosion`  
**Requirements:** oxiacantha, ability, research1, t.nuestraeclosion  
**Start Description:** 'The Brotherhood and I share a quality--we wage our war on every front. It seems they had returned from a row in the Wood and somehow brought some root-clinging Nowhere-influences along. I have often found myself wishing that the Mansus had a proper wall around it. I will make do by sealing this whole mess together into a wall that will last, even against Nowhere.'  
**Research Aspect Description:** '\[I provided Oxiacantha with the knowledge she needed to seal the Nowhere-influences she is fighting behind a wall.]'  
**Effect:** x.door.wall  
**Mutation Effect:** Oxiacantha -> +1 research2

### Assisting Sister Oxiacantha
`talk.faculty.failure3.oxiacantha`  
**Requirements:** oxiacantha, ability, research2  
**Start Description:** 'The time has come to strike. Someone moves up the mountain, seeking hospitality here. He is exactly the kind of man Robigo would love to welcome: an aesthete and pine-scented eunuch-adept, easily fooled and easily exploited. I will slay him as he comes to La Espinada, and save myself the apologies to my colleagues.'

### Assisting Sister Oxiacantha
`talk.faculty.success3.oxiacantha.perinculate`  
**Requirements:** oxiacantha, ability, research2, perinculate  
**Start Description:** 'I will compose a fatal letter, although I generally oppose the idea of correspondence. I wish the Haustorium could be closed from the world forever, so that our rot does not spill forth in ink and paper. This will perhaps be an ironic way to wage my war. Are you uncomfortable with murder, librarian? I remind you that I am an Edge-Long; you must grow comfortable with it if you are to continue helping.'  
**Research Aspect Description:** '\[I supplied Oxiacantha with a poison that she will use to murder an adept she thinks Robigo would manipulate. She reminded me that she is an Edge-Long, though I still see no sign of her Dyad.]'  
**Effect:** x.edictsmartial  
**Mutation Effect:** Oxiacantha -> +1 research3

### Assisting Sister Oxiacantha
`talk.faculty.success3.oxiacantha.oscula`  
**Requirements:** oxiacantha, ability, research2, oscula.lunae  
**Start Description:** 'The Tragulari method. I have sought their services before, but they are willing to deal with the Growth in ways that I will not. This will perhaps be an ironic way to wage my war. Are you uncomfortable with murder, librarian? I remind you that I am an Edge-Long; you must grow comfortable with it if you are to continue helping.'  
**Research Aspect Description:** '\[I supplied Oxiacantha with a poison that she will use to murder an adept she thinks Robigo would manipulate. She reminded me that she is an Edge-Long, though I still see no sign of her Dyad.]'  
**Effect:** x.edictsmartial  
**Mutation Effect:** Oxiacantha -> +1 research3

### Assisting Sister Oxiacantha
`talk.faculty.failure4.oxiacantha`  
**Requirements:** oxiacantha, ability, research3  
**Start Description:** 'Three Hours defend the Wake against the Growth, and I serve the oldest of them. To strike at the heart of the rot here, I will need to address my supplications to one of the other two: by the White or the Black. One will answer to sufficient invocation of regret, the other is much harder to find. Scour the collection, and bring me something suitably substantial \[10+\], then perhaps I will explain to you how I became Long.'

### Assisting Sister Oxiacantha
`talk.faculty.success4.oxiacantha.ragged`  
**Requirements:** oxiacantha, ability, research3, r.raggedcrossroads, soph:10  
**Start Description:** 'An alliance with the Sun-in-Rags it will be. I will bring about a beautiful ending to this messy war. The Growth seeks to persist, to become, to prolong. Both the Sun-in-Rags and my patron loathe this. In the House of the Moon, you know, the Horned-Axe still embodies Edge. When the time came for me to go further, I journeyed to the Meniscate's Halls and there I found my Longhood. I have no pair, I have only a great encroaching enemy and a desire to finally be separated from all of this mess. When the time comes for my struggle to cease, I will be blissfully alone.'  
**Research Aspect Description:** '\[I helped Oxiacantha research supplications to an Hour that resists the Growth, and in return she explained to me her journey to the House of the Moon to ascend as a singular Edge-Long under the Horned-Axe.\]'  
**Effect:** x.meniscatereflections (x2)  
**Mutation Effect:** Oxiacantha -> +1 research4

### Assisting Sister Oxiacantha
`talk.faculty.success4.oxiacantha.meetings`  
**Requirements:** oxiacantha, ability, research3, t.meetingsinthemist  
**Start Description:** 'An alliance with the Black-Flax it will be. The Growth wishes to share, to become, to commune. Both the Velevet and my patron loathe this. In the House of the Moon, you know, the Horned-Axe still embodies Edge. When the time came for me to go further, I journeyed to the Meniscate's Halls and there I found my Longhood. I have no pair, I have only a great encroaching enemy and a desire to finally be separated from all of this mess. When the time comes for my struggle to cease, I will be blissfully alone.'  
**Research AspectDescription:** '\[I helped Oxiacantha research supplications to an Hour that resists the Growth, and in return she explained to me her journey to the House of the Moon to ascend as a singular Edge-Long under the Horned-Axe.\]'  
**Effect:** x.meniscatereflections (x2)  
**Mutation Effect:** Oxiacantha -> +1 research4

### Assisting Sister Oxiacantha
`talk.faculty.failure5.oxiacantha`  
**Requirements:** oxiacantha, ability, research4  
**Start Description:** 'My first time here as Long was a week after the Mutuality fell. I felt their death in the Rock of the Owl, and made the journey immediately. I have never understood why or how the Earth chose to slay them, despite its Protector and the might of the Growth. Someone must have forged that weapon, but who? and how? Find me the weapon, and I may learn a weakness that will allow me to circumvent Robigo.'

### Assisting Sister Oxiacantha
`talk.faculty.success5.oxiacantha.name`  
**Requirements:** oxiacantha, ability, research4, earthquake.name
<br>**Start Description:** 'Someone spoke the Earthquake Name, and loudly. There is no way that Robigo could not have heard, no way that she could have permitted the incantor to live; though she could have permitted them to speak. I suspected Robigo resented her post, and she must desire a world that is different from the Mutuality's telos of all-encompassing theories.'  
<br>**Research AspectDescription:** '\[I taught Oxiacantha the name of the Earthquake that destroyed the Mutuality, but she determined that perhaps Robigo was not a faithful protector of their research.]'  
<br>**Effect:** x.wolfstories (x2)  
<br>**Mutation Effect:** Oxiacantha -> +1 research5

### Assisting Sister Oxiacantha
`talk.faculty.failure6.oxiacantha`  
**Requirements:** oxiacantha, ability, research5
<br>**Start Description:** 'Victory is near, librarian. I have a map, an ally, perhaps even a weakness. I will complete my work and against my best judgment, you may even wield it. Bring me the most secret knowledge of struggle and war. Bring me the hidden words of this place that will allow me once and for all to outline the victory that will seal off the Growth's further incursion.'

### Earning Sister Oxiacantha's Respect  
`talk.faculty.success6.oxiacantha.tresp`  
**Requirements:** oxiacantha, ability, research5, numen.tresp  
<br>**Start Description:** 'So many scars mar the Haustorium's foundation, but it is true that Menard's folly lies at the root of much of the Growth's power. I sought to seal the threat through force. I now see that forgiveness may be the only way to close that door for good.'  
<br>**Research Aspect Description:** '\[I assisted Oxiacantha in fulfilling her work: closing the passage to Nowhere in the Frustum.\]'  
<br>**Effect:** [[remedy.oxiacantha|Oxiacantha's Remedy]], [[abjuration.vehementi|Abjuration de vehementi]]
<br>**Mutation Effect:** Oxiacantha -> +1 grateful

### Earning Sister Oxiacantha's Respect  
`talk.faculty.success6.oxiacantha.damn`  
**Requirements:** oxiacantha, ability, research5, numen.damn  
<br>**Start Description:** 'Does Robigo bleed? I imagine he does. Does she feel pain? I imagine so, as well... Bengui left these secrets. She knew how fang could pierce that corpoluent protector, and turn her on her heels to run. Cry havoc!'  
<br>**Research AspectDescription:** '\[I assisted Oxiacantha in fulfilling her work: summoning a beast to chase Robigo away.\]'  
<br>**Effect:** [[remedy.oxiacantha|Oxiacantha's Remedy]], [[ward.whistle|Ward-Whistle]]
<br>**Mutation Effect:** Oxiacantha -> +1 grateful

### Earning Sister Oxiacantha's Respect  
`talk.faculty.success6.oxiacantha.crown`  
**Requirements:** oxiacantha, ability, research5, numen.crown  
<br>**Start Description:** 'Ha! Have you seen that throne? Robigo sees himself atop it... the benevolent patron of a bounteous world. He would loathe to see another take their seat. Let us host a coronation, and defy the Growth's wish for dominion once and for all. Their kingdom will crumble before our 'Queen in Ribbons.''  
<br>**Research Aspect Description:** '\[I assisted Oxiacantha in fulfilling her work: a coronation for a worm-regent who would devour the Growth.\]'  
<br>**Effect:** [[remedy.oxiacantha|Oxiacantha's Remedy]], [[crown.ribbons|The Ribboned Crown]]
<br>**Mutation Effect:** Oxiacantha -> +1 grateful
