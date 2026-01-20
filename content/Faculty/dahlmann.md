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
<br>**Research Aspect Description:** \[I provided Dahlmann the means to find 'a certain Door' and learnt of his previous position at the Labyrinth of Lions.]
<br>**Effect:** permission.dahlmann
<br> **Mutation Effect:** dahlmann -> +1 research1

### Assisting Dahlmann
`talk.faculty.success1.dahlmann.sclerotia.divina`
<br>**Requirements:** Talk, dahlmann, ability, [[sclerotia.divina]]
<br>**Start Description:** Knowledge is stored here unwisely, but it is certainly more accessible than where I studied before. The Labyrinth of Lions was always circumspitious with using those tools of learning closer to Nowhere. How ironic the enlightenment I sought was found in a dark place such as this.'
<br>**Research Aspect Description:** \[I provided Dahlmann the means to find 'a certain Door' and learnt of his previous position at the Labyrinth of Lions.]
<br>**Effect:** permission.dahlmann
<br> **Mutation Effect:** dahlmann -> +1 research1

### Assisting Dahlmann
`talk.faculty.failure2.dahlmann`
<br>**Requirements:** Talk, dahlmann, ability, research1
<br>**Start Description:** I did not find the Door, no, but I did find something akin to a seam. I seek to widen it, or narrow myself. The latter could be accomplished with Transcendence & Ascendance. As for the former, I believe a Rhodesian wrote something relevant; alternatively, the dissection by Taglufon could provide a solution.'

### Assisting Dahlmann
`talk.faculty.success2.dahlmann.transcendence.ascendance`
<br>**Requirements:** Talk, dahlmann, ability, research1, [[s.transcendence.ascendance|r.transcendence.ascendance]], soph:4
<br>**Start Description:** There are eyes we see with, eyes which see us, and eyes which see without seeing at all. When we narrow our senses, other paths we knew not become more apparent, though there is only one I wish to see. Which one, you ask? The ascent of the Unwise Mortal, if you've heard the tale. If you must know why, one of the Labyrinth's copies had a... weighty impact upon me, metaphorically and literally. But with your help, my journey has found some more direction.'
<br>**Research Aspect Description:** \[Dahlmann revealed to me his desire to chart the ascent of the Unwise Mortal, and how the tale had a 'weighty impact' upon him, metaphorically and literally.]
<br>**Effect:** x.carving.stoneworking
<br> **Mutation Effect:** dahlmann -> +1 research2

### Assisting Dahlmann
`talk.faculty.success2.dahlmann.t.escapetogoldenkhersonese`
<br>**Requirements:** Talk, dahlmann, ability, research1, [[t.escapetogoldenkhersonese|Escape to Golden Khersonese]]
<br>**Start Description:** I suspect Marinus's cartographic work caught the attentions of the Hooded Princes. Shaping maps are rather significant, in the Mansus as in the Wake. Now we chart one of our own. Charting what, you ask? The ascent of the Unwise Mortal, if you've heard the tale. If you must know why, one of the Labyrinth's copies had a... weighty impact upon me, metaphorically and literally. But with your help, my journey has found some more direction.'
<br>**Research Aspect Description:** \[Dahlmann revealed to me his desire to chart the ascent of the Unwise Mortal, and how the tale had a 'weighty impact' upon him, metaphorically and literally.]
<br>**Effect:** x.carving.stoneworking
<br> **Mutation Effect:** dahlmann -> +1 research2

### Assisting Dahlmann
`talk.faculty.success2.dahlmann.t.anightofseriousdreaming`
<br>**Requirements:** Talk, dahlmann, ability, research1, [[t.anightofseriousdreaming|A Night of Serious Dreaming]]
<br>**Start Description:** Nyctodromy began in the Wood, some say. I don't know if it's true, but I do know it is relevant to my own studies. On what, you ask? The ascent of the Unwise Mortal, if you've heard the tale. If you must know why, one of the Labyrinth's copies had a... weighty impact upon me, metaphorically and literally. But with your help, my journey has found some more direction.'
<br>**Research Aspect Description:** \[Dahlmann revealed to me his desire to chart the ascent of the Unwise Mortal, and how the tale had a 'weighty impact' upon him, metaphorically and literally.]
<br>**Effect:** x.carving.stoneworking
<br> **Mutation Effect:** dahlmann -> +1 research2

### Assisting Dahlmann
`talk.faculty.failure3.dahlmann`
<br>**Requirements:** Talk, dahlmann, ability, research2
<br>**Start Description:** This seam we spoke of last, I believe it is a remnant of one of the ways the Unwise Mortal shaped. Confirming is such is one matter, traversing it another entirely. It is not collapsed, but it is blocked, and old dreams do not lend themselves well to being sketched as the Doors do. However, there are other methods. One of the Wayfinder's auditory implmements should suffice. If not that, I've conceived of a certain flame which could help requiring a specific fuel, some mycological work to do with the flames of foxes or somesuch.

### Assisting Dahlmann
`talk.faculty.success3.dahlmann.chasqui.clarion`
<br>**Requirements:** Talk, dahlmann, ability, research2, [[chasqui.clarion|Chasqui Clarion]]
<br>**Start Description:** The gods-who-were-stone navigated the Mansus with echoes. Of course the Unwise Mortal did the same. Many thanks for the assistance. Navigating the world is hard when blind, but navigating dreams is much easier. The Watchman learnt that when opened the Door in his own Eye, as did the victims of the Sight-Thief, and most probably the Pilgrims who follow them. I will not be one of them. My interest ends at the line of mortality, blurry as it appears.'
<br>**Research Aspect Description:** \[I assisted Dahlmann with recording one of the ways the Unwise Mortal took into the Mansus. In return, he confided in me his disinterest in joining the Vagabond in her Pilgrimage to the Glory.]
<br>**Effect:** x.skystories
<br> **Mutation Effect:** dahlmann -> +1 research3

### Assisting Dahlmann
`talk.faculty.success3.dahlmann.fuel.velletri`
<br>**Requirements:** Talk, dahlmann, ability, research2, [[fuel.velletri|Olio Velletri]]
<br>**Start Description:** Let it never be said that the Dottore is no one of learning. Igniting an old flame with a new fuel... an oddity very much in his purview, Many thanks for the assistance. Navigating the world is hard when blind, but navigating dreams is much easier. The Watchman learnt that when opened the Door in his own Eye, as did the victims of the Sight-Thief, and most probably the Pilgrims who follow them. I will not be one of them. My interest ends at the line of mortality, blurry as it appears.'
<br>**Research Aspect Description:** \[I assisted Dahlmann with recording one of the ways the Unwise Mortal took into the Mansus. In return, he confided in me his disinterest in joining the Vagabond in her Pilgrimage to the Glory.]
<br>**Effect:** x.skystories
<br> **Mutation Effect:** dahlmann -> +1 research3

### Assisting Dahlmann
`talk.faculty.failure4.dahlmann`
<br>**Requirements:** Talk, dahlmann, ability, research3
<br>**Start Description:** I have found the Unwise Mortal's way, sketched it best I can, but the other end of this passage eludes me still. It should lead to one of the chambers of the upper Mansus, directionally, though directions bend many ways in Dream. Orientation is difficult to keep, though not impossible. Bring me the Obliviates' atlas, or Vögel's work with fulgents, and I can keep myself righted during my survey. Otherwise, the greater methods of the Company Anchorite will suffice [+10].

### Assisting Dahlmann
`talk.faculty.success4.dahlmann.r.anchoritemeditations`
<br>**Requirements:** Talk, dahlmann, ability, research3, [[s.anchoritemeditations|r.anchoritemeditations]], soph:10
<br>**Start Description:** I chose to use this wing for this reason. The Company is gone, but their knowledge remains, and these remnants which can uphold me as bones do. What do I hope to find at the other end, you ask? A new sight, as with the Sight-Thief's artificial eye. As she holds it in her hand, as the Watchman holds his lantern, the world reveals itself in new ways, old as the paths are. However this new sight comes to me, I will hold it close... and share what I do see with you, as thanks.'
<br>**Research Aspect Description:** \[After providing Dahlmann a way to keep himself oriented while traversing the way of the Unwise Mortal, he spoke of his desire to gain 'a new sight' from his studies, as the Sight-Thief has with her artificial eye.]
<br>**Effect:** x.sandstories (x2)
<br> **Mutation Effect:** dahlmann -> +1 research4

### Assisting Dahlmann
`talk.faculty.success4.dahlmann.t.theuppermostsecrets`
<br>**Requirements:** Talk, dahlmann, ability, research3, [[t.theuppermostsecrets|The Uppermost Secrets]]
<br>**Start Description:** The fulgents know of a lesser crossroads beneath the Concursum, one more stable than other ways of the House. It will serve as my north in dream. What do I hope to find at the other end, you ask? A new sight, as with the Sight-Thief's artificial eye. As she holds it in her hand, as the Watchman holds his lantern, the world reveals itself in new ways, old as the paths are. However this new sight comes to me, I will hold it close... and share what I do see with you, as thanks.'
<br>**Research Aspect Description:** \[After providing Dahlmann a way to keep himself oriented while traversing the way of the Unwise Mortal, he spoke of his desire to gain 'a new sight' from his studies, as the Sight-Thief has with her artificial eye.]
<br>**Effect:** x.sandstories (x2)
<br> **Mutation Effect:** dahlmann -> +1 research4

### Assisting Dahlmann
`talk.faculty.success4.dahlmann.a.atlasofdreams`
<br>**Requirements:** Talk, dahlmann, ability, research3, [[t.atlasofdreams|Atlas of Dreams]]
<br>**Start Description:** Translating the metaphorical into the practical is difficult, but dreams allow more flexibility. This will suffice to guide me through this bygone way. What do I hope to find at the other end, you ask? A new sight, as with the Sight-Thief's artificial eye. As she holds it in her hand, as the Watchman holds his lantern, the world reveals itself in new ways, old as the paths are. However this new sight comes to me, I will hold it close... and share what I do see with you, as thanks.'
<br>**Research Aspect Description:** \[After providing Dahlmann a way to keep himself oriented while traversing the way of the Unwise Mortal, he spoke of his desire to gain 'a new sight' from his studies, as the Sight-Thief has with her artificial eye.]
<br>**Effect:** x.sandstories (x2)
<br> **Mutation Effect:** dahlmann -> +1 research4

### Assisting Dahlmann
`talk.faculty.failure5.dahlmann`
<br>**Requirements:** Talk, dahlmann, ability, research4
<br>**Start Description:** I emerged at a threshold near the Glory; but not the Tricuspid Gate, nor even the Peacock Door. One of the House's secret doors - perhaps shaped by the Unwise Mortal himself. It is locked by a riddle; not spoken, but observed. I have sketched it best I could for you, yet this riddle requires an answer of rare sights. With your vision, I'm certain you can find this answer more easily than I.'

### Assisting Dahlmann
`talk.faculty.success5.dahlmann.gossamerglimpse`
<br>**Requirements:** Talk, dahlmann, ability, research4, [[glimpse.gossamer|Gossamer Glimpse]]
<br>**Start Description:** Before we spoke of our dreams, we painted them, and only in darkness do images endure. The Unwise Mortal knew this. I believe the Watchman does as well. Why else would he cultviate the Tree? Let me share something with you, Librarian. Many histories are painted along the corridors of the Labyrinth of Lions. The most exalted are kept in light, but the most precious are reserved for the dark. Some of them were taken from the skin of the Seven-Coiled when she was opened to the brighter sun. Now imagine what secrets may live in a darkness so close to the Glory. Imagine what we will come to see.'
<br>**Research Aspect Description:** \[Dahlmann made use of my answer of sights to unlock a secret door - perhaps made by the Unwise Mortal - and anticipated what secret sights could lie behind it in darkness.]
<br>**Effect:** x.sights.sensations (x2)
<br> **Mutation Effect:** dahlmann -> +1 research5

### Assisting Dahlmann
`talk.faculty.failure6.dahlmann`
<br>**Requirements:** Talk, dahlmann, ability, research5
<br>**Start Description:** The Door is open, yet I cannot enter. The chamber only allows one occupant, and the secret sight the Unwise Mortal have up so long ago lies within; yet it is not entirely beyond our reach yet. If I lay a sufficiently tantalizing secret upon our side of the threshold, it may come to seek it, and cross back out. For such passage, a great truth of passage must be rendered: of places between, of stproes before, of what is held by the greatest of the bereaved beneath the sky.'

### Earning Dahlmann's Respect
`talk.faculty.success6.dahlmann.void`
<br>**Requirements:** Talk, dahlmann, ability, research5, [[numen.void|Numen: The Void Between]]
<br>**Start Description:** Wilwardo's work speaks, even after he has given up his voice. Perhaps this place lying in the Bounds is why the words of his work resonate so deeply, even with secrets of so long ago. I found my sight, and the labyrinths of time are clearer than ever, as are the seasons who walk them. Not all of them will come here, but one is more acquainted with this place than others. If you wish to speak with her, use this. I have my own conversations to attend to.'
<br>**Description:** \[I assisted Dahlmann in fulfilling his work: acquiring the 'secret sight' of the Unwise Mortal, making the labyrinths of time ever clearer to him.]
<br>**Effect:** [[remedy.dahlmann|Dahlmann's Remedy]], [[x.summon.camai.quilla|Lesson: Camai Quilla's Plenty]]
<br> **Mutation Effect:** dahlmann -> +1 grateful

### Earning Dahlmann's Respect
`talk.faculty.success6.dahlmann.keys`
<br>**Requirements:** Talk, dahlmann, ability, research5, [[numen.keys|Numen: Key of Keys]]
<br>**Start Description:** Ironic for the Mutality's work to coax something out rather than force themselves in. But perversions of intent are rather the point of this place, no? I found my sight, and the labyrinths of dream are clearer than ever. The oldest of these passages have revealed themeslves to me, and it is only right I help reveal them to you as well. Hang this over the dreaming circle, and you'll learn how to do more than see dreams, but to hear them. I have my own voices to listen to.'
<br>**Description:** \[I assisted Dahlmann in fulfilling his work: acquiring the 'secret sight' of the Unwise Mortal, making the labyrinths of dream ever clearer to him.]
<br>**Effect:** [[remedy.dahlmann|Dahlmann's Remedy]], [[black.hamsa|Black Hamsa]]
<br> **Mutation Effect:** dahlmann -> +1 grateful

### Earning Dahlmann's Respect
`talk.faculty.success6.dahlmann.stone`
<br>**Requirements:** Talk, dahlmann, ability, research5, [[numen.stone|Numen: The Traveling Stones]]
<br>**Start Description:** The Egg and the Sun and the Vagabond all have their stories, and the Horned-Axe has always been there to listen. Every mouth is a threshold after all. I found my sight, and the labyrinths of history are clearer than ever. Whatever is to come of them, the Horned will always stand between, to watch and wait and distinguish each from the next. Hang this at her shrine, and you'll learn a little of the same. I have my own histories to navigate through.'
<br>**Description:** \[I assisted Dahlmann in fulfilling his work: acquiring the 'secret sight' of the Unwise Mortal, making the labyrinths of history ever clearer to him.] 
<br>**Effect:** [[remedy.dahlmann|Dahlmann's Remedy]], [[dual.skandola|Dual Skandola]]
<br> **Mutation Effect:** dahlmann -> +1 grateful