# FFR Achievement Tracker

A save reader for **Final Fantasy Resonance** that shows your progress toward every achievement the save file records, styled after the classic FF7 menu.

**Use it here:** https://aiseubol.github.io/ffr-achievement-tracker/

## How to use

1. Open the page.
2. Drop `GameSaveData0.sav` or `GameSaveData1.sav` onto it, or click to choose a file.

Saves live in `%LOCALAPPDATA%\FFRS\Steam\<your Steam ID>\`.

The save is decrypted and read entirely in your browser. Nothing is uploaded.

## What it tracks

| Achievement | Read from the save |
|---|---|
| Keep Them on Their Toes (stagger 1000 times) | `Player.breakCount` |
| Resonance Rapid Fire (use Resonances 400 times) | `Player.finishblowCount` (most likely the Resonance counter) |
| Chapters 1–8 | Story progress value |
| Those Who Defy Fate | Party members joined |
| Airship Enterprise | Airship flag |
| Colosseum leagues | Fights cleared per league |
| Visions Assemble / Will Crystallized | Visions owned (26 total) |
| Awakened Light | Highest vision awakening (max 3) |
| Gil Comes and Goes / Making Lid Proud | Total gil spent and earned |

The remaining achievements are listed but marked "Not in save", because the save only stores internal IDs for them (cave masters, Legendary Arms, Mastery Rank and so on).

The page also remembers your last stagger and Resonance counts in your browser and shows how many you've gained since the previous save you loaded.

## Notes

- Achievement icons and names belong to Square Enix and are shown as they appear on Steam.
- This is a fan-made tool and isn't affiliated with Square Enix or Valve.
