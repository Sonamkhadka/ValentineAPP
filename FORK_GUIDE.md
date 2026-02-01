# 🍴 Fork & Customize Guide

Want to create your own DateMePlease proposal? Here's the fastest way!

## ⚡ Quick Start (5 minutes)

### Step 1: Fork This Repository
1. Click the **Fork** button at the top right of this page
2. Wait for GitHub to create your copy

### Step 2: Enable GitHub Pages
1. Go to **Settings** → **Pages** in your forked repo
2. Under "Build and deployment", select:
   - Source: **Deploy from a branch**
   - Branch: **main** / **root**
3. Click **Save**
4. Wait 1-2 minutes for the site to build

### Step 3: Customize (Edit directly on GitHub)

#### Change the Name
1. Open `index.html`
2. Click the **Edit** button (pencil icon)
3. Find line 75:
   ```html
   <h3 class="username">Pookie 🌸</h3>
   ```
4. Change "Pookie" to your Valentine's name
5. Scroll down, click **Commit changes**

#### Change the Date
1. Still in `index.html`, find lines 257-273:
   ```html
   <span>Feb 14th, 2026</span>
   <span>7:00 PM</span>
   <span>Top Secret Location</span>
   ```
2. Update to your actual date/time/location
3. Commit changes

### Step 4: Get Your Link
- Your site will be at: `https://YOURUSERNAME.github.io/ValentineAPP/`
- Or add a custom domain in Settings → Pages

### Step 5: Send It! 💌
Text the link to your Valentine!

---

## 🎨 Deeper Customization

### Change the Messages
Edit `script.js` (lines 1-86) to change:
- Boot sequence text
- Guilt-trip messages
- Question variations

### Change GIFs
Edit `script.js` (lines 13-31):
1. Go to [Giphy](https://giphy.com)
2. Find cute GIFs
3. Copy the GIF URL
4. Replace in the config

### Change Colors
Edit `style.css` line 1-19 (CSS variables) to change the pink theme:
```css
:root {
    --primary-pink: #ff7eb3;
    --secondary-pink: #ff758c;
    /* ... etc */
}
```

---

## 🆘 Troubleshooting

**Site not showing?**
- Check Settings → Pages for build errors
- Make sure your repo is public

**Changes not appearing?**
- Clear browser cache (Ctrl+Shift+R or Cmd+Shift+R)
- Wait 2-3 minutes for GitHub to rebuild

**Want to test locally?**
- Download the ZIP
- Open `index.html` in your browser

---

## 💡 Pro Tips

1. **Test first** - Send the link to yourself to make sure it works
2. **Mobile check** - Open it on your phone to see how it looks
3. **Screenshot** - Take a screenshot of the success screen to save the memory!

---

Good luck with your DateMePlease proposal! 💕 If it works, star this repo and share your story!
