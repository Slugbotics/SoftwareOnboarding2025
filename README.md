# 🎉 Welcome to the Slugbotics Software Onboarding (2025)

This guide will get your computer set up with all the tools you’ll need to start coding, collaborating, and building robots with us 🚀

---

## 📚 Table of Contents
1. [Git + GitHub Setup](#-1-git--github-setup)  
2. [VS Code Setup](#-2-vs-code-setup)  
3. [Python Setup](#-3-python-setup)  
4. [ROS 2 Setup](#-4-ros-2-setup)  
5. [WSL (Optional, Windows Only)](#-5-wsl-optional-windows-only)  
6. [VS Code Extensions](#-6-vs-code-extensions)  
7. [Next Steps + Club Resources](#-7-next-steps--club-resources)  

---

## 🗂️ 1. Git + GitHub Setup
Git is like Google Drive for code. It keeps track of changes and makes teamwork possible.  

### Install Git
- **Windows** → [Download Git](https://git-scm.com/downloads) and run the installer.
- **macOS** → Install Homebrew first if not already installed:  
  ```bash
  /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
   ```
  * Then run:
  `brew install git`

* **Ubuntu Linux** →
  `sudo apt update && sudo apt install git`

### GitHub CLI (recomended)

- Download the [GitHub CLI](https://cli.github.com/). This makes it easier to interact with GitHub from your terminal. It also makes it super easy to connect your computer to GitHub and handle authentication without the hassle of tokens or SSH setup.

- Once installed, run:
  ```
  gh auth login
  ```
  💡 *Note on SSH keys:* These are like secure “passwords” for GitHub. You don’t need to worry about them now, but if you want to learn more, see [GitHub’s SSH guide](https://docs.github.com/en/authentication/connecting-to-github-with-ssh). Github CLI should set these up for you automatically. If you want to learn how that works, check it out [here](https://cli.github.com/manual/gh_auth_login)

---

## 📝 2. VS Code Setup

[Download VS Code](https://code.visualstudio.com/) for your OS.

* **Windows/macOS** → Just run the installer.
* **Ubuntu Linux** →
  `
  sudo snap install --classic code
  `

Once installed, you can open projects, run code, and manage Git all inside VS Code.

---

## 🐍 3. Python Setup

We use **Python** for most of our development.

* **Windows** → [Download Python](https://www.python.org/downloads/). 

    * ⚠️ During install, remember to check ***Add Python to PATH***.
* **macOS** →

  ```bash
  brew install python
  ```
* **Ubuntu Linux** →

  ```bash
  sudo apt install python3 python3-pip
  ```

**Optional (recommended):** Create a virtual environment for Rover work. This keeps your python packages localized to the project so the specific version #s don't bog the rest of your projects:

```bash
# After cloning the current repository: 
cd {repository}
python3 -m venv ./.rover
source ./.rover/bin/activate
```

---

## 🤖 4. ROS 2 Setup

We use **ROS 2 Jazzy Jalisco (LTS)** for rover development.

Follow the official installation instructions here:
👉 [ROS 2 Jazzy Jalisco Install Guide](https://docs.ros.org/en/jazzy/Installation.html)

*(Tip: Ubuntu is the easiest environment for ROS 2, so if you’re on Windows consider using WSL — see next section.)*

---

## 🐧 5. WSL (Optional, Windows Only)

Want a Linux-like environment inside Windows? Install **Windows Subsystem for Linux (WSL)**:

1. Open PowerShell as Administrator and run:

   ```bash
   wsl --install
   ```
2. Restart your computer.
3. Open the “Ubuntu” app from your Start menu, or open Terminal/Powershell and run `wsl`.

This gives you access to the same tools Linux users enjoy, without partitioning your drive into two.

---

## 🔌 6. VS Code Extensions

Make VS Code your all-in-one dev environment:

* 🧰 [Git Extension Pack](https://marketplace.visualstudio.com/items?itemName=donjayamanne.git-extension-pack) – Git tools made simple
* 🤖 [GitHub Copilot](https://marketplace.visualstudio.com/items?itemName=GitHub.copilot) + [Copilot Chat](https://marketplace.visualstudio.com/items?itemName=GitHub.copilot-chat) – AI helper
* 🐍 [Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python) – Python support
* 🐧 [Remote - WSL](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-wsl) – for WSL users
* 🤖 [ROS 2 RDE Pack](https://marketplace.visualstudio.com/items?itemName=Ranch-Hand-Robotics.rde-pack) – ROS2 development made easier

### Source Control Options

You can manage your GitHub repos in different ways:

* **VS Code Source Control Tab** (built-in, very beginner-friendly).
* **GitHub Desktop** if you prefer a GUI.
* **CLI** if you want full power, and to be familiar with CLI for when you might not have a mouse (Raspberry Pi/Integrated Systems)

---

## 🌐 7. Next Steps + Club Resources

* Join the Rover team by filling out this quick survey to get invited to our Discord and assigned roles: [https://forms.gle/npHtGR95Z3k5cKRw5](https://forms.gle/npHtGR95Z3k5cKRw5)
  <details>
    <summary><strong>QR Code</strong></summary>
      <img src="qrcode.jpg" alt="QR Code" width="200" height="200">
  </details>

* Complete the official GitHub Hello World tutorial [here](https://docs.github.com/en/get-started/start-your-journey/hello-world)
* Check out [ROS Projects on Youtube](https://www.youtube.com/results?search_query=intro+to+ros)

---
## 🖥️ Optional: Command Line Basics
Not sure how to navigate folders or use Git commands in the terminal?  
Check out our [Command Line Cheatsheet](./COMMANDS.md) for a quick reference.

---

🎉 You’re ready to code with us!
