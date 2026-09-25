# Website artwork

Both header and footer use `assets/superbird-logo.png`, a transparent image isolated with the image-generation tool from the title on the game's `ArtSource/Superbird/superbirdSpriteV1.png`. This preserves the source's yellow/orange lettering, red cape, navy outline, and blue 2.0 rather than substituting a web font. It is a generated extraction, not a pixel-identical crop.

Extraction prompt:

> Extract ONLY the complete SUPERBIRD 2.0 logo at the TOP LEFT of this spritesheet. Exact duplicate of that existing logo: preserve the original yellow-orange Superbird lettering, chunky dark navy outline, red cape above the lettering and blue 2.0 tucked underneath at right. Do not redesign, do not use a different font, do not alter text, color or shape. Remove everything else, including the 'Small Bird. Big Adventure.' tagline, all birds, labels, and the checkerboard background. Output the isolated original logo as a wide tightly framed asset with genuine transparent alpha background, with a small clear margin around all edges. No checkerboard, no background, no new design.

The hero uses copies of `Assets/Art/Farm/FarmDistant.png` and `Assets/Art/Farm/FarmFields.png` from the game as `assets/hero-sky.png` and `assets/hero-fields.png`. The bird remains the existing `assets/superbird-flight.png`; CSS displays one frame without stretching it.
