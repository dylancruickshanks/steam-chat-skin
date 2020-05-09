![Lint](https://github.com/LaserFlash/steam-chat-skin/workflows/Lint/badge.svg?branch=master)![Deploy](https://github.com/LaserFlash/steam-chat-skin/workflows/Build%20and%20Deploy/badge.svg)

# Steam Friends / Chat Skin

Check out <https://steamchatskinning.tk> to see the skin in action.
Also provides a visual way to customise the appearance.

## Installation

### Prerequisite

**Steam Friends Patcher:** <https://github.com/PhantomGamers/SteamFriendsPatcher/releases>

This is required to apply the theme to the Steam Friends UI. Setting the patcher to run in the background will automatically patch the UI whenever Valve releases a new update for the Friends UI.

### Theme Installation

#### Manual

Copy [`friends.custom.css`](https://raw.githubusercontent.com/LaserFlash/steam-chat-skin/master/src/friends.custom.css) to `Steam/clientui`

#### Automatic

If on Windows running the installer script will automatically download and install the theme.
**Installer:** <https://github.com/LaserFlash/steam-chat-skin-installer/releases>

## Preview

![Skin Image](https://laserflash.tk/assets/images/steam.png)

## Customisation

[`friends.custom.css`](https://raw.githubusercontent.com/LaserFlash/steam-chat-skin/master/src/friends.custom.css) can be customised to apply different styles to the theme. This customisation is performed in the that file

### Theme Options:

#### Theme Colour:

- Discord Theme
- Dark Theme
- Light Theme

#### Status Styles:

- Discord status or dot status
- Border status (outline around the avatar)

#### Avatar Styles:

- Round Avatar
- Square Avatar
- Squircle Avatar

#### Visual Effects:

- Glow Effects
- Shadows
- Blur

#### Font Customisation

You can change the font used, either read the comment block in [`friends.custom.css`](https://raw.githubusercontent.com/LaserFlash/steam-chat-skin/master/src/friends.custom.css) or add something like the following:

```css
* {
  font-family: <Replace me with your font> !important;
}
```

Just make sure you either use a web safe font or one that is installed on your system

- https://www.w3schools.com/cssref/css_websafe_fonts.asp
- https://fonts.google.com/?selection.family=Big+Shoulders+Text (also a good resource, use the `@IMPORT` option)

# Contributing

Contributions of any sort are always welcome.

If you have problems or suggestions I would recommend you create an [Issue](https://github.com/LaserFlash/steam-chat-skin/issues) with a clear explanation and ideally a relevant screenshot.

#### Code

Code contributions are also welcome (less work for me). Just put in a [Merge Request](https://github.com/LaserFlash/steam-chat-skin/pulls). I'm slowly working on creating a solid project structure, but for now just be sensible with the code changes.

# Credits

- PhantomGamers <https://github.com/PhantomGamers> for their work on the patcher.
- Originally a fork of <https://github.com/AikoMidori/steam-friends-skin>
