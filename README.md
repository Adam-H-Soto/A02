# A02
# Adam Soto IS117-005
#
# 1) Tutorial on setting up Git / Visual Studio Code / GitHub
#        First you want to download Git for your OS (Operating System)
#        Being a Windows user, I went to (https://gitforwindows.org/) and downloaded GitBash
#        You should download the latest version of GitBash
#        Once it is installed, you want to go to GitHub and create an account (https://github.com/)
#        Create a repository and name it appropriately (adding a README.md during this setup)
#        From here you should go and download an IDE (Integrated Development Environment) such as Visual Studio Code (https://code.visualstudio.com/download) and install it for your OS
#        Now you should clone your repository (repo) either by using HTTPS or SSH found when clicking the green "Code" button of your repo and copying the URLs found there
#        This can be done by using the "git clone [HTTPS-URL or SSH-URL]" command in your newly installed GitBash application
#        This will synchronize your GitHub repo with your local machine
#        Now if you search in your File Explorer for your GitHub repo's name you should find it
#        From there you can right-click on the repo folder and see the option to open it with VSCode (you can also open GitBash with this process to execute commands quicker)
#        Doing this will open your VSCode application and allow you to visualize any documents you create in this repo (you should be able to see the README.md file we made earlier)
#        You can also access the GitBash terminal from here by clicking the "..." tab and opening a new Terminal to execute any commands you may need
#        From here you are free to create and edit any files using VSCode
#        Once done with your file, you can then use the GitBash commands "git add .", "git commit -m "Custom message of your choice for notation", and "git push origin main" to [...]
#        [...] synchronize your local machine with the remote repo on GitHub, effectively transferring any locally made files onto GitHub
#        Lastly, if you ever make any files on GitHub rather than VSCode, you can use the "git pull origin main" to update your local machine with those files
#
#        *NOTE* When creating/accessing files through GitBash (even on VSCode) make sure you use the command "cd /(your repo name)" to ensure you are on your repo locally
#
# 2) Definition of Terms associated with Git and GitHub
#        a) Branch - A branch is a copy of the main version of a project, it does not affect the main version, allowing the user to edit and test things as they please until they want to merge it with the main version.
#        b) Clone - To clone something on GitHub is to make a local copy of a repository on GitHub using the clone command.
#        c) Commit - To commit something on GitHub is to record any changes to files in a branch using the commit command.
#        d) Fetch - To fetch something on GitHub is to retrieve updates from a remote repository for your local repository without merging them.
#        e) GIT - Git is a distributed version control system that allows developers to track changes in their codebase over time.
#        f) GitHub - GitHub is a platform that hosts code repositories and utilizes Git for version control.
#        g) Merge - To merge something on GitHub is to combine a branch of a version with another branch, typically into the "main" branch. Essentially to update that main branch with changes from the other branch.
#        h) Merge Conflict - A merge conflict happens when two branches both have changes to similar aspects of a file and try to merge them making Git have an error because it does not know which version to keep.
#        i) Push - Push is a command in Git that allows you to upload local repository content to a remote repository.
#        j) Pull - Pull is a command in Git to update the local repository with changes from a remote repository.
#        k) Remote - Remote refers to the repositories hosted on GitHub rather than on one's local machine.
#        l) Repository - A repository refers to the space where project files live, allowing for version control and collaboration.
#
# References
# All information about how to set up Git, GitHub, and VSCode is paraphrased and sourced from Prof. Matt Toegel's presentations.
# All definitions come from GitHub documentation and Google searches.
