## Git & GitHub Workshop for Beginners  Session 1

This workshop covers the fundamentals of **Git**, **GitHub**, and **Version Control** in Malayalam through practical demonstrations. It is intended for students, beginners, and anyone looking to start collaborating on software projects or contribute to open source.

To follow the workshop effectively, use this guide alongside the video.

---

## Initial Setup

### Create a GitHub Account

Create a free GitHub account to host your repositories and collaborate with other developers.

**Website:** https://github.com

**Timestamp:** https://youtube.com/live/XCChijCuqOs?t=101

### Install Git

Download and install Git for your operating system.

**Website:** https://git-scm.com

**Timestamp:** https://youtube.com/live/XCChijCuqOs?t=705

### Install Visual Studio Code

VS Code is used throughout the workshop for writing and managing code.

**Website:** https://code.visualstudio.com

**Timestamp:** https://youtube.com/live/XCChijCuqOs?t=1372

---

## Essential Git Commands

### Initialize a Repository

```bash
git init
```

**Timestamp:** https://youtube.com/live/XCChijCuqOs?t=3290

### Stage Files

Stage a specific file:

```bash
git add filename
```

Stage all changes:

```bash
git add .
```

**Timestamp:** https://youtube.com/live/XCChijCuqOs?t=3956

### Commit Changes

```bash
git commit -m "Your descriptive commit message"
```

**Timestamp:** https://youtube.com/live/XCChijCuqOs?t=4556

### Check Repository Status

```bash
git status
```

**Timestamp:** https://youtube.com/live/XCChijCuqOs?t=5634

### View Commit History

Detailed history:

```bash
git log
```

Compact history:

```bash
git log --oneline
```

**Timestamps:**

- https://youtube.com/live/XCChijCuqOs?t=5667
- https://youtube.com/live/XCChijCuqOs?t=5741

---

## Connecting Your Project to GitHub

### Add a Remote Repository

```bash
git remote add origin <repository-url>
```

**Timestamp:** https://youtube.com/live/XCChijCuqOs?t=4899

### Verify the Remote

```bash
git remote -v
```

**Timestamp:** https://youtube.com/live/XCChijCuqOs?t=5049

### Push Your Project

For most new repositories:

```bash
git push -u origin main
```

If your repository uses the older **master** branch, replace `main` with `master`.

**Timestamp:** https://youtube.com/live/XCChijCuqOs?t=5269

---

## Security & Best Practices

### Ignore Sensitive Files

Create a `.gitignore` file to prevent files like passwords, API keys, virtual environments, or dependencies from being tracked.

Example:

```text
.env
node_modules/
passwords.txt
```

**Timestamp:** https://youtube.com/live/XCChijCuqOs?t=4392

---

## Deploy with GitHub Pages

You can host static websites for free using GitHub Pages.

Go to:

**Repository → Settings → Pages → Deploy from Branch → main (or master) → Save**

**Timestamp:** https://youtube.com/live/XCChijCuqOs?t=5337

---

### Topics Covered

- Introduction to Git
- Git vs GitHub
- Version Control
- Repositories
- Commits
- Branching
- GitHub Remotes
- GitHub Pages
- `.gitignore`
- Git Workflow
- Best Practices

---

This workshop was conducted in Malayalam under **ISTE Student Chapter, Government Engineering College Barton Hill (ISTE SC GECB)**. 

https://istegecb.in/check-us-out


If you found this session useful, consider sharing it with friends who are beginning their software development journey.



#Git #GitHub #GitTutorial #GitHubTutorial #GitMalayalam #GitHubMalayalam #VersionControl #OpenSource #Programming #SoftwareDevelopment #Coding #ISTEGECB #KeralaTech