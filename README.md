# 🎶 myTunes - JavaFX Music Player

A desktop-based music player application built with **JavaFX** and **MongoDB**, designed to offer iTunes-like features including song playback, playlist management, and song library interaction.

---

## 📖 Overview

**myTunes** is a sleek and interactive music player developed using **Java** and **JavaFX**, with **MongoDB** used for persistent storage of song and playlist data.  
The application replicates core iTunes functionality, allowing users to:

- 🎧 Play songs  
- 🗂 Create and manage playlists  
- 🕹 Control playback using intuitive UI elements like Play, Pause, Skip, and Volume

---

## 🚀 Features

- **🎨 Modern UI with JavaFX**: Visually engaging and responsive interface designed with JavaFX  
- **💾 MongoDB Integration**: Stores user-added songs and playlists persistently using MongoDB  
- **🎵 Song Playback**: Supports MP3 playback with standard controls — Play, Pause, Stop, Next, and Previous  
- **📁 Playlist Management**: Users can create, delete, and manage custom playlists  
- **📂 Song Library**: Add songs from your local system to the application’s database  
- **🔄 Dynamic UI Components**: Real-time UI updates for playlists and song additions  
- **🔊 Volume Control & Seek Bar**: Smooth audio control and song tracking

---

## ⚙️ How It Works

- **📦 Song Storage**: Songs added by the user are saved into the MongoDB database along with metadata  
- **🧠 Playlist Logic**: Playlists are dynamically created and linked to song entries in the database  
- **🖥 JavaFX UI**: Provides an interactive layout for users to browse, control, and manage their music  
- **🎧 Media Handling**: Utilizes JavaFX’s `Media` and `MediaPlayer` classes to support MP3 playback  
- **🔐 Data Persistence**: All changes (songs, playlists) are retained across sessions via MongoDB
