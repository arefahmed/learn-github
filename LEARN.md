###############################################################################################################
###################### How to Configure Username & Email For using Git Bash ####################################
###################### This is Beginner Toutorial on How to use either github or gitlab #######################
###################### Written By Aref Ahmed Date:-10/7/2021 Wanak-Tech-corp ##################################
###############################################################################################################
--------------------------------------------------------------------------------------------------------------
Solved git error message:-  
Error-message:-
 Author identity unknown
*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: empty ident name (for <etee@eteearch.localdomain>) not allowed

Solved by following the next steps
Configure you gitlab email,user and your name with the git-new-project-name

-Example used here user=arefahmed1, name=arefahmed1, e-mail sabata5000@gmail.com, project name= test
Commands using the example given above:-
---------------------------------------
$ git init myproject(ex:test) ----intializing git for the first time ever used
$ git config --global user.email "arefahmed1.sabata5000@gmail.com"
*Omit --global to set the identity only in this repository.*
$ git config --local user.name "arefahmed1.arefahmed1"
-To check if user and name in the git list
$ git.config --list

-After finishing setuping user and email to gitlab through the terminal
-----------------------------------------------------------------------
-Now we actually ready to send our files to the gitlab repo or github by run the following several commands:-
6- we need to get the files ready to be pushed to gitlab or github repo projectby using the following
two commands

Example-used here is the README.md this file orginally created in the repo of gitlab or github.

For one file we use the following command
$ git add README.md
wether the one file was orginally created in the terminal or orginally created in the github or gitlab repo"

FOR several files 
If you have several files was created orginally in the gitlab or github reposotiry then use the following command
$ git add -u 

Exception as follow:
--------------------
This will work if you have multi files but these files was orginally created in github or gitlab reposoitory you download them from github repo and then you modifed them in the terminal example README.md or any file was orginally created on github then git add -u  command will work for getting these files to be ready for the commit command

*commit command= will make a file or several files ready-not send yet to be ready for the push command the push command will send the files or one file to the github or gitlab reposotory.*

*Note if thers is a new file was created in the terminal orginally, then you MUST use the one file command which is 
 git add  "name-of-the-file was created in the bash terminal".*git add -u  command will NOT work

$ git status   
This status command will give you the status of the file or several files if they are ready for the next commit command and then they are send to the gitlab or github reposoitory using the pushed command which is the final step.

$ git commit -m "write any message"

$ git push       
The push command is the final step then it will ask for your gitlab or github username and password enter them then push enter.
You are done

Useful commands(git pull and git log):-
----------------------------------------
-using pull command to download the licene file or any several files from gitlab or github reposoitory
$ git pull 

-using git log command to see who work on the project
$ git log


Thank-You licensed%100 Only by Aref Ahmed 10/7/2021 
#####################################################################################################################
