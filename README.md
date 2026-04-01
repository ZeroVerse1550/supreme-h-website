# Supreme H - DJ Portfolio Website

Professional portfolio website for Supreme H, a South African deep house DJ and music producer from Tsakane, East Rand.

## 🎵 About Supreme H

Supreme H is known for crafting emotionally charged, groove-driven music that moves both the body and the soul. Performing professionally since 2021, he has established himself as a focused and disciplined artist with a clear sonic identity rooted in deep and soulful house music.

## 🚀 Features

- **Modern Design**: Bold neon purple and cyan aesthetic with smooth animations
- **Responsive Layout**: Works perfectly on desktop, tablet, and mobile devices
- **Interactive Elements**: Smooth scroll animations, hover effects, and dynamic content
- **Artist Branding**: Prominent logo integration throughout the site
- **Music Integration**: Direct links to Spotify, YouTube, Apple Music, and SoundCloud
- **Complete Discography**: Showcases all releases from 2024-2025
- **Booking Section**: Easy contact via WhatsApp, email, and social media

## 📁 Repository Structure

```
supreme-h-website/
├── index.html                 # Main HTML file
├── assets/
│   ├── css/
│   │   └── style.css         # All styling
│   ├── js/
│   │   └── main.js           # JavaScript for interactions
│   └── images/
│       ├── logo.png          # Supreme H logo (Designer.png)
│       ├── about.jpg         # About section image
│       └── gallery/
│           ├── image1.jpg    # Gallery image 1
│           ├── image2.jpg    # Gallery image 2
│           ├── image3.jpg    # Gallery image 3
│           ├── image4.jpg    # Gallery image 4
│           ├── image5.jpg    # Gallery image 5
│           └── image6.jpg    # Gallery image 6
├── README.md                  # This file
└── .gitignore                # Git ignore file
```

## 📝 Setup Instructions

### 1. Create the Repository Structure

```bash
# Create the main directory
mkdir supreme-h-website
cd supreme-h-website

# Create subdirectories
mkdir -p assets/css
mkdir -p assets/js
mkdir -p assets/images/gallery
```

### 2. Add Your Files

- Place `index.html` in the root directory
- Place `style.css` in `assets/css/`
- Place `main.js` in `assets/js/`
- Place your **logo image** (Designer.png) as `assets/images/logo.png`
- Choose one of your **photos** for the About section and save as `assets/images/about.jpg`
- Place **6 gallery images** (from the 10 photos you provided) in `assets/images/gallery/` named:
  - `image1.jpg` through `image6.jpg`

### 3. Recommended Image Selection

From your uploaded photos, I recommend:

**For About Section** (`assets/images/about.jpg`):
- Use Image 1 (purple shirt, blue wall) - professional and engaging

**For Gallery** (pick 6 from these):
- Image 2 (white shirt, hand gestures)
- Image 3 (sunglasses, chain)
- Image 5 (DJ booth, blue/yellow lighting)
- Image 6 (headphones, DJ performance)
- Image 7 (headphones, focused)
- Image 8 (white shirt, clean portrait)

### 4. Initialize Git Repository

```bash
# Initialize repository
git init

# Create .gitignore file
echo "# macOS
.DS_Store
.AppleDouble
.LSOverride

# Windows
Thumbs.db
ehthumbs.db
Desktop.ini

# Editor directories
.vscode/
.idea/
*.swp
*.swo

# Temporary files
*.log
*.tmp
" > .gitignore

# Add all files
git add .

# Initial commit
git commit -m "Initial commit: Supreme H portfolio website"
```

### 5. Push to GitHub

```bash
# Create repository on GitHub (via website)
# Then connect local repository to GitHub:

git remote add origin https://github.com/YOUR_USERNAME/supreme-h-website.git
git branch -M main
git push -u origin main
```

## 🌐 Deployment Options

### Option 1: GitHub Pages (Free)

1. Go to your repository on GitHub
2. Click **Settings** → **Pages**
3. Under "Source", select **main** branch
4. Click **Save**
5. Your site will be live at: `https://YOUR_USERNAME.github.io/supreme-h-website/`

### Option 2: Netlify (Free, with custom domain support)

1. Go to [netlify.com](https://netlify.com)
2. Click "Add new site" → "Import an existing project"
3. Connect to your GitHub repository
4. Deploy! (automatic builds on every commit)
5. Optionally add custom domain

### Option 3: Vercel (Free, fast deployment)

1. Go to [vercel.com](https://vercel.com)
2. Click "New Project"
3. Import your GitHub repository
4. Deploy automatically

## 🎨 Customization

### Update Content

- **Personal Info**: Edit contact details in the HTML (phone, email, social links)
- **Music Links**: Update Spotify, YouTube, Apple Music, SoundCloud URLs
- **Discography**: Add new releases by editing the discography section
- **Colors**: Modify CSS variables in `style.css` (lines 1-8)

### Update Images

Simply replace the image files in the `assets/images/` directory while keeping the same filenames.

## 🔧 Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with animations and gradients
- **JavaScript**: Smooth scrolling and scroll reveal effects
- **Google Fonts**: Bebas Neue, Oswald font families

## 📱 Contact & Booking

- **Phone/WhatsApp**: +27 78 396 2342
- **Email**: supremeh34@gmail.com
- **Location**: Tsakane, East Rand, South Africa

## 📄 License

All rights reserved © 2025 Supreme H

---

**Built with passion for deep house music** 🎵
