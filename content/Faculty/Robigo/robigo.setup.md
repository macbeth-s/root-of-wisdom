# Dottore Robigo
The Generous of Hosts, Protector of the Haustorium, Name of the Crowned Growth. Italian only by convention.
## Aspects
- Interest: Grail 7
- Interest: Heart 7
- Interest: Nectar 7
- Understands Latin
- Understands Fucine
- [[protector|Protector]]
- [[Faculty]]
- Sceptical
## Talk
### A Conversation with Dottore Robigo
`talk.faculty.robigo.setup.intro`
**Start Description:** Welcome, esteemed guest, to the Haustorium! Should you seek hospitality at our hostel, learning in the archives, or the blessed release of death in any of the other wings, we, and the Faculty, are most happy to oblige you. What do you seek?'
<br>**Requirements:** robigo.setup, sceptical
<br>**Slot for Readable**
### A Conversation with Dottore Robigo
`talk.faculty.robigo.setup.failure`
**Start Description:** Hmmm? Oh...
<br>**Description:** If you want to read, go bother the faculty. I am admiring my art.
<br>**Requirements:** robigo.setup, sceptical, -1journal

### A Conversation with Dottore Robigo
`talk.faculty.robigo.setup.journal`
**Start Description:** You would entrust me with your own private thoughts? I appreciate the generosity. It is good to know you trust me with your innermost contemplations.
<br>**Description:** The Haustorium is in need of a librarian. We have had a few over the years... snivelling little pawns who could never much handle the rigor. If you are a person of learning, perhaps you could follow in their footsteps. I am a generous patron of letters.
<br>**Requirements:** robigo.setup, sceptical, journal
<br>**Effect:** Mutate Robigo -1sceptical

### A Conversation with Dottore Robigo
`talk.faculty.robigo.prove.intro`
**Start Description:** Should you serve as librarian, you must understand my Haustorium is a place of softness and learning, where the greatest scholars of the world might rest and research in peace until they join in the chorus of heavenly muses. But you will not be their colleague, you will be their servant. We have among us historians, archaeologists, artisans, and mycologists. Prove to me your worthiness in one of these fields.
<br>**Requirements:** robigo.setup, -1sceptical
<br>**Slot for Skill**
### A Conversation with Dottore Robigo
`talk.faculty.robigo.prove.failure`
**Start Description:** This is not impressive.
<br>**Description:** I am not interested in a dilletante. Reapply when you have sufficient skill.
<br>**Requirements:** robigo.setup, -1sceptical, 1skill
### A Conversation with Dottore Robigo
`talk.faculty.robigo.prove.success`
**Start Description:** So you are learned. Or you are at least committed to becoming learned...
<br>**Description:** You are provisionally appointed librarian of the Haustorium. Help the Faculty with their research, and receive visitors with as much hospitality as I would. And clean up the place while you're at it... it is an embarrassment to see the state everything is in. I will be back soon enough to check in on you.
<br>**Requirements:** robigo.setup, -1sceptical, 2skill
<br>**Effect:** [[wc|Writing-Case]], [[permission.robigo|Robigo's Permission]]