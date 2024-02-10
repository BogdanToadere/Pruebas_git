DOWNLOAD
https://git-scm.com/downloads
SETUP							
Configuring user information used across all local repositories
git config --global -e
git config --global user.name “[firstname lastname]”	set a name that is identifiable for credit when review version history
git config --global user.email “[valid-email]”		    set an email address that will be associated with each history marker
git config --global init.defaultBranch main		        set "main" as first default branch name 
git config --global core.editor "code --wait" 
git config --global core.autocrlf true/input            windows/linux
git config -h
SETUP & INIT
Configuring user information, initializing and cloning repositories
git config --global color.ui auto			set automatic command line coloring for Git for easy reviewinggit init 		initialize an existing directory as a Git repository
git clone [url]						retrieve an entire repository from a hosted location via URL
