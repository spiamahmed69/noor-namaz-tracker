# Noor – নামাজ ট্র্যাকার

A premium, mobile-first Islamic Namaz Tracker web app.

Emerald green, white and soft gold design with glassmorphism cards, elegant typography and smooth animations. Fully responsive for Android, iPhone, tablet and desktop.

## Features

- Daily 5 Waqt Namaz Tracker (Fajr, Dhuhr, Asr, Maghrib, Isha) — mark each prayer Completed, Missed, or Pending
- Daily, Weekly and Monthly Namaz Statistics, completion percentage and progress charts
- Monthly Namaz Calendar with prayer history
- Qaza Namaz Tracker
- Live Digital Tasbih Counter (9 dhikrs with targets)
- Daily Islamic Goals and Habit Tracker
- Islamic Quotes and Daily Hadith
- Prayer Time Schedule with location selection (12 cities, Dhaka default, Hanafi Asr)
- Daily Prayer Reminder Notifications
- Hijri and Gregorian Calendar
- Dark Mode and Light Mode
- Offline Support using LocalStorage
- Data Backup and Restore (JSON export / import)
- Beautiful Dashboard with today's date and prayer progress
- Bengali and English language support
- Bottom navigation for mobile
- Installable as a PWA

## How to use

Open `index.html` in any modern browser, or serve it locally:

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

No build step and no server are needed. All data is saved locally in the browser (LocalStorage) on your device. Use Backup in the app to export a JSON copy — clearing browser site data will clear the saved data.

## Prayer times

Prayer times are calculated in the app for the selected city. Verified for Dhaka on 2026-11-18: Fajr 4:58 AM, Dhuhr 11:46 AM, Asr 3:36 PM, Maghrib 5:14 PM, Isha 6:26 PM. Hijri date shown: Jumada II 9, 1448 AH.

## Tech

Single-file HTML, CSS and JavaScript app (`index.html`). No framework or backend required.
