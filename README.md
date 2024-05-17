This is just an extension of the default third person template. It uses C++ to extend the CommonActivatableWidget class, allowing Enhanced Input to work with Common UI (it's the only thing done in C++)

Everything in blueprint is commented thoroughly and in lamen terms so don't be offended if comments overexplain or are too simple

The template also adds:
 - BP_PlayerController - Holds the logic for opening and closing the generic tab menu, nothing more. 
 - BP_PlayerState - there's no logic in this blueprint, but it's nice to have in a template
 - A bunch of Common UI stuff already setup (Base widget with 4 stacks, generic button, basic menu logic)
 - Organized file structure (with colors :))
 - Updated GameMode that uses aforementioned blueprint classes

The third person movement and input scripts are unchanged and remain in the third person character blueprint. 
All third person template files are inside the ThirdPersonTemplate folder.
