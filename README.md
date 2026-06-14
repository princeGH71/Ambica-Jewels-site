# Ambica Jewellers — Website

A luxury static gallery website for Ambica Jewellers.
Built with HTML, CSS, and vanilla JavaScript. No frameworks needed.

---

## 📁 Folder Structure

```
ambica-jewellers/
├── index.html               ← Main website file
├── css/
│   └── style.css            ← All styles
├── js/
│   └── main.js              ← Interactions (filter, animations)
├── images/
│   ├── necklaces/           ← Add necklace photos here
│   ├── earrings/            ← Add earring photos here
│   ├── bangles/             ← Add bangle photos here
│   ├── rings/               ← Add ring photos here
│   ├── sets/                ← Add bridal set photos here
│   ├── maang-tikka/         ← Add tikka photos here
│   └── about-store.jpg      ← Add your store photo here
└── README.md
```

---

## 🖼 How to Add Your Jewellery Images

1. Name your images exactly as listed in `index.html`:
   - `images/necklaces/necklace-01.jpg`, `necklace-02.jpg`, `necklace-03.jpg`
   - `images/earrings/earring-01.jpg`, etc.
   - `images/bangles/bangle-01.jpg`, etc.
   - `images/rings/ring-01.jpg`, etc.
   - `images/sets/set-01.jpg`, etc.
   - `images/maang-tikka/tikka-01.jpg`, etc.
2. Drop them in the correct folder
3. Commit and push to GitHub → site updates automatically!

**To add more images**, copy a gallery item block in `index.html` and change the filename.

---

## ✏️ How to Update Your Details

Open `index.html` and find these sections:

- **Address**: Search for "Your Shop Address Here" and replace
- **Phone**: Search for "+91 00000 00000" and replace with your number
- **WhatsApp**: Change the number in `https://wa.me/910000000000`
- **Store Hours**: Update in the Contact section

---

## 🚀 Deployment Guide (GitHub + Netlify)

### Step 1 — Push to GitHub

1. Create a free account at https://github.com
2. Create a new repository called `ambica-jewellers`
3. Upload all files OR use Git commands:

```bash
git init
git add .
git commit -m "Initial website launch"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/ambica-jewellers.git
git push -u origin main
```

### Step 2 — Connect Netlify to GitHub

1. Go to https://netlify.com and sign up (free)
2. Click **"Add new site" → "Import an existing project"**
3. Choose **GitHub**
4. Authorize Netlify and select your `ambica-jewellers` repo
5. Settings:
   - Branch: `main`
   - Build command: *(leave empty)*
   - Publish directory: `.` (just a dot)
6. Click **"Deploy site"**

✅ Your site is now live at `something.netlify.app`!

### Step 3 — Connect Custom Domain

1. In Netlify → Site Settings → Domain Management → Add custom domain
2. Enter `ambicajewellers.com` (or your domain)
3. Netlify gives you nameservers like `dns1.p05.nsone.net`
4. Go to your domain registrar (Namecheap / GoDaddy)
5. Replace nameservers with the ones Netlify gave you
6. Wait up to 24 hours

### ✅ Auto-Deploy is now active!

Every time you push changes to GitHub, Netlify automatically redeploys your site within ~30 seconds.

---

## 🎨 Customization Tips

| What to change | Where |
|---|---|
| Brand colors | `css/style.css` → `:root` variables at top |
| Tagline | `index.html` → Hero section |
| Category names | `index.html` → filter buttons + gallery items |
| Add new items | Copy a `gallery-item` div in `index.html` |
| Footer text | `index.html` → Footer section |

---

Made with ❤️ for Ambica Jewellers — Est. 1989
