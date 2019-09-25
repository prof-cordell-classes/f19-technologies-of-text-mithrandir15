# Lab Report: PROGRAMMING LITERATURE

#### David Polansky

## Process Description

I brought in four lines of the song 'Stabbed to Death Outside San Juan' by the Mountain Goats:

> And the sky goes dark and there I am
> 
> Climbing down the Hertzsprung-Russell diagram
> 
> I drop from the top of my tall steel cage
> 
> Drop to the concrete floor
	
I connected [a new Twitter account](https://twitter.com/temp34486026) to Cheap Bots, Done Quick, then typed the lines into the Tracery editor. After resolving a syntax error (I hadn't been including commas after the closing brackets), I wrote down lists of alternatives for the words "sky", "dark", "climbing", "down", "Hertzsprung-Russell", "diagram", "tall", "steel", and "concrete". I input the resulting JSON into Good Bots, Done Quick and set it to post every 3 hours. Here's my JSON:

```
{
"thing":["sky","sea","room","floor"],
"move":["climbing","scrambling","crawling","crumbling"],
"prep":["up","down","through","on"],
"color":["light","dark"],
"dimension":["tall","short","long","small","large"],
"material":["steel","glass","bronze","stone","brass","straw","wood"],
"material2":["concrete","wooden","iron","metal","asphalt"],
"diagram_type":["Hertzsprung-Russell","Ishikawa","constellation","system context","program structure","kinematic"],
"diagram":["diagram","sonogram","histogram","hologram","epigram","telegram","diaphragm"],
"origin":["And the #thing# goes #color# and there I am\n #move.capitalize# #prep# the #diagram_type# #diagram#\nI drop from the top of my #dimension# #material# cage\nDrop to the #material2# floor"]
}
```

Afterwards, I briefly attempted to create a JSON that could produce a line of comprehensible iambic pentameter using multiple grammar structures and words of various syllable lengths, but that proved far too ambitious to be done quickly.

## Observations

In the next section of each report, you should in **2-3 paragraphs** move from a literal description of what you did in the lab to a more conceptual set of observations. In brief, you want to home in on those aspects of the lab that raised questions or prompted new insights into the textual technology we investigated in the lab activity. What new ideas occurred to you while working? What surprised, delighted, or frustrated you?

The primary challenge in creating the JSON was to change things about the poetry while keeping it recognizable. For example, if I had replaced every word with a different, random word of the same part of speech, nothing unique or comprehensible would have remained. So I only replaced nine words. Furthermore, the new alternatives retained the meter of the original words, and made some sense in context: e.g. the word "steel" was only replaced with other 1-syllable building materials.

The secondary challenge in creating the JSON was to create something with a purpose. The examples were all deliberately created to be artistic, novel, and/or funny. My JSON created stanzas that retained a similar aesthetic to the original, but didn't seem quite as purposeful - e.g. an "Ishikawa diagram" is a real thing, but doesn't have the symbolic subtext of the original "Hertzsprung-Russell diagram". The main effect of the JSON was to imagine the narrator in slightly different settings; in a bronze cage by the sea, for instance, instead of in a steel cage in a wrestling arena.

## Analysis

In the preface to his translation of Genesis, AElfric writes, "We also said before that the book is very profoundly spiritual in understanding and we will write no more than the naked narrative. Then it seems to the unlearned that all that meaning is locked up in the simple narrative, but it is very far from it." In other words, the Bible has two meanings: the literal narrative, and its symbolism and interpretation. Aelfric is worried that translation will capture the former and mutate the latter (or not capture it at all). 

*Every* text has these two meanings: the literal and the figurative. When changing the words of a text, we cannot help but to change one or both of these meanings. The act of creating a Twitterbot to remix a text is a special case of this. I attempted to change the literal meaning of my text while keeping the figurative: the text has the same "vibe", and the narrator's message is the same, just distorted. (Specifically, the narrator is on a stretcher, imagining jumping from the top of the cage (in a cage match) but finding himself not on the mat, but on a hard surface. Credits to [Genius](https://genius.com/5169066).) The literal meaning of the text is changed, however, by switching up meaningless details like building materials and types of diagrams.

The exemplar Twitterbots did something more radical. They changed details around - some minor, some major - but the effect of this wasn't to keep the same figurative meaning, but to change it entirely. For instance, TwoHeadlines mashes up literal details for a very different literal story, yet the story isn't intended to provide information (like the original headlines were), it's intended to showcase absurdity. This dynamic is successful, and it influences the purposes that bots are used for: instead of preservation, in the case of AElfric, they're used for transformation.