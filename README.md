<h1>Git Course</h1>

Setting up global Git configuration with user information and line ending preferences. Commands configure username, email, default branch name, and CRLF handling settings.
<p align="center">
  <img src="Screenshots/ (1)" alt="Git config"/>
</p>

Creating a working environment for the Git project. Using `mkdir work` to create a new directory, `cd work` to navigate into it, and `touch hello.html` to create an empty HTML file.
<p align="center">
  <img src="Screenshots/ (2)" alt="Create workspace"/>
</p>

Creating a simple HTML file named "hello.html" containing only the text "Hello, World" - the first file for our Git repository.
<p align="center">
  <img src="Screenshots/ (3)" alt="Hello HTML"/>
</p>

Initializing a new Git repository using `git init` command and making the first commit with hello.html file using `git add` and `git commit -m "Initial Commit"` commands.
<p align="center">
  <img src="Screenshots/ (4)" alt="Git init and commit"/>
</p>

Checking the repository status using `git status` command, which shows we're on the main branch with a clean working tree - meaning all changes are committed.
<p align="center">
  <img src="Screenshots/ (5)" alt="Git status"/>
</p>


Updating the HTML file with proper h1 tags to format "Hello, World!" as a heading.
<p align="center">
  <img src="Screenshots/ (6).png" alt="(6)"/>
</p>

Checking Git status which shows there are unstaged changes in hello.html file that need to be committed.
<p align="center">
  <img src="Screenshots/ (7).png" alt="(7)"/>
</p>

Adding the modified hello.html file to staging area using `git add` command and verifying the staged changes with `git status`.
<p align="center">
  <img src="Screenshots/ (8).png" alt="(8)"/>
</p>

Starting the commit process with the `git commit` command to save the staged changes.
<p align="center">
  <img src="Screenshots/ (9).png" alt="(9)"/>
</p>

Git commit editor window opened, showing the commit message template with the summary "Added h1 tag" and additional information about the changes to be committed.
<p align="center">
  <img src="Screenshots/ (10).png" alt="(10)"/>
</p>

Successful commit with message "Added h1 tag" confirmed, followed by a clean status check showing no pending changes.
<p align="center">
 <img src="Screenshots/(11).png" alt="(11)"/>
</p>

Adding proper HTML structure to the file by including html and body tags around the existing h1 heading.
<p align="center">
 <img src="Screenshots/(12).png" alt="(12)"/>
</p>

Using the `git add` command to stage the modified hello.html file for commit.
<p align="center">
 <img src="Screenshots/(13).png" alt="(13)"/>
</p>

Further improving the HTML structure by adding a head section to the document, maintaining proper indentation and tag hierarchy.
<p align="center">
 <img src="Screenshots/(14).png" alt="(14)"/>
</p>

Git status showing the modified hello.html file is staged for commit, with helpful command hints for managing staged and unstaged changes.
<p align="center">
 <img src="Screenshots/(15).png" alt="(15)"/>
</p>

Committing changes with message "Added standard HTML page tags" and checking status to confirm clean working tree.
<p align="center">
 <img src="Screenshots/(16).png" alt="(16)"/>
</p>

Using `git add .` to stage all changes, followed by committing with message "Added HTML header" with successful confirmation.
<p align="center">
 <img src="Screenshots/(17).png" alt="(17)"/>
</p>

Viewing commit history with `git log`, showing all commits including author information, dates, and commit messages from initial commit to latest HTML header addition.
<p align="center">
 <img src="Screenshots/(18).png" alt="(18)"/>
</p>

Using `git log --pretty=oneline` to display a condensed version of the commit history, showing commit hashes and messages in a single line format.
<p align="center">
 <img src="Screenshots/(19).png" alt="(19)"/>
</p>

Demonstrating various `git log` formatting options including `--max-count`, `--since`, `--until`, `--author`, and `--oneline` to filter and format the commit history display.
<p align="center">
 <img src="Screenshots/(20).png" alt="(20)"/>
</p>

Demonstrating different git log format options with `--pretty=format` and setting global format preferences, along with using `--date=short` for condensed date display.
<p align="center">
 <img src="Screenshots/(21).png" alt="(21)"/>
</p>

Viewing the commit log with the newly configured short date format, showing a cleaner history output.
<p align="center">
 <img src="Screenshots/(22).png" alt="(22)"/>
</p>

Using `git checkout` with a specific commit hash to examine the repository state at the initial commit. Shows detailed information about detached HEAD state.
<p align="center">
 <img src="Screenshots/(23).png" alt="(23)"/>
</p>

Switching back to the main branch with `git switch main` and viewing the current state of hello.html file showing all HTML structure is present.
<p align="center">
 <img src="Screenshots/(24).png" alt="(24)"/>
</p>

Creating a version tag 'v1' and viewing the log with the new tag information included in the commit history.
<p align="center">
 <img src="Screenshots/(25).png" alt="(25)"/>
</p>

Checking out tag v1A which points to a specific commit, showing the state of hello.html at that point and providing information about the detached HEAD state.
<p align="center">
 <img src="Screenshots/(26).png" alt="(26)"/>
</p>

Creating a new tag 'v1-beta' and switching between different tagged versions of the repository using checkout commands.
<p align="center">
 <img src="Screenshots/(27).png" alt="(27)"/>
</p>

Listing available tags and viewing commit history in the main branch with all tag references shown.
<p align="center">
 <img src="Screenshots/(28).png" alt="(28)"/>
</p>

Switching back to the main branch from a tagged version, showing the HEAD movement in the process.
<p align="center">
 <img src="Screenshots/(29).png" alt="(29)"/>
</p>

Adding a comment to hello.html file that we plan to revert later, demonstrating preparation for practicing Git's revert functionality.
<p align="center">
 <img src="Screenshots/(30).png" alt="(30)"/>
</p>

Git status showing unstaged changes in hello.html file that haven't been added to the staging area yet.
<p align="center">
 <img src="Screenshots/(31).png" alt="(31)"/>
</p>

Using `git checkout hello.html` to discard changes and restore the file to its last committed state, followed by verification with `cat` command.
<p align="center">
 <img src="Screenshots/(32).png" alt="(32)"/>
</p>

Adding an unwanted HTML comment in the head section of hello.html file to demonstrate Git's file restoration capabilities.
<p align="center">
 <img src="Screenshots/(33).png" alt="(33)"/>
</p>

Staging the changes with `git add` and then using `git reset HEAD` to unstage the changes in hello.html file.
<p align="center">
 <img src="Screenshots/(34).png" alt="(34)"/>
</p>

Using `git checkout` again to revert the file to its last committed state, resulting in a clean working directory.
<p align="center">
 <img src="Screenshots/(35).png" alt="(35)"/>
</p>

Adding an unwanted comment to hello.html file and preparing to demonstrate Git's revert functionality.
<p align="center">
 <img src="Screenshots/(36).png" alt="(36)"/>
</p>

Staging and committing the unwanted change with a message indicating it was a mistake: "Oops, we didn't want this commit".
<p align="center">
 <img src="Screenshots/(37).png" alt="(37)"/>
</p>

Using the `git revert HEAD` command to undo the last commit while maintaining history.
<p align="center">
 <img src="Screenshots/(38).png" alt="(38)"/>
</p>

Checking the git log to see both the mistaken commit and the revert commit in the history.
<p align="center">
 <img src="Screenshots/(39).png" alt="(39)"/>
</p>

Creating a new tag 'oops' to mark this learning point about reverting commits, and viewing the updated log with all tags.
<p align="center">
 <img src="Screenshots/(40).png" alt="(40)"/>
</p>

Using `git reset --hard v1` to move HEAD back to the v1 tag, effectively removing later commits from the history.
<p align="center">
 <img src="Screenshots/(41).png" alt="(41)"/>
</p>

Removing the 'oops' tag with `git tag -d oops` command and verifying the cleaned-up history with git log.
<p align="center">
 <img src="Screenshots/(42).png" alt="(42)"/>
</p>

Adding a copyright comment at the beginning of hello.html file with author information.
<p align="center">
 <img src="Screenshots/(43).png" alt="(43)"/>
</p>

Staging and committing the copyright statement addition with appropriate commit message and viewing the updated log.
<p align="center">
 <img src="Screenshots/(44).png" alt="(44)"/>
</p>

Updating the copyright comment to include the author's email address.
<p align="center">
 <img src="Screenshots/(45).png" alt="(45)"/>
</p>
Committing the updated copyright comment with email and verifying the change in the git log.
<p align="center">
 <img src="Screenshots/(46).png" alt="(46)"/>
</p>

Creating and switching to a new branch named 'style' using `git switch -c style` for CSS development.
<p align="center">
 <img src="Screenshots/(47).png" alt="(47)"/>
</p>

Creating a simple CSS file with a rule to make h1 elements red.
<p align="center">
 <img src="Screenshots/(48).png" alt="(48)"/>
</p>

Adding and committing the new style.css file to the repository.
<p align="center">
 <img src="Screenshots/(49).png" alt="(49)"/>
</p>

Updating hello.html to include a link tag in the head section that references the new style.css file.
<p align="center">
 <img src="Screenshots/(50).png" alt="(50)"/>
</p>

Staging and committing the changes to hello.html that include the stylesheet reference.
<p align="center">
 <img src="Screenshots/(51).png" alt="(51)"/>
</p>

Viewing the complete git log showing the full history of changes across both branches.
<p align="center">
 <img src="Screenshots/(52).png" alt="(52)"/>
</p>

Switching back to the main branch and viewing hello.html content, which doesn't include the stylesheet link.
<p align="center">
 <img src="Screenshots/(53).png" alt="(53)"/>
</p>

Switching to the style branch and confirming the content of hello.html includes the stylesheet link.
<p align="center">
 <img src="Screenshots/(54).png" alt="(54)"/>
</p>

Viewing the commit history specifically for hello.html and style.css files using `git log` with file paths.
<p align="center">
 <img src="Screenshots/(55).png" alt="(55)"/>
</p>

Using `git show v1` command to display the changes made in the commit tagged as 'v1', showing the addition of head tags.
<p align="center">
 <img src="Screenshots/(56).png" alt="(56)"/>
</p>

Renaming hello.html to index.html using the `mv` command, with Git status showing the deleted and untracked files.
<p align="center">
 <img src="Screenshots/(57).png" alt="(57)"/>
</p>

Using `git add .` to stage the rename operation, with Git correctly identifying it as a file rename rather than a delete and create.
<p align="center">
 <img src="Screenshots/(58).png" alt="(58)"/>
</p>

Creating a css directory and moving style.css into it, organizing the project structure better.
<p align="center">
 <img src="Screenshots/(59).png" alt="(59)"/>
</p>

Committing the file structure changes and viewing the commit history for the CSS file in both its original and new location.
<p align="center">
 <img src="Screenshots/(60).png" alt="(60)"/>
</p>
Creating a README file with a description of the project from the GitHowTo tutorial.
<p align="center">
 <img src="Screenshots/(61).png" alt="(61)"/>
</p>

Switching to main branch and committing the new README file.
<p align="center">
 <img src="Screenshots/(62).png" alt="(62)"/>
</p>

Viewing the commit history with `git log --all --graph` to see the branching structure and all commits across branches.
<p align="center">
 <img src="Screenshots/(63).png" alt="(63)"/>
</p>

Switching to the style branch and initiating a merge from the main branch to incorporate the README file.
<p align="center">
 <img src="Screenshots/(64).png" alt="(64)"/>
</p>

Checking the log after successful merge, showing how the 'ort' strategy automatically merged the README file from main into the style branch.
<p align="center">
 <img src="Screenshots/(65).png" alt="(65)"/>
</p>


Switching back to the main branch from style to make additional changes.
<p align="center">
 <img src="Screenshots/(66).png" alt="(66)"/>
</p>

Adding a title tag and a paragraph to hello.html to expand the page content.
<p align="center">
 <img src="Screenshots/(67).png" alt="(67)"/>
</p>

Committing the changes with message "Added meta title" after staging the modified hello.html file.
<p align="center">
 <img src="Screenshots/(68).png" alt="(68)"/>
</p>

Viewing the commit history with graph visualization to see the branch structure including the new title changes.
<p align="center">
 <img src="Screenshots/(69).png" alt="(69)"/>
</p>

Attempting to merge main branch into style branch, resulting in a merge conflict in index.html that needs manual resolution.
<p align="center">
 <img src="Screenshots/(70).png" alt="(70)"/>
</p>

Git status showing the merge conflict in index.html and providing instructions for resolving it.
<p align="center">
 <img src="Screenshots/(71).png" alt="(71)"/>
</p>

The merge conflict interface showing the differences between the current HEAD version and incoming changes from main branch.
<p align="center">
 <img src="Screenshots/(72).png" alt="(72)"/>
</p>

Aborting the merge with `git merge --abort` to start fresh, then attempting the merge again.
<p align="center">
 <img src="Screenshots/(73).png" alt="(73)"/>
</p>

The resolved version of index.html after manually combining both changes, keeping both the title and stylesheet link.
<p align="center">
 <img src="Screenshots/(74).png" alt="(74)"/>
</p>

Committing the resolved merge with `git add` and `git commit`, then viewing the updated branch history with --graph option.
<p align="center">
 <img src="Screenshots/(75).png" alt="(75)"/>
</p>

Using `git reset --hard HEAD~2` to move back two commits, then viewing the simplified log with --graph option.
<p align="center">
 <img src="Screenshots/(76).png" alt="(76)"/>
</p>

Starting a rebase operation on main branch, which encounters a merge conflict in hello.html file.
<p align="center">
 <img src="Screenshots/(77).png" alt="(77)"/>
</p>

The merge conflict resolution interface showing both the current HEAD changes and incoming changes from the rebase.
<p align="center">
 <img src="Screenshots/(78).png" alt="(78)"/>
</p>

Resolved version of hello.html after manually combining both changes during the rebase.
<p align="center">
 <img src="Screenshots/(79).png" alt="(79)"/>
</p>

Using `git add` to stage the resolved file and continuing the rebase process with `git rebase --continue`.
<p align="center">
 <img src="Screenshots/(80).png" alt="(80)"/>
</p>

Checking repository status and viewing commit history using `git status` and `git log --all --graph`. The output shows that a stylesheet was included in hello.html with successful rebase and updated references. The commit history displays various changes including file renames and additions.

<p align="center">
<img src="Screenshots/(81).png" alt="(81)"/>
</p>

Switching to the main branch and merging the style branch using `git switch main` and `git merge style`. The merge shows changes in CSS and HTML files with Fast-forward merge type.

<p align="center">
<img src="Screenshots/(82).png" alt="(82)"/>
</p>

Viewing the complete commit history after the merge using `git log --all --graph`. The log shows all commits with their respective changes, including file renames and additions of various HTML elements.

<p align="center">
<img src="Screenshots/(83).png" alt="(83)"/>
</p>

Navigating directories and cloning repository using `cd`, `pwd`, and `git clone`. The commands show directory navigation and successful cloning of the 'work' repository to 'home'.

<p align="center">
<img src="Screenshots/(84).png" alt="(84)"/>
</p>

Moving to the home directory and inspecting its contents using `cd home`, `ls`, and `git log --all`. The log shows the complete history of changes including file movements and additions with their respective commit messages.

<p align="center">
<img src="Screenshots/(85).png" alt="(85)"/>
</p>

Using `git remote` and `git remote show origin` commands to display information about the remote repository. The output shows fetch and push URLs, tracked branches, and their configurations for pull and push operations.

<p align="center">
<img src="Screenshots/(86).png" alt="(86)"/>
</p>

Viewing branch information using `git branch` and `git branch -a` commands. The output displays the current local branch and all remote branches, showing the relationship between local and remote repositories.

<p align="center">
<img src="Screenshots/(87).png" alt="(87)"/>
</p>

Navigating to the work directory using the `cd ../work` command. This changes the current working directory to continue with repository operations.

<p align="center">
<img src="Screenshots/(88).png" alt="(88)"/>
</p>

Viewing the README file content, which contains the Hello World example from the git tutorial with a note indicating changes made in the origin.

<p align="center">
<img src="Screenshots/(89).png" alt="(89)"/>
</p>

Adding and committing changes to the README file using `git add README` and `git commit` commands. The commit message indicates changes were made in the original repo, with one file changed and multiple insertions/deletions.

<p align="center">
<img src="Screenshots/(90).png" alt="(90)"/>
</p>


Navigating to home directory and using `git fetch` to update repository information. The command shows the process of enumerating, counting, and compressing objects, followed by viewing commit history with `git log --all`.

<p align="center">
<img src="Screenshots/(91).png" alt="(91)"/>
</p>

Using `cat README` command to view the contents of the README file, which displays the hello world example description from the GitHowTo tutorial.

<p align="center">
<img src="Screenshots/(92).png" alt="(92)"/>
</p>

Merging changes from origin/main using `git merge origin/main` and `git pull`. The output shows a Fast-forward merge with file changes, and confirmation that the local repository is up to date.

<p align="center">
<img src="Screenshots/(93).png" alt="(93)"/>
</p>

Setting up branch tracking with `git branch --track` and viewing branch information using `git branch -a`. The log shows recent changes using `git log --max-count=2` command.

<p align="center">
<img src="Screenshots/(94).png" alt="(94)"/>
</p>

Creating a bare repository clone using `git clone --bare` command and viewing its contents. The output shows the basic structure of a Git repository with its system directories.

<p align="center">
<img src="Screenshots/(95).png" alt="(95)"/>
</p>

Moving to the work directory and adding a shared remote repository using `cd work` and `git remote add shared` commands, pointing to the bare repository.

<p align="center">
<img src="Screenshots/(96).png" alt="(96)"/>
</p>

Viewing the README file content that shows the hello world example with a note about changes being pushed to the shared repository.

<p align="center">
<img src="Screenshots/(97).png" alt="(97)"/>
</p>

Adding the README file to staging, committing changes with a shared comment, and pushing to the shared repository using `git add`, `git commit`, and `git push` commands.

<p align="center">
<img src="Screenshots/(98).png" alt="(98)"/>
</p>

Navigating back to the home directory using the `cd ../home` command to continue with repository operations.

<p align="center">
<img src="Screenshots/(99).png" alt="(99)"/>
</p>

Adding the shared remote, setting up branch tracking, and pulling changes from the shared repository. The output shows the synchronization process and updated README content.

<p align="center">
<img src="Screenshots/(100).png" alt="(100)"/>
</p>

Starting the Git daemon in verbose mode with export-all option using `git daemon --verbose --export-all --base-path=.` command. The output shows the daemon is ready to rumble.

<p align="center">
<img src="Screenshots/(101).png" alt="(101)"/>
</p>

Cloning a repository from localhost using Git protocol with `git clone git://localhost/work.git network_work`. After successful cloning, navigating into the new directory and listing its contents, showing README, css directory, and index.html file.

<p align="center">
<img src="Screenshots/(102).png" alt="(102)"/>
</p>
