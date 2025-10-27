# GitHub Setup Instructions

## Repository Status
✅ **Local Git repository initialized**
✅ **All files committed** 
✅ **Main branch created**

## Next Steps to Connect to GitHub:

### 1. Create a New Repository on GitHub
1. Go to [GitHub.com](https://github.com)
2. Click the "+" icon in the top right corner
3. Select "New repository"
4. Repository name: `julianbernauer.github.io` (recommended for GitHub Pages)
   - Or any other name you prefer
5. Description: "Personal website of Dr. Julian Bernauer"
6. Make it **Public** (required for free GitHub Pages)
7. **Do NOT** initialize with README, .gitignore, or license (we already have these)
8. Click "Create repository"

### 2. Connect Your Local Repository to GitHub
Run these commands from your current directory:

```powershell
# Add the remote repository (replace 'julianbernauer' with your GitHub username)
git remote add origin https://github.com/julianbernauer/julianbernauer.github.io.git

# Push your code to GitHub
git push -u origin main
```

### 3. Enable GitHub Pages
1. Go to your repository on GitHub
2. Click "Settings" tab
3. Scroll down to "Pages" in the left sidebar
4. Under "Source", select "Deploy from a branch"
5. Choose "main" branch and "/ (root)" folder
6. Click "Save"

### 4. Your Website Will Be Live At:
- If named `julianbernauer.github.io`: https://julianbernauer.github.io
- If named something else: https://julianbernauer.github.io/repository-name

## Future Updates
To update your website:
1. Make changes to your files
2. Run: `git add .`
3. Run: `git commit -m "Description of changes"`  
4. Run: `git push`

GitHub Pages will automatically rebuild and update your site!

## Files Ready for GitHub:
- ✅ HTML pages (index, research, publications, teaching)
- ✅ CSS styling (responsive, modern design)
- ✅ Jekyll configuration for GitHub Pages
- ✅ README documentation
- ✅ .gitignore for clean repository
- ✅ robots.txt for SEO

## Don't Forget:
- Add your profile photo as `images/julianface.jpg`
- Update any links or information as needed
- The website is fully responsive and mobile-friendly!