# DailySense — Intelligent Daily Companion

Android team project (2025). README by **Mengxuan Shen**.

**Portfolio page with full demo video:** https://shine574269.github.io/projects/dailysense.html

DailySense combines phone-sensor activity tracking, a calendar and AI-generated daily diary entries, linking what was planned with what actually happened.

## My contribution
- Designed the full user interface in Figma.
- Built the calendar (schedule) module and integrated it with teammates' sensing and diary modules, so calendar events feed the diary generator.
- Wrote the related sections of the technical report (contributions are listed in §2.5).

Activity sensing and AI diary generation were built by my teammates; the demo video was produced by the team.

## Files
| File | Contents |
|---|---|
| `DailySense_AndroidStudio_Public_Source.zip` | Android Studio project (Java), with private keys and settings removed |
| `DailySense_Technical_Report_Public.pdf` | Architecture, calendar module and integration |
| `DailySense_Video_Poster.jpg` | Cover frame of the demo video |

## Building
Unzip the project, open it in Android Studio and run it on an Android device or emulator. AI diary generation needs your own API key: replace `REPLACE_WITH_YOUR_OWN_KEY` in `util/ApiUtil.java`. No real key is included.
