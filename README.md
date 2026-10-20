# Bayou Studio

Bayou Studio makes Steam profile artwork with Hunt: Showdown hunters in it. You pick a hunter, their guns and a
walkout, pose them in 3D, design the artwork around them, and bake it into the animated GIF or APNG you upload to
your Steam profile's artwork showcase.

The preview is your real Steam profile page, with your background and the artwork swapped in, so you see exactly what
visitors will see before you upload anything.

## What you can do

- **Pose any hunter.** Every hunter skin in the game (367), holding any primary and with any secondary holstered where
  the game puts it (over 800 weapons, legendary skins included), with any of the 127 weapon charms, or empty-handed.
- **Animate them.** Play any walkout on any hunter, followed by the gun's draw and its menu idle, as the game's menu
  does. Trim the loop, repeat it, ping-pong it, blend its end into its start, play it once and hold, or turn the
  hunter on a turntable.
- **Light them.** The game menu's own lighting, read from the game's menu level (lights, shadows, reflections and colour
  grade), or a neutral studio light. Adjust saturation and gamma, and lay colour gradients over the hunter.
- **Use up to four hunters** in one artwork, each posed and placed with its own camera.
- **Build the artwork in layers:** hunters, your own images, text and blurred areas, in any order, dragged, resized
  and rotated right on the preview. Text comes in about 200 fonts (or upload your own) with 22 effects such as
  handwriting, typewriter, burn-in, glitch and neon.
- **Choose a background** from a ranked catalogue of Steam backgrounds, the Steam points shop, your own upload, or a URL.
- **Set the size:** 630 px wide, as Steam shows it, and from 100 to 2500 px tall. Taller than 800 px, the app points you
  to the guide for uploading long artwork.
- **Bake it for Steam:** a GIF or an APNG under Steam's 5 MB limit, at the artwork's exact size, with the background
  behind it baked in or left transparent. A slider decides whether a file that must shrink keeps its smooth motion or
  its image quality. Bakes are kept for a week, then deleted, so download yours.

## Reporting an issue

Use **Report an issue** in the app's top bar, or open one directly at
[github.com/bayoustudio/bayoustudio/issues](https://github.com/bayoustudio/bayoustudio/issues).

## Known limitations

- Cloth (cloaks, coat tails) moves with the body but isn't simulated, so it doesn't drape or swing. Charms hang still
  in their rest pose.
- A few legendary weapons name textures the game no longer ships, so they render untextured.
- A GIF has one loop for the whole file, so an intro can't play once before a looping idle. Play once and hold is the
  closest option.
- Whether Steam's showcase animates an APNG is untested; GIF is the safe choice.

## Third-party pieces

- Fonts: Inter and Playfair Display (SIL Open Font License), and the caption fonts in `site/public/fonts` (each with
  its licence in `site/public/fonts/licenses/`).
- Icons: [Lucide](https://lucide.dev) (ISC).
- gifski (AGPL) is used as a separate program if you install it. It is not part of this repository.
- Hunt: Showdown and its assets © Crytek. This project isn't affiliated with or endorsed by Crytek or Valve.
