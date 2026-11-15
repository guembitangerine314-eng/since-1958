<div align="center">

# 🌑 Since 1958

### *They went, they worked, they fell silent. Their achievements are not.*

An interactive 3D time machine for the machines NASA left on the Moon, on Mars and in deep space.

[![Live site](https://img.shields.io/badge/▶_Live_site-open_Since_1958-f5b942?style=for-the-badge)](https://guembitangerine314-eng.github.io/since-1958/)

![Space Apps 2026](https://img.shields.io/badge/NASA_Space_Apps_Challenge-2026-0b3d91?style=flat-square)
![Challenge](https://img.shields.io/badge/Challenge-Abandoned_but_not_Forgotten-6b4fbb?style=flat-square)
![Team](https://img.shields.io/badge/Team-Concinendial-2f855a?style=flat-square)
![No install](https://img.shields.io/badge/runs_in-any_browser-555?style=flat-square)

**👉 https://guembitangerine314-eng.github.io/since-1958/**

</div>

---

## 🛰️ The problem

Most of the machines we sent into space never came home. Their stories are scattered across technical archives, so most people only ever hear about the missions that are flying today. The landers, rovers and probes that opened up the Solar System are, for most of us, already forgotten.

## ✨ Our answer

**Since 1958** puts all of them in one place, on one clock. Press play in 1958 and watch each machine arrive on its real date, at its real landing site. Fly down to it, walk around it, take it apart, and learn what it was for, what it found, and why it is still out there.

| | |
|---|---|
| 🕰️ **One clock, 1958 → today** | 83 events on a timeline. The Sun, planets and Moon are computed for every moment, at true size and distance. |
| 📍 **Every site, at its real place** | 24 landing and impact sites on the Moon and Mars, each at its real latitude and longitude, and 11 probes in deep space. |
| 🎬 **Watch each one land** | 30 short mission films, plus 4 featured animations: Apollo 11 from pad to Tranquility Base, Voyager 1 up close, Perseverance's seven minutes, and how James Webb works. |
| 🚶 **Walk right up to it** | Walk the Apollo sites in the Moon's real gravity, and follow Curiosity, Perseverance and Ingenuity along NASA/JPL's published routes. |
| 🏛️ **Virtual exhibition** | A clean-room hall with 44 exhibits at true size. Walk, jump, and take each machine apart piece by piece. |
| 💡 **Some still work today** | The machines still working show what they have achieved so far, from Voyager's 49 years to Perseverance's new driving record. |
| ✉️ **Message to Voyager** | Write to Voyager 1, as more than 30,000 people did through NASA in 2017, and follow your message out at the speed of light. |
| 📰 **News** | The biggest moments told as news stories, with official NASA, ESA, CSA and STScI photos. |
| 🎓 **Start guidance** | A short, hands-on tutorial teaches the controls by using them. |

Made for curious people from about age 10 up. Works on a computer or a phone, with no install and no account.

## 📡 NASA data at the core

- **NASA NSSDCA catalogue and NASA mission pages:** dates, landing coordinates and facts. Every object lists its own sources, inside the site.
- **NASA 3D Resources:** spacecraft models (lunar module, Viking, Spirit/Opportunity, Curiosity, Perseverance, Ingenuity, InSight, Hubble, Webb, Cassini and more).
- **NASA SVS CGI Moon Kit (LRO):** the detailed Moon map.
- **NASA SVS star maps:** about 150,000 real stars at their real places, from the Yale, Hipparcos and Tycho catalogues.
- **NASA/JPL rover traverse data:** the real routes of Curiosity, Perseverance and Ingenuity.
- **Astronomy Engine:** positions of the Sun, Moon and planets for any date.

## ✅ Accuracy, honestly

Accuracy matters in a story about real machines, so the site has a **"What is real?"** panel. It separates real data (positions, sites, dates, routes) from what is simplified (flight paths between planets, hand-built models where NASA has none) and what is only illustration (the Milky Way's fine detail, flames and smoke in the films).

## 🎮 Controls

| Action | How |
|---|---|
| Look around / zoom | Drag / scroll |
| Pick a world or a site | Click it, or use **Go to…** and **Find** |
| Control time | Clock panel (top right) or the timeline |
| Skip a film or animation | **Tab** |
| Exhibition | **W A S D** walk · **Space** jump · **V** 3rd person · **E** take apart |
| Hide everything but the view | **H** |

## 🛠️ Built with

JavaScript (ES modules) · [three.js](https://threejs.org) · GLSL shaders · HTML/CSS · [Astronomy Engine](https://github.com/cosinekitty/astronomy) · Python and Blender for preparing data and models.

### Run it yourself
It is a static site with no build step. Serve the folder with any web server (ES modules do not load from `file://`):

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

## 📚 Credits and references

- **Libraries:** three.js and Astronomy Engine (both MIT licence).
- **3D models:** NASA 3D Resources. Surveyor, the lunar rover, the Apollo science stations, Pathfinder/Sojourner, Phoenix, New Horizons, Voyager, Webb, the Saturn V and Launch Complex 39A were built by hand to NASA's published sizes.
- **Planet maps:** Solar System Scope (CC BY 4.0, resized) for Mercury, Venus, Jupiter, Saturn, Uranus, Neptune and the detailed Earth and Mars; NASA SVS CGI Moon Kit (LRO) for the detailed Moon; NASA 3D Resources for the first Mars map and Pluto; three.js examples (MIT) for the first Earth and Moon maps.
- **Photos:** official NASA, ESA, CSA and STScI images, credited under each one in the site.
- **Fonts:** Archivo Narrow, Cinzel and Newsreader (SIL Open Font License), via Google Fonts.
- **Music:** generated live in the browser; no recording is used.
- **AI assistance:** code and procedural artwork were written with help from an AI assistant (Claude). Every fact was checked against the NASA pages listed on each object. No NASA logos or branding are used or modified.

This is a student project for the NASA Space Apps Challenge. It is not an official NASA website.

## 👩‍🚀 Team Concinendial

1. **Semin Cheon**, Garden International School, 10M (Managing Head)
2. **Ian Lee**, Garden International School, 10M (Team Leader)
3. **Junyi Chai**, Garden International School, 11W (Advisor for mobile experience)

<div align="center">

*Made for everyone who looks up and wonders what we left out there.* ✨

</div>
