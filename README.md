# Executable Crac

This is the autoexec that I personally use on CS2. I've designed it to be modular for easy setup and updates.

## Features

- Layered keys (+-alt, +-ctrl)  
- Mute toggle  
- 3-way voice switch (On, quiet, off)  
- Local practice script (prac in console when on local game)
- Chat console aliases (shrug, wave, etc)

## Installation

1) Download the latest release from the [release tab](https://github.com/ToxiWoxi/ExecutableCrac/releases) OR clone this repository.
2) Install into a config folder. Leave all files in their folders!
   - This can be either a user cfg folder (ex: `Steam\userdata\374320225\730\local\cfg`) or the CS2 cfg folder (`<SteamGamesFolder>\Counter-Strike Global Offensive\game\csgo\cfg`).
3) Add `+exec autoexec` to your launch options.
   - If you have more autoexecs that you run, add them to `autoexec.cfg`
4) Edit `ExecutableCrac/Settings.cfg`.
   - For help with internet settings, look at `ExecutableCrac/Modules/Internet.cfg`.
5) (optional) if you want to use layered keys, edit the files in `ExecutableCrac/Custom/LayeredKeys`.
   - I've provided examples (`+example` and `-example`) to show how it works.

## Folder Structure

```txt
/ <root cfg folder>
├── autoexec.cfg
└── /ExecutableCrac
    ├── /Custom
    │   ├── /LayerKeys
    │   │   ├── +Example
    │   │   ├── -Example
    │   │   ├── +Alt.cfg
    │   │   ├── -Alt.cfg
    │   │   ├── +Ctrl.cfg
    │   │   └── -Ctrl.cfg
    │   ├── LayerKeys.cfg
    │   └── ChatAliases.cfg
    ├── /Info
    │   ├── Contributors.cfg
    │   └── Version.cfg
    ├── /Modules
    │   ├── Internet.cfg
    │   ├── LocalPractice.cfg
    │   ├── Mute.cfg
    │   └── VoiceSwitch.cfg
    ├── Aliases.cfg
    ├── Custom.cfg
    ├── Main.cfg
    ├── Modules.cfg
    ├── OnLaunch.cfg
    └── Settings.cfg
```

## Feature requests/contributions

If you want any features, open an [Issue](https://github.com/ToxiWoxi/ExecutableCrac/issues)!  
If you know how to implement them, submit a [Pull Request](https://github.com/ToxiWoxi/ExecutableCrac/pulls)!  
If you submit a PR, add yourself to the Contributors list in `ExecutableCrac/Info/Contributors.cfg` with your cs or github username; whichever you prefer along with a brief description of what you added/fixed.

- example: `Sum1 - Made potatoinator script"`
