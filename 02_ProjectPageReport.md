
## Summary (Summarize the bug encountered concisely)
There is a typographical error a button present on the create a new project page.


## Steps to reproduce     
To reproduce the bug we must navigate to the GitLab project creation page (https://gitlab.com/projects/new#blank_project), the error is in the button intended for creating a new blank project.
   

## What is the current bug behavior?
The button is labeled as "Create black project".
     

## What is the expected correct behavior?
The button should be labeled as "Create blank project".

     
## Relevant logs and/or screenshots
![Screenshot of typo](https://ibb.co/Xxmgxyk)
    

## Possible fixes
The typo in the source code needs to be corrected. This is likely located in the HTML file in which the project creation page is located, where there is a misspelling of the word "blank" in the button text.


## Whom do you report/ Assign To/ Tags
/label ~bug ~typo ~ui
/cc @project-manager
/assign @frontend-developer


## Priority
Minor - The typo doesn't impact the functionality of the button but can influence negatively the user experience.

      
