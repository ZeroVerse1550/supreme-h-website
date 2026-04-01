# Quick Setup Guide for Supreme H Website

## Step-by-Step Instructions

### 1. Download All Files

Download these 4 files from Claude:
- `index.html`
- `style.css`
- `main.js`
- `README.md`

### 2. Create Folder Structure

On your computer, create this exact folder structure:

```
supreme-h-website/
├── index.html
├── README.md
├── assets/
│   ├── css/
│   │   └── style.css
│   ├── js/
│   │   └── main.js
│   └── images/
│       ├── logo.png
│       ├── about.jpg
│       └── gallery/
│           ├── image1.jpg
│           ├── image2.jpg
│           ├── image3.jpg
│           ├── image4.jpg
│           ├── image5.jpg
│           └── image6.jpg
```

### 3. Add Your Images

**Logo** (`assets/images/logo.png`):
- Use the Designer.png file (the Supreme H logo)

**About Photo** (`assets/images/about.jpg`):
- I recommend: Image 1 (purple shirt, blue wall)

**Gallery Photos** (pick 6 and name them image1.jpg through image6.jpg):
- Suggested: Images 2, 3, 5, 6, 7, 8 from your collection

### 4. Test Locally

1. Double-click `index.html` to open in your browser
2. Check that all images load correctly
3. Test all navigation links
4. Check responsive design (resize browser window)

### 5. Push to GitHub

**Create Repository:**
1. Go to GitHub.com and sign in
2. Click the "+" button (top right) → "New repository"
3. Name it: `supreme-h-website`
4. Make it Public
5. Don't initialize with README (you already have one)
6. Click "Create repository"

**Upload Files:**

**Option A - Use GitHub Website (Easiest):**
1. On your new repository page, click "uploading an existing file"
2. Drag and drop your entire `supreme-h-website` folder
3. Write commit message: "Initial commit: Supreme H portfolio"
4. Click "Commit changes"

**Option B - Use Command Line:**
```bash
cd supreme-h-website
git init
git add .
git commit -m "Initial commit: Supreme H portfolio website"
git remote add origin https://github.com/YOUR_USERNAME/supreme-h-website.git
git branch -M main
git push -u origin main
```

### 6. Deploy to GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings** (top menu)
3. Click **Pages** (left sidebar)
4. Under "Source", select **main** branch
5. Click **Save**
6. Wait 1-2 minutes
7. Your site will be live at:
   `https://YOUR_USERNAME.github.io/supreme-h-website/`

### 7. Share Your Website!

Once live, share the link:
- On social media
- In your bio
- With promoters and venues
- On business cards

## Need Help?

If something doesn't work:
1. Check that all files are in the correct folders
2. Make sure image filenames match exactly (case-sensitive)
3. Verify images are in JPG or PNG format
4. Check browser console for errors (F12 key)

## Updating Content

To update your website:
1. Edit the files on your computer
2. Upload changes to GitHub (same process as step 5)
3. GitHub Pages will automatically update in 1-2 minutes

---

**You're ready to go live! 🚀**
