# Wise Deal REI - Website

Professional real estate investment website for Wise Deal REI, Milwaukee, Wisconsin.

## 📁 Files Included

- `index.html` - Main website page with all sections
- `styles.css` - Professional styling
- `README.md` - This file

## ⚡ Quick Setup

### 1. Set Up Contact Form (Formspree)

To make the contact form work:

1. Go to [formspree.io](https://formspree.io)
2. Sign up with your email (wisedealrei1@gmail.com)
3. Create a new form
4. Copy your form endpoint (looks like: `f/abc123xyz`)
5. Open `index.html` in a text editor
6. Find this line: `action="https://formspree.io/f/YOUR_FORM_ID"`
7. Replace `YOUR_FORM_ID` with your actual form ID
8. Save the file

### 2. Push to GitHub

**Option A - Using Git Command Line:**

```bash
cd wisedealrei-website
git init
git add .
git commit -m "Initial Wise Deal REI website"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/wisedealrei.github.io.git
git push -u origin main
```

**Option B - Upload via GitHub Web:**

1. Go to your GitHub repo: `https://github.com/YOUR_USERNAME/wisedealrei.github.io`
2. Click **"Add file"** → **"Upload files"**
3. Drag and drop all files from this folder
4. Click **"Commit changes"**

### 3. Enable GitHub Pages

1. Go to your repo settings
2. Find **"Pages"** section
3. Set "Source" to `main` branch
4. Save

### 4. Connect Your Domain

**In GitHub:**
1. Go to repo **"Settings"** → **"Pages"**
2. Under "Custom domain," enter: `wisedealrei.com`
3. Click **"Save"**
4. GitHub will show DNS records needed

**In GoDaddy:**
1. Log into [GoDaddy.com](https://www.godaddy.com)
2. Go to your domain → **"Manage DNS"**
3. Add these A records:
   - `185.199.108.153`
   - `185.199.109.153`
   - `185.199.110.153`
   - `185.199.111.153`
4. Save changes (may take 10-30 min to activate)

## ✅ Your Site

Once deployed:
- **GitHub Pages URL:** `https://YOUR_USERNAME.github.io`
- **Custom Domain:** `https://wisedealrei.com` (after DNS updates)

## 📝 Customizing Content

Edit `index.html` to:
- Change property descriptions
- Add more properties
- Update contact information
- Modify any text

Edit `styles.css` to:
- Change colors (look for `--primary`, `--secondary`, `--accent`)
- Adjust fonts
- Modify spacing

## 🎨 Current Colors

- **Primary (Navy):** #001f3f
- **Secondary (Blue):** #0074d9
- **Accent (Orange):** #ff6b35

## 📧 Contact Info

- **Email:** wisedealrei1@gmail.com
- **Location:** Milwaukee, Wisconsin

## 📞 Support

- [GitHub Pages Docs](https://pages.github.com)
- [GoDaddy DNS Help](https://www.godaddy.com/help)
- [Formspree Help](https://formspree.io/help)

---

**Website ready to deploy!** 🚀
