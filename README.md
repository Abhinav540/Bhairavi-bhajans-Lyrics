# Bhairavi Bhajans - Lyrics Website

A simple HTML website to view bhajan lyrics on stage, hosted on GitHub Pages.

## Features
- Home page with all songs as hyperlinks
- Each song opens its own lyrics page
- **Back to Home** button on every lyrics page
- Search to find bhajans quickly
- Dark mode for stage reading
- Adjustable font size (A+ / A-)
- Songs without lyrics show **NO LYRICS** in red
- Pitch & section markings shown for musicians

## How to add / edit bhajans

Open `index.html` and find the `bhajans` array.

**Song with lyrics:**
```javascript
{
    title: "Song Name",
    lyrics: `Line one of lyrics
Line two of lyrics
Line three of lyrics`
}
```

**Song without lyrics (shows NO LYRICS in red):**
```javascript
{
    title: "Song Name",
    lyrics: null
}
```

**Musical markings** (Pitch, section names, etc.) — start the line with `~`:
```javascript
{
    title: "Song Name",
    lyrics: `~Pitch - A
~Starting singers
line one of lyrics`
}
```

## How to host on GitHub Pages
1. Create a new repository on GitHub
2. Push this folder to the repository
3. Go to **Settings → Pages**
4. Under "Branch", select `main` and `/ (root)`, then Save
5. Your site will be live at:
   `https://YOUR_USERNAME.github.io/REPO_NAME/`
