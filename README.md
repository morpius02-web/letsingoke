# 🎤 LetSingOke

A modern karaoke player for Android. Sing along with your own song files, search karaoke videos on YouTube, get scored on your pitch, challenge a friend in Battle Mode, and record your performance with video and lyrics.

**Current version:** 4.3.0

---

## ✨ Features

### Karaoke
- Karaoke player with synced lyrics, countdown, and adjustable lyric font and shadow
- Built-in song library, with song search and a song book
- Background visuals: videos, photos, or your camera
- Scoring with **Easy / Medium / Hard** difficulty, **Random** or **Microphone** score mode, and fanfare sounds

### 🎬 YouTube Oke
Search karaoke videos on YouTube and queue them up. Reserve songs, reorder or clear the queue.

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

### 🎵 Guess Song
A guessing game hub that also links to the Pitch Guide and Battle Mode.

### 🎙 Mic and Sound
- Live mic with voice effects (echo, reverb, clarity) and anti-feedback
- Pick your input: built-in, wired, USB / 2.4 GHz, or Bluetooth
- Sound Engine settings

### 📹 Recording
Record yourself singing with the camera, the backing track, and the lyrics overlay. If the live mic channel is silent, the app falls back to the mic so your voice always makes it into the recording.

### 📱 Web Remote
Control the app from a phone or any browser on the same network, and use your phone as a wireless mic.

### 📺 TV friendly
Works with remote and D-pad navigation on Android TV.

### 🔄 Updates
The app checks `manifest.json` in this repository for new versions. Use **Settings → Check for a newer version of LetSingOke**.

---

## 📲 Install

1. Download the latest APK [LetSingOke](https://github.com/morpius02-web/letsingoke/releases/download/V4.3.0/LetSingOke.v4.3.0.apk).
2. On your phone, allow **Install unknown apps** for your browser or file manager.
3. Open the APK and install.
4. Open the app and go to settings and download the LetSingOke assets files.

**Requires:** Android 6.0 (API 23) or higher.

## 🔐 Permissions

| Permission | Why |
|---|---|
| Microphone | Singing, pitch guide, recording |
| Camera | Camera background and video recording |
| Storage / Media (audio, video, images) | Your song files and saved recordings |
| Internet / Wi-Fi / Nearby devices | YouTube Oke, Web Remote, updates |
| Bluetooth | Wireless mics and headsets |
| Notifications / Foreground service | Keeps the app running during playback and remote sessions |
| Install packages | Installing updates |

## 🛠 Tips

- **Song leaks into the mic?** Lower the speaker volume or use a headset or wireless mic.
- **Wrong octave on the pitch bar?** Keep Octave-forgiving on in the Pitch Guide options.
- **No voice in a recording?** Check that the microphone permission is allowed, then try again.

## 🧱 Build

The project is a decoded APK (apktool). To rebuild:

```bash
apktool b <project-folder> -o LetSingOke-4.3.0.apk
# then zipalign and sign with your own keystore
```

## 🙏 Credits

- [BASS](https://www.un4seen.com/) audio library (un4seen), used for playback and MIDI. Check its license for your use case.
- [Java-WebSocket](https://github.com/TooTallNate/Java-WebSocket)
- [Conscrypt](https://github.com/google/conscrypt)
- [Jipe Spd](https://www.facebook.com/jpdcs2001)
## ⚠️ Notes

- YouTube Oke content is provided by YouTube. Use it in line with YouTube's Terms of Service.
- Please respect the copyright of the songs and videos you use.
