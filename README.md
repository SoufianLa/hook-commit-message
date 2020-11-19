# Hook pre-commit for git conventional commits

**ℹ Reference [Git Commit Conventions](https://www.conventionalcommits.org/)**

### Usage
* Clone the repository on your local machine `git clone https://github.com/SoufianLa/hook-commit-message.git`
* Copy .git-hooks directory into your project `cp -R hook-commit-message/.git-hooks $YOURPROJECTPATH`
* Make commit-msg executable `chmod +x .git-hooks/commit-msg`
* Set git hook directory to .githooks `git config core.hooksPath .git-hooks`


Control your git message by using conventionnal commit

