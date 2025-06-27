---
tags:
  - faculty
---
# Shura the Pythian
A child? An old woman? Their voice is sweet like stomach bile and their eyes are red like blood.
## Aspects
- [[faculty|Faculty]]
- Interest: Grail 7
- Interest: Heart 7
- Interest: Sky 7
- Understands Hyksos
- Understands Fucine
## Talk
### An Unimpressed Academic?
`talk.faculty.Shura.sceptical.intro
**Requirements:** shura, sceptical
<br>**Start Description:** 'You are not who I hoped to see. Leave.' \[The academic culture at the Haustorium is generally unfriendly. It takes effort to be worth the faculty’s time.]
### Impressing an Academic
`talk.faculty.Shura.sceptical
**Requirements:** shura, sceptical, interest=mystery
<br>**Start Description:** 'Oh, a bedtime story?'
<br>**Description:** 'Reading soothes me. You show me a gentle kindness.'
<br>**Effect:** [Bronze Spintria](https://uadaf.theevilroot.xyz/rowenarium/element/spintria.bronze)
<br>**Mutation Effects:** shura -> -1 sceptical
### A Conversation with Shura the Pythian
`talk.faculty.intro.Shura
**Requirements:** shura, sceptical -1
<br>**Start Description:** 'You are not who I hoped to see.' \[The faculty can tutor you in a language and comment on Incidents, or you can assist them with their ongoing research by offering a soul-element.]
### Assisting Shura the Pythian
`talk.faculty.assist.Shura
**Requirements:** shura, ability
<br>**Start Description:** 'I yearn, librarian. I yearn so deeply... perhaps you can help me end my misery.' \[The faculty's needs can be exacting, but academic work is slow. If you can't find exactly what you need, they'll ignore you until you have something to offer.]
### Assisting Shura the Pythian
`talk.faculty.failure1.Shura
**Requirements:** shura, ability, research -1
<br>**Start Description:** 'I work alone, for I am always alone... if you are to assist me, you must show me that you understand what it is to yearn and to remain unsatisfied. I will only work with you should you also sing yourself softly to sleep as you dread the sweet dreams to come.'
### Assisting Shura the Pythian
`talk.faculty.success1.Shura.saudade
**Requirements:** shura, ability, research -1, [[saudade|Saudade]]
<br>**Start Description:** 'Leonor's curse, and mine. It seems to be yours too, librarian. If you know this ache, you will be able to know my work. I am apart from the one to whom I should be closest, and I mean for us to be reunited.'
<br>**Research Aspect Description:** \[Shura and I found understanding in our shared longing for something (someone?) from which we are separated.]
<br>**Effect:** [[permission.shura|Shura's Permission]]
<br>**Mutation Effect:** shura -> research 1
### Assisting Shura the Pythian
`talk.faculty.success1.Shura.music.wistful
**Requirements:** shura, ability, research -1, [Wistful Air](https://uadaf.theevilroot.xyz/rowenarium/element/music.wistful)
<br>**Start Description:** 'It is a paradox, is it not, how something as sweet as a song can speak of something so sad as separation? If you know this ache, you will be able to know my work. I am apart from the one to whom I should be closest, and I mean for us to be reunited.'
<br>**Research Aspect Description:** \[Shura and I found understanding in our shared longing for something (someone?) from which we are separated.]
<br>**Effect:** [[permission.shura|Shura's Permission]]
<br>**Mutation Effect:** shura -> research 1
### Assisting Shura the Pythian
`talk.faculty.failure2.Shura
**Requirements:** shura, ability, research 1
<br>**Start Description:** 'You might call my work genealogical. My paternal line is simpler... I know where he has gone, just not how he got there. Bring me what you have on Transformations & Liberations, or more specifically on the paths of ascension under the aspect of Heart.'
### Assisting Shura the Pythian
`talk.faculty.success2.Shura.transformations
**Requirements:** shura, ability, research 1,  r.transformations.librations, soph: 4
<br>**Start Description:** 'I flinch at the word 'liberations,' librarian. Liberation from family? From fatherhood?! The once-man who sired me is now a duendrazone, a Long that beats with the Heart Unceasing. I will not believe he chose that nature to leave me. He chose to persist so I would never be an orphan. For that I am grateful.'
<br>**Research Aspect Description:** \[I helped Shura understand how their father came to leave them by ascending as a duendrazone under the Thunderskin.]
<br>**Effect:** x.drums.dances
<br>**Mutation Effect:** shura -> research 2
### Assisting Shura the Pythian
`talk.faculty.success2.Shura.cordite
**Requirements:** shura, ability, research 1, [[t.corditesupplications|Cordite Supplications]]
<br>**Start Description:** 'I have a womb-memory of my father speaking these prayers over me as I gestated. The once-man who sired me is now a duendrazone, a Long that beats with the Heart Unceasing. I will not believe he chose that nature to leave me. He chose to persist so I would never be an orphan. For that I am grateful.'
<br>**Research Aspect Description:** \[I helped Shura understand how their father came to leave them by ascending as a duendrazone under the Thunderskin.]
<br>**Effect:** x.drums.dances
<br>**Mutation Effect:** shura -> research 2
### Assisting Shura the Pythian
`talk.faculty.success2.Shura.leonor
**Requirements:** shura, ability, research 1, [[t.thetaleofleonorconvergence|The Tale of Leonor: Convergence]]
<br>**Start Description:** 'It was Leonor's story that brought me here. She worked so hard to be united Quilaco... I seek to learn from her all I can. The once-man who sired me is now a duendrazone, a Long that beats with the Heart Unceasing. I will not believe he chose that nature to leave me. He chose to persist so I would never be an orphan. For that I am grateful.'
<br>**Research Aspect Description:** \[I helped Shura understand how their father came to leave them by ascending as a duendrazone under the Thunderskin.]
<br>**Effect:** x.drums.dances
<br>**Mutation Effect:** shura -> research 2
### Assisting Shura the Pythian
`talk.faculty.failure3.Shura
**Requirements:** shura, ability, research 2
<br>**Start Description:** 'Would you help me with a medical issue? I have a wound in my heel cord and a burning across my skin. The Dottore always has a remedy for me, but sometimes all I need is a drink strong enough to dull the pain.'
### Assisting Shura the Pythian
`talk.faculty.success3.Shura.salve
**Requirements:** shura, ability, research 2, [[salve.protector|Protector's Salve]]
<br>**Start Description:** 'That feels much better. I am not immortal... I am not even old. But my flesh is of a different nature through the traumas of my second birth, and many mortal remedies do nothing for me. I am grateful to the midwives of my second birth, but they saw me as a tool in service of their quest for perpetual youth. I will not be so used by the Applebright.'
<br>**Research Aspect Description:** \[I treated Shura's wounds and learned that they suffer from many debilitations tied to their difficult 'second birth' facilitated by a cult of the Applebright.]
<br>**Effect:** x.applebrighteuphanies
<br>**Mutation Effect:** shura -> research 3
### Assisting Shura the Pythian
`talk.faculty.success3.Shura.chicha
**Requirements:** shura, ability
<br>**Start Description:** 'Something to take the edge off. I am not immortal... I am not even old. But my flesh is of a different nature through the traumas of my second birth, and many mortal remedies do nothing for me. I am grateful to the midwives of my second birth, but they saw me as a tool in service of their quest for perpetual youth. I will not be so used by the Applebright.'
<br>**Research Aspect Description:** \[I treated Shura's wounds and learned that they suffer from many debilitations tied to their difficult 'second birth' facilitated by a cult of the Applebright.]
<br>**Effect:** x.applebrighteuphanies
<br>**Mutation Effect:** shura -> research 3
### Assisting Shura the Pythian
`talk.faculty.failure4.Shura
**Requirements:** shura, ability, research 3
<br>**Start Description:** 'It is time for me to reconnect with the ones who saved me, then used me, then abandoned me. If I am to contact them, I need to ensure my letter is worded properly to not betray my location. The methods of the prodigal called Phalanx might be helpful, or anything about the most complex arts of occlusion.'
### Assisting Shura the Pythian
`talk.faculty.success4.Shura.edictsinviolable
**Requirements:** shura, ability, research 3, r.edictsinviolable, soph: 10
<br>**Start Description:** 'Here, Calyptra protects me from many who wish to find me: the Midwives of Pythia, any number of Reckoners, my mother. I wish I could reveal myself and welcome them all to be with me here. But as long as the Crime of the Sky is punished and the Ligeia Club feels its hunger, I must keep myself safe. I believe I am close to figuring out how to avoid the Chancel's laws so that my mother might come here without wishing to swallow me again.'
<br>**Research Aspect Description:** \[Shura revealed their mother to be a Ligeian who devoured them, regurgitated them, and hungers for them still.]
<br>**Effect:** x.edictsliminal (x2)
<br>**Mutation Effect:** shura -> research 4
### Assisting Shura the Pythian
`talk.faculty.success4.Shura.colophon
**Requirements:** shura, ability, research 3, [[t.thechildofcolophon|The Child of Colophon]]
<br>**Start Description:** 'Here, I can use Phalanx's methods to protect myself from those who wish to find me: the Midwives of Pythia, any number of Reckoners, my mother. I wish I could reveal myself and welcome them all to be with me here. But as long as the Crime of the Sky is punished and the Ligeia Club feels its hunger, I must keep myself safe. I believe I am close to figuring out how to avoid the Chancel's laws so that my mother might come here without wishing to swallow me again.'
<br>**Research Aspect Description:** \[Shura revealed their mother to be a Ligeian who devoured them, regurgitated them, and hungers for them still.]
<br>**Effect:** x.edictsliminal (x2)
<br>**Mutation Effect:** shura -> research 4
### Assisting Shura the Pythian
`talk.faculty.failure5.Shura
**Requirements:** shura, ability, research 4
<br>**Start Description:** 'The Midwives have sent their reply, and they rejoice to know I live, though they would rather I be with them. They have also warned me that it is only through the most powerful protective arts that I can stand to be with my mother for long. I will look to Leonor's example, and bring my mother to a meeting-place through the same arts that Leonor brought Quilaco here. With a mighty curio of Heart, perhaps I can survive long enough to rest in my mother's embrace.'
### Assisting Shura the Pythian
`talk.faculty.success5.Shura.lazo.quilaco
**Requirements:** shura, ability, research 4, [[lazo.quilaco|Quilaco's Lazo]]
<br>**Start Description:** 'Quilaco's guide, Leonor's design... now my only safety, and my only hope. I will go into the Wound-Roots, as Leonor did, and bind my mother with the lazo so that she might follow our tether–not her hunger–to me. Through the greatest arts of binding I know–the Sister's love that tames the Witch's hunger, the Witch's art which awakens the sister's power–I think I will live. I think I will weep. I hope I will find my peace.'
<br>**Research Aspect Description:** \[I provided Shura with Quilaco's Lazo, a device powerful enough to bring Shura's mother to the Haustorium while protecting Shura from their hunger.]
<br>**Effect:** x.stitching.binding (x2)
<br>**Mutation Effect:** shura -> research 5
### Assisting Shura the Pythian
`talk.faculty.failure6.Shura
**Requirements:** shura, ability, research 5
<br>**Start Description:** 'It was more than I hoped for. She was not the shadow of teeth I remember on dark nights, nor the shrouds of warmth I remember on sweet nights. She was the most fearsome and beautiful thing. She did not hold me, but she spoke. I spoke too, though I was overcome with my sobs. I want to see her again, but I saw how her every impulse strove against my bindings. The arts of Sky teach me to find peace, the arts of Grail teach me to embrace the Crime, and the arts of Heart teach me to find union. Which do you recommend, librarian?'
### Earning Shura's Respect
`talk.faculty.success6.Shura.kind
**Requirements:** shura, ability, research 5, [[numen.kind|Numen: A Kind Amnesia]]
<br>**Start Description:** 'You wish to do me a kindness. I see that. It fills my bones with despair to hear you argue for my capitulation like this. And yet it is that very despair I would be free of were I to follow your guidance. I will embrace the White Flower, the Limestone Egg, and end my misery. I will be someone else. But I will not be sad. I do not know if you have saved me, librarian, but you have certainly chosen to help. Here, before I forget my mother, is my remedy.'
<br>**Research Aspect Description:** \[I assisted Shura in fulfilling their work: forgetting their mother's existence and nature through the might of the White Flower and finding peace.]
<br>**Effect:** [[remedy.shura|Shura's Remedy]], [[shura.orphan|Shura the Orphan]], -1 shura
<br>**Mutation Effect:** shura.orphan -> +1 grateful
### Earning Shura's Respect
`talk.faculty.success6.Shura.incu
**Requirements:** shura, ability, research 5, [[numen.incu|Numen: Incubation]]
<br>**Start Description:** 'You suggest I become the parent I never had. You suggest I use these devilish arts to give the light to my own forbidden child, as my parents did. You suggest that would bring me some satisfaction. I think you are right. I think I will be the parent mine were not, through these schemes of the Red Flower. Lay my child's cinnabar egg in the cradle, librarian, and come visit us often. She will hatch a beautiful and beloved thing.'
<br>**Research Aspect Description:** \[I assisted Shura in fulfilling their work: hatching a forbidden child of their own who might become a focus for their unfulfilled need for love.]
<br>**Effect:** [[remedy.shura|Shura's Remedy]], [[egg.mare|Vermillion Egg]]<br>**Mutation Effect:** shura -> +1 grateful
### Earning Shura's Respect
`talk.faculty.success6.Shura.void
**Requirements:** shura, ability, research 5, [[numen.void|Numen: The Void Between]]
<br>**Start Description:** 'The root of my sorrow has not been my mother, but the punishment enforced upon her by the cruelty of the Hours. Her so-called Crime and her appointed punishment has hurt me more than her, and I will never be happy as long as we are apart. The Black Flower teaches the ways of obscurity and escape which my mother might use to avoid her ravenous punishment. In the shelter of the place where the obsidian egg was concealed, she will feel no hunger. We will meet in the caverns, below the Angstloch, in the darkness of the New Moon, and we will be child and daughter as we should.
<br>**Research Aspect Description:** \[I assisted Shura in fulfilling their work: creating a secret sanctum outside of the rules of the Hours where the Crime of the Sky was not punished and they and their mother can be together.]
<br>**Effect:** [[remedy.shura|Shura's Remedy]], [[void.key|Void-Key]]
<br>**Mutation Effect:** shura -> +1 grateful