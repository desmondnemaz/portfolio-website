# Deploying to GitHub Pages 🚀

Since your code is already hosted on GitHub, the easiest way to deploy your portfolio is using **GitHub Pages**. It's free and hosting is immediate.

## Steps to Deploy

1. **Go to your Repository on GitHub**
   - Visit: [https://github.com/desmondnemaz/portfolio-website](https://github.com/desmondnemaz/portfolio-website)

2. **Open Settings**
   - Click on the **Settings** tab (usually the last tab on the right side of the repo menu).

3. **Navigate to "Pages"**
   - In the left sidebar menu, look for the "Code and automation" section.
   - Click on **Pages**.

4. **Configure Source**
   - Under "Build and deployment" > "Source", ensure **Deploy from a branch** is selected.
   - Under "Branch", click the dropdown menu that says "None".
   - Select **main**.
   - Ensure the folder is set to **/(root)**.
   - Click **Save**.

5. **Wait for Deployment**
   - GitHub will now build and deploy your site. This usually takes about 1-2 minutes.
   - You can refresh the page to see the status.
   - Once complete, a bar will appear at the top of the Pages settings saying:  
     "Your site is live at **https://desmondnemaz.github.io/portfolio-website/**"

6. **Visit Your Site**
   - Click the provided link to see your live portfolio! 🎉

## Updating Your Site
Whenever you want to update your portfolio:
1. Make changes to your code locally.
2. Run `git add .`
3. Run `git commit -m "Description of changes"`
4. Run `git push origin main`

GitHub Pages will automatically detect the new commit and update your live site within minutes.
