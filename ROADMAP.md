# GAINX Development Roadmap

GAINX – Modular Gain Utility Plugin | JUCE, C++  
Licensed under BUSL-1.1 (non-commercial use only)

---

## Project Vision

GAINX is a minimalist yet advanced gain-staging plugin, designed to give audio producers intuitive and precise gain control with mid/side processing, intelligent metering, and a sleek, clear user interface.

---

## Roadmap and Milestones

### Phase 1 – Setup & Planning
- [x] GitHub repository created, set to public
- [x] BUSL-1.1 License defined and included
- [x] README created, detailed project specifications documented
- [x] Roadmap clearly outlined and published

---

### Phase 2 – Basic Plugin Implementation (v0.1.0)
- [x] JUCE project initialized (Projucer or CMake)
- [ ] Basic gain processing functionality (input/output gain control)
- [ ] Functional gain slider UI component
- [ ] Minimal, scalable graphical user interface (GUI)
- [ ] Plugin state save/load using JUCE ValueTreeState

---

### Phase 3 – Mid/Side Processing (v0.2.0)
- [ ] Mid/side gain processing toggle
- [ ] Independent mid/side gain control sliders
- [ ] Stereo linked gain mode (left/right link toggle)
- [ ] Mid/side bypass functionality

---

### Phase 4 – Intelligent Metering System (v0.3.0)
- [ ] Input/output metering implementation (peak and RMS)
- [ ] Mid/side specific metering views
- [ ] Automatic gain compensation (match gain functionality)
- [ ] Optional correlation meter (spec bonus)

---

### Phase 5 – GUI Refinement & Interaction (v0.4.0)
- [ ] Custom JUCE look-and-feel implementation
- [ ] Responsive, calibrated animated VU meter
- [ ] Parameter-specific tooltips and precise reset controls
- [ ] Preparation for future changes.

---

## Development Timeline (Estimates)

| Phase | Target Completion Date | Status      |
|-------|------------------------|-------------|
| 1     | June 2025              | Completed   |
| 2     | July 2025              | In Progress |
| 3     | August 2025            | Planned     |
| 4     | Fall 2025              | Planned     |

---

## Repository Structure

GAINX/
├── Source/               # JUCE and C++ plugin source files
├── docs/                 # UI mockups, screenshots, visual references
├── LICENSE               # BUSL-1.1 License file
├── README.md             # Project overview, features, and getting started
└── ROADMAP.md            # This roadmap file


---

## Contribution & Collaboration

Contributions are encouraged for non-commercial and non-production use.  
See the [LICENSE](./LICENSE) file for complete details regarding allowed use.
