## 0.1. Table of Contents
- [1. SoftwareOnboarding2025](#1-softwareonboarding2025)
  - [1.1. Git and Github setup](#11-git-and-github-setup)
  - [1.2. Navigating the Command Line](#12-navigating-the-command-line)
  - [1.3. Github CLI](#13-github-cli)
  - [1.4. Vscode Setup](#14-vscode-setup)
  - [1.5. Install Python](#15-install-python)
  - [1.6. Rover Team Interest Survey](#16-rover-team-interest-survey)

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
`cd {REPO_NAME}`
  
To update local files:
```bash
git pull
```

To update the Git repository to match local files:
```bash
git add .
git commit -m "{Commit Message}"
git push
```
## 1.2. Navigating the Command Line
<details>
  <summary><strong>Mac and Linux</strong></summary>
  
  To move through directories:
  ```bash
  cd {directory_name}
  ```
  
  To move backwards through directories:
  ```bash
  cd ..
  ```

  To make a new file:
  ```bash
  touch {filename.txt}
  ```
  To make a new directory:
  ```bash
  mkdir {directory_name}
  ```
  
  To delete a file:
  ```bash
  rm {file_name}
  ```
To delete a directory (and contents): 
```bash
rm -rf {directory_name}
```
  To view a file without accessing:
  ```bash
  cat {file_name}
  ```
  To view current directory:
  ```bash
ls
```
or
```bash
ls {path/to/directory/directory_name}
```
  
</details>

<details><summary><strong>Windows</strong></summary>

  To move through directories:
  ```bash
  cd {directory_name}
  ```
  To move backwards through directories:
  ```bash
  cd ..
  ```
  To make a new file:
  ```bash
  echo. > {filename.txt}
  ```
  To make a new directory:
  ```bash
  mkdir {directory_name}
  ```
  
  To delete a file:
  ```bash
  del {file_name}
  ```
To force delete a directory(and contents): 
```bash
rmdir /S /Q {directory_name}
```
  To view a file without accessing:
  ```bash
  type {file_name}
  ```
  To view current directory:
  ```bash
dir
```
or
```bash
dir {path/to/directory/directory_name}
```

</details>

<details><summary><strong>Windows Powershell</strong></summary>

To move through directories:
  ```bash
  cd {directory_name}
  ```
  To move backwards through directories:
  ```bash
  cd ..
  ```
  To make a new file:
  ```bash
  New-Item {filename.txt}
  ```
  To make a new directory:
  ```bash
  New-Item -ItemType Directory {directory_name}
  ```
  
  To delete a file:
  ```bash
  Remove-Item {file_name}
  ```
To force delete a directory(and contents): 
```bash
Remove-Item {directory_name} -Recurse -Force
```
  To view a file without accessing:
  ```bash
  Get-Content {file_name}
  ```
  To view current directory:
  ```bash
Get-ChildItem
```



</details>

---

## 1.3. Github CLI

Instead of using SSH keys, we recommend authentication using github CLI ('gh')

### Step 1: Install Github CLI
<details>
  <summary><strong>Windows</strong></summary>
  Download the GitHub CLI installer from [here](https://cli.github.com/).  
Alternatively, install via **winget**:  
```bash
winget install --id GitHub.cli
```
</details>

<details>
  <summary><strong>Mac</strong></summary>
  Install using homebrew:
  ```bash
  brew install gh
  ```
</details>

<details>
  <summary><strong>Linux</strong></summary>
```bash
  sudo apt install gh
  ```
</details>

### Step 2: Authenticate Github
```bash
gh auth login
```
You will be guided through the following: 
1. Select Github.com
2. Select HTTPS as preferred protocol
3. When asked, click "Login with a web broswer"
4. Follow on screen instructions to copy and paste a one time code
5. Test your connection with:
```bash
gh auth status
```

### Step 3: Using Github ClI

Github CLI gives you access to useful commands, such as 
`gh repo clone owner/repo-name`
`gh issue list`
`gh pr create`
`gh repo view`

---

## 1.4. Vscode Setup

<details>
<summary><strong>Windows and Mac</strong></summary>

install [vscode](https://code.visualstudio.com/download)

</details>

<details>
<summary><strong>Linux</strong></summary>

here's an example for Ubuntu, other distros will be similar but with a different package manager  
`sudo snap install --classic code`

</details>


## 1.5. Install Python

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

## 1.6 Rover Team Interest Survey


  Please fill out [this form](https://forms.gle/npHtGR95Z3k5cKRw5) to gain your specific discord roles
  <details>
    <summary><strong>QR Code</strong></summary>
  <img src="qrcode.jpg" alt="QR Code" width="200" height="200">
  </details>




 
