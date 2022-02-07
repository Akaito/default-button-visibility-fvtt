<!-- Foundry compatibility info., and module popularity -->
![Foundry Minimum Core Version](https://img.shields.io/badge/dynamic/json.svg?url=https%3A%2F%2Fraw.githubusercontent.com%2FAkaito%2Fdefault-button-visibility-fvtt%2Fmain%2Fmodule.json&label=Minimum%20Foundry%20Version&query=$.minimumCoreVersion&colorB=orange) ![Foundry Core Compatible Version](https://img.shields.io/badge/dynamic/json.svg?url=https%3A%2F%2Fraw.githubusercontent.com%2FAkaito%2Fdefault-button-visibility-fvtt%2Fmain%2Fmodule.json&label=Tested%20With%20Version&query=$.compatibleCoreVersion&colorB=orange) <!-- | ![All Releases Download Count](https://img.shields.io/github/downloads/Akaito/default-button-visibility-fvtt/total) ![Latest Release Download Count](https://img.shields.io/github/downloads/Akaito/default-button-visibility-fvtt/latest/module.zip) -->
<!-- Badges that help identify an old, decrepit repo. -->
![GitHub last commit (main)](https://img.shields.io/github/last-commit/Akaito/default-button-visibility-fvtt/main) ![GitHub issues](https://img.shields.io/github/issues/Akaito/default-button-visibility-fvtt) ![GitHub pull requests](https://img.shields.io/github/issues-pr/Akaito/default-button-visibility-fvtt) ![GitHub forks](https://img.shields.io/github/forks/Akaito/default-button-visibility-fvtt?style=social)

<!--- Forge Bazaar Install % Badge -->
<!--- replace <your-module-name> with the `name` in your manifest -->
<!--- ![Forge Installs](https://img.shields.io/badge/dynamic/json?label=Forge%20Installs&query=package.installs&suffix=%25&url=https%3A%2F%2Fforge-vtt.com%2Fapi%2Fbazaar%2Fpackage%2Fdefault-button-visibility-fvtt&colorB=4aa94a) -->

# Default Button Visibility

Just make default buttons easier to notice.  All this module has is a tiny bit of CSS to indicate very clearly which button in any given dialog (of Foundry's normal CSS classes) is the default one.  This is completely system-agnostic, and just affects styling of Foundry UI.

My own use case: when my players with things like a passive advantage on Wisdom saves goes to roll, they'll see which button they should probably be clicking.  Instead of muscle-memory clicking "Normal", or having to ask.  Also helps me as a GM to remember to roll Disadvantage when players apply such to the monsters.
Note that in this specific use case, the default button being set to "Advantage" is provided by midi-QOL's Effects while playing in D&D 5e.  But this default highlight will still work with any system using Foundry's normal CSS classes.

![Comparison of a Wisdom saving throw dialog without and with the Default Button Visibility module active.](https://raw.githubusercontent.com/Akaito/default-button-visibility-fvtt/main/default-button-visibility.jpg)

