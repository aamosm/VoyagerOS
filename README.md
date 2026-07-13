<div align="center">

# VoyagerOS

A browser-based operating system for the fictional Voyager-9 deep-space probe.

**Live:** https://aamosm.github.io/VoyagerOS <br>
**Devlog:** https://stardance.hackclub.com/projects/31884

</div>

---

## About

VoyagerOS is a browser-based operating system built for the fictional Voyager-9 deep-space probe.

The goal is to make it feel like real software instead of just another website. From the boot sequence to the desktop, terminal, applications and virtual filesystem, everything happens inside the operating system.

VoyagerOS is also part of a larger project alongside **[This Alien Does Not Exist](http://thisaliendoesnotexist.app/)**. The long-term goal is to make VoyagerOS the in-universe operating system used aboard Voyager-9 for discovering, documenting and cataloguing procedurally generated alien species through the Alien Registry.

---

## Features

- Boot sequence
- Desktop environment
- Draggable and resizable windows
- Virtual filesystem
- Terminal with command history
- File Explorer
- Paint
- Alien Registry
- ALR (Alien Registration) package support
- Archive Viewer
- Internet Archive integration
- Dynamic data mounting

---

## Applications

The operating system currently includes:

- Alien Registry
- Archive Viewer
- File Explorer
- Paint
- Process Manager
- Settings
- Terminal
- Text Viewer

---

## Alien Registry

The Alien Registry is VoyagerOS' primary scientific database for browsing and documenting procedurally generated alien species.

It supports:

- Procedural alien archive
- Official ALR repository integration
- Local registrations
- Registry search
- Random browsing
- Alien Registration (`.alr`) packages

Interested in contributing your own discoveries?

See the **[ALR Repository Guide](./alr/README.md)** for instructions on creating and submitting Alien Registration packages.

---

## Technologies

- JavaScript
- HTML
- CSS
- HTML5 Canvas
- Fetch API
- JSZip
- Web Crypto API
- LocalStorage
- SessionStorage
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

- More desktop applications
- More terminal commands
- Expand the virtual filesystem
- Better window management
- More ship logs and mission files
- Reverse alien search
- Expanded Alien Registry
- Saveable desktop sessions

---

## License

No License
