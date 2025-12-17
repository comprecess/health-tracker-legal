# How to Enable GitHub Pages (30 seconds)

## ✅ Step-by-Step Instructions

### 1. Open Repository Settings
Go to: https://github.com/comprecess/health-tracker-legal/settings/pages

### 2. Configure GitHub Pages
Under **"Build and deployment"** section:

- **Source:** Select **"Deploy from a branch"**
- **Branch:** Select **"main"** and **"/ (root)"**
- Click **"Save"**

### 3. Wait for Deployment (1-2 minutes)
GitHub will automatically build and deploy your site.

You'll see a message: **"Your site is live at https://comprecess.github.io/health-tracker-legal/"**

### 4. Your URLs are Ready!

Once deployed, your legal documents will be available at:

- **Privacy Policy:** `https://comprecess.github.io/health-tracker-legal/privacy.html`
- **Terms of Service:** `https://comprecess.github.io/health-tracker-legal/terms.html`
- **Main Page:** `https://comprecess.github.io/health-tracker-legal/`

---

## 📱 Use These URLs in App Store Connect

When submitting your Health Tracker app to the App Store:

1. Go to **App Store Connect** → Your App → **App Privacy**
2. **Privacy Policy URL:** Paste `https://comprecess.github.io/health-tracker-legal/privacy.html`
3. Click **Save**

That's it! ✅

---

## 🔍 Verify Deployment

After enabling GitHub Pages:

1. Go to **Actions** tab: https://github.com/comprecess/health-tracker-legal/actions
2. You should see a **"pages build and deployment"** workflow running
3. Wait for the green checkmark ✅
4. Click on the deployment URL to verify your documents are live

---

## 🐛 Troubleshooting

**If GitHub Pages doesn't show up in Settings:**

1. Make sure the repository is **public** (not private)
2. Refresh the page
3. Try going directly to: https://github.com/comprecess/health-tracker-legal/settings/pages

**If deployment fails:**

1. Check the **Actions** tab for error messages
2. Make sure `index.html`, `privacy.html`, and `terms.html` exist in the main branch
3. Re-run the deployment from the Actions tab

---

## 📧 Need Help?

If you encounter any issues, contact: pauldealman@gmail.com
