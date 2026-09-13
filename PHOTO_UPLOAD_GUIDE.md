# 📸 Adding Photos to Your Birthday Website

## Quick Upload Instructions

### Option 1: Upload via GitHub Web Interface (Easiest)

1. Go to your repository: https://github.com/golumonu/bachcha-birthday
2. Click **"Add file"** → **"Upload files"**
3. Create a new folder named `images`
4. Upload your photos with these names:
   - `photo1.jpg` (Image 1 - Traditional attire mirror selfie)
   - `photo2.jpg` (Image 3 - Checkered shirt selfie)
   - `photo3.jpg` (Image 2 - Close-up with emojis)
   - `photo5.jpg` (Image 4 top - Leopard spots face paint)
   - `photo6.jpg` (Image 4 bottom - Leopard spots with friends)
   - `photo7.jpg` (Any additional photo)

5. Commit the changes

### Option 2: Using Git Command Line

```bash
# Clone your repo
git clone https://github.com/golumonu/bachcha-birthday.git
cd bachcha-birthday

# Create images folder
mkdir images

# Copy your 6 photos to the images folder
# photo1.jpg, photo2.jpg, photo3.jpg, photo5.jpg, photo6.jpg, photo7.jpg

# Push to GitHub
git add images/
git commit -m "Add birthday photos"
git push origin main
```

## 🌐 View Your Website

Once photos are uploaded, your live site will be at:
**https://golumonu.github.io/bachcha-birthday**

The gallery will automatically display your photos in a beautiful 2-column grid layout!

---

**Tips:**
- Use `.jpg` or `.png` formats
- Recommended size: 1000x1000px or larger (the site will optimize them)
- All 6 photos are referenced in the gallery, so upload all of them
