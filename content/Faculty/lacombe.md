---
tags: faculty
---
# Charles Lacombe
A former agent of Britain's ruthless Suppression Bureau, now transformed. Terminally robigoid, preserved through the generostiy of the Protector.
## Aspects
- Interest: Moth 7
- Interest: Lantern 7
- Interest: Forge 7
- Understands Sabazine
- Understands Greek
- [[Faculty]]
## Talk
### An Unimpressed Academic?
`talk.faculty.lacombe.sceptical.intro`
<br>**Requirements:** lacombe, sceptical
<br>**Start Description:** 'My focus is on keeping my lungs moving right now. I can't be bothered with meddlers and marplots.' \[The academic culture at the Haustorium is generally unfriendly. It takes effort to be worth the faculty’s time.]
### Impressing an Academic
`talk.faculty.lacombe.sceptical`
<br>**Requirements:** lacombe, sceptical, interest=mystery
<br>**Start Description:** 'I do have a reason to read this one, though.'
<br>**Description:** 'The Dottore likes be to keep abreast of the collection, and often suggests uses for its knowledge when we meet. Cheers.'
<br>**Effect:** [Bronze Spintria](https://uadaf.theevilroot.xyz/rowenarium/element/spintria.bronze)
<br>**Mutation Effects:** lacombe -> -1 sceptical
### A Conversation with Lacombe
`talk.faculty.intro.lacombe`
<br>**Requirements:** lacombe, sceptical -1
<br>**Start Description:** Lacombe wheezes. 'Cheers.' \[The faculty can tutor you in a language and comment on Incidents, or you can assist them with their ongoing research by offering a soul-element.]
### Assisting Lacombe
`talk.faculty.assist.lacombe`
<br>**Requirements:** lacombe, ability
<br>**Start Description:** ''I'm here on borrowed time (and borrowed lungs), so I need to get cracking on the work I came here for in the first place. Spare a minute to help me out?' \[The faculty's needs can be exacting, but academic work is slow. If you can't find exactly what you need, they'll ignore you until you have something to offer.]

### Assisting Lacombe
`talk.faculty.failure1.lacombe`
<br>**Requirements:** lacombe, ability, research -1<br>**Start Description:** 'This first errand is one we ought keep between ourselves. I've got a few pages here of stuff that really nobody needs to be reading, least of all that cat that comes riling through my stuff, or that scary nun who stalks about. All I've got is some stargall when another ink would be much more suitable to my more delicate materials, or you could head down to the garden and find me a fungal reagent that could take care of the documents just as well.' 
### Assisting Lacombe
`talk.faculty.success1.lacombe.catwink`
<br>**Requirements:** lacobe, ability, research -1, [catwink](https://uadaf.theevilroot.xyz/rowenarium/element/catwink)
<br>**Start Description:** 'Thanks, chap. This'll do to keep the Cupcake away. And I'll just spread some muck on the carpet to keep the good Sister distracted. I used to carry around files on nasty people, you see. But nowawdays I mostly find myself corresponding with them. It's dangerous work to betray Calyptra like this, but I'm in a bit of a corner.'
<br>**Research Aspect Description:** \[I helped Lacombe shield some delicate files from the eyes of the rest of the Faculty, and learned of his ongoing correspondence with some 'nasty people.']
<br>**Effect:** [[permission.lacombe|Lacombe's Permission]]
<br> **Mutation Effect:** lacombe -> research 1
### Assisting Lacombe
`talk.faculty.success1.lacombe.moldgloss`
<br>**Requirements:** lacombe, ability, research -1, [[moldgloss|Moldgloss]]
<br>**Start Description:** ''Thanks, chap. A good smearing of this always does wonders to keep prying eyes averted. I used to carry around files on nasty people, you see. But nowawdays I mostly find myself corresponding with them. It's dangerous work to betray Calyptra like this, but I'm in a bit of a corner.''
<br>**Research Aspect Description:** \[I helped Lacombe shield some delicate files from the eyes of the rest of the Faculty, and learned of his ongoing correspondence with some 'nasty people.']
<br>**Effect:** [[permission.lacombe|Lacombe's Permission]]
<br> **Mutation Effect:** lacombe -> research 1
### Assisting Lacombe
`talk.faculty.failure2.lacombe`
<br>**Requirements:** lacombe, ability, research 1
<br>**Start Description:** 'I've made some bad decisions in my day, see. There's no going back now... I've tried a great many methods to live with the thing I took into my abdomen–the caul–back in Velletri. The Dottore's always got some remedy, but I'd like to develop a little more autonomy. What can you find me on Herbs and Infusions? Or maybe I ought look to the techniques they used in Pontus to preserve themselves against poison.'
### Assisting Lacombe
`talk.faculty.success2.lacombe.herbs`
<br>**Requirements:** lacombe, ability, research 1,  r.herbs.infusions, soph: 4
<br>**Start Description:** 'A cup of tea has great healing power, especially when you make it here. With every advancement, I see a way away from the Dottore's control. My question then is who my new benefactor will be. A turncoat officer cannot last long in the Invisible World without someone powerful backing them up.'
<br>**Research Aspect Description:** \[I advised Lacombe on medical techniques to break his dependence on the Dottore's healing, allowing him to begin considering other benefactors who might not be so demanding of him.]
<br>**Effect:** x.raggedcrossroads
<br>**Mutation Effect:** lacombe -> research 2
### Assisting Lacombe
`talk.faculty.success2.lacombe.mithradatic`
<br>**Requirements:** lacombe, ability, research 1, [[t.themithradaticgenesis|The Mithradatic Genesis]]
<br>**Start Description:** 'Like the Great King, I can build tolerance enough to survive. With every advancement, I see a way away from the Dottore's control. My question then is who my new benefactor will be. A turncoat officer cannot last long in the Invisible World without someone powerful backing them up.'
<br>**Research Aspect Description:** \[I advised Lacombe on medical techniques to break his dependence on the Dottore's healing, allowing him to begin considering other benefactors who might not be so demanding of him.]
<br>**Effect:** x.raggedcrossroads
<br>**Mutation Effect:** lacombe -> research 2
### Assisting Lacombe
`talk.faculty.failure3.lacombe`
<br>**Requirements:** lacombe, ability, research 2
<br>**Start Description:** 'I must turn now to anatomy. When I came upon this great trove at Ortucchio, the Dottore insisted I would only be increased by incoprorating what I found. It was the promise that I might be something great that lured me away from my duty... I need to study other bundles of moth-touched warp-flesh to see what pitiable or enviable forms I might still take.'
### Assisting Lacombe
`talk.faculty.success3.lacombe.larva`
**Requirements:** lacombe, ability, research 2, [larva.chimeric](https://uadaf.theevilroot.xyz/rowenarium/element/larva.chimeric)
<br>**Start Description:** 'Although I am well past middle-age, I am in many ways still pupate. The Dottore does not much publicize his relations with the Moth, but the old lad loves to exploit the mania of the Change. If I'm to thread this needle, I'll need to watch the difference between changing and growing very carefully. With your help, mate, I can find my way through these tangling woods.
<br>**Research Aspect Description:** \[I helped Lacombe analyze a creature of perilous potential, spying a way through the Moth that he might embrace the changes within himself without being consumed by the Growth.]
<br>**Effect:** x.sylvanstories 
<br>**Mutation Effect:** lacombe -> research 3
### Assisting Lacombe
`talk.faculty.success3.lacombe.substrate`
<br>**Requirements:** lacombe, ability, research 2, [[substrate.tame|Shambling Substrate]]
<br>**Start Description:** 'That which we take into us always changes us... The Dottore does not much publicize his relations with the Moth, but the old lad loves to exploit the mania of the Change. If I'm to thread this needle, I'll need to watch the difference between changing and growing very carefully. With your help, mate, I can find my way through these tangling woods.'
<br>**Research Aspect Description:** \[I helped Lacombe analyze a creature of perilous potential, spying a way through the Moth that he might embrace the changes within himself without being consumed by the Growth.]
<br>**Effect:** x.sylvanstories 
<br>**Mutation Effect:** lacombe -> research 3
### Assisting Lacombe
`talk.faculty.failure4.lacombe`
<br>**Requirements:** lacombe, ability, research 3
<br>**Start Description:** 'Since our last realization, I've been walking more in the wood. Well, stumbling, really. On my last venture I found myself suckling at the tea party of a Name of the Mare-in-the-Tree; a woman who came to visit me shortly before my little pyrotechnics display at the Cucurbit Gaol. She goaded me on to another stunt here; can you see the flames dancing in my eyes? I need some technique I can use to impress the Mare without enraging the Dottore. Find me something sophisticated on fire and smoke \[10+], or some other way to appease the Red Flower...'
### Assisting Lacombe
`talk.faculty.success4.lacombe.pyroglyphics`
<br>**Requirements:** lacombe, ability, research 3, r.pyroglyphics, soph: 10
<br>**Start Description:** 'I think I can manage a way to singe and obscure, but not destroy utterly. A half-measure in Calyptra's name, as their faithful man on the inside. I feel my debts are soon come due: the Reckoners I've been updating about the visitors to the library, the Mare who wishes me return to Calyptra's fold, the Dottore who above all despises betrayal... I have pushed my luck and my lungs to their limit. I'll rest and recuperate as best I can, but then you must help me take this final step before I go the way of Kume.'
<br>**Research Aspect Description:** \[I suggested a half-measure to Lacombe to appease his master from the Calyptra, but his worries grew that his debts to other occult interests are soon come due.]
<br>**Effect:** x.edictsinviolable (x2)
<br>**Mutation Effect:** lacombe -> research 4
### Assisting Lacombe
`talk.faculty.success4.lacombe.eucalyptra`
<br>**Requirements:** lacombe, ability, research 3, [[t.eucalyptra|Eucalyptra]]
<br>**Start Description:** 'Only she would tolerate these praises, and only coated in irony. She'll accept this in lieu of arson, I hope, but I feel my debts are soon come due: the Reckoners I've been updating about the visitors to the library, the Mare who wishes me return to Calyptra's fold, the Dottore who above all despises betrayal... I have pushed my luck and my lungs to their limit. I'll rest and recuperate as best I can, but then you must help me take this final step before I go the way of Kume.'
<br>**Research Aspect Description:** \[I suggested a half-measure to Lacombe to appease his master from the Calyptra, but his worries grew that his debts to other occult interests are soon come due.]
<br>**Effect:** x.edictsinviolable (x2)
<br>**Mutation Effect:** lacombe -> research 4
### Assisting Lacombe
`talk.faculty.failure5.lacombe`
<br>**Requirements:** lacombe, ability, research 4
<br>**Start Description:** 'We're so close, but I don't know if I can make it. I feel...' Lacombe wheezes deeply, and is silent for several torturous breaths. 'There is only so much time left, but I need more, if we are to finish this. Just a little more time...'
### Assisting Lacombe
`talk.faculty.success5.lacombe.yeartally`
<br>**Requirements:** lacombe, ability, research 4, [yeartally](https://uadaf.theevilroot.xyz/rowenarium/element/yeartally)
<br>**Start Description:** 'You must be keeping in touch with the traffickers in stolen years, as well. Or are you just a gifted thaumaturgist? Either way, the White Flower will permit my persistence another year. We should finish my work in that time. I feel the warmth of accomplishment.'
<br>**Research Aspect Description:** \[I used a powerful technique of the Madrugad to buy Lacombe another year of life, allowing him time to finish his project.]
<br>**Effect:** x.quenchings.quellings (x2)
<br>**Mutation Effect:** lacombe -> research 5
### Assisting Lacombe
`talk.faculty.failure6.lacombe`
<br>**Requirements:** lacombe, ability, research 5
<br>**Start Description:** 'I received three messages last night, librarian. One was a dream of my old Aunt Mopsy, who told me that this flittering in my chest could be burnt out, but only in shadow. The next was a termination notice from the Dottore, unless I unlock the changes the caul is trying to bring out of me. The third was the blinking eye of the Reckoners–a sure sign they will kill me unless I deliver the location of the forgotten heir they claim is hidden away here. I cannot have all three of my would-be patrons abandon me. But which among them can I serve?'
### Earning Lacombe's Respect
`talk.faculty.success6.lacombe.glor`
<br>**Requirements:** lacombe, ability, research 5, [[numen.glor|Numen: Glorious Shadows]]
<br>**Start Description:** 'A shadow is never truly the shape of its occulter, it only seems to be. The Mare can teach me to sever the thrumming from myself, at least by day. At night in the Wood I may be a shambling mass of gasping wrath as the Dottore always hoped, but here I can keep this proper English shape I've grown fond of. It will burn. I am used to fire. Will you help me with the purging?'
<br>**Research Aspect Description:** \[I assisted Lacombe in fulfilling his work: burning the caul from his Wake-self and consigning his sickness only to dreams.]
<br>**Effect:** [[remedy.lacombe|Lacombe's Remedy]], -1 lacombe, [[lacombe.patient|Lacombe, My Patient]]
<br>**Mutation Effect:** lacombe -> +1 grateful
### Earning Lacombe's Respect
`talk.faculty.success6.lacombe.key`
<br>**Requirements:** lacombe, ability, research 5, [[numen.keys|Numen: Key of Keys]] <br>
**Start Description:** 'I was a fool to have ever considered an alternative. It was Robigo who showed me a way from the Suppression Bureau, it was he who gave me a second chance after my confinement in the Cucurbit Gaol. I have been ungrateful by resisting the transformations he wants for me. Unlock the caul, librarian. I am sure my sickness will worsen, but my knowledge will increase. I will entrust the fruits of my labors to you.'
<br> **Research Aspect Description:** \[I assisted Lacombe in fulfilling his work: becoming the mycological savant of the Dottore's dreams, and bringing the Crowned Growth's designs ever-nearer.]
<br>**Effect:** [[remedy.lacombe|Lacombe's Remedy]], [[spore.seed|Seeds of the Crowned Growth]]
<br>**Mutation Effect:** lacombe -> +1 grateful
### Earning Lacombe's Respect
`talk.faculty.success6.lacombe.scion`
<br>**Requirements:** lacombe, ability, research 5, [[numen.scion|Numen: The Unnamed Scion]]
<br>**Start Description:** 'The first lesson they taught me when I joined the Bureau: there's nothing more dangerous than a secret. The first lesson I learned when I betrayed the Bureau: there's nothing worth more than a secret. Even within Calyptra, there are secrets. The Reckoners sent no reply to this piece of intelligence, but I feel the Madrugad's protection around me, and they sent a gift. Feel free to use it all you want–we'll speak nothing of it.'
<br>**Research Aspect Description:** \[I assisted Lacombe in fulfilling his work: gaining a new life under the protection of the Madrugad, while remaining Calyptra's 'man on the inside.']
<br>**Effect:** [[remedy.lacombe|Lacombe's Remedy]], [[scales.cindered|Cindered Scales]]
<br>**Mutation Effect:** lacombe -> +1 grateful