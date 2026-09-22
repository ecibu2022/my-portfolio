# Ecibu Michael - Portfolio

Personal portfolio website for **Ecibu Michael** — Microsoft Dynamics 365 Business Central Developer & Full-Stack Software Engineer.

Live site (after deployment): `https://ecibu2022.github.io/my-portfolio/`

## Project Structure

```
my-portfolio/
├── index.html
├── css/
│   └── styles.css
└── README.md
```

## Local Preview

Open `index.html` in your browser, or run a simple server:

```bash
cd my-portfolio
python3 -m http.server 8080
```

Then visit: http://localhost:8080

## Deploy to GitHub Pages

### Step 1: Create a GitHub repository

1. Go to [github.com/new](https://github.com/new)
2. Repository name: **`my-portfolio`**
3. Set visibility to **Public**
4. Do **not** add README, .gitignore, or license (we already have files)
5. Click **Create repository**

### Step 2: Upload your portfolio files

In Terminal, from the folder containing `my-portfolio`:

```bash
cd /Users/ecibu/Downloads/my-portfolio

git init
git add .
git commit -m "Add portfolio website"
git branch -M main
git remote add origin https://github.com/ecibu2022/my-portfolio.git
git push -u origin main
```

> Replace `ecibu2022` with your GitHub username if different.

### Step 3: Enable GitHub Pages

1. Open your repo: `https://github.com/ecibu2022/my-portfolio`
2. Go to **Settings** → **Pages**
3. Under **Build and deployment**:
   - **Source:** Deploy from a branch
   - **Branch:** `main`
   - **Folder:** `/ (root)`
4. Click **Save**

### Step 4: Wait and visit your site

GitHub will build your site in 1–3 minutes. Your portfolio will be live at:

**https://ecibu2022.github.io/my-portfolio/**

You can share this link on LinkedIn, your CV, and your GitHub profile.

### Step 5 (Optional): Add link to GitHub profile

Edit your profile README (`ecibu2022/ecibu2022`) and add:

```markdown
🌐 Portfolio: https://ecibu2022.github.io/my-portfolio/
```

## Updating the site

After editing `index.html` or `css/styles.css`:

```bash
git add .
git commit -m "Update portfolio content"
git push
```

Changes appear on GitHub Pages within a few minutes.

## Custom domain (Optional)

If you own a domain (e.g. `ecibumichael.dev`):

1. Add a `CNAME` file to the repo containing your domain name
2. Configure DNS at your domain provider (A records or CNAME to GitHub Pages)
3. Enable the custom domain in **Settings → Pages**

See: [GitHub Pages custom domains documentation](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site)
