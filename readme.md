# 📚 Student Kanban Board (PWA Edition)

A playful, ultra-lightweight kanban board sticky note tool designed for students. Features a fun hand-drawn aesthetic with crayon-style borders and paper texture background. **Now installable as a Progressive Web App!**

## ✨ Features

### Core Functionality
- **Three Column System**: TODO, IN PROGRESS, and DONE
- **Drag & Drop**: Smoothly move cards between columns and reorder within columns
- **Editable Cards**: Click to edit titles and descriptions inline
- **Tag System**: Categorize cards as Homework, Project, or Task
- **Color Customization**: Choose from 5 sticky note colors per card
- **Sort Options**: Reorder cards using arrow buttons or drag-and-drop
- **Delete with Confirmation**: Safely remove cards with confirmation dialog

### 📱 PWA Features (NEW!)
- **Install to Home Screen**: Works like a native app on mobile and desktop
- **Offline Mode**: Use without internet connection
- **App Icon**: Appears on your device like any other app
- **Standalone Mode**: Opens without browser UI for distraction-free use
- **Auto-Update**: Service worker keeps app updated
- **Fast Loading**: Cached for instant startup

### Data Management
- **Auto-Save**: All changes automatically saved to browser storage
- **Export Data**: Download your cards as JSON backup
- **Import Data**: Restore cards from exported JSON file
- **Offline First**: Works completely offline, no internet required
- **Sample Data**: Loads with example cards on first use

### Design
- **Playful Aesthetic**: Hand-drawn crayon borders and Comic Sans font
- **Paper Texture**: Realistic notebook-style background
- **Responsive**: Works on desktop, tablet, and mobile
- **Smooth Animations**: Satisfying drag-and-drop feedback
- **Toast Notifications**: Friendly confirmation messages

## 🚀 Quick Start

### Option 1: Install as PWA (Recommended!) 📱

1. **Visit the live site** (after deploying to GitHub Pages)
2. **Look for the install prompt** or click the "📱 Install App" button
3. **Click "Install"** when prompted
4. **Done!** The app appears on your home screen/desktop

**Mobile (iOS):**
- Safari → Share button → "Add to Home Screen"

**Mobile (Android):**
- Chrome → Menu → "Install app" or "Add to Home Screen"

**Desktop (Chrome/Edge):**
- Look for install icon in address bar
- Or click "📱 Install App" button in the controls

### Option 2: Open Locally
1. Download all files: `index.html`, `manifest.json`, `service-worker.js`, icons
2. Double-click `index.html` to open in your browser
3. Start organizing! (PWA features work best when served via HTTPS)

### Option 3: Deploy to GitHub Pages

1. **Create a new GitHub repository**
   - Go to github.com and click "New repository"
   - Name it (e.g., "student-kanban-pwa")
   - Make it public
   - Don't initialize with README (we have our own)

2. **Upload files**
   - Click "uploading an existing file"
   - Drag and drop ALL files:
     - `index.html`
     - `manifest.json`
     - `service-worker.js`
     - `README.md`
     - `.gitignore`
     - `icon-192.png` (you need to create this - see ICONS.md)
     - `icon-512.png` (you need to create this - see ICONS.md)
   - Commit the files

3. **Enable GitHub Pages**
   - Go to repository Settings
   - Scroll to "Pages" section
   - Under "Source", select "main" branch
   - Click Save
   - Your app will be live at: `https://yourusername.github.io/student-kanban-pwa/`

4. **Test PWA Installation**
   - Visit your live URL
   - Click the "📱 Install App" button
   - Enjoy your installed app!

## 🎨 Creating Icons

You need two icon files for the PWA to work:
- `icon-192.png` (192x192 pixels)
- `icon-512.png` (512x512 pixels)

**Quick options:**
1. Use https://www.pwabuilder.com/imageGenerator (auto-generates all sizes)
2. Use https://favicon.io/favicon-generator/ (create text-based icons)
3. Create a simple square with 📚 emoji on #f4e4c1 background
4. See `ICONS.md` for detailed instructions

## 📖 How to Use

### Creating Cards
- Click the "+ Add Card" button at the top of any column
- Click on the title or description to edit
- Cards auto-save as you type

### Moving Cards
- **Drag & Drop**: Click and drag cards between columns
- **Arrow Buttons**: Use ↑↓ buttons to reorder within a column
- Cards automatically save their new position

### Customizing Cards
- **Change Tag**: Click the tag button to cycle through Homework → Project → Task
- **Change Color**: Click any color circle at the bottom of the card
- **Delete**: Click the 🗑️ button (you'll be asked to confirm)

### Managing Data
- **Export**: Click "💾 Export Data" to download a backup JSON file
- **Import**: Click "📂 Import Data" to restore from a backup
- **Clear All**: Click "🗑️ Clear All" to start fresh (with confirmation)

### Installing the App
- **Install Button**: Click "📱 Install App" in the controls
- **Install Prompt**: A prompt may appear automatically after 3 seconds
- **Manual Install**: Use browser menu → "Install [app name]"

## 📱 Mobile Support

The app is fully responsive and mobile-optimized:
- Columns stack vertically on mobile
- Touch-friendly drag and drop
- Large tap targets for buttons
- Installable on iOS and Android
- Works offline after installation

## 🔒 Privacy & Data

- **100% Local**: All data stored in your browser's localStorage
- **No Tracking**: No analytics, cookies, or external requests
- **No Account Required**: Use immediately, no sign-up
- **Export Anytime**: Your data is always portable
- **Offline First**: Works without internet after first load

## 🛠️ Technical Details

### Files Included
- `index.html` - Main application (single file with embedded CSS/JS)
- `manifest.json` - PWA configuration
- `service-worker.js` - Offline caching and PWA functionality
- `README.md` - This file
- `.gitignore` - Git ignore rules
- `icon-192.png` - App icon (192x192) - **You need to create**
- `icon-512.png` - App icon (512x512) - **You need to create**

### Browser Support
- ✅ Chrome/Edge (full PWA support)
- ✅ Firefox (full PWA support)
- ✅ Safari (iOS 11.3+, limited PWA features)
- ✅ Samsung Internet
- ✅ Opera

### PWA Features
- **Service Worker**: Caches app for offline use
- **Web App Manifest**: Defines app name, icons, colors
- **Installable**: Can be added to home screen
- **Standalone**: Runs in its own window
- **Responsive**: Adapts to any screen size

## 🐛 Troubleshooting

**Install button not appearing?**
- Make sure you're on HTTPS (GitHub Pages provides this)
- Try a different browser (Chrome works best)
- Check if app is already installed
- Clear browser cache and reload

**Cards disappeared?**
- Data is stored per browser. If you cleared browser data, cards are lost
- Always export backups regularly!
- Check if you're in the same browser/profile

**Drag and drop not working?**
- Make sure you're clicking and holding on the card
- Try using the arrow buttons instead
- Check if browser permissions are blocking drag events

**App not working offline?**
- Visit the app once while online to cache it
- Check if service worker is registered (F12 → Application tab → Service Workers)
- Try reinstalling the app

**Import not working?**
- Make sure you're importing a valid JSON file exported from this app
- File must have the correct structure with `todo`, `inprogress`, and `done` arrays

## 🎓 Perfect For Students

- Track homework assignments
- Manage group projects
- Organize study tasks
- Plan exam preparation
- Visualize progress
- Use offline during class

## 🎨 Customization

### Changing Colors
Edit the `colors` array in the JavaScript section:
```javascript
const colors = ['#ffd54f', '#ffb3ba', '#bae1ff', '#baffc9', '#ffdfba'];
```

### Changing Tag Names
Find the `cycleTag` function and modify:
```javascript
const tags = ['task', 'homework', 'project']; // Add or change tags here
```

### Adjusting Styles
All CSS is embedded in the `<style>` section. Search for specific elements:
- Background: Search for `body { background:`
- Font: Search for `font-family:`
- Card colors: Search for `.card {`

### Modifying PWA Settings
Edit `manifest.json`:
- Change `name` and `short_name`
- Update `theme_color` and `background_color`
- Modify `display` mode (standalone, fullscreen, minimal-ui)

## 📄 License

Free to use and modify! Share with your classmates.

## 🤝 Contributing

This is a single-file PWA designed for easy sharing. Feel free to:
- Fork and customize
- Share with friends
- Modify for your needs
- Create your own version
- Add new features

## 💡 Tips

1. **Install It**: The app works best when installed - faster and works offline!
2. **Use Tags Wisely**: Color-code by tag to see what needs attention
3. **Regular Exports**: Backup weekly, especially before exams
4. **Keep it Simple**: Don't overload with too many cards
5. **Archive Done Items**: Periodically export and clear completed work
6. **Mobile First**: Add cards on-the-go from your phone
7. **Offline Ready**: Perfect for studying in places without WiFi

## 🆚 PWA vs Web Version

| Feature | Web Version | PWA (Installed) |
|---------|-------------|-----------------|
| Offline Use | ❌ | ✅ |
| Home Screen Icon | ❌ | ✅ |
| Fast Loading | ⚠️ | ✅ |
| Standalone Window | ❌ | ✅ |
| Auto-Updates | ❌ | ✅ |
| Works in Browser | ✅ | ✅ |

---

Made with 💖 for students who love to stay organized!

**Questions or issues?** Check the code comments in the files - everything is documented!

**Want to learn more about PWAs?** Visit https://web.dev/progressive-web-apps/