# using act on Windows to run GitHub Actions locally
## introduction
Some notes on how to use [act](https://nektosact.com/) on Windows to run GitHub Actions workflows locally for
quick testing without pushing changes to GitHub.

The current setup uses the "self-hosted" runner type, which requires all necessary tools to be installed on the host
system (see preconditions).

## preconditions
the following tools must be installed and available in the system PATH:
- act.exe (https://nektosact.com/installation/index.html)
- node.exe (https://nodejs.org/en/download/)
- apache-maven-3.x (mvn command) (https://maven.apache.org/download.cgi)
- git.exe (https://git-scm.com/install/windows)

## execution
- open a command prompt (cmd.exe) or PowerShell
- execute one of the batch files inside this directory (assumption: current directory is <root>/act/)
