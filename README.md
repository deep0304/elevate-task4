# DevOps Project Task 4

## Overview
This project demonstrates Git workflows in a DevOps context.

## Branching Strategy
- **main** → stable production branch  
- **dev** → integration branch  
- **feature-\*** → feature-specific branches  

## App File
- `app.py`: simple Python app returning a greeting.  

## Workflow
1. Feature branches created from dev.  
2. Work committed on feature branches.  
3. Pull request from feature → dev.  
4. Once stable, dev → main.  

## Versioning
- Tags are used for marking stable releases (e.g., `v1.0`).  

## Ignore Rules
- Common unnecessary files are excluded using `.gitignore`.  

## Screenshots

### Pull Request from Feature Branch
Pull request created from `feature-setup` → `dev`.  

<img width="933" height="383" alt="pull request from feature-setup" src="https://github.com/user-attachments/assets/ae83215e-2c86-445f-b2ce-a5590f750667" />

### Merge into Dev Branch
Pull request merged into `dev`.  

<img width="974" height="477" alt="merge into dev" src="https://github.com/user-attachments/assets/c8e42270-43d1-49f7-81ad-97e93e300892" />

### Merge into Main Branch
Pull request merged from `dev` → `main`.  

<img width="895" height="440" alt="merged into main" src="https://github.com/user-attachments/assets/9bdddd5f-4555-4171-84e4-ded82efc8b84" />

### Tag Added to Repo
Tag `v1.0` created and pushed to the repository.  

<img width="895" height="440" alt="tag v1.0 created" src="https://github.com/user-attachments/assets/93987c4a-1209-403f-b3d3-f7f58ec6a847" />
