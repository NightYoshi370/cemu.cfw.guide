## Game Profiles

1. Open the Cemu main menu
1. Right click on your game(s) and click `Edit game profile`
1. Set "Mode" to:
  - If you use a CPU with 6 logical processors or higher, set to `Triplecore-recompiler`
  - For a CPU with 4 logical processors, set to `Dualcore-recompiler`
  - for a CPU with 2 logical processors, set to `Singlecore-recompiler`

Using triple or dualcore recompiler can cause some games to crash. If a game stops working because of this, try at a lower setting.

![]({{ "/assets/images/cemu-game-profile.png" | absolute_url }})

## GPU Settings

1. Open NVIDIA Control Panel
  - You can access this by right clicking on your Desktop
1. Make sure you are on the `Manage 3D Settings` section
  - This is the default section when opening the control panel
1. Go to the `Program Settings` tab
1. In "1. Select a program to customise" click `Add` -> `Browse`
1. Navigate to your Cemu folder and select the Cemu executable
1. If you are on a laptop with dual graphics, under "2. select the preferred graphics processor for this program" select `High-performance NVIDIA processor`
1. Under `OpenGL rendering GPU` select your main graphics processor
1. Under `Power management` select `Prefer maximum performance`
1. Enable the `Threaded optimization` option
1. If you have a compatible display, enable G-Sync

![]({{ "/assets/images/nvidia-gpu-settings.png" | absolute_url }})

## Cemu Settings

1. Open the Cemu main menu
1. Click `Options` -> `General settings` on the top bar

    ---

3. Navigate to the `Graphics` tab
1. Change the `Graphics API` to `OpenGL`
  - This can cause stuttering when playing for the first time, but will go away after time
1. Ensure that `Graphics Device` is correct and using your most powerful card in the case of devices with dual graphics
1. Set `VSync` to triple buffering

    ---

7. Navigate to the `Audio` tab
1. Under `General`, change `API` to `XAudio2`
