Git Command: 

// git help
1. git help <verb>
Example: git help config


// git configaration
2. git config <verb> / git config <opt verb> <value.multipleKey>
Example: git config --list // see the configaration list
Example: git config --global user.name='yourUserName' // set git user name
Example: git config --global user.email='yourEmail@mail.com' // set git email address
Example: git config --global core.editor emacs // set emacs as ur default editor for git
Example: git config user.name // see the user name used or configure by u
Example: git config user.email // see the user email used or configure by u

// git initialization in ur project
3. git init
Example: git init // used the commad in your project dirctory

// are u tracking your project file?? which file u are tracking or untracking or modified?? for this we will use this command
4. git status <opt verb>
Example: git status // to get all kind of git status
Example: git status -s // for shorter status
Example: git status --short // same thing as above


// track your project file
5. git add <filename> / git add <regEx>

Example: git add index.php // in ur project if any file exits called 'index.php' it will be track by git by this command
Example: git add *.php // all file with .php extenstion will be track by this command
Example: git add -A // will track all the file in your project


// cloning a repository in your project
6. git clone <url> <opt folderName>
Example: git clone https://github.com/OwlCarousel2/OwlCarousel2.git // by this command u will clone owlCarousel in your porject
Example: git clone https://github.com/OwlCarousel2/OwlCarousel2.git yourFolderName // by this command u will clone owlCarousel in your porject but in your spcefided directory

// exactly what u change in the file
7. git diff <verb>
Example: git diff // it will show u what u last added in your file in unstaged area
Example: git diff --staged // it will show u what u last added in your file in staged area
Example: git diff --cached // it will show u what u last added in your file in staged area







