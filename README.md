# TurfDeck - Garden Maintenance Website

Professional garden maintenance website for Derby, UK.

## Quick Start

This is a static website. To deploy:

### Option 1: Netlify Drop (Easiest)

1. Go to [netlify.com/drop](https://netlify.com/drop)
2. Drag the `turfdeck` folder onto the page
3. Your site is live!
4. Buy a domain (e.g., TurfDeck.co.uk)
5. In Netlify: Site Settings → Domain Management → Add custom domain

### Option 2: GitHub + Netlify (Auto-deploy)

#### Step 1: Create GitHub Repo
1. Go to [github.com/new](https://github.com/new)
2. Repository name: `turfdeck`
3. Public or Private
4. Click "Create repository" (don't add any files)

#### Step 2: Set Up Git on Your Computer

```bash
# 1. Open Terminal/Command Prompt

# 2. Navigate to where you want the folder
cd Desktop

# 3. Clone the empty repo
git clone https://github.com/YOURUSERNAME/turfdeck.git

# 4. Go into the folder
cd turfdeck

# 5. Copy all files from my turfdeck folder into this folder
# (drag and drop or copy-paste)

# 6. Add all files
git add .

# 7. Commit
git commit -m "Initial commit"

# 8. Push to GitHub
git push origin main
```

#### Step 3: Connect to Netlify

1. Go to [netlify.com](https://netlify.com)
2. Sign up / Log in with GitHub
3. Click "Add new site" → "Import an existing project"
4. Select GitHub → Select your `turfdeck` repo
5. Click "Deploy site"

Now every time you push to GitHub, Netlify automatically updates!

---

## Updating the Site

### To Make Changes:

1. Edit files locally in your turfdeck folder
2. Commit and push:
```bash
git add .
git commit -m "Describe your changes"
git push origin main
```
3. Netlify auto-deploys in ~30-60 seconds

---

## Site Structure

```
turfdeck/
├── index.html        # Homepage
├── derby.html        # Derby-specific landing page
├── contact.html      # Contact page
├── styles.css        # All styling
├── robots.txt        # Search engine instructions
└── README.md         # This file
```

---

## Customization

### To Change Phone Number:
Edit in all .html files:
- Find: `01332700000`
- Replace with your number

### To Change Business Name:
- Edit logo in header: `<a href="index.html" class="logo">TurfDeck</a>`
- Edit footer: `<h3>TurfDeck</h3>`

### To Add a New City (e.g., Nottingham):
1. Copy `derby.html` → `nottingham.html`
2. Find/replace "Derby" → "Nottingham"
3. Add link in navigation

---

## SEO Tips

This site includes:
- LocalBusiness Schema markup (JSON-LD)
- Proper meta descriptions
- Semantic HTML
- City-specific pages
- Canonical URLs

For better SEO:
1. Set up Google Business Profile
2. Get listed in local directories (Yelp, Yell, FreeIndex)
3. Add more city pages over time

---

## Support

For questions about this site, contact the developer.
