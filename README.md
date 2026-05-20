Here's a beginner-friendly step-by-step guide:

---

### Step 1: Install Git
1. Go to [git-scm.com](https://git-scm.com/download/win) and download the Windows installer.
2. Run the installer — keep all defaults and click **Next** through everything.
3. When done, open **Command Prompt** and type `git --version` to confirm it installed.

---

### Step 2: Install VS Code
1. Go to [code.visualstudio.com](https://code.visualstudio.com/) and download for Windows.
2. Install it — check the box **"Add to PATH"** during setup.

---

### Step 3: Create a GitHub Account
1. Go to [github.com](https://github.com) → **Sign up** with a school email.
2. Verify your email and log in.

---

### Step 4: Connect Git to GitHub (one-time setup)
Open **Git Bash** (installed with Git) and run:
```bash
git config --global user.name "Your Name"
git config --global user.email "your@email.com"
```
Use the same email as your GitHub account.

---

### Step 5: Sign into GitHub in VS Code
1. Open VS Code.
2. Click the **Accounts icon** (bottom-left, person icon) → **Sign in with GitHub**.
3. A browser window opens — log in and authorize VS Code.

---

### Step 6: Clone a Repo (get code from GitHub)
1. In VS Code, press `Ctrl+Shift+P` → type **Git: Clone** → hit Enter.
2. Paste the GitHub repo URL (e.g. `https://github.com/username/repo-name`).
3. Choose a folder on your PC to save it → click **Open** when prompted.

---

### Step 7: Make Changes & Push to GitHub
After editing files in VS Code:
1. Click the **Source Control icon** (left sidebar, looks like a branch).
2. Hover over changed files → click **+** to stage them.
3. Type a **commit message** (e.g. `"added homework solution"`).
4. Click the **✓ Commit** button.
5. Click **Sync Changes** (or the `...` menu → **Push**) to upload to GitHub.

---

### Step 8: Create Your Own Repo (optional)
1. On [github.com](https://github.com) → click **New** (green button).
2. Name it, set to **Public** or **Private**, check **Add a README**.
3. Click **Create repository** → then clone it in VS Code (Step 6).

---

**That's it!** The main daily workflow is: edit → stage → commit → push. 🎉

> 💡 **Tip for students:** GitHub offers free private repos and extra perks via [GitHub Education](https://education.github.com/students) with a school email.