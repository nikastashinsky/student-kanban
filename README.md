<artifact identifier="kanban-readme" type="text/markdown" title="README.md - Student Kanban Board">
# 📚 Student Kanban Board
A playful, ultra-lightweight kanban board sticky note tool designed for students. Features a fun hand-drawn aesthetic with crayon-style borders and paper texture background.
✨ Features
Core Functionality

Three Column System: TODO, IN PROGRESS, and DONE
Drag & Drop: Smoothly move cards between columns and reorder within columns
Editable Cards: Click to edit titles and descriptions inline
Tag System: Categorize cards as Homework, Project, or Task
Color Customization: Choose from 5 sticky note colors per card
Sort Options: Reorder cards using arrow buttons or drag-and-drop
Delete with Confirmation: Safely remove cards with confirmation dialog

Data Management

Auto-Save: All changes automatically saved to browser storage
Export Data: Download your cards as JSON backup
Import Data: Restore cards from exported JSON file
Offline First: Works completely offline, no internet required
Sample Data: Loads with example cards on first use

Design

Playful Aesthetic: Hand-drawn crayon borders and Comic Sans font
Paper Texture: Realistic notebook-style background
Responsive: Works on desktop, tablet, and mobile
Smooth Animations: Satisfying drag-and-drop feedback
Toast Notifications: Friendly confirmation messages

🚀 Quick Start
Option 1: Open Locally

Download the index.html file
Double-click to open in your browser
Start organizing! No setup required.

Option 2: Deploy to GitHub Pages

Create a new GitHub repository

Go to github.com and click "New repository"
Name it (e.g., "my-kanban-board")
Make it public
Don't initialize with README (we have our own)


Upload files

Click "uploading an existing file"
Drag and drop index.html and README.md
Commit the files


Enable GitHub Pages

Go to repository Settings
Scroll to "Pages" section
Under "Source", select "main" branch
Click Save
Your app will be live at: https://yourusername.github.io/my-kanban-board/



📖 How to Use
Creating Cards

Click the "+ Add Card" button at the top of any column
Click on the title or description to edit
Cards auto-save as you type

Moving Cards

Drag & Drop: Click and drag cards between columns
Arrow Buttons: Use ↑↓ buttons to reorder within a column
Cards automatically save their new position

Customizing Cards

Change Tag: Click the tag button to cycle through Homework → Project → Task
Change Color: Click any color circle at the bottom of the card
Delete: Click the 🗑️ button (you'll be asked to confirm)

Managing Data

Export: Click "💾 Export Data" to download a backup JSON file
Import: Click "📂 Import Data" to restore from a backup
Clear All: Click "🗑️ Clear All" to start fresh (with confirmation)

🎨 Customization
Changing Colors
Edit the colors array in the JavaScript section:
javascriptconst colors = ['#ffd54f', '#ffb3ba', '#bae1ff', '#baffc9', '#ffdfba'];
Changing Tag Names
Find the cycleTag function and modify:
javascriptconst tags = ['task', 'homework', 'project']; // Add or change tags here
Adjusting Styles
All CSS is embedded in the <style> section. Search for specific elements:

Background: Search for body { background:
Font: Search for font-family:
Card colors: Search for .card {

📱 Mobile Support
The app is fully responsive:

Columns stack vertically on mobile
Touch-friendly drag and drop
Large tap targets for buttons
Optimized for small screens

🔒 Privacy & Data

100% Local: All data stored in your browser's localStorage
No Tracking: No analytics, cookies, or external requests
No Account Required: Use immediately, no sign-up
Export Anytime: Your data is always portable

🐛 Troubleshooting
Cards disappeared?

Data is stored per browser. If you cleared browser data, cards are lost
Always export backups regularly!

Drag and drop not working?

Make sure you're clicking and holding on the card
Try using the arrow buttons instead
Check if browser permissions are blocking drag events

Import not working?

Make sure you're importing a valid JSON file exported from this app
File must have the correct structure with todo, inprogress, and done arrays

🎓 Perfect For Students

Track homework assignments
Manage group projects
Organize study tasks
Plan exam preparation
Visualize progress

📄 License
Free to use and modify! Share with your classmates.
🤝 Contributing
This is a single-file app designed for easy sharing. Feel free to:

Fork and customize
Share with friends
Modify for your needs
Create your own version

💡 Tips

Use Tags Wisely: Color-code by tag to see what needs attention
Regular Exports: Backup weekly, especially before exams
Keep it Simple: Don't overload with too many cards
Archive Done Items: Periodically export and clear completed work
Mobile First: Add cards on-the-go from your phone


Made with 💖 for students who love to stay organized!
Questions or issues? Check the code comments in index.html - everything is documented!
</artifact>
And finally, the .gitignore file:
<artifact identifier="kanban-gitignore" type="application/vnd.ant.code" language="gitignore" title=".gitignore">
# macOS
.DS_Store
.AppleDouble
.LSOverride
Windows
Thumbs.db
ehthumbs.db
Desktop.ini
Linux
*~
.directory
Editor directories and files
.vscode/
.idea/
*.swp
*.swo
*~
Backup files
*.bak
*.backup
*.json.backup
Log files
.log
npm-debug.log
Temporary files
*.tmp
*.temp
</artifact>
Perfect! 🎉 I've created a complete, production-ready Student Kanban Board with all the features you requested:
✅ What You Got:

index.html - Single file app that works immediately
README.md - Complete documentation with deployment instructions
.gitignore - Clean repository management

🎨 Design Features:

✅ Comic Sans font throughout
✅ Paper texture background (grid lines)
✅ Crayon-style wobbly borders on cards and columns
✅ Sticky note colors (yellow, pink, blue, green, orange)
✅ Hand-drawn aesthetic with rotated cards

🚀 Functionality:

✅ Drag & drop between columns
✅ Reorder with arrow buttons or dragging
✅ Inline editing (click title/description)
✅ 3 tag types: Homework, Project, Task
✅ Color picker per card
✅ Delete with confirmation
✅ Export/Import JSON data
✅ Auto-save to localStorage
✅ Sample cards on first load
✅ Toast notifications
✅ Mobile responsive

📦 How to Use:
Instantly: Just open index.html in your browser - it works!
Deploy to GitHub Pages:

Create new repo on GitHub
Upload the 3 files
Enable Pages in Settings
Done! Share the URL with others

The app requires ZERO setup - no accounts, no configuration, no installation! 🎊
