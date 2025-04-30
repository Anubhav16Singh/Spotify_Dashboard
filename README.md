# 🎧 Spotify Streaming Behavior Analytics

This project analyzes user listening behavior on Spotify based on detailed event-level data. The dataset includes track metadata, playback interactions, and user session details—ideal for building insights, engagement models, or music recommendation systems.

---

## 📊 Project Highlights

- 🔍 In-depth analysis of listening sessions and playback behavior  
- 🎶 Top artists, tracks, and albums identified from user preferences  
- ⏱️ Skip rates and play duration analysis  
- 🧠 Behavioral insights based on device, shuffle use, and reasons for stopping/starting tracks  
- 📈 Visual dashboards created using tools like Power BI/Tableau  

> 📸 **Screenshots of dashboards and visualizations are included in the repository.**

---

## 🧾 Dataset Fields

| Column Name        | Description |
|--------------------|-------------|
| `spotify_track_uri` | Spotify’s unique track identifier (`spotify:track:<base62>`). |
| `ts` | Timestamp (UTC) when the track stopped, in ISO 8601 format. |
| `platform` | Device/platform used: `desktop`, `mobile`, `web`, `smart_speaker`. |
| `ms_played` | Milliseconds the track was played (e.g., `215000`). |
| `track_name` | Title of the song. |
| `artist_name` | Performing artist’s name. |
| `album_name` | Album the track belongs to. |
| `reason_start` | Trigger for playback: `trackdone`, `clickrow`, `autoplay`, etc. |
| `reason_end` | Reason track stopped: `trackdone`, `fwdbtn`, `logout`, etc. |
| `shuffle` | `TRUE`/`FALSE` — whether shuffle mode was on. |
| `skipped` | `TRUE`/`FALSE` — whether the track was skipped. |

---

## 🔍 Use Cases

- Predict user churn or dropout during playback  
- Identify user preferences by artist, album, or device  
- Analyze session-level behavior (autoplay, shuffle, skips)  
- Create visual storytelling with streaming data  

---

## 📄 License

For educational and non-commercial use only.

---

## 🙌 Acknowledgements

- **Spotify** – for the platform and streaming data structure  
- **DataViz & ML Community** – for tools, libraries, and inspiration  
