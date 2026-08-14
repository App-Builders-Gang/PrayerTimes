<p align="center">
    <strong>English</strong> | <a href="README.ar.md">العربية</a> | <a href="README.id.md">Indonesia</a> | <a href="README.fa.md">فارسی</a> | <a href="README.ur.md">اردو</a>
</p>

<p align="center">
    <img src="art/en/logo.png" alt="PrayerTimes Pro — Prayer Times for Mac" height="120">
</p>

<h1 align="center">PrayerTimes Pro</h1>

<p align="center">
    <strong>A minimalist, privacy-first Islamic prayer times app for your Mac's menu bar.</strong><br>
    Offline prayer-time calculation · 18+ methods · 5 languages · Apple Silicon & Intel
</p>

<p align="center">
    <a href="https://apps.apple.com/eg/app/prayer-times-pro-menubar/id6763390896?mt=12">
        <img src="https://developer.apple.com/app-store/marketing/guidelines/images/badge-download-on-the-mac-app-store.svg" alt="Download on the Mac App Store" height="56">
    </a>
</p>

<p align="center">
    <a href="https://github.com/abd3lraouf-studios/PrayerTimes/releases/latest"><img src="https://img.shields.io/github/v/release/abd3lraouf-studios/PrayerTimes?color=%2300834a&label=latest" alt="Latest release"></a>
    <a href="https://github.com/abd3lraouf-studios/PrayerTimes/releases/latest"><img src="https://img.shields.io/github/downloads/abd3lraouf-studios/PrayerTimes/latest/total?color=%2300834a&label=downloads%20%28latest%29" alt="Latest downloads"></a>
    <a href="https://github.com/abd3lraouf-studios/PrayerTimes/releases"><img src="https://img.shields.io/github/downloads/abd3lraouf-studios/PrayerTimes/total?color=%2300834a&label=downloads%20%28total%29" alt="Total downloads"></a>
    <a href="https://github.com/abd3lraouf-studios/PrayerTimes/issues"><img src="https://img.shields.io/github/issues/abd3lraouf-studios/PrayerTimes?color=%2300834a" alt="Open issues"></a>
    <a href="https://github.com/abd3lraouf-studios/PrayerTimes/stargazers"><img src="https://img.shields.io/github/stars/abd3lraouf-studios/PrayerTimes?color=%2300834a&style=flat" alt="Stars"></a>
</p>

<p align="center">
    <img src="https://img.shields.io/badge/platform-macOS%2014%2B-informational.svg" alt="macOS 14+">
    <img src="https://img.shields.io/badge/arch-Apple%20Silicon%20%7C%20Intel-lightgrey.svg" alt="Apple Silicon & Intel">
    <img src="https://img.shields.io/badge/notarized-✓-success.svg" alt="Apple Notarized">
    <img src="https://img.shields.io/badge/sandboxed-✓-success.svg" alt="Sandboxed">
</p>

<p align="center">
    <img src="art/en/screenshots.png" alt="PrayerTimes Pro screenshots — the welcome guide, the prayer timeline with countdown and streak, a full-screen prayer alert, and Settings" width="780">
</p>

---

## Why PrayerTimes Pro?

- **Completely private** — no tracking, no analytics, no accounts. Prayer times are calculated on your Mac, and your precise location is never transmitted.
- **Designed for the menu bar** — always visible, never in the way. Countdown, exact time, compact, or icon-only.
- **Accurate worldwide** — 18+ calculation methods, per-prayer adjustments, custom angles.
- **Offline-first** — calculations happen on-device. Network is only used for optional location search.

## Install

**Requirements:** macOS 14 (Sonoma) or later · Apple Silicon & Intel

### Mac App Store (recommended)

<a href="https://apps.apple.com/eg/app/prayer-times-pro-menubar/id6763390896?mt=12">
    <img src="https://developer.apple.com/app-store/marketing/guidelines/images/badge-download-on-the-mac-app-store.svg" alt="Download on the Mac App Store" height="48">
</a>

### Homebrew

```sh
brew install --cask abd3lraouf-studios/tap/prayertimes
```

### Direct download

Download the latest `.dmg` from [Releases](https://github.com/abd3lraouf-studios/PrayerTimes/releases/latest). The Developer ID build is signed, notarized, and auto-updates via [Sparkle](https://sparkle-project.org).

If macOS blocks the first launch:

```sh
xattr -r -d com.apple.quarantine /Applications/PrayerTimes.app
```

## Features

- Menu bar **countdown**, exact time, compact, or icon-only display
- **Notifications** before and at prayer time, with optional full-screen alerts
- **18+ calculation methods**: Muslim World League (MWL), ISNA, Egyptian General Authority, Umm al-Qura (Makkah), Diyanet (Turkey), Kemenag (Indonesia), Karachi, Tehran, Dubai, Qatar, Singapore, Kuwait, Algeria, France, Germany, Malaysia (JAKIM), and more
- **Auto or manual location** · per-prayer time adjustments to match your local mosque
- **Hijri calendar** with adjustable date and Islamic event notifications (Ramadan, Eid al-Fitr, Eid al-Adha, Islamic New Year, Day of Ashura, and more)
- **Ramadan mode**: Suhoor and Iftar notifications with pre-alerts
- **Prayer log** — mark each prayer as you pray it, with a Fajr-anchored day rollover, streaks, and make-up (qada) tracking
- **Sunnah & Nawāfil** tracking alongside the five obligatory prayers
- **Qibla compass** pointing to the Kaaba from wherever you are
- **Adhan library** — a catalogue of recordings from 28 countries, with a separate adhan for Fajr, quiet hours, snooze defaults, and per-prayer announcements
- **Settings that find themselves** — a sidebar window with search across every pane
- **Locale-aware numerals** (Arabic-Indic, Extended Arabic-Indic, Western)
- **5 languages**: English, العربية, Bahasa Indonesia, فارسی, اردو — with full RTL support
- **Light/dark mode** follows your system, with an appearance override and accent colour picker
- **Accessible** — Dynamic Type, Increase Contrast and Reduce Motion respected app-wide

## Free and Pro

The **direct download** and the **Homebrew cask** ship every feature unlocked, free — there is no paywall in that build and nothing to buy.

The **Mac App Store** build sells a **$5 one-time Pro unlock**, which covers the prayer log and streaks, the animated prayer scenes, and the full adhan library. Everything else is free there too.

## Privacy

No tracking. No analytics. No crash reporters. No advertising. No accounts. Prayer times are calculated entirely on your Mac, and your **precise** location is never transmitted.

To show a city name rather than raw coordinates, the app rounds your position to ~1.1 km and asks Apple's geocoder for a name. Sending that coarsened coordinate to **OpenStreetMap Nominatim** instead — which Indonesian, Persian and Urdu need for a correctly-written name — is **off by default** and opt-in under Settings → Calculation & Location. Typing a city into the location picker sends the text you typed. Pro adhan clips download on demand from the Internet Archive, and Sparkle update checks run in the Developer ID build only. The Mac App Store build receives updates exclusively through Apple.

## What you can do here

- 🐛 [**Issues**](https://github.com/abd3lraouf-studios/PrayerTimes/issues) — report a bug or request a feature, or [create a new one](https://github.com/abd3lraouf-studios/PrayerTimes/issues/new/choose).
- 💬 [**Discussions**](https://github.com/abd3lraouf-studios/PrayerTimes/discussions) — ask questions, share ideas, and chat with other users.
- 📥 [**Releases**](https://github.com/abd3lraouf-studios/PrayerTimes/releases) — download a specific version or read the changelog.
- 📚 [**Wiki**](https://github.com/abd3lraouf-studios/PrayerTimes/wiki) — guides, FAQ, and shared knowledge.

If you have a problem or a request, search [Issues](https://github.com/abd3lraouf-studios/PrayerTimes/issues) first, then [open a new one](https://github.com/abd3lraouf-studios/PrayerTimes/issues/new/choose). For general chat that doesn't fit as an issue, head to [Discussions](https://github.com/abd3lraouf-studios/PrayerTimes/discussions).

## Support development

PrayerTimes Pro is built and maintained by one developer in their spare time. If it's useful to you, please consider supporting development:

<p>
    <a href="https://github.com/sponsors/abd3lraouf"><img src="https://img.shields.io/badge/GitHub%20Sponsors-EA4AAA?logo=github-sponsors&logoColor=white" alt="GitHub Sponsors" height="32"></a>
    <a href="https://www.buymeacoffee.com/abd3lraouf"><img src="https://img.shields.io/badge/Buy%20Me%20a%20Coffee-FFDD00?logo=buy-me-a-coffee&logoColor=black" alt="Buy Me a Coffee" height="32"></a>
    <a href="https://ko-fi.com/abd3lraouf"><img src="https://img.shields.io/badge/Ko--fi-FF5E5B?logo=ko-fi&logoColor=white" alt="Ko-fi" height="32"></a>
</p>

Every contribution — no matter how small — helps keep the app actively developed and free of ads, trackers, and accounts.

## Press & marketing assets

App icons, the logo lockup, the screen set, and the canonical product copy — naming, descriptions, links — are indexed in [`art/assets.json`](art/assets.json), next to the image files it describes. The product page is [abd3lraouf.dev/work/prayertimes](https://abd3lraouf.dev/work/prayertimes/).

## Credits

Built on top of these excellent projects:

- [Adhan](https://github.com/batoulapps/Adhan) — prayer time calculation
- [FluidMenuBarExtra](https://github.com/lfroms/fluid-menu-bar-extra) — menu bar UI
- [NavigationStack](https://github.com/indieSoftware/NavigationStack) — navigation
- [Sparkle](https://sparkle-project.org) — auto-update framework (Developer ID build)
- Inspired by [Sajda](https://github.com/ikoshura/Sajda)

## License

PrayerTimes Pro is **closed source**. This repository hosts the public release artifacts, issues, and discussions only. The application is distributed under its own End User License Agreement — see the [Mac App Store listing](https://apps.apple.com/eg/app/prayer-times-pro-menubar/id6763390896?mt=12).
