# Deploying to GitHub Pages (Free)

## Step 1: Create a GitHub Account
1. Go to [github.com](https://github.com) and sign up (free)
2. Verify your email address

## Step 2: Create a New Repository
1. Click the **+** button → **New repository**
2. Name it: `aniyah-hunter.github.io` (replace `aniyah-hunter` with your actual GitHub username)
3. Set to **Public**
4. Click **Create repository**

## Step 3: Upload Your Website Files
1. On the new repo page, click **"uploading an existing file"**
2. Drag and drop ALL files from the `aniyah-hunter-website` folder:
   - `index.html`
   - `style.css`
   - `script.js`
   - `optimized_resume.html`
   - `hero-bg.png`
3. Click **Commit changes**

## Step 4: Enable GitHub Pages
1. Go to **Settings** → **Pages** (left sidebar)
2. Under **Source**, select **Deploy from a branch**
3. Set branch to `main` and folder to `/ (root)`
4. Click **Save**

## Step 5: Access Your Site
Your website will be live at: `https://<your-username>.github.io`

> It may take 1-2 minutes to deploy the first time.

## Optional: Custom Domain
If you want a custom domain (e.g., `aniyahhunter.com`):
1. Purchase a domain from [Namecheap](https://namecheap.com) or [Google Domains](https://domains.google)
2. In your repo → **Settings** → **Pages** → **Custom domain**, enter your domain
3. Add DNS records as instructed by GitHub

## Updating the Contact Form
The contact form currently uses a placeholder Formspree URL. To make it functional:
1. Go to [formspree.io](https://formspree.io) and create a free account
2. Create a new form and copy the endpoint URL
3. In `index.html`, replace `https://formspree.io/f/xExample` with your actual Formspree endpoint
4. Also remove the `e.preventDefault()` line from `script.js` in the contact form handler
