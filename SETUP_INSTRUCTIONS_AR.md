# 🚀 Professional README Setup Guide

## 📋 Required Steps:

### 1️⃣ **Create a Personal Repository**

Create a new repository named `MoBMoCaffeine` (same as your GitHub username)

```bash
# On GitHub:
# 1. Click "New Repository"
# 2. Repository name must be: MoBMoCaffeine
# 3. Make it Public
# 4. Enable "Add a README file"
# 5. Click "Create repository"
```

### 2️⃣ **Upload Files**

```bash
# Clone the repository you just created
git clone https://github.com/MoBMoCaffeine/MoBMoCaffeine.git
cd MoBMoCaffeine

# Copy your README.md file
# (Replace the old content with the new one)

# Upload your profile picture
# Place the file mohamedBakr.png in the repository

# Add changes
git add .
git commit -m "✨ Add professional animated README"
git push origin main
```

### 3️⃣ **Enable Snake Animation**

```bash
# Copy the .github folder you created
cp -r .github MoBMoCaffeine/

# Push the workflow
cd MoBMoCaffeine
git add .github/
git commit -m "🐍 Add snake animation workflow"
git push origin main
```

After a few minutes, the workflow will run automatically and generate the Snake Animation!

### 4️⃣ **Verify the Result**

1. Go to: `https://github.com/MoBMoCaffeine`
2. Your amazing profile page will appear! 🎉

---

## 🎨 Additional Customizations:

### Change Colors:

In your README.md file, you can change colors from `00ff41` (green) to any color you like:

* `#ff0000` - Red
* `#0000ff` - Blue
* `#ff00ff` - Purple

### Add Spotify Now Playing:

Add this code to your README:

```markdown
<img src="https://spotify-github-profile.vercel.app/api/view?uid=YOUR_SPOTIFY_ID&cover_image=true&theme=default&show_offline=false&background_color=121212&interchange=false&bar_color=53b14f&bar_color_cover=false" />
```

### Add WakaTime Stats:

```markdown
<img src="https://wakatime.com/badge/user/YOUR_WAKATIME_ID.svg" />
```

---

## 🐛 Troubleshooting:

### If Your Profile Picture Doesn’t Show:

Make sure the image path is correct:

```markdown
https://raw.githubusercontent.com/MoBMoCaffeine/MoBMoCaffeine/main/mohamedBakr.png
```

### If Snake Animation Doesn’t Work:

1. Make sure GitHub Actions is enabled in Settings → Actions
2. Wait 12 hours for automatic execution, or run it manually from Actions → Generate Snake → Run workflow

---

## 📞 Need Help?

Contact me at: [bakrm1921@gmail.com](mailto:bakrm1921@gmail.com)

---

**Made with ❤️ and ☕ by Mohamed Bakr**
