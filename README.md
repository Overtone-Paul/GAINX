# GAINX Modular Gain Utility Plugin

## Overview

- **Type:** VST3 / AU Plugin (Standalone optional)
- **Category:** Gain, Metering, Utility
- **Platforms:** macOS 11+, Windows 10+
- **Plugin Formats:** VST3, AU
- **Development Framework:** JUCE (May 2025+ compatible)
- **For:** Mixing engineers, mastering engineers, producers

---

## Planned Features

### Core Gain Engine

- **Input & Output Gain:** Continuous -48 dB to +48 dB
- **Trim Mode:** Bypasses makeup gain; applies static offset
- **Auto Gain Matching:** Toggleable compensation to preserve perceived loudness

### Mid/Side Gain Tools

- Independent **Mid Gain** and **Side Gain** controls
- Preserve or manipulate stereo image with full transparency
- Useful for stereo mastering, vocal isolation, width control

### Metering System

- **True VU Meter:** Calibrated to -18 dBFS = 0 VU
- **Peak Meter:** Fast attack with adjustable decay
- **RMS Overlay:** Toggleable RMS curve for dynamic context
- **Clip Indicator:** With manual reset

### Gain Match A/B

- Slot A/B toggling for comparative loudness decisions
- **Smart Match:** Loudness normalization between slots

### Mono & Phase Tools

- **Mono Sum:** Collapse stereo signal to mono
- **Phase Flip:** Flip L, R, or both channels
- **Stereo Width Display:** Visual-only stereo spread indicator

---

## Roadmap

See the full [ROADMAP.md](./ROADMAP.md) for feature milestones and progress tracking.

---

## License

This project is licensed under the **GNU Affero General Public License v3.0 (AGPLv3)**.

*Note:* This license is temporary. Once a JUCE Pro license is obtained, the project will be relicensed under the *Business Source License 1.1 (BUSL-1.1)* to allow non-commercial use with future commercial licensing options.

You may **view, fork, and contribute** to the source code for **non-commercial and non-production** purposes only.

**Commercial/production use is strictly prohibited** unless a commercial license is obtained from the author.

A future open-source license may be granted at the Licensors discretion, but no specific timeline is guaranteed.

- **GAINX Plugin Code and JUCE Framework:** AGPLv3 (see [LICENSE](./LICENSE))
- **Steinberg VST3 SDK:** GPLv3 (under Steinbergâ€™s dual-licensing model â€” see [VST3_SDK_LICENSE.md](./VST3_SDK_LICENSE.md))
