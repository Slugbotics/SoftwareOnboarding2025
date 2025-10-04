## 0.1. Table of Contents
- [1. SoftwareOnboarding2025](#1-softwareonboarding2025)
  - [1.1. Git and Github setup](#11-git-and-github-setup)
  - [1.2. Navigating the Command Line](#12-navigating-the-command-line)
  - [1.3. SSH Keys](#13-ssh-keys)
  - [1.4. Vscode Setup](#14-vscode-setup)
  - [1.5. Install Python](#15-install-python)
  - [1.6. Rover Team Interest Survey](#16-rover-team-interest-survey)

# 1. SoftwareOnboarding2025

Get started with essential tools and skills for software development.

## 1.1. Git and Github setup
Install Git and learn basic commands to manage code with GitHub.

### Setup Process
<details>
<summary><strong>Windows</strong></summary>

Download and install [Git](https://git-scm.com/downloads).

</details>

<details>
<summary><strong>Mac</strong></summary>

Install Homebrew:  
`/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`

Then use brew to install git  
`brew install git`

</details>

<details>
<summary><strong>Linux</strong></summary>

For Ubuntu:  
`sudo apt update && sudo apt install git`

</details>

### Basic Git Commands

Clone a repo:  
`git clone https://github.com/{USERNAME}/{REPO_NAME}`

Enter folder:  
`cd {REPO_NAME}`

Update files:  
`git pull`

Save changes:  
`git add .`  
`git commit -m "Your message"`  
`git push`

## 1.2. Navigating the Command Line
Learn basic terminal commands to navigate files and folders.

<details>
  <summary><strong>Mac and Linux</strong></summary>
  
  Change directory: `cd {directory_name}`  
  Go back: `cd ..`  
  Create file: `touch {filename.txt}`  
  Create folder: `mkdir {directory_name}`  
  Delete file: `rm {file_name}`  
  Delete folder: `rm -rf {directory_name}`  
  View file: `cat {file_name}`  
  List files: `ls` or `ls {path/to/folder}`
  
</details>

<details><summary><strong>Windows</strong></summary>

  Change directory: `cd {directory_name}`  
  Go back: `cd ..`  
  Create file: `echo. > {filename.txt}`  
  Create folder: `mkdir {directory_name}`  
  Delete file: `del {file_name}`  
  Delete folder: `rmdir /S /Q {directory_name}`  
  View file: `type {file_name}`  
  List files: `dir` or `dir {path\to\folder}`

</details>

## 1.3. SSH Keys
Generate SSH keys for secure, password-less GitHub access.

Follow [this guide](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent).

## 1.4. Vscode Setup
Install Visual Studio Code, a free code editor.

<details>
<summary><strong>Windows and Mac</strong></summary>

Download from [VS Code](https://code.visualstudio.com/download).

</details>

<details>
<summary><strong>Linux</strong></summary>

For Ubuntu: `sudo snap install --classic code`

</details>

## 1.5. Install Python
Install Python and create a virtual environment for projects.

<details>
<summary><strong>Windows</strong></summary>

Download [Python](https://www.python.org/downloads/). Check "Add to PATH".

</details>

<details>
<summary><strong>Mac</strong></summary>

`brew install python`

</details>

<details>
<summary><strong>Linux</strong></summary>

`sudo apt install python3 python3-pip`

</details>

**Virtual Environment:**  
Create: `python3 -m venv ~/.rover`  
Activate: `source ~/.rover/bin/activate`

## 1.6 Rover Team Interest Survey
Fill out the form to get Discord roles and join the Rover team.

Form: [https://forms.gle/npHtGR95Z3k5cKRw5](https://forms.gle/npHtGR95Z3k5cKRw5)  
<details>
  <summary><strong>QR Code</strong></summary>
  <img src="qrcode.jpg" alt="QR Code" width="200" height="200">
</details>





