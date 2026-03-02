# Sound Recipe Android - Day 1
**Date:** March 1, 2026

## What We Did Today
- Created the Android project folder structure:
  - `/SoundRecipe/SoundRecipeAndroid/Development` - for the Android Studio project
  - `/SoundRecipe/SoundRecipeAndroid/ClaudeMemory` - for session notes

## iOS App Overview (What We're Porting)
The iOS app "Sound Recipe" does the following:
- Converts Spotify playlists into downloadable spreadsheets
- Emails the spreadsheet to users
- Features: playlist input, email validation, history tracking, subscription paywall (RevenueCat)
- Backend: Firebase (Firestore, Cloud Messaging), Spotify API, Mailboxlayer API

## Key Backend Info
- Backend location: `/SoundRecipe/v2/soundRecipeGoogleCloudLocalTestZone`
- Backend is language-agnostic (REST APIs + Firebase) - will work with Android

## Completed Today
1. Set up Samsung Galaxy phone:
   - Initial setup complete (WiFi, Google account with Sound Recipe Gmail)
   - Skipped Samsung account (signed in via Google to get past it)
   - Display set to auto dark mode (sunset to sunrise)
   - Developer Mode enabled (tapped Build Number 7 times)
   - USB Debugging enabled
   - Connected to Mac via USB-C

## Next Session
1. Open Android Studio and create new project:
   - Template: Empty Activity (Compose)
   - Name: SoundRecipe
   - Package: com.soundrecipe.app
   - Save to: .../SoundRecipeAndroid/Development
   - Language: Kotlin
   - Min SDK: API 24
2. Run "Hello World" on the Samsung phone
3. Start porting Sound Recipe features

## Phone Info
- Samsung Galaxy (refurbished)
- Connected via USB-C to Mac (charges + dev connection)
- Screenshot: Power + Volume Down

## Tools Confirmed
- Android Studio: Installed at /Applications/Android Studio.app
