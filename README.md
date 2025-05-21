# Overview
* Magic: the Gathering cards based upon the Bible.
* We do not endorse, intentionally demean, nor otherwise express an opinion towards any religion.
* These cards are a meant as a respectful way to engage the Bible as a historical and literary work.
* __mtg-bible__ is unofficial Fan Content permitted under Wizards' [Fan Content Policy](https://company.wizards.com/en/legal/fancontentpolicy). This content is neither approved nor endorsed by Wizards. Portions of the materials herein are property of Wizards of the Coast.

# Usage
* Install [Cockatrice](https://cockatrice.github.io/).
* Place `01.cockatrice_db.xml` into your customsets folder.
* Optionally, to use our images, place them into your custompics folder.
# Contents
## db 
* `01.cockatrice_db.xml`
## Card Sketches
* `card_sketches.txt` describes whiteboarded cards envisioned in an ad-hoc, top-down style. The format is sufficient to communicate the nature and effects of each, and mimics WotC's release notes.    
## Artwork
### Attribution
Cards in the db have a custom `<imgsrc>` tag.

All images are [CC0](https://creativecommons.org/public-domain/cc0/) or in the public domain.

Some cited sources:
* [The National Gallery of Art](https://www.nga.gov/collection/collection-search.html)
* [The Walters](https://art.thewalters.org/)
* [Wikimedia Commons](https://commons.wikimedia.org/)

### Raw Images
* Details cropped from `<imgsrc>`.
### Images
* Produced by [Magic Set Editor](https://magicseteditor.boards.net/).
### MSE
* File: `mse_db`
* When there are discrepancies between this file and the Cockatrice db, this file is considered authoritative.
# Set Design
## Color pairs
* UB, tertiary R: The Sadducees
    * This group rejects predestination, and does not believe in an afterlife.
    * The law is enforced by this group's colors.
* UW, tertiary G: The Pharisees
    * This group believes in tradition.
    * This group is neutral or positive towards Jesus.
* WG, tertiary U: The Believers
    * This group will take actions to support Jesus.
    * Black sacrifice effects are considered off-type for the believers.
* WR, tertiary G: The Government
    * This group can be neutral, beneficial, or harmful.
* UG, tertiary B: The Creators
    * This group can violate the laws of nature.
* BR tertiary G: The Free
    * Satan and his minions.
* WB, tertiary R:
* UR, tertiary G: The Essenes
    * Mystics.
* BG, tertiary R: 
* RG, tertiary B: The Nephilim.
## Lands
Dual lands enter tapped with a stun counter but create a treasure token when they enter. These lands are typed. All ten pairs are represented.
## The Plagues
* Boils - BR
* Frogs - BG
* Hail - UR
* ...
# Release Notes
## Existing Mechanics
* Finality
* Commiting a crime
* Vansishing
* Gifting

## New Mechanics and Special Creatures
* Inspire - When an Inspired creature dies, its controller creates a food token.
* The creature names Jesus, Adam and Eve all have cross-referenced rules text.
* The Deserter type has appeared on tokens. It is present in this set on a proper creature.

This set is trinitarian so yes, you can target Jesus with a spell meant to target the Holy Spirit.

For now, יהוה is not represented.

## Zones
There are three new named zones - Heaven, Hell, and Limbo.

Sending a creature to any is not an exile effect (unless specified by another card). Creatures _do_ enter the graveyard before they meet their destiny.

Objects lose all attributes and abilities when they are in these zones apart from type and mana cost. Specifically, they still contribute to devotion and the number of creatures you control.

* When a creature is in Heaven, it gains {T}: You gain 2 life.
* When a creature is in Hell, it gains {T}: Add B or R. You lose two life.
* When a creature is in Limbo, it gains {T}: Add {C}.

## Citations
 * The primary author of this set references [NRSVCE](https://www.biblegateway.com/versions/New-Revised-Standard-Version-Catholic-Edition-NRSVCE-Bible).
 * Images from NGA are hereby credited as _Courtesy National Gallery of Art, Washington_.
 * Chapter and verse: `<chvs>`. This tag has no effect on gameplay.