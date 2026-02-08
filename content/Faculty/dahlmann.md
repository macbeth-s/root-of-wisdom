# Isidoro Dahlmann
Once a well-respected curator of a much better-respected library. Now a blind man who walks labyrinths of his own design.
## Aspects
- Interest: Knock 7
- Interest: Lantern 7
- Interest: Moon 7
- Understands Aramaic
- Understands Deep Mandaic
- [[Faculty]]
## Talk
### An Unimpressed Academic?
`talk.faculty.dahlmann.sceptical.intro`
<br>**Requirements:** Talk, dahlmann, sceptical
<br>**Start Description:** Do try not to distract me.' \[The academic culture at the Haustorium is generally unfriendly. It takes effort to be worth the faculty’s time.]

### Impressing an Academic
`talk.faculty.dahlmann.sceptical`
<br>**Requirements:** Talk, dahlmann, interest=mystery, sceptical
<br>**Start Description:** Have you traversed this maze as well?'
<br>**Description:** You are not blind as I am, though perhaps another kind of blindness is what I need.'
<br>**Effect:** Spintria.bronze
<br> **Mutation Effect:** dahlmann -> -1 sceptical

### A Conversation with Dahlmann
`talk.faculty.intro.dahlmann`
<br>**Requirements:** Talk, dahlmann, -1 sceptical
<br>**Start Description:** You are quite the interruption to my wanderings.' \[The faculty can tutor you in a language and comment on Incidents, or you can assist them with their ongoing research by offering a soul-element.]

### Assisting Dahlmann
`talk.faculty.assist.dahlmann`
<br>**Requirements:** Talk, dahlmann, ability
<br>**Start Description:** It is difficult to view things from a perspective other than our own. I hope to borrow yours to make refinements to mine.  \[The faculty's needs can be exacting, but academic work is slow. If you can't find exactly what you need, they'll ignore you until you have something to offer.]

### Assisting Dahlmann
`talk.faculty.failure1.dahlmann`
<br>**Requirements:** Talk, dahlmann, ability, -1 research
<br>**Start Description:** There is a certain Door I seek which cannot be touched nor seen. If you could show me where it may be, or lend me a sunnier entheogen, I believe it can be found.'

### Assisting Dahlmann
`talk.faculty.success1.dahlmann.secret.threshold`
<br>**Requirements:** Talk, dahlmann, ability, [secret.threshold](https://uadaf.theevilroot.xyz/rowenarium/element/secret.threshold)
<br>**Start Description:** Knowledge is stored here unwisely, but it is certainly more accessible than where I studied before. The Labyrinth of Lions was always circumspitious in matters of Knock. How ironic the enlightenment I sought was found in a dark place such as this.'
<br>**Description:** \[I provided Dahlmann the means to find 'a certain Door' and learnt of his previous position at the Labyrinth of Lions.]
<br>**Effect:** permission.dahlmann
<br> **Mutation Effect:** dahlmann -> +1 research1

### Assisting Dahlmann
`talk.faculty.success1.dahlmann.sclerotia.divina`
<br>**Requirements:** Talk, dahlmann, ability, [[sclerotia.divina]]
<br>**Start Description:** Knowledge is stored here unwisely, but it is certainly more accessible than where I studied before. The Labyrinth of Lions was always circumspitious with using those tools of learning closer to Nowhere. How ironic the enlightenment I sought was found in a dark place such as this.'
<br>**Description:** \[I provided Dahlmann the means to find 'a certain Door' and learnt of his previous position at the Labyrinth of Lions.]
<br>**Effect:** permission.dahlmann
<br> **Mutation Effect:** dahlmann -> +1 research1

### Assisting Dahlmann
`talk.faculty.failure2.dahlmann`
<br>**Requirements:** Talk, dahlmann, ability, research1
<br>**Start Description:** I did not find the Door, no, but I did find something akin to a seam. I seek to widen it, or narrow myself. The latter could be accomplished with Transcendence & Ascendance. As for the former, I believe a Rhodian wrote something relevant; alternatively, the dissection by Taglufon could provide a solution.'

### Assisting Dahlmann
`talk.faculty.success2.dahlmann.transcendence.ascendance`
<br>**Requirements:** Talk, dahlmann, ability, research1, [[s.transcendence.ascendance|r.transcendence.ascendance]], soph:4
<br>**Start Description:** There are eyes we see with, eyes which see us, and eyes which see without seeing at all. When we narrow our senses, other paths we knew not become more apparent, though there is only one I wish to see. Which one, you ask? The ascent of the Unwise Mortal, if you've heard the tale. If you must know why, one of the Labyrinth's copies had a... weighty impact upon me, metaphorically and literally. But with your help, my journey has found some more direction.'
<br>**Description:** \[Dahlmann revealed to me his desire to chart the ascent of the Unwise Mortal, and how the tale had a 'weighty impact' upon him, metaphorically and literally.]
<br>**Effect:** x.carving.stoneworking
<br> **Mutation Effect:** dahlmann -> +1 research2

### Assisting Dahlmann
`talk.faculty.success2.dahlmann.t.escapetogoldenkhersonese`
<br>**Requirements:** Talk, dahlmann, ability, research1, [[t.escapetogoldenkhersonese|Escape to Golden Khersonese]]
<br>**Start Description:** I suspect Marinus's cartographic work caught the attentions of the Hooded Princes. Shaping maps are rather significant, in the Mansus as in the Wake. Now we chart one of our own. Charting what, you ask? The ascent of the Unwise Mortal, if you've heard the tale. If you must know why, one of the Labyrinth's copies had a... weighty impact upon me, metaphorically and literally. But with your help, my journey has found some more direction.'
<br>**Description:** \[Dahlmann revealed to me his desire to chart the ascent of the Unwise Mortal, and how the tale had a 'weighty impact' upon him, metaphorically and literally.]
<br>**Effect:** x.carving.stoneworking
<br> **Mutation Effect:** dahlmann -> +1 research2

### Assisting Dahlmann
`talk.faculty.success2.dahlmann.t.anightofseriousdreaming`
<br>**Requirements:** Talk, dahlmann, ability, research1, [[t.anightofseriousdreaming|A Night of Serious Dreaming]]
<br>**Start Description:** Nyctodromy began in the Wood, some say. I don't know if it's true, but I do know it is relevant to my own studies. On what, you ask? The ascent of the Unwise Mortal, if you've heard the tale. If you must know why, one of the Labyrinth's copies had a... weighty impact upon me, metaphorically and literally. But with your help, my journey has found some more direction.'
<br>**Description:** \[Dahlmann revealed to me his desire to chart the ascent of the Unwise Mortal, and how the tale had a 'weighty impact' upon him, metaphorically and literally.]
<br>**Effect:** x.carving.stoneworking
<br> **Mutation Effect:** dahlmann -> +1 research2

### Assisting Dahlmann
`talk.faculty.failure3.dahlmann`
<br>**Requirements:** Talk, dahlmann, ability, research2
<br>**Start Description:** This seam we spoke of last, I believe it is a remnant of one of the ways the Unwise Mortal shaped a dream of - or dreamed the shape of. Confirming is such is one matter, traversing it another entirely. It is not collapsed, but it is blocked, and old dreams do not lend themselves well to being sketched as the Doors do. However, there are other methods. One of the Wayfinder's auditory implmements should suffice. If not that, I've conceived of a certain flame which could help requiring a specific fuel, some mycological work to do with the flames of foxes or somesuch.

### Assisting Dahlmann
`talk.faculty.success3.dahlmann.chasqui.clarion`
<br>**Requirements:** Talk, dahlmann, ability, research2, [[chasqui.clarion]]
<br>**Start Description:** The gods-who-were-stone navigated the Mansus with echoes. Of course the Unwise Mortal did the same. Many thanks for the assistance. Navigating the world is harder when blind, but navigating the darkness becomes easier. It is why I departed from the Labyrinth, to join one of the Lower Limbs of the Watchman's Tree. As for why I ended up here... the Monastery was dark, but not tall; the Grove was tall, but its roots were shallow; but at the Haustorium, haze and height and history are abundant, or so Cipagauta's correspondence implied. Much more for me to navigate here than anywhere else.'
<br>**Description:** \[I assisted Dahlmann with recording one of the ways the Unwise Mortal took into the Mansus. In return, he confided in me his reasons for seeking the Haustorium, having learned of its qualities from correspondence with Cipagauta.]
<br>**Effect:** x.skystories
<br> **Mutation Effect:** dahlmann -> +1 research3

### Assisting Dahlmann
`talk.faculty.success3.dahlmann.fuel.velletri`
<br>**Requirements:** Talk, dahlmann, ability, research2, [[fuel.velletri]]
<br>**Start Description:** Let it never be said that the Dottore is no one of learning. Igniting an old flame with a new fuel... an oddity very much in his purview, Many thanks for the assistance. Navigating the world is harder when blind, but navigating the darkness becomes easier. It is why I departed from the Labyrinth, to join one of the Lower Limbs of the Watchman's Tree. As for why I ended up here... the Monastery was dark, but not tall; the Grove was tall, but its roots were shallow; but at the Haustorium, haze and height and history are abundant, or so Cipagauta's correspondence implied. Much more for me to navigate here than anywhere else.'
<br>**Description:** \[I assisted Dahlmann with recording one of the ways the Unwise Mortal took into the Mansus. In return, he confided in me his reasons for seeking the Haustorium, having learned of its qualities from correspondence with Cipagauta.]
<br>**Effect:** x.skystories
<br> **Mutation Effect:** dahlmann -> +1 research3

### Assisting Dahlmann
`talk.faculty.failure4.dahlmann`
<br>**Requirements:** Talk, dahlmann, ability, research3
<br>**Start Description:** I have found the Unwise Mortal's way, sketched it best I can, but the other end of this passage eludes me still. It should lead to one of the chambers of the upper Mansus, directionally, though directions bend many ways in Dream. Orientation is difficult to keep, though not impossible. Bring me the Obliviates' atlas, or Vögel's work with fulgents, and I can keep myself righted during my survey. Otherwise, the greater methods of the Company Anchorite will suffice \[+10].

### Assisting Dahlmann
`talk.faculty.success4.dahlmann.r.anchoritemeditations`
<br>**Requirements:** Talk, dahlmann, ability, research3, [[s.anchoritemeditations|r.anchoritemeditations]], soph:10
<br>**Start Description:** I chose to use this wing for this reason. The Company is gone, but their knowledge remains, and these remnants which can uphold me as bones do. What do I hope to find at the other end, you ask? The sight the Unwise Mortal lost, when he opened his own eye - when the Hour-to-be called Watchman first came forth. It can teach how I too may send an Other forth from me, to travel afar while I remain here at the Dottore's insistance. As the Sight-Thief's glass eye still sees what has long passed, I wish for this Other to see more than I ever can.'
<br>**Description:** \[After providing Dahlmann a way to traverse the way of the Unwise Mortal, he spoke of his desire to gain the sight the Mortal sacrificed to bring forth the Watchman, hoping to learn how to send his 'Other' to travel the world while he remains at the Haustorium.]
<br>**Effect:** x.sandstories (x2)
<br> **Mutation Effect:** dahlmann -> +1 research4

### Assisting Dahlmann
`talk.faculty.success4.dahlmann.t.theuppermostsecrets`
<br>**Requirements:** Talk, dahlmann, ability, research3, [[t.theuppermostsecrets]]
<br>**Start Description:** The fulgents know of a lesser crossroads beneath the Concursum, one more stable than other ways of the House. It will serve as my north in dream. What do I hope to find at the other end, you ask? The sight the Unwise Mortal lost, when he opened his own eye - when the Hour-to-be called Watchman first came forth.  It can teach how I too may send an Other forth from me, to travel afar while I remain here at the Dottore's insistance. As the Sight-Thief's glass eye still sees what has long passed, I wish for this Other to see more than I ever can.'
<br>**Description:** \[After providing Dahlmann a way to traverse the way of the Unwise Mortal, he spoke of his desire to gain the sight the Mortal sacrificed to bring forth the Watchman, hoping to learn how to send his 'Other' to travel the world while he remains at the Haustorium.]
<br>**Effect:** x.sandstories (x2)
<br> **Mutation Effect:** dahlmann -> +1 research4

### Assisting Dahlmann
`talk.faculty.success4.dahlmann.a.atlasofdreams`
<br>**Requirements:** Talk, dahlmann, ability, research3, [[a.atlasofdreams]]
<br>**Start Description:** Translating the metaphorical into the practical is difficult, but dreams allow more flexibility. This will suffice to guide me through this bygone way. What do I hope to find at the other end, you ask? The sight the Unwise Mortal lost, when he opened his own eye - when the Hour-to-be called Watchman  first came forth.  It can teach how I too may send an Other forth from me, to travel afar while I remain here at the Dottore's insistance. As the Sight-Thief's glass eye still sees what has long passed, I wish for this Other to see more than I ever can.'
<br>**Description:** \[After providing Dahlmann a way to traverse the way of the Unwise Mortal, he spoke of his desire to gain the sight the Mortal sacrificed to bring forth the Watchman, hoping to learn how to send his 'Other' to travel the world while he remains at the Haustorium.]
<br>**Effect:** x.sandstories (x2)
<br> **Mutation Effect:** dahlmann -> +1 research4

### Assisting Dahlmann
`talk.faculty.failure5.dahlmann`
<br>**Requirements:** Talk, dahlmann, ability, research4
<br>**Start Description:** I emerged at a threshold near the Glory; but not the Tricuspid Gate, nor even the Peacock Door. One of the House's secret doors - perhaps the one the Unwise Mortal passed into the shadow of the Egg. It is locked by a riddle; not spoken, but observed. I have sketched it best I could for you, yet this riddle requires an answer of rare sights. With your vision, I'm certain you can find this answer more easily than I.'

### Assisting Dahlmann
`talk.faculty.success5.dahlmann.gossamerglimpse`
<br>**Requirements:** Talk, dahlmann, ability, research4, [[gossamer.glimpse]]
<br>**Start Description:** Before we spoke of our dreams, we painted them, and only in darkness do images endure. The Unwise Mortal knew this. I believe the Watchman does as well. Why else would he cultviate the Tree? Let me share something with you, Librarian. Many histories are painted along the corridors of the Labyrinth of Lions. The most exalted are kept in light, but the most precious are reserved for the dark, recovered from the Seven-Coiled whence she was opened to the brighter sun. The Mortal recorded his own history not long after, the First History - and what was painted in his eye, before he opened it unto Glory? An image of himself, a brighter one who could walk by Light: his Hourly Other.'
<br>**Description:** \[Dahlmann made use of my answer of sights to unlock the Door of the Unwise Mortal. Afterwards, he mused on the Mortal's recording of the First History, the image painted in his eye as he did so, and the consequent emergance of his 'Hourly Other.']
<br>**Effect:** x.sights.sensations (x2)
<br> **Mutation Effect:** dahlmann -> +1 research5

### Assisting Dahlmann
`talk.faculty.failure6.dahlmann`
<br>**Requirements:** Talk, dahlmann, ability, research5
<br>**Start Description:** The Door is open; I cannot enter as the Know I am; but the sight the Unwise Mortal sacrificed to bring the Door-in-the-Eye unto Glory lies past. If I offer a worthy truth-to-be, it can come before me to show how I may bring forth my Other. But for such a great passage, a great truth of passage must be rendered: of places between, of stories before, of what is held by the greatest of the bereaved beneath the sky.'

### Earning Dahlmann's Respect
`talk.faculty.success6.dahlmann.void`
<br>**Requirements:** Talk, dahlmann, ability, research5, [[numen.void]]
<br>**Start Description:** Wilwardo's work speaks, even after he has given up his voice. Perhaps this place lying in the Bounds is why his work resonates so deeply, even with secrets of so long ago. The Mortal's sight has passed into my hollows, and my Other has passed out into the world. The labyrinths of time are clearer to me than ever, as are the forgotten seasons who walk them. Not all of them will come here, but one is more acquainted with this place than others. If you wish to speak with her, use this - knowledge she taught to my Other. And have this, a trick Cipagauta and I used to keep in touch across continents. Sleep deep, Librarian. Sleep deep.'
<br>**Description:** \[I assisted Dahlmann in fulfilling his work: bringing forth his Other from within himself to traverse the world and its labyrinths of time for him.]
<br>**Effect:** [[remedy.dahlmann]], [[callingcard.dream]], [[x.summon.camai.quilla]]
<br> **Mutation Effect:** dahlmann -> +1 grateful

### Earning Dahlmann's Respect
`talk.faculty.success6.dahlmann.keys`
<br>**Requirements:** Talk, dahlmann, ability, research5, [[numen.keys]]
<br>**Start Description:** Ironic for the Mutality's work to coax something out rather than force themselves in. But perversions of intent are rather the point of this place, no? The Mortal's sight has unlocked me, and my Other has been freed from the shackles of my self. The labyrinths of dream are clearer than ever, and the passages have revealed themselves, and it is only right I help reveal them to you. Hang this over the dreaming circle - my Other carved it in the image of those first dreamers - and you'll learn how to travel dreams not just by sight, but by sound. And have this, a trick Cipagauta and I used to keep in touch across continents. Sleep deep, Librarian. Sleep deep.'
<br>**Description:** \[I assisted Dahlmann in fulfilling his work: unbinding his Other from himself to traverse the world and its labyrinths of dream for him.] 
<br>**Effect:** [[remedy.dahlmann]], [[callingcard.dream]], [[black.khamsa]]
<br> **Mutation Effect:** dahlmann -> +1 grateful

### Earning Dahlmann's Respect
`talk.faculty.success6.dahlmann.stone`
<br>**Requirements:** Talk, dahlmann, ability, research5, [[numen.stone]]
<br>**Start Description:** Stories were the first divisions of dreams, to which the Axe has always attended. Every mouth is a threshold, after all, and the Mortal's sight has spoken back. I have spoken my Other into being and bid him make a quick departure, and now the labyrinths of history are clearer than ever. The Horned knows how to distinguish them from Time, to carve out Truth from Mystery. Hang this at her shrine - a memento of her old self my Other found in older sands - and you'll learn a little of the same. And have this, a trick Cipagauta and I used to keep in touch across continents. Sleep deep, Librarian. Sleep deep.'
<br>**Description:** \[I assisted Dahlmann in fulfilling his work: speaking his Other into existence to traverse the world and its labyrinths of history for him.] 
<br>**Effect:** [[remedy.dahlmann]], [[callingcard.dream]], [[dual.skandola]]
<br> **Mutation Effect:** dahlmann -> +1 grateful