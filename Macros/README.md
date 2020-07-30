# All about macros

Most of these macros are intended to be used as Abilities on the Character Sheets. You click on the 'Attributes & Abilities' tab, then click the '+ Add' button to the right of Abilities. Enter in the file name as the title (minus the file extension) and then paste the file contents into the text area.

I am doing my best to insure that these macros are creature agnostic. That is, any character or NPC that has the ability in the file should be able to use it with no changes. When there have to be modifications, it will be documented.

The macros do rely on the Global Modifiers. As an example, if a character has been Blessed, there should be a Global Attack Modifier set up on their character sheet to add the 1d4 from Bless and it should be checked. When these macros make their rolls, they call out to the system to get any active modifiers, assuming that if they are active then they would apply.

I am working on setting up Hunter's Mark, Hex, and Hexblade's Curse to use their own system that automatically marks the target with a status marker and will only apply the additional damage to a properly marked creature.

These macros also assume that Normal/Advantage/Disadvantage is set to Toggle on the character sheet, and that the macro user has properly set their roll mode.
