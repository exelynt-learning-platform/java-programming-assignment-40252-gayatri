# Git Environment Checklist for a New Intern

## 1. Introduction

Git is a distributed version control system used to track changes in files and manage source code. It helps developers work together, maintain project history, and manage different versions of a project.

## 2. Git Installation Steps

### Windows
1. Visit https://git-scm.com/download/win.
2. Download and run the Git installer.
3. Follow the installation instructions and open Git Bash or Command Prompt.

### macOS
1. Open Terminal.
2. Run `xcode-select --install` to install Apple's command-line developer tools, which include Git.
3. Follow the installation instructions and verify Git is installed.

### Linux (Ubuntu/Debian)
1. Open the Terminal.
2. Update package information using `sudo apt update`.
3. Install Git using `sudo apt install git`.

## 3. Verify Git Installation

Run this command in the terminal:

```bash
git --version
```

**Actual output from my computer:**

```text
[Paste your actual git --version output here]
```

## 4. Configure Git User Details

Git requires a username and email address to identify the author of commits.

Run these commands:

```bash
git config --global user.name "Your Name"
git config --global user.email "your-email@example.com"
```

Replace the example details with your own name and GitHub-associated email address.

Verify the configuration:

```bash
git config --global --list
```

**Actual output (name and email lines only):**

```text
[Paste your actual user.name and user.email output here]
```

## 5. Terminal Basics

The following commands are useful for navigating folders and managing files.

### 1. pwd
Displays the current working directory.

Command:
```bash
pwd
```

Output:
```text
[Paste your actual output here]
```

### 2. ls / dir
Displays the files and folders in the current directory.

Command:
```bash
ls
```
On Windows Command Prompt, use:
```cmd
dir
```

Output:
```text
[Paste your actual output here]
```

### 3. cd
Changes the current working directory.

Command:
```bash
cd folder-name
```

Output:
```text
[Paste your actual output or show the directory after running pwd]
```

### 4. mkdir
Creates a new directory.

Command:
```bash
mkdir intern-practice
```

Output:
```text
[Paste your actual output here]
```

Note: `mkdir` normally produces no output when successful. You can verify the folder was created by running `ls` or `dir`.

## 6. Git Assignment Branch and Commit

Create a new branch for this assignment:

```bash
git switch -c assignment/git-installation-setup
```

Add the checklist file:

```bash
git add onboarding-checklist.md
```

Commit the changes:

```bash
git commit -m "docs: add Git installation and setup checklist"
```

Push the branch to GitHub:

```bash
git push -u origin assignment/git-installation-setup
```

## 7. Conclusion

Git installation and configuration are important first steps for every software development intern. Understanding basic terminal commands helps developers navigate their projects. Git also makes it easier to track changes, create branches, commit work, and collaborate with other developers.

**Checklist:**
- [ ] Git installed successfully.
- [ ] Git version verified.
- [ ] Global username configured.
- [ ] Global email configured.
- [ ] Terminal commands executed.
- [ ] Assignment branch created.
- [ ] Changes committed.
- [ ] Branch pushed to GitHub.
