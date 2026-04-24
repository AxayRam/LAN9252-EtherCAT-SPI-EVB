# GitHub Upload Guide for LAN9252 EtherCAT SPI EVB

## Quick Start: Push Your Project to GitHub

Follow these steps to upload your project to your existing GitHub repository: `https://github.com/AxayRam/LAN9252-EtherCAT-SPI-EVB`

### Prerequisites
- Git installed on your computer ([Download Git](https://git-scm.com/))
- GitHub account with push access to the repository
- Command line or Git GUI tool

---

## Method 1: Using Git Command Line (Recommended)

### Step 1: Initialize Git (First Time Only)
Open Command Prompt or PowerShell in your project folder:

```powershell
cd "e:\ETHERCAT PCB DESIGN"
git init
```

### Step 2: Add Remote Repository
```powershell
git remote add origin https://github.com/AxayRam/LAN9252-EtherCAT-SPI-EVB.git
```

### Step 3: Configure Git (First Time Only)
```powershell
git config user.name "Your Name"
git config user.email "your.email@example.com"
```

### Step 4: Add All Files
```powershell
git add .
```

### Step 5: Create Initial Commit
```powershell
git commit -m "Initial commit: Add PCB design files, BOM, and documentation"
```

### Step 6: Upload to GitHub
```powershell
git branch -M main
git push -u origin main
```

**Note**: You may be prompted to authenticate. Use your GitHub credentials or personal access token.

---

## Method 2: Using GitHub Desktop (GUI)

### Step 1: Install GitHub Desktop
Download from: https://desktop.github.com/

### Step 2: Clone Your Repository
1. Open GitHub Desktop
2. Click **File → Clone Repository**
3. Enter: `https://github.com/AxayRam/LAN9252-EtherCAT-SPI-EVB.git`
4. Choose local path: `e:\ETHERCAT PCB DESIGN`

### Step 3: Add Files
1. GitHub Desktop will detect all new files automatically
2. Review the changes in the "Changes" tab
3. Enter commit message: *"Initial commit: Add PCB design files"*

### Step 4: Publish to GitHub
1. Click **Publish branch** button
2. Ensure settings are correct
3. Click **Publish Repository**

---

## Method 3: Using VS Code Git Integration

### Step 1: Open Project in VS Code
```powershell
code "e:\ETHERCAT PCB DESIGN"
```

### Step 2: Initialize Repository
1. Click **Source Control** (left sidebar)
2. Click **Initialize Repository**
3. Select your project folder

### Step 3: Stage All Files
1. In Source Control panel
2. Click the **+** button next to "Changes" (or use **Stage All Changes**)

### Step 4: Create Commit
1. Enter message: `"Initial commit: Add PCB design files and documentation"`
2. Click **Commit** (checkmark icon)

### Step 5: Add Remote
1. Terminal → New Terminal
2. Run:
```powershell
git remote add origin https://github.com/AxayRam/LAN9252-EtherCAT-SPI-EVB.git
git branch -M main
git push -u origin main
```

---

## Authentication Options

### Option A: Personal Access Token (Recommended for 2FA)
1. Go to GitHub → Settings → Developer settings → Personal access tokens
2. Generate new token with `repo` scope
3. Use token as password when prompted

### Option B: SSH Keys
1. Generate SSH key: `ssh-keygen -t ed25519 -C "your.email@example.com"`
2. Add to GitHub: Settings → SSH and GPG keys
3. Use SSH URL: `git@github.com:AxayRam/LAN9252-EtherCAT-SPI-EVB.git`

### Option C: Windows Credential Manager
Windows will automatically store credentials after first login.

---

## Troubleshooting

### Issue: "fatal: not a git repository"
**Solution**:
```powershell
cd "e:\ETHERCAT PCB DESIGN"
git init
```

### Issue: "Permission denied" or "Authentication failed"
**Solution**:
1. Use personal access token instead of password
2. Verify repository permissions on GitHub
3. Check internet connection

### Issue: Large file warning
**Solution**: 
Files over 100MB need Git LFS. For Gerber files (usually small):
```powershell
git lfs install
git lfs track "*.GER"
```

### Issue: Need to update existing repository
**Solution**:
```powershell
git fetch origin
git merge origin/main
```

---

## Verifying Upload Success

### Check on GitHub Web
1. Go to https://github.com/AxayRam/LAN9252-EtherCAT-SPI-EVB
2. You should see:
   - ✅ All files uploaded
   - ✅ README.md displayed as project description
   - ✅ License visible in sidebar
   - ✅ Contributor count: 1

### Check Locally
```powershell
git log
```
You should see your commits listed.

---

## Future Updates

Once uploaded, to make changes:

```powershell
# Make your changes to files

# Stage changes
git add .

# Commit
git commit -m "Update: Description of changes"

# Push to GitHub
git push origin main
```

---

## Recommended GitHub Settings

After uploading, visit your repository settings:

1. **Settings → General**
   - ✅ Enable "Issues"
   - ✅ Enable "Discussions"

2. **Settings → Code security & analysis**
   - ✅ Enable "Dependabot alerts"

3. **Settings → Branches**
   - Set "main" as default branch
   - Add branch protection rules (optional)

---

## Repository Management

### Create Releases
1. Go to Releases → Create new release
2. Tag version: `v1.0`
3. Title: `LAN9252 EVB v1.0`
4. Add release notes
5. Publish

### Add Badges to README
Copy badge markdown to your README:

```markdown
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![GitHub Release](https://img.shields.io/github/v/release/AxayRam/LAN9252-EtherCAT-SPI-EVB)](../../releases)
[![GitHub Stars](https://img.shields.io/github/stars/AxayRam/LAN9252-EtherCAT-SPI-EVB)](../../stargazers)
```

---

## Need Help?

- **Git Tutorials**: https://github.com/skills
- **GitHub Help**: https://docs.github.com
- **Markdown Guide**: https://www.markdownguide.org/

---

**Ready?** Start with Method 1 (Command Line) for quickest results!
