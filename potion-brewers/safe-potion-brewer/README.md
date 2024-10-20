## Designer
- @flafy

## Credits
- Inspired by @meowphedrone's 2 Wide Tileable Potion Brewer for the brewing cycle.
- @sam.8742 for the horizontal item gate

## Versions
- 1.21+

## Rates
Around 245/h Potions with 2 ingredients

## Description

The brewer will safely and automatically brew the desired potion. It's designed to be fail-proof, unlike other brewers of this form factor which fail when there is a lack of ingredients, potions, etc.

Supports 2+ ingredients.

Tileable with a gap of 1 block, since ingredients are accessed from the right side and Redstone will interfere. Potions are accessible from both the right side and front. 

## Files

2 ingredients(3x8x5): [Image]() [Litematic]()

5 ingredients(3x8x8): [Image]() [Litematic]()

## Positives

- Cannot fail due to missing resources. When one of the materials needed to create the potion is missing, the brewer will stop until resupplied.

## Negatives

- More expensive to build compared to non-failproof potion brewers of this size.
- No bottle filler.
- Not tileable.

## Instructions

### Build
- Not directional or locational.
- It's relatively straightforward how to add more slots for ingredients. Look at the differences between the 2 ingredients and 5 ingredients brewers. This is how the slice looks: [Slice image]()

### Initial setup
Only do this once after building the brewer.

1. Place a single item that can be stacked to 64 in the inner hopper. [Image]().
2. Place 19 items that can be stacked to 64 in the 2nd slot of the hopper above the brewing stand. Place a single item in the 3rd, 4th, and 5th slots of the hopper. So only the 1st slot should be free. [Image](). 
3. Figure out the order of ingredients for your potion. For example: [Nether Warts, Gunpowder, Golden Carrot, Fermented Spider Eye, Redstone Dust].
4. Place the first ingredient in the brewing stand.

### Resupply
This is where each of the brewer's resources go.

[How to resupply image]()

1. Filled bottles go into the top right barrel.
2. Blaze powder goes into the brewing stand.
3. The ingredients go to the droppers. The 1st ingredient goes to the rightmost dropper and the rest go left to right. This may be confusing, see the resupply image.
4. Make sure the brewed potion barrel is empty.

Once resupplied, the farm will auto-start.
