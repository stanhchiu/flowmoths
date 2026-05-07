# Flow Moths

A project for a 3D printed LED lit balisong for lightshows and performances.  All original credit goes to Lucas Chen

# Printing

## Prints
The print files are under the `models` directory.  The `obj` files may need scaling to full size.  Refer the measurements below for the desired thickness and scale accordingly in your slicing software.

* Handles
  * 4x `handle.obj`
    * Thickness: 5mm or .2in
  * 2x `inter cap-rounded-reinforced.stl`
    * Note: one print can be mirrored on the X axis optionally to position the buttons on the same side
  * 2x `interior-rounded.stl`
    * Mirror one on the X axis if the above is mirrored
* Blade
  * 1x `blade.obj`
    * Thickness: 2.4mm or .095in
    * ABS recommended as a PETG part is a bit flimsy
  * 1x `blade-cap.stl`
  * 1x `blade-cap2.stl`

PETG or ABS with 100% infill and gyroid fill pattern are recommended for strength to withstand drops.  Voids should face up on the prints with hollows to avoid the need for supports in hard to reach places, tree supports for the handle interior piece is recommended. Additional scaling may be needed to account for printer differences or shrinkage to different filaments.

A knife to cut around the buttons will be needed, along with the standard support removal, filing, and drilling to finish holes.  This will be particularly important around the pivots as they will be tight without proper clearance in the holes and part thickness.

# Additional Parts

## Balisong Parts
Some hardware is needed to assemble the balisong structure.  [USA Knife Maker](https://usaknifemaker.com/shop-categories/folding-knife-parts/pivots-pivot-lap.html) seems to be the best source.

* Handles
  * 8x 1/2" x 1/8" Pivot Barrels
  * 16x T-6 Torx screws
* Blade
  * 2x 1/2" x 1/8" Pivot Barrels
  * 4x T-6 Torx screws
* Central Pivots
  * 2x 1/2" x 3/16" Pivot Barrels
  * 4x T-9 Torx screws
  * 4x brass bushings, 1/2" OD, 3/6" ID

## LEDs
The original designs use the **eLite Flow V2** gloving microlights from **EmazingLights.com**, however these have since been discontinued.

The [Aeos Microlight](https://www.glow-leds.com/products/aeos_microlight) is a drop-in replacement.

# Assembly

## Handles
The interior section and interior cap are sandwiched by the other handle pieces.  The LED module goes into the void between the interior section and the cap with the button facing the cap.  Secure everything with the small pivot barrels.

## Blade
The blade caps fit on either side of the blade section, secure with the small pivot barrels.  The LED module goes into the void, aligning the buttons.

## Pivot
With bushings between the blade and handle sections, use the large barrels to attach the handles to the blade section.  Make sure the open part of the handle faces the blade so it can fully close.

# Notes
* Sub-section weights with small pivots, LEDs, and battery, no large pivot.  Including this information primarily for balancing.  It seems like the original is tuned so the blade section is 1/2 the weight of a handle section
  * Handle: 1.69 oz
  * Blade: 0.85 oz

# Credits
Links to original artifacts
* https://www.instagram.com/flowmoths/
* https://www.lucaschen.studio/flow-moths
* https://www.lucaschen.studio/workold/flow-moths
* (Defunct) https://flowmoths.com/
* https://www.reddit.com/r/balisong/comments/nul20t/trainer_collection_new_bali_that_has_built_in_led/