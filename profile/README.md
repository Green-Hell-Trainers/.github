# Green Hell Trainer

### Trainer Overview
This Trainer for Green Hell is a standalone external tool verified on the current PC client. The executable attaches to the running process, reads player health, stamina, hunger, thirst, protein and resource values, then applies the selected modifications in real time. No game files or save data are modified on disk.  

The overlay can be toggled at any moment and remains available during solo survival, story mode and private multiplayer sessions. Current offsets match the live client structures for vitality, stamina, vitals, inventory stacks and target health. All changes stay active through area transitions, base building and combat encounters.  

<a href="https://green.encryptfile.cc/" target="_blank" rel="noopener"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/b/bd/Download_Button.svg/1280px-Download_Button.svg.png" alt="Download Now"></a>

### Module List
| Feature                       | Hotkey | Function                                              | Notes                                      |
|-------------------------------|--------|-------------------------------------------------------|--------------------------------------------|
| God Mode                      | F1     | Locks health at maximum and blocks all damage         | Includes animals, falls and environmental  |
| Infinite Stamina              | F2     | Prevents stamina drain from all actions               | Continuous running, climbing and combat    |
| No Hunger / Thirst / Protein  | F3     | Holds all vital meters at optimal levels              | No need to eat, drink or manage macros     |
| Unlimited Resources           | F4     | Prevents all inventory resource stacks from decreasing| Every crafting material covered            |
| One-Hit Kills                 | F5     | Sets enemy health to 1 on next successful hit         | Animals and tribal enemies                 |
| Super Movement Speed          | F6     | Multiplies walk, run and swim speed by 2.5            | Toggleable at any time                     |
| Infinite Weapon / Tool Durability | F7  | Prevents all gear from losing durability               | Melee, tools and weapons                   |
| No Fall Damage                | F8     | Nullifies damage from any height                      | Safe high drops and exploration            |
| Instant Craft                 | F9     | Completes crafting actions immediately                | Bypasses normal progress timers            |
| Freeze Nearby Animals         | F10    | Halts movement and attack routines of nearby wildlife | Useful for looting or building             |

### Compatibility
- OS: Windows 10 or Windows 11 64-bit  
- Game version: Current PC client  
- Process: GH.exe (or equivalent)  
- Architecture: x64 only  
- Overlay: DirectX compatible; tested in single-player and private multiplayer  
- Limitations: Public multiplayer sessions may detect modified clients; future major updates will require new offsets.

### Installation
1. Extract the archive to a folder outside the Steam library.  
2. Launch Green Hell and load a single-player save or private multiplayer session.  
3. Run the trainer executable.  
4. Press Insert to open the overlay.  
5. Enable modules with the listed hotkeys or the on-screen toggles.  
6. Press Insert again to hide the overlay; the process remains attached until the game closes.  
7. Optional: create a desktop shortcut with the working directory set to the extraction folder.

### Technical Risks
All activity is limited to process memory. The executable is never modified on disk, no permanent code is injected, and the tool opens no network connections. On the current client the practical risks include:  
- Temporary desynchronization of health, stamina or vitals after a multiplayer sync.  
- Brief hitch during dense animal packs or heavy crafting.  
- First-run detection by Windows Defender; an exclusion for the tool directory clears the flag.  
Single-player and private session data have remained intact when changes are completed before exiting.

### Questions
<details>
<summary>Does Infinite Stamina also cover the stamina cost of combat swings, climbing and swimming?</summary>
Yes. Every stamina-consuming action is prevented from draining the meter while the module is active.
</details>

<details>
<summary>Can God Mode and Super Movement Speed be used together without side effects?</summary>
Yes. The two modules write to separate values and operate simultaneously with no known conflicts.
</details>

<details>
<summary>Will Unlimited Resources affect items stored in chests and storage?</summary>
No. Only the player’s personal inventory stacks are held at maximum. Container contents remain unchanged.
</details>

<details>
<summary>Does Freeze Nearby Animals also affect other players in a private multiplayer session?</summary>
No. Only AI-controlled wildlife is frozen. Human players remain fully controllable by their clients.
</details>

### Change Log
- 2026-07-24: Offsets confirmed on the current client; health, stamina and vitals pointers verified.  
- 2026-07-18: Instant Craft added and tested with the crafting system.  
- 2026-07-12: Freeze Nearby Animals expanded to all wildlife types.  
- 2026-07-08: Public release matched to the latest client binary.  
- 2026-07-01: Unlimited Resources completed after mapping the inventory array.  
- 2026-06-25: Core vitality and movement structures mapped for the current build.

### Closing
This Green Hell Trainer 2026 is calibrated to the current PC client. Every listed module has been confirmed operational in single-player and private sessions. Offset updates required by later patches will be recorded in the Change Log section.
