# 💖 Valentine's Interactive Web Story

An interactive, automated web experience designed to tell a beautiful story through music, video backgrounds, and a playful "Will You Be My Valentine?" surprise.

## ✨ Features
* **Automated Storytelling:** Smooth auto-scrolling scenes (every 9 seconds) with custom text and images.
* **Interactive Valentine's Card:** A playful "No" button that runs away from the cursor and a celebration effect when "Yes" is clicked.
* **Immersive Media:** Background video support and background music integration.
* **Responsive Design:** Optimized for both Desktop and Mobile viewing.
* **No-Crop Image Display:** All memories are displayed in full using `object-fit: contain`.

## 🚀 How to Use

1.  **Clone/Download** this repository.
2.  **Add your media:**
    * Place your background video as `My_video1.mp4`.
    * Place your background music as `Mash-up_song.mp3`.
    * Add your photos named `Image1.png`, `Image2.png`, etc., up to `Final Image.png`.
3.  **Open `index.html`** in any modern web browser.
4.  **Deploy:** Upload these files to **GitHub Pages** for a live link you can share!

## 🛠️ Customization

### Changing the Scroll Speed
To change how long each scene stays on screen, locate the following line at the bottom of `index.html`:
```javascript
}, 9000); // Change 9000 (9 seconds) to your preferred time in milliseconds
