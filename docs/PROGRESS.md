# SnapShot: Project Plan and Progress

## Goal
A booking, gallery and admin app for my photobooth business. I'm building it to learn Git, GitHub, CI/CD and AWS properly, and to use it as a portfolio piece.

## Instructions for the AI assistant (read this first in a new chat)
- I'm a beginner. Explain each concept before we build it, and check my understanding at the end of each stage.
- I write the code and you review it. Don't just hand me finished code.
- I'm on Windows with PowerShell. Repo: https://github.com/boyo-code/SnapShot
- I can spend 8-10 hours a week.

## Stack
- Backend: Python 3.12 with FastAPI
- Database: SQLite locally, then PostgreSQL (AWS RDS)
- Frontend: plain HTML and JavaScript at first
- Tooling: Git, GitHub, GitHub Actions, Docker, pytest
- AWS: S3 (photos), App Runner or ECS (hosting), RDS (database), IAM (permissions)

## Stages
- [x] 1. Git and GitHub foundations: first commit, branches, pull requests, branch protection, issues
- [ ] 2. Design: user stories, data model (bookings, packages, galleries, photos)
- [ ] 3. Core backend: booking API, validation, admin login, tests
- [ ] 4. CI with GitHub Actions: lint and test on every pull request
- [ ] 5. Docker: containerise the app
- [ ] 6. AWS setup: billing alarm, IAM, database, S3
- [ ] 7. CD: auto-deploy on merge to main, using OIDC (no stored secrets)
- [ ] 8. Gallery and admin dashboard: S3 uploads, expiring private links, bookings view
- [ ] 9. Production polish: logging, monitoring, backups, domain and HTTPS, README with screenshots
- [ ] 10. Portfolio: case study and practice walkthrough

## Notes (what I learned)
- Git is the tool on my computer. GitHub is the website that hosts repos.
- Git has three areas: working directory, staging area, repository.
