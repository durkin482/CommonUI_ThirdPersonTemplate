This is just an extension of the default third person template. It uses C++ to extend the CommonActivatableWidget class, allowing Enhanced Input to work with Common UI (it's the only thing done in C++)

Everything in blueprint is commented thoroughly and in lamen terms so don't be offended if comments overexplain or are too simple

The template also adds:
 - BP_PlayerController - Holds the logic for opening and closing the generic tab menu, as well as the default scripts found in BP_ThirdPersonCharacter
 - BP_PlayerState - there's no logic in this blueprint, but it's nice to have in a template
 - A bunch of Common UI stuff already setup (Base widget with 4 stacks, button styles, text styles, universal back action, QOL settings menu)
 - Organized file structure (with colors :))
 - Updated GameMode that uses aforementioned blueprint classes

The third person movement, input, and camera scripts have been moved to the player controller. 
All third person template files are inside the ThirdPersonTemplate folder.
