# Personal Portfolio Website

A modern, responsive personal portfolio website with a beautiful green gradient theme.

## Features

- **Home Page**: Hero section with introduction and call-to-action buttons
- **About Page**: Information about you, your journey, and skills
- **Contact Info Page**: Contact details and a contact form
- **Photos Page**: Gallery showcasing your work and projects

## Design

- Dark theme with vibrant green gradients
- Smooth animations and transitions
- Fully responsive design
- Modern UI/UX with glassmorphism effects

## How to Deploy to GitHub Pages

Follow these steps to push your portfolio to GitHub and make it live:

### Step 1: Create a GitHub Account
If you don't have one, go to [github.com](https://github.com) and sign up.

### Step 2: Create a New Repository
1. Click the "+" icon in the top right corner of GitHub
2. Select "New repository"
3. Name it `your-username.github.io` (replace `your-username` with your actual GitHub username)
   - **Important**: This exact naming format enables GitHub Pages automatically
   - Alternatively, you can name it anything (e.g., `portfolio`) and configure it later
4. Make it **Public** (required for free GitHub Pages)
5. **Don't** initialize with README, .gitignore, or license (we already have files)
6. Click "Create repository"

### Step 3: Initialize Git in Your Project
Open your terminal/command prompt in the project folder and run:

```bash
# Initialize git repository
git init

# Add all files
git add .

# Create your first commit
git commit -m "Initial commit: Portfolio website"
```

### Step 4: Connect to GitHub and Push
```bash
# Add your GitHub repository as remote (replace YOUR_USERNAME with your actual username)
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git

# Rename branch to main (if needed)
git branch -M main

# Push to GitHub
git push -u origin main
```

**Note**: You'll be prompted for your GitHub username and password. For password, use a **Personal Access Token** (not your regular password):
- Go to GitHub Settings → Developer settings → Personal access tokens → Tokens (classic)
- Generate a new token with `repo` permissions
- Use this token as your password

### Step 5: Enable GitHub Pages
1. Go to your repository on GitHub
2. Click on **Settings** tab
3. Scroll down to **Pages** in the left sidebar
4. Under **Source**, select **Deploy from a branch**
5. Choose **main** branch and **/ (root)** folder
6. Click **Save**

### Step 6: Access Your Live Website
Your portfolio will be available at:
- `https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/` (if you named it something other than `username.github.io`)
- OR `https://YOUR_USERNAME.github.io/` (if you named it exactly `username.github.io`)

It may take a few minutes for the site to go live. You'll see a green checkmark when it's ready!

## Customization

Before deploying, make sure to customize:

1. **Replace "Your Name"** throughout all HTML files with your actual name
2. **Update contact information** in `contact.html`
3. **Add your actual photos** by replacing the placeholder divs with `<img>` tags
4. **Update the About page** with your real information and skills
5. **Modify colors** in `styles.css` if desired (look for the `:root` variables)

## File Structure

```
portfolio/
├── index.html      # Home page
├── about.html      # About page
├── contact.html    # Contact page
├── photos.html     # Photos/Gallery page
├── styles.css      # Main stylesheet
└── README.md       # This file
```

## Future Updates

To update your portfolio after making changes:

```bash
git add .
git commit -m "Description of your changes"
git push
```

Your changes will automatically update on GitHub Pages within a few minutes!

## Need Help?

- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [Git Basics](https://git-scm.com/book/en/v2/Getting-Started-Git-Basics)

---

**Happy coding! 🚀**

