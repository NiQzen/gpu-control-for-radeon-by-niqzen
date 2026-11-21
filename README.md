# GPU Control for Radeon for Stream Deck

![GPU Control for Radeon](images/cover.png)

See your AMD Radeon GPU's temperature, usage, power, VRAM and in-game FPS on your Stream Deck, and save Instant Replay clips with one press.

Works on every Stream Deck model with keys. On a Stream Deck +, you can also use the dials and the touch strip.

## GPU Status
Shows one GPU reading on a key or on a dial (Stream Deck +):
- Temperature and hotspot temperature
- GPU usage and power
- VRAM used, clock speed and fan speed

**Key:** press to show the next reading (or set it to do nothing). **Dial:** rotate or press to switch readings.
The ring turns orange above 85 °C. Readings your GPU doesn't report are marked *not available* and skipped.

## FPS
Shows the current frame rate of the running game with a graph of the last 30 seconds. Press the key to toggle the AMD metrics overlay. The key shows *no game* when no game is running.

## Instant Replay and Save Clip
- **Instant Replay:** turns AMD Instant Replay on or off. If Record & Stream is turned off in AMD Software, the key shows *DISABLED*.
- **Save Clip:** saves the last moments recorded by Instant Replay. The key confirms with *Saved*.

Both keys press your AMD Software hotkeys, so clips are saved where AMD Software saves them.

## Settings
- **Show** (GPU Status): the reading to show
- **Key press** (GPU Status): show the next reading, or do nothing
- **Adrenalin hotkey** (FPS, Instant Replay, Save Clip): must match the hotkey set in *AMD Software › Settings › Hotkeys*. Pre-filled with `ctrl+shift+o` (Toggle Metrics Overlay), `ctrl+shift+r` (Toggle Instant Replay) and `ctrl+shift+s` (Save Instant Replay); change them if your hotkeys differ

The top of every settings panel shows which GPU the plugin found. Click **Refresh** after installing a new driver.

## Setup
1. Install a recent **AMD Software: Adrenalin Edition** driver.
2. Drag **GPU Status** and **FPS** onto keys or dials.
3. For clips: in AMD Software, open **Record & Stream**, turn on **Instant Replay**, and check the hotkeys under **Settings › Hotkeys**. Then drag **Instant Replay** and **Save Clip** onto keys.

If a key shows *NO AMD GPU*, the plugin couldn't find an AMD Radeon GPU or the AMD driver. Install or update AMD Software and click **Refresh** in the settings panel.

## Requirements
- Windows 10 / 11, Stream Deck 6.9 or later
- An AMD Radeon graphics card or Radeon graphics in an AMD Ryzen processor, with a recent AMD Software: Adrenalin Edition driver
- Available readings depend on your GPU. Some, such as power and fan speed, are usually reported only by discrete graphics cards.

No data leaves your computer.

## Need more control?
**GPU Control Plus for Radeon** adds Anti-Lag, Radeon Chill, Image Sharpening, FPS Limit and FreeSync switches, Stream Deck + dials to fine-tune them, and display color controls.

## Release notes

### 1.0.0
- First release: GPU Status (temperature, hotspot, usage, power, VRAM, clock, fan) on keys and Stream Deck + dials, in-game FPS with a graph, Instant Replay on/off and Save Clip.

## Support
Open an issue on this page.

## License
Copyright © 2026 NiQzen. All rights reserved. Use of the plugin is governed by the end user license agreement in [LICENSE](LICENSE).

AMD, Radeon and FreeSync are trademarks of Advanced Micro Devices, Inc. This plugin is not affiliated with, sponsored or endorsed by AMD. Stream Deck and Elgato are trademarks of Corsair Memory, Inc.
