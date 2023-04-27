
## Summary (Summarize the bug encountered concisely)

Incorrect word displays in a GitLab main page in the section "Create black project", which should be "Create blank project"

## Steps to reproduce

  1. Open the website on Safari version 15.6.1.
  2. Navitage to https://gitlab.com/users/sign_in.
  3. Log in with correct username/email and password. 
  4. In the main page press "Create the project" button. 
  5. In the projects page the section "Create black project" has a word "black" incorrect. 
  6. Open the code and navigate to right place where the wrong word "black" is.
  7. Find the code <h3 class= "gl-font-size-h2 gl-reset-color"> "Create black project <h3> and correct "black" word to "blank". 
  8. Save the code of the file. 
  9. Go back to https://gitlab.com/projects/new and refersh the page to make sure that the correct word "blank" is in the right place.     

## What is the current bug behavior?

Incorrect word "black" is displaying in page https://gitlab.com/projects/new section "Create black project". 
    
## What is the expected correct behavior?

Section "Create black project" in page https://gitlab.com/projects/new, should be the word "blank", instead of "black".
     
## Relevant logs and/or screenshots

Code of the website on Macbook Air (Early 2015) MacOS Big Sur version 11.5.2 : <h3 class= "gl-font-size-h2 gl-reset-color"> "Create black project" <h3> . Displays incorrect word "black". 

## Possible fixes

To fix the bug needs to change the incorrect word "black" to "blank" for the sentence "Create black project" in a code. 

## Whom do you report/ Assign To/ Tags

Whom do you report

    - Technical Lead or manager

Assign to 

    - AQ tester

Tags

    - Frontend 
    - Copywriting
    - Text
    - Content

## Priority

Priority: Low 

      
