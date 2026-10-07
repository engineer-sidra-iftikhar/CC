# Assignment 01: Git, Gitea, GitHub, Git LFS, and GitHub Pages

| | |
|---|---|
| **University** | Fatima Jinnah Women University |
| **Department** | Software Engineering |
| **Course** | Cloud Computing (BSE-410) |
| **Semester** | BS(SE)-V |
| **Submitted To** | Sir Waqas Saleem |
| **Submitted By** | Sidra Iftikhar |
| **Registration No** | FA24B1-SE-063 |
| **GitHub Username** | engineer-sidra-iftikhar |
| **Submission Date** | 02-10-2026 |

---

## Summary of Work

### Task 1: Install Gitea and Push a Repository from the Ubuntu Server
- Installed Docker Engine and the Docker Compose plug-in on the Ubuntu server.
- Cloned the instructor's Gitea setup repository and started Gitea and PostgreSQL with `docker compose up -d`.
- Confirmed both containers were running and Gitea returned HTTP status 200 on port 3000.
- Created a public `Assignment01` repository in Gitea and a separate local repository on the server.
- Added `README.md` (full name and registration number), committed it, and pushed it to Gitea using a personal access token (no token in the remote URL).

### Task 2: Push the Same Repository to GitHub
- Created a public `Assignment01` repository on GitHub.
- Added `github` as the second remote alongside `gitea` and verified both with `git remote -v`.
- Pushed the `main` branch to GitHub.

### Task 3: Track Three Large Files with Git LFS
- Ran `git lfs install` and tracked `*.bin` files.
- Created three files larger than 100 MiB (`large-file-1.bin`, `large-file-2.bin`, `large-file-3.bin`).
- Verified them with `git lfs ls-files --size`, committed, and pushed to GitHub (LFS upload 100% (3/3)).

### Task 4: Create a Portfolio with GitHub Pages
- Created the `engineer-sidra-iftikhar.github.io` repository with `index.html` and `styles.css`.
- The portfolio contains the About Me, Education, Skills, and Projects sections.
- Published it with GitHub Pages (Deploy from a branch, `main`, `/ (root)`).

---

## Links

| Item | Link |
|---|---|
| CC repository (submission) | https://github.com/engineer-sidra-iftikhar/CC |
| GitHub Assignment01 repository | https://github.com/engineer-sidra-iftikhar/Assignment01 |
| Portfolio repository | https://github.com/engineer-sidra-iftikhar/engineer-sidra-iftikhar.github.io |
| Live portfolio (GitHub Pages) | https://engineer-sidra-iftikhar.github.io/ |
| Gitea Assignment01 repository (local lab server) | http://192.168.124.132:3000/engineer-sidra-iftikhar/Assignment01 |

---

## Submission Files

```
CC/
└── Assignments/
    └── Assignment01/
        ├── Assignment01.md
        ├── Assignment01_Solution.docx
        ├── Assignment01_Solution.pdf
        └── screenshots/
            ├── task1_gitea_running.png
            ├── task1_gitea_push.png
            ├── task1_gitea_repository.png
            ├── task2_remotes.png
            ├── task2_github_push.png
            ├── task2_github_repository.png
            ├── task3_lfs_setup.png
            ├── task3_lfs_files.png
            ├── task3_lfs_push.png
            ├── task4_pages_repository.png
            ├── task4_pages_deployment.png
            └── task4_portfolio_live.png
```

---

*I completed this assignment individually, and all screenshots are from my own work.*
