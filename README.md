# 462: Doai Station

A first-person horror game set at an abandoned mountain station in Japan. A school project. Headphones, lights off.

## Mac (Apple silicon: M1, M2, M3, M4 or newer, macOS 14 Sonoma or newer)

1. Open **Terminal** (press Cmd + Space, type `Terminal`, press Return).
2. Paste this line and press Return:

   ```
   curl -fsSL https://github.com/costoudesiason/462-game/releases/latest/download/install_mac.sh | bash
   ```

3. Wait while it downloads the game (3.5 GB). It puts **462 Doai Station** in your Applications folder and opens it.

Next time, open **462 Doai Station** from Applications or Launchpad. Paste the same line again to update.
It needs about 12 GB free while installing (4 GB once done). Intel Macs can't run it.

## Windows (10/11, 64-bit)

Get `Setup.exe` from the [newest release](https://github.com/costoudesiason/462-game/releases/latest/download/Setup.exe) and run it. It downloads the game (3.3 GB), installs it where you choose, and puts a shortcut on your desktop. Run it again later to update.

If Windows says it protected your PC: **More info**, then **Run anyway** (the installer isn't code-signed).

This repository only holds the game's builds.


cd ~/Desktop && { sw_vers; sysctl -n machdep.cpu.brand_string; } > 462_mac_info.txt; zip -qj 462_crash.zip 462_mac_info.txt ~/Library/Logs/Doai462/*.log $(ls -t ~/Library/Logs/DiagnosticReports/Doai462* 2>/dev/null | head -2) && rm 462_mac_info.txt && echo "Saved 462_crash.zip on the Desktop"
