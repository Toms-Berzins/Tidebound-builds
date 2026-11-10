# Tidebound test builds

Newest build: **[Windows](https://github.com/Toms-Berzins/Tidebound-builds/releases/latest/download/Tidebound-windows.zip)** · **[Linux](https://github.com/Toms-Berzins/Tidebound-builds/releases/latest/download/Tidebound-linux.zip)** (older ones under [Releases](https://github.com/Toms-Berzins/Tidebound-builds/releases)).

**Windows 10/11:** unzip and run `Tidebound.exe`. Windows shows "Windows protected your PC" because the
game isn't signed: click **More info → Run anyway**. If it won't start, run `Tidebound.console.exe`
and send a screenshot of what it prints.

## System requirements

Estimates: so far the game has only been tested on a GTX 1070 with a Ryzen 5 2600X. Tell us how it runs on your PC.

| | Minimum (estimate) | Tested on |
|---|---|---|
| OS | Windows 10/11 64-bit, or 64-bit Linux | Linux |
| CPU | 4 cores / 8 threads, about 2017 or newer (Ryzen 5 1600, Core i5-8400) | Ryzen 5 2600X |
| Graphics | Vulkan support, 2 GB VRAM (GTX 960 / 1050, RX 470) | GTX 1070 |
| RAM | 4 GB (8 GB recommended) | uses about 1 GB |
| Disk | about 200 MB | |

No Mac, ARM or 32-bit builds. Running slowly? In the main menu open **Settings → Video** and set
**Resolution** to Performance and **Anti-aliasing** lower.

**Controls:** WASD sail · E land / dock / board · B dock menu at a dock · F eat · Tab game speed ·
mouse wheel zoom · right-drag pan · Q/R turn the view · Space re-centre.

**Reporting a bug:** include the "world N" number shown at the top of the screen, your graphics card,
and the newest log from `%APPDATA%\Godot\app_userdata\Tidebound\logs`.
