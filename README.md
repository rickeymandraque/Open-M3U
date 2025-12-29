🌍 **Languages**  
[🇬🇧 English](README.md) · [🇫🇷 Français](README.fr.md) · [🇪🇸 Español](README.es.md) · [🇮🇹 Italiano](README.it.md) · [🇵🇹 Português](README.pt.md)

---

## What is Open-M3U?

**Open-M3U** is an open, community-driven project that documents and improves the real-world usage of **M3U playlists**, especially in the context of **IPTV**.

M3U playlists are widely used, but there is **no official specification** for IPTV-specific tags and behaviors.  
As a result, every player, provider, and tool interprets M3U files slightly differently.

Open-M3U aims to:

- document existing practices,
- identify what actually works across players,
- and propose **pragmatic, optional standard profiles** based on real usage.

> Open-M3U does **not** impose a mandatory standard.  
> It proposes **documented, observable, and tested conventions**.

---

## What is an M3U file?

An **M3U file** is a plain text playlist that lists media streams (audio or video).

In IPTV, M3U files are commonly used to describe:
- TV channels
- Radio streams
- IPTV services

A basic M3U file looks like this:

```m3u
#EXTM3U
#EXTINF:-1,Example Channel
https://example.com/stream.m3u8
````

---

## Why does Open-M3U exist?

Because today:

* There is **no official IPTV M3U standard**
* IPTV tags like `tvg-id`, `group-title`, or `catchup` are undocumented
* Compatibility issues are common between players (VLC, Kodi, TiviMate, etc.)

Open-M3U provides:

* a **clear overview** of what exists,
* **sources and references** for each behavior,
* and **recommended profiles** to improve compatibility.

---

## Project structure

* **docs/** – explanations and beginner documentation
* **registry/** – observed M3U tags and attributes
* **profiles/** – proposed standard profiles (Core, IPTV Plus, etc.)
* **players/** – player capabilities (FFmpeg, VLC, Kodi, TiviMate…)
* **fixtures/** – real test playlists
* **examples/** – simple scripts and samples

---

## Getting started

Start here if you are new:

* 📘 [What is M3U?](docs/what-is-m3u.md)
* 🔤 [Encoding and line endings](docs/encoding-and-lines.md)
* 🧱 [Basic M3U structure](docs/basic-structure.md)
* 📖 [Glossary](docs/glossary.md)

---

## Contributions

Contributions are welcome, especially if you provide:

* real playlists or test cases,
* references to documentation or code,
* reproducible player behaviors.

Open-M3U values **facts over opinions**.

---

