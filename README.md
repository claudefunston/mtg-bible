# Overview
These are Magic: the Gathering cards based upon the Bible.

We do not endorse, demean, nor otherwise express an opinion on relegion. These cards are a respecful way to engage the Bible as a historical and literary work.

__mtg-bible__ is unofficial Fan Content permitted under Wizards' [Fan Content Policy](https://company.wizards.com/en/legal/fancontentpolicy). This content is not approved nor endorsed by Wizards. Portions of the materials herein are property of Wizards of the Coast.

This project welcomes any feedback.

# Usage
* Install [Cockatrice](https://cockatrice.github.io/).
* Place `01.cockatrice_db.xml` into your customsets folder.
* Optionally, if you want to use our images, place them into your custompics folder.

You can access either from the Cockatrice UI via the Card Database menu.
# Contents
## db 
* `01.cockatrice_db.xml`.
## Card Sketches
* `card_sketches.txt`.
These are Whiteboarded cards envisioned in an ad-hoc, top-down style. They are presented in a non-standardized format, but mimicking WotC's. They are sufficient to communicate the nature, effects, and idea of each card.

Once moved to db, cards here are deleted.

## Images
### Recordkeeping and Attribution
Cards in the db have a non-standard `<imgsrc>` tag to record their origens.

All images are [CC0](https://creativecommons.org/public-domain/cc0/) licensed.

We very much enjoy works from [The National Gallery of Art](https://www.nga.gov/collection/collection-search.html).

Images with an NGA source are credited by us as _Courtesy National Gallery of Art, Washington_.

[The Met](https://www.metmuseum.org/art/collection/search) is a good source as well.

### Raw Images
* `images_raw`
* These are cropped from `<imgsrc>`. It is a recordkeeping mechanism.
### Images
* `images`
* Cards are placed into frames using [Magic Set Editor](https://magicseteditor.boards.net/)
### `mse_db`
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
## The Plague Cycle
###
* שְׁחִין
* צְפַרְדֵּעַ
* כִּנִּים
* עָרוֹב
* דֶּבֶר
* שְׁחִין
* בָּרָד
* חֹשֶׁךְ
* מַכַּת בְּכוֹרוֹת
# Release Notes
## Existing Mechanics
Finality Counters have returned. When a creature with a Finality Counter on it dies, it is exiled instead of being sent to the graveyard.

## New Mechanics and Special Creatures
We have one new mechanic: Inspire: When an Inspired creature dies, its controller creates a food token.

The creature names Jesus, Adam and Eve all have cross-referenced rules text. Assume that the infant you created and the very powerful grownup Jesus are the same person. (Teenager schooling the temple, too.)

There are three new creature types:
* Donkey. In rules text and cardnames, it should be considered synonymous with ass.
* Infant.
* Rooster.

The Deserter creature type has appeared before on tokens. It is present in this set on a proper creature.

Because this set is both Biblical and Trinitarian in nature, yes, you can target Jesus with a spell that wants to target the Holy Spirit.

For now, יהוה is considered too powerful to include.

## Zones
There are three new named zones - Heaven, Hell, and Limbo. The Lands naming them needn't be in play for the zones to exist.

Sending a creature to any of these is not an exile effect (unless specified by another card). Creatures do enter the graveyard before they meet their destiny. As tokens cease to exist when they enter the graveyard, tokens can't reach these zones.

Creatures in these zones lose all attributes and abilities apart from type. Specifically, they contribute to devotion, and count for the number of creatures you control.

Just as the exile zone operates, each player has their own version of these zones.

* When a creature is in Heaven, it gains {T}: Add 2 life.
* When a creature is in Hell, it gains {T}: Add B or R. You lose two life.
* When a creature is in Limbo, it gains {T}: Add {C}.

# Contributing
## Design a card
Think of your favorite Biblical hero or event and get cracking.

Some considerations:
* Absolutely no advocation nor condoning of sexual violence.
* Smiting sinful individuals and Armogeddening an entire city are acceptable acts and concepts, as are horrible diseases, plagues and Divine mind control.
* Deuterocanonical works are gladly included; Apocrypha are not. Maybe for the expansion.
* Cards can suggest, imply or compel that a character made a choice not described in the Bible if it makes a better card or produces interesting thought.
## Make some Art
Either find a CC0 source, or draw something of your own.
## Balance the Wheels
This set needs organization, and a skeleton to take the cards from isolated ideas into a proper system. Rarity is currently ambiguous.

# Biblcal Translations
We are by and large translation agnostic, because meaning can be difficult to decipher if you don't know Hebrew and Greek (&c). The purpose of this set is to produce fun, not communicate Theology.

The primary author of this Set uses [RSVCE](https://www.biblegateway.com/versions/Revised-Standard-Version-Catholic-Edition-RSVCE-Bible/).

We adopt the stance that characters adhere to the loosely-defined concept of "what the populace understands about this person or story."
## Citations
Whenever sensible, we attach a custom tag to cards: `<chvs>`. Chapter and verse. Consistency between Acts and the Synoptic Gospels is not always guaranteed. These tags have no gameplay effect.