# 🎧 Voxen — Lightweight Synced Lyrics Editor

Voxen is a **fast, lightweight, and no-install** tool for creating **synced lyrics** with both **line-by-line** and **word-by-word** timing support. It’s built as a **single HTML file**, so it runs **entirely in your browser**—on **PC and mobile**—with no setup required.

Just drop in your **MP3**, paste your lyrics, and start syncing. Simple as that.

---

## 🌐 Try It Online

If you don’t want to download the HTML file, you can use the web version instead:

🔗 **[Voxen Sync Online](https://raqhael-ux.github.io/Voxen-Advanced-LRC-Editor-Word-by-word-/)**

> 📱 **Mobile note:** On Chrome mobile, the header UI may get cut off during editing. For a smoother experience, consider using a web-wrapper app like **Weblo**.

---

## Screenshots :

<div style="display: flex; gap: 10px;">
  <img src="https://cdn.discordapp.com/attachments/1344634704946528287/1456175876952821992/Screenshot_20260101-1441572.png?ex=695768f7&is=69561777&hm=60654e1624c397c0d43417c3f72418dbb735fa4e08954cb872bf68f3bf582485" alt="Android" width="150"/>
  <img src="https://cdn.discordapp.com/attachments/1344634704946528287/1456174371545551030/image.png?ex=69576790&is=69561610&hm=d13db4089a49ec4d5fd95b46c7d13151378ae1d12c2c7e636277d2a5244344d2" alt="Windows" width="560"/>
</div>

---

## ✨ Features

* 🎯 **Word-level lyric timing** (perfect for karaoke-style effects)
* 📝 **Line-by-line syncing mode**
* ➕ Add, remove, or modify lyric lines
* 🌍 Runs **fully in the browser**
* 💾 Works **locally** (no internet required after loading)
* 📤 **Export to LRC** format
* 📁 **Import & export projects** as JSON
* ⏱️ **Reaction Offset** support for timing adjustments

---

## 🚧 Planned Features

* ~~Bulk offset modification~~
* ~~Improved lyrics text editor~~
* ~~Import LRC~~
* Built-in preview mode (maybe)

---

## 🛠️ Usage Guide

1. From the **left-side panel**, upload your **MP3** file.
2. Paste the **plain lyrics** of your song.
3. Choose your preferred syncing mode:

### ▸ Line Mode

Syncs lyrics **line-by-line**.

```
(mm:ss:xx) For you I'd bleed myself dry
```

### ▸ Word Mode

Syncs lyrics **word-by-word** for precise timing.

```
<for:ss.xx:ss.xx|you:ss.xx:ss.xx|I'd:ss.xx:ss.xx|bleed:ss.xx:ss.xx|myself:ss.xx:ss.xx|dry:ss.xx:ss.xx>
```

4. Click **Create New Editor**.
5. Play the audio, then press the **Sync** button to time the currently highlighted word or line.
6. Export your synced lyrics as an **LRC file**.

---

## ⌨️ Controls

* **Enter** — Sync current word / line
* **Left Arrow** — Seek **5 seconds backward**
* **Right Arrow** — Seek **5 seconds forward**

---

## Demo :
<video src="https://github.com/user-attachments/assets/f709faf8-92d8-4de0-995d-fc0000465591" 
       controls 
       width="200">
</video>

App Used: [Metrolist](https://github.com/mostafaalagamy/Metrolist)

## 💡 Notes

* Designed to be minimal, fast, and distraction-free
* Ideal for karaoke lyrics, music players, or custom lyric visualizers
