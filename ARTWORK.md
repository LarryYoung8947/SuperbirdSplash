# Website artwork

Both header and footer use `assets/superbird-logo.png`, a transparent image isolated with the built-in image-generation tool from the title on the game's `ArtSource/Superbird/superbirdSpriteV1.png`. This preserves the source's yellow/orange lettering, red cape, and navy outline rather than substituting a web font. It is a generated extraction, not a pixel-identical crop. A subsequent edit removed the blue version number at the user's request.

Extraction prompt:

> Extract ONLY the complete SUPERBIRD 2.0 logo at the TOP LEFT of this spritesheet. Exact duplicate of that existing logo: preserve the original yellow-orange Superbird lettering, chunky dark navy outline, red cape above the lettering and blue 2.0 tucked underneath at right. Do not redesign, do not use a different font, do not alter text, color or shape. Remove everything else, including the 'Small Bird. Big Adventure.' tagline, all birds, labels, and the checkerboard background. Output the isolated original logo as a wide tightly framed asset with genuine transparent alpha background, with a small clear margin around all edges. No checkerboard, no background, no new design.

Final edit prompt (built-in image-generation tool, using the extracted logo as the edit target):

> Edit target: the attached transparent Superbird logo. Remove ONLY the blue '2.0' text at the lower right, including its outline and shadow, making that area transparent. Preserve the SUPERBIRD lettering, yellow/orange colors, dark navy outline, red cape, all other shapes, scale, position, and wide 2:1 canvas composition exactly as they are. Where the removed number touches the cape or lettering, finish their existing contours cleanly. Do not redesign, resize or reposition the logo. No new text. Output a PNG with genuine transparent alpha background; no colored background or checkerboard. The final logo must say only SUPERBIRD.

The hero uses copies of `Assets/Art/Farm/FarmDistant.png` and `Assets/Art/Farm/FarmFields.png` from the game as `assets/hero-sky.png` and `assets/hero-fields.png`. The bird remains the existing `assets/superbird-flight.png`; CSS displays one frame without stretching it.
