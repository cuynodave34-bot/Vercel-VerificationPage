# Tensei Email Verification Page

This is a standalone static site for handling Supabase email verification redirects.

## 🚀 Quick Deploy to Vercel

### Option 1: Deploy from GitHub (Recommended)

1. **Create a new GitHub repository** just for this verification page
2. **Upload these files:**
   - `index.html` (the verification page)
   - `vercel.json` (Vercel configuration)
   - `README.md` (this file)

3. **Connect to Vercel:**
   - Go to [vercel.com](https://vercel.com)
   - Click "New Project"
   - Import your GitHub repository
   - Vercel will auto-detect the configuration
   - Deploy!

### Option 2: Deploy from Local (Alternative)

1. **Install Vercel CLI:**
   ```bash
   npm install -g vercel
   ```

2. **Deploy:**
   ```bash
   cd vercel-email-verification
   vercel --prod
   ```

## ⚙️ Configuration

After deployment, update your Supabase settings:

**Site URL:** `https://your-vercel-app.vercel.app`

**Redirect URLs:**
```
https://your-vercel-app.vercel.app
```

## 🎯 Features

- ✅ Beautiful, responsive design
- ✅ Automatic app deep linking
- ✅ Error handling for failed verifications
- ✅ Mobile-friendly interface
- ✅ Fast loading (static HTML)

## 🔧 Customization

Edit `index.html` to:
- Change app scheme for deep linking
- Update store download links
- Modify colors and styling
- Add additional functionality

---

**Deployed URL will be:** `https://[your-repo-name].vercel.app`
