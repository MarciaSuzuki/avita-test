# AViTA – Aural-Visual Tagging App

Language Archive Builder for the Tripod Method

## About

AViTA helps facilitators and language workers tag oral language recordings with semantic metadata. It is part of the Ready Vessels Project for AI-assisted Bible translation.

## Folder Structure

```
avita-test/
├── index.html          # Main application
├── README.md           # This file
└── audio/              # Audio files go here
    ├── full_story.mp3  # Complete story for overview
    ├── segment_0.mp3   # Individual segments
    ├── segment_1.mp3
    └── ...
```

## Adding Your Audio Files

1. Place your **full story recording** in the `audio/` folder as `full_story.mp3`
2. Place your **segmented audio files** as `segment_0.mp3`, `segment_1.mp3`, etc.
3. Update the segment list in `index.html` if you have more or fewer segments

## Deploying to GitHub Pages

### Step 1: Create a GitHub Repository

1. Go to [github.com/new](https://github.com/new)
2. Name it `avita-test` (or your preferred name)
3. Set it to **Public**
4. Click **Create repository**

### Step 2: Upload Files

**Option A: Using GitHub web interface**
1. Click **"uploading an existing file"** link
2. Drag and drop all files from this folder
3. Click **Commit changes**

**Option B: Using Git command line**
```bash
cd avita-test
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/avita-test.git
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings** (tab at the top)
3. Click **Pages** (left sidebar)
4. Under "Source", select **Deploy from a branch**
5. Choose **main** branch and **/ (root)**
6. Click **Save**
7. Wait 1-2 minutes

### Step 4: Access Your App

Your app will be live at:
```
https://YOUR_USERNAME.github.io/avita-test/
```

## Testing on Mobile

The app works on phones and tablets. Share the GitHub Pages URL with your team. They can:
- Open it in any browser
- Add it to their home screen for quick access

## Updating the App

To update after making changes:
1. Edit files locally
2. Push to GitHub:
   ```bash
   git add .
   git commit -m "Description of changes"
   git push
   ```
3. GitHub Pages will automatically update (may take 1-2 minutes)

## Audio File Requirements

- **Format:** MP3 (recommended) or WAV
- **Segments:** Should be short clips (3-10 seconds each)
- **Naming:** Must match the names in the code (`segment_0.mp3`, etc.)

## Support

For questions about the Tripod Method or AViTA, contact the OBT Lab team.

---

*Ready Vessels Project – University of the Nations / YWAM Kansas City*
