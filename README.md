# Personal Portfolio Website

A professional portfolio website built with HTML and CSS, designed to showcase your work experience, education, skills, and projects.

## 📋 Requirements Met

This portfolio includes all required sections:
- ✅ Home / About Me (Name, Image, Introduction, Objectives)
- ✅ Work Experiences (Position, Tasks, Dates, Employment Type, Company Details)
- ✅ Educational Background (Degrees, Honors, Awards)
- ✅ Skills (Technical/IT, Managerial, Tools & Applications)
- ✅ Trainings and Seminars Attended (Title, Duration, Conductor, Location)
- ✅ Projects (Minimum 2 sample projects)
- ✅ Contact Details (Phone, Email, Address, Social Media)

## 🚀 Deployment Instructions for GitHub Pages

### Step 1: Create a GitHub Repository

1. Go to [GitHub](https://github.com) and log in
2. Click the "+" icon in the top right corner
3. Select "New repository"
4. Name your repository: `username.github.io` (replace 'username' with your GitHub username)
5. Set it to **Public**
6. Do NOT initialize with README (we already have files)
7. Click "Create repository"

### Step 2: Upload Your Files to GitHub

#### Option A: Using GitHub Web Interface (Easier)
1. In your new repository, click "uploading an existing file"
2. Drag and drop these files:
   - `index.html`
   - `styles.css`
   - Your profile photo (rename it to `your-photo.jpg`)
   - Project images (if you have them)
3. Write a commit message: "Initial commit - Portfolio website"
4. Click "Commit changes"

#### Option B: Using Git Command Line
```bash
# Navigate to your portfolio folder
cd path/to/your/portfolio

# Initialize Git
git init

# Add all files
git add .

# Commit files
git commit -m "Initial commit - Portfolio website"

# Add remote repository (replace username with yours)
git remote add origin https://github.com/username/username.github.io.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click on "Settings"
3. Scroll down to "Pages" in the left sidebar
4. Under "Source", select "main" branch
5. Click "Save"
6. Wait a few minutes for deployment

### Step 4: Access Your Live Website

Your portfolio will be available at: `https://username.github.io/portfolio`
(or `https://username.github.io` if you named it `username.github.io`)

## 📝 Customization Guide

### Before Deploying, Replace the Following:

1. **In `index.html`:**
   - `[Your Name]` - Your full name
   - `[Your Title/Role]` - e.g., "Web Developer", "Software Engineer"
   - `[Write a short self-introduction...]` - Your personal introduction
   - `[Your career objectives...]` - Your career goals
   - All work experience details
   - All education details
   - All skills
   - All training/seminar details
   - All project details
   - All contact information

2. **Images to Add:**
   - `your-photo.jpg` - Your professional photo
   - `project1.jpg` - Screenshot or image of your first project
   - `project2.jpg` - Screenshot or image of your second project

3. **In `styles.css`:**
   - Optionally change color scheme by modifying CSS variables in `:root`

### Color Customization

To change the color scheme, modify these variables in `styles.css`:
```css
:root {
    --primary-color: #2563eb;     /* Main brand color */
    --secondary-color: #1e40af;   /* Darker shade */
    --accent-color: #3b82f6;      /* Accent color */
}
```

## 📱 Features

- ✨ Modern, professional design
- 📱 Fully responsive (mobile, tablet, desktop)
- 🎨 Clean and organized layout
- 🚀 Smooth scrolling navigation
- 🎯 All required sections included
- 💼 Ready for GitHub Pages deployment

## 🔄 Making Updates

After deployment, to update your portfolio:

1. Make changes to your files locally
2. Commit changes:
   ```bash
   git add .
   git commit -m "Update portfolio content"
   git push
   ```
3. Changes will appear on your live site within a few minutes

## 📅 Submission Checklist

Before submitting (Deadline: February 4, 2026):

- [ ] All sections filled with your information
- [ ] Profile photo added
- [ ] Project images added
- [ ] Repository is public
- [ ] GitHub Pages is enabled
- [ ] Website is accessible at live URL
- [ ] All links work correctly
- [ ] Contact information is accurate
- [ ] Tested on mobile and desktop

## 📧 Support

If you encounter issues:
1. Check GitHub Pages status in repository settings
2. Ensure repository is public
3. Verify all file names are correct (case-sensitive)
4. Wait 5-10 minutes after pushing changes

## 📄 License

This portfolio template is free to use for your personal portfolio.

---

**Good luck with your submission! 🎓**

Remember to submit only the live website link: `https://username.github.io/portfolio`
# portfolio-test
