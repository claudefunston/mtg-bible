# Overview
These are custom-designed cards meant to interact with the game system of Magic, the Gathering.

The cards are not desiged in any way to insult relegion. They are a respecful way that I interact with the Bible as a historical and literary work.

I am not a set designer nor scholar, but I can get to a concept of a biblical figure and just throw a card out there. If you are a good set designer, I would appreciate any feedback on balance.

# Contents
## Card Sketches
These are whiteboarded cards envisioned in an ad-hoc, top-down style. They are presented in a non-standard format which should be sufficient enough to communicate the nature, effects, and idea of each card.
## db
A standardized .XML database tested to load into Cockatrice for custom games.

# Contributing
## Design a card!
Simply think of your favorite Biblical hero or event, and create something that makes sense in that context. Slight violations of the color pie are acceptable, so long as the color aligns to the card in question. Heros are heros, afterall.

The only restriction is that everying has to come directly from the Bible, so no tangential things which might fit -- Enoch, Josephus &c. References to Deuterocanonical works are gladly included.
## Convert to .XML
Take a card from `card_sketches.txt` and make a proper file out of it. I am using the specification from [Cockatrice](https://github.com/Cockatrice/Cockatrice). For now, minimalistic tagging is fine; we will update the file if exotic fields become necessary.
## Artwork and Flavor Text
Up for grabs. From the shell of proper frames and borders to a nice picture of Moses striking a rock, let's make it look special. Automated tools to incorporate existing card frames are under consideration. Flavor text is probably best when it has a reference to chapter and verse.
## Organize archetypes and run statistics on colors, meta-effects, and balance