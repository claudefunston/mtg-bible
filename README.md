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
* `card_sketches.txt` Are whiteboarded cards envisioned in an ad-hoc, top-down style. The format is sufficient to communicate the nature and effects of each card, and mimics WotC's release notes.
## Artwork
### Attribution
Cards in the db have an `<imgsrc>` tag to record their origins.

All images are [CC0](https://creativecommons.org/public-domain/cc0/) licenced or in the public domain.

Some sources are:
* [The National Gallery of Art](https://www.nga.gov/collection/collection-search.html)
* [The Walters](https://art.thewalters.org/)
* [Wikimedia Commons](https://commons.wikimedia.org/)

Images from NGA are hereby credited with _Courtesy National Gallery of Art, Washington_.

### Raw Images
* Details cropped from `<imgsrc>` for each card.
### Images
* These are produced by [Magic Set Editor](https://magicseteditor.boards.net/).
### MSE
* File: `mse_db`
* When there are discrepancies between this file and the Cockatrice db, this file is considered authoritative.
# Set Design
## Color pairs
* UB, tertiary R: The Sadducees
    * This group rejects predestination, and does not believe in an afterlife.
    * The law is important, so we use its colors to enforce it.
* UW, tertiary G: The Pharisees
    * This group believes in tradition.
    * This group is either neutral or positive towards Jesus.
* WG, tertiary U: The Believers
    * This group will sacrifice their lives to support the message of Jesus.
    * Black sacrifice effects are considered off-type for the Believers, despite their willingness to die.
* WR, tertiary G: The Government
    * The Government can be neutral, beneficial, or harmful.
* UG, tertiary B: The Creators
    * This tribe can violate the laws of nature.
* BR, tertiary G: The Free
    * Satan and his minions.
* WB, tertiary R:
* UR, tertiary G: The Essenes
    * This group are mystics.
* BG, tertiary R: 
* RG, tertiary B: The Nephilim.
## The Lands
Dual lands enter tapped with a stun counter, and create a treasure token. The lands are typed. All ten pairs are represented.
## The Plagues
* Boils - BR
* Frogs - BG
* Hail - UR
* Lice - UB
# Release Notes
## Existing Mechanics
* Finality
* Commiting a crime
* Vansishing
* Gifting

## New Mechanics and Special Creatures
We have one new mechanic: Inspire: When an Inspired creature dies, its controller creates a food token.

The creature names Jesus, Adam and Eve all have cross-referenced rules text. Assume that the infant you created and the very powerful grownup Jesus are the same person (Teenager schooling the temple, too).

There are three new creature types:
* Donkey (In rules text and cardnames, it is considered synonymous with ass)
* Infant
* Rooster

The Deserter creature type has appeared before on tokens. It is present in this set on a proper creature.

Because this set is both Biblical and Trinitarian, yes, you can target Jesus with a spell that wants to target the Holy Spirit.

For now, יהוה is excluded.

## Zones
There are three named zones - Heaven, Hell, and Limbo. There are cards associated to each, but they needn't be in play for the zones to exist.

Sending a creature to any is not an exile effect (unless specified by another card). Creatures do enter the graveyard before they meet their destiny.  Creatures cannot leave these zones.

Creatures in these zones lose all attributes and abilities apart from type. Specifically, they contribute to devotion, and the number of creatures you control.

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
* Deuterocanonical works are allowed but Apocrypha are not.
## Art
Look at a [CC0](https://creativecommons.org/public-domain/cc0/) source, or draw something of your own.
## General QC and templating
Edit and standardize.
## MSE API
This does not exist but it should.
## Balance the Wheels
Propose a framework for these cards to be made into a proper set.
# Biblical Translations
We are flexible. The purpose of this set is to be fun, not communicate theology.

The primary author of this set uses [RSVCE](https://www.biblegateway.com/versions/Revised-Standard-Version-Catholic-Edition-RSVCE-Bible/)

## Citations
 Chapter and Verse: `<chvs>`. This tag has no effect on gameplay.