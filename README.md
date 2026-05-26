# Amit Sah — Personal Website
## amitmesah.github.io

A creative, distinctive personal professional website built for European recruiters.

---

## 🚀 How to Deploy on GitHub Pages (Step by Step)

### Step 1 — Create the Repository

1. Go to [github.com](https://github.com) and sign in with your account (`amitmesah`)
2. Click the **+** button (top right) → **New repository**
3. Repository name: `amitmesah.github.io` *(must match exactly)*
4. Set to **Public**
5. Click **Create repository**

---

### Step 2 — Upload Your Files

**Option A — Simple Upload (recommended for beginners):**

1. Open your new repository on GitHub
2. Click **uploading an existing file**
3. Drag and drop `index.html` into the upload area
4. Scroll down → click **Commit changes**

**Option B — Using Git (if you have it installed):**

```bash
git clone https://github.com/amitmesah/amitmesah.github.io
cd amitmesah.github.io
# Copy your index.html here
git add .
git commit -m "Launch personal website"
git push origin main
```

---

### Step 3 — Enable GitHub Pages

1. Go to your repository → **Settings**
2. Scroll down to **Pages** (left sidebar)
3. Under **Source** → select **Deploy from a branch**
4. Branch: **main** · Folder: **/ (root)**
5. Click **Save**

---

### Step 4 — Your Site is Live!

Wait 2–3 minutes, then visit:
**https://amitmesah.github.io**

That's it. Free hosting, forever. ✅

---

## 📄 Adding Your CV for Download

1. Save your CV as `Amit_Sah_CV.pdf`
2. Upload it to your GitHub repository (same as Step 2)
3. In `index.html`, find this line:
   ```html
   <a href="#" class="contact-link">Download CV</a>
   ```
4. Change `href="#"` to `href="Amit_Sah_CV.pdf"`
5. Commit the change

---

## ✏️ How to Update Content

All content is in `index.html`. Open it in any text editor (Notepad, VS Code, etc.).

Key sections to update:
- **Hero stats** — search for `stat-number` to find the 19 / 50+ / $149M figures
- **Experience** — search for `exp-item` to find each role
- **Contact email** — search for `amitmesah@gmail.com`
- **LinkedIn URL** — search for `linkedin.com/in/amitmesah`

After editing, re-upload to GitHub and changes go live in ~1 minute.

---

## 🎨 What's Included

- ✅ Custom animated cursor
- ✅ Smooth scroll navigation with active highlights
- ✅ Scroll-reveal animations on all sections
- ✅ Full sections: Hero · About · Experience · Skills · Achievements · Certifications · Roadmap · Contact
- ✅ Mobile responsive
- ✅ No frameworks, no dependencies — pure HTML/CSS/JS
- ✅ Fast loading — works on all devices

---

## 📱 Sections

| Section | Content |
|---|---|
| Hero | Name, headline, tags, key stats |
| About | Summary, location, targeting |
| Experience | Full career timeline |
| Skills | 6 core competency cards |
| Achievements | 4 impact numbers |
| Certifications | All 9 credentials |
| Roadmap | Learning plan 2026 |
| Contact | Email, LinkedIn, CV download |

---

*Built with Claude · May 2026*
