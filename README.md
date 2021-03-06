# DISCLAIMER
I no longer use this, so it's possible it won't work anymore

# Bar

Bar is an  [Übersicht](https://github.com/felixhageloh/uebersicht) widget
that places a customizable bar on your desktop.

This repository is a fork from [callahanrts' job](https://github.com/callahanrts/bar) updated to meet my needs.
___
This bar probably supports only 1 monitor.

![Spotify](./screenshots/custom.png)

## Elements

- Workspace {chunkwm needed}
  - highlights currently working workspace
  - adds/removes workspaces dynamically 
- Focused window {chunkwm needed}

- Currently playing music from
  - Spotify
  - Cmus {uses 'cmus-remote'}

- Free disk space
- Free memory
- CPU usage and temperature
    - temperature depends on [osx-cpu-temp](https://github.com/lavoiesl/osx-cpu-temp)
- Wi-Fi
- Battery
  - added icon when plugged
  - changes color depending on percentage 
- Date/Time


## Installation

1. Download (or clone) this repository and place the folder in your Übersicht widgets directory.
2. Copy `script` folder to `~/scripts/uber/`

## Configuration

Open [index.jsx](https://github.com/samurajhais/bar/blob/master/index.jsx)
and edit as you'd like. Some of the objects toward the top should make
customization a little easier.

Elements itself are located in `src` folder.

Scripts located in `script` folder are loaded from custom `~/scripts/uber/` folder. Read files very carefully if you are trying to rebuild this thing. Debug console is your best friend. 

## Questions?

If you find a bug or have any questions about Bar, [submit an issue](https://github.com/samurajhais/bar/issues/new).

