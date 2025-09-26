## 0.1. Table of Contents
- [1. SoftwareOnboarding2025](#1-softwareonboarding2025)
  - [1.1. Git and Github setup](#11-git-and-github-setup)
  - [1.2. SSH Keys](#12-ssh-keys)
  - [1.3. Vscode Setup](#13-vscode-setup)
  - [1.4. Install Python](#14-install-python)

# 1. SoftwareOnboarding2025

## 1.1. Git and Github setup
### Setup Process
<details>
<summary><strong>Windows</strong></summary>

install [git](https://git-scm.com/downloads)

</details>

<details>
<summary><strong>Mac</strong></summary>

Open terminal, paste this command and press enter to install homebrew  
`/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`

Then use brew to install git  
`brew install git`

</details>

<details>
<summary><strong>Linux</strong></summary>

here's an example for Ubuntu, other distros will be similar but with a different package manager  
`sudo apt update`  
`sudo apt upgrade`  
`sudo apt install git`

</details>

### Basic Git Commands

To clone a repo onto your device: 
```bash
git clone https://github.com/{USERNAME}/{REPO_NAME}
```
Following this clone, you can now access the directory using: 
```bash
cd {REPO_NAME}
```
  
To update local files:
```bash
git pull
```

To update the Git repository to match local files:
```bash
git add .
git commit -m "{Commit Message})"
git push
```


---

## 1.2. SSH Keys

Follow [this](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent) guide

---

## 1.3. Vscode Setup

<details>
<summary><strong>Windows and Mac</strong></summary>

install [vscode](https://code.visualstudio.com/download)

</details>

<details>
<summary><strong>Linux</strong></summary>

here's an example for Ubuntu, other distros will be similar but with a different package manager  
`sudo snap install --classic code`

</details>


## 1.4. Install Python

<details>
<summary><strong>Windows</strong></summary>

install [python](https://www.python.org/downloads/)
**when it prompts you, select "Add to PATH"**

</details>

<details>

<summary><strong>Mac</strong></summary>

`brew install python`

</details>

<details>

<summary><strong>Linux</strong></summary>

`sudo apt install python3`
`sudo apt install python3-pip`

</details>

**venv setup:**
in order to use pip packages you need to set up a venv (virtual environment)

go to your terminal (git bash for windows, terminal for everyone else)

and type 
`python3 -m venv ~/.rover`
`source ~/.rover/bin/activate` 




 
