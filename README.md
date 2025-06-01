# Running a Git Repo Using Docker

This guide outlines the steps to run a GitHub repository using Docker on an AWS Ubuntu instance.

## Repository

GitHub Repo: [https://github.com/rajendra0968jangid/python-dockerfile](https://github.com/rajendra0968jangid/python-dockerfile)

---

## Steps to Deploy

### Step 1: Launch AWS Ubuntu Instance
- Create an Ubuntu instance on AWS EC2.

### Step 2: Install Docker
- Connect to your instance via SSH.
- Install Docker using:
  ```bash
  sudo apt update
  sudo apt install docker.io -y
