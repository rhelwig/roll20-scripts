For the AC, always use bar2 instead of AC or npc_AC. This does require us to make sure that all tokens have bar2 linked to the appropriate character sheet attribute.

We have been using bar3 for HP. Others often use bar1 for HP. Because of this we want to make it easy to change the scripts and macros. For macros, doing a search/replace on bar3 is simple enough. For API scripts, a global constant should be used at the top of the file.

Most macros try to apply any damage done to the target. This is usually towards the end of the script.

If a macro applies damage to a target, it also likely checks to see if the target has been knocked unconscious. If so it applies a red X status marker.

We always use $ATK, $DMG, $CritDMG, ad $lvl

For cantrip progression replace the '1' in the 1d8 or whatever with '[[round((@{selected|level} + 1) / 6 + 0.5)]]' for damage rolls.

