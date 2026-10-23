# Spanglish

I use a British Mac keyboard and write in English and Spanish. Spanglish adds the accents and punctuation I need without switching layouts. There’s a US version too.

Pick **Spanglish UK** or **Spanglish US** to match your usual layout. Command and Control shortcuts stay the same.

## Install

1. Download this repo ([**Code → Download ZIP**](https://github.com/hugocornejo/spanglish/archive/refs/heads/main.zip)) and unzip it.
2. Copy `Spanglish.bundle` to `~/Library/Keyboard Layouts/`. In Finder, press **⌘⇧G** to open that path. Create the folder if it doesn’t exist.
3. Log out and back in, or restart your Mac.
4. Go to **System Settings → Keyboard → Text Input → Edit → +** and add **Spanglish UK** or **Spanglish US** (under English). Then select it from the input menu in the menu bar.

## Typing

For sequences, release the first key before pressing the next one. Option is **⌥**.

| Character | Shortcut |
| --- | --- |
| á é í ó ú | `'`, then the vowel |
| Á É Í Ó Ú | `'`, then Shift + vowel |
| ñ / Ñ | Option + N / Option + Shift + N |
| ü / Ü | Option + U / Option + Shift + U |
| ç / Ç | Option + C / Option + Shift + C |
| ¡ | Option + 1 |
| ¿ | Option + / |
| « / » | Option + backslash / Option + Shift + backslash |
| Apostrophe `'` | `'`, then Space; or `'` twice |
| Double quote `"` | Shift + `'` |

The apostrophe waits for the next character: `'e` becomes `é`, while contractions like `don't` still work. For a literal apostrophe before a vowel, use `'` then Space. The space isn’t inserted. This also works for quotes in code.

## Update or remove

To update, replace the bundle and log out and back in. To remove, switch to another layout, remove Spanglish from Input Sources, then delete the bundle and log out and back in.

## Credits and license

The base mappings come from Apple’s British and U.S. layouts. The Spanish shortcuts were inspired by [EurKEY](https://eurkey.steffen.bruentjen.eu/) by Steffen Brüntjen and [EurKEY Next](https://github.com/felixfoertsch/EurKEY-Next), maintained by Felix Förtsch, building on [Leonardo Brondani Schenkel’s macOS port](https://github.com/lbschenkel/EurKEY-Mac). Their XML files, icons and other assets aren’t included.

Licensed under [GPLv3](LICENSE) (`GPL-3.0-only`).
