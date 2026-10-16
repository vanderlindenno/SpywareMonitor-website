# Android app SpywareMonitor – website

Source of **[spywaremonitor.app](https://spywaremonitor.app/)**, the website of **SpywareMonitor**, a privacy-first Android app that checks which apps on your phone could be used to watch you.

## About the app

- Finds known stalkerware (131 apps, by name and signing certificate), hidden apps, apps that read your screen or notifications, device admins and apps installed outside an app store
- Checks screen lock, USB debugging and developer options
- Pro (one payment): background monitoring, history and an evidence report (PDF)
- No internet permission, no ads, no account. All data stays on the device.
- Available in English, Norwegian and Dutch

Made by Nordic Appworks, who also make [UpdateMonitor](https://updatemonitor.app/) and [RebootMonitor](https://rebootmonitor.com/).

## Pages

| Page | Topic |
|------|-------|
| [Home](https://spywaremonitor.app/) | Overview, safety advice, FAQ |
| [Norsk](https://spywaremonitor.app/no/) | Norwegian homepage |
| [Privacy policy](https://spywaremonitor.app/privacy.html) | What the app and the website do with data |
| [Personvern](https://spywaremonitor.app/no/personvern.html) | Norwegian privacy policy |

Every page has a "Quick exit" button that replaces the page with google.com, for visitors who may be watched.

## About this repository

A plain static website hosted on GitHub Pages, without analytics or tracking. After a push that changes pages, two GitHub Actions update `lastmod` in `sitemap.xml` and notify Bing about the changed pages (needs the `BING_API_KEY` repository secret).

The list of known stalkerware mentioned on the site comes from [Echap's stalkerware indicators](https://github.com/AssoEchap/stalkerware-indicators), CC BY 4.0.

© 2026 Nordic Appworks. All rights reserved.
