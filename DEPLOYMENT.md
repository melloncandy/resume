# GitHub Pages Deployment Guide

## Quick Setup Steps

1. **Create a new GitHub repository**
   - Go to GitHub.com and create a new repository
   - Name it something like `portfolio-website` or `mellon-candy-portfolio`
   - Make it public (required for GitHub Pages on free accounts)

2. **Upload these files**
   - Upload all files from the `github-pages` folder to your repository
   - Make sure `index.html` is in the root directory

3. **Enable GitHub Pages**
   - Go to your repository Settings
   - Scroll down to "Pages" section
   - Under "Source", select "Deploy from a branch"
   - Choose "main" branch and "/ (root)" folder
   - Click "Save"

4. **Access your website**
   - Your site will be available at: `https://yourusername.github.io/repository-name`
   - It may take a few minutes to deploy initially

## Files Included

- `index.html` - Main website file
- `assets/` - CSS, JavaScript, and image files
- `.nojekyll` - Tells GitHub Pages not to use Jekyll
- `README.md` - Project documentation
- `CNAME` - For custom domain (optional)

## Custom Domain (Optional)

If you have a custom domain:
1. Edit the `CNAME` file and add your domain
2. Configure your domain's DNS to point to GitHub Pages
3. In repository Settings > Pages, add your custom domain

Your beautiful animated flower portfolio website is now ready for GitHub Pages deployment!