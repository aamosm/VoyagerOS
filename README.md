<div align="center">

# VoyagerOS

A browser-based operating system for the fictional Voyager-9 deep-space probe.

**Live:** https://aamosm.github.io/VoyagerOS <br>
**Devlog:** https://stardance.hackclub.com/projects/31884

</div>

---

## About

VoyagerOS is a browser-based operating system built for the fictional Voyager-9 deep-space probe.

The goal is to make it feel like real software instead of another website. From the boot sequence to the desktop, terminal, windows, virtual filesystem and applications, everything happens inside the operating system.

VoyagerOS is part of a larger world built around **[This Alien Does Not Exist](http://thisaliendoesnotexist.app/)**. It serves as the in-universe operating system used aboard Voyager-9 for documenting, browsing and managing extraterrestrial life through the Alien Registry.

---

## Features

- Boot sequence
- Desktop environment
- Draggable and resizable windows
- Virtual filesystem
- File Explorer
- Terminal with command history
- Text Viewer
- Settings
- Process Manager
- Archive Viewer
- Internet Archive integration
- Dynamic data mounting
- Alien Registry
- Paint application
- ALR (Alien Observation Package) support
- Local Observation storage
- Official Registry integration
- Procedural observation archive

---

## Applications

VoyagerOS currently includes:

- Terminal
- File Explorer
- Paint
- Alien Registry
- Text Viewer
- Settings
- Process Manager
- Archive Viewer

---

## Alien Registry

The Alien Registry is used to browse and document extraterrestrial observations.

It supports:

- Procedural observation archive
- Official observations from the ALR repository
- Local observations
- Observation validation
- Registry search
- Random observation browsing
- Observation packages (`.alr`)

Interested in contributing?

See the **[ALR Repository README](https://github.com/aamosm/VoyagerOS/tree/main/alr#readme)** for instructions on creating and submitting Observation Packages.

---

## Technologies

- JavaScript
- HTML
- CSS
- Flexbox
- Fetch API
- HTML5 Canvas
- HTML5 Drag and Drop API
- LocalStorage
- SessionStorage
- JSZip
- Web Crypto API
- Internet Archive Metadata API

---

## Running Locally

Clone the repository:

```bash
git clone https://github.com/aamosm/VoyagerOS.git
cd VoyagerOS
```

Start a local server:

```bash
python -m http.server
```

Open:

```text
http://localhost:8000
```

---

## Roadmap

- Additional desktop applications
- Expanded terminal command set
- Improved virtual filesystem
- Better window management
- More ship logs and mission files
- Expanded Alien Registry
- Additional observation tools
- More ALR repository integration
- Saveable desktop sessions

---

## License

No License
