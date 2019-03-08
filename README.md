# Project Luncher

## Git workflow
1. Each student's role should have a separate repository. 
    Example:
    ```
    UI (Landing page) - separate repo,
    Front End (react app) - separate repo
    Back End (API) - separate repo
    ```
    If you are working together with another student with the same role, you will both work on the same repo on separate branches. Branches naming convention: `firstname-lastname`

2. Don't **fork** the repo!
3. Clone the master branch of the assigned repo to you.
4. Before creating a new branch, pull the changes from upstream. Your master needs to be up to date.
    ```
    git pull
    ```
5. Create a new branch with your first name and last name
    ```
    git branch [firstname-lastname]
    ```
6. Switch your working directory to your newly created branch
    ```
    git checkout [firstname-lastname]
    ```
7. CODE CODE CODE
8. Checkout to master branch `git checkout master`
9. Make sure master is up to date with `git pull`
10. Checkout to your branch `git checkout [firstname-lastname]`
11. Merge the master branch `git merge master`
12. Commit changes `git commit -m "message"`
13. Push it
    ```
    git push -u origin [firstname-lastname]
    ```
14. If stuck, get help. :D

## Project pitch
There are kids today in this country who go without student lunches. This app allows schools to broadcast the needs of their students by declaring an amount of donations that they would need to be fullfilled in order to provide lunches for those that go without. 

## MVP Features Breakdown:

This app contains two user types. A school administrator and a donor. Their attributes are listed below in the data design description.

**Login Page** - After a "A school administrator (who has the ability to log in) they'll be directed to a home page where they will see a list of schools in need. Donors do not need the ability to login. 

**Navigation** - Navigation is present on all pages, Users should know what page is active by clicking on a nav link and activating their tab.


**Home Page  (For a school)** - If no profile is created, be sure to allow a school to create a profile and add it to the list of schools that need assistance. 


**Single School Page** - An admin will be able to see their current funds and be able to add their needs for more funding, update and delete their profile and funding needs.


**Home Page (For a donor)** - Contains a list of schools who have requested financial needs for their students. Each school is laid out in a grid format, with the name of the school, physical address/location of the school and a requested amount of funds that the school needs in order to provide lunches for their students

## Stretch Goal 
Allow a 2nd user type (patrons) to login and donate to a school. 
