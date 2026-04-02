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
- [x] Duet Support
- [ ] UI Overhaul / Preview Mode Overhaul
- [x] Background Lyrics Support
- [x] Change export type (Advanced or Pro)
- [ ] Slide Animation
- [ ] Wiki (How To Use)
- [ ] Flexible LRC Output (Multiple App Support)
- [X] Fix Lag

**Concept :**
<img width="1920" height="1080" alt="EXPORT" src="https://github.com/user-attachments/assets/556b2e26-86a3-4956-9dc4-6ce2f69819ae" />


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

## Music App with Advanced LRC Support
| App Name     | Word-by-Word | BG Vocals      | Syllable-by-Syllable | Duet Support |
|-------------|--------------|----------------|---------------------|--------------|
| [Metrolist](https://github.com/mostafaalagamy/Metrolist)   | ✅ Yes       | ✅ Yes       | ✅ Yes          | ✅ Yes     |
| [Gramophone](https://github.com/FoedusProgramme/Gramophone)  | ✅ Yes       | ✅ Yes         | ✅ Yes               | ✅ Yes       |
| [Oto Music](https://play.google.com/store/apps/details?id=com.piyush.music&hl=en)   | ✅ Yes       | ❌ No          | ✅ Yes               | ❌ Kind of        |

## Demo:

<table>
  <tr>
    <td align="center">
      <b>App Used: <a href="https://github.com/FoedusProgramme/Gramophone">Gramophone</a></b><br>
      <video 
        src="https://github.com/user-attachments/assets/70a79040-3e19-44d8-8c99-af0754a72df0" 
        controls 
        width="200" 
        height="150">
      </video>
    </td>
       <td align="center">
      <b>App Used: <a href="https://github.com/mostafaalagamy/Metrolist">Metrolist</a></b><br>
      <video 
        src="https://github.com/user-attachments/assets/f709faf8-92d8-4de0-995d-fc0000465591" 
        controls 
        width="200" 
        height="150">
      </video>
    </td>
  </tr>
</table>

