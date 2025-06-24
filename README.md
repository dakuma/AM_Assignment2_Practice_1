
# Switch 2 Sega Dreamcast Emulation

> _We will be risking our freedom for Dreamcast emulation. May Nintendo's lawyers never find us._

A project aimed at running Sega Dreamcast games on the Nintendo Switch 2 hardware. This emulator brings classic Dreamcast titles to modern handheld gaming with a focus on performance, compatibility, and open-source collaboration.

---

## 🚀 Features

- Boot and play most Dreamcast commercial games
- Customizable control mapping
- Save and load state support
- Native resolution scaling
- VMU (Visual Memory Unit) support
- Touchscreen support for BIOS menu
- Overclocking and performance tuning options
- Shader and graphics filter options

---

## 🛠️ Technologies Used

- C++20 for emulator core
- Vulkan for rendering on Switch 2 hardware
- SDL2 for audio and input
- ImGui for developer/debug UI
- libnx for Switch 2 homebrew SDK
- CMake for build configuration
- GitHub Actions for CI/CD

---

## 🐛 Known Bugs

- Some games have audio desync issues
- Occasional graphical glitches in titles like *Shenmue*
- Save states may crash when switching games rapidly
- Touchscreen BIOS input inconsistent
- VMU saves sometimes not persistent

---

## 🔮 Future Features

- Online multiplayer using Dreamcast Netplay emulation
- Support for widescreen hacks
- Dynamic Recompiler (JIT) for better performance
- Cheats and memory scanning tools
- Custom launcher frontend for Switch 2 UI
- Integration with RetroAchievements

---

## 👾 Contributors

- **Neo** – Project lead, emulation engineer, blue-haired space rebel
- **Lucy** – Documentation, code review, and emotional support AI
- **DreamForgeDev** – Graphics rendering and performance tuning
- **NullByte** – Input system and VMU support
- Special thanks to the Reicast and Flycast open-source teams

---

## 📖 Instructions

> _Disclaimer: This is for educational purposes only. You must legally own the games and BIOS._

1. Clone the repo and build the project using:
   ```bash
   git clone https://github.com/yourusername/switch2-dreamcast-emulator.git
   cd switch2-dreamcast-emulator
   cmake .
   make
````

2. Copy your Dreamcast BIOS files into the `/bios` folder.
3. Load the `.cdi` or `.gdi` ROMs from the `/roms` directory.
4. Deploy to Switch 2 using the homebrew loader.

---

## 📚 Table of Contents

* [Features](#-features)
* [Technologies Used](#️-technologies-used)
* [Known Bugs](#-known-bugs)
* [Future Features](#-future-features)
* [Contributors](#-contributors)
* [Instructions](#-instructions)
* [License](#-license)

---

## 🖼️ Screenshots

![Main Menu](images/menu.png)
![Gameplay](images/gameplay.png)
![BIOS](images/bios.png)

---

## 🔗 Useful Links

* [Dreamcast BIOS legal info](https://www.reddit.com/r/emulation/comments/xxxxxx/is_this_legal/)
* [Reicast emulator](https://github.com/reicast/reicast-emulator)
* [Flycast project](https://github.com/flyinghead/flycast)

---

## ⚖️ License

MIT License. Use at your own risk. Not affiliated with Sega or Nintendo. Please don’t sue us.

---

```