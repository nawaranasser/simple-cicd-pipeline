#  How to Build a Simple CI/CD Pipeline for Static Websites

A step-by-step guide to creating your first CI/CD pipeline that automatically tests and deploys static websites.

##  What You'll Learn

- How to set up automated testing with **GitHub Actions**
- How to deploy static sites to **Vercel**
- How to create a complete CI/CD workflow
- DevOps principles in practice

##  Prerequisites

- GitHub account
- Basic knowledge of HTML
- Git installed locally

##  Step-by-Step Implementation

### Step 1: Create Your Static Website

    >> look at index.html & style.css files in this repo

### Step 2: Set Up GitHub Repository

    # Initialize Git
    git init
    git add .
    git commit -m "Initial commit"

    # Create GitHub repository and push
    git remote add origin https://github.com/YOUR_USERNAME/my-cicd-project.git
    git branch -M main
    git push -u origin main

### Step 3: Create CI/CD Pipeline with GitHub Actions

    Create .github/workflows/deploy.yml , you can find it above

### Step 4: Set Up Vercel Deployment

    1- Go to Vercel:https://vercel.com/ and sign up with GitHub
    2- Click "New Project"
    3- Import your GitHub repository
    4- Vercel will automatically deploy your site!
    
### Step 5: Test Your Pipeline

    1- Make a change to your index.html

    2- Commit and push:

        git add index.html
        git commit -m "Test CI/CD pipeline"
        git push

    3- Watch GitHub Actions run automatically!

    4- Your site will update on Vercel within minutes

### 🔧 Troubleshooting Common Issues

    ❌ Workflow won't run
        Check YAML indentation (must be spaces, not tabs)

        Ensure file is in .github/workflows/ directory

        Check branch name matches your repository

    ❌ Vercel deployment fails
        Ensure index.html is in root directory

        Check repository permissions in Vercel


### Feel free to fork this project and adapt it for your needs!

























































