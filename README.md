# 🌍 Portfolio - Sem Jérémie Boymbongo-Ndoye

Professional portfolio of **Sem Jérémie Boymbongo-Ndoye**, Civil Engineer and Climate Change Researcher specializing in sustainable infrastructure and climate adaptation in Africa.

## 📋 Features

- ✨ **Modern, Responsive Design** - Built with Tailwind CSS
- 🌓 **Dark Mode Support** - Toggle between light and dark themes
- 📱 **Mobile Optimized** - Works seamlessly on all devices
- 🎨 **Smooth Animations** - AOS (Animate On Scroll) integration
- 📧 **Contact Form** - Integrated with Formspree for email submissions
- 📥 **CV Download** - Direct download functionality
- 🌐 **Multi-language Ready** - French, English, and Arabic support
- ♿ **Accessible** - WCAG compliant

## 🚀 Live Demo

**GitHub Pages:** [sbjboymbongo-sys.github.io/portfolio](https://sbjboymbongo-sys.github.io/portfolio)

## 🛠️ Tech Stack

- HTML5
- Tailwind CSS
- Font Awesome Icons
- AOS (Animate On Scroll)
- Formspree (Contact Form)

## 📂 Project Structure

```
portfolio/
├── index.html           # Main portfolio page
├── assets/
│   └── CV_Jeremie_Boymbongo.pdf    # Curriculum Vitae
├── .gitignore          # Git ignore rules
└── README.md           # This file
```

## 📦 Setup & Deployment

### Option 1: GitHub Pages (Automatic)
1. Repository is public
2. Go to **Settings → Pages**
3. Source: `Deploy from branch`
4. Branch: `main` / Folder: `/ (root)`
5. Site will be live at: `https://sbjboymbongo-sys.github.io/portfolio`

### Option 2: Netlify (Recommended)
1. Go to [netlify.com](https://netlify.com)
2. Click **"New site from Git"**
3. Connect GitHub → Select **portfolio** repo
4. Build command: (leave empty - static site)
5. Publish directory: `.` (root)
6. Deploy! 🎉

### Option 3: Vercel
1. Go to [vercel.com](https://vercel.com)
2. Import the GitHub repository
3. Click **Deploy**
4. Automatic updates on every push!

## 📝 Configuration

### Update CV Download Link
1. Add your PDF to `assets/CV_Jeremie_Boymbongo.pdf`
2. The download link in `index.html` already points to it:
```html
<a href="./assets/CV_Jeremie_Boymbongo.pdf" download="CV_Jeremie_Boymbongo.pdf">
```

### Setup Contact Form
1. Go to [formspree.io](https://formspree.io)
2. Create a new form and get your Form ID
3. Replace `xyzabcd` in `index.html` with your Form ID:
```javascript
const response = await fetch('https://formspree.io/f/YOUR_FORM_ID', {
```

### Customize Content
- **Navigation**: Edit nav links in the `<nav>` section
- **Hero Section**: Update title, description, and buttons
- **Research Section**: Modify research areas and descriptions
- **Contact**: Update email, phone, and social links
- **Colors**: Change Tailwind theme in `<script>` tag:
  - `primary`: `#0F172A` (Deep Blue)
  - `secondary`: `#16A34A` (Green)
  - `accent`: `#38BDF8` (Sky Blue)

## 🌐 Multi-Language Support

The site supports FR, EN, and AR. To complete translations, expand the i18n system in the JavaScript section.

## 📊 SEO Optimization

- Meta tags for search engines
- Keywords: Civil Engineering, Climate Change, PAUWES, etc.
- Semantic HTML structure
- Mobile-friendly design

## 🔗 Social & Contact Links

- **Email**: sbjboymbongo@gmail.com
- **Phone**: +236 72 75 87 38
- **LinkedIn**: [Profile Link](https://www.linkedin.com/in/sem-jérémie-boymbongo-ndoye-892985279)
- **Twitter/X**: [@jeremie_se25328](https://x.com/jeremie_se25328)
- **Instagram**: [@72758738sbj](https://www.instagram.com/72758738sbj)

## 📄 License

© 2024 SEM JÉRÉMIE BOYMBONGO-NDOYE. All rights reserved.

## ✨ Future Enhancements

- [ ] Blog section
- [ ] Project gallery
- [ ] Case studies
- [ ] Publications/Research papers
- [ ] Team/Collaborations section
- [ ] Full i18n implementation

---

**Last Updated**: 2024  
**Status**: 🟢 Live
