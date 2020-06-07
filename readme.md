## Greenview - A theme for Typora

A green theme to be used in [Typora](https://typora.io) editor.

Highly influenced by my preferences of green and solarized dark like color schemes. Most of the credits goes to [LostKeys](https://theme.typora.io/theme/Lostkeys/) and [Solarized](https://theme.typora.io/theme/Solarized/) themes authors. I just adjusted some colors, sizes and corner roundness.

### Installation

Based on the operating system you use, the location where to put the theme files is different. Go to Typora's `Preferences > Appearance` menu path and click `Open Theme Folder` button to find that location.

For example, on macOS the location is `/Users/{username}/Library/Application Support/abnerworks.Typora/themes`.

### Monospaced Fonts

The monopaced fonts that are configured (in this order) are:
- [Letter Gotic FS](https://www.fontspring.com/fonts/fontsite/letter-gothic-fs) Medium,
  - this is what I am currently using (installed on my macOS, so there is no need for woff files) and it is a paid one.
- [Mononoki](https://github.com/madmalik/mononoki)
  - it is included in the theme, as being free.

However, you can customize the font to be used by updating this line in `greenview.css` file:<br/>
`--monospace-font: "LetterGothicFS-Medium", "Mononoki", monospace;`

## Screenshots

As this is very visual related thing, see below some samples.

Using _Letter Gothic FS Medium_ font:
![Sample](./sample_lettergothicfs.png)

Using _Mononoki_ font:
![Sample](./sample_mononoki.png)
