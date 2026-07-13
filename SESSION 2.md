# Git & GitHub Workshop Part 2 (Malayalam)

This session builds on the fundamentals covered in Part 1 and focuses on practical Git workflows used in real-world software development. Topics include branching, merging, collaboration, resolving conflicts, and customizing your GitHub profile.

If you're new to Git, it's recommended to watch **Part 1** before following this workshop.

👨‍🏫 Workshop Instructor: Nithin A 

🔗 Workshop Resources: <br>
• GitHub Workshop Repository: https://github.com/Underemployed/gitflow4 <br>
•  Session 1 Notes:
https://github.com/Underemployed/gitflow4/blob/main/README.md <br>
•  Session 2 Notes:
https://github.com/Underemployed/gitflow4/blob/main/SESSION%202.md <br>

📺 Watch Part 1:<br>
• Git & GitHub Workshop (Malayalam) | Session 1:
https://www.youtube.com/watch?v=XCChijCuqOs&list=PLiCelQ3GQcPbGllN0M7Y7ssUkRPZTgxLk&index=1 <br>
📺 Watch Part 2:<br>
• Git & GitHub Workshop (Malayalam) | Session 2:
https://www.youtube.com/watch?v=GpqFRMq2YJY&list=PLiCelQ3GQcPbGllN0M7Y7ssUkRPZTgxLk&index=2 <br>


---

## Quick Revision (Part 1)

A quick recap of the essential Git commands and workflow covered in Session 1.

**Timestamp:** https://www.youtube.com/live/XCChijCuqOs

---

## VS Code Integration & Git Authentication

### GitHub Authentication

When pushing to GitHub for the first time, Git may ask you to authenticate through your browser. Complete the authorization process to connect your local Git installation with your GitHub account.

### VS Code Git Integration

Visual Studio Code provides built-in Git support, allowing you to:

- Stage files
- Commit changes
- View differences
- Push and pull changes
- Visualize commit history
- Manage branches

For Python development, install the official **Microsoft Python Extension** from the VS Code Marketplace.

**Timestamp:** https://youtu.be/XCChijCuqOs?t=125

---

## Git Workflow Refresher

### Stage All Changes

```bash
git add .
```

### Commit Changes

```bash
git commit -m "Your commit message"
```

### Push to GitHub

```bash
git push
```

**Timestamp:** https://youtu.be/XCChijCuqOs?t=363

---

## Synchronizing with GitHub

If changes are made directly on GitHub (or by another collaborator), update your local repository before continuing.

### Pull Latest Changes

```bash
git pull
```

**Timestamp:** https://youtu.be/XCChijCuqOs?t=567

---

## Working with Branches

Branches allow you to work on new features or fixes without affecting the main codebase.

### Create and Switch to a New Branch

```bash
git checkout -b feature-branch
```

### Switch Between Existing Branches

```bash
git checkout branch-name
```

### Push a New Branch

```bash
git push -u origin branch-name
```

**Timestamp:** https://youtu.be/XCChijCuqOs?t=864

---

## Merging Branches

Once development is complete, merge your feature branch into the target branch.

### Switch to the Target Branch

```bash
git checkout main
```

### Merge Another Branch

```bash
git merge feature-branch
```

**Timestamp:** https://youtu.be/XCChijCuqOs?t=1998

---

## Correcting Mistakes

Update the most recent commit after staging additional changes.

```bash
git commit --amend
```

This is useful for:

- Correcting commit messages
- Including forgotten files
- Making small fixes before pushing

**Timestamp:** https://youtu.be/XCChijCuqOs?t=2076

---

## Collaboration & Merge Conflicts

### Add Collaborators

Repository Settings → Collaborators → Invite using GitHub username.

### Resolve Remote Changes

Before pushing, pull the latest changes.

```bash
git pull --rebase
```

Using `--rebase` keeps your Git history cleaner and reduces unnecessary merge commits.

**Timestamp:** https://youtu.be/XCChijCuqOs?t=4106

---

## Deploying with GitHub Pages

Host your static website directly from GitHub.

Go to:

**Repository → Settings → Pages → Deploy from Branch → Select Branch → Save**

**Timestamp:** https://youtu.be/XCChijCuqOs?t=5436

---

## Creating a GitHub Profile README

Create a repository with the **exact same name as your GitHub username** to enable your profile README.

You can customize it with:

- About Me
- Skills
- Tech Stack
- GitHub Statistics
- Social Links
- Contribution Graphs
- Badges

Profile README Generator:

https://gprm.itsvg.in/

**Timestamp:** https://youtu.be/XCChijCuqOs?t=5688

---

## Topics Covered

- VS Code Git Integration
- Git Authentication
- Git Workflow
- git pull
- Branching
- Branch Management
- Merging
- git commit --amend
- Merge Conflicts
- Collaboration
- GitHub Pages
- GitHub Profile README
- GitHub Profile Customization

---
🤝 Organized by:
ISTE Student Chapter, Government Engineering College Barton Hill
Website:
https://istegecb.in/check-us-out

If you found this workshop helpful, consider sharing it with friends who are beginning their software development journey. Feel free to ask your Git and GitHub questions in the comments below.