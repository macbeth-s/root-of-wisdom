---
tags:
  - faculty
---
# Socorro Valenzuela
An archaeologist from far away. She has more in common with the fossils she excavates than her colleagues here.
## Aspects
- [[faculty|Faculty]]
- Interest: Scale 7
- Interest: R0se 7
- Interest: Edge 7
- Understands Cracktrack
- Understands Quechua
- Understands Sanskrit
## Talk
### An Unimpressed Academic?
`talk.faculty.valenzuela.sceptical.intro`
<br>**Requirements:** valenzuela, sceptical
<br>**Start Description:** 'I am not certain you respect the land on which you tread. Leave me be.' \[The academic culture at the Haustorium is generally unfriendly. It takes effort to be worth the faculty’s time.]
### Impressing an Academic
`talk.faculty.valenzuela.sceptical`
<br>**Requirements:** valenzuela, sceptical, interest=mystery
<br>**Start Description:** 'I was mistaken. It seems you do understand the things worth knowing about this place and the places that came before.'
<br>**Description:** 'Books have their place, but so do stones. There are many messages hidden within the creases and line-breaks of each. I am glad you understand this. Here is your tally for your contribution to my work.'
<br>**Effect:** [Bronze Spintria](https://uadaf.theevilroot.xyz/rowenarium/element/spintria.bronze)
<br>**Mutation Effects:** valenzuela -> -1 sceptical
### A Conversation with Valenzuela
`talk.faculty.intro.valenzuela`
<br>**Requirements:** valenzuela, sceptical -1
<br>**Start Description:** 'There's much to learn here.' \[The faculty can tutor you in a language and comment on Incidents, or you can assist them with their ongoing research by offering a soul-element.]
### Assisting Valenzuela
`talk.faculty.assist.valenzuela`
<br>**Requirements:** valenzuela, ability
<br>**Start Description:** 'In every stone, a story. When you take the longest view, nothing is ever stagnant. I'm seeking answers to the oldest questions among these rocks.' \[The faculty's needs can be exacting, but academic work is slow. If you can't find exactly what you need, they'll ignore you until you have something to offer.]

### Assisting Valenzuela
`talk.faculty.failure1.valenzuela`
<br>**Requirements:** valenzuela, ability, research -1<br>**Start Description:** 'If you're to be useful, you'll start by procuring things before I let you anywhere near a fossil or fragment. I'm low on biological samples to analyze. Specifically, those with traces of creatures that are more than mortal. Their remains always respond best to my tests.'
### Assisting Valenzuela
`talk.faculty.success1.valenzuela.bonechalk`
<br>**Requirements:** valenzuela, ability, research -1, [[bone.chalk|Bone-Chalk]]
<br>**Start Description:** 'Look within, librarian. There is stone, yes, but also there are fragments of snail-whorl and oceans long past. It is always possible to be deader, and that is the single greatest lesson the bones have for us. Ruminate on that while you bustle about these halls.'
<br>**Research Aspect Description:** \[I provided Valenzuela with trace materials of old beings, which she reminded me can always be deader.]
<br>**Effect:** [[permission.valenzuela|Valenzuela's Permission]]
<br> **Mutation Effect:** valenzuela -> research 1
### Assisting Valenzuela
`talk.faculty.success1.valenzuela.tincture.labhitic`
<br>**Requirements:** valenzuela, ability, research -1, [Labhitic Tincture](https://uadaf.theevilroot.xyz/rowenarium/element/tincture.labhitic)
<br>**Start Description:** 'Look within, librarian. There are the solvent and solution, yes, but if you are careful you can see their precursors. The labhites only eat of the sky, and so their remnants still speak of the wind's howl through the mountains. It is always possible to be deader, and that is the single greatest lesson the bones have for us. Ruminate on that while you bustle about these halls.'
<br>**Research Aspect Description:** \[I provided Valenzuela with trace materials of old beings, which she reminded me can always be deader.]
<br>**Effect:** [[permission.valenzuela|Valenzuela's Permission]]
<br> **Mutation Effect:** valenzuela -> research 1
### Assisting Valenzuela
`talk.faculty.failure2.valenzuela`
<br>**Requirements:** valenzuela, ability, research 1
<br>**Start Description:** 'Trapped in amber, beneath a cornerstone of the Frustum, I have found a six-limbed thorax that suggests something very important about the Carapace Cross' role at this place. Find me what you have about hexapods and their secretions. Or anything by Zawistowski will probably cover the same material.'
### Assisting valenzuela
`talk.faculty.success2.valenzuela.insects.nectars`
<br>**Requirements:** valenzuela, ability, research 1,  r.insects.nectars, soph: 4
<br>**Start Description:** 'It seems to be as I've long thought; the foundations of the 'Ruin of the Roots' was set by the Cross as a place of veneration for their–or our–Old Gods. Their trickster-heroes fancied themselves dragonslayers, and taught those rites to humanity. I was of the travelling-kinds, not the flower-bearing kinds who ventured to this place. But all the Cross traveled somewhat, just for different reasons.'
<br>**Research Aspect Description:** \[I helped Valenzuela identify an insectoid fossil from below the Haustorium, and in so doing learned she once counted herself among the 'travelling-kinds' of the Carapace Cross.]
<br>**Effect:** x.path.pilgrim
<br>**Mutation Effect:** valenzuela -> research 2
### Assisting Valenzuela
`talk.faculty.success2.valenzuela.t.thetantraofworms`
<br>**Requirements:** valenzuela, ability, research 1, [The Tantra of Worms](https://uadaf.theevilroot.xyz/rowenarium/element/t.thetantraofworms)
<br>**Start Description:** 'Zawistowski's work on the wyrmfota corroborates my theory that the foundations of the 'Ruin of the Roots' was set by the Cross as a place of veneration for their–or our–Old Gods. Their trickster-heroes fancied themselves dragonslayers, and taught those rites to humanity. I was of the travelling-kinds, not the flower-bearing kinds who ventured to this place. But all the Cross traveled somewhat, just for different reasons.'
<br>**Research Aspect Description:** \[I helped Valenzuela identify an insectoid fossil from below the Haustorium, and in so doing learned she once counted herself among the 'travelling-kinds' of the Carapace Cross.]
<br>**Effect:** x.path.pilgrim
<br>**Mutation Effect:** valenzuela -> research 2
### Assisting Valenzuela
`talk.faculty.success2.valenzuela.t.aclearcarapace`
<br>**Requirements:** valenzuela, ability, research 1, [[t.aclearcarapace|A Clear Carapace]]
<br>**Start Description:** 'Zawistowski's work on the wyrmfota corroborates my theory that the foundations of the 'Ruin of the Roots' was set by the Cross as a place of veneration for their–or our–Old Gods. Their trickster-heroes fancied themselves dragonslayers, and taught those rites to humanity. I was of the travelling-kinds, not the flower-bearing kinds who ventured to this place. But all the Cross traveled somewhat, just for different reasons.'
<br>**Research Aspect Description:** \[I helped Valenzuela identify an insectoid fossil from below the Haustorium, and in so doing learned she once counted herself among the 'travelling-kinds' of the Carapace Cross.]
<br>**Effect:** x.path.pilgrim
<br>**Mutation Effect:** valenzuela -> research 2
### Assisting Valenzuela
`talk.faculty.failure3.valenzuela`
<br>**Requirements:** valenzuela, ability, research 2
<br>**Start Description:** 'There were no wyrmfota among us when we travelled, though I know that many of them were said to have wings. Of the others, they died or passed within your–our–kind. I suspect that if we look closely into further remains, either those that remain from flesh or those that remain from stone, we can learn much more about what the rest have done.'
### Assisting Valenzuela
`talk.faculty.success3.valenzuela.essential.periost`
**Requirements:** valenzuela, ability, research 2, [Essential Periost](https://uadaf.theevilroot.xyz/rowenarium/element/essential.periost)
<br>**Start Description:** 'Your own bones would say the same thing as these scrapings of memory, librarian. When the Gods-from-Stone died, many Cross turned to the Moth and embraced it to pass within. Now, the Moth's powers are used to undo the passage. Like the spoke of a wheel, it returns. In the Wound-Roots, I found records of these old rites, which required me to perform and then mock the rites of the Wheel, the Seven-Coils, the Egg Unhatching... I look back with some regret, but I cannot deny what my passage has done for me.'
<br>**Research Aspect Description:** \[I aided Valenzuela in analyzing the traces of the Carapace Cross which persist in the world, leading her to tell me of how she was able to shed her Cross-form and become human through old rites found beneath the Haustorium.]
<br>**Effect:** x.rites.theroots 
<br>**Mutation Effect:** valenzuela -> research 3
### Assisting Valenzuela
`talk.faculty.success3.valenzuela.ichor.lernaean`
<br>**Requirements:** valenzuela, ability, research 2, [[ichor.lernaean|Ichor Lernaean]]]
<br>**Start Description:** 'The blood of the Earth speaks of the golden blood of the Cross. When the Gods-from-Stone died, many Cross turned to the Moth and embraced it to pass within. Now, the Moth's powers are used to undo the passage. Like the spoke of a wheel, it returns. In the Wound-Roots, I found records of these old rites, which required me to perform and then mock the rites of the Wheel, the Seven-Coils, the Egg Unhatching... I look back with some regret, but I cannot deny what my passage has done for me.'
<br>**Research Aspect Description:** \[I aided Valenzuela in analyzing the traces of the Carapace Cross which persist in the world, leading her to tell me of how she was able to shed her Cross-form and become human through old rites found beneath the Haustorium.]
<br>**Effect:** x.rites.theroots 
<br>**Mutation Effect:** valenzuela -> research 3
### Assisting Valenzuela
`talk.faculty.failure4.valenzuela`
<br>**Requirements:** valenzuela, ability, research 3
<br>**Start Description:** 'I have sometimes compared archaeology to pearl-diving. One must have keen eyes, hard hands, and a strong constitution. Recently the similarity has been literal. A colleague on the coast has sent me a sample (still squirming) that may teach us the methods we need to finally hear the stones speak. Since the Tide's draining there are only two Hours who govern the seas, and neither is easily invoked. Bring me what you can on the ways of the ocean \[10+] or the protective rites of the Witch-and-Sister.'
### Assisting Valenzuela
`talk.faculty.success4.valenzuela.seastories`
<br>**Requirements:** valenzuela, ability, research 3, r.seastories, soph: 10
<br>**Start Description:** 'In the days of the Tide, the sea was a glorious bounty. Now its tenebrous depths are stalked by the grasping limbs of the Blackbone. In its hoards of cracked timber and gnawing hungers, the Blackbone still keeps the precious life-secrets that the Tide once wore like jewels. Its power, though destructive, has sustained our sample and through it I can find the essential humors of the Seglaz-kind. With canny enough knowledge of its forms, I might preserve more than a fossil.'
<br>**Research Aspect Description:** \[Valenzuela and I count ourselves among the few who benefit from the work of the cast-down Hour called Blackbone, as we used a part of its hoard to extract an essence of the Carapace Cross.]
<br>**Effect:** Lesson: [[s.meontologicalglimpses|Meontological Glimpses]] (x2)
<br>**Mutation Effect:** valenzuela -> research 4
### Assisting Valenzuela
`talk.faculty.success4.valenzuela.pearl`
<br>**Requirements:** valenzuela, ability, research 3, [[t.thewitchspearl|The Witch's Pearl]]
<br>**Start Description:** 'In the days of the Tide, the sea was a glorious bounty. Now its tenebrous depths are stalked by the grasping limbs of the Blackbone. In its hoards of cracked timber and gnawing hungers, the Blackbone still keeps the precious life-secrets that the Tide once wore like jewels. Its power, though destructive, has sustained our sample and through it I can find the essential humors of the Seglaz-kind. With the rites of the Witch-and-Sister, I might preserve more than a fossil.'
<br>**Research Aspect Description:** \[Valenzuela and I count ourselves among the few who benefit from the work of the cast-down Hour called Blackbone, as we used a part of its hoard to extract an essence of the Carapace Cross.]
<br>**Effect:** Lesson: [[s.meontologicalglimpses|Meontological Glimpses]] (x2)
<br>**Mutation Effect:** valenzuela -> research 4
### Assisting Valenzuela
`talk.faculty.failure5.valenzuela`
<br>**Requirements:** valenzuela, ability, research 4
<br>**Start Description:** 'When we were traveling, you could say we knew many things. But the Cross do not 'know' in the way of books or records; I was of instinct and memory. Even without life, the carapace remembers to twitch and to curl upon itself. If I can recover some small part of that knowledge I had when I was other–when I was behind the Sky–I could make something miraculous happen. But I must find a way to remember what it was like to be among the stars.'
### Assisting Valenzuela
`talk.faculty.success5.valenzuela.didumos`
<br>**Requirements:** valenzuela, ability, research 4, [didumos](https://uadaf.theevilroot.xyz/rowenarium/element/didumos)
<br>**Start Description:** 'The *didumos* was generous. I felt its cold quiet the blood in my veins for a moment, and the hemolymph return. I know now–no, I feel now–how to do something incredible.'
<br>**Research Aspect Description:** \[I reconnected Valenzuela with her other life behind the Sky and reawakened and instinctual knowledge within her.]
<br>**Effect:** x.resurgences.emergences (x2)
<br>**Mutation Effect:** valenzuela -> research 5
### Assisting Valenzuela
`talk.faculty.failure6.valenzuela`
<br>**Requirements:** valenzuela, ability, research 5
<br>**Start Description:** 'The Stones will speak, but we must choose from which we will excavate. I see three potential digs: the mountains themselves, the Spine of the World; the scattered stones and their mournful songs; or you, librarian, and the inheritance of the Carapace Cross I feel thrumming in your chest as we speak.'
### Earning valenzuela's Respect
`talk.faculty.success6.valenzuela.spine`
<br>**Requirements:** valenzuela, ability, research 5, [[numen.spine|Numen: The Spine's Awakening]]
<br>**Start Description:** 'In the era before scars, these mountains were seamless and their rulers were the dragons. There are fossils here in the Andes which never tasted Hour-flesh. Perhaps we ought make a reminder to the worms of what they once were. Let me teach you how to bring back a dragon; not any bone will do. You must find some flesh that still moves.'
<br>**Research Aspect Description:** \[I assisted Valenzuela in fulfilling her work: bringing forth a mighty demonstration of the fossils beneath the mountains.]
<br>**Effect:** [[remedy.valenzuela|Valenzuela's Remedy]], -1 valenzuela, [[x.awaken.relic|Lesson: Awaken a Relic]
<br>**Mutation Effect:** valenzuela -> +1 grateful
### Earning valenzuela's Respect
`talk.faculty.success6.valenzuela.stone`
<br>**Requirements:** valenzuela, ability, research 5, [[numen.stone|Numen: The Traveling Stones]]<br>
**Start Description:** 'Ever since my return, I have felt I am the only one who knows how the stones speak. Now, at last, you also hear them. We must make everyone hear this song. The halls of the Haustorium will echo with the mournful war-songs of the fallen dragonslayers, the defeated Blomberende. I will invoke their moirologist, and you will place her in the apiary. Then no one will forget that the stones speak still.'
<br> **Research Aspect Description:** \[I assisted Valenzuela in fulfilling her work: returning the songs of the vanquished dragonslayers to the halls of the Haustorium.]
<br>**Effect:** [[remedy.valenzuela|Valenzuela's Remedy]], [[wayrapuka|Wayrapuka, who Weeps]]
<br>**Mutation Effect:** valenzuela -> +1 grateful
### Earning valenzuela's Respect
`talk.faculty.success6.valenzuela.scion`
<br>**Requirements:** valenzuela, ability, research 5, [[numen.scion|Numen: The Unnamed Scion]]
<br>**Start Description:** 'The Gods-from-Stone left their heir to return, and all of you who know this secret must decide whether to kneel or resist. Your ancestors who passed within did not abandon you, librarian. If you carry the knowledge of who they served and know who it is you may once again serve, I can help you be more. Do you feel your eyes becoming compound as I speak? The change has already begun, colleague.'
<br>**Research Aspect Description:** \[I assisted Valenzuela in fulfilling her work: awakening the fragment of the Cross within me, and making me something else.]
<br>**Effect:** [[remedy.valenzuela|valenzuela's Remedy]], [[sebast|Sebast]]
<br>**Mutation Effect:** valenzuela -> +1 gratefulÏ