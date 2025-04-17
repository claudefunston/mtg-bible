# Overview
These are cards meant to interact with the game system of Magic: the Gathering. The conepts are based upon the Bible.

We are neutral on the concept of religion. The cards are aimed to be a respecful way to interact with the Bible as a historical and literary work.

We adhere to WotC's [Fan Content Policy](https://company.wizards.com/en/legal/fancontentpolicy). 

# Usage
* Install [Cockatrice](https://cockatrice.github.io/).
* Place `01.cockatrice_db.xml` into `~/Cockatrice/Cockatrice/customsets`.
* Optionally, move contents of `images` into `~/Cockatrice/Cockatrice/pics/CUSTOM`.

# Contents
## db 
* `01.cockatrice_db.xml`.
* This is an .XML file tested to load into Cockatrice. Cards here are under consideration for inclusion in the set.
** The numerical prefix is necessary to load multiple custom sets in a Cockatrice instance.
## Card Sketches 
* `card_sketches.txt`.
** These are Whiteboarded cards envisioned in an ad-hoc, top-down style. They are presented in a non-standard format, sufficient to communicate the nature, effects, and idea of each card. The style mimics, but does not stricly adhere to standard card templating.

Once moved to db, cards here are deleted.

## Images
### Recordkeeping and Attribution
Cards in the db have a non-standard `<imgsrc>` tag. They will not load into Cockatrice, but as now don't break anything.

Images are drawn from sources using the [CC0](https://creativecommons.org/public-domain/cc0/) license.

### Raw Images
* `images_raw`
* Cropped images linked to cards as a 1-1 mapping. This is a recordkeeping mechanism.
### Images
* `images`
* After loading an image from `images_raw`, cards are placed into frames using [Magic Set Editor](https://magicseteditor.boards.net/)
### `mse_db`
The Set Editor file used to created framed images of artwork. Work in progress.
# Release Notes
## Returning Mechanics
Finality Counters have returned. When a creature with a Finality Counter on it dies, it is exiled instead of being sent to the graveyard.

## New Mechanics and Special Creatures
We have one new mechanic: Inspire: When an Inspired creature dies, its controller creates a food token.

The names Jesus, Adam and Eve all have cross-referenced rules text. Assume that the infant you created and the very powerful grownup Jesus are the same person. (Teenager schooling the temple, too.)

There is also a new creature type, Donkey. In rules text and cardnames, it should be considered synonymous with ass.

Because this set is both Biblical and Trinitarian, yes, you can target Jesus with a spell that wants to target the Holy Spirit.

For now, יהוה is considered too powerful to include.

## Zones
There are three new named zones - Heaven, Hell, and Limbo. The lands naming them needn't be in play for the zones to exist.

Sending a creature to any of these is not an exile effect (unless spefified by another card), and they do not enter the graveyard in transit.

Just as the exile zone operates, each player has their own version of each.

* When a creature is in Heaven, it gains {T}: Add 2 life.
* When a creature is in Hell, it gains {T}: Add {BR}. You lose one life.
* When a creature is in Limbo, it gains {T}: Add {C}.

# Contributing
## Design a card
Simply think of your favorite Biblical hero or event, and create something that makes sense in that context. Slight violations of the color pie are acceptable.

Some considerations:
* Absolutely no advocation nor condoning of sexual violence.
* Smiting sinful individuals and Armogeddening an entire city are acceptable acts and concepts, as are horrible diseases, plagues and Divine mind control.
* We prefer that everything comes directly from the Bible. References to Deuterocanonical works are gladly included.
* Cards can suggest, imply or compel that a Biblical character made an alternate choice otherwise not described in the original story if it makes for a better card or interesting thought.

# Translations
We are by and large translation agnostic, because meaning can be difficult to decipher if you don't know Hebrew and Greek (&c), and the purpose of this set is to produce fun, not communicate Theology.

We adopt the stance that characters adhere to the loosely-defined concept of "what the populace understands about this person or story."