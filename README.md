# Overview
These are cards meant to interact with the game system of Magic: the Gathering. The concepts are based upon the Bible.

We adopt a neutral stance towards religion. These cards are a respecful way to interact with the Bible as a historical and literary work.

__mtg-bible__ is unofficial Fan Content permitted under Wizards' [Fan Content Policy](https://company.wizards.com/en/legal/fancontentpolicy). This content is not approved nor endorsed by Wizards. Portions of the materials herein are property of Wizards of the Coast.

# Usage
* Install [Cockatrice](https://cockatrice.github.io/).
* Place `01.cockatrice_db.xml` into `%LOCALAPPDATA%\Cockatrice\Cockatrice\customsets`.
* Optionally, move contents of `images` into `%LOCALAPPDATA%\Cockatrice\Cockatrice\pics\CUSTOM`.

You can access both of these folders from the Cockatrice UI via the Card Database menu.
# Contents
## db 
* `01.cockatrice_db.xml`.
    * Tested to load into Cockatrice. Cards here are under consideration for inclusion in the set.
    * The numerical prefix is necessary to load multiple custom sets in a Cockatrice instance.
## Card Sketches
* `card_sketches.txt`.
These are Whiteboarded cards envisioned in an ad-hoc, top-down style. They are presented in a non-standardized format, but mimicking WotC's. They are sufficient to communicate the nature, effects, and idea of each card.

Once moved to db, cards here are deleted.

## Images
### Recordkeeping and Attribution
Cards in the db have a non-standard `<imgsrc>` tag. They will not load diretly into Cockatrice, but as now don't break anything.

All images are licensed under [CC0](https://creativecommons.org/public-domain/cc0/).

We very much enjoy artwork pulled from [The National Gallery](https://www.nga.gov/collection/collection-search.html). [The Met](https://www.metmuseum.org/art/collection/search) is a good source as well.

### Raw Images
* `images_raw`
* These are cropped from the `<imgsrc>` of each card. It is a recordkeeping archive.
### Images
* `images`
* Cards are placed into frames using [Magic Set Editor](https://magicseteditor.boards.net/)
### `mse_db`
An MSE file used to create framed images of artwork.
# Bottom-up Design Framework
## Color pairs
* UB, tertiary R: The Sadducees
* UW, tertiary G: The Pharisees
* WG, tertiary U: The Believers
* WR, tertiary G: The Government
* UG, tertiary R: The Creators
* BR, tertiary U: The Heretics
* WB, tertiary R: The Essenes
* UR, tertiary G: The Mystics
* BG, tertiary R: The Lifegivers
* RG, tertiary B: The Giants
# Release Notes
## Existing Mechanics
Finality Counters have returned. When a creature with a Finality Counter on it dies, it is exiled instead of being sent to the graveyard.

## The Lands
Dual lands enter tapped with a stun counter, but they give you a treasure token. Lands are typed. All ten pairs are represented.

## New Mechanics and Special Creatures
We have one new mechanic: Inspire: When an Inspired creature dies, its controller creates a food token.

The names Jesus, Adam and Eve all have cross-referenced rules text. Assume that the infant you created and the very powerful grownup Jesus are the same person. (Teenager schooling the temple, too.)

There are two new creature types:
* Donkey. In rules text and cardnames, it should be considered synonymous with ass.
* Infant.

The Deserter creature type has appeared before only on tokens, but is present in this set on a proper creature.

Because this set is both Biblical and Trinitarian in nature, yes, you can target Jesus with a spell that wants to target the Holy Spirit.

For now, יהוה is considered too powerful to include.

## Zones
There are three new named zones - Heaven, Hell, and Limbo. The Lands naming them needn't be in play for the zones to exist.

Sending a creature to any of these is not an exile effect (unless specified by another card). Those creatures do enter the graveyard before they meet their destiny.

Creatures in these zones lose all attributes and abilities. Specifically, they do not contribute to devotion nor the number of creatures you control.

Just as the exile zone operates, each player has their own version of these zones.

* When a creature is in Heaven, it gains {T}: Add 2 life.
* When a creature is in Hell, it gains {T}: Add B or R. You lose two life.
* When a creature is in Limbo, it gains {T}: Add {C}.

# Contributing
## Design a card
Simply think of your favorite Biblical hero or event, and create something that makes sense in that context. Slight violations of the color pie are acceptable.

Some considerations:
* Absolutely no advocation nor condoning of sexual violence.
* Smiting sinful individuals and Armogeddening an entire city are acceptable acts and concepts, as are horrible diseases, plagues and Divine mind control.
* We prefer that everything comes directly from the Bible. References to Deuterocanonical works are gladly included.
* Cards can suggest, imply or compel that a Biblical character made an alternate choice otherwise not described in the original story if it makes for a better card or interesting thought.
## Make some Art
Either find a CC0 source, or draw something of your own.
## Balance the Wheels
This set needs some organization, and a skeleton to take the cards from isolated ideas into a proper system.
# Biblcal Translations
We are by and large translation agnostic, because meaning can be difficult to decipher if you don't know Hebrew and Greek (&c), and the purpose of this set is to produce fun, not communicate Theology.

The primary author of this Set uses [RSVCE](https://www.biblegateway.com/versions/Revised-Standard-Version-Catholic-Edition-RSVCE-Bible/).

We adopt the stance that characters adhere to the loosely-defined concept of "what the populace understands about this person or story."
## Citations
Whenever reasonable, we attach a custom tag to each card: `<chvs>`. Chapter and verse. Consistency between Acts and the Synopic Gospels is not always guaranteed. These tags have no function on gameplay.