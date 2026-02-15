# Portfolio Setup Instructions

## Files Included
- `index.html` - Your complete portfolio website

## Setup Steps

### 1. Download the Files
Download `index.html` from this folder.

### 2. Add Your Profile Picture
Save your professional photo as `profile.jpg` in the **same folder** as `index.html`:
- Recommended size: 280x280 pixels minimum
- Format: JPG
- Square aspect ratio works best
- Professional headshot with good lighting

### 3. Add Your CV
Place your `Asad_Mehmood_CV.pdf` file in the same folder.

### 4. Test Locally
1. Double-click `index.html` to open in your browser
2. You should see your complete portfolio
3. Check that all sections load properly

### 5. Upload to GitHub
```bash
# In your GitHub repository folder
git add index.html profile.jpg Asad_Mehmood_CV.pdf
git commit -m "Update portfolio website"
git push origin main
```

### 6. Enable GitHub Pages
1. Go to your repository settings
2. Navigate to "Pages" section
3. Select "main" branch as source
4. Your site will be live at: `https://asadmehmood2.github.io/`

## Folder Structure Should Look Like:
```
your-repo/
├── index.html
├── profile.jpg (your photo)
├── Asad_Mehmood_CV.pdf
└── README.md
```

## Troubleshooting

**If the page looks empty:**
- Make sure you're opening `index.html` in a web browser (Chrome, Firefox, Safari)
- Check browser console for errors (F12 key)
- Ensure all files are in the same directory

**If profile picture doesn't show:**
- Verify the image is named exactly `profile.jpg` (case-sensitive)
- Try a different image format if needed

**If CV download doesn't work:**
- Ensure `Asad_Mehmood_CV.pdf` is in the same folder
- Check the filename matches exactly

## Customization

### Updating Content
The HTML file is well-organized with comments marking each section:
- Hero Section (lines ~805-822)
- About Section (lines ~824-875)
- Expertise Section
- Projects Section  
- Publications Section
- Certifications Section
- Contact Section

### Changing Colors
Edit the CSS variables at the top of the file (lines 15-31):
```css
:root {
    --primary: #0a192f;      /* Dark background */
    --accent: #64ffda;       /* Cyan accent color */
    --text: #ccd6f6;         /* Light text */
}
```

## Need Help?
If something isn't working, check:
1. All files are in the correct location
2. File names match exactly (case-sensitive)
3. Browser console for error messages
4. That you're viewing in a modern browser

Your portfolio is ready to showcase your work professionally!
