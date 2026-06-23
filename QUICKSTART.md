# 📋 QUICK START GUIDE

## 🚀 Deploy Your Portfolio in 5 Minutes

### **Step 1: Choose Your Platform**

Pick ONE of these three options:

#### Option A: GitHub Pages (EASIEST)
1. Go to: https://github.com/sbjboymbongo-sys/portfolio/settings/pages
2. Source: `Deploy from branch` → `main` → `/root`
3. Wait 2-3 minutes
4. **Live at:** https://sbjboymbongo-sys.github.io/portfolio

#### Option B: Netlify (RECOMMENDED)
1. Go to: https://app.netlify.com
2. "Add new site" → Connect GitHub → Select portfolio repo
3. Deploy settings: Build command (empty), Publish directory (`.`)
4. Click Deploy
5. **Live at:** (Netlify URL will appear)

#### Option C: Vercel (BEST PERFORMANCE)
1. Go to: https://vercel.com
2. "New Project" → Import repository → Select portfolio
3. Click Deploy
4. **Live at:** (Vercel URL will appear)

---

### **Step 2: Add Your CV** (5 minutes)
1. Create folder in repo: `assets/`
2. Upload your PDF: `CV_Jeremie_Boymbongo.pdf`
3. The download button already points to it!

---

### **Step 3: Setup Contact Form** (5 minutes)
1. Go to: https://formspree.io
2. Create account → New form
3. Copy your Form ID (looks like: `f_xxxxxxxxx`)
4. Edit `index.html` line ~270:
   ```javascript
   const response = await fetch('https://formspree.io/f/YOUR_FORM_ID', {
   ```
5. Replace `YOUR_FORM_ID` with your actual ID
6. Push to GitHub
7. Done! Form will work on live site

---

### **Step 4: Update Your Photo** (2 minutes)
1. Open `index.html`
2. Find: `<img src="https://via.placeholder.com/800x1000?text=JEREMIE+BOYMBONGO"`
3. Replace with your photo URL
4. Push changes
5. Live site updates automatically!

---

## ✅ Verification Checklist

After deployment, test these:

- [ ] Site loads on the live URL
- [ ] Dark mode toggle works
- [ ] Mobile looks good (test on phone)
- [ ] CV download button works
- [ ] Contact form submits
- [ ] Social links work
- [ ] Animations load smoothly

---

## 📞 Need Help?

See **DEPLOYMENT.md** for detailed troubleshooting and advanced setup.

---

**That's it! Your portfolio is live! 🎉**

---

## 💡 Pro Tips

✅ **GitHub Pages**: Simplest, no extra setup needed
✅ **Netlify**: Best forms & deployment features  
✅ **Vercel**: Fastest performance & best SEO

All three are **FREE** and auto-update when you push to GitHub!

---

**Questions?** Check the full [DEPLOYMENT.md](./DEPLOYMENT.md) guide
