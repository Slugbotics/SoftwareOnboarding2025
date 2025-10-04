# 🖥️ Command Line + Git Basics

This is your quick reference for navigating the terminal and using Git/GitHub.
Don’t worry if you’ve never used it before — you don’t need to memorize everything. Just copy-paste what you need when you need it.

---

## 📂 Navigating Your System


<details>
<summary><h3>Windows</h3></summary>

* Change directory:

  ```powershell
  cd folder_name
  ```
* Go back:

  ```powershell
  cd ..
  ```
* Create a file:

  ```powershell
  echo. > file.txt
  ```
* Create a folder:

  ```powershell
  mkdir folder_name
  ```
* Delete file:

  ```powershell
  del file.txt
  ```
* Delete folder:

  ```powershell
  rmdir /S /Q folder_name
  ```
* List files:

  ```powershell
  dir
  ```
</details>

<details>
<summary><h3>macOS + Linux</h3></summary>
* Change directory:

  ```bash
  cd folder_name
  ```
* Go back:

  ```bash
  cd ..
  ```
* Create a file:

  ```bash
  touch file.txt
  ```
* Create a folder:

  ```bash
  mkdir folder_name
  ```
* Delete file:

  ```bash
  rm file.txt
  ```
* Delete folder:

  ```bash
  rm -rf folder_name
  ```
* List files:

  ```bash
  ls
  ```
</details>

---

## 🔧 Git Commands

* Clone a repo:

  ```bash
  git clone https://github.com/username/repo.git
  ```
* Move into the repo:

  ```bash
  cd repo
  ```
* Check status:

  ```bash
  git status
  ```
* Pull the latest changes:

  ```bash
  git pull
  ```
* **(1)** Stage changes:

  ```bash
  git add .
  ```
* **(2)** Commit changes:

  ```bash
  git commit -m "your message"
  ```
* **(3)** Push changes:

  ```bash
  git push
  ```

  Remember to do all three steps **(1), (2), (3)** to get your changes onto GitHub.

---

## 🔧 GitHub CLI (`gh`) Commands

* Authenticate:

  ```bash
  gh auth login
  ```
  ```bash
  gh auth status # check status of login
  ```
* Clone a repo:

  ```bash
  gh repo clone username/repo #slugbotics/softwareonboarding2025
  ```
* View repo details (issues, pull requests, README):

  ```bash
  gh repo view
  ```
* Show open issues:

  ```bash
  gh issue list
  gh issue view <number>
  ```

* Create a pull request:

  ```bash
  gh pr create
  ```
* Check notifications:

  ```bash
  gh notifications
  ```

---

### ✅ Remember

You don’t need to use all of these right away. Start with **clone → add → commit → push** and you’ll already be contributing!

