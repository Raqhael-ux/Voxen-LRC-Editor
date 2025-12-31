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
  <img src="https://cdn.discordapp.com/attachments/1344634704946528287/1455877183695487038/Screenshot_20251231-1855082.png?ex=695652c9&is=69550149&hm=022a040f9e988aed04b892a76984826ea0eb16214475e6b1b0cb5d426c6b51d5" alt="Android" width="200"/>
  <img src="https://cdn.discordapp.com/attachments/1344634704946528287/1455877366990504078/PC.png?ex=695652f5&is=69550175&hm=fcb14f14980690163b0d3db0b91e9bc09d516d5d10440950118362cbe3d81473" alt="Windows" width="740"/>
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

* Bulk offset modification
* Improved lyrics text editor
* Built-in preview mode (maybe 👀)

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
