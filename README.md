# Sarweshwor — Portfolio Site
## Complete guide: test locally → GitHub → live on the internet

---

## 📁 What's in this folder

| File | What it is |
|---|---|
| `index.html` | Your main portfolio website |
| `socialsphere.html` | SocialSphere app (social media) |
| `swiftchat.html` | SwiftChat app (messaging) |
| `pixelforge.html` | PixelForge app (pixel art editor) |
| `flowtask.html` | FlowTask app (task manager) |
| `bnbbooking.html` | BnB Booking app (your IT7537 project) |

> ⚠️ All 6 files MUST stay in the same folder. They link to each other.

---

## ✅ STEP 1 — Test it on your computer first

1. Open the folder on your computer
2. Double-click `index.html`
3. It opens in your browser — done!
4. Click any "Live App" button or hover a project → click the preview panel
5. Each app opens inside the portfolio modal

> ℹ️ If a browser blocks the iframe, just right-click `index.html` → Open With → Chrome or Firefox

---

## 🐙 STEP 2 — Put it on GitHub (free, forever)

### 2a. Create a GitHub account
1. Go to **github.com**
2. Click **Sign up**
3. Use any email, pick a username (this becomes part of your URL, e.g. `sarweshwor`)
4. Verify your email

### 2b. Create a new repository
1. Click the **+** button top-right → **New repository**
2. Repository name: `sarweshwor.github.io`
   - ⚠️ The name MUST match your GitHub username exactly, e.g. if your username is `sarweshwor` then name it `sarweshwor.github.io`
3. Make it **Public**
4. Do NOT tick "Add README" (you already have one)
5. Click **Create repository**

### 2c. Upload your files
1. On the empty repo page, click **uploading an existing file**
2. Drag ALL 7 files into the upload box (index.html + 5 app files + README.md)
3. Scroll down, write "first upload" in the commit message box
4. Click **Commit changes**

### 2d. Enable GitHub Pages
1. Go to your repo → click **Settings** (top tab)
2. Scroll down to **Pages** in the left sidebar
3. Under "Source" → select **Deploy from a branch**
4. Branch: **main** | Folder: **/ (root)**
5. Click **Save**
6. Wait 2–3 minutes

### 2e. Your site is live! 🎉
URL: `https://YOUR-USERNAME.github.io`

Example: `https://sarweshwor.github.io`

---

## ⚡ STEP 3 — Host on Vercel (faster + custom domain support)

Vercel is better than GitHub Pages — faster, HTTPS, and lets you add a custom `.dev` domain.

### 3a. Sign up for Vercel
1. Go to **vercel.com**
2. Click **Sign Up** → choose **Continue with GitHub**
3. Authorize Vercel to access GitHub

### 3b. Import your project
1. Click **Add New → Project**
2. Find your `sarweshwor.github.io` repo → click **Import**
3. Leave all settings as default
4. Click **Deploy**

### 3c. Your site is live on Vercel! 🎉
You get a URL like: `https://sarweshwor-github-io.vercel.app`

Every time you update files on GitHub, Vercel auto-deploys in ~30 seconds.

---

## 🌐 STEP 4 — Get a real .dev domain (like benscott.dev)

A `.dev` domain costs about **$12–15 USD per year** (~NRS 1,600–2,000).

### 4a. Buy the domain
1. Go to **namecheap.com** or **porkbun.com** (cheapest)
2. Search for `sarweshwor.dev` or `sarweshwor.com`
3. Add to cart → checkout
4. Pay with card or PayPal

### 4b. Connect domain to Vercel
1. In Vercel → go to your project → **Settings → Domains**
2. Type your domain e.g. `sarweshwor.dev` → click **Add**
3. Vercel shows you two DNS records (A record + CNAME)
4. Go to Namecheap → **Dashboard → Manage → Advanced DNS**
5. Delete existing A records
6. Add the records Vercel gave you
7. Wait 10–30 minutes for DNS to update

### 4c. Done! Your custom domain is live 🎉
`https://sarweshwor.dev` ← your portfolio

---

## 🆓 Super fast free option — Netlify Drop

If you just want a quick live link (no GitHub needed):
1. Go to **netlify.com/drop**
2. Drag your entire portfolio folder onto the page
3. Done! You get a random URL like `https://random-name-123.netlify.app`
4. You can rename it in Netlify settings

---

## 🔑 App login details (for demos)

| App | How to log in |
|---|---|
| SocialSphere | Username: `demo` / Password: `demo123` |
| SwiftChat | Click any user (Sarweshwor or Dev) → Enter Chat |
| PixelForge | Opens directly — just start drawing |
| FlowTask | Opens directly — just add tasks |
| BnB Booking | Opens directly — pick dates and book |

---

## 📝 How to update your portfolio later

1. Edit any `.html` file on your computer
2. Go to your GitHub repo
3. Click the file → click the ✏️ pencil icon → paste your changes → Commit
4. Vercel auto-deploys in ~30 seconds

That's it! Good luck 🚀
