# Quick Start Guide for Craft Fair

## Your Website is LIVE! 🎉

**URL:** https://jtwm-0677.github.io/LxL3D-Printing

## What You Have

✅ Professional website with:
- Services showcase
- Contact form
- Mobile-friendly design
- Purple gradient theme

✅ Table tent with:
- QR code (auto-generated)
- Business name and tagline
- Services list
- Website URL

## Steps to Print Your Table Tent

1. **Open the file:**
   - Navigate to: `C:\Development\LxL3D Printing Website\table-tent.html`
   - Double-click to open in your browser

2. **Wait for QR code:**
   - The QR code will appear automatically (takes 1-2 seconds)
   - It will be purple/blue and scannable

3. **Print:**
   - Press `Ctrl + P` (or File > Print)
   - Settings:
     - Paper size: Letter (8.5" x 11")
     - Orientation: Portrait
     - Margins: None or Minimal
     - Background graphics: ON (important for colors!)
   - Print or Save as PDF

4. **Fold:**
   - Fold the paper in HALF along the dotted line
   - Portrait orientation (hamburger style, not hotdog)
   - Both sides will face outward when standing

## Testing Your QR Code

1. Open the table tent in your browser
2. Use your phone's camera to scan the QR code on screen
3. It should take you to: https://jtwm-0677.github.io/LxL3D-Printing

## At the Craft Fair

- Stand the table tent on your table (folded in half)
- Customers scan the QR code to:
  - See your services
  - Fill out the contact form
  - Get your website URL

## Form Submissions

The contact form currently stores submissions in the browser's localStorage. To view submissions:
1. Open your website
2. Press F12 (developer tools)
3. Go to Console tab
4. Type: `JSON.parse(localStorage.getItem('formSubmissions'))`

**Note:** For a production solution, you'll want to set up a proper form backend (like Formspree, Netlify Forms, or Google Forms).

## Need to Make Changes?

1. Edit the files locally
2. Run:
   ```bash
   git add .
   git commit -m "Update website"
   git push
   ```
3. Changes will appear on your website in 1-2 minutes

## Troubleshooting

**QR code not showing?**
- Make sure you're connected to the internet (uses CDN)
- Refresh the page

**Colors not printing?**
- Enable "Background graphics" in print settings
- Try "Print to PDF" first to preview

**Website not updating?**
- Wait 1-2 minutes after pushing
- Clear your browser cache
- GitHub Pages can take a moment to rebuild

---

Good luck at your craft fair! 🎨🖨️
