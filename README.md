# Hardik Bhatia — Matrimonial Biodata Website

A beautiful, responsive single-page biodata website.

## Structure

```
BioData/
├── index.html          ← Main website file
├── photos/             ← Drop your photos here
│   ├── photo-1.jpeg
│   ├── photo-2.jpeg
│   ├── photo-3.jpeg
│   └── photo-4.jpeg
└── README.md
```

## Adding / Removing Photos

1. Add your image files to the `photos/` folder (jpeg, jpg, png, webp all work)
2. Name them: `photo-1.jpeg`, `photo-2.jpeg`, etc.
3. Open `index.html` and update the photos array at the top of the `<script>` section:

```javascript
const photos = [
    'photos/photo-1.jpeg',
    'photos/photo-2.jpeg',
    'photos/photo-3.jpeg',
    'photos/photo-4.jpeg',
    'photos/photo-5.jpeg',  // ← add new ones here
];
```

4. The hero/profile photo is always `photos/photo-1.jpeg`

## Hosting on GitHub Pages

1. Create a GitHub repo (e.g., `biodata`)
2. Push this folder:
   ```bash
   cd /Users/hardikhh/Documents/BioData
   git init
   git add .
   git commit -m "Initial biodata website"
   git remote add origin https://github.com/YOUR_USERNAME/biodata.git
   git branch -M main
   git push -u origin main
   ```
3. Go to repo **Settings → Pages → Source: main branch → Save**
4. Your site will be live at: `https://YOUR_USERNAME.github.io/biodata/`

## Custom Domain (Optional)

If you buy a domain (e.g., `hardikbhatia.com`):
1. Add a `CNAME` file with your domain name
2. Configure DNS at your registrar to point to GitHub Pages
