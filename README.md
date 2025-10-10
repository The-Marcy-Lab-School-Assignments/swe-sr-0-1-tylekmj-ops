# Technical Writing Assignment

For guidance on setting up and submitting this assignment, refer to the Marcy lab School Docs How-To guide for [Working with Short Response and Coding Assignments](https://marcylabschool.gitbook.io/marcy-lab-school-docs/how-tos/working-with-assignments#how-to-work-on-assignments).

## Prompt 1

A good technical explanation often uses a metaphor to help others understand a complex concept. Choose a metaphor to represent a Git commit. 

In a few brief paragraphs, use your chosen metaphor to explain:
* What a commit is
* How a commit is created (include the command-line syntax)
* Why commits are useful in version control.
* Why it is important to write descriptive clear messages in team settings.

### Response 1
A commit is a git command that saves any staged changes that came from the working directory and puts them into the repository. You can also have multiple commits so its useful in version control since programmers can not only save current changes made to their program but they can also go back to previous changes if they deleted a function that they need back or maybe even for troubleshooting since a programmer can go back to an earlier version and figure out what code did they add that causes their current program to get errors.

You can use the git command ``"git commit -m "".` to commit your changes. You still have to stage your changes first using git add though.
Here's what a commit would look like on the terminal,

``git add .`
``git commit -m "Put anything here"`

-m is necessary for git commit. It adds a message to you're commit which is useful since commit is basically a savefile and just like a savefile you can have multiple. So adding a message with the commit will let you and people collaborating on the same project as you know what each savefile is for and what was done in those versions