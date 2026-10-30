# 🌸 GitHub Profile Setup Guide for @santhiyab010

This guide explains how to publish your customized **Black with Cherry Blossom** GitHub profile in less than 2 minutes.

---

### Step 1: Create Your Special Profile Repository on GitHub
1. Go to [GitHub - New Repository](https://github.com/new).
2. Set the **Repository name** to exactly:
   ```text
   santhiyab010
   ```
   *(GitHub will show a special banner saying: "You found a secret! santhiyab010/santhiyab010 is a special repository...")*
3. Make sure the repository is set to **Public**.
4. Check **Add a README file** (or leave it unchecked if pushing from local).
5. Click **Create repository**.

---

### Step 2: Upload Your Files
Upload the following files from your local folder:
```text
santhiyab010-profile/
├── README.md
└── assets/
    ├── banner.jpg
    ├── header.svg
    ├── about.svg
    ├── skills.svg
    ├── divider.svg
    └── education-certs.svg
```

#### Option A: Quick Upload via GitHub Web Interface
1. In your new `santhiyab010` repository, click **Add file** -> **Upload files**.
2. Drag and drop `README.md` and the entire `assets/` folder.
3. Click **Commit changes**.

#### Option B: Via Git Command Line
In PowerShell inside the folder:
```powershell
cd C:\Users\santhiya\.gemini\antigravity\scratch\santhiyab010-profile
git init
git add .
git commit -m "feat: customize profile with black & cherry blossom theme"
git branch -M main
git remote add origin https://github.com/santhiyab010/santhiyab010.git
git push -u origin main
```

---

### Step 3: Personalize Your Details
In `README.md`:
- Replace `your-email@example.com` with your real email address.
- Replace `your-linkedin` with your LinkedIn username.
- Replace `your-twitter` with your Twitter/X handle.
- You can easily edit any skill names or descriptions directly in `assets/skills.svg` or `assets/about.svg` using any text editor!

