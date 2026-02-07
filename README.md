# 🎧 Voxen — Lightweight Synced Lyrics Editor

Voxen is a **fast, lightweight, and no-install** tool for creating **synced lyrics** with both **line-by-line** and **word-by-word** timing support. It’s built as a **single HTML file**, so it runs **entirely in your browser**—on **PC and mobile**—with no setup required.

Just drop in your **MP3**, paste your lyrics, and start syncing. Simple as that.

## 🌐 Try It Online

If you don’t want to download the HTML file, you can use the web version instead:

🔗 **[Voxen Sync Online](https://raqhael-ux.github.io/Voxen-LRC-Editor/)**

<div style="display: flex; gap: 10px;">
<img width="700" height="438" alt="image" src="https://github.com/user-attachments/assets/063db70e-ab1f-4200-a1ae-a6e54209de81" />
<img width="200" height="438" alt="image" src="https://github.com/user-attachments/assets/ba57efdd-9b79-4778-992e-9abed45df163" />
</div>

## 💖 V2 is coming :
- [ ] Duet Support
- [ ] UI Overhaul
- [x] Background Lyrics Support
- [x] Change export type (Advanced or Pro)
- [ ] (Unsure) Preview slide animation
- [ ] Wiki

## ✨ Features :

* **Word-level lyric timing** (perfect for karaoke-style effects)
* **Line-by-line syncing mode**
* Add, remove, or modify lyric lines
* Runs **fully in the browser**
* Works **locally** (no internet required after loading)
* **Export to LRC** format
* **Import & export projects** as JSON
* **Reaction Offset** support for timing adjustments
* **Preview Mode** Preview your LRC File

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

Advanced (For Metrolist)
```
<for:ss.xx:ss.xx|you:ss.xx:ss.xx|I'd:ss.xx:ss.xx|bleed:ss.xx:ss.xx|myself:ss.xx:ss.xx|dry:ss.xx:ss.xx>
```

Pro (Default for most Apps)
```
[01:28.866]v1:<01:28.866>Your <01:29.565>skin, <01:31.332>oh <01:31.669>yeah, <01:32.017>your <01:32.338>skin, <01:32.702>and <01:33.122>bones<01:33.874>
```
```
[bg:<01:33.778>Ooh-<01:36.594>oo-<01:37.947>ooh<01:39.035>]
```
Note: You can convert Pro format to Advanced format by just changing the format in the sidebar.

## ⌨️ Controls

* **Enter** — Sync current word / line
* **Left Arrow** — Seek **5 seconds backward**
* **Right Arrow** — Seek **5 seconds forward**


## Demo :
<video src="https://github.com/user-attachments/assets/f709faf8-92d8-4de0-995d-fc0000465591" 
       controls 
       width="200">
</video>

App Used: [Metrolist](https://github.com/mostafaalagamy/Metrolist)
