# Android app SpywareMonitor – website

Source of **[spywaremonitor.app](https://spywaremonitor.app/)**, the website of **SpywareMonitor**, a privacy-first Android app that checks which apps on your phone could be used to watch you.

## About the app

- Finds known stalkerware (132 apps, by name and signing certificate), hidden apps, apps that read your screen or notifications, device admins, and apps installed from a file or from a computer over USB instead of an app store
- Shows family and tracking apps (27 apps, such as Life360 and Qustodio) in orange, never red, with a plain explanation
- Checks the keyboard, screen lock, USB debugging and developer options
- Access (free): which apps may use the microphone, location, camera, contacts, messages and other access, and what is normal for them
- Pro (one payment): automatic checks, unlock log, history, an evidence report (PDF), and disguise and PIN lock
- No internet permission, no ads, no account. All data stays on the device.
- Available in 10 languages: English, Norwegian, Dutch, German, French, Spanish, Polish, Simplified Chinese, Hindi and Arabic

Made by Nordic Appworks, who also make [UpdateMonitor](https://updatemonitor.app/) and [RebootMonitor](https://rebootmonitor.com/).

## Pages

| Page | Topic |
|------|-------|
| [Home](https://spywaremonitor.app/) | Overview, safety advice, FAQ |
| [Help](https://spywaremonitor.app/help.html) | Step-by-step help for the app |
| [Norsk](https://spywaremonitor.app/no/) | Norwegian homepage, with [help](https://spywaremonitor.app/no/hjelp.html) |
| [Nederlands](https://spywaremonitor.app/nl/) | Dutch homepage |
| [de](https://spywaremonitor.app/de/), [fr](https://spywaremonitor.app/fr/), [es](https://spywaremonitor.app/es/), [pl](https://spywaremonitor.app/pl/), [zh](https://spywaremonitor.app/zh/), [hi](https://spywaremonitor.app/hi/), [ar](https://spywaremonitor.app/ar/) | Homepages in German, French, Spanish, Polish, Simplified Chinese, Hindi and Arabic |
| [Privacy policy](https://spywaremonitor.app/privacy.html) | What the app and the website do with data |
| [Personvern](https://spywaremonitor.app/no/personvern.html) | Norwegian privacy policy |

Every page has a "Quick exit" button that replaces the page with google.com, for visitors who may be watched.

## About this repository

A plain static website hosted on GitHub Pages, without analytics or tracking. After a push that changes pages, two GitHub Actions update `lastmod` in `sitemap.xml` and notify Bing about the changed pages (needs the `BING_API_KEY` repository secret).

The list of known stalkerware mentioned on the site comes from [Echap's stalkerware indicators](https://github.com/AssoEchap/stalkerware-indicators), CC BY 4.0.

© 2026 Nordic Appworks. All rights reserved.
