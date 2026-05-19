# 🪳 Cockroach Janta Party — Website

> "Voice of the Lazy & Unemployed." — Stronger Together.

## Files
```
index.html      ← The entire website (one file)
logo.webp       ← CJP logo (optimized)
hero.webp       ← Hero/eligibility poster (optimized)
netlify.toml    ← Netlify config (caching, headers)
```

---

## 🚀 Deploy to GitHub Pages

1. Create a new repo on GitHub (e.g. `cockroach-janta-party`)
2. Upload all files (drag & drop on GitHub UI, or use git):
   ```bash
   git init
   git add .
   git commit -m "CJP website launch 🪳"
   git remote add origin https://github.com/YOUR_USERNAME/cockroach-janta-party.git
   git push -u origin main
   ```
3. Go to **Settings → Pages → Source → main branch / root**
4. Your site will be live at `https://YOUR_USERNAME.github.io/cockroach-janta-party/`

---

## 🚀 Deploy to Netlify (Recommended — Free)

### Option A: Drag & Drop (Easiest)
1. Go to [app.netlify.com](https://app.netlify.com)
2. Drag the entire `cjp-website` folder onto the deploy zone
3. Done! You get a free URL instantly.
4. To use `cockroachjantaparty.org` → go to **Domain Settings → Add custom domain**

### Option B: Connect GitHub repo
1. Push to GitHub (see above)
2. On Netlify: **Add new site → Import from Git → Select your repo**
3. Build command: *(leave empty)*
4. Publish directory: `.`
5. Click Deploy!

---

## Custom Domain (cockroachjantaparty.org)

After deploying on Netlify:
1. Go to **Site Configuration → Domain Management**
2. Click **Add custom domain** → enter `cockroachjantaparty.org`
3. Update your domain's DNS:
   - Add a CNAME record: `www` → `your-site-name.netlify.app`
   - Or A record: `@` → Netlify's IP (shown in dashboard)
4. Netlify gives you **free HTTPS/SSL** automatically ✅

---

## Legal Notes
- The website includes a disclaimer: *"Satire. Parody. Political commentary."*
- Not affiliated with any registered Indian political party
- All content is protected as political satire under free speech provisions
