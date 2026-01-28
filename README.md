# Git Flow Workflow Demo

## Current Stage 1:
Initial repository setup on main branch.

## Purpose
This repository demonstrates the Git Flow branching strategy step by step.

## Stage 2: Develop Branch

The develop branch is created from main.
All feature branches will be created from develop.

## Stage 3: Feature Development

Feature branches are created from develop.
This branch adds login feature documentation.

### Feature Merge

The feature/login branch was reviewed and merged into develop using a Pull Request.

## Stage 4: Release Preparation

Release branch v1.0 is created from develop.
Only bug fixes and documentation updates are allowed.

### Production Release

Release v1.0 has been merged into main.
Main now reflects production-ready code.

## Stage 5: Hotfix

Hotfix branch created from main to fix production issue.

### Hotfix merge
The hotfix/fix-readme branch was reviewed and merged into main using a Pull Request.