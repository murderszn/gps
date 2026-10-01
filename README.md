# Glory's Sticker Studio ⭐

An interactive creative studio where Glory can design magical scenes starring her favorite TV characters — **My Little Pony, Care Bears, Peppa Pig, Bluey, Baby Shark, Finny the Shark, Gumball, and We Bare Bears**!

> Note: TV-show stickers are emoji-style fan representations made for personal play, not official artwork. Swap in licensed images before publishing anywhere public.

---

## 🌟 Highlights & New Features

### ⭐ 77 Stickers — every pack is a TV show
- **Mane 6**: Fluttershy, Twilight Sparkle, Pinkie Pie, Rainbow Dash, Applejack, Rarity
- **Royalty & Magic**: Princess Celestia, Princess Luna, Princess Cadance, Spike, Starlight Glimmer, Sunset Shimmer
- **Friends & Mischief**: The Great and Powerful Trixie, Discord, Big Macintosh, Derpy Hooves
- **Cutie Mark Crusaders & Pets**: Apple Bloom, Sweetie Belle, Scootaloo, Angel Bunny
- **Care Bears**: Cheer Bear, Grumpy Bear, Wish Bear, Funshine Bear, Share Bear, Tenderheart Bear, Good Luck Bear, Bedtime Bear
- **🐷 Peppa** (10): Peppa, George, Mummy Pig, Daddy Pig, Suzy Sheep, Danny Dog, Rebecca Rabbit, Pedro Pony, Muddy Puddle, Teddy
- **🐶 Bluey** (9): Bluey, Bingo, Bandit, Chilli, Muffin, Socks, Bluey House, Keepy Uppy, Tennis Ball
- **🦈 Baby Shark** (8): Baby, Mommy, Daddy, Grandma, Grandpa, Bubbles, Little Fish, Anchor
- **🏄 Finny** (6): Finny, Sharkdog, Max, Olivia, Surfboard, Beach Day
- **🐱 Gumball** (8): Gumball, Darwin, Anais, Nicole, Richard, Penny, Rob, Elmore School
- **🐻 Bare Bears** (8): Grizz, Panda, Ice Bear, Chloe, Charlie, Nom Nom, Food Truck, Ranger Tabes

TV stickers are local emoji art (zero downloads). Missing image files fall back to emoji instead of breaking.

### 🖼️ Adding real art
Want real pictures instead of emoji? Save transparent PNGs into `stickers/` named by sticker id (e.g. `stickers/bluey.png`) — the game picks them up automatically on reload. See [stickers/README.md](stickers/README.md) for the full filename table. Only use art you have rights to (your own drawings, officially released assets); most "free PNG" sites host unlicensed copyrighted copies.

### ⭐ Favorites & 🎲 Surprise
- Tap the **★** on any sticker to save it — **⭐ Favs** category persists in `localStorage`.
- **🎲 Surprise Me!** drops a random sticker with a sparkle burst.

### 🖼️ 9 Scenic Backgrounds
- 🌈 **Rainbow** (Animated dynamic pastel shader)
- 🏡 **Fluttershy's Cottage**
- 🏰 **Canterlot Castle**
- 🏘️ **Ponyville Mainstreet**
- 📚 **Twilight's Golden Oak Library**
- 🍎 **Sweet Apple Acres**
- ☁️ **Cloudsdale**
- ☁️ **Care-a-lot**
- 🚶 **Abbey Road**

### 💬 Speech & Thought Bubbles
- Click **"Add Speech Bubble"** to place editable dialogue boxes on your scene.
- Type any phrase or quote! Bubbles can be flipped, resized, and repositioned right next to your ponies.

### ✨ Ambient Magic & Particle FX
- **Ambient modes**: Sparkles ✨, Floating Butterflies 🦋, Hearts 💖, Star Shower ⭐, or Off.
- **Sparkle Bursts**: Dropping, duplicating, or clicking stickers triggers a burst of stars and sparkles.

### 🎵 Interactive Sound Synthesizer (Web Audio API)
- Zero external audio files required — synthesizes bubbly pops, magical arpeggios, duplicate boings, and shutter clicks.
- Toggle sound on/off with the 🔊 / 🔇 button in the sidebar header.

### 🎨 Intuitive Controls & Polish
- **Drag & Drop**: Drag characters directly from the sidebar onto the canvas, or click to spawn them.
- **Category pills with live counts** + search across all 77 stickers.
- **Corner Scale Handle**: Drag the bottom-right handle (⤡) to resize smoothly.
- **Mouse Wheel Zoom**: Scroll on any selected sticker to resize on the fly.
- **Horizontal Flip (↔)**: Mirror characters so they face each other in dialogue.
- **Rotate (🔄)**: Rotate 45° with a click or keyboard shortcut.
- **Layer Controls**: Bring to Front (▲) and Send to Back (▼).
- **Full Undo / Redo (↺ / ↻)**: Step backwards and forwards through all scene edits (`Ctrl+Z` / `Ctrl+Y`).
- **Auto-Save**: Scenes automatically save to `localStorage`, so your artwork is never lost on refresh.
- **📸 High-Resolution PNG Export**: Click **"Save Art"** to download your creation as a PNG image!

---

## ⌨️ Keyboard Shortcuts

| Shortcut | Action |
| :--- | :--- |
| **`Delete` / `Backspace`** | Delete selected sticker |
| **`F`** | Flip horizontal (mirror) |
| **`[` / `]`** | Rotate left / right 15° |
| **`+` / `-`** | Make bigger / smaller |
| **`Ctrl + D`** | Duplicate selected sticker |
| **`Ctrl + Z`** | Undo |
| **`Ctrl + Y`** (or `Ctrl+Shift+Z`) | Redo |
| **`PageUp` / `PageDown`** | Bring to Front / Send to Back |
| **`Arrow Keys`** | Nudge position (hold `Shift` for bigger jumps) |
| **`Escape`** | Deselect |

---

## 🚀 Running Locally

Serve the studio using any local web server:

```bash
# Using Python 3
python3 -m http.server 8080
```

Open **http://localhost:8080** in your browser.
