# 💘 Love_OS v14.0 - The Ultimate Valentine's Proposal App

<p align="center">
  <img src="https://img.shields.io/badge/Made%20with-HTML%2C%20CSS%2C%20JS-ff69b4?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Deployed%20on-GitHub%20Pages-181717?style=for-the-badge&logo=github" />
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" />
</p>

<p align="center">
  <b>A "gamified persistence" web app designed to be the cutest (and most unrefusable) digital Valentine's proposal.</b>
</p>

<p align="center">
  🌸 <a href="https://sonamkhadka.github.io/ValentineAPP/" target="_blank"><b>Live Demo</b></a> 🌸
</p>

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| 💻 **Boot Sequence** | Hacker-style terminal intro with cute pink aesthetics |
| 🔒 **Security Check** | Verifies "Suspiciously Cute" users before proceeding |
| 🐱 **Love Captcha** | "Select all images with a reason to say YES" |
| 💌 **The Envelope** | Smooth CSS envelope opening animation |
| 💕 **The UNREFUSABLE Question** | Interactive "Will you be my Valentine?" with playful mechanics |
| 🏃 **Evasive "No" Button** | The "No" button literally runs away from the cursor after multiple attempts |
| 😢 **Guilt Trip Mode** | Progressive sad GIFs and pleading messages |
| 💥 **Mega Yes Button** | "Yes" button grows until it dominates the screen |
| 💔 **Fake BSOD** | Stubborn users get a pink "Heart Broken Exception" screen |
| 🎉 **Victory Celebration** | Confetti explosion with customizable date details |
| 🔊 **Background Music** | Optional lofi music with toggle controls |
| 📱 **Mobile Optimized** | Fully responsive, touch-friendly evasion mechanics |

---

## 🚀 Quick Start

### For Users (Send to Your Valentine)

**Option 1: GitHub Pages (Recommended)**
1. Visit the [live demo](https://sonamkhadka.github.io/ValentineAPP/)
2. Or fork this repo and enable GitHub Pages in Settings

**Option 2: Local File**
1. Download this repository as ZIP
2. Extract and open `index.html` in any browser
3. Send the folder to your Valentine!

---

## 🎨 Customization Guide

### 1. Change the Recipient's Name

**File:** `index.html` (Line 75)
```html
<h3 class="username">Pookie 🌸</h3>
```

### 2. Update the Date Details

**File:** `index.html` (Lines 257-273)
```html
<div class="detail-row">
    <span class="icon">📅</span>
    <span>Feb 14th, 2026</span>  <!-- Change this -->
</div>
<div class="detail-row">
    <span class="icon">⏰</span>
    <span>7:00 PM</span>  <!-- Change this -->
</div>
<div class="detail-row">
    <span class="icon">📍</span>
    <span>Top Secret Location</span>  <!-- Change this -->
</div>
```

### 3. Customize the Messages

**File:** `script.js` (Lines 1-86)

Edit the `config` object to personalize:

```javascript
const config = {
    bootLogs: [
        // Change the terminal messages
        { text: "💕 Initializing Love_OS kernel...", type: "loading" },
        // ... more logs
    ],
    
    noTexts: [
        // Change guilt-trip messages
        "No 💔",
        "Are you sure? 🥺",
        "Really sure? 💔",
        // ... more messages
    ],
    
    questionVariations: [
        // Change the question variants
        "Will you be my Valentine?",
        "Pretty please? 🥺",
        // ... more variations
    ]
};
```

### 4. Replace GIFs

**File:** `script.js` (Lines 13-31)

Replace the Giphy URLs with your own:
```javascript
gifs: {
    happy: "https://media.giphy.com/media/...",      // Happy reaction
    celebration: "https://media.giphy.com/media/...", // Success celebration
    sad: "https://media.giphy.com/media/...",         // Sad reaction
    noSequence: [
        // Sequential sad GIFs for "No" clicks
    ]
}
```

### 5. Change Background Music

**File:** `script.js` (Lines 33-38)

Replace with your own audio URLs:
```javascript
sounds: {
    bgm: "https://cdn.pixabay.com/...",  // Background music
    pop: "https://cdn.pixabay.com/...",  // Pop sound
    yay: "https://cdn.pixabay.com/...",  // Success sound
    no: "https://cdn.pixabay.com/..."    // Reject sound
}
```

---

## 🛠️ Tech Stack

- **HTML5** - Semantic structure
- **CSS3** - Animations, gradients, glassmorphism effects
- **Vanilla JavaScript** - No frameworks, pure JS magic
- **Canvas Confetti** - Celebration effects
- **External APIs** - Giphy, Pixabay (audio), LoremFlickr

---

## 📂 Project Structure

```
ValentineApp/
├── index.html      # Main HTML structure
├── style.css       # All styling and animations
├── script.js       # Game logic and interactions
├── README.md       # This file
└── LICENSE         # MIT License
```

---

## 🎯 How It Works

1. **Boot Sequence** - Terminal-style intro builds anticipation
2. **Security Check** - Playful "identity verification"
3. **Love Captcha** - Interactive image selection game
4. **The Envelope** - Click to reveal the letter
5. **The Question** - Main interactive experience:
   - First few "No" clicks show sad GIFs
   - After 5 clicks: Button becomes evasive (runs from cursor)
   - After 12 clicks: Fake "Heart Broken Exception" BSOD
   - "Yes" button grows larger with each "No" click
6. **Success** - Confetti celebration with date details

---

## 📱 Mobile Features

- Touch-optimized evasion mechanics
- Responsive design for all screen sizes
- Portrait and landscape support
- Smooth animations on mobile devices

---

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Report bugs via [Issues](../../issues)
- Suggest new features
- Submit pull requests

### Ideas for Contributions
- [ ] Add more language translations
- [ ] Create themes (dark mode, different color schemes)
- [ ] Add sound effect volume control
- [ ] Implement share functionality
- [ ] Create a customization wizard

---

## 📜 License

This project is licensed under the [MIT License](LICENSE) - feel free to use it for your own Valentine's proposal! 💝

---

## 🙏 Credits

- GIFs powered by [Giphy](https://giphy.com)
- Audio from [Pixabay](https://pixabay.com)
- Confetti effect by [canvas-confetti](https://github.com/catdad/canvas-confetti)
- Fonts from [Google Fonts](https://fonts.google.com)

---

<p align="center">
  <b>Made with 💕 and too much JavaScript</b><br>
  <sub>If you used this for your Valentine, let me know how it went! 🌸</sub>
</p>
