
# ⚙️ 1. Git Installation for Windows

1. Go to [https://git-scm.com](https://git-scm.com)
2. Download the Windows installer
3. Run the installer:
   a) Keep default settings
   b) Choose **Git Bash** as default terminal (recommended)

After installation, open **Git Bash** and run:

```bash
git --version
```

---

# 🛠️ 2. Set Up Git (Configure user info)

Open **Git Bash** and run:

```bash
git config --global user.name "Your GitHub Name"
git config --global user.email "you@example.com"
```

Check your setup with:

```bash
git config --list
```

---

# 🧠 3. Link Git with VS Code

1. Install **Visual Studio Code**
2. Open VS Code → Go to **Extensions** → (Optional) Install: **GitHub Pull Requests and Issues**
3. Git will be automatically detected in VS Code ✅

Now you can:

* Use the **Source Control** tab
* Perform Git actions like **commit**, **push**, and more
* Run Git **commands** directly from the built-in terminal or use visual buttons

---


