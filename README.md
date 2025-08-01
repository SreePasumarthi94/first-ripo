# Hello World
This is my first project ever.
I want write few git commands to remember

to initiate git :
git init

to create repository:
mkdir <dire_name>
then
go to the dir 
cd <dir_name>

echo "here write down whatever you want to push in to your repository" > (here give the file name you want keep)
Eg: echo " # MY FIRST PROJECT" > README.md

here md - markdown language
likewise you can specify the file format as you wish if .py means python script 

now we have to stage the changes 
git add.
this will stage all the changed ,new ,edited files 

if i want to specifically stage only the .md file then i prefer
git add README.md

Then,
save the changes to repository using this commit command
git commit -m "here specify or mention keyword thriugh which you can identify what is inside and what changes u have made into this commit
Eg: git commit -m "Basic commands to learn git"

now if this is the first time ur pushing changes then make sure ur doing it into the main branch for that better to give this command
git branch -M main

here is the main,till now we have seen that saving and pushing but now mention where to push 
git remote add origin https://github.com/<giveur username>/<give ripo name>.git

NOte: Before above command make sure you have one ripository in ur github so that u can give name of it in command.

push the changes now
git push -u origin main

if u wnat to remove then remove it using
git remote remove origin

if want to see the repos :
git remote -v

