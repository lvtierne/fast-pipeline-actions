# Fast Pipeline Actions
CI/CD with GitHub Actions and AWS EC2+Nginx.

## Daily Updates
### Day 1: March 12, 2025
- GitHub Actions workflow (`fast-pipeline.yml`) echoes "Started!".
- EC2 t2.micro with Nginx "Welcome" page.
<br>

------------------------------------------------
# Fast Pipeline Actions - Daily Updates
Quick CI/CD setup with GitHub Actions and AWS EC2 hosting Nginx.

## Overview
Building a fast, lightweight pipeline to automate tasks and deploy a web server. Started with GitHub Actions (switched from Jenkins for speed) and launched an EC2 instance with Nginx.

## Daily Updates
### Day 1: March 12, 2025
- **What I Did:**
  - Set up GitHub Actions with a "hello world" job.
  - Launched an AWS EC2 t2.micro instance, installed Nginx, and served a "Welcome" page.
  - Made 2 commits: Actions workflow and EC2 notes.
- **How I Did It:**
  - Actions: Created `.github/workflows/fast-pipeline.yml` to echo "Started!" on push.
  - EC2: Used AWS Free Tier, SSH’d in with PuTTY (Windows 11), ran `sudo amazon-linux-extras install nginx1 -y`, added `index.html` to fix 404.
  - Git: Committed locally (`git add/commit/push`) from Windows 11.
- **Why I Did It:**
  - Actions over Jenkins: Faster setup, no local Java hassle on Windows 11 Home.
  - EC2 with Nginx: Quick proof-of-concept for hosting, learning AWS basics.
  - Goal: Test a minimal CI/CD-to-cloud workflow in 5 hours.

## Files
- `.github/workflows/fast-pipeline.yml`: Actions config.
- `ec2-notes.txt`: EC2 setup details.
