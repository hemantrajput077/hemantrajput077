# GitHub Profile README Setup Guide

## 📁 Folder Structure

```
YOUR_GITHUB_USERNAME/          # Create a repository with your GitHub username
├── README.md                   # Main profile README
├── .github/
│   └── workflows/
│       └── snake.yml          # Snake animation workflow
└── assets/                    # Optional: for custom images
    ├── banner.png
    └── icons/
```

## 🚀 Setup Instructions

### Step 1: Create Profile Repository

1. Create a new repository on GitHub with **exactly** your GitHub username
   - Example: If your username is `hemantrajput`, create a repository named `hemantrajput`
2. Make sure it's **public**
3. Initialize with a README (or push this README.md)

### Step 2: Update Personal Information

Replace the following placeholders in `README.md`:

- `YOUR_GITHUB_USERNAME` → Your actual GitHub username (appears ~15 times)
- `YOUR_LINKEDIN_USERNAME` → Your LinkedIn username
- `YOUR_LEETCODE_USERNAME` → Your LeetCode username
- `YOUR_EMAIL@gmail.com` → Your email address
- `YOUR_PORTFOLIO.vercel.app` → Your portfolio URL

**Quick Find & Replace:**
```bash
# In your text editor, find and replace:
YOUR_GITHUB_USERNAME → hemantrajput
YOUR_LINKEDIN_USERNAME → hemant-rajput
YOUR_LEETCODE_USERNAME → hemantrajput
YOUR_EMAIL@gmail.com → your.email@gmail.com
YOUR_PORTFOLIO.vercel.app → hemantrajput.vercel.app
```

### Step 3: Enable GitHub Actions

1. Go to your repository settings
2. Navigate to **Actions** → **General**
3. Under "Workflow permissions", select:
   - ✅ **Read and write permissions**
4. Click **Save**

### Step 4: Set Up Contribution Snake

1. Copy the `.github/workflows/snake.yml` file to your repository
2. Commit and push to the `main` branch
3. The action will automatically run and create an `output` branch
4. The snake animation will be available at:
   ```
   https://raw.githubusercontent.com/YOUR_GITHUB_USERNAME/YOUR_GITHUB_USERNAME/output/github-contribution-grid-snake-dark.svg
   ```

### Step 5: Set Up Spotify Widget (Optional)

1. Fork this repository: [novatorem/novatorem](https://github.com/novatorem/novatorem)
2. Follow the setup instructions in that repo:
   - Create a Spotify Developer App
   - Get your Client ID and Client Secret
   - Set up refresh token
3. Deploy to Vercel:
   - Connect the forked repo to Vercel
   - Add environment variables (from novatorem instructions)
4. Update the README.md:
   - Replace `YOUR_VERCEL_DEPLOY` with your Vercel app URL
   - Replace `YOUR_SPOTIFY_USER` with your Spotify username

If you don't want the Spotify widget, simply remove that section from the README.

## 🎨 Customization Options

### Color Scheme

Current theme uses:
- **Background**: `#0D1117` (Dark Black)
- **Primary Accent**: `#A78BFA` (Purple)
- **Secondary Accent**: `#60A5FA` (Blue)
- **Text**: `#FFFFFF` (White)

To change colors, search for these hex codes in README.md and replace them.

### GitHub Stats Themes

Current theme: `tokyonight`

Other popular themes:
- `radical`
- `merko`
- `gruvbox`
- `dracula`
- `monokai`
- `onedark`
- `cobalt`
- `synthwave`
- `highcontrast`
- `dark`

Replace `theme=tokyonight` with any theme name.

### Adding Custom Banner

1. Create a custom banner image (1200x400px recommended)
2. Upload to `assets/banner.png`
3. Update the header image URL in README.md:
   ```markdown
   <img src="./assets/banner.png" width="100%"/>
   ```

Or use the current **Capsule Render** dynamic banner (recommended).

## 🔧 Troubleshooting

### Snake Animation Not Showing

1. Check if the `output` branch exists in your repository
2. Verify GitHub Actions ran successfully (check Actions tab)
3. Wait 24 hours for the first run (or manually trigger the workflow)
4. Ensure the repository is public

### Stats Not Loading

1. Verify your GitHub username is correct
2. Check if the Vercel services are online:
   - [github-readme-stats](https://github.com/anuraghazra/github-readme-stats)
   - [github-readme-streak-stats](https://github.com/DenverCoder1/github-readme-streak-stats)
3. Try refreshing the page (Ctrl + Shift + R)

### Profile View Counter Not Incrementing

- The counter may be cached
- Only counts unique visits
- Refreshing from the same browser won't increment

## 📝 Additional Resources

- [GitHub Profile README Generator](https://rahuldkjain.github.io/gh-profile-readme-generator/)
- [Shields.io Badge Generator](https://shields.io/)
- [GitHub Readme Stats](https://github.com/anuraghazra/github-readme-stats)
- [Simple Icons](https://simpleicons.org/)
- [Emoji Cheat Sheet](https://github.com/ikatyang/emoji-cheat-sheet)

## 🎯 Next Steps

1. ✅ Create profile repository
2. ✅ Copy README.md and snake.yml
3. ✅ Replace all placeholder values
4. ✅ Enable GitHub Actions
5. ✅ Commit and push
6. ✅ Wait for first workflow run
7. ✅ Visit your profile: `https://github.com/YOUR_GITHUB_USERNAME`

## 💡 Tips

- Update your pinned repositories to showcase your best work
- Keep your profile README updated with current learning and projects
- Add a profile picture and bio in GitHub settings
- Star repositories you find useful
- Contribute to open source projects

---

**Made with 💜 by Hemant Rajput**
