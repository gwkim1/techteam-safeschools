# TechTeam Winter 2017 Workshops - Illinois Safe Schools Alliance

This is a GitHub repository for a web development project by Uchicago Techteam, Winter 2017.

## Goals
- Learn how to use terminal and Github.
- Learn HTML, CSS, and Chrome DevTools
- Learn how to use the Squarespace platform
- Create a new website for Illinois Safe Schools Alliance with cleaner design and added functionality.

## What you will do
  - Go over basic HTML/CSS concepts
  - Practice HTML/CSS skills with exercises that will be uploaded here
  - Using Chrome DevTools would be helpful
  - Compile a list of pages/files we need to relocate to the new website (Week 1~2) and finalize layout/page structure
  - Once the list is complete, start adding pages/files using the Squarespace platform.
  - I may assign some additional readings that could help you understand web development better.

## Useful Links
  - <a href="http://illinoissafeschools.org/">Current Website for Safe Schools</a>
    - NOTE: You must log in with administrator account to gain access to the list of available pages and files.
    - The list of pages and files can be found <a href="http://illinoissafeschools.org/admin/content">here</a>.
  - <a href="https://www.squarespace.com/">Squarespace</a>
    - This is a web development platform that allows simple, user-friendly interface for editing HTML/CSS
    - As per our client's request, we will be using the pre-built <a href="http://sonora-demo.squarespace.com/">Sonora</a> template in particular.
    - <a href="https://support.squarespace.com/hc/en-us/articles/206756327">Squarespace User Guide</a>
      - Later I will update a list of articles in this portal that might be helpful in some of our tasks.
  - <a href="http://learn.shayhowe.com/html-css/">HTML/CSS Tutorial</a>
    - A few of these lessons may be given as assignments. (Don't stress out! We will also go over these during the workshops)
    - Some other resources (Feel free to learn for yourself)
      - <a href="http://www.w3schools.com/">W3Schools</a>
      - <a href="https://www.codecademy.com/learn/web">Codecademy</a>

  - Useful Websites (More to come)
    - <a href="https://fonts.google.com/">Google Fonts</a> for new fancy fonts.
    - <a href="https://color.adobe.com/create/color-wheel">Adobe Color Wheel</a> for choosing a color scheme for your website.

## Getting Started
  1. Install <a href="https://desktop.github.com/">GitHub Desktop</a>
    - Within the package, we will mostly use Git Shell so that you could contribute to this GitHub project.
  2. Create a <a href="https://github.com/">GitHub account</a> if you don't have one.
    - Once you create an account, verify your email address
    - Let me know what your account name is, and accept my invitation to this project.
  3. Install Chrome if you don't have it already. 
    - We will be using <a href="https://developers.google.com/web/tools/chrome-devtools/">Chrome DevTools</a> to easily inspect HTML elements and its CSS styling.
  4. Install a text editor.
    - We will be using a text editor to edit HTML and CSS files.
    - Some options
      - <a href="https://notepad-plus-plus.org/">Notepad++</a> (for Windows)
      - <a href="http://www.barebones.com/products/textwrangler/download.html">TextWrangler</a> (for Mac)
      - <a href="https://www.sublimetext.com/">Sublime Text</a>

  
## GitHub Workflow
  1. Open Git Shell and navigate to a directory where you want the project files to be.
  ```
  Useful Git Shell commands

  # print current working directory
  pwd
  # check what files and folders are inside the current directory   
  ls
  # move to a child directory
  cd <directory> 
  # move upwards to a parent directory
  cd ..
  # create a new directory
  mkdir <directory name>
  ```
  2. Clone this repository in your chosen location. <br>
  ```
  git clone https://github.com/gwkim1/techteam-safeschools
  ```
  3. Create your own branch  
  ```
  # Check what the current branches are. (Initially there would only be master)
  git branch
  # Create your own branch
  git branch <your_name>
  # Move to your new branch (You will only be making changes within this branch and merge with master branch later)
  git checkout <your_name>
  ```
  
  4. Create your own repository
  ```
  mkdir <your_name>
  ```
- You will be submitting the HTML/CSS exercises, so you should create a folder of your own when you submit.

  5. Update your clone so that it is up-to-date with my version
  ```
  git pull upstream master
  ```  
- This won't be needed when you first clone this repository, but would be essential for your later contributions as I will be constantly updating this repository with new resources.

  6. Create/Edit files in your clone repository using text editor.
  7. Add, Commit, and Push your change
  ```
  git add <filename to add>
  git commit -m "message that describes what changes you have made"
  git push
  
  # When you first create your branch, you will need this command as well
  git push --set-upstream origin <branch_name>
  ```  
  8. Send a pull request.
    - Click on the branch button and click "new pull request" button for your own branch
    - Later I will check on your changes and merge them to the master branch.
    
  9. For every new changes, repeat Step 5 ~ 8.
  
  
