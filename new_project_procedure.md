# New Project Procedure

### Requirements

1. **Git** (needed for version control)  
   - Download and install: https://git-scm.com/downloads

2. **Visual Studio Code** (code editor with Git integration)  
   - Download and install: https://code.visualstudio.com/

3. **GitHub `.gitignore` extension** (to add `.gitignore` templates via GUI)  
   - Install from **Extensions sidebar** in VS Code

4. **GitHub Pull Requests and Issues extension** (for managing pull requests and issues from VS Code)  
   - Install from **Extensions sidebar** in VS Code

---

### Step-by-Step GUI Workflow

### Step 1: Create your project folder
- On your computer, create a new folder, e.g., `my-project`

---

### Step 2: Open the folder in VS Code
- Open Visual Studio Code  
- Click **File → Open Folder**  
- Select your project folder  

---

### Step 3: Initialize Git (GUI only)
- Click the **Source Control icon** (left sidebar)  
- Click **“Initialize Repository”**  

Git is now enabled for your project without using the terminal

---

### Step 4: Create your project files
- In the Explorer panel, click **New File**  
- For example: `main.c`  
- Add your code  
- You can also create folders using **New Folder**

---

### Step 5: Add a `.gitignore` (GUI)
- Open the **Extensions sidebar**  
- Install **GitHub `.gitignore`**  
- Press `Ctrl + Shift + P` → type `Add .gitignore` → select your project type  

This creates the `.gitignore` automatically in your project root

---

### Step 6: Add a README file locally
- In the Explorer panel, click **New File**  
- Name the file `README.md`  
- Add content describing your project, e.g., project name, description, features, setup instructions  
- Go to **Source Control tab** → **Stage (+)** → **Commit (✔)** with a message like `Add README file`

---

### Step 7: Stage changes
- Go to **Source Control**  
- You’ll see your files under **Changes**  
- Click the **+ icon** next to each file, or **Stage All Changes**

---

### Step 8: Commit changes
- In the message box at the top, type:  
  ```
  Initial commit
  ```  
- Click the **✔ Commit** button

---

### Step 9: Publish to GitHub (GUI only)
- Click **“Publish to GitHub”**  
- Choose **Public** or **Private**  
- Sign in if prompted  
- VS Code handles the rest

---

### Step 10: Add a LICENSE file (via GitHub website)
- Go to your repository on GitHub (web)  
- Click **“Add file” → “Create new file”**  
- Name the file `LICENSE`  
- Click **“Choose a license template”**  
- Select your license (MIT, Apache 2.0, GPL, etc.)  
- Scroll down, add a commit message like `Add LICENSE file`  
- Click **Commit new file**

---

### Step 11: Use GitHub Pull Requests (GUI)
- Open the **GitHub Pull Requests and Issues** tab (left sidebar) in VS Code  
- Sign in to your GitHub account  
- You can now:
  - Create pull requests  
  - Review PRs from collaborators  
  - Merge PRs directly in VS Code

---

### Step 12: Continue working (GUI workflow)
- Edit files  
- Stage (+) and commit (✔) changes  
- Click **Sync Changes** to push/pull from GitHub

---

✅ This workflow fully sets up a local project with version control, `.gitignore`, README, LICENSE, GitHub publishing, and pull request management — all through GUI only.

