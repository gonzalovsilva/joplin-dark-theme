# How my [Joplin](https://joplinapp.org/) looks like

Based on the dark theme from [@xplosionmind](https://github.com/xplosionmind/joplin-theme)

Modified to look more like the [One Dark Pro](https://github.com/Binaryify/OneDark-Pro) on vscode.
Took some inspiration on the PHPStorm [Nord](https://www.nordtheme.com/ports/jetbrains) theme.

- Added margins to the editor
- Add custom headers (with 1 color per header)
- Custom notes separator
- Better reading experience (subjective)
- fixed note links contrast with new modern icon
- responsive multi-column markdown render
- 2-column export for pdf

## Todo

- [ ] Clean CSS


## Installation

`userchrome.css` is used to style the entire app, `userstyle.css` is used to style the parsed markdown, instead.

In order to use these stylesheets, place them in `~/.config/joplin-desktop/` on linux, and in `%userprofile%\.config\joplin-desktop\` on windows.

## What it looks like

[![youtube video demo](https://img.youtube.com/vi/f7V8PbmumOY/0.jpg)](https://www.youtube.com/watch?v=f7V8PbmumOY)


![how_my_joplin_looks_like.gif](./_resources/3ff4c2509d9c4095996bc6db57c004c9.gif)

![side_by_side_note_taking_joplin.gif](./_resources/5e0aa07405f84903ac89881f1663bf93.gif)

## Responsive markdown render

![responsive-demo.gif](./_resources/responsive-demo.gif)

## How to enable those header styles (h1 to h6)

If you want to use those, don't forget to enable the rich markdown plugin and check this option bellow :

![Rich Markdown plugin option to check](_resources/additional_cc_classes.png)

## PDF 2-column example (for grayscale printing)

![pdf-grayscale-demo](_resources/pdf-grayscale-example.png)