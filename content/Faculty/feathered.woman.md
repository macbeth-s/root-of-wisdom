---
tags:
  - faculty
---
# The Feathered Woman
She is recorded in the Faculty roster by this name, but Robigo does not speak of her. She has appeared seven times in the Haustorium's history, by seven names. Now she appears to me.
## Aspects
- Interest: Moon 7
- Interest: Scale 7
- Interest: Nectar 7
- Understands Vak
- Understands Cracktrack
- [[Faculty]]
## Talk
### An Unimpressed Academic?
`talk.faculty.feathered.woman.sceptical.intro`
<br>**Requirements:** Talk, feathered.woman, sceptical
<br>**Start Description:** She has appeared. She watches from across the cavern. Dare I watch back? \[The academic culture at the Haustorium is generally unfriendly. It takes effort to be worth the faculty’s time.]
### An Unimpressed Academic
`talk.faculty.feathered.woman.sceptical.hint`
<br>**Requirements:** Talk, feathered.woman, interest=mystery, sceptical, readable, -1 artifact
<br>**Start Description:** 'There are no words you could show me which would open my eyes any further.'
### Impressing an Academic
`talk.faculty.feathered.woman.sceptical`
<br>**Requirements:** Talk, feathered.woman, interest=mystery, sceptical, artifact
<br>**Start Description:** 'Eternity up, Death down, Life behind, History ahead. You seek answers among Silk, Shell, and Blood. You are servant to many, but master of what matters. You have passed the Threshold to Greatness but not to Knowledge, you have escaped Death and will escape it still.'
<br>**Effect:** [Earth-sign](https://uadaf.theevilroot.xyz/rowenarium/element/earthsign)
<br> **Mutation Effect:** feathered.woman -> -1 sceptical
### A Conversation with The Feathered Woman
`talk.faculty.intro.feathered.woman`
<br>**Requirements:** Talk, feathered.woman, -1 sceptical
<br>**Start Description:** 'Shall we be uprooted?' \[The faculty can tutor you in a language and comment on Incidents, or you can assist them with their ongoing research by offering a soul-element.]
### Assisting The Feathered Woman
`talk.faculty.assist.feathered.woman`
<br>**Requirements:** Talk, feathered.woman, ability
<br>**Start Description:** 'You offer of yourself to this place. There is more you can offer.' \[The faculty's needs can be exacting, but academic work is slow. If you can't find exactly what you need, they'll ignore you until you have something to offer.]
### Assisting The Feathered Woman
`talk.faculty.failure1.feathered.woman`
<br>**Requirements:** Talk, feathered.woman, ability, -1 research
<br>**Start Description:** 'You are limited by the present. You see only the tree, but this place has always been marked by its flower. Bring what it Was or what it Is, and the truth of the bloom might reveal more about the choice before you.'
### Assisting The Feathered Woman
`talk.faculty.success1.feathered.woman.snow.plant`
<br>**Requirements:** Talk, feathered.woman, ability, [[snow.plant|Snow Plant]]
<br>**Start Description:** 'This is the flower of the Haustorium. It speaks of a place that blooms, that infests. It has not always been this way. The Haustorium Is, the Ruin of the Roots Was. Both were given shelter, protected by one outside the Law. Go on and seek out the fullness of this place. Its dangers will part for my word.'
<br>**Research Aspect Description:** \[The Feathered Woman taught me to see the Tree's nature in its flowers, and that the Flower of the Haustorium has not always been as it is now.]
<br>**Effect:** [[permission.feathered.woman|The Feathered Woman's Permission]]
<br> **Mutation Effect:** feathered.woman -> +1 research1
### Assisting The Feathered Woman
`talk.faculty.success1.feathered.woman.helical.chuquiraga`
<br>**Requirements:** Talk, feathered.woman, ability, [[helical.chuquiraga|Helical Chuquiraga]]
<br>**Start Description:** 'This was the flower of the Ruin of the Roots. It speaks of a place that nourishes, that survives. It did not stay this way. The Haustorium Is, the Ruin of the Roots Was. Both were given shelter, protected by one outside the Law. Go on and seek out the fullness of this place. Its dangers will part for my word.'
<br>**Research Aspect Description:** \[The Feathered Woman taught me to see the Tree's nature in its flowers, and that the Flower of the Haustorium has not always been as it is now.]
<br>**Effect:** [[permission.feathered.woman|The Feathered Woman's Permission]]
<br> **Mutation Effect:** feathered.woman -> +1 research1
### Assisting The Feathered Woman
`talk.faculty.failure2.feathered.woman`
<br>**Requirements:** Talk, feathered.woman, ability, research1
<br>**Start Description:** 'You seek me in the hidden places, in the hollow of the world. Others have sought me here in the same way. I can tell you of the words spoken to them, if you show me those songs which echo beneath the earth, or if you recount the tales of those who found me here.'
### Assisting The Feathered Woman
`talk.faculty.success2.feathered.woman.hill.hollow`
<br>**Requirements:** Talk, feathered.woman, ability, research1, r.hill.hollow, soph:4
<br>**Start Description:** 'From within these tunnels I have been six times oracle, now to you seventh. To Cipagauta I could speak only woe, to Quilaco impending weal, but to Leonor I could tell the whole truth. Nothing in the order of Hours persists, no stone set remains forever. She saw the end of her life, her empire, her Sun, her love, and still she chose to act. What will you do, librarian?'
<br>**Research Aspect Description:** \[The Feathered Woman told me of her past prophecies, and of how Leonor never despaired even when she knew of the terrors to come.]
<br>**Effect:** x.raggedcrossroads
<br> **Mutation Effect:** feathered.woman -> +1 research2
### Assisting The Feathered Woman
`talk.faculty.success2.feathered.woman.thetaleofleonortapestry`
<br>**Requirements:** Talk, feathered.woman, ability, research1, [[t.thetaleofleonortapestry|The Tale of Leonor: Tapestry]]
<br>**Start Description:** 'From within these tunnels I have been six times oracle, now to you seventh. To Cipagauta I could speak only woe, to Quilaco impending weal, but to Leonor I could tell the whole truth. Nothing in the order of Hours persists, no stone set remains forever. She saw the end of her life, her empire, her Sun, her love, and still she chose to act. What will you do, librarian?'
<br>**Research Aspect Description:** \[The Feathered Woman told me of her past prophecies, and of how Leonor never despaired even when she knew of the terrors to come.]
<br>**Effect:** x.raggedcrossroads
<br> **Mutation Effect:** feathered.woman -> +1 research2
### Assisting The Feathered Woman
`talk.faculty.success2.feathered.woman.caveechoes`
<br>**Requirements:** Talk, feathered.woman, ability, research1, [[t.caveechoes|Cave-Echoes]]
<br>**Start Description:** 'From within these tunnels I have been six times oracle, now to you seventh. To Cipagauta I could speak only woe, to Quilaco impending weal, but to Leonor I could tell the whole truth. Nothing in the order of Hours persists, no stone set remains forever. She saw the end of her life, her empire, her Sun, her love, and still she chose to act. What will you do, librarian?'
<br>**Research Aspect Description:** \[The Feathered Woman told me of her past prophecies, and of how Leonor never despaired even when she knew of the terrors to come.]
<br>**Effect:** x.raggedcrossroads
<br> **Mutation Effect:** feathered.woman -> +1 research2
### Assisting The Feathered Woman
`talk.faculty.success2.feathered.woman.spelunking`
<br>**Requirements:** Talk, feathered.woman, ability, research1, [[t.againstspelunkingdelvingandotherendeavorsofgreatfoolishanddestructiveends|Against Spelunking, Delving, and Other Endeavors of Great Foolish and Destructive Ends]]
<br>**Start Description:** 'From within these tunnels I have been six times oracle, now to you seventh. To Cipagauta I could speak only woe, to Quilaco impending weal, but to Leonor I could tell the whole truth. Nothing in the order of Hours persists, no stone set remains forever. She saw the end of her life, her empire, her Sun, her love, and still she chose to act. What will you do, librarian?'
<br>**Research Aspect Description:** \[The Feathered Woman told me of her past prophecies, and of how Leonor never despaired even when she knew of the terrors to come.]
<br>**Effect:** x.raggedcrossroads
<br> **Mutation Effect:** feathered.woman -> +1 research2
### Assisting The Feathered Woman
`talk.faculty.failure3.feathered.woman`
<br>**Requirements:** Talk, feathered.woman, ability, research2
<br>**Start Description:** 'When the world was young, I was here. The great heroes of the first age sought my counsel in their quests, but in my youth I was afeared. If you could see through my eyes, or speak to me of those slain heroes' tragedies, I could make you understand. But you are likely too young–younger even than I was in those days.'
### Assisting The Feathered Woman
`talk.faculty.success3.feathered.woman.music.hive`
<br>**Requirements:** Talk, feathered.woman, ability, research2
<br>**Start Description:** 'It was only one of the bee-heroes who found me. I could tell her only the truth, and she despaired so deeply for our kind that she weeps still. I was always afraid of the dragonslayers, just as I was afraid to fly. But I was never afraid to learn, and so I kept my gaze turned towards the roots. I saw blood spilt of all colors–Gold, Red, Green–and I saw Histories born. There is more to be said, when next you descend here.'
<br>**Research Aspect Description:** \[The Feathered Woman ceased to speak of the future and instead spoke of her youth in an era long past, when she was afraid to fly with her kin.]
<br>**Effect:** x.sights.sensations
<br> **Mutation Effect:** feathered.woman -> +1 research3
### Assisting The Feathered Woman
`talk.faculty.success3.feathered.woman.old.moment`
<br>**Requirements:** Talk, feathered.woman, ability, research2
<br>**Start Description:** 'The world must be understood not through a single gaze, but through many. I was the last of my many-eyed kin, the smallest and weakest. I was afraid to fly, but I was never afraid to learn, and so I kept my gaze turned towards the roots. I saw blood spilt of all colors–Gold, Red, Green–and I saw Histories born. There is more to be said, when next you descend here.'
<br>**Research Aspect Description:** \[The Feathered Woman ceased to speak of the future and instead spoke of her youth in an era long past, when she was afraid to fly with her kin.]
<br>**Effect:** x.sights.sensations
<br> **Mutation Effect:** feathered.woman -> +1 research3
### Assisting The Feathered Woman
`talk.faculty.failure4.feathered.woman`
<br>**Requirements:** Talk, feathered.woman, ability, research3
<br>**Start Description:** 'I will speak to you of my sin, if you will show me you know from whom sin originates. The Law is now governed by three, and their rule is absolute. Or speak to me of my sister-in-sin Medusa, and of how her crimes are to be imitated.'
### Assisting The Feathered Woman
`talk.faculty.success4.feathered.woman.edictsliminal`
<br>**Requirements:** Talk, feathered.woman, ability, research3, r.edictsliminal, soph:10
<br>**Start Description:** 'The Edicts of the Chancel have now established your Law: the Crime of the Sky, greatest among them. But in the days when the Sky was governed by another, this was not a Crime. The Low Red Sun permitted much, but what he could not abide was the Crime of Ado, the Crime of Sight, the Gaze-turned-Elsewhere. It was in my nature to See. So it was my fate to be cast out at the Gods-from-Stone's Behest.'
<br>**Research Aspect Description:** \[The Feathered Woman spoke of the mutability of Law, and how in the time before the Chancel established the Crime of the Sky, it was forbidden to become Know.]
<br>**Effect:** x.meontologicalglimpses (x2)
<br> **Mutation Effect:** feathered.woman -> +1 research4
### Assisting The Feathered Woman
`talk.faculty.success4.feathered.woman.medusancommentaries`
<br>**Requirements:** Talk, feathered.woman, ability, research3, [[t.medusancommentariesunpublishedmanuscript|Medusan Commentaries (Unpublished Manuscript)]]
<br>**Start Description:** 'The Ligeians are set apart because of the Crime of the Sky. But before Medusa trespassed, this was not a Crime. The Low Red Sun permitted much, but what he could not abide was the Crime of Ado, the Crime of Sight, the Gaze-turned-Elsewhere. It was in my nature to See. So it was my fate to be cast out at the Gods-from-Stone's Behest.'
<br>**Research Aspect Description:** \[The Feathered Woman spoke of the mutability of Law, and how in the time before the Chancel established the Crime of the Sky, it was forbidden to become Know.]
<br>**Effect:** [[s.meontologicalglimpses|x.meontologicalglimpses]] (x2)
<br> **Mutation Effect:** feathered.woman -> +1 research4
### Assisting The Feathered Woman
`talk.faculty.failure5.feathered.woman`
<br>**Start Description:** 'The last question is of this place. Why do I persist, when the Protector would wish me gone? It is a story told in a gnarled root, in the shape of the tangled Histories, in ancient geometry.'
### Assisting The Feathered Woman
`talk.faculty.success5.feathered.woman.haustorical.pentagram`
<br>**Requirements:** Talk, feathered.woman, ability, research4
<br>**Start Description:** 'Can you see it here? A place that begins in the Cross's blood falling on the roots of the queñua, the theft of eggs from hidden nests, the setting of the stone... There was a brief time when I was the one who watched and guarded. But it was not to last: the Protector is also outside the law, and its greed far surpasses mine. I have acquiesced. So I watch, but I do not protect.'
<br>**Research Aspect Description:** \[The Feathered Woman revealed that for a short time before Robigo's arrival, she was the Protector of the library here.]
<br>**Effect:** [[t.inscribedandesitetablet|Inscribed Andesite Tablet]]
<br> **Mutation Effect:** feathered.woman -> +1 research5
### Assisting The Feathered Woman
`talk.faculty.failure6.feathered.woman`
<br>**Requirements:** Talk, feathered.woman, ability, research5
<br>**Start Description:** 'There is nothing else in the past. There is only your choice. I can offer you Knowledge of the beginnings of things, Greatness in the eyes of the Hours, or if you can learn to forgive your weakness, I may be able to offer Wisdom.'
### Earning The Feathered Woman's Respect
`talk.faculty.success6.feathered.woman.hour`
<br>**Requirements:** Talk, feathered.woman, ability, research5, [[numen.hour|Numen: Before All Hours]]
<br>**Start Description:** 'So you have chosen Knowledge. Many others have done the same. These answers lie in word and relic, in study and seriousness. Be Knowing. You will join others on this path, but you will not have doubts.'
<br>**Research Aspect Description:** \[The Feathered Woman guided me towards my goal: Knowledge of the truth, at the expense of all else.]
<br>**Effect:** [[remedy.feathered.woman|The Feathered Woman's Remedy]], [[x.awen]], [[x.duende]], [[x.epiphany]], [[x.ubisunt]]
<br> **Mutation Effect:** feathered.woman -> +1 grateful
### Earning The Feathered Woman's Respect
`talk.faculty.success6.feathered.woman.puzz`
<br>**Requirements:** Talk, feathered.woman, ability, research5, [[numen.puzz|Numen: Penultimate Puzzle]]
<br>**Start Description:** 'So you have chosen Greatness. This was the path of the dragonslayer, the Colonel, the Mother of Ants. From your pen the Histories will bleed. You will be victorious.'
<br>**Research Aspect Description:** \[The Feathered Woman guided me towards my goal: achieving Greatness and leaving my mark on History, at the expense of all else.]
<br>**Effect:** [[remedy.feathered.woman|The Feathered Woman's Remedy]], [[x.theblood|Lesson: The Blood of History]]
<br> **Mutation Effect:** feathered.woman -> +1 grateful
### Earning The Feathered Woman's Respect
`talk.faculty.success6.feathered.woman.tresp`
<br>**Requirements:** Talk, feathered.woman, ability, research5, [[numen.tresp|Numen: A Trespass Forgiven]]
<br>**Start Description:** 'So you have chosen Wisdom. This has always been a choice, but it has not been taken. To walk this path is to forswear your purpose. You may still turn away.'
<br>**Research Aspect Description:** \[The Feathered Woman guided me towards my goal: Wisdom, at the expense of all else.]
<br>**Effect:** [[remedy.feathered.woman|The Feathered Woman's Remedy]], [[numen.wis|Numen?: Wisdom]]
<br> **Mutation Effect:** feathered.woman -> +1 grateful