# odaiameera.com — Personal Portfolio

Built with plain HTML/CSS/JS. Hosted on GitHub Pages. Zero cost.

---

## How to Deploy (Step by Step)

### 1. Create GitHub Repository
- Go to github.com and create a new repository
- Name it exactly: `odaiameera.github.io`
- Set it to **Public**
- Don't add README (you already have one)

### 2. Upload Files
- Upload `index.html` and this `README.md` to the repo
- Commit directly to `main` branch

### 3. Enable GitHub Pages
- Go to repo **Settings** → **Pages**
- Source: Deploy from branch
- Branch: `main` / `root`
- Hit Save

Your site will be live at: `https://odaiameera.github.io`

### 4. Point Your Domain (odaiameera.com)
In your domain registrar (wherever you bought the domain):

Add these DNS records:
```
Type: A    Name: @    Value: 185.199.108.153
Type: A    Name: @    Value: 185.199.109.153
Type: A    Name: @    Value: 185.199.110.153
Type: A    Name: @    Value: 185.199.111.153
Type: CNAME  Name: www  Value: odaiameera.github.io
```

Then in GitHub Pages settings, add your custom domain: `odaiameera.com`

DNS takes 10-30 minutes to propagate. After that, odaiameera.com is live.

---

## What to Update as You Build

- **Projects section**: Replace the "wip" cards with links to your GitHub repos as they're done
- **Experience section**: Update dates and roles as needed
- **GitHub link**: Make sure github.com/odaiameera is your actual username

---

## File Structure
```
odaiameera.github.io/
└── index.html   ← everything is in here, single file
└── README.md
```
