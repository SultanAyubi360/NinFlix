<div align="center">

<!-- Banner -->
<img src="https://i.ibb.co/wpmd3ZT/logo.png" height="180" />
<br>

<img src="https://i.postimg.cc/HnL7y8y1/Screenshot-2025-11-12-181024.png" height="800" />


# 🎬 NinFlix – Live Streaming & OTT Android App

![Java](https://img.shields.io/badge/Built%20with-Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Kotlin](https://img.shields.io/badge/Also%20Uses-Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)
![Firebase](https://img.shields.io/badge/Powered%20by-Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![Stars](https://img.shields.io/github/stars/SultanAyubi360/NinFlix?style=for-the-badge&color=brightgreen)
![Android](https://img.shields.io/badge/Platform-Android-green?style=for-the-badge&logo=android&logoColor=white)

</div>

---

**NinFlix** is a powerful, feature-rich **live streaming and on-demand entertainment platform** built for Android.  
It provides seamless access to **Movies, Series, Animes, and Live TV Channels**, all managed through a robust **Admin Panel** that controls content, users, and updates in real time.

---

## 🌟 Key Highlights
- 🎥 Stream **Movies, Series, Animes & Live TV**
- ⚙️ Fully functional **Admin Panel**
- 📲 Optimized for **Android SDK 16+**
- 💾 Lightweight native libraries (~16 KB)
- 🧩 Supports **HD, Full HD, and 4K** content streaming
- 🧠 Built using modern **Android Jetpack** components
- 🔒 Secure, scalable, and Firebase-powered backend

---

## 🎬 Video Quality & Playback
NinFlix ensures smooth, adaptive streaming across multiple quality levels for every type of content:

| Quality Level | Resolution | Use Case |
|----------------|-------------|-----------|
| **SD (480p)** | Standard Definition | Low bandwidth or mobile data |
| **HD (720p)** | High Definition | Default for most users |
| **Full HD (1080p)** | Crisp clarity | Recommended for stable Wi-Fi |
| **4K UHD** | Ultra HD | Premium users & smart devices |

🎧 Audio and video automatically adapt based on network speed using **adaptive bitrate streaming (HLS, DASH)**.  
NinFlix also supports **DRM-protected content (Widevine, ClearKey)** for secure premium playback.

### 📂 Supported Media Formats
NinFlix supports a wide variety of video formats:

- **Video Files:** MP4, MOV, MKV, WebM, TS  
- **Streaming Formats:** HLS (.m3u8), DASH (.mpd), Smooth Streaming (.ism)  
- **Private / Custom MediaItems:** Handled via `buildMediaItem(String url)` for secure playback  

---

## 🧑‍💼 Admin Panel Features
The **Admin Dashboard** provides complete control over every aspect of the Ninflix platform:

- ➕ **Add / Update / Delete** – Movies, Series, Animes, TV Channels, Seasons, Episodes, and Cast Members  
- 🧠 **Manage** – Content metadata, thumbnails, multi-quality links, user accounts, subscriptions, and activity logs  
- 📡 **Notifications** – Send instant updates or error reports (e.g., not working channels) and receive admin alerts in real time  
- 🔧 **Analytics** – Track active users, watch history, and download statistics  

---

## 📱 User App Features
- 🎞️ Watch **Movies, Series, Animes, and Live TV**
- 🔑 **Authentication & Profile**
  - Login and Signup via Email / Firebase Auth
  - Forgot Password support
  - Add or update **Profile Image**
  - Set or edit **Bio / About Me**
- 💾 Download content for offline viewing (Foreground Download Service)
- ❤️ Add or remove **Favorites** (Movies, Series, Casts)
- ⏯️ **Continue Watching** – resume playback anytime
- 🔢 Choose between multiple streaming **qualities (SD / HD / 4K)**
- 🌐 Play from **embedded sources** (Dailymotion, Okru, MediaFire, etc.)
- 🔔 Receive **custom notifications** from Admin
- 🧭 In-app **network availability & VPN protection**
- 🪶 Lightweight and **battery-optimized**
- 🌗 **Dark / Light mode** theme support
- 🧩 Smooth animations and material transitions

---

## 🧰 Core Technologies
- **Kotlin + Java**  
- **ExoPlayer** for adaptive HLS / DASH streaming  
- **Firebase Suite** (Auth, Firestore, Realtime Database, Storage, Functions, FCM, Crashlytics, Analytics)  
- **Fetch2** for downloads  
- **Glide** for image loading  
- **OAuth2 + Firestore** for custom notifications and admin control  
- **Material Design 3** for clean, modern UI  

---

## ⚡ Performance & Optimization
- 🚀 Built with **Android SDK 16+** and **NDK r29**
- 🧠 Optimized for **speed and memory efficiency**
- 🔒 **ProGuard** and **resource shrinking** enabled
- 🔋 Minimal CPU load during playback and background downloads
- 💬 Handles **network interruptions** gracefully with automatic reconnection

---

## 🔒 Security
- DRM support (**Widevine, ClearKey**) for premium content
- Firebase authentication and user verification
- Scoped storage and runtime permission handling
- VPN usage detection for secure streaming
- Foreground service with controlled background tasks

---

## 📸 Screenshots

### 📱 User App Screenshots
*(Show screenshots of user app UI: movies, series, player screen, favorites, download manager, etc.)*  
<img src="https://i.ibb.co/album/user-screenshot1.png" width="300" />
<img src="https://i.ibb.co/album/user-screenshot2.png" width="300" />
<img src="https://i.ibb.co/album/user-screenshot3.png" width="300" />


---

### 🧑‍💼 Admin App Screenshots
<kbd>
<table>
  <tr>
    <td align="center"><b>Dashboard</b><br><br><img src="https://i.ibb.co/JWzgD03Q/1.jpg" width="230"/></td>
    <td align="center">&nbsp;</td>
    <td align="center"><b>Tools</b><br><br><img src="https://i.ibb.co/tTQf5Y8C/2.jpg" width="230"/></td>
    <td align="center">&nbsp;</td>
    <td align="center"><b>Channels</b><br><br><img src="https://i.postimg.cc/qRQ3bKdG/3.jpg" width="230"/></td>
  </tr>

  <tr>
    <td colspan="5" align="center">&nbsp;</td>
  </tr>

  <tr>
    <td align="center"><b>Tv Tools</b><br><br><img src="https://i.ibb.co/XfjwvQW2/4.jpg" width="230"/></td>
    <td align="center">&nbsp;</td>
    <td align="center"><b>Delete Movie/Serie</b><br><br><img src="https://i.ibb.co/Kp3k0Hp4/5.jpg" width="230"/></td>
    <td align="center">&nbsp;</td>
    <td align="center"><b>Delete Channel</b><br><br><img src="https://i.ibb.co/Vcsddb1g/6.jpg" width="230"/></td>
  </tr>

  <tr>
    <td colspan="5" align="center">&nbsp;</td>
  </tr>

  <tr>
    <td align="center"><b>Add Channel</b><br><br><img src="https://i.ibb.co/hFxqbW0X/7.jpg" width="230"/></td>
    <td align="center">&nbsp;</td>
    <td align="center"><b>Categories & Add New</b><br><br><img src="https://i.ibb.co/ZpRypBt8/8.jpg" width="230"/></td>
    <td align="center">&nbsp;</td>
    <td align="center"><b>Countries & Add New</b><br><br><img src="https://i.ibb.co/8DdH0Tdx/9.jpg" width="230"/></td>
  </tr>
  
  <tr>
    <td colspan="5" align="center">&nbsp;</td>
  </tr>

  <tr>
    <td align="center"><b>Channels Category Wise</b><br><br><img src="https://i.ibb.co/67XpWNc6/10.jpg" width="230"/></td>
    <td align="center">&nbsp;</td>
    <td align="center"><b>Add New Category</b><br><br><img src="https://i.ibb.co/6R3zF7CB/14.jpg" width="230"/></td>
    <td align="center">&nbsp;</td>
    <td align="center"><b>Update & Delete Category</b><br><br><img src="https://i.ibb.co/tMKw0kFs/13.jpg" width="230"/></td>
  </tr>

   <tr>
    <td colspan="5" align="center">&nbsp;</td>
  </tr>

  <tr>
    <td align="center"><b>Add New Country</b><br><br><img src="https://i.ibb.co/sdZxZYrm/11.jpg" width="230"/></td>
    <td align="center">&nbsp;</td>
    <td align="center"><b>Update & Delete Country</b><br><br><img src="https://i.ibb.co/fzn2d3Ff/15.jpg" width="230"/></td>
    <td align="center">&nbsp;</td>
    <td align="center"><b>Not Working Channels</b><br><br><img src="https://i.ibb.co/gL68dqzL/12.jpg" width="230"/></td>
  </tr>
  
</table>
</kbd>

---

## 📊 Analytics & Monetization
- Real-time **usage tracking** via Firebase Analytics  
- **Crashlytics** for error monitoring  
- Optional **StartApp Ads SDK** for revenue generation  

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-------------|
| **Language** | Kotlin + Java |
| **Player** | ExoPlayer (HLS, DASH, DRM) |
| **Backend** | Firebase (Firestore, Storage, Realtime DB, Auth, Functions) |
| **Networking** | OkHttp, Fast Android Networking, Jsoup |
| **Image Loading** | Glide |
| **Download Manager** | Fetch2 |
| **UI / UX** | Material 3, Lottie, CircleImageView, SwipeRevealLayout |
| **Analytics & Crash Reporting** | Firebase Analytics, Crashlytics |
| **Notifications** | Firebase FCM + Custom Foreground Handling |
| **Monetization** | StartApp In-App Ads SDK |
| **Authentication** | Google OAuth2 Library |

---

## 💬 Contact
**Developer:** [Sultan Ayubi](mailto:sultanayubi360@gmail.com)  
**GitHub:** [github.com/SultanAyubi360](https://github.com/SultanAyubi360)

---

## :heart: Support My Projects  

However, if you get some profit from this or just want to encourage me to continue creating stuff, there are few ways you can do it. ☕ 🍔 🍟 🍎  

 **Starring:** You may give a star ⭐ or share the projects you like.

### Find this useful? ❤️

Support it by joining the stargazers for this repository. ⭐  
Also, [follow me on GitHub](https://github.com/SultanAyubi360) for my next creations! 🤩

---

 🎥 *NinFlix – Stream everything, anywhere, anytime.*

