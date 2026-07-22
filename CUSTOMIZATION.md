# 🎨 Customization Guide

## Overview

This guide will help you customize every aspect of your GitHub profile README to match your personal brand and style.

---

## 🌈 Color Themes

### Current Theme: Dark Purple/Blue

```yaml
Background: #0D1117 (Dark Black)
Primary: #A78BFA (Purple)
Secondary: #60A5FA (Blue)
Text: #FFFFFF (White)
```

### Alternative Color Schemes

#### Cyberpunk Neon
```yaml
Background: #0a0e27
Primary: #FF006E (Hot Pink)
Secondary: #00F5FF (Cyan)
Text: #FFFFFF
Theme: radical
```

#### Matrix Green
```yaml
Background: #000000
Primary: #00FF41 (Matrix Green)
Secondary: #008F11 (Dark Green)
Text: #FFFFFF
Theme: dark
```

#### Sunset Orange/Purple
```yaml
Background: #1a1b27
Primary: #FF6E96 (Pink)
Secondary: #FFA500 (Orange)
Text: #FFFFFF
Theme: dracula
```

#### Ocean Blue
```yaml
Background: #0d1117
Primary: #58A6FF (Blue)
Secondary: #1F6FEB (Dark Blue)
Text: #FFFFFF
Theme: github_dark
```

### How to Change Colors

**Find and replace these hex codes in README.md:**

1. **Background**: Search for `0D1117`
2. **Purple Accent**: Search for `A78BFA`
3. **Blue Accent**: Search for `60A5FA`
4. **Theme Name**: Search for `tokyonight`

---

## 🎭 Badge Styles

### Current Style: `for-the-badge`

### Available Styles

```markdown
<!-- Flat -->
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)

<!-- Flat Square -->
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

<!-- For The Badge (Current) -->
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

<!-- Plastic -->
![Python](https://img.shields.io/badge/Python-3776AB?style=plastic&logo=python&logoColor=white)

<!-- Social -->
![Python](https://img.shields.io/badge/Python-3776AB?style=social&logo=python&logoColor=white)
```

### Custom Badge Colors

```markdown
<!-- Syntax -->
![Label](https://img.shields.io/badge/Label-Text-HEX_COLOR?style=STYLE&logo=LOGO&logoColor=COLOR)

<!-- Examples -->
![Custom](https://img.shields.io/badge/Custom-Badge-A78BFA?style=for-the-badge)
![My_Tech](https://img.shields.io/badge/My_Tech-Stack-60A5FA?style=for-the-badge&logo=github)
```

**Find More Icons**: [Simple Icons](https://simpleicons.org/)

---

## 📊 GitHub Stats Customization

### Available Themes

```markdown
default, transparent, shadow, dark, radical, merko, gruvbox, 
tokyonight, onedark, cobalt, synthwave, highcontrast, dracula, 
prussian, monokai, vue, vue-dark, shades-of-purple, nightowl, 
buefy, blue-green, algolia, great-gatsby, darcula, bear, 
solarized-dark, solarized-light, chartreuse-dark, nord, 
gotham, material-palenight, graywhite, vision-friendly-dark, 
ayu-mirage, midnight-purple, calm, flag-india, omni, react, 
jolly, maroongold, yeblu, blueberry, slateorange, kacho_ga
```

### Custom Parameters

```markdown
<!-- Hide specific stats -->
&hide=stars,commits,prs,issues,contribs

<!-- Show icons -->
&show_icons=true

<!-- Include all commits -->
&count_private=true

<!-- Custom title -->
&custom_title=My%20GitHub%20Stats

<!-- Disable animations -->
&disable_animations=true

<!-- Hide border -->
&hide_border=true

<!-- Hide rank -->
&hide_rank=true

<!-- Line height -->
&line_height=27

<!-- Card width -->
&card_width=500
```

### Example Customizations

#### Minimalist Stats
```markdown
![Stats](https://github-readme-stats.vercel.app/api?username=YOUR_USERNAME&show_icons=true&theme=dark&hide_border=true&hide=prs&custom_title=GitHub%20Overview)
```

#### Detailed Stats
```markdown
![Stats](https://github-readme-stats.vercel.app/api?username=YOUR_USERNAME&show_icons=true&theme=radical&count_private=true&include_all_commits=true&line_height=27)
```

---

## 🔥 Streak Stats Customization

### Parameters

```markdown
<!-- Fire color -->
&fire=FF6E96

<!-- Ring color -->
&ring=58A6FF

<!-- Current streak number color -->
&currStreakNum=FFFFFF

<!-- Current streak label color -->
&currStreakLabel=58A6FF

<!-- Longest streak number color -->
&sideNums=FFFFFF

<!-- Longest streak label color -->
&sideLabels=58A6FF

<!-- Background -->
&background=0D1117

<!-- Border -->
&border=A78BFA

<!-- Stroke -->
&stroke=58A6FF

<!-- Dates color -->
&dates=FFFFFF
```

### Example
```markdown
![Streak](https://github-readme-streak-stats.herokuapp.com/?user=YOUR_USERNAME&theme=dark&hide_border=true&background=0D1117&ring=A78BFA&fire=60A5FA&currStreakLabel=FFFFFF&sideNums=A78BFA&sideLabels=60A5FA&dates=FFFFFF&border=A78BFA)
```

---

## 🏆 Trophy Customization

### Rank Options

```markdown
<!-- Show all ranks -->
&rank=SSS,SS,S,AAA,AA,A,B,C

<!-- Show only top ranks -->
&rank=SSS,SS,S

<!-- Hide specific ranks -->
&rank=-C,-B
```

### Themes

```markdown
flat, onedark, gruvbox, dracula, monokai, chalk, nord, 
alduin, darkhub, juicyfresh, buddhism, oldie, radical, 
onestar, discord, algolia, gitdimmed, tokyonight, matrix, 
apprentice, dark_dimmed, dark_lover
```

### Layout Options

```markdown
<!-- Column count (1-8) -->
&column=7

<!-- Row count -->
&row=2

<!-- Margin width -->
&margin-w=15

<!-- Margin height -->
&margin-h=15

<!-- No background -->
&no-bg=true

<!-- No frame -->
&no-frame=true
```

### Example
```markdown
![Trophy](https://github-profile-trophy.vercel.app/?username=YOUR_USERNAME&theme=radical&no-frame=true&no-bg=true&column=7&rank=SSS,SS,S,AAA,AA,A&margin-w=15&margin-h=15)
```

---

## 🐍 Snake Animation Customization

Edit `.github/workflows/snake.yml`:

### Custom Colors

```yaml
outputs: |
  dist/github-contribution-grid-snake-dark.svg?palette=github-dark
  dist/github-contribution-grid-snake.svg?color_snake=purple&color_dots=#bfd6f6,#8dbdff,#64a1f4,#4b91f1,#3c7dd9
```

### Color Palettes

```yaml
# Purple theme
color_snake=A78BFA&color_dots=#E9D5FF,#C4B5FD,#A78BFA,#8B5CF6,#7C3AED

# Blue theme
color_snake=60A5FA&color_dots=#DBEAFE,#93C5FD,#60A5FA,#3B82F6,#2563EB

# Green theme
color_snake=10B981&color_dots=#D1FAE5,#6EE7B7,#34D399,#10B981,#059669

# Pink theme
color_snake=EC4899&color_dots=#FCE7F3,#F9A8D4,#F472B6,#EC4899,#DB2777
```

### Schedule

```yaml
schedule:
  # Every 6 hours
  - cron: "0 */6 * * *"
  
  # Every 12 hours
  - cron: "0 */12 * * *"
  
  # Daily at midnight
  - cron: "0 0 * * *"
  
  # Weekly (Sunday at midnight)
  - cron: "0 0 * * 0"
```

---

## ✨ Typing Animation

### Current Animation

```markdown
https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&duration=3000&pause=1000&color=A78BFA&center=true&vCenter=true&multiline=false&width=800&height=70&lines=Building+Scalable+Backend+Systems;Exploring+Generative+AI+%26+LLMs
```

### Parameters

```markdown
font=Fira+Code              # Font family
weight=600                  # Font weight (100-900)
size=28                     # Font size
duration=3000               # Typing duration (ms)
pause=1000                  # Pause between lines (ms)
color=A78BFA                # Text color (hex without #)
center=true                 # Center align
vCenter=true                # Vertical center
multiline=false             # Single/Multi line
width=800                   # SVG width
height=70                   # SVG height
lines=Line1;Line2;Line3     # Text lines (semicolon separated)
```

### Custom Examples

```markdown
<!-- Fast typing -->
https://readme-typing-svg.demolab.com?font=Fira+Code&size=24&duration=2000&pause=500&color=60A5FA&center=true&lines=Fast+Typer;Backend+Developer;AI+Enthusiast

<!-- Slow, dramatic -->
https://readme-typing-svg.demolab.com?font=Courier+New&size=32&duration=5000&pause=2000&color=A78BFA&center=true&lines=Code.;Create.;Innovate.

<!-- Multiple colors (use multiple instances) -->
<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&color=A78BFA&lines=Backend+Developer"/>
<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&color=60A5FA&lines=AI+Enthusiast"/>
```

---

## 🎯 Profile View Counter

### Styles

```markdown
<!-- Flat -->
![Views](https://komarev.com/ghpvc/?username=YOUR_USERNAME&style=flat)

<!-- Flat Square -->
![Views](https://komarev.com/ghpvc/?username=YOUR_USERNAME&style=flat-square)

<!-- For The Badge (Current) -->
![Views](https://komarev.com/ghpvc/?username=YOUR_USERNAME&style=for-the-badge)

<!-- Plastic -->
![Views](https://komarev.com/ghpvc/?username=YOUR_USERNAME&style=plastic)
```

### Colors

```markdown
<!-- Named colors -->
blue, green, red, orange, yellow, brightgreen, blueviolet (current)

<!-- Hex colors (without #) -->
![Views](https://komarev.com/ghpvc/?username=YOUR_USERNAME&color=A78BFA&style=for-the-badge)
```

### Custom Label

```markdown
![Views](https://komarev.com/ghpvc/?username=YOUR_USERNAME&label=Visitors&color=blueviolet&style=for-the-badge)
```

---

## 🌊 Wave Separators

### Types

```markdown
<!-- Wave (Current) -->
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

<!-- Capsule Render Waves -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=100&section=footer"/>

<!-- Custom color wave -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:A78BFA,100:60A5FA&height=100"/>
```

### Capsule Render Types

```markdown
type=waving          # Wave animation
type=wave            # Static wave
type=slice           # Diagonal slice
type=shark           # Shark fin
type=cylinder        # 3D cylinder
type=rounded         # Rounded corners
type=rect            # Rectangle
type=soft            # Soft edges
type=transparent     # Transparent bg
```

---

## 📱 Layout Variations

### Centered Layout (Current)

```markdown
<div align="center">
  Content here
</div>
```

### Side-by-Side Stats

```markdown
<div align="center">
  <img width="49%" src="STATS_URL_1" />
  <img width="49%" src="STATS_URL_2" />
</div>
```

### Three Column

```markdown
<div align="center">
  <img width="32%" src="URL_1" />
  <img width="32%" src="URL_2" />
  <img width="32%" src="URL_3" />
</div>
```

### Collapsible Sections

```markdown
<details>
<summary>Click to expand</summary>

Hidden content here

</details>
```

---

## 🎬 Adding GIFs

### Recommended GIF Sources

- [GIPHY](https://giphy.com/)
- [Tenor](https://tenor.com/)
- [GitHub Octodex](https://octodex.github.com/)

### Usage

```markdown
<!-- Inline -->
<img src="GIF_URL" width="30px"/>

<!-- Block -->
<img src="GIF_URL" width="300px" align="center"/>

<!-- With link -->
<a href="URL"><img src="GIF_URL" width="200px"/></a>
```

### Popular Coding GIFs

```markdown
<!-- Typing -->
<img src="https://media.giphy.com/media/LmNwrBhejkK9EFP504/giphy.gif" width="200"/>

<!-- Coding -->
<img src="https://media.giphy.com/media/qgQUggAC3Pfv687qPC/giphy.gif" width="200"/>

<!-- Developer -->
<img src="https://media.giphy.com/media/ZVik7pBtu9dNS/giphy.gif" width="200"/>
```

---

## 💡 Pro Tips

1. **Test Locally**: Use a markdown previewer before pushing
2. **Cache Issues**: Add `?v=1`, `?v=2` to image URLs to force refresh
3. **Loading Speed**: Don't use too many external resources
4. **Mobile View**: Test how it looks on mobile
5. **Accessibility**: Add alt text to all images
6. **Keep Updated**: Update stats and projects regularly

---

## 🔗 Useful Resources

- [Shields.io](https://shields.io/) - Badge generator
- [Simple Icons](https://simpleicons.org/) - Brand icons
- [Devicon](https://devicon.dev/) - Developer icons
- [Readme Typing SVG](https://readme-typing-svg.demolab.com/demo/) - Live demo
- [GitHub Profile Readme Generator](https://arturssmirnovs.github.io/github-profile-readme-generator/)
- [Awesome GitHub Profile README](https://github.com/abhisheknaiidu/awesome-github-profile-readme)

---

**Happy Customizing! 🎨**
