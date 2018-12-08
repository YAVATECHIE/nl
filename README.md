"# nl" 

C:\Users\YAVA\Documents\GitHub\nl>git status
On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)

        README.md

nothing added to commit but untracked files present (use "git add" to track)

C:\Users\YAVA\Documents\GitHub\nl>cat README.md
'cat' is not recognized as an internal or external command,
operable program or batch file.

C:\Users\YAVA\Documents\GitHub\nl>git add README.md

C:\Users\YAVA\Documents\GitHub\nl>get status
'get' is not recognized as an internal or external command,
operable program or batch file.

C:\Users\YAVA\Documents\GitHub\nl>git status
On branch master
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

        new file:   README.md


C:\Users\YAVA\Documents\GitHub\nl>git commit -m "README file added"
[master a3d3183] README file added
 1 file changed, 1 insertion(+)
 create mode 100644 README.md

C:\Users\YAVA\Documents\GitHub\nl>git status
On branch master
nothing to commit, working tree clean


