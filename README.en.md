# Hi, I'm Iordan 👋

[Português](README.md)

**Android developer (Kotlin + Jetpack Compose), also writing C++ on Windows.**
8 years in credit and financial products at Banco Bradesco.

I build apps that model real Brazilian credit rules (payroll loan limits, loan portability, the IOF tax, the Price
amortization table), because I work with those rules every day before writing them in code.
Outside the bank, I make the programs I use myself: a game hub, a TV player and music apps driven by a gamepad.

- 🔭 Moving into software development, focused on fintech and credit
- 🎓 Studying Computer Science at Unifacs
- 📱 Published on Google Play: [CSE, a loan calculator](https://play.google.com/store/apps/details?id=com.cse.calculadora)
- 📫 nadroi.dev@gmail.com

## Stack

![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat&logo=kotlin&logoColor=white)
![Jetpack Compose](https://img.shields.io/badge/Jetpack%20Compose-4285F4?style=flat&logo=jetpackcompose&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=flat&logo=android&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat&logo=cplusplus&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![JUnit](https://img.shields.io/badge/JUnit-25A162?style=flat&logo=junit5&logoColor=white)
![Gradle](https://img.shields.io/badge/Gradle-02303A?style=flat&logo=gradle&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

## Featured projects

### 📱 [CSE, payroll loan calculator](https://github.com/iordan21/cse-calculadora-emprestimo)

Native Android app, **published on Google Play**. It simulates loan portability, works out the available payroll
margin and projects new loans with the IOF tax deducted.

`Kotlin` `Jetpack Compose (Material 3)` `MVVM` `StateFlow` `JUnit` `Gradle KTS`

Three-layer MVVM that keeps calculation, state and UI apart, with 48 JVM tests covering the Price formulas,
Brazilian currency parsing and input sanitizing.

### 🎮 [Ranga EMU](https://github.com/iordan21/Ranga-EMU)

A game hub for Windows: 26 consoles on one screen, with player profiles, friends, chat, achievements and online play
with friends. It updates itself with signed releases (ECDSA P-256) and has its own app store with a signed catalog
([Ranga-Apps](https://github.com/iordan21/Ranga-Apps)).
Games run on open source libretro cores by other authors, and the project started as a fork of AnyPS5.
My work is what surrounds them: the interface, accounts, online rooms, store and signed updates.

`C++20` `Dear ImGui` `Direct3D 11` `SDL2` `libretro` `Cloudflare Workers`

### 📺 [Ranga TV](https://github.com/iordan21/Ranga-TV) · 🎵 [Ranga YTM and Ranga Spot](https://github.com/iordan21/Ranga-YTM)

Apps from the Ranga EMU store, made for a game controller.
**Ranga TV** plays the official streams of Brazilian free-to-air channels.
**Ranga YTM** and **Ranga Spot** open YouTube Music and Spotify in a light window, with a mini player and a
now-playing notice in the corner while you play.

`Kotlin` `Compose Multiplatform` `VLC` · `C++` `WebView2` `Win32`

### 🛠️ Others

- [ghost-lol](https://github.com/iordan21/ghost-lol): League of Legends HUD using the client's local API (PowerShell).
- [Payroll system](https://github.com/iordan21/sistema-rh-pagamento-java): plain Java, inheritance and polymorphism in salary calculation (Unifacs coursework).
