# 🚀 GitHub Profile Setup Guide

## 📋 Prerequisites

1. A GitHub account
2. A repository named exactly the same as your GitHub username (e.g., if your username is `RanaAreeb`, the repo should be `RanaAreeb`)

## 🎯 Quick Setup

### Step 1: Create the Repository
- Go to GitHub and create a new repository
- **Important**: Name it exactly the same as your GitHub username
- Make it **public**
- Initialize with a README (optional, we'll replace it)

### Step 2: Customize the README.md

Replace the following placeholders in `README.md`:

1. **Username**: Replace `RanaAreeb` with your actual GitHub username throughout the file
2. **Social Links**: Update all social media links with your actual profiles
3. **Email**: Replace `your-email@example.com` with your email
4. **Portfolio**: Replace `https://your-portfolio.com` with your portfolio URL
5. **Repository Links**: Update the featured projects section with your actual repositories
6. **Tech Stack**: Modify the badges to match your actual skills
7. **About Me**: Customize the JavaScript object with your actual information

### Step 3: Enable GitHub Actions

1. Go to your repository settings
2. Navigate to **Actions** → **General**
3. Enable "Allow all actions and reusable workflows"
4. The snake animation workflow will run automatically

### Step 4: Commit and Push

```bash
git add .
git commit -m "Add amazing GitHub profile README"
git push origin main
```

## 🎨 Customization Tips

### Colors & Themes
- Change `tokyonight` to other themes: `radical`, `merko`, `gruvbox`, `dracula`, `monokai`, `vue`, `dark`, `nord`, `onedark`, `cobalt`, `synthwave`, `highcontrast`, `dracula`
- Update badge colors to match your brand

### Stats Cards
- The stats cards automatically pull from your GitHub account
- Make sure your username is correct in all API calls

### Adding More Sections
- Add your own custom sections
- Include project showcases
- Add blog post feeds
- Include Spotify currently playing (requires additional setup)

## 🔧 Advanced Features

### WakaTime Integration (Optional)
To show coding activity, you need to:
1. Sign up at [WakaTime](https://wakatime.com)
2. Add your WakaTime API key to GitHub Secrets
3. Create a workflow to fetch and update stats

### Blog Posts (Optional)
To show latest blog posts:
1. Use RSS feed from your blog
2. Add a workflow to fetch and display posts
3. Or manually update the blog posts section

## 📝 Notes

- The profile README will appear at the top of your GitHub profile
- It updates automatically based on your GitHub activity
- Some features require GitHub Actions to be enabled
- Make sure all external links are working

## 🎉 You're All Set!

Once you've customized everything and pushed to GitHub, your profile will look amazing! 🚀

