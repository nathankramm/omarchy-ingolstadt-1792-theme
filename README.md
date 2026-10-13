# Ingolstadt 1792

![Ingolstadt 1792](preview.png)

> Ingolstadt, November 1792. One in the morning. Rain on the attic panes, the candle nearly burnt out. Victor Frankenstein has built everything he can. All that's left is a spark of being. AI and Omarchy put the laboratory in our hands. So build. Experiment.

An Omarchy theme in plum night, moonlit lavender and candle amber, sampled from the painting.

**Background intros.** The attic opens with rain running down the panes while the candle and lamp settle. The Fire opens at night on the beggars' embers: the wet branches dry and catch, and the fire gives light as well as heat. Montanvert is the evening the creature leaves, when "the sun was upon the verge of the horizon": the peaks deepen into alpenglow, the glacier sinks into dusk, and smoke rises from the hut. London arrives "on a clear morning": the low sun reaches the steeples, the domes and the treetops first, and warms the city out of the dawn shade. Midnight Sun acts out Walton's "the sun is for ever visible, its broad disk just skirting the horizon": the sun never leaves the sky, it burns from deep red to gold, and the gold comes back across the water and the ice. Out of chaos acts out its quote: the first line surfaces from the dark, then the second is built from single bits flying in from every direction, and the words are given a spark of being. Omarchy plays a background's intro at login and when you switch to the theme, once background intros reach a release (they're in Omarchy's development branch now).

https://github.com/user-attachments/assets/dcdc6712-cac7-4054-b486-2d8360d4bdbf

https://github.com/user-attachments/assets/449aa755-af8a-4bfc-9b3b-f56d8bbcba74

## Backgrounds

Numbered in the order the story happens. Click a picture for the full 5504×3072 wallpaper.

[![Victor Frankenstein in his attic laboratory at night, rain on the window, Ingolstadt beyond](thumbnails/1-ingolstadt-1792.webp)](backgrounds/1-ingolstadt-1792.webp)

**1 · Ingolstadt, 1792.** November, one in the morning. Moments before the creature opens its eye. It will wake up good; whether Victor stays or runs is still his to choose. Every time we build something now, we stand in this room.

[![A small fire under bare oaks at winter dusk, wet branches drying beside it, a crescent moon above](thumbnails/2-the-fire-1792.webp)](backgrounds/2-the-fire-1792.webp)

**2 · The Fire, 1792.** Winter, a few weeks after the creature woke, in "the forest near Ingolstadt". He found a fire left by "wandering beggars", burnt his hand in it, and wondered "that the same cause should produce such opposite effects". Then he worked it out: he dried wet branches by the heat, kept it alive through the night, and found "that the fire gave light as well as heat." There's no one in the picture. You're the creature, standing at the edge of the trees. A dangerous new power, learned and tended. Build.

[![Sunset alpenglow over the Mer de Glace, a lit hut on the slope](thumbnails/3-montanvert-1794.webp)](backgrounds/3-montanvert-1794.webp)

**3 · Montanvert, 1794.** August, sunset over the Mer de Glace, the "sea of ice" that gave Victor "a sublime ecstasy that gave wings to the soul". In the hut on the mountain, by the creature's fire, Victor has heard his creation out and says yes: "I consent." The creature's answer: "Depart to your home and commence your labours." Find him on the ice, and the light in the hut. Then build.

[![London and St Paul's from Greenwich Park, ships on the Thames](thumbnails/4-london-1794.webp)](backgrounds/4-london-1794.webp)

**4 · London, 1794.** A clear autumn morning, from Greenwich Park. Victor and Clerval sail up the Thames past Greenwich, and "at length we saw the numerous steeples of London, St. Paul's towering above all." Victor has come for "the most distinguished natural philosophers"; Clerval for "the men of genius and talent who flourished at this time." Find their ship on the river. The best minds used to be a voyage away. With AI, they're a question away. Learn, then build.

[![A low sun over Arctic pack ice, a ship far off](thumbnails/5-midnight-sun-1797.webp)](backgrounds/5-midnight-sun-1797.webp)

**5 · Midnight Sun, 1797.** July, "a very high latitude", where "the sun is for ever visible". Robert Walton drives north through the drifting ice toward the pole, the voyage that frames the whole novel. "Success shall crown my endeavours." "What can stop the determined heart and resolved will of man?" With AI, nothing. Build.

<table><tr>
<td width="33%"><a href="backgrounds/6-out-of-chaos.webp"><img src="thumbnails/6-out-of-chaos.webp" alt="Pixel text: Not out of void, but out of chaos"></a></td>
<td width="33%"><a href="backgrounds/7-omarchy.webp"><img src="thumbnails/7-omarchy.webp" alt="The Omarchy wordmark"></a></td>
<td width="33%"><a href="backgrounds/8-omarchy-logo.webp"><img src="thumbnails/8-omarchy-logo.webp" alt="The Omarchy logo"></a></td>
</tr></table>

**6 · Out of chaos.** Mary Shelley, 1831: invention "does not consist in creating out of void, but out of chaos." AI is the same: something new, made from everything we've already made.

**7 · Omarchy** and **8 · The symbol.** The Omarchy wordmark and logo in the theme's colours, drawn from the official pixel grid.

## Install

```bash
omarchy-theme-install https://github.com/nathankramm/omarchy-ingolstadt-1792-theme
```

Or Omarchy menu → Install → Style → Theme, then paste the same URL. Works on Omarchy 4, and on 3.4 or later.

**Boot screen.** Choose Ingolstadt 1792 under Style → Unlock for the OMARCHY wordmark in candle gold (Omarchy 3.7 or later).

**Screensaver.** *OMARCHY; or, The Modern Prometheus*, after the 1818 title page, drawn in the Omarchy logo font. It's optional. To use it:

```bash
cp ~/.config/omarchy/themes/ingolstadt-1792/branding/screensaver.txt ~/.config/omarchy/branding/screensaver.txt
```

It uses newer block characters that Foot (Omarchy's default), Ghostty and Kitty draw. On Alacritty, copy `screensaver-classic.txt` instead. Style → Screensaver → Restore Default brings back the Omarchy logo.

## Palette

| Role | Hex |
| --- | --- |
| Background | `#1c1226` |
| Dark background | `#160e1e` |
| Darker background | `#100a16` |
| Lighter background | `#2a1d3a` |
| Foreground | `#cbbfe8` |
| Accent | `#a78bfa` |
| Selection | `#3a2856` |
| Muted | `#584a7c` |
| Candle amber | `#f0b45e` |

Full palette in [`colors.toml`](colors.toml). Icons are `Yaru-purple`; Chrome gets near-stock greys (`#161518`).

## Credit

The five scenes are AI-generated (Grok Imagine, Nano Banana Pro), directed by Nathan Kramm. 6, 7 and 8 are drawn in code.

Every quotation is Mary Shelley's own: the 1818 novel, her 1831 revision and her 1831 introduction. The novel dates its letters only "17—", so the years are reconstructed from the story.

Midnight Sun is painted over a public-domain NOAA photograph (NOAA Photo Library, pl23arct0259, Beaufort Sea, 2008).

Montanvert is painted over a public-domain photograph of the Mer de Glace from Montanvert, 1863–65 (Rijksmuseum, RP-F-F80196).

London is painted over a public-domain watercolour, *The Thames at Greenwich*, after John Robert Cozens (composition 1792; Victoria and Albert Museum, P.28-1934).

*"And now, once again, I bid my hideous progeny go forth and prosper."* — Mary Shelley, 1831
