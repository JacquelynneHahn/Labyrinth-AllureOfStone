# Labyrinth — Allure of Stone

A native Android reader for the *Labyrinth — Allure of Stone* novel, with
chapter narration, live party / encounter / bestiary panels, and a gallery
of story-moment art that unlocks as you read.

This repository hosts release binaries — the source code lives elsewhere.

## Download the latest version

| | |
|---|---|
| **Latest release** | [v1.64](https://github.com/JacquelynneHahn/Labyrinth-AllureOfStone/releases/latest) |
| **APK** | [app-debug.apk](https://github.com/JacquelynneHahn/Labyrinth-AllureOfStone/releases/latest/download/app-debug.apk) (~18 MB) |
| **Manifest** | [latest.json](https://github.com/JacquelynneHahn/Labyrinth-AllureOfStone/releases/latest/download/latest.json) |

The APK itself is small. On first launch the app downloads the story
content — about 1.2 GB of prose, art, and audio narration — directly
from this repo. **Wi-Fi is strongly recommended** for that first-launch
download. After it's done the app works fully offline.

## Install on Android

1. Open the APK link above on your Android device, or transfer the file
   from a computer and tap it in your Files / Downloads app.
2. Android will ask whether to allow installs from this source. Approve
   for whichever app you used to open the APK (your browser or file
   manager).
3. Tap **Install**, wait a moment, then **Open**.
4. The app will show a one-time setup screen and download the story
   bundles (~1.2 GB). Leave it on Wi-Fi for ~10-15 minutes; you can
   navigate away and come back when it's done.
5. After setup completes, the app lands on a profile picker — pick a
   slot, then tap into the book.

## Self-updates

The app keeps itself current. About eight seconds after launch on Wi-Fi
it checks the manifest in the background; if a newer version is out,
a gold "Update available" banner slides down at the top of the screen.
Tap it to install — you'll only need to confirm once with Android's
standard install prompt.

To check manually any time: open the chapter selector at the top of the
reader → scroll to the bottom of the dropdown → tap
**v1.x • Check for updates**.

Updates are modular — the story-data, image, and audio bundles are
versioned independently, so a release that only adjusts prose doesn't
force a re-download of the 700 MB audio bundle.

## What's inside the app

- **42 chapters** of prose with full audio narration that follows along word-by-word
- **Party tracking** — HP, MP, Stamina, Emotional Stamina, buffs and statuses, per beat
- **Live combat ledger** with formulas, kill counts, and HP bars that drain as the fight unfolds
- **Bestiary integrated into the Enemies panel** — tap any enemy tile to see the body shot and full lore (zone, attacks, behaviour, strategy)
- **Character bonds** — relationship tracking between Rob, Mirelle, Elara, and Johr
- **Story-moment gallery** that fills in as you read; unlocks pop a notification you can tap to view
- **Sacred Texts** — Preface, Arathi Bible, Book of the Ordained, Priest Codex, Dark Scriptures as separate sections accessible from the chapter dropdown
- **Profiles** so multiple readers can each track their own progress

## About the book

*Labyrinth — Allure of Stone* opens with Rob, a stranded medic, recruited
into the dangerous world of the labyrinth — a vast subterranean structure
that grants powers to those who survive its depths. The story follows him,
his guide Mirelle, and the companions they find as they navigate combat,
politics, and growing magical bonds across the city of Lethar and the
labyrinth's three accessible levels.

Two books in one app: *Allure of Stone* (Chapters 1-21) and *Trinity*
(Chapters 22-42).

## Release notes

See the [Releases](https://github.com/JacquelynneHahn/Labyrinth-AllureOfStone/releases)
page for the version history. Each release notes what's new, what's
fixed, and any actions you should take.

## Reporting issues

If something looks wrong in the reader (missing image, wrong stat,
glitchy text, broken audio sync) — note the chapter and approximate
beat, and reach out directly. This isn't a public-issue-tracker setup;
feedback goes through personal channels.

---

*Personal project — please don't redistribute without permission.*

