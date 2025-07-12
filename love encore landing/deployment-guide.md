# Detailed Deployment Guide for Love-Encore

## Step 1: Prepare Your Files

### Check you have these files:
- [x] index.html (main website)
- [x] qr-code.html (QR generator)
- [ ] kaegan-photo.jpg (your photo - YOU NEED TO ADD THIS)
- [ ] love-encore-banner.png (Love-Encore logo - YOU NEED TO ADD THIS)

### Add your images:
1. Take your professional photo and save it as `kaegan-photo.jpg`
2. Save the Love-Encore banner image as `love-encore-banner.png`
3. Put both images in this folder

## Step 2: Create GitHub Account

1. Go to https://github.com
2. Click "Sign up"
3. Create your account (free)
4. Verify your email

## Step 3: Create a New Repository

1. Once logged in, click the "+" icon (top right)
2. Select "New repository"
3. Name it: `love-encore`
4. Description: "Love-Encore scheduling page"
5. Make it PUBLIC
6. DON'T initialize with README
7. Click "Create repository"

## Step 4: Upload Your Files

1. On the empty repository page, click "uploading an existing file"
2. Drag ALL files from this folder into the browser:
   - index.html
   - qr-code.html
   - kaegan-photo.jpg
   - love-encore-banner.png
   - README.md
   - deployment-guide.md
3. Write commit message: "Initial Love-Encore site"
4. Click "Commit changes"

## Step 5: Deploy with Vercel

1. Go to https://vercel.com
2. Click "Sign up"
3. Choose "Continue with GitHub"
4. Authorize Vercel to access your GitHub

### Import and Deploy:
1. Click "New Project"
2. Find and import your `love-encore` repository
3. Project settings should be automatic (no changes needed)
4. Click "Deploy"
5. Wait 30-60 seconds

### Your site is now live!
You'll see a URL like: `https://love-encore-git-main-yourusername.vercel.app`

## Step 6: Get a Clean URL

1. In Vercel dashboard, go to your project
2. Click "Settings" → "Domains"
3. You'll see your production domain
4. It might look like: `https://love-encore.vercel.app`

## Step 7: Generate Your QR Code

1. Open `qr-code.html` in a text editor (like Notepad)
2. Find this line:
   ```javascript
   const YOUR_WEBSITE_URL = 'https://love-encore.vercel.app';
   ```
3. Replace with your actual Vercel URL
4. Save the file
5. Open `qr-code.html` in your browser
6. Right-click the QR code → "Save image as..." → Save as "love-encore-qr.png"

## Step 8: Test Everything

1. **Test the website:**
   - Visit your Vercel URL
   - Check all links work
   - Verify phone numbers are clickable
   - Test Calendly button
   - Test Gifts for Good link

2. **Test the QR code:**
   - Scan with your phone
   - Verify it goes to your site
   - Test on both iPhone and Android

## Step 9: Print Your QR Codes

### Recommended sizes:
- Business cards: 1" x 1"
- Flyers/Brochures: 2" x 2"
- Desk displays: 3" x 3"
- Posters: 4" x 4" or larger

### Printing tips:
- Use high-resolution printing
- Keep good contrast (dark blue on white)
- Leave white space around the QR code
- Test one before printing many

## Step 10: Future Updates

To update your site:
1. Edit the files on your computer
2. Go to your GitHub repository
3. Click "Upload files"
4. Upload the changed files
5. Vercel auto-deploys in ~30 seconds

## Troubleshooting

### QR code won't scan:
- Make sure it's printed large enough
- Check lighting conditions
- Try different QR scanner apps

### Website not loading:
- Check the URL is correct
- Clear browser cache
- Verify Vercel deployment status

### Images not showing:
- Verify file names match exactly
- Check files were uploaded to GitHub
- Make sure image files aren't too large (keep under 2MB)

## Need Help?

- Vercel Support: https://vercel.com/support
- GitHub Docs: https://docs.github.com
- Or call Kaegan: (505) 428-5562