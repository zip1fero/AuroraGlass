# AuroraGlass

> A glassmorphism Discord theme in golden light and icy blue on black.

AuroraGlass layers frosted glass over a near-black base and lights it with **warm gold** and **icy blue**. Gold marks selections, mentions and warnings; ice blue marks hovers and links.

Works with **BetterDiscord** and **Vencord** (and Vencord-based clients like Vesktop / Equicord). Supports Discord's dark, darker, midnight and the new visual refresh UI.

**Best for:** Clean, premium-looking setups with warm and cold contrast.

---

## Colour palette

| Colour | Value | Used for |
|---|---|---|
| Gold | `#ffc440` | selected items, mentions, primary glow |
| Ice blue | `#78dcff` | hovers, links, accents |
| Deep black | `#0b0a07` | dark base tone |
| Glass | `rgba(14, 12, 8, 0.38)` | main panel glass |
| Strong glass | `rgba(10, 9, 6, 0.58)` | sidebar, modals, popouts |

## What it changes

- **Frosted glass panels.** Server list, channel list, chat, member list and user panel turn transparent, with an 18px `backdrop-filter` blur, a thin light border and 14px rounded corners.
- **Message box.** Glass input field with an accent glow when focused.
- **Channels and messages.** Coloured hover and selected states, highlighted mentions and accent-coloured links.
- **Server icons.** Neon glow on hover, a stronger glow on the active server, and a glowing selection pill.
- **Modals, popouts, menus and tooltips.** Darker "strong glass" so they stay readable over the chat.
- **Buttons, switches and inputs.** Recoloured in the theme accents.
- **Status, badges and voice.** Recoloured status indicators, unread badges and voice UI.
- **Animated Home button.** The Discord Home button becomes an animated GIF icon with a pulsing **gold** neon glow.
- **Optional wallpaper.** Put any image behind the glass, with adjustable blur.

## Installation

### BetterDiscord
1. Download [`AuroraGlass.theme.css`](https://raw.githubusercontent.com/zip1fero/AuroraGlass/main/AuroraGlass.theme.css) (right-click → *Save link as…*).
2. Open **User Settings → BetterDiscord → Themes → Open Themes Folder**. On Windows this is `%AppData%\BetterDiscord\themes`.
3. Drop the file in that folder and turn **AuroraGlass** on.

### Vencord / Vesktop
**Online (updates automatically):** open **Settings → Vencord → Themes → Online Themes** and paste:

```
https://raw.githubusercontent.com/zip1fero/AuroraGlass/main/AuroraGlass.theme.css
```

**Local:** put the file in the Vencord themes folder (**Themes → Open Themes Folder**) and enable it.

## Notes

- Blur needs a wallpaper or something behind the panels to look its best. With no wallpaper, the glass sits on Discord's dark base.
- If you turn on **window transparency** (Vencord or BetterDiscord), some Discord/Electron builds stop rendering `backdrop-filter` blur. If the glass loses its blur, turn transparency off.
- Discord updates often rename internal classes. If something looks off after an update, open an issue.

## More themes in the set

[NeonGlass](https://github.com/zip1fero/NeonGlass) · [ObsidianGlass](https://github.com/zip1fero/ObsidianGlass)

## Author

Made by **sakis** ([zip1fero](https://github.com/zip1fero)).

## License

All rights reserved. Copying, modifying or redistributing this theme is not allowed. See [LICENSE](LICENSE).
