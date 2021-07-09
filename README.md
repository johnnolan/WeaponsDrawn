![](https://img.shields.io/badge/Foundry-v0.8.8-informational)
![Latest Release Download Count](https://img.shields.io/github/downloads/johnnolan/WeaponsDrawn/latest/module.zip)

# Weapons Drawn

A visual utility plugin, which allows characters to have a secondary token image which is automatically swapped to when in combat.

## !!! THIS IS A FORKED VERSION OF THE EXCELLENT WORK DONE BY VanirDev !!!

This is for personal use and is not supported for others at the moment. I do not want to release this and promote it as that would be disrepectful to the original developer.

When/if they decide to update their code base I shall archive this one.

If you do wish to use this, you can install it by adding the following install file to get the latest version.

[https://github.com/johnnolan/WeaponsDrawn/releases/latest/download/module.json](https://github.com/johnnolan/WeaponsDrawn/releases/latest/download/module.json)

## Update Changelogs

<details>
  <summary>Click to Expand</summary>
  
  ### Release 0.2 - Compatability and Bug Fixing
  * Removed support for WD icons in the combat tracker due to inconsistent permissions needed to change them.
  * Removed unnecessary dependencies on the dnd5e system. Weapons Drawn is now likely compatible with any system that doesn't alter the token system!

  ### Release 0.1
  
  * Initial release, allowing for per-actor configuration of tokens, with a per-actor toggle for WD tokens.
</details>

## Features

### Dynamic Token Switch

![](https://github.com/VanirDev/WeaponsDrawn/blob/main/assets/WeaponsDrawn.gif)

Tokens configured with this module will automatically swap their token when entering/leaving a combat state.

### Settings UI

![](https://github.com/VanirDev/WeaponsDrawn/blob/main/assets/SettingsUI.png)

Every actor now has a toggle for WD token images. When enabled, the standard token path input is replaced by two inputs, which are used for out of combat and in combat states.

##### As a disclaimer, this module currently works on a per-actor basis, regardless of whether tokens are linked to their actor. All tokens that derive from the same actor will be modified according to the WD settings, so it suggested that this primarily be used for player characters or creatures that don't need individually unique tokens if they are copied from the same base actor. This will likely be improved in a future version to remove this limitation.

## Installation

1. Open the "Add-On Modules" tab inside the FoundryVTT setup section.
2. Click "Install Module" and paste this link into the "Manifest URL" box: https://raw.githubusercontent.com/VanirDev/WeaponsDrawn/main/module.json
3. Click "Install", and once the module has finished installing enable the module in "Manage Modules" in the "Game Settings" tab.

## License

This module is licensed using the Creative Commons Attributions International License, any adaptations must provide both credit and indication of changes made.

