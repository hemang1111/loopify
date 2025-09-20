## 🎵 About Loopify  

Loopify is a lightweight **music streaming experiment** I built to practice **Supabase**, **async JavaScript patterns**, and **continuous playback logic**.  

The idea is simple: keep music flowing without interruptions by **fetching and managing batches of tracks in the background**. This way, the player always has fresh songs ready to play — hence the name **Loopify**.  

1. Overview

Loopify is a full-stack music streaming app built with React & Node.js.
It provides a seamless music discovery and playback experience, featuring:

🎧 Infinite Song Playback – keep the music going without breaks.

🎭 Mood-Based Discovery – explore tracks tailored to different moods.

⚡ Background Batch Loading – songs are prepared in advance for smooth playback.

📂 Playlist Management – create, manage, and loop playlists with ease.

🔄 Real-Time Sync – instant updates for an uninterrupted user experience.

🚀 Performance Optimized – fast rendering and low-latency API calls.

2. Tech Stack & Implementation

Frontend:

React.js (functional components + hooks)

Backend:

Node.js + Express.js REST APIs

Optimized batch fetching logic

Secure environment configuration

Core Features & Logic:

Infinite scrolling & lazy loading for tracks

Mood-based song filtering algorithm

Background batch preparation of upcoming songs

Playlist creation, updates, and looping functionality

Additional:

Modular architecture for scalability
Error handling & retry mechanisms for API stability


### ✨ Key Functionalities  
- 🎶 **Continuous Playback** → seamless looping of songs without gaps.  
- 📦 **Batch Preloading** → fetches multiple songs in advance to ensure smooth playback.  
- ⏳ **Queue Management** → maintains a clear separation of the **current batch** and the **next batch**.  
- 🔄 **Auto Replacement** → instantly swaps in the next batch when one ends.  
- ⚡ **Async Operations** → built with `async/await` for clean, non-blocking background tasks.  
- 🔗 **API Integration** → fetches tracks from sources like Pixabay.  
- 🗂 **Scalable Structure** → code allows adding more music providers later.  
- 🧪 **Experimental Playground** → foundation for a future **lo-fi / focus music player**.  


