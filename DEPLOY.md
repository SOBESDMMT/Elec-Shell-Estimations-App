# 🚀 Deploy to GitHub Pages

## Step 1: Create a GitHub Repository

1. Go to [github.com/new](https://github.com/new)
2. Name it **`electrical-estimator-web`**
3. Set it to **Public** (required for free GitHub Pages)
4. **Do NOT** add a README, .gitignore, or license (the project already has everything)
5. Click **Create repository**

## Step 2: Push the Code

Run these commands in the project folder:

```bash
cd /Users/micol2007/.gemini/antigravity/scratch/electrical-estimator-web

git init
git add .
git commit -m "Initial commit: Electrical Estimator web app"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/electrical-estimator-web.git
git push -u origin main
```

> ⚠️ Replace `YOUR_USERNAME` with your actual GitHub username.

## Step 3: Enable GitHub Pages

1. Go to your repo on GitHub → **Settings** → **Pages**
2. Under **Build and deployment**, set **Source** to **GitHub Actions**
3. The deploy workflow will run automatically on each push

## Step 4: Get Your URL

After the first deploy completes (~1-2 minutes):

```
https://YOUR_USERNAME.github.io/electrical-estimator-web/
```

## Updating the App

After making changes locally, just push:

```bash
git add .
git commit -m "your update message"
git push
```

GitHub Actions will automatically rebuild and redeploy. 🎉
