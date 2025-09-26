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
- Tags used for marking releases (e.g., v1.0).  

## Ignore Rules
Common unnecessary files excluded using `.gitignore`.  

