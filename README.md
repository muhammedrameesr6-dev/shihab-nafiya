# Muhammad Shihab & Nafiya Rizwana — The Wedding

A complete, elegant, and interactive wedding invitation website for **Muhammad Shihab & Nafiya Rizwana**, cloned and customized from [ruban-athulya.vercel.app](https://ruban-athulya.vercel.app/).

---

## 💍 Wedding & Event Details

- **Groom**: Muhammad Shihab
  - **Father**: Mr. Sulaiman Thudimmal
  - **Mother**: Mrs. Suhara Pattappurath
  - **Family House**: Thudimmal House, Irimbiliyam, Malappuram, Kerala

- **Bride**: Nafiya Rizwana
  - **Father**: Mr. Sharafudheen Pari
  - **Mother**: Mrs. Ayishabi Mandayappuram
  - **Family House**: Pari House, Irimbiliyam, Malappuram, Kerala

### 📅 Schedule of Events
1. **Nikah Ceremony**
   - **Date**: Friday, 25 December 2026
   - **Time**: 6:00 PM IST
   - **Venue**: Ideal International School, Irimbiliyam, Malappuram, Kerala
   - [Google Maps Location](https://www.google.com/maps/search/?api=1&query=Ideal+International+School%2C+Irimbiliyam%2C+Kerala)

2. **Wedding Reception**
   - **Date**: Monday, 28 December 2026
   - **Time**: 4:00 PM onwards
   - **Venue**: Ideal International School, Irimbiliyam, Malappuram, Kerala
   - [Google Maps Location](https://www.google.com/maps/search/?api=1&query=Ideal+International+School%2C+Irimbiliyam%2C+Kerala)

---

## 📁 Project Structure

```
shihal & nafiya/
├── index.html                       # Complete wedding invitation website
├── og-thumb.png                     # WhatsApp / social preview thumbnail
├── wedding-card.jpg                 # Printable / downloadable invitation card
├── README.md                        # Documentation
└── assets/
    ├── hero-clouds-sound.mp4        # Hero video film background with audio
    ├── wedding-bgm.mp3              # Background instrumental music
    ├── cover-couple.jpg             # Invitation cover photo
    ├── bg-clouds-deep.jpg           # Background clouds texture
    ├── bg-clouds-soft.jpg           # Background soft texture
    ├── bg-pattern.jpg               # Background pattern texture
    ├── library.js                   # 37-track curated wedding music library
    ├── gallery/                     # Photo gallery (14 images)
    │   ├── gallery-01.jpg ... gallery-14.jpg
    └── vendor/                      # Offline vendor dependencies
        ├── firebase-app-compat.js
        ├── firebase-database-compat.js
        ├── html2canvas.min.js
        └── jspdf.umd.min.js
```

---

## 🚀 How to Run & Preview Locally

Open [`index.html`](index.html) directly in your browser, or launch a local web server:

```bash
# Using Python:
python3 -m http.server 3000
```
Then visit: [http://localhost:3000](http://localhost:3000)

---

## ✨ Features Included

1. **Gate Envelope Screen**: Traditional curtain reveal with Arabic Bismillah (`بِسْمِ ٱللَّٰهِ ٱلرَّحْمَٰنِ ٱلرَّحِيمِ`) and "Open Invitation" action.
2. **Falling Petals Animation**: Canvas-driven floral petal animation.
3. **Hero Film Section**: Autoplaying cinematic background film with ambient audio controls.
4. **Interactive BGM Player**: Floating music player with volume toggle, loop, and track selection from the built-in library.
5. **Sacred Verses & Blessings**:
   - Quranic Verse: Surah Ar-Rum (30:21) with Arabic Bismillah.
   - Prophetic Blessing: Sunan Abi Dawud (*"Barakallahu laka wa baraka 'alayka..."*).
6. **Live Countdown Timer**: Realtime countdown targeting the Nikah Ceremony on 25 December 2026 at 6:00 PM.
7. **Event Schedule Cards**: Nikah and Reception cards with direct Google Maps integration and one-click "Add to Google Calendar" button.
8. **Family Details Section**: Groom's and Bride's family blocks with parent names and family houses.
9. **Photo Gallery & Lightbox**: Responsive masonry grid with full-screen viewer supporting keyboard arrow keys and touch gestures.
10. **RSVP & Guest Wishes Wall**: Realtime guestbook powered by Firebase with privacy locking for the couple.
11. **Invitation Download**: One-click download as high-resolution invitation card image or formatted PDF.
12. **Owner / Admin Login**: PIN `2026SN` (or password `SHIHAB`, `NAFIYA`, `2026`) to unlock wishes and access admin controls.

---

## 🎨 Color Palette & Theme

- **Sage Green**: `#484932` (Primary Dark Accent, Headings, Buttons, Badges, Borders)
- **Warm Ivory**: `#F2E5D0` (Paper Background, Cards, Light Highlights, Form Bed)
- **Antique Gold**: `#A68038` / `#E0C68D` (Sacred Calligraphy, Monograms, Ornaments)
