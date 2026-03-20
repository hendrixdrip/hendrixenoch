# Arubu Enoch Portfolio Website

A simple, professional portfolio website ready to upload to GitHub Pages.

## 📁 File Structure

```
portfolio-static/
├── index.html        ← Home page
├── services.html     ← Services page
├── contact.html      ← Contact page
├── assets/
│   ├── styles.css    ← All styles
│   ├── photo.jpg     ← Your profile photo
│   └── logo.jpg      ← Your logo (also favicon)
└── README.md         ← This file
```

---

## 🚀 How to Upload to GitHub Pages (Beginner's Guide)

### Step 1: Create a GitHub Account
1. Go to **https://github.com**
2. Click **"Sign up"** and create your free account
3. Verify your email address

### Step 2: Create a New Repository
1. Click the **"+"** icon in the top right
2. Select **"New repository"**
3. Repository name: `yourusername.github.io`
   - Replace `yourusername` with YOUR GitHub username
   - Example: if your username is `enocharubu`, name it `enocharubu.github.io`
4. Select **"Public"**
5. Click **"Create repository"**

### Step 3: Upload Your Files
1. On the repository page, click **"uploading an existing file"**
2. Drag and drop ALL files from the `portfolio-static` folder:
   - `index.html`
   - `services.html`
   - `contact.html`
   - The entire `assets` folder
   - `README.md` (optional)
3. Scroll down and click **"Commit changes"**

### Step 4: Enable GitHub Pages
1. Go to your repository
2. Click **"Settings"** (gear icon)
3. In the left sidebar, click **"Pages"**
4. Under "Source", select **"Deploy from a branch"**
5. Under "Branch", select **"main"** and **"/ (root)"**
6. Click **"Save"**

### Step 5: View Your Website! 🎉
1. Wait 1-2 minutes for deployment
2. Go to **Settings → Pages**
3. You'll see: "Your site is live at **https://yourusername.github.io**"
4. Click the link to view your portfolio!

---

## 📧 Setting Up the Contact Form

The contact form needs **Formspree** to work (it's free!).

### Step 1: Create Formspree Account
1. Go to **https://formspree.io**
2. Sign up for a free account
3. Click **"New Form"**
4. Name it "Portfolio Contact"
5. Copy your form endpoint (looks like: `https://formspree.io/f/xabc1234`)

### Step 2: Update Your Contact Form
1. Open `contact.html` in a text editor
2. Find this line:
   ```html
   action="https://formspree.io/f/YOUR_FORM_ID"
   ```
3. Replace `YOUR_FORM_ID` with your actual Formspree ID
4. Save the file
5. Upload the updated file to GitHub

Now when someone submits the form, you'll receive an email!

---

## ✏️ How to Edit Your Website

### Edit Text Content
1. Open any `.html` file in a text editor (Notepad, VS Code, etc.)
2. Find the text you want to change
3. Edit it
4. Save the file
5. Upload to GitHub (replace the old file)

### Change Colors
1. Open `assets/styles.css`
2. Find the `:root` section at the top:
   ```css
   :root {
     --color-deep: #45496a;      /* Primary navy */
     --color-muted: #7d8bae;     /* Secondary blue-gray */
     --color-coral: #e5857b;     /* Accent coral/salmon */
     --color-light: #f1b2b2;     /* Light pink */
     --color-cream: #e8ccc7;     /* Cream background */
   }
   ```
3. Change any color value
4. Save and upload

### Update Your Photo or Logo
1. Replace `assets/photo.jpg` with your new photo (keep same filename)
2. Replace `assets/logo.jpg` with your new logo (keep same filename)
3. Upload to GitHub

---

## 📱 Features

- ✅ **Responsive Design** - Works on mobile, tablet, and desktop
- ✅ **Professional Look** - Clean, modern design
- ✅ **SEO Friendly** - Meta tags for search engines
- ✅ **Contact Form** - Working form with Formspree
- ✅ **Social Links** - Facebook, Instagram, WhatsApp
- ✅ **Fast Loading** - No external dependencies (except icons)

---

## 🔗 Your Links

- **Website**: https://yourusername.github.io
- **Email**: enocharubu@gmail.com
- **WhatsApp**: +234 905 688 0659
- **Facebook**: https://facebook.com/enocharubu
- **Instagram**: https://instagram.com/enocharubu

---

## 🆘 Troubleshooting

### "My website shows 404"
- Wait 5-10 minutes after uploading
- Make sure repository is named `yourusername.github.io` exactly
- Check Settings → Pages shows your site is live

### "My changes aren't showing"
- Hard refresh: Ctrl+F5 (Windows) or Cmd+Shift+R (Mac)
- Wait 1-2 minutes for GitHub to update

### "Contact form not working"
- Make sure you updated the Formspree URL in `contact.html`
- Check that your Formspree account is active

---

## 💡 Need Help?

- GitHub Pages Docs: https://docs.github.com/en/pages
- Formspree Help: https://help.formspree.io

---

**Made with ❤️ for Arubu Enoch**
