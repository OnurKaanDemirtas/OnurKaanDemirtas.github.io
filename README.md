# Onur Kaan Demirtaş - Personal Portfolio & GitHub Pages

Welcome to your personal portfolio and resume website! This site is built with pure HTML5, CSS3, and JavaScript, designed to be hosted directly on **GitHub Pages** with zero build configuration needed.

## 🚀 Live URL
Once pushed to your GitHub repository, your site will be live at:
**`https://OnurKaanDemirtas.github.io`**

---

## 📁 Project Structure

```text
OnurKaanDemirtas.github.io/
├── index.html        # Main webpage structure and content
├── styles.css        # Responsive styling with Dark & Light theme support
├── script.js         # Interactive features (theme toggle, active scroll tracking, mobile nav)
└── README.md         # Deployment instructions
```

---

## 🛠️ Step-by-Step GitHub Pages Deployment

### Step 1: Create a Repository on GitHub
1. Go to [github.com/new](https://github.com/new).
2. Set the **Repository name** to exactly:
   ```
   OnurKaanDemirtas.github.io
   ```
   *(Must match your GitHub username followed by `.github.io` for automatic user-page hosting).*
3. Set the repository visibility to **Public**.
4. Do **not** check "Initialize this repository with a README" (we already have our files ready).
5. Click **Create repository**.

### Step 2: Push Your Local Code to GitHub
Open your terminal in this directory and run:

```bash
cd /Users/onurkaandemirtas/.gemini/antigravity/scratch/OnurKaanDemirtas.github.io

# Initialize git if not already done
git init
git branch -M main
git add .
git commit -m "Initial commit: portfolio website for GitHub Pages"

# Connect to your GitHub repository (replace with your repo URL if needed)
git remote add origin https://github.com/OnurKaanDemirtas/OnurKaanDemirtas.github.io.git

# Push to GitHub
git push -u origin main
```

### Step 3: Verify GitHub Pages Settings
1. On GitHub, go to your repository: `https://github.com/OnurKaanDemirtas/OnurKaanDemirtas.github.io`
2. Click **Settings** > **Pages** (in the left sidebar).
3. Under **Build and deployment**:
   - **Source**: `Deploy from a branch`
   - **Branch**: `main` / `/ (root)`
4. GitHub Pages will build and deploy the site in 1-2 minutes.
5. Visit your new website at **`https://OnurKaanDemirtas.github.io`**!

---

## 🎨 Customizing Content
- **Bio & Name**: Update the hero heading and description in [index.html](file:///Users/onurkaandemirtas/.gemini/antigravity/scratch/OnurKaanDemirtas.github.io/index.html).
- **Projects**: Add your own GitHub repositories, screenshots, and live demo links inside the `<section id="projects">` block.
- **Experience**: Edit your past work and education timeline under `<section id="experience">`.
- **Socials & Email**: Update your LinkedIn profile or other links inside the hero and footer sections.
