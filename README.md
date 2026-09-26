# Johnny Silverhand Codex Pet

A custom animated desktop pet inspired by Johnny Silverhand from **Cyberpunk 2077**, created with Codex and AI-generated character artwork.

**This is an unofficial fan work and is not approved or endorsed by CD PROJEKT RED or OpenAI.**

## Preview

![Working animation: laptop and cigarette](media/working.gif)

While Codex is working, Johnny holds a small laptop and smokes a cigarette. The pet includes nine standard animation states and sixteen look directions.

## Install

1. Download [johnny-silverhand.zip](johnny-silverhand.zip).
2. Extract `pet.json` and `spritesheet.webp` into `~/.codex/pets/johnny-silverhand/`.
   On Windows, this is `%USERPROFILE%\.codex\pets\johnny-silverhand\`.
3. Select Johnny Silverhand in the app's pet selector. Restart the app if the custom pet does not appear.

The package uses `spriteVersionNumber: 2`, an 8 × 11 atlas, 192 × 208 pixel cells, and a 1536 × 2288 transparent WebP spritesheet. It has passed structural validation and visual animation review.

## Files

- `pet/`: installable pet definition and spritesheet.
- `media/working.gif`: working-state animation.
- `media/spritesheet-preview.png`: overview of the animations and look directions.
- `references/`: generated canonical character, cardinal look references, and working poses used during production.

## Credits and references

- Character inspiration: Johnny Silverhand, **Cyberpunk 2077**, CD PROJEKT RED.
- Generated character art and sprite poses: created through the Codex image-generation workflow.
- Official character references consulted: [Cyberpunk 2077 cosplay guides](https://www.cyberpunk.net/en/cosplay-guides) and the [Ultimate Edition booklet](https://cdn-s-cyberpunk.cdprojektred.com/CP2077-UE-Booklet-EN-1.pdf).
- [CD PROJEKT RED Fan Content Guidelines](https://www.cdprojektred.com/en/fan-content).

Cyberpunk 2077, Johnny Silverhand, the original soundtrack, and related intellectual property remain the property of their respective rights holders. This repository does not grant a license to those underlying works.
