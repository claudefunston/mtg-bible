# Overview
* Magic: the Gathering cards based upon the Bible.
* We do not endorse, intentionally demean, nor otherwise express an opinion towards any religion.
* These cards are a meant as a respectful way to engage the Bible as a historical and literary work.
* __mtg-bible__ is unofficial Fan Content permitted under Wizards' [Fan Content Policy](https://company.wizards.com/en/legal/fancontentpolicy). This content is not approved nor endorsed by Wizards. Portions of the materials herein are property of Wizards of the Coast.

# Usage
* Install [Cockatrice](https://cockatrice.github.io/).
* Place `01.cockatrice_db.xml` into your customsets folder.
* Optionally, to use our images, place them into your custompics folder.
# Contents
## db 
* `01.cockatrice_db.xml`
## Card Sketches
* `card_sketches.txt`
These are whiteboarded cards envisioned in an ad-hoc, top-down style. The format is sufficient to communicate the nature and effects of each card, and mimics WotC's release notes.
## Artwork
### Attribution
Cards in the db have an `<imgsrc>` tag to record their origins.

All images are [CC0](https://creativecommons.org/public-domain/cc0/) licenced or in the public domain.

Some sources are:
* [The National Gallery of Art](https://www.nga.gov/collection/collection-search.html)
* [The Walters](https://art.thewalters.org/)
* [Wiki Commons](https://commons.wikimedia.org/)

Images used from NGA are hereby credited with _Courtesy National Gallery of Art, Washington_.

If there's an option, we give priority to works not currently on display at their institutions.

### Raw Images
* `images_raw`
* These are details cropped from `<imgsrc>`
### Images
* `images`
* Cards placed into frames using [Magic Set Editor](https://magicseteditor.boards.net/).
### MSE
* `mse_db`
When there are discrepancies between this file and the Cockatrice db, this file is considered authoritative.
# Set Design
## Color pairs
* UB, tertiary R: The Sadducees
    * This group strongly rejects predestination, and does not believe in an afterlife.
    * The law is important, so we use the colors of UB to enforce it.
* UW, tertiary G: The Pharisees
    * This group believes in tradition.
    * Pharasees are either neutral or positive towards Jesus.
* WG, tertiary U: The Believers
    * This group will sacrifice their lives to support the message of Christ.
    * Black sacrifice effects are considered off-type for the Believers, despite their willingness to die.
* WR, tertiary G: The Government
    * The Government can be neutral, beneficial, or harmful.
* UG, tertiary B: The Creators
    * Actors from this tribe can violate the laws of nature.
* BR, tertiary U: The Free
    * It's just Satan and his minions.
* WB, tertiary R: 
* UR, tertiary G: The Essenes
    * This group are mystics, and embrace colorful sources.
* BG, tertiary R: 
* RG, tertiary B: The Nephilim
    * This group are giants and you should expect huge creatures here.
## The Lands
Dual lands enter tapped with a stun counter, but they create a treasure token. Dual lands are typed. All ten pairs are represented.
## The Plagues
* Boils - BR
* Frogs - BG
* Hail - UR
# Release Notes
## Existing Mechanics
* Finality Counters. When a creature with a Finality Counter on it dies, it is exiled instead of being sent to the graveyard.
* Commiting a crime. You commit a crime whenever you target an opposing player or their objects, defined as their spells on the stack, their permanents on the battlefield, or cards in their graveyard.

## New Mechanics and Special Creatures
We have one new mechanic: Inspire: When an Inspired creature dies, its controller creates a food token.

The creature names Jesus, Adam and Eve all have cross-referenced rules text. Assume that the infant you created and the very powerful grownup Jesus are the same person (Teenager schooling the temple, too).

There are three new creature types:
* Donkey. In rules text and cardnames, it should be considered synonymous with ass.
* Infant
* Rooster

The Deserter creature type has appeared before on tokens. It is present in this set on a proper creature.

Because this set is both Biblical and Trinitarian in nature, yes, you can target Jesus with a spell that wants to target the Holy Spirit.

For now, יהוה is considered too powerful to include.

## Zones
There are three new named zones - Heaven, Hell, and Limbo. There are cards associated to each, but they needn't be in play for the zones to exist.

Sending a creature to any is not an exile effect (unless specified by another card). Creatures do enter the graveyard before they meet their destiny.  Creatures cannot leave these zones.

As tokens cease to exist at a time just after entering the graveyard, tokens can't reach them.

Creatures in these zones lose all attributes and abilities apart from type. Specifically, they contribute to devotion, and count for the number of creatures you control.

Just as the exile zone operates, each player has their own version of each.

* When a creature is in Heaven, it gains {T}: Add 2 life.
* When a creature is in Hell, it gains {T}: Add B or R. You lose two life.
* When a creature is in Limbo, it gains {T}: Add {C}.

# Contributing
## Design a card
Some considerations:
* Absolutely no advocation nor condoning of sexual violence nor slavery.
* Absolutely no direct insults nor advocation of any faith or creed.
* Smiting sinful individuals and Armogeddening an entire city are acceptable concepts. As are horrible diseases, plagues and divine mind control.
* Deuterocanonical works are gladly allowed but Apocrypha are not.
## Add Art
Look at a [CC0](https://creativecommons.org/public-domain/cc0/) source, or draw something of your own.
## General QC and templating
Edit a card.
## MSE API
This does no exist.
## Balance the Wheels
This set needs a skeleton to take the cards from isolated ideas into a proper set.
# Biblical Translations
We are open, because meaning can be difficult to decipher if you don't know Hebrew nor Greek. The purpose of this set is to be fun, not communicate theology.

The primary author of this set uses [RSVCE](https://www.biblegateway.com/versions/Revised-Standard-Version-Catholic-Edition-RSVCE-Bible/)

## Citations
 Chapter and Verse: `<chvs>`. This tag has no effect on gameplay.