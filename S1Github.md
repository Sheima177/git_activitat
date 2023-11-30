The process I performed with the Git commands is as follows:

ls: List the contents of the current directory.
cd desktop: Change to the "desktop" directory.
ls: List the contents of the "desktop" directory.
mkdir github_activitat: Create a new directory named "github_activity".
cd github_activitat: Change to the "github_activitat" directory.
ls: List the contents of the "github_activitat" directory.
git clone https://github.com/Sheima177/github_activitat.git: Clone the GitHub repository "github_activitat" to your local directory.
ls: List the contents of the "github_activitat" directory. You now see a directory called "github_activitat" that contains your local copy of your GitHub repository.
cd github_activitat: Change to the "github_activitat" directory you just cloned.
git init:  new Git repository in this directory. This command does not seem to be necessary since you have cloned an existing repository.
touch S1Github.md: Create an empty file called "S1Github.md".
git add S1Github.md: Adds the "S1Github.md" file to the Git staging area.
git commit -m S1Github.md: Make a commit with the message "S1Github.md" to store the changes in your local branch.
git log: Show commit history. Here you see the commit you made with the "S1Github.md" message.
git status: Shows the current status of your repository, indicating that there are no pending changes.
git push origin main: Push your changes to the "main" branch of the GitHub repository.
ls -l: List the contents of the directory, showing the "S1Github.md" file.
nano github_activitat: Trying to open the 'nano' text editor with the file 'github_activitat', but it seems to cancel immediately afterwards.
You have now created a GitHub repository with a "S1Github.md" file and performed an initial commit. There may have been a mix-up with the github_activitat nano command, as it appears that you are trying to open a text editor with the name "github_activitat", which could be confused with the name of your current working directory.
