<h1>GitCommands</h1>
<ol type="01">
    <li>git --version</li>
    <li>git init <ul type= "disc"><li>creates a git repository</li></ul></li>
    <li>git status <ul type= "disc"><li>checks for undone commits</li></ul></li>
    <li>git log <ul type= "disc"><li>displays the whole commit history</li></ul></li>
    <li>git log --pretty=oneline <ul type= "disc"><li>display entire commit history, but only with commit number and associated message</li></ul></li>
    <li>git log --graph <ul type= "disc"><li>Displays the commit history in a <b><I>Visual</I></b> form [For remote repos and different branches]</li></ul></li>
    <li>git add FILE-NAME <ul type= "disc"><li>to track file</li></ul></li>
    <li>git commit -m "MESSAGE" <ul type= "disc"><li>to save changes</li></ul></li>
    <li>git diff <ul type= "disc"><li>to see changes in file of Working directory with the last commit</li></ul></li>
    <li>git diff --staged <ul type= "disc"><li>to see changes in file of staged directory with the last commit</li></ul></li>
    <li>git commit -a -m "MESSAGE" <ul type= "disc"><li>a shortcut of doing add and commit in one line</li></ul></li>
    <li>git rm --cached FILE-NAME <ul type= "disc"><li>to remove a file from git's staged repository</li></ul></li>
    <li>git branch -M NAME-OF-BRANCH <ul type= "disc"><li>used to rename a branch</li></ul></li>
    <li>git clone ADDRESS <ul type= "disc"><li>used to copy a git repository to a different location</li></ul></li>
    <li>git remote add origin ADDRESS <ul type= "disc"><li>used to add a remote repository as target</li><li><i><b>origin</b></i> is a name given to that remote repository, and so can be changed anytime.</li></ul></li>
    <li>git push -u origin main <ul type= "disc"><li>used to send local repository data from <i><b>main branch</b></I> to <b><i>origin</i></b> repository [remote repo]</li></ul></li>
    <li>git remote remove origin <ul type= "disc"><li>used to remove the link of targeted remote repo</li></ul></li>
    <li>git remote set-url origin ADDRESS <ul type= "disc"><li>used to <b><I>rename</I></b> the link of targeted remote repo</li></ul></li>
    <li>git remote -v <ul type= "disc"><li>used to check the address of currently targeted remote repo</li></ul></li>
    <li>git tag -a TAG-NAME -m "MESSAGE" <ul type= "disc"><li>used to add a tag with the last commit</li></ul></li>
    <li>git tag <ul type= "disc"><li>used to display all given tags till now</li></ul></li>
    <li>git show TAG-NAME <ul type= "disc"><li>used to display all information regarding the specified tag</li></ul></li>
    <li>git checkout -b BRANCH-NAME <ul type= "disc"><li>Creates and switches to the BRANCH-NAME</li></ul></li>
    <li>git switch -c BRANCH-NAME <ul type= "disc"><li>Same as above</li></ul></li>
    <li>git branch [--all] <ul type= "disc"><li>shows list of all local branches, and all local+global branches if --all is given</li></ul></li>
    <li>git branch BRANCH-NAME<ul type= "disc"><li>It also creates a new branch, but <b><i>stays</i></b> on the current branch</li></ul></li>
    <li>git switch - <ul type= "disc"><li>switches to the last branch you were at before coming here [to the current branch]</li></ul></li>
    <li>git branch -d BRANCH-NAME <ul type= "disc"><li>Deletes the specified branch</li></ul></li>
    <li>git merge TARGET-BRANCH <ul type= "disc"><li>Merges the commits of TARGET-BRANCH <b>to</b> the branch you are at</li><li>In case of a conflict, you have to resolve that conflict (git helps you) and then you have to again <i>add and commit</i> the changed file</li></ul></li>
    <li>git fetch<ul type="disc"><li>Fetches all information from remote git repository to local git repository, but in order to see the possible changes, we will have to use <b><i>git log</i></b> command.</li></ul></li>
    <li>git pull [from] [to]<ul><li>Used to pull the remote changes into local machine</li></ul></li>
</ol>
