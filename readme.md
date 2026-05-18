
> [!IMPORTANT] 
> <br>
>  **Status:** 🚧 Under Construction 
> 

## 🔤 What does VIO mean?
VIO = Vibrancy + Input + Output

Sound (Input) generates a visual vibration (Output) that the user perceives through colors and reactive lighting (Vibrancy). It's music you don't just hear — you see it.

## 🚀 About the Project
VIO is more than an audio player, it's an immersive music management ecosystem. The goal is to combine data intelligence with a reactive visual interface, creating an experience where each track is felt as much as it's heard.
The project was born from the need to apply advanced front-end concepts:  glassmorphism, reactive animations, dynamic state management and lay the foundation for a robust full-stack architecture.

## ✨ Features

# 🎨 Interface

* **Visual Card Grid** — Replaces text lists with depth-effect cards and smooth hover animations
* **Real-Time Overlays** — Tracks display artist, title, and duration via translucent, animated overlays
* **Seamless Tab Navigation** — Switch between Library, Favorites, and Stats without page reloads
* **Dark Mode** — Toggleable via the smart profile menu
* **Glassmorphism UI** — Frosted-glass aesthetic throughout the interface
  
&nbsp;
#🎵 Player

* **Dynamic Playlist** — Full queue control with "Play Now" or "Add to Queue" options via contextual pop-ups
* **Favorites System** — Algorithm that separates and organizes user-marked tracks
* **Visual Audio Engine** — Ambient lighting that reacts to sound frequencies (Reactive LED UI)
* **Vinyl Animation** — Rotating disc visual synced to playback state
  
&nbsp;
#📊 Data & Auth (planned)

* **Consumption Metrics** — Most-played tracks, listening history based on behavior
* **User Authentication** — Login system to persist playlists and preferences per user
* **Data Persistence** — PostgreSQL database for music catalog, profiles, and stats
* **Loading Optimization** — Architecture built to handle large libraries without performance loss

---

<div align="center">

<h2>🛠️ Tech Stack</h2>

<table width="600">
  <tr>
    <th>Front-end</th>
    <th>Back-end</th>
    <th>Database</th>
  </tr>

  <tr>
    <td>
      <img src="https://skillicons.dev/icons?i=html,css,js,react" />
    </td>
    <td>
      <img src="https://skillicons.dev/icons?i=nodejs,expressjs" />
    </td>
    <td>
      <img src="https://skillicons.dev/icons?i=postgresql" />
    </td>
  </tr>
</table>

</div>

---

## 📂 Folder Organization
<pre>
  VIO/
  ├── client/
  │   ├── index.html          # Main entry point
  │   ├── assets/             # Images, icons, and audio files (.mp3)
  │   ├── css/
  │   │   ├── global.css      # CSS reset and color variables (neon/purple theme)
  │   │   ├── layout.css      # Sidebar and PlayerBar styles
  │   │   └── components.css  # Card styles and glassmorphism effects
  │   └── js/
  │       ├── main.js         # Screen/tab switching coordinator
  │       ├── player-logic.js       # Play/pause logic and progress bar
  │       └── ui-effects.js   # Vinyl animation and hover effects
  ├── server/                 # Reserved — Node.js + Express (planned)
  └── database/               # Reserved — PostgreSQL scripts (planned)
</pre>

---

## 🗺️ Roadmap

| Complete | In  Progress | Planned  
| :---: | :---: | :---: | 
| 🟢 | 🟡 | ⚪ |


### 🟡 Phase 01 — Interface Foundation
> Build the visual and interactive soul of VIO before anything else.

- [x] Card grid with depth and hover animations
- [x] Real-Time Track Overlays
- [ ] Seamless Tab Navigation (Library / Favorites / Stats)
- [x] Responsive layout structure
- [x] Dark mode & glassmorphism


### 🟡 Phase 02 - PLayback Experience
> Transform the interface into a living music environment.
- [ ] Dynamic Playlist and queue management
- [ ] Contextual pop-up actions (Play Now / Add to Queue)
- [ ] Favorites System for personalized organization
- [ ] Visual Audio Engine - Reactive LED UI
- [ ] Playback synchronization and state handling

      
### ⚪ Phase 03 — Intelligence  & Persistence
> Give VIO a memory. Connect the interface to real data.

- [ ] Back-end API architecture
- [ ] PostgreSQL database integration
- [ ] User Authentication and persistent sessions
- [ ] Listening history and consumption metrics
- [ ] User profile and preference persistence
- [ ] Scalable data structure for large music libraries


### ⚪ Phase 04 — Optimization & Deployment
> Take VIO from localhost to the world.

- [ ] Front-end deployment on Vercel
- [ ] Back-end deployment on Railway or Render
- [ ] Asset performance optimization
- [ ] Playback performance optimization
- [ ] Cross-device responsiveness validation
- [ ] Production environment configuration

---

<div align="center">
  <h3>📬 Contact me</h3>

  <p>Made by Davi — feel free to reach out or connect.</p>

  <a href="mailto:davibc2018@gmail.com">
    <img src="https://img.shields.io/badge/-Gmail-%23333?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>

  <a href="https://www.linkedin.com/in/davi-carvalho-dev/" target="_blank">
    <img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>

  <a href="https://discord.com/users/695431975175061505" target="_blank">
    <img src="https://img.shields.io/badge/Discord-7289DA?style=for-the-badge&logo=discord&logoColor=white"/>
  </a>
</div>

---

<div align="center">
  <sub>VIO — because music should be seen, not just heard.</sub>
</div>
