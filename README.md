# PinterestDL

A simple, fast, and ad-free Pinterest image and video downloader for Android. 

I built this because most Pinterest downloaders on the Play Store are filled with annoying ads, trackers, and terrible UI. PinterestDL is lightweight, uses a pure black AMOLED theme to save battery, and gets the job done without any BS.

## Features

- **AMOLED Black UI:** Clean, dark interface that doesn't blind you at night.
- **Bulk Download:** Search for a topic, and download all loaded images with one tap.
- **4-Column Grid:** Nice grid layout to preview images before downloading.
- **Infinite Scroll:** Loads 50 images at a time. Just keep scrolling.
- **No Ads:** Zero ads, zero trackers. Completely free.
- **Smart Naming:** Saves files automatically as `Sasuke-(Title).jpg` so your gallery doesn't look like a mess.

## How it works

The UI is built with Kotlin and Jetpack Compose. For the backend scraping, instead of relying on a heavy external API, I embedded Python directly into the app using Chaquopy. It uses a Python library to fetch the image URLs, and then Android's native download manager handles the rest.

## Build Instructions

1. Clone the repo:
   `git clone https://github.com/yourusername/PinterestDL.git`
2. Open the project in Android Studio.
3. Let Gradle sync (Chaquopy will take a minute to download the Python dependencies on the first build).
4. Build the APK and install it on your device.

**Note:** The app requires storage permissions to save the downloaded images to your `Pictures/PinterestDL` folder.

## Downloads

You can grab the latest APK from the [Releases](https://github.com/yourusername/PinterestDL/releases) tab.

## Contact

If you find any bugs or have any feature requests, hit me up:
- **Email:** Sasuke.winx@gmail.com
- **Dev:** ѕαѕυкє

## Disclaimer

This is an unofficial third-party app. It is not affiliated with Pinterest. Please respect copyright and only download content for personal use.
