# Overview
These are Magic: the Gathering cards based upon the Bible

We do not endorse, intentionally demean, nor otherwise express an opinion on any relegion. 

These cards are a meant as a respecful way to engage the Bible as a historical and literary work

We strongly discourage any disparaging references to Christianity, Judaism, or any other Faith. If you contribute, we reserve the right at our sole discretion to reject any card or concept violating that principle
 
__mtg-bible__ is unofficial Fan Content permitted under Wizards' [Fan Content Policy](https://company.wizards.com/en/legal/fancontentpolicy). This content is not approved nor endorsed by Wizards. Portions of the materials herein are property of Wizards of the Coast.

# Usage
* Install [Cockatrice](https://cockatrice.github.io/)
* Place `01.cockatrice_db.xml` into your customsets folder
* Optionally, to use our images, place them into your custompics folder. Otherwise, use your own. ADHERE TO OUR LEGAL ATTRIBUTION POLICIES, DESCRIBED BELOW AND ABOVE
    * We believe that artwork should be free for the public, but we adhere to the rights authors intended and understand that copyright law does not allow us to do so
* To edit card images, use [Magic Set Editor](https://magicseteditor.boards.net/)
    * Coordinate the Cockatrice db with this file
    * Any imagas that are not on current display at their respective galleries are given priority, in order to increase publicity. We believe that the public should have access and use to artworks, but we understand that rights are necessary
# Contents
## db 
* `01.cockatrice_db.xml`
## Card Sketches
* `card_sketches.txt`
These are whiteboarded cards envisioned in an ad-hoc, top-down style. They are presented in a non-standardized way, but mimicking WotC's closely. The format is sufficient to communicate the nature and effects of each card

Once moved to db, card descriptions are deleted. This folder is intended to be deprecated
## Master Image File
* `mse_db`

## Artwork
### Recordkeeping and Attribution
Cards in the db have an `<imgsrc>` tag to record their origins

All images are [CC0](https://creativecommons.org/public-domain/cc0/), or licensed in the public domain with sufficient permissions. We prefer if public domain images do not have content attribution requirements

Our preferred source is [The National Gallery of Art](https://www.nga.gov/collection/collection-search.html).

Images from NGA are hereby credited as _Courtesy National Gallery of Art, Washington_

### Raw Images
* `images_raw`
* These are cropped from `<imgsrc>`. It is a recordkeeping mechanism
### Images
* `images`
* Cards are placed into frames using [Magic Set Editor](https://magicseteditor.boards.net/)
### Magic Set Editor
* `mse_db`
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
# Release Notes
## Existing Mechanics
* Finality Counters. When a creature with a Finality Counter on it dies, it is exiled instead of being sent to the graveyard
* Commiting a crime. You commit a crime in Magic whenever you target an opposing player or their objects, defined as their spells on the stack, their permanents on the battlefield, or cards in their graveyard

## New Mechanics and Special Creatures
We have one new mechanic: Inspire: When an Inspired creature dies, its controller creates a food token

The creature names Jesus, Adam and Eve all have cross-referenced rules text. Assume that the infant you created and the very powerful grownup Jesus are the same person (Teenager schooling the temple, too)

There are three new creature types:
* Donkey. In rules text and cardnames, it should be considered synonymous with ass
* Infant
* Rooster

The Deserter creature type has appeared before on tokens. It is present in this set on a proper creature

Because this set is both Biblical and Trinitarian in nature, yes, you can target Jesus with a spell that wants to target the Holy Spirit

For now, יהוה is considered too powerful to include

## Zones
There are three new named zones - Heaven, Hell, and Limbo. There are cards associated to each, but they needn't be in play for the zones to exist

Sending a creature to any is not an exile effect (unless specified by another card). Creatures do enter the graveyard before they meet their destiny.  Creatures cannot leave these zones

As tokens cease to exist at a time just after entering the graveyard, tokens can't reach them

Creatures in these zones lose all attributes and abilities apart from type. Specifically, they contribute to devotion, and count for the number of creatures you control

Just as the exile zone operates, each player has their own version of each

* When a creature is in Heaven, it gains {T}: Add 2 life
* When a creature is in Hell, it gains {T}: Add B or R. You lose two life
* When a creature is in Limbo, it gains {T}: Add {C}

# Contributing
## Design a card
Think of your favorite Biblical hero or event

Some considerations:
* Absolutely no advocation nor condoning of sexual violence
* Absolutely no direct insults nor advocation of Christianity, Judaism, nor any another Faith. We reserve the right at our sole discrection to enforce this policy
* Smiting sinful individuals and Armogeddening an entire city are acceptable concepts to describe in cards. As are horrible diseases, plagues and divine mind control
* Deuterocanonical works are gladly included; Apocrypha are not
    * For example: Judith and Tobit are fine, Enoch is not
* Cards can suggest, imply or compel that a character made a choice not precisely described in the Bible if it makes a better card or produces an interesting thought
    * For example: Peter can choose to not deny Christ
## Make some Art
Find a [CC0](https://creativecommons.org/public-domain/cc0/) source, or draw something of your own.
## Balance the Wheels
This set needs a skeleton to take the cards from isolated ideas into a proper system. Rarity is currently ambiguous.

# Biblcal Translations
We are open to many, because meaning can be difficult to decipher if you don't know Hebrew nor Greek of some variety. The purpose of this set is to produce fun, not communicate Theology.

The primary author of this set uses [RSVCE](https://www.biblegateway.com/versions/Revised-Standard-Version-Catholic-Edition-RSVCE-Bible/) but is certainly open to discussion.

## Citations
 Chapter and Verse: `<chvs>` -  is an optional but preferred tag.