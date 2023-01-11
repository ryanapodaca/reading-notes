# Git

Git is a distributed version control system (DVCS)

A DVCS accounts for the limitations of centralized version control system.
Centralized systems are at higher risk of losing information due to centralization.
Distributed systems also allow for non-linear development workflows.  

Git functions by producing snapshots, or place markers, of the development process.

Files within Git will be in one of 3 states:

1. staged 
2. modified - file has been changed but not committed to a base
3. commited - data securely stored in local data base

## Local Repository Structure

1. Working Directory - where actual files exist
2. Index - area for staging
3. Head - shows the most recent commit

## Notable Git Commands

git help (Produces all commands)

git status (Shows changes to commited files)

git add (for staging)

git commit -m "explanations for changes go here"

git push origin main