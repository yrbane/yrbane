<div align="center">

<br>

### Hey, I'm Seb

**Systems engineer & open source developer**

I build tools that harden servers, replace core utilities, and make the web more secure. blablabla

<br>

![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-1572B6?style=for-the-badge&logo=css3&logoColor=white)

<br>

</div>

---

### Featured projects

<sub>🕹️ Everything with a screenshot is a **live demo** — click the pictures!</sub>

<table>
<tr>
<td colspan="2" valign="top">

**[micro-blog-static](https://nethttp.net)** 📝
Static blog generator with a PHP admin — full-text search (weighted inverted index), date archives, responsive WebP/LQIP media, scheduled publishing, TOTP 2FA, encrypted backups, outgoing webmentions, auto breadcrumbs, an AI assistant (Claude API) and a hardened CSP. Ships bespoke per-article themes (an interactive cost calculator included). TDD, PHPStan L5, CI + atomic deploy. **[Live demo](https://nethttp.net)**

[<img src="https://yrbane.github.io/shots/micro-blog-static.webp" alt="micro-blog-static screenshot" width="100%">](https://nethttp.net)

`php` `static-site-generator` `sqlite` `blog` `self-hosted`

</td>
</tr>
<tr>
<td colspan="2" valign="top">

**[minoupix](https://minoupix.com)** 🐱
One name, one cat. Forever. — a Rust generator of kawaii pixel-art cat heads, 100% deterministic and offline: the name is hashed into a seed, the seed draws everything (29 coats, 12 moods, 36 accessories, rarity ornaments), and the same name always yields the exact same cat. GIFs are alive: blinking with a wink sparkle, jingling bell, twinkling stars, beating hearts, floating Zzz, a snail that actually crawls. Now an NFT collection — the **210-cat genesis** (from Bastet to Ziggy) lives on **Base**, metadata pinned on IPFS with verifiable on-chain freeze, and the whole genesis is browsable at **[minoupix.com](https://minoupix.com)** — every cat with its own page in 11 languages. 354 tests, TDD all the way. **[Live site](https://minoupix.com)**

[<img src="https://yrbane.github.io/shots/minoupix.webp" alt="minoupix.com — the genesis home page, a grid of 210 animated pixel-art cats" width="100%">](https://minoupix.com)

`rust` `pixel-art` `deterministic` `nft` `base` `ipfs`

</td>
</tr>
<tr>
<td colspan="2" valign="top">

**[SysWall](https://github.com/yrbane/SysWall)** 🛡️
Application-level firewall for Linux — the Little Snitch experience, native and open source. Intercepts every new connection with **nftables + NFQUEUE**, attributes it to the owning process via **eBPF**, and prompts you to allow / block / snooze / make-a-rule from a **Tauri** desktop app. Live connection monitor, audit journal, learning mode, kill-switch with anti-lockout. Rust **hexagonal architecture** (domain/app/infra/daemon), gRPC over a `SO_PEERCRED`-hardened Unix socket, systemd-sandboxed unit. TDD, fuzzing + proptest, green CI, one-command install. **[Latest release](https://github.com/yrbane/SysWall/releases/latest)**

[<img src="https://yrbane.github.io/shots/syswall.webp" alt="SysWall screenshot" width="100%">](https://github.com/yrbane/SysWall)

`rust` `linux` `firewall` `nftables` `ebpf` `tauri`

</td>
</tr>
<tr>
<td colspan="2" valign="top">

**[Oscillo](https://github.com/yrbane/oscillo)** 〰️
Real-time stereo audio oscilloscope in Rust — the **Mordax DATA** spirit on your desktop. Cross-platform capture with **cpal** (WASAPI / CoreAudio / ALSA), **egui** rendering at 60 FPS, and a **lock-free ring buffer** between the audio callback and the UI — zero allocation in the hot path. Overlay / Split / **XY (Lissajous)** display modes, scope-grade trigger (level, edge, single-shot), per-channel gain & offset, persistent settings. Feed it two oscillators, switch to XY, and *watch* a perfect fifth draw itself. MIT. **[Latest release](https://github.com/yrbane/oscillo/releases/latest)**

[<img src="https://yrbane.github.io/shots/oscillo.webp" alt="Oscillo screenshot — real-time stereo waveforms" width="100%">](https://github.com/yrbane/oscillo)

`rust` `audio` `dsp` `egui` `oscilloscope` `real-time`

</td>
</tr>
<tr>
<td colspan="2" valign="top">

**[okulist](https://yrbane.github.io/okulist/)** 👁️
Visual self-screening in your browser — acuity (Landolt rings), duochrome, astigmatism, contrast sensitivity, near vision, color vision, Amsler grid, digital eye strain, 14 tests in all. Screen calibration via a credit card reference + measured gamma (proper Weber contrast, sub-pixel vernier rendering), optional webcam distance tracking (FaceMesh, 100% local, nothing leaves the browser), session history with acuity trend graphs. Wraps up with the macOS accessibility settings your results actually suggest. Clearly labeled indicative, not diagnostic. Offline-first PWA, single-file vanilla JS. **[Live demo](https://yrbane.github.io/okulist/)**

[<img src="https://yrbane.github.io/shots/okulist.webp" alt="okulist screenshot — red/green duochrome test bars above the calibration screen" width="100%">](https://yrbane.github.io/okulist/)

`javascript` `accessibility` `vision` `pwa` `canvas`

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[youtubator](https://yrbane.github.io/youtubator/)** 🎛️
DJ mixer in the browser — decks are YouTube players **or local files**. Customizable **automix** (harmonic mixing, bass swap, fade curves), auto beatmatch, 3-band EQ, beat-locked loops, waveforms, MIDI, PWA. **[Live demo](https://yrbane.github.io/youtubator/)**

[<img src="https://yrbane.github.io/shots/youtubator.webp" alt="youtubator screenshot" width="100%">](https://yrbane.github.io/youtubator/)

`typescript` `web-audio` `dj` `beatmatch` `svelte`

</td>
<td width="50%" valign="top">

**[WebGlitch](https://github.com/yrbane/WebGlitch)** 📺
Browser extension that bends web pages with sound or a MIDI controller — audio and CC drive CSS variables in real time. CC learn, per-site presets, effect snippets. **[Latest release](https://github.com/yrbane/WebGlitch/releases/latest)**

[<img src="https://yrbane.github.io/shots/webglitch.webp" alt="WebGlitch screenshot" width="100%">](https://github.com/yrbane/WebGlitch)

`typescript` `web-audio` `css` `glitch` `extension`

</td>
</tr>
<tr>
<td colspan="2" valign="top">

**[RustyPet](https://github.com/yrbane/rustypet)** 🐑🐈
Desktop pet for GNOME Shell on Wayland — a Rust port of the legendary eSheep/Neko screenmates. The sheep drops from the sky, lands on your windows, strolls across their roofs… then dances, smokes, flies like Superman, rockets away, pops an umbrella under his personal rain cloud (or gets soaked), and trips on acid 🕶️🚀🌧️. He falls in love — a ewe walks in, two lambs trot behind (**multi-pet** engine) — you can **grab him with the mouse**, and he **bleats, quietly**. Pure engine testable without a display (95+ tests, deterministic replay by seed), D-Bus daemon + GNOME extension, all 28 original pets supported. TDD all the way. **[Latest release](https://github.com/yrbane/rustypet/releases/latest)**

[<img src="https://yrbane.github.io/shots/rustypet.webp" alt="RustyPet screenshot — the whole sheep family: superman, parachute, rocket, umbrella, the ewe in love and the lambs" width="100%">](https://github.com/yrbane/rustypet)

`rust` `gnome-shell` `wayland` `d-bus` `desktop-pet`

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[potard](https://github.com/yrbane/potard)**
Ableton/Traktor-style audio controls as Web Components — knobs, faders, arrow sliders, crossfader… and constant-sum mix groups to split a budget or skill points 🎚️ Zero deps. **[Interactive docs](https://yrbane.github.io/potard/)** · **[v0.3.0](https://github.com/yrbane/potard/releases/tag/v0.3.0)**

[<img src="https://yrbane.github.io/shots/potard.webp" alt="potard screenshot" width="100%">](https://yrbane.github.io/potard/)

`typescript` `web-components` `ui`

</td>
<td width="50%" valign="top">

**[mystical-runic](https://github.com/yrbane/mystical-runic)** 🔮
Ancient Symbols for Modern Web Magic — runic template engine in Rust. Most starred here.

`rust` `templating` `runes`

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[torall](https://github.com/yrbane/torall)**
GNOME Shell extension: route all traffic through Tor, with a colored status icon.

`gnome-shell` `tor` `privacy`

</td>
<td width="50%" valign="top">

**[cp](https://github.com/yrbane/cp)**
Modern GNU-compatible `cp` in Rust — zero-copy I/O, parallel directory copy, sparse files, reflink.

[<img src="https://yrbane.github.io/shots/cp.webp" alt="cp docs screenshot" width="100%">](https://yrbane.github.io/cp/)

`rust` `cli` `unix` `zero-copy`

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[multishiva](https://github.com/yrbane/multishiva)**
Share one keyboard & mouse across Linux, macOS, Windows on LAN.

`rust` `kvm` `cross-platform` `network`

</td>
<td width="50%" valign="top">

**[debian13-admin](https://github.com/yrbane/debian13-admin)**
Bootstrap, hardening & multi-domain management for Debian 13. 465 tests, zero deps.

[<img src="https://yrbane.github.io/shots/debian13-admin.webp" alt="debian13-admin docs screenshot" width="100%">](https://yrbane.github.io/debian13-admin/)

`bash` `security` `ovh-api` `fail2ban` `letsencrypt`

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[photo-sort](https://github.com/yrbane/photo-sort)**
EXIF photo sorter, BLAKE3 dedup, web gallery, tags, REST server.

[<img src="https://yrbane.github.io/shots/photo-sort.webp" alt="photo-sort docs screenshot" width="100%">](https://yrbane.github.io/photo-sort/)

`rust` `exif` `gallery` `blake3`

</td>
<td width="50%" valign="top">

**[lunar-aurora](https://github.com/yrbane/lunar-aurora)**
Avant-garde CSS framework — OKLCH colors, `@property`, nesting, container queries, 30 themes.

[<img src="https://yrbane.github.io/shots/lunar-aurora.webp" alt="lunar-aurora screenshot" width="100%">](https://yrbane.github.io/lunar-aurora/)

`css` `framework` `modern-css`

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[music-sorter](https://github.com/yrbane/music-sorter)** 🎵
Automatic music library organizer — MusicBrainz, AcoustID & Discogs tagging, content-hash dedup, `_review` quarantine, fully reversible rollback. Rust + rayon, SQLite-cached, blazing on re-runs. **[Latest release](https://github.com/yrbane/music-sorter/releases/latest)**

[<img src="https://yrbane.github.io/shots/music-sorter.webp" alt="music-sorter screenshot" width="100%">](https://github.com/yrbane/music-sorter/releases/latest)

`rust` `musicbrainz` `acoustid` `discogs`

</td>
<td width="50%" valign="top">

**[tuner](https://github.com/yrbane/tuner)** ᛚ
Chromatic tuner in the browser, built for analog synths — mic → autocorrelation → giant note, cents offset, needle, unambiguous colors. Median + hysteresis anti-jitter, SENS knob, VU meter (powered by [potard](https://github.com/yrbane/potard)). Zero deps, no sound ever leaves the browser. **[Tune now](https://tuner.nethttp.net)**

[<img src="https://yrbane.github.io/shots/tuner.webp" alt="tuner screenshot — LA1 at +1 cent, all green" width="100%">](https://tuner.nethttp.net)

`javascript` `web-audio` `autocorrelation` `synths`

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[LacheMoiLaGrappe](https://github.com/yrbane/LacheMoiLaGrappe)** 🛡️
Anti-telemarketer shield for Android — smart call filtering, open source, free, zero tracking. **[Project page](https://yrbane.github.io/LacheMoiLaGrappe/)**

[<img src="https://yrbane.github.io/shots/lachemoilagrappe.webp" alt="LacheMoiLaGrappe screenshot" width="100%">](https://yrbane.github.io/LacheMoiLaGrappe/)

`kotlin` `android` `privacy`

</td>
<td width="50%" valign="top">

**[geo3d](https://github.com/yrbane/geo3d)** 🔺
Generative 3D wireframe animation — 7 polyhedra, 8 palettes, random mode, URL params. Zero deps. **[Live demo](https://yrbane.github.io/geo3d/)**

[<img src="https://yrbane.github.io/shots/geo3d.webp" alt="geo3d screenshot" width="100%">](https://yrbane.github.io/geo3d/)

`javascript` `3d` `generative` `wireframe`

</td>
</tr>
</table>

---

<div align="center">

<img src="https://github-readme-streak-stats.herokuapp.com?user=yrbane&theme=tokyonight&hide_border=true&background=0A1628&ring=DC5C3B&fire=DC5C3B&currStreakLabel=6BDBDB&sideLabels=6BDBDB&dates=64748B&currStreakNum=E2E8F0&sideNums=E2E8F0" width="500" />

<br><br>

<sub>

[micro-blog-static](https://nethttp.net) · [SysWall](https://github.com/yrbane/SysWall) · [youtubator](https://yrbane.github.io/youtubator/) · [music-sorter](https://github.com/yrbane/music-sorter) · [debian13-admin](https://yrbane.github.io/debian13-admin/) · [geo3d](https://yrbane.github.io/geo3d/) · [GitHub](https://github.com/yrbane?tab=repositories)

</sub>

</div>
