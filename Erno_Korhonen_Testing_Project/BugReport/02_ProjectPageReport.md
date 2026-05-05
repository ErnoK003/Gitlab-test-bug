## Summary (Summarize the bug encountered concisely)

Small typo in creating blank project.


## Steps to reproduce

Start creating a new project
    Navigate to https://gitlab.com/projects/new#
    Projects -> New project
    'Create blank project' has the bug


## What is the current bug behavior?

Here it says 'Create black project'


## What is the expected correct behavior?

Expected behavior is 'Create blank project'


## Relevant logs and/or screenshots

![Create black project](/Image/New_Black_Project.png)


## Possible fixes

Fix in HTML, change the text black into blank. Search for href="#blank_project" in HTML file. Just a few lines down.


## Whom do you report/ Assign To/ Tags

Tags: HTML, Projects, New project
Retesting can be done by anyone. It is just a simple typo.


## Priority

Trivial, Simple fix.
