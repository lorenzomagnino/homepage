# NeurIPS 2025 Connection Website

A minimalist website for scheduling follow-up meetings during NeurIPS 2025 in San Diego.

## Deploy to GitHub Pages

### Option 1: Using GitHub Web Interface (Easiest)

1. **Create a new repository on GitHub:**
   - Go to [github.com/new](https://github.com/new)
   - Name it something like `neurips2025-connection` or `connection-website`
   - Make it **Public** (required for free GitHub Pages)
   - Don't initialize with README, .gitignore, or license
   - Click "Create repository"

2. **Upload your files:**
   - On the repository page, click "uploading an existing file"
   - Drag and drop `index.html` into the upload area
   - Add a commit message like "Initial commit"
   - Click "Commit changes"

3. **Enable GitHub Pages:**
   - Go to **Settings** tab in your repository
   - Scroll down to **Pages** in the left sidebar
   - Under **Source**, select `main` branch and `/ (root)` folder
   - Click **Save**
   - Your site will be live at: `https://YOUR_USERNAME.github.io/REPOSITORY_NAME/`

### Option 2: Using Git Command Line

1. **Initialize git repository:**
   ```bash
   cd /Users/lorenzomagnino/Connection-website
   git init
   git add index.html
   git commit -m "Initial commit"
   ```

2. **Create repository on GitHub** (same as Option 1, step 1)

3. **Push to GitHub:**
   ```bash
   git remote add origin https://github.com/YOUR_USERNAME/REPOSITORY_NAME.git
   git branch -M main
   git push -u origin main
   ```

4. **Enable GitHub Pages** (same as Option 1, step 3)

## Your Site URL

Once deployed, your site will be accessible at:
- GitHub Pages: `https://lorenzomagnino.github.io/REPOSITORY_NAME/`
- Or a custom domain if you configure one

