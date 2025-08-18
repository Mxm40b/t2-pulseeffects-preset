# T2 MacBook Pro PulseEffects Preset

This preset for the PulseEffects app enhances speaker quality for T2 Linux users. 

It has been tested on a MacBook Pro 16 inch 2019 running NixOS, but it should be compatible with any other pulseaudio-based platform.

## Installation

1. Install [PulseEffects](https://github.com/mikhailnov/pulseeffects)

2. Download the [mbp-pulseeffects.json](mbp-pulseeffects.json) file.

3. Open PulseEffects. Click on the left-most button in the top-right corner, then on `Import Presets` (file icon), and navigate to the downloaded `mbp-pulseeffects.json` file.

Optionally, you can enable PulseEffects on startup:

4. Click on the three dots in the top right corner, go to the `General` section.

5. Enable the `Launch Service at System Startup` option, `Process All Outputs`

6. You can set the `Priority Type` to Real Time if you notice stuttering when playing sound.

7. Enjoy!

Note: if you want more accurate, stereo sound from the speakers, disable the Stereo Tools effect.

## Licence

This project is under the GPL3 license. Read the [LICENSE](LICENSE.md) for more.

## Contribution

Feel free to contribute to this project.

---

This preset is based on [angelobdev](https://github.com/angelobdev)'s [EasyEffects preset](https://github.com/angelobdev/t2-easyeffects-preset/blob/main).
