# Camera Upgrades Mod

## Overview:

**Camera Upgrades** is a mod for _Hitman WOA_ that overhauls both the regular and suspect cameras, adding new features and fixes to enhance gameplay. This mod gives players more control over camera behavior and includes helpful customization options for different playstyles.

---

## Installation Instructions:

1. **Download** the mod from the [GitHub Releases](https://github.com/NeetBux-Hash/Tumbler.CameraUpgrades/releases).
2. Open **Simple Mod Framework (SMF)** and click **Add a Mod**.
3. **Enable** the mod in SMF, then click **Deploy**.

---

## Key Considerations:

### Keyboard Layouts:

This mod uses default keybinds for many features. Depending on your keyboard layout (QWERTY, AZERTY, Chinese, etc.), the keys for certain actions may differ. For instance, options listed as **"A/Q"** refer to the key next to your walk forward button, usually **W or Z** depending on your keyboard layout.

Be sure to double check your keybindings in the game settings if something is off, as the options are configured to swap default inputs and may affect how the mod interacts with your custom keybindings. (But who changes E to open door, really?)

---

### Clarificated Notes on Keybindings:

### How Hitman Handles Inputs:

_Hitman WOA_ uses internal references like **eGameInputActions** for key inputs, which are mapped to actions rather than specific keys. For example:

-   **eGameInputCrouch**: The default action for crouching (usually mapped to "C").
-   **eGameInputCloseCombatChoke**: The action for melee attacks, often mapped to "A" or "Q" depending on your layout.
-   **eGameInputActionPerform**: Typically assigned to the "use" action (commonly "E").

The mod modifies these internal actions, but the potential issue occurs if you’ve changed the keybindings for these actions in your game settings.

### Example:

In this mod, the **Prime Tag** option changes the action in the game files from **eGameInputCrouch** (default crouch action) to **eGameInputCloseCombatChoke (A/Q)** (default melee action). If you’ve remapped **eGameInputCloseCombatChoke (default A/Q)** to a different key in your keybindings, this mod might not function as expected. However, if you’re using the **default keybindings**, the mod should work without issue.

---

## Mod Options and Features:

### General:

-   **I agree!**  
     This option doesn’t affect gameplay but is a reminder that you understand the mod's input changes. Checking this confirms you’ve read through everything.

-   **I failed to understand**  
     If you're confused by the options and made some changes that produced undesirable outcomes in the game, this suggests uninstalling and reinstalling the mod to reset any changed settings you made back to the default enabled options which don't turn on those options by default when installing the mod. It has no impact on gameplay but serves as a warning not to enable settings you don't fully understand.

---

### Fixes:

-   **Stay low!**  
     Prevents Agent 47 from standing up when using the suspect camera and allows crouching while using it. Best in used in combination with any of the **Prime set button** options

-   **Zoom slider on top**  
     Moves the zoom slider to the top of the photo mode menu. This works well with Anthony Fuller’s **Selfie Mode Mod**.

-   **Proper flash in picture mode**  
     Prevents the flash from fading completely, enhancing visibility in dark environments like the Berlin club mission.

---

### Camera Functions:

-   **Instinct in Normal Camera**  
     Adds **Instinct Mode** to the normal camera, allowing you to highlight targets and items while using it.

-   **Disable Proximity-based Tagging**  
     Removes the distance restriction on suspect tagging, letting you tag suspects from any distance.

-   **Reset Zoom on Exit**  
     Automatically resets the zoom level to 1x when exiting the normal camera, ensuring consistent behavior.

-   **Disable Suspect Reset Zoom**  
     Keeps your zoom level when exiting and re-entering the suspect camera's aiming mode.

-   **Disable Proximity-based Intel Scanning**
    This option removes the distance limit for intel scanning, allowing you to scan intel to unlock safes from any distance. Be aware that the visual effect may become buggy if multiple pieces of intel are within view, but this also means you can scan several intel items at once.



---

Let me know if you'd like to adjust the wording or add more detail!


---

### Input Settings:

-   **Scroll to Zoom**  
     Enables zooming with the mouse scroll wheel. However, this will swap the up/down and left/right controls, which may affect your photo menu navigation. Depending on your keyboard layout and default button bindings, **Z/W** and **X** keys will be used to go up or down instead. A fix for this is planned which will use your mouse's side buttons.

---

### Group Selections:

#### Prime Set Button (For Suspect Tagging):

This group lets you customize the **Prime Tag** button, which by default is set to **Crouch (C)**.

-   **Off**  
     Leaves the **Crouch (C)** button as the **Prime Set** button.
-   **Switch to A/Q**  
     Changes the **Prime Tag** action to the **Melee button (A/Q)**, depending on your keyboard layout. This prevents accidental suspect tagging while crouching.

-   **Switch to E**  
     Maps the **Prime Tag** function to the **Use button (E)** for easier access near the movement keys.

---

#### Viewfinder/Hide Menu Button (Toggle):

This group controls the buttons for toggling the viewfinder in photo mode.

-   **Off**  
     Keeps the default settings: **Melee button (A/Q)** for the normal camera and **Use button (E)** for the suspect camera.
-   **Normal camera to E**  
     Moves the **Hide Menu** button for the normal camera to the **Use button (E)**, matching the suspect camera.

-   **Suspect camera to A/Q**  
     Sets the **Viewfinder Toggle** for the suspect camera to **Melee button (A/Q)**, matching the normal camera's default button to hide UI instead.

---

### Suspect Camera Zoom:

These options modify the suspect camera’s zoom behavior.

-   **Doesn’t touch any zoom options**  
     Leaves any suspect camera zoom functionality, unchanged.
-   **Increment Steps Zoom Fix**  
     Fixes the zoom to increase in smaller 1x steps instead of jumping from 1x to 4x.

-   **10x Zoom with 1x Increment Steps**  
     Extends the zoom to 10x and allows for finer zoom control with 1x increments. This is recommended for players who want more precision AND zoom.

-   **10x Zoom but in 2x Increments**  
     Offers 10x zoom with larger 2x steps (2x, 4x, etc.), providing quicker zoom but less precision. It removes the 1x entirely for the moment untill a proper fix has been implemented.

---

### Editing Options:

-   **Suspect Camera Filters**  
     Adds the normal camera’s picture editing options to the suspect camera for applying visual effects.

-   **Suspect Camera DOF (Depth of Field)**  
     Adds a DOF slider to the suspect camera, giving you more focus control.

-   **Remove Normal Camera Filters/DOF**  
     Removes filter and DOF options from the normal camera if you don’t want or need them.

---

### UI Enhancements:

-   **Disable Cripple Camera HUD**  
     Removes the large “USE CAMERA” prompt from the HUD, decluttering the interface.

-   **Clutter Off**  
     Makes you able to toggle off the camera UI at any time instead of just when you're in picture mode.

-   **Clear the Grid**  
     Removes gridlines from the suspect camera, improving visibility.

-   **Self Cleaning UI**  
     Dynamically hides UI elements that are irrelevant to your current camera mode (like zoom or DOF).

---

## Troubleshooting:

For questions or issues, join the [**Glacier Modding Discord**](https://discord.gg/6UDtuYhZP6). Additionally, new mod releases are automatically displayed in SMF, from where you can download them.

---

[Install](https://hitman-resources.netlify.app/smf-install-link/https://github.com/NeetBux-Hash/Tumbler.CameraUpgrades/releases/latest/download/mod.framework.zip) | [Download](https://github.com/NeetBux-Hash/Tumbler.CameraUpgrades/releases/latest/download/mod.framework.zip)

---

`Tumbler.CameraUpgrades` by Tumbler, Atampy26, invalid, Notex, Sierra Knox, and Lux Manifestus.

---

Let me know if you'd like to make further adjustments or more clarfications to this 'Read me' page!
