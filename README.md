# Al-Waqt BN

**Prayer Time Widget Tailored for Brunei Darussalam**

Al-Waqt BN is a lightweight desktop widget for Windows that keeps accurate prayer times for Brunei Darussalam always on your screen — no browser tab, no phone in hand. It floats on the desktop, stays out of your way, and updates itself automatically as the day and the calendar move forward.

## Features

**Prayer Times**
- Five daily obligatory prayer times: Subuh, Zohor, Asar, Maghrib, Isyak
- Optional additional times, individually toggleable: Imsak, Syuruk (sunrise), Doha
- Automatic Friday label switch (Zohor → Jumaat/Jumuah)
- Arabic prayer names shown alongside Malay/English labels
- Live countdown and progress bar to the next prayer
- Big always-on digital clock

**Calendar**
- Built-in prayer time calendar covering the full year 2026
- Browse any date via a month-grid date picker, or step day-by-day
- Each day shows its Hijri date alongside all prayer times

**Location**
- District selector for all four districts of Brunei (Brunei-Muara, Tutong, Belait, Temburong), with an interactive clickable map
- Prayer times automatically adjust to the selected district
- Hijri calendar date display
- Manual Hijri offset adjustment (±2 days) for local moon-sighting corrections

**Notifications**
- Windows desktop notifications 10 minutes before and at the start of each prayer
- Separate, independently configurable sounds for the 10-minutes-before reminder and the exact prayer-time notification
- Custom notification sounds — upload your own (mp3/wav/ogg/m4a/aac) for either notification type, choose between them or the built-in default, and delete any you no longer want
- Per-prayer notification on/off toggle

**Customization**
- Malay and English language toggle
- Dark and light theme toggle (with matching sun/moon icon)
- All preferences (district, language, theme, additional prayer times, notification sounds, per-prayer notification toggles, Hijri offset) are remembered between launches

**Widget Behavior**
- Always-on-top floating widget (toggleable from the tray)
- Freely draggable and resizable, with position and size remembered between launches
- Minimizes to the system tray; double-click tray icon to show/hide
- Runs quietly in the background without cluttering the taskbar
- Only one instance runs at a time, even if launched more than once

## Installation

Download the latest installer from the [Releases](../../releases) page — `Al-Waqt BN Setup <version>.exe` — and run it. This adds Al-Waqt BN to your Start Menu and Desktop like any other installed Windows app.

**Auto-start on login (optional):** right-click the app's shortcut → Properties, or drop a shortcut into `shell:startup` (paste that into File Explorer's address bar) so it launches automatically when Windows starts.

**Updating:** quit Al-Waqt BN from the tray ("Quit Al-Waqt BN") before running a newer installer over an existing install, so it isn't still running when the installer tries to replace it.

If you're currently on a build affected by the "stuck on 16 Safar" issue (see Release Notes for v1.0.0-beta.3), updating is strongly recommended — prayer times on that build stop advancing past 31 July 2026.

## Notes

- Preferences and window position/size are saved to a small config file in `%APPDATA%\al-waqt-bn-widget`.
- Uploaded notification sounds are stored in `%APPDATA%\al-waqt-bn-widget\sounds`.

---
Copyright © 2026 Afifi Hidayat Nordin
