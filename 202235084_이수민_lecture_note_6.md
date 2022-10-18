# Git
### Version Control and Collaboration
It’s essential to use a version control system for software development and other documentation works
Basic solution: Making copies
(*you can overwrite but overwriting is inconvenient to modify*)
We need a systematic management system for version control and collaboration

### Change vs. Snapshots
- Storing data as changes to the base version()
- Storing data as snapshots

### Local, Centralized, and Distributed
- Local : File and Version Database
- Centralized : Central VCS Server to Computers
- Distributed : Server Computer and Local Computers

### Three Staes in Git
1. Modified
    - Working Directory
    - Stage Fixes to Staged
1. Staged
    - Staging area
    - Commit to Comitted
1. Comitted
    - git directory(Repository)
    - Checkout the project(back to no.1)

### Installing
- Linux / Mac / Windows
    - $ git --version
- Linux(install on a Debian-based distribution)
    - sudo apt install git-all
- Mac(<http://git-scm.com/download/mac>)
- Windows - Run "Git Bash"(<http://git-scm.com/download/win>)

### Git config
1. System level: --system option. Affect all uses and repositories on the system
1. Global(user) level: --global option. Affects all repositories of a current user
1. Local level: --local option. Specific to the current repository

- $ Git init
- $ git status
- $ git add [file_name]
- $ git add . 
- $ git rm -cached [file_name]
- .gitignore file
- $ git commit -m "commit message"
- $ git branch