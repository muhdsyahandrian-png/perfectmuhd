# 🎮 Syah Andrian Portfolio Website

Website biodata Syah Andrian dengan design gaming theme yang colorful dan creative!

## 🌟 Features

- ✅ Design creative & colorful dengan gaming theme
- ✅ Animasi smooth dan interactive
- ✅ Neon glow effects
- ✅ Responsive (cantik di phone & desktop)
- ✅ Particle effects & animations
- ✅ Cursor trail effect
- ✅ Ready untuk deploy!

## 📁 Files

```
syah-portfolio/
├── index.html          # Main website file
├── images/
│   └── profile.jpg     # Your profile picture (included!)
└── README.md          # Instructions ini
```

## 🚀 Cara Deploy ke Vercel

### Step 1: Upload ke GitHub

1. **Buat GitHub Account** (kalau belum ada)
   - Pergi ke https://github.com
   - Sign up percuma

2. **Buat Repository Baru**
   - Click button "New" atau "+" 
   - Nama repository: `syah-portfolio` (atau nama lain yang anda suka)
   - Set ke **Public**
   - Jangan check "Add README" (sebab kita dah ada)
   - Click "Create repository"

3. **Upload Files**
   - Dalam repository page, click "Add file" → "Upload files"
   - Drag & drop file `index.html` dan `README.md` 
   - Tulis commit message: "Initial commit"
   - Click "Commit changes"

### Step 2: Deploy ke Vercel

1. **Pergi ke Vercel**
   - Buka https://vercel.com
   - Click "Sign Up" atau "Login"
   - Login dengan **GitHub account** anda (paling senang!)

2. **Import Project**
   - Click "Add New..." → "Project"
   - Vercel akan tunjuk list GitHub repos anda
   - Cari `syah-portfolio` dan click "Import"

3. **Deploy!**
   - Vercel akan auto detect settings
   - Click "Deploy"
   - Tunggu 30-60 saat
   - ✅ **DONE!** Website dah live!

4. **Dapat URL**
   - Vercel akan bagi URL macam: `syah-portfolio.vercel.app`
   - Atau anda boleh set custom domain (optional)

## 🎨 Gambar Profile

Gambar profile anda **dah included** dalam folder `images/profile.jpg`! ✅

Bila upload ke GitHub, pastikan upload **folder `images` sekali** dengan file `profile.jpg` di dalamnya.

**Kalau nak tukar gambar later:**

### Option 1: Replace dalam GitHub
1. Pergi ke folder `images` dalam GitHub repo
2. Click `profile.jpg`
3. Click icon trash untuk delete
4. Upload gambar baru, **mesti nama `profile.jpg`** (sama nama!)
5. Commit changes
6. Vercel akan auto update!

### Option 2: Guna Imgur (Alternative)
1. Upload gambar baru ke Imgur
2. Copy **direct image link** (mesti end dengan .jpg atau .png)
3. Edit `index.html` → cari line:
   ```html
   <img src="images/profile.jpg" alt="Syah Andrian" class="profile-img">
   ```
4. Replace dengan:
   ```html
   <img src="LINK_IMGUR_ANDA.jpg" alt="Syah Andrian" class="profile-img">
   ```
5. Commit changes
6. Done!

## ✏️ Cara Edit Content

Nak tukar text atau maklumat? Senang je!

1. Dalam GitHub repo, click `index.html`
2. Click icon pencil (✏️) untuk edit
3. Cari text yang nak tukar (contoh: "Tentang Saya", skills, contact info)
4. Edit macam biasa
5. Scroll bawah → tulis commit message
6. Click "Commit changes"
7. Vercel akan auto update website! (dalam 30 saat)

## 🎯 Features Yang Ada

- **Neon Glow Effects** - Text dan gambar profile ada glow effect
- **Animated Background** - Background bergerak dengan gradient
- **Floating Particles** - Particles naik dari bawah ke atas
- **Hover Effects** - Cards naik bila hover
- **Cursor Trail** - Bila move mouse ada trail pink
- **Smooth Animations** - Semua element masuk dengan smooth
- **Responsive Design** - Cantik di phone, tablet, desktop

## 💡 Tips

- Website ni responsive, jadi test di phone & computer
- Semua dalam satu file `index.html` - senang maintain!
- Colors boleh tukar dalam CSS variables (atas sekali dalam `<style>`)
- Font guna Google Fonts (Bangers & Poppins) - free & auto load

## 🆘 Troubleshooting

**Gambar tak keluar?**
- Check link Imgur betul ke tak
- Try buka link dalam browser baru
- Pastikan gambar di Imgur set public

**Website tak update?**
- Tunggu 1-2 minit untuk Vercel deploy
- Try clear browser cache (Ctrl + Shift + R)
- Check GitHub - changes dah commit ke belum?

**Colors nak tukar?**
- Edit CSS variables dalam `<style>` section
- Cari `--neon-pink`, `--neon-blue`, etc
- Tukar dengan color code lain

## 📱 Preview

Website ada:
- Hero section dengan profile pic & nama
- About section
- Skills showcase
- Education/Experience
- Contact info
- Footer dengan copyright

Semua dengan **neon gaming theme** yang colorful! 🎮✨

## 🎊 Credits

Dibuat untuk **Syah Andrian** - Roblox Trader & Pro Gamer! 🏆

---

**Happy Gaming! 🎮**

Kalau ada masalah atau nak add features lagi, boleh edit `index.html` dalam GitHub!
