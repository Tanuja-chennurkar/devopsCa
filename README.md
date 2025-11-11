# DevOps CA – Linux File Operations & Git Workflow

This repository demonstrates basic Linux file operations combined with a Git branching workflow as part of the DevOps Continuous Assessment (CA).

## 🧩 Part A – Linux File Operations
- Created directories: `/pending`, `/completed`, `/logs`
- Added a sample order file `pending_order1.txt` under `pending`
- Moved order files from `pending` to `completed`
- Logged movements in `logs/movements.log`
- Compressed completed orders into `completed_backup.tar.gz`
- Displayed and saved disk usage details into `logs/usage.txt`

## 🌿 Part B – Git Workflow
- Initialized local repository in `/var/orders`
- Created `.gitignore` to exclude backup and log files
- Made initial commit with base order files
- Created and switched to branch `update-logs`
- Updated `movements.log` and committed the change
- Merged branch `update-logs` into `main`

## ✅ Tools Used
- **Linux Commands:** `mkdir`, `mv`, `tar`, `du`, `echo`
- **Version Control:** Git (branching, merging, ignore rules)

---

### Submitted By
**Tanuja Chennurkar**  
B.Tech CSE | Lovely Professional University  
Date: *November 11, 2025*
