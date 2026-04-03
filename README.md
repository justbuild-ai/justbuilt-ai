# Orbital Edge

Exploring edge AI applications for space infrastructure and autonomous systems.

These repositories document hands-on R&D at the intersection of embedded AI hardware, space domain awareness, and autonomous decision-making — built independently by a technical program manager working in aerospace and defense.

---

## 🛰️ Projects

### [OrbGuard](https://github.com/justbuild-ai/OrbGuard)
Autonomous orbital situational awareness and debris avoidance system. System architecture and early-stage R&D for onboard conjunction analysis, threat modeling, and collision avoidance — designed to operate without ground uplink dependency.

### [ai_hull_inspection](https://github.com/justbuild-ai/ai_hull_inspection)
Edge AI prototype for spacecraft hull damage detection. Runs YOLOv8s inference on a Hailo-8L NPU — the sensing layer that feeds into OrbGuard's situational awareness pipeline.

### [smart-mirror-hailo](https://github.com/justbuild-ai/smart-mirror-hailo)
Python-based smart mirror interface built on Raspberry Pi 5 + Hailo-8L AI HAT. Integrates real-time facial recognition using YOLOv5s, user profile management, weather data, and a touchscreen UI — built to validate edge AI inference hardware and explore on-device computer vision.

---

## 🔧 Hardware Stack

- Raspberry Pi 5 (8GB) + Hailo-8L AI HAT (26 TOPS)
- Hailo SDK v4.20.0 / hailortcli
- Python 3.11 / aarch64 Debian Bookworm

---

## 🎯 Focus Areas

- Edge AI inference on resource-constrained hardware
- Space domain awareness and orbital safety
- Autonomous systems architecture
- Applied computer vision for aerospace applications

---

*Independent R&D. Not affiliated with any spacecraft operator or government program.*
