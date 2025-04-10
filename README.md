# Overview
These are custom-designed cards meant to interact with the game system of Magic, the Gathering.

The cards are not desiged in any way to insult relegion. They are a respecful way that I interact with the Bible as a historical and literary work.

I am not a set designer nor scholar, but I can get to a concept of a biblical figure and just throw a card out there. If you are a good set designer, I would appreciate any feedback on balance.

This project aims to adhere to WotC's [Fan Content Policy](https://company.wizards.com/en/legal/fancontentpolicy). This project does not, and will not, accept money at any time. Any potential contradictions to the policy should be flagged immediately, and will be corrected by us.

# Usage
Place `01.cockatrice_db.xml` into `~\Cockatrice\Cockatrice\customsets` (or `%APPDATA%\Local\Cockatrice\Cockatrice\customsets`). From the Cockatrice menu (Card Database -> Manage Sets), you should see your custom set available to load amongst all the rest.

Images may be placed in `~Cockatrice\Cockatrice\pics\CUSTOM`. You can use the pictures from this repo, or make images of your own. If you place a .png or .jpg image in this folder, and the name of the image matches the name of a card, the image will load. Apostrophes matter.

No guarantees that names like Barad-dûr will be rendered properly! Extended character sets under exploration.

# Contents
## Card Sketches
These are whiteboarded cards envisioned in an ad-hoc, top-down style. They are presented in a non-standard format which should be sufficient enough to communicate the nature, effects, and idea of each card.
## db
A standardized .XML database tested to load into Cockatrice for custom games.
## Images
This is slowly growing. Images must have proper attribution, and evidence of propriety of use in this context.

# Contributing
## Design a card!
Simply think of your favorite Biblical hero or event, and create something that makes sense in that context. Slight violations of the color pie are acceptable, so long as the color aligns to the card in question. Heros are heros, afterall.

Keep the content safe. Do not contribute cards which advocate or condone sexual violence. Smiting, and the destroying of cities is fine, but keep it neutral - like the classic MTG card Wrath of God.

The only other restriction is that everying has to come directly from the Bible, so no tangential things which might seem to fit but don't - Enoch, Josephus, Helena &c. References to Deuterocanonical works are gladly included.
## Convert to .XML
Take a card from `card_sketches.txt` and make a proper file out of it. We are using the specification from [Cockatrice](https://github.com/Cockatrice/Cockatrice). For now, minimalistic tagging is fine; we will update the File if exotic fields become necessary.
## Artwork and Flavor Text
Up for grabs. From the shell of proper frames and borders to a nice picture of Moses striking a rock, let's make it look special. Automated tools to incorporate existing card frames are under consideration. Flavor text is probably best when it has a reference to chapter and verse.

For now, we are using [MSE](https://magicseteditor.boards.net/) to make the frames.

## Organize archetypes and run statistics on colors, meta-effects, and balance
Now, it's time to make a set! MSE runs stats, but there sure are tools out there to link everything together.