---
tags:
  - faculty
---
# La Magdalena
A cat. A very, very, intelligent cat.
## Aspects
- Interest: Moth 7
- Interest: Rose 7
- Interest: Sky 7
- Understands Ramsund
- Understands [[s.tecuanilatolli|Tecuanilatolli]]
- [[Faculty]]
## Talk
### An Unimpressed Academic?
`talk.faculty.magdalena.sceptical.intro`  
**Requirements:** magdalena, sceptical  
**Start Description:** The cat does not rise from her perch. She blinks, sees my empty hands, then resumes her slumber. \[The academic culture at the Haustorium is generally unfriendly. It takes effort to be worth the faculty’s time.]

### Impressing an Academic
`talk.faculty.magdalena.sceptical`  
**Requirements:** magdalena, sceptical, interest=mystery  
**Start Description:** I feel foolish offering the cat a book. I set it down, then awkwardly open to a page.
**Description:** The rustling of the pages intrigues the cat. She rises and runs a careful claw down the spine. Taking the severed page into her mouth, she tucks it in a lower drawer of the desk. I spy within many similar pages, stacked neatly; a collection of inks; a dead rat; and what I hope is not but likely is a human skull. One glinting trinket atop the mess is for me. 
**Effect:** Spintria.bronze  
**Effect:** magdalena -> -1 sceptical

### A Conversation with La Magdalena
`talk.faculty.intro.magdalena`  
**Requirements:** magdalena, -1 sceptical  
**Start Description:** 'Miau.' \[The faculty can tutor you in a language and comment on incidents, or you can assist them with their ongoing research by offering a soul-element.]

### Assisting La Magdalena
`talk.faculty.assist.magdalena`  
**Requirements:** magdalena, ability  
**Start Description:** Her ears twitch. Her eyes dilate to dark moons. Her tail curls into a question mark, then slowly sways across the ground. \[The faculty's needs can be exacting, but academic work is slow. If you can't find exactly what you need, they'll ignore you until you have something to offer.]

### Assisting La Magdalena
`talk.faculty.failure1.magdalena`  
**Requirements:** magdalena, ability, -1 research  
**Start Description:** The cat squeezes behind her desk, emerging with a sheet of paper in her mouth which she offers to me. It appears to be an illustration from a storybook, depicting a sickly child being menaced by a miasmatic specter. She seems to have made her own additions, putting a dark stroke of ink between the child and specter; drawn nearby are the alchemic symbols for earth and air.

### Assisting La Magdalena
`talk.faculty.success1.magdalena.awakened.feather`  
**Requirements:** magdalena, ability, awakened.feather 
**Start Description:** I place the feather before her along with the illustration. She curiously paws at it before sweeping it over the paper, the specter brushed away like a drawing in dust until only the space it occupied remains. When she gazes up at me once more, her pupils expand like a lung. I can almost imagine her upturned mouth is a smile.  
**Research Aspect Description:** \[I provided La Magdalena with a means to ward off disease... probably.]
**Effect:** [[permission.magdalena|La Magdalena's Permission]]
**Mutation Effect:** magdalena -> +1 research1

### Assisting La Magdalena
`talk.faculty.success1.magdalena.clouded.carbuncle`  
**Requirements:** magdalena, ability, [[carbuncle.clouded|Clouded Carbuncle]]
**Start Description:** I place the carbuncle before her along with the illustration. She curiously paws at it before nudging it onto the paper to rest over the specter. After a moment, the specter begins to withdraw into the stone, a sponge absorbing a freshly-inked sketch, until not even a stain remains. When she gazes up at me once more, her pupils expand like a lung. I can almost imagine her upturned mouth is a smile.
**Research Aspect Description:** \[I provided La Magdalena with a means to ward off disease... probably.]
**Effect:** [[permission.magdalena|La Magdalena's Permission]]
**Mutation Effect:** magdalena -> +1 research1

### Assisting La Magdalena
`talk.faculty.failure2.magdalena`  
**Requirements:** magdalena, ability, research1
**Start Description:** Another sheet of paper. Not a drawing, but music: a guitar tablature for a piece called 'Volveremos' composed by Fatima Abeja. She penned this during her stay at the Convent of Santo Domingo, and it was supposedly the reason she was barred from the premises. Dark writing along the margins: 'Birth and death are only directions. Between the two we find a crossroads.' The cat watches me expectantly.

### Assisting La Magdalena
`talk.faculty.success2.magdalena.resurgences.emergences`  
**Requirements:** magdalena, ability, research1, r.resurgences.emergences, soph:4  
**Start Description:** Once more, I lay a book before her. She paws through at a languid pace until she finds a suitable spot. The music is slipped between the pages, the cover closed, and she slips away. In the distance, a vinyl crackling like autumn leaves. Then the melody of 'Volveremos', sung by a soft voice; I can catch a mewed harmony beneath it. The book rumbles and breathes at the sound. When silence falls, the cat reappears and retrieves the music. The notes now shimmer pink, and in its corner, the mountain-mark of the Wayfinders has appeared. Then it's slipped into a drawer away from prying eyes.
**Research Aspect Description:** \[La Magdalena struck up a song of restorative nostalgia, investing that power into sheet music, with my <i>possibly</i> needed assistance.]
**Effect:** x.strings.songs 
**Mutation Effect:** magdalena -> +1 research2

### Assisting La Magdalena
`talk.faculty.success2.magdalena.t.abejasflightlbleeding`  
**Requirements:** magdalena, ability, research1, [[t.abejasflightbleeding|Abeja's Flight: Bleeding]]
**Start Description:** Once more, I lay a book before her. She paws through at a languid pace until she finds a suitable spot. The music is slipped between the pages, the cover closed, and she slips away. In the distance, a vinyl crackling like autumn leaves. Then the melody of 'Volveremos', sung by a soft voice; I can catch a mewed harmony beneath it. The book rumbles and breathes at the sound. When silence falls, the cat reappears and retrieves the music. The notes now shimmer pink, and in its corner, the mountain-mark of the Wayfinders has appeared. Then it's slipped into a drawer away from prying eyes.
**Research Aspect Description:** \[La Magdalena struck up a song of restorative nostalgia, investing that power into sheet music, with my <i>possibly</i> needed assistance.]
**Effect:** x.strings.songs
**Mutation Effect:** magdalena -> +1 research2

### Assisting La Magdalena
`talk.faculty.success2.magdalena.t.abejasflightlbeating`  
**Requirements:** magdalena, ability, research1, [[t.abejasflightbeating|Abeja's Flight: Beating]]
**Start Description:** Once more, I lay a book before her. She paws through at a languid pace until she finds a suitable spot. The music is slipped between the pages, the cover closed, and she slips away. In the distance, a vinyl crackling like autumn leaves. Then the melody of 'Volveremos', sung by a soft voice; I can catch a mewed harmony beneath it. The book rumbles and breathes at the sound. When silence falls, the cat reappears and retrieves the music. The notes now shimmer pink, and in its corner, the mountain-mark of the Wayfinders has appeared. Then it's slipped into a drawer away from prying eyes.
**Research Aspect Description:** \[La Magdalena struck up a song of restorative nostalgia, investing that power into sheet music, with my <i>possibly</i> needed assistance.]
**Effect:** x.strings.songs 
**Mutation Effect:** magdalena -> +1 research2

### Assisting La Magdalena
`talk.faculty.failure3.magdalena`  
**Requirements:** magdalena, ability, research2  
**Start Description:** She jumps into the hollow below the desk, mewing at me to come. In the dim light, her pupils are mirrors; once my eyes adjust, she looks towards the panel at the far end. It's intricately carved, depicting a number of felines thronged around a heart with 'Magdalena' inscribed on the surface and - oddly - given a pair of ears. Two banderoles frame the scene above and below, phrases written upon them: 'Sing the song of joyous sacrifice' and 'Let us learn who we truly are'.

### Assisting La Magdalena
`talk.faculty.success3.magdalena.music.thunderskin`  
**Requirements:** magdalena, ability, research2, music.thunderskin  
**Start Description:** Quietly, I hum the song into one of the ears. It seems absurd in the moment, but when I finish, something clicks and the panel swings open. The cat squeezes through, revealing a mossy interior stuffed with scraps of pale paper and stony trinkets. It goes back far further than it should, and the cat lazily winds her way into the impenetrable gloom. My hand is drawn to reach in, and I give into the whim. Pain passes through my arm like red and water and lightning and through the Kingskin Gate and into Door in the Well she crawls down down down into that first Darkness.  
  
When I pull my hand out, it still has its skin. For a moment, it feels too tight. Then the world loosens once more as the cat returns.
**Research Aspect Description:** \[I opened a way to what might be the Wood, and might have *become* a way to La Magdalena. Likely not, but whatever happened, a Door has been left ajar.] 
**Effect:** x.pentiments.precursors  
**Mutation Effect:** magdalena -> +1 research3

### Assisting La Magdalena
`talk.faculty.success3.magdalena.riddle.nameday`  
**Requirements:** magdalena, ability, research2, riddle.nameday
**Start Description:** Quietly, I whisper the riddle into one of the ears. It seems absurd in the moment, but when I finish, something clicks, and the panel swings open just a bit. It seems absurd in the moment, but when I finish, something clicks and the panel swings open. The cat squeezes through, revealing a mossy interior stuffed with scraps of pale paper and stony trinkets. It goes back far further than it should, and the cat lazily winds her way into the impenetrable gloom. My hand is drawn to reach in, and I give into the whim. Pain passes through my arm like red and water and lightning and through the Kingskin Gate and into Door in the Well she crawls down down down into that first Darkness.  
  
When I pull my hand out, it still has its skin. For a moment, it feels too tight. Then the world loosens once more as the cat returns.
**Research Aspect Description:** \[I opened a way to what might be the Wood, and might have *become* a way to La Magdalena. Likely not, but whatever happened, a Door has been left ajar.]
**Effect:** x.pentiments.precursors  
**Mutation Effect:** magdalena -> +1 research3

### Assisting La Magdalena
`talk.faculty.failure4.magdalena`  
**Requirements:** magdalena, ability, research3  
**Start Description:** The cat leaps from the desk and solemnly slinks off. Where she sat lies a grainy photo. In it, the desk is overrun with cats, each resembling the one I've come to know. In the foreground are two people: a figure bundled in scarves, with a cat curled upon their shoulder; and an infamous face, Lord Jacob Gristwood, holding a bottle lined with a mottled fungus. Handwritten on the back in a pronounced style: 'Explorers of Zeboim, navigators of the Rending Mountains. Let us celebrate the living and the dead alike.'

### Assisting La Magdalena
`talk.faculty.success4.magdalena.rhyme.remembrance`  
**Requirements:** magdalena, ability, research3, r.rhyme.remembrance, soph:10  
**Start Description:** Before I can place it down, the cat leaps out from nowhere to snatch the tome from my hands, then she's gone again like lightning. Fluttering in her wake is a stray sheet of paper which lands softly on the desk. An itinerary, seemingly, for Dr Hagan and Lord Gristwood, arranged by Robigo in 1905. It seems the Dottore prepared a celebration of their achievements. Following their arrival, the itinerary is scribbled over in red, and various epithets surround Gristwood's name: 'THIEF', 'KIT NAPPER', 'TRAITOR' and so on. By the time I read them all, the cat has returned. She places a paw on the sheet, nudging it through a thin gap in the floor, into darkness, obscurity.
**Research Aspect Description:** \[I helped find some knowledge related to Lord Gristwood, and learnt a bit more of what crimes barred him evermore from the Haustorium - and how they might be bound up in La Magdalena's past.]
**Effect:** x.edictsinviolable (x2)  
**Mutation Effect:** Oxiacantha -> +1 research4

### Assisting La Magdalena
`talk.faculty.success4.magdalena.t.funerarycustomsoftherendingmountains`  
**Requirements:** magdalena, ability, research3, [[t.funerarycustomsoftherendingmountains|Funerary Customs of the Rending Mountains]]
**Start Description:** Before I can place it down, the cat leaps out from nowhere to snatch the tome from my hands, then she's gone again like lightning. Fluttering in her wake is a stray sheet of paper which lands softly on the desk. An itinerary, seemingly, for Dr Hagan and Lord Gristwood, arranged by Robigo in 1905. It seems the Dottore prepared a celebration of their achievements. Following their arrival, the itinerary is scribbled over in red, and various epithets surround Gristwood's name: 'THIEF', 'KIT NAPPER', 'TRAITOR' and so on. By the time I read them all, the cat has returned. She places a paw on the sheet, nudging it through a thin gap in the floor, into darkness, obscurity.
**Research AspectDescription:** \[I helped find some knowledge related to Lord Gristwood, and learnt a bit more of what crimes barred him evermore from the Haustorium - and how they might be bound up in La Magdalena's past.]
**Effect:** x.edictsinviolable (x2)  
**Mutation Effect:** magdalena -> +1 research4

### Assisting La Magdalena
`talk.faculty.success4.magdalena.elixirzeboim`  
**Requirements:** magdalena, ability, research3, [[a.elixirzeboim|Elixir Zeboim]]
**Start Description:** Before I can place it down, the cat leaps out from nowhere to snatch the bottle from my hands, then she's gone again like lightning. Fluttering in her wake is a stray sheet of paper which lands softly on the desk. An itinerary, seemingly, for Dr Hagan and Lord Gristwood, arranged by Robigo in 1905. It seems the Dottore prepared a celebration of their achievements. Following their arrival, the itinerary is scribbled over in red, and various epithets surround Gristwood's name: 'THIEF', 'KIT NAPPER', 'TRAITOR' and so on. By the time I read them all, the cat has returned. She places a paw on the sheet, nudging it through a thin gap in the floor, into darkness, obscurity.
**Research AspectDescription:** \[I helped find some knowledge related to Lord Gristwood, and learnt a bit more of what crimes barred him evermore from the Haustorium - and how they might be bound up in La Magdalena's past.]
**Effect:** x.edictsinviolable (x2)  
**Mutation Effect:** magdalena -> +1 research4

### Assisting La Magdalena
`talk.faculty.failure5.magdalena`  
**Requirements:** magdalena, ability, research4  
**Start Description:** After getting my attention, she prowls around the desk in some strange ritual, pawing a panel here, scratching at a scroll there. It would seem nonsensical to anyone who didn't know better. Sure enough, when she makes her final steps, there's the scratching of an old vinyl record, and a subdued voice speaking beneath. 'Anyone can spill blood, with a blade or rock or what have you. Yet what we need is more than a willingness to cut a living body open. We must be earnest in our sacrifice, even if we do not provide, for the first who chose to spill their own blood upon the earth knew not just pain, but ecstasy as well.' Her eyes meet mine expectantly. Her ears twitch to an unheard rhythm.

### Assisting La Magdalena
`talk.faculty.success5.magdalena.enthusiastic.sacrifice`  
**Requirements:** magdalena, ability, research4, [[enthusiastic.sacrifice|Enthusiastic Sacrifice]]
**Start Description:** The memory churns at all sides of my skull, threatening to spill over. When the cat comes before me, her ears twitch to the rhythm of blood pounding at my own, at the beat of my heart aching to fly. I do not speak this desire so much as it escapes me, and it sinks into her fur and through her skin. She shudders, lets out a piercing mewl - my blood curls like sundew - then takes an impossible step into the space between the desk and the floor. Or was it a trick of the eyes? When I crouch to see where she's gone, at the narrow dark beneath the desk, I jump away when tendrils reach out at me. No, not tendrils - darkened roots. And not the roots of any plant I know, but the roots of the desk itself, burrowing downwards, through the floorboards to who knows where in the Haustorium? Yet I recall stories of blood being spilt in this room, across the planks and the paneling, and how bloodstains never took. Is this why? Nothing comes forth to answer. 
**Research AspectDescription:** \[La Magdalena accepted an earnest yearning for sacrifice, and took it with her into the dark beneath the desk - a desk with roots which perhaps thirst for blood. For a time, that thirst has been heightened.]
**Effect:** x.rites.theroots (x2)  
**Mutation Effect:** magdalena -> +1 research4

### Assisting La Magdalena
`talk.faculty.failure6.magdalena`  
**Requirements:** magdalena, ability, research5 
**Start Description:** More photos scattered across the desk, and the cat is nowhere to be seen. The subjects are wildly varied - cloudy vistas from many mountain ranges; an explorer standing amongst cloaked Wayfinders; the same explorer with cats wreathed around their scarf-concealed face - and amongst them all: La Magdalena, arched or curled or posed different in each. It all seems meaningless at first, but as I look over them, a sequence gradually reveals itself. Impossibly, La Magdalena dances through the photos, their different times and locales, as if nothing stood between them, joined occasionally by near-identical cats and the explorer. Near the end, the photos all appear to have been taken in the Haustorium, and La Magdalena settles and stills, entirely alone. When I slide the last of these into place, she suddenly appears to leap atop the desk, with three photos in her mouth that she softly sets down. The heady scent of darkroom chemicals lightly wafts from them.  
  
La Magdalena looks towards the camera in each, sat before a series of seven skulls. Six are small and feline, with the last human, but it is the last of these I recall seeing stowed away in her drawers. In one, they are crowded in a nest. In another, a harsh light off to the side makes them cast severe shadows. The last leaves them atop a pillow, heads tilted to the side as though they were asleep. These must be questions; La Magdalena looks to me for an answer.

### Earning La Magdalena's Respect  
`talk.faculty.success6.magdalena.incu`  
**Requirements:** ability, research5, [[numen.incu|Numen: Incubation]]  
**Start Description:** I speak of the Egg and the Nest, the Shell and the Cuckoo. La Magdalena listens with watchful eyes until I finish, then sets about scurrying around the desk, drawers opening and items spilling and the rhythm of wood filling the room. Try as I might to focus, I struggle to grasp onto any one image, until something which is not here passes into my vision like an errant lock of hair. It is brief: a nest of roots in the earth, long-dormant and awaiting a new brood. I see a skull tiled with obsidian, and six smaller skulls held within; in the nest, they shake, until the crackled sound of hatching begins. The vision passes, and in my hands, I hold that very skull. La Magdalena stretches, then jumps off the desk, giving me one last glance before wandering off into the dark. Perhaps she is smiling.
**Research Aspect Description:** \[I assisted La Magdalena in fulfilling her work; rebirthing her lost kin from an Obsidian Egg.]
**Effect:** [[remedy.magdalena|La Magdalena's Remedy]], [[skull.obsidian|Obsidian Skull]]
**Mutation Effect:** magdalena -> +1 grateful

### Earning La Magdalena's Respect  
`talk.faculty.success6.magdalena.shad`  
**Requirements:** ability, research5, [[numen.shad|Numen: The Glorious Shadows]] 
**Start Description:** I speak of the shadows of Glory, the hidden Light in darkness. La Magdalena listens with watchful eyes until I finish, then sets about scurrying around the desk, drawers opening and items spilling and the rhythm of wood filling the room. Try as I might to focus, I struggle to grasp onto any one image, until something which is not here passes into my vision like an errant lock of hair. It is brief: a shrine shrouded in darkness, matted with black moss. I see a skull set upon its surface, six smaller skulls placed within. A candle burns bright upon the depressed scalp, until I am blinded by light before being plunged into the dark. Faintly, I hear the night-soft steps of a life fragile as mist. The vision passes, and in my hands, I hold that very skull. La Magdalena stretches, then jumps off the desk, giving me one last glance before wandering off into the dark. Perhaps she is smiling. 
** Research AspectDescription:** \[I assisted La Magdalena in fulfilling her work; letting her lost kin live on through their living shadows.]
**Effect:** [[remedy.magdalena|La Magdalena's Remedy]], [[skull.shadowed|Shadowed Skull]]
**Mutation Effect:** magdalena -> +1 grateful

### Earning La Magdalena's Respect  
`talk.faculty.success6.magdalena.awak`  
**Requirements:** ability, research5, [[numen.spine|Numen: The Spine's Awakening]] 
**Start Description:** I speak of the Hours cast-down, the bones beneath the world's skin. La Magdalena listens with watchful eyes until I finish, then sets about scurrying around the desk, drawers opening and items spilling and the rhythm of wood filling the room. Try as I might to focus, I struggle to grasp onto any one image, until something which is not here passes into my vision like an errant lock of hair. It is brief: a petrified snarl of curled trunks at the heart of a forest of stone. I see a skull emplaced in a hollow, with six smaller skulls set within it. Whispered words fill the air, and the skull trembles and clatters against the stony gnarl, until the world rumbles like a yawning giant. The vision passes, and in my hands, I hold that very skull. La Magdalena stretches, then jumps off the desk, giving me one last glance before wandering off into the dark. Perhaps she is smiling.
**Description:** \[I assisted La Magdalena in fulfilling her work; awakening the bones of her lost kin to ensure their eventual return.]
**Effect:** [[remedy.magdalena|La Magdalena's Remedy]], [[skull.sleeping|Sleeping Skull]]
**Mutation Effect:** magdalena -> +1 grateful