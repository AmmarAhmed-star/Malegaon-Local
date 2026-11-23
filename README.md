# My City Business Finder App

**Live Demo:** https://ammarahmed-star.github.io/Malegaon-Local/  
**Platform:** Android + Web Showcase  
**Theme:** Dark Premium - #0C0A14 + #10B981 Neon  
**Developer:** Ammar Ahmed

## Overview
Professional local business discovery platform for Malegaon. Find Kirana Stores, Medical Shops, and Mobile Repair Services with direct call, WhatsApp, and map integration.

## Features
- Business directory with 8 categories
- Live search by name and area
- Category filter chips
- Direct call intent
- WhatsApp messaging intent
- Google Maps navigation intent
- Add business functionality
- Offline-first with Room database
- Firebase Firestore backend

## Focus Categories (1, 2, 3)
1. Kirana Store
2. Medical Shop
3. Mobile Repair

Additional: Electrician, Plumber, Tailor, Restaurants, Coaching

## Technology Stack
- Kotlin - 58% - Main logic
- Java - 18% - Utilities
- XML - 16% - Layouts
- Firebase Firestore - Real-time database
- Firebase Auth - Business owner authentication
- Room Database - Offline caching
- Google Maps Intent - Location navigation
- HTML/CSS/JavaScript - Showcase website

## UI Design
- Background: #0C0A14 (Dark Black)
- Card: #1A1628 with border #1F2937
- Primary: #10B981 (Green) + #06B6D4 (Cyan)
- Neon glow: 0 0 18px rgba(16,185,129,.45)
- Glass morphism: backdrop-filter blur 16px
- High visibility buttons with 2px borders

## Project Structure
```
app/src/main/
├── java/com/malegaonlocal/
│   ├── MainActivity.kt
│   ├── Shop.kt (data class)
│   ├── ShopAdapter.kt
│   └── ShopDao.kt (Room)
├── res/layout/
│   ├── activity_main.xml
│   └── item_shop.xml
├── res/values/
│   ├── colors.xml
│   └── themes.xml
└── res/drawable/
    └── bg_input.xml
```

## Build Instructions
1. Open in Android Studio
2. Add google-services.json for Firebase
3. Gradle Sync
4. Run on device or emulator
5. Build APK: Build > Build APK(s)

## License
MIT - Ammar Ahmed - 2026
