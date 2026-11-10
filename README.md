# Tidebound test builds

Newest build: **[Windows installer](https://github.com/Toms-Berzins/Tidebound-builds/releases/latest/download/Tidebound-win-Setup.exe)** · **[Linux AppImage](https://github.com/Toms-Berzins/Tidebound-builds/releases/latest/download/Tidebound.AppImage)**
(zips: [Windows](https://github.com/Toms-Berzins/Tidebound-builds/releases/latest/download/Tidebound-windows.zip) · [Linux](https://github.com/Toms-Berzins/Tidebound-builds/releases/latest/download/Tidebound-linux.zip); older builds under [Releases](https://github.com/Toms-Berzins/Tidebound-builds/releases)).

**Windows 10/11:** run `Tidebound-win-Setup.exe`. It installs for you only (no admin), adds desktop and
Start menu shortcuts, and updates itself: a newer build shows a notice in the main menu, one click to
update. Windows shows "Windows protected your PC" because the game isn't signed: click
**More info → Run anyway**. The zip runs without installing (unzip, run `Tidebound.exe`) but doesn't
update. If the game won't start, run `Tidebound.console.exe` from the zip and send a screenshot of what
it prints.

**Linux:** make `Tidebound.AppImage` executable (`chmod +x Tidebound.AppImage`) and run it; it updates
itself too.

## System requirements

Estimates: so far the game has only been tested on a GTX 1070 with a Ryzen 5 2600X. Tell us how it runs on your PC.

| | Minimum (estimate) | Tested on |
|---|---|---|
| OS | Windows 10/11 64-bit, or 64-bit Linux | Linux |
| CPU | 4 cores / 8 threads, about 2017 or newer (Ryzen 5 1600, Core i5-8400) | Ryzen 5 2600X |
| Graphics | Vulkan support, 2 GB VRAM (GTX 960 / 1050, RX 470); with Graphics: Low, any GPU with OpenGL 3.3 | GTX 1070 |
| RAM | 4 GB (8 GB recommended) | uses about 1 GB |
| Disk | about 200 MB | |

No Mac, ARM or 32-bit builds.

**Running slowly?** Open **Settings → Video** (in the main menu, or **Esc** during a voyage):
- **Resolution** to Performance, and **Anti-aliasing** lower.
- **Graphics** to **Low (OpenGL)** for older or integrated graphics, or a GPU without Vulkan. It
  uses about half the GPU time of Standard, but looks plainer: no ambient occlusion, no cloud
  shadows on the trees, paler trees and darker grass. Picked in the main menu, the game restarts
  on it at once; picked during a voyage, it applies from the next start.

**Controls:** the cursor says what a left click does there (walk, gather, fell, open, board...), so
most things are a click.
- WASD walk or sail · Shift jog · E land, dock, board, or call a castaway over
- C or a click on the camp or dock: its window · B build (shelter on a new island) · V what you carry
- F the fire by a camp, eat aboard · 1-6 your tool belt · Z mark a work area · J work areas · K known ways
- Right click or Esc lets go of what's in hand · Esc with nothing in hand: Settings and Quit · Alt shows the whole HUD for a moment
- Mouse wheel zoom · middle-drag pan · Q/R turn the view · Space re-centre · Tab game speed

**Reporting a bug:** include the "world N" number shown at the top of the screen, your graphics card,
and the newest log from `%APPDATA%\Godot\app_userdata\Tidebound\logs` (Linux:
`~/.local/share/godot/app_userdata/Tidebound/logs`).
