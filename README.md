# ScummVM Game Icons

This repository contains high-resolution icons of [ScummVM-compatible games](https://www.scummvm.org/compatibility/) that can be used with [integrations](https://wiki.scummvm.org/index.php?title=User_Manual/Appendix:_Integrations) like Discord or plain old desktop shortcuts.

## Contributing

Check the [Table of Contents](TOC.md) to see what icons we're missing. This covers every stable ScummVM game, so prioritize mainstream titles over minor fan games and tech demos.

To send us your icons:

- If you're familiar with Git, use a [pull request](https://github.com/scummvm/scummvm-icons/pulls). Be sure to update the `TOC.md` accordingly.
- Otherwise just open an [issue](https://github.com/scummvm/scummvm-icons/issues) with your icons attached. Put them inside a ZIP so Github doesn't mangle the images.

Icons should follow this format:

- PNG format with alpha transparent background.
- 512x512px size.
- `<engine>-<game>.png` filename (use the IDs in the TOC).

Commits should follow this message format in order to comply with our standards:

`ICONS: Add icon for The Great Adventures of ScummVM` or  
`ICONS: Update icons for The Even Greater Adventures of ScummVM`

Variants of the same game can have the same icon. For engines with lots of games (eg. Wintermute, Glk) it might be better to have a generic `<engine>.png` icon to cover all the games.
