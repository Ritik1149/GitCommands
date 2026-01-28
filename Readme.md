<h1>GitCommands</h1>
<ol>
    <li>git --version</li>
    <li>git init <ul><li>creates a git repository</li></ul></li>
    <li>git status <ul><li>check for undone commits</li></ul></li>
    <li>git log <ul><li>displays the whole commit history</li></ul></li>
    <li>git log --pretty=oneline <ul><li>display entire commit history, but only with commit number and associated message</li></ul></li>
    <li>git log --graph <ul><li>Displays the commit history in a <b><I>Visual</I></b> form [For remote repos and different branches]</li></ul></li>
    <li>git add FILE-NAME <ul><li>to track file</li></ul></li>
    <li>git commit -m "MESSAGE" <ul><li>to save changes</li></ul></li>
    <li>git diff <ul><li>to see changes in file of Working directory with the last commit</li></ul></li>
    <li>git diff --staged <ul><li>to see changes in file of staged directory with the last commit</li></ul></li>
    <li>git commit -a -m "MESSAGE" <ul><li>a shortcut of doing add and commit in one line</li></ul></li>
    <li>git rm --cached FILE-NAME <ul><li>to remove a file from git's staged repository</li></ul></li>
    <li>git branch -M NAME-OF-BRANCH <ul><li>used to rename a branch</li></ul></li>
    <li>git clone ADDRESS <ul><li>used to copy a git repository to a different location</li></ul></li>
    <li>git remote add origin ADDRESS <ul><li>used to add a remote repository as target</li></ul></li>
    <li>git push -u origin main <ul><li>used to send local repository data <I>from main branch</I> to remotely targeted repository</li></ul></li>
    <li>git remote remove origin <ul><li>used to remove the link of targeted remote repo</li></ul></li>
    <li>git remote set-url origin ADDRESS <ul><li>used to <b><I>rename</I></b> the link of targeted remote repo</li></ul></li>
    <li>git remote -v <ul><li>used to check the address of currently targeted remote repo</li></ul></li>
    <li>git tag -a TAG-NAME -m "MESSAGE" <ul><li>used to add a tag with the last commit</li></ul></li>
    <li>git tag <ul><li>used to display all given tags till now</li></ul></li>
    <li>git show TAG-NAME <ul><li>used to display all information regarding the specified tag</li></ul></li>
    <li>git checkout -b BRANCH-NAME <ul><li>Creates and switches to the BRANCH-NAME</li></ul></li>
    <li>git switch -c BRANCH-NAME <ul><li>Same as above</li></ul></li>
    <li>git branch [--all] <ul><li>shows list of all local branches, and all local+global branches if --all is given</li></ul></li>
    <li>git switch - <ul><li>switches to the last branch you were at before coming here [to the current branch]</li></ul></li>
    <li>git branch -d BRANCH-NAME <ul><li>Deletes the specified branch</li></ul></li>
    <li>git merge TARGET-BRANCH <ul><li>Merges the commits of TARGET-BRANCH <b>to</b> the branch you are at</li></ul></li>
</ol>
