{
    "$schema": "https://raw.githubusercontent.com/atampy25/simple-mod-framework/main/Mod%20Manager/src/lib/manifest-schema.json",
    "version": "0.3.4",
    "id": "Tumbler.Cameratweaks",
    "name": "Camera Overhaul",
    "description": "An overhaul for both cameras, providing improved functionality, new options, and customizable controls for a better experience. Default enabled options are recommended.",
    "authors": [
        "Tumbler",
        "Atampy26",
        "invalid",
        "Notex"
    ],
    "frameworkVersion": "2.22.1",
    "contentFolders": [],
    "options": [
        {
            "name": "I agree!",
            "tooltip": "Options in each 'group' may apply to the regular or suspect camera. Read each description carefully to understand possible issues when selecting. This checkbox does not perform any action.",
            "type": "checkbox",
            "enabledByDefault": false
        },
        {
            "name": "I failed to understand",
            "tooltip": "If you're unsure of an option's function, it's recommended to uninstall and reinstall the mod. Do not enable options unless you understand their use.",
            "image": "thepics/deathanim.gif",
            "type": "checkbox",
            "enabledByDefault": false
        },
        {
            "name": "Fix - Stay low!",
            "tooltip": "Prevents Agent 47 from standing up when using the suspect camera and allows crouching. Note: The crouch button doubles as the 'Prime tag' button. Enable 'Switch Prime set button' to adjust this.",
            "type": "checkbox",
            "enabledByDefault": true,
            "image": "thepics/staylow.gif",
            "contentFolders": ["Fix/staylow"]
        },
        {
            "name": "Fix - Correct Camera Positioning",
            "tooltip": "Aligns the camera based on Agent 47’s stance, enhancing immersion.",
            "type": "checkbox",
            "enabledByDefault": true,
            "contentFolders": ["Fix/dynamicpositioning"]
        },
        {
            "name": "Functions - Instinct in Normal Camera",
            "tooltip": "Adds instinct mode to the normal camera, mirroring the suspect camera’s ability.",
            "type": "checkbox",
            "enabledByDefault": true,
            "image": "thepics/instinctnormalcamera.gif",
            "contentFolders": ["Functions/normalcaminstinct"]
        },
        {
            "name": "Functions - Disable Distance-based Tagging",
            "tooltip": "[Recommended] Removes the distance limit for suspect tagging, allowing tagging from any range. Credits to Notex.",
            "type": "checkbox",
            "image": "thepics/distancetagging.gif",
            "enabledByDefault": true,
            "contentFolders": ["Functions/spycamnoproxy"]
        },
        {
            "name": "Functions - Reset Zoom on Exit",
            "tooltip": "Resets the zoom slider to 1x when leaving the normal camera view. Designed to work with Atampy26’s Enhanced Camera Zoom mod.",
            "type": "checkbox",
            "image": "thepics/zoomreset.gif",
            "enabledByDefault": true,
            "contentFolders": ["Functions/Resetonexit"]
        },
        {
            "name": "Functions - Disable Suspect Reset Zoom",
            "tooltip": "[Not Recommended] Retains the current zoom level when switching in and out of aiming mode with the suspect camera.",
            "type": "checkbox",
            "image": "thepics/noresetzoom.gif",
            "enabledByDefault": false,
            "contentFolders": ["Functions/Disablereset"]
        },
        {
            "group": "Scroll to Zoom",
            "name": "Scroll to Zoom",
            "tooltip": "Enables zooming with the mouse scroll for both cameras. Note: This replaces up/down and left/right controls. Z/W and X will now control navigation. Adjust for your keyboard layout.",
            "type": "select",
            "enabledByDefault": false,
            "image": "thepics/fastscrolltozoom.gif",
            "contentFolders": ["Inputs/scrolltozoom"]
        },
        {
            "group": "Scroll to Zoom",
            "name": "Read about The Navigation Issue",
            "tooltip": "This zoom solution may impact navigation in photo mode by swapping Up/Down and Left/Right inputs. Additional information is available in the mod's README. This checkbox is informational only.",
            "type": "select",
            "enabledByDefault": false,
            "contentFolders": []
        },
        {
            "group": "Scroll to Zoom",
            "name": "Input - Navigate Up/Down",
            "tooltip": "'Up' will use the Camera Shoulder Swap (default: Mouse Button 4) and 'Down' will use Inventory (default: Mouse Button 5). Set these in-game.",
            "type": "select",
            "enabledByDefault": false,
            "contentFolders": ["zscrolltozoompatch"]
        },
        {
            "name": "Input - Switch Prime set button",
            "tooltip": "Switches the 'Prime tag' button from crouch to melee (default: A or Q) so crouching doesn’t tag suspects.",
            "type": "checkbox",
            "enabledByDefault": false,
            "image": "thepics/from C to A or Q.png",
            "contentFolders": ["Inputs/PrimeSetA"]
        },
        {
            "name": "Input - Muscle Memory",
            "tooltip": "Makes the viewfinder toggle button in the normal camera the same as the suspect camera's (default: E). Adjusts for similar functionality across both cameras.",
            "type": "checkbox",
            "enabledByDefault": false,
            "image": "thepics/From A to E.png",
            "contentFolders": ["Inputs/ToggleSetE"]
        },
        {
            "name": "Editing - Suspect Camera Filters",
            "tooltip": "Adds filter options from the normal camera to the suspect camera.",
            "type": "checkbox",
            "enabledByDefault": false,
            "image": "thepics/Filterrgb.gif",
            "contentFolders": ["Editing/spyfilters"]
        },
        {
            "name": "Editing - Suspect Camera DOF",
            "tooltip": "Adds a Depth of Field slider to the suspect camera, similar to the normal camera.",
            "type": "checkbox",
            "enabledByDefault": false,
            "image": "thepics/DOFsingleshowcase.gif",
            "contentFolders": ["Editing/spyfuzzy"]
        },
        {
            "name": "Editing - Remove Normal Camera Filters",
            "tooltip": "Removes filter options from the normal camera.",
            "type": "checkbox",
            "enabledByDefault": false,
            "contentFolders": ["Editing/RemoveFilters"]
        },
        {
            "name": "Editing - Remove Normal Camera DOF",
            "tooltip": "Removes the Depth of Field slider from the normal camera.",
            "type": "checkbox",
            "enabledByDefault": false,
            "contentFolders": ["Editing/RemoveDOF"]
        },
        {
            "name": "UI - Disable Cripple Camera HUD",
            "tooltip": "[Recommended] Disables the large USE CAMERA button when holding a camera. Credits to -invalid-.",
            "type": "checkbox",
            "enabledByDefault": true,
            "image": "thepics/nocripplehud.gif",
            "contentFolders": ["UI/noUsecamerahud"]
        },
        {
            "name": "UI - Clutter Off",
            "tooltip": "Toggles off the suspect camera's viewfinder for a cleaner display.",
            "type": "checkbox",
            "image": "thepics/alwaystoggledisplay.gif",
            "enabledByDefault": false,
            "contentFolders": ["UI/noviewfinder"]
        },
        {
            "name": "UI - UI Off",
            "tooltip": "Allows toggling off the normal camera's UI anytime.",
            "type": "checkbox",
            "image": "thepics/alwaystoggledisplay.gif",
            "enabledByDefault": false,
            "contentFolders": ["UI/noUsecamerahud"]
        },
        {
            "name": "UI - Clear The Grid",
            "tooltip": "Removes grid lines from the spy camera for better visibility.",
            "type": "checkbox",
            "enabledByDefault": false,
            "image": "thepics/cleangrid.gif",
            "contentFolders": ["UI/clearcam"]
        },
        {
            "name": "UI - Self Cleaning UI",
            "tooltip": "Dynamically hides UI elements like zoom or DOF that are not available in certain modes.",
            "type": "checkbox",
            "enabledByDefault": false,
            "image": "thepics/smartui.gif",
            "contentFolders": ["UI/cleanstatic"]
        },
        {
            "name": "Running Camera-Man",
            "tooltip": "Allows running while using the camera in aiming mode.",
            "type": "checkbox",
            "enabledByDefault": false,
            "contentFolders": ["Bonus/running47"]
        },
        {
            "name": "Showdown Sportsman",
            "tooltip": "Allows running with the suspect camera in aiming mode.",
            "type
