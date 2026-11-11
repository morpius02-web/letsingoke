# 🎤 LetSingOke

A modern karaoke player for Android. Sing along with your own song files, search karaoke videos on YouTube, get scored on your pitch, challenge a friend in Battle Mode, play music mini games, watch movies and live TV, and record your performance with video and lyrics.

**Current version:** 4.4.2

---

## ✨ Features

### Karaoke
- Karaoke player with synced lyrics, countdown, and adjustable lyric font and shadow
- Built-in song library, with song search, new songs, rankings, and a song book
- Add your own songs and files by importing them
- Singer 1 / Singer 2 modes for duets
- Tempo, key, and lyric-sync adjustments during playback
- Background visuals: videos, photos, or your camera
- Scoring with **Easy / Medium / Hard** difficulty, **Random** or **Microphone** score mode, and fanfare sounds
- Optional downloads: prebuilt songs, background photos, background videos, and soundfonts

### 🎬 YouTube Oke
Search karaoke videos on YouTube and queue them up.
- Queue, queue all, play next, skip, reorder, or clear the queue
- **Fair turns** mode rotates singers in the queue
- Favorites and saved playlists
- Backup code to copy and restore your data

### 🍿 Movie Oke
Browse, search, and watch movies and TV series.
- Trending, Movies, TV Series, and Downloads tabs
- **Continue Watching**: picks up where you stopped, with a Resume button and a progress bar
- Series remember your last episode and move on to the next one
- Subtitles, playback speed, quality selection, and episode picker
- **Scale option** in the player menu: Fit, Fill, or Stretch to your screen
- Download titles for offline viewing
- Fast, smooth browsing with instant loading from the last session and prefetching of details
- **Faster first open:** Movie Oke is warmed up in the background shortly after the app starts
- Full remote and D-pad support on TV

### 📺 IPTV Oke
Watch live channels with a country filter and full-screen playback.

### 🌐 Stream Oke
Watch streamed video inside the app.

### 🎮 Oke Arcade
Four music mini games, each playable on phone, tablet, and TV.
- **Guess Song:** name the tune
- **Beat Drop Oke:** a rhythm game for 1 or 2 players, Easy to Turbo difficulty, with Auto mode and a tutorial
- **Pulse Oke:** a touch rhythm game with Easy to Fast difficulty, random song, and a tutorial
- **Pitch Perfect:** match the pitch, practice a specific part, or sing the full song
- Beat Drop Oke and Pulse Oke can be controlled from your phone using the Web Remote

### 🎯 Pitch Guide
A scrolling pitch bar shows the melody notes and your voice in real time.
- Octave-forgiving mode, so you can sing in your own octave
- Handles key shift (transpose)
- Mic is tuned to pick up your voice over the backing track (echo cancellation, noise suppression, adaptive noise gate)

### ⚔ Battle Mode
Two singers, one song, one turn each. The higher score wins.
- Enter both singers' names
- "You're up!" screen before each turn
- Result screen with winner, point margin, and Perfect / Good / Miss / Max combo
- Series tracker, rematch (swaps who sings first), or a new random song
- Open it from the Guess Song hub

### 🎙 Mic and Sound
- Live mic with voice effects (echo, reverb, clarity) and anti-feedback
- Pick your input: built-in, wired, USB / 2.4 GHz, or Bluetooth
- Sound Engine with soundfont support and an equalizer
- Mic check and live concert mode

### 📹 Recording
Record yourself singing with the camera, the backing track, and the lyrics overlay. If the live mic channel is silent, the app falls back to the mic so your voice always makes it into the recording.

### 🔗 Share Center
Share built-in songs, your own songs, your Song Book, and your video records. Shown on TV and set-top boxes.

### 📱 Web Remote
Control the app from a phone or any browser on the same network, and use your phone as a wireless mic.
- Browse songs, reserve them, and play now
- Control mic volume, tempo, and lyric timing
- Use the phone keyboard to type searches on a TV or box
- Generate a Song Book from your selected songs

### 📺 TV friendly
Works with remote and D-pad navigation on Android TV, TV boxes, and projectors. Devices without a touchscreen are treated as a TV automatically.

### 🔄 Updates
The app checks `manifest.json` in this repository for new versions. Use **Settings → Check for a newer version of LetSingOke**.

---

## 📲 Install

1. Download the latest APK [LetSingOke](https://github.com/morpius02-web/letsingoke/releases/download/v4.4.2/LetSingOke.v4.4.2.apk).
2. On your phone, allow **Install unknown apps** for your browser or file manager.
3. Open the APK and install.
4. Open the app and go to settings and download the LetSingOke assets files.

**Requires:** Android 6.0 (API 23) or higher. About 2 GB of RAM is recommended; 3 GB or more is best for Movie Oke and the soundfont engine.

## 🔐 Permissions

| Permission | Why |
|---|---|
| Microphone | Singing, pitch guide, recording |
| Camera | Camera background and video recording |
| Storage / Media (audio, video, images) | Your song files, downloads, and saved recordings |
| Internet / Wi-Fi / Nearby devices | YouTube Oke, Movie Oke, IPTV, Web Remote, updates |
| Bluetooth | Wireless mics and headsets |
| Notifications / Foreground service | Keeps the app running during playback and remote sessions |
| Install packages | Installing updates |

## 🛠 Tips

- **Song leaks into the mic?** Lower the speaker volume or use a headset or wireless mic.
- **Wrong octave on the pitch bar?** Keep Octave-forgiving on in the Pitch Guide options.
- **No voice in a recording?** Check that the microphone permission is allowed, then try again.
- **Movie Oke search not working?** Check your internet connection and the device date and time, then try again.
- **Video does not fill the screen?** Open the player menu and change **Scale** to Fill or Stretch.

## 🧱 Build

The project is a decoded APK (apktool). To rebuild:

```bash
apktool b <project-folder> -o LetSingOke-4.4.2.apk
# then zipalign and sign with your own keystore
```

## ❤️ Support the Project

LetSingOke is free. If you enjoy the app, any amount of support helps keep it free and updated. Maraming salamat!

<p align="center">
  <img src="https://github.com/morpius02-web/letsingoke/releases/download/assets/gcash_qr.png" alt="GCash donation QR code" width="280">
</p>

Open GCash on your phone, tap **Scan QR**, scan this code, and enter any amount. You can also take a screenshot of the QR and use **Upload QR** in GCash. You can open this same QR in the app with the **Support me** button.

## 💬 Contact and Updates

Follow the developer on Facebook for news, updates, and support: [JKRapada02](https://www.facebook.com/JKRapada02/)

## 🙏 Credits

- [BASS](https://www.un4seen.com/) audio library (un4seen), used for playback and MIDI. Check its license for your use case.
- [Java-WebSocket](https://github.com/TooTallNate/Java-WebSocket)
- [Conscrypt](https://github.com/google/conscrypt)
- [Jipe Spd](https://www.facebook.com/jpdcs2001)

## ⚠️ Notes

- YouTube Oke content is provided by YouTube. Use it in line with YouTube's Terms of Service.
- Movie Oke and IPTV Oke content comes from third-party sources. Availability can change, and you are responsible for using it in line with the laws and terms that apply to you.
- Please respect the copyright of the songs and videos you use.
