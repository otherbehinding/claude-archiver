# claude-archiver

This archives your claude or any ai chatbot into a prompt where it can save ~35% of token usage on (almost) everything.

# HOW TO USE:

1- When you're near the end of your chat copy ENTER_FIRST and paste it into your chat.

2- Copy the codeblock it gave you and paste it into a new chat, with that pasted code, copy NEW_CHAT and paste it besides it.

3- Press enter and watch the chat remember itself.

# Testing

The text I gave it,
```
Essay: The Illusion of Simplicity — How Complexity Hides in Plain Sight
Every morning, billions of people flip a light switch without a second thought. The light comes on. The interaction is so frictionless, so instantaneous, that it feels almost trivial — a binary event, off to on, darkness to light. But behind that switch lies one of the most staggeringly complex engineered systems in human history: the electrical grid. Thousands of power stations, millions of kilometers of transmission lines, and a real-time balancing act that must match supply to demand within fractions of a second, at every moment, across entire continents. The simplicity you experience is not an absence of complexity. It is complexity so thoroughly mastered that it becomes invisible.
This phenomenon — call it the illusion of simplicity — is one of the defining features of mature technology. The better a system works, the less you notice it. Roads feel obvious until you consider the centuries of civil engineering, material science, and urban planning theory embedded in the asphalt beneath your tires. Language feels effortless until you try to teach it to a machine and discover that even the most basic sentence requires resolving ambiguities that would paralyze a formal logic system. The ATM that dispenses your cash in eight seconds is the visible tip of a vast iceberg of cryptographic protocols, interbank clearing networks, fraud detection algorithms, and regulatory compliance layers — none of which you will ever see or need to think about.
What makes this illusion so powerful is that it is, in many ways, the explicit goal of good engineering. The entire discipline of user experience design is fundamentally about moving complexity out of the user's mental model and into the system itself. A well-designed interface should feel like thinking — the gap between intention and outcome should approach zero. When it succeeds, the technology disappears. The tool becomes an extension of the hand. The software becomes an extension of the mind. The infrastructure becomes an extension of the environment.
But the illusion carries a hidden cost. When complexity is invisible, so is fragility. People who have never seen the inside of a system cannot intuit where it might break. They cannot estimate the effort required to change it, extend it, or repair it. This is why non-technical stakeholders routinely underestimate software projects — not because they are unintelligent, but because the interface they interact with gives them no signal of the depth beneath it. A button that took two weeks to build looks identical to one that took two hours. The invisible complexity has been so successfully hidden that it has also been hidden from the people who must decide how to resource, prioritize, and maintain it.
There is also a civilizational dimension to this problem. As systems become more complex and more interconnected, the number of people who fully understand any given system shrinks — often to nearly zero. No single person understands the entire internet. No single person understands the full supply chain that produced the device you are reading this on. We have built a world that runs on collective, distributed, and deeply specialized knowledge — a world where understanding is always partial, always local, and always dependent on trusting systems and institutions that operate beyond any individual's ability to verify. The light comes on when you flip the switch. And you have no real idea why.
The honest response to this condition is not anxiety but humility. The correct posture is to remain curious about the layers beneath the interface — to resist the comfortable illusion that because something is easy to use, it is simple to understand. Every system that feels obvious was once someone's unsolved problem. Every abstraction that feels natural was once a hard-won insight. The switch on the wall is a monument to ten thousand invisible decisions. Flipping it is the least interesting thing about it.
```

The result that spat out,
```
Ev morning,billions flip light switch w/o 2nd thought. Light→on. Interaction so
frictionless,instantaneous→feels trivial — binary ev,off→on,dark→light. But behind
switch lies 1 of most staggeringly complex engineered sys in human history: electrical
grid. ..K.s,, power stations,..M.k,, km transmission lines,real-time balance act
matching supply→demand w/in fractions/sec,ev moment,across continents. Simplicity
experienced≠absence complexity — complexity so thoroughly mastered→becomes invisible.

Phenomenon(="illusion of simplicity")→1 defining feature mature tech. Better sys
works→less noticed. Roads feel obvious til consider centuries civil eng,material sci,
urban planning theory embedded in asphalt. Language feels effortless til teach
machine→discover basic sentence requires resolving ambiguities paralyzing formal logic
sys. ATM dispensing cash in 8s→visible tip vast iceberg: cryptographic protocols,
interbank clearing nets,fraud detection algos,regulatory compliance layers — none ever
seen/needed.

Illusion powerful b/c explicit goal good eng. Entire UX discipline→moving complexity
out user mental model→into sys itself. Well-designed interface→feel like thinking —
gap intention→outcome→~0. When succeeds,tech disappears. Tool→ext hand. Software→ext
mind. Infrastructure→ext environment.

But illusion carries hidden cost. Complexity invisible→fragility invisible. Ppl never
seen inside sys→can't intuit where breaks. Can't estimate effort to change/extend/
repair. Why non-tech stakeholders routinely underestimate software projects — not
unintelligent,b/c interface gives no signal depth beneath. Button took 2wks→looks
identical→2hr button. Invisible complexity hidden so successfully→also hidden from ppl
deciding resourcing,prioritization,maintenance.

Also civilizational dimension. Sys→more complex&interconnected→# ppl fully
understanding any sys shrinks→~0. No single person understands entire internet. No
single person understands full supply chain→device reading on. Built world running on
collective,distributed,specialized knowledge — understanding always partial,local,
dependent on trusting sys&institutions beyond individual ability verify. Light→on when
flip switch. No real idea why.

Honest response→not anxiety but humility. Correct posture→remain curious layers beneath
interface — resist comfortable illusion easy-to-use=simple-to-understand. Ev sys
feeling obvious→once unsolved problem. Ev abstraction feeling natural→once hard-won
insight. Switch on wall→monument ..10.k,, invisible decisions. Flipping it→least
interesting thing about it.
```

Results (original:CODECv2:saved):
```
Characters: 3,956:2,581:1,375 (35%)
Words: 640:291:349 (55%)  
Tokens (est.): 1,041:679:362 (35%)
```
