# MoneyBuckets

Personal budget tracker PWA with Supabase sync.

## Deploy to GitHub Pages — Step by Step

### 1. Create the repo on GitHub

1. Go to **github.com/new**
2. Repository name: `moneybuckets`
3. Set it to **Public** (required for free GitHub Pages)
4. Check **"Add a README file"**
5. Click **Create repository**

### 2. Upload the app files

1. On your new repo page, click **"Add file" → "Upload files"**
2. Drag and drop ALL 4 files from this folder:
   - `index.html`
   - `manifest.json`
   - `icon-192.png`
   - `icon-512.png`
3. Type a commit message like "Initial deploy"
4. Click **"Commit changes"**

### 3. Enable GitHub Pages

1. Go to your repo's **Settings** tab (the gear icon)
2. In the left sidebar, click **Pages**
3. Under "Source", select **Deploy from a branch**
4. Branch: **main**, Folder: **/ (root)**
5. Click **Save**
6. Wait 1-2 minutes, then refresh — you'll see your site URL:
   `https://YOURUSERNAME.github.io/moneybuckets/`

### 4. Configure Supabase redirect

For magic link auth to work, Supabase needs to know your site URL:

1. Go to your **Supabase dashboard → Authentication → URL Configuration**
2. Set **Site URL** to: `https://YOURUSERNAME.github.io/moneybuckets/`
3. Under **Redirect URLs**, add: `https://YOURUSERNAME.github.io/moneybuckets/`
4. Click **Save**

### 5. Test it

1. Open `https://YOURUSERNAME.github.io/moneybuckets/` on your phone
2. Enter your email and tap "Send Magic Link"
3. Check your email, tap the link
4. You're in! Add some income and bills
5. Open the same URL on your work computer — same data

### 6. Add to home screen (iPhone)

1. Open the URL in Safari
2. Tap the Share button (square with arrow)
3. Tap "Add to Home Screen"
4. Now it looks and feels like a native app
