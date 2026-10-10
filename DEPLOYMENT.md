# 🚀 Deployment Instructions for Crypto Live Dashboard

## Option 1: Deploy via Vercel Dashboard (Easiest)

1. **Go to Vercel Dashboard**
   - Visit: https://vercel.com/new

2. **Import Your Project**
   - Click "Import Git Repository" or "Deploy"
   - If you have the project in GitHub/GitLab/Bitbucket, connect it
   - OR upload the files directly

3. **Upload Files**
   - Upload these files to your Vercel project:
     - `index.html`
     - `style.css`
     - `script.js`
     - `vercel.json`

4. **Configure Project**
   - Framework Preset: Select "Other" or "Static"
   - Build Command: Leave empty
   - Output Directory: `/` (root)

5. **Deploy**
   - Click "Deploy" button
   - Wait for deployment to complete
   - Your dashboard will be live at: `https://your-project-name.vercel.app`

---

## Option 2: Deploy via Vercel CLI (Command Line)

### Step 1: Install Node.js
```bash
# Download from https://nodejs.org/
# Or use winget:
winget install OpenJS.NodeJS.LTS
```

### Step 2: Install Vercel CLI
```bash
npm install -g vercel
```

### Step 3: Deploy
```bash
cd C:\Users\OKTA\Downloads\dashboard-trading-raachees\dashboard-trading-main
vercel --token YOUR_ACTUAL_VERCEL_TOKEN
```

Replace `YOUR_ACTUAL_VERCEL_TOKEN` with your real token from https://vercel.com/account/tokens

---

## Option 3: Deploy via GitHub

1. **Create GitHub Repository**
   - Go to https://github.com/new
   - Create a new repository (e.g., `crypto-dashboard`)

2. **Upload Files**
   - Upload all dashboard files to the repository:
     - `index.html`
     - `style.css`
     - `script.js`
     - `vercel.json`

3. **Connect to Vercel**
   - Go to https://vercel.com/new
   - Import your GitHub repository
   - Click "Deploy"

4. **Access Your Dashboard**
   - Your dashboard will be live at: `https://crypto-dashboard.vercel.app`

---

## 📁 Project Files

All files are located in:
```
C:\Users\OKTA\Downloads\dashboard-trading-raachees\dashboard-trading-main\
```

Files to deploy:
- `index.html` - Main HTML file
- `style.css` - Stylesheet
- `script.js` - JavaScript for real-time data
- `vercel.json` - Vercel configuration

---

## 🔧 Features

- ✅ Real-time crypto prices from Binance API
- ✅ Auto-refreshes every 10 seconds
- ✅ Market overview cards
- ✅ Top gainers and losers
- ✅ Coin detail view
- ✅ Search functionality
- ✅ Responsive design
- ✅ Dark theme

---

## 🌐 Live URL

Once deployed, your dashboard will be accessible at:
```
https://your-project-name.vercel.app
```

---

## ⚠️ Notes

- The dashboard uses Binance public API (no API key required)
- Data refreshes automatically every 10 seconds
- Works on all devices (mobile, tablet, desktop)
- No backend required - runs entirely in the browser
