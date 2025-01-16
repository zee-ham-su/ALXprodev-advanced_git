# Git and Github - Advanced

## Learning Objectives

At the end of this project, you should be able to:

- Understand what is GitFlow and how to use it
- Create and merge branches using GitFlow workflow
- Handle pull requests and code reviews
- Resolve merge conflicts effectively
- Work collaboratively using Git

## GitFlow Workflow

GitFlow is a branching model for Git that provides a robust framework for managing larger projects. It defines specific branch roles and how they should interact.

### Main Branches

- `main` - Contains production code
- `develop` - Contains pre-production code

### Supporting Branches  

- `feature/*` - Used to develop new features
- `release/*` - Prepare for a production release
- `hotfix/*` - Fix critical bugs in production
- `bugfix/*` - Fix bugs in development

## Basic Commands

```bash
# Initialize GitFlow
git flow init

# Start a new feature
git flow feature start feature_name

# Finish a feature
git flow feature finish feature_name

# Start a release
git flow release start release_name

# Finish a release
git flow release finish release_name

# Start a hotfix
git flow hotfix start hotfix_name
