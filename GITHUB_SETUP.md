# GitHub Setup Instructions

## Step 1: Create a GitHub Repository

1. Go to [GitHub.com](https://github.com) and sign in
2. Click the "+" icon in the top right corner
3. Select "New repository"
4. Repository name: `portfolio` (or any name you prefer)
5. Description: "My portfolio website"
6. Choose **Public** (required for free GitHub Pages)
7. **DO NOT** initialize with README, .gitignore, or license (we already have these)
8. Click "Create repository"

## Step 2: Connect and Push Your Code

After creating the repository, GitHub will show you commands. Use these commands in your terminal:

```bash
cd "c:\Users\ayush\OneDrive\Desktop\Portfolito - Ayush Kabra"
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
git branch -M main
git push -u origin main
```

**Replace:**
- `YOUR_USERNAME` with your GitHub username
- `YOUR_REPO_NAME` with the repository name you created

## Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click on **Settings** tab
3. Scroll down to **Pages** in the left sidebar
4. Under "Source", select **Deploy from a branch**
5. Select branch: **main**
6. Select folder: **/ (root)**
7. Click **Save**

## Step 4: Access Your Live Site

Your site will be available at:
`https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/`

It may take a few minutes for the site to go live after enabling Pages.

---

**Note:** If you want to use a custom domain later, you can add it in the Pages settings.
