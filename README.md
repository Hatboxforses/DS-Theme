# Run this all as one command using git: 
git clone https://github.com/Hatboxforses/DS-Theme.git ~/Downloads/DS-Theme && git clone -b calendar https://github.com/Hatboxforses/DS-Theme.git ~/Downloads/DS-Theme/calendar && rm -rf ~/Downloads/DS-Theme/calendar/.git ~/Downloads/DS-Theme/.git ~/Downloads/DS-Theme/README.md
## Note for windows
* rm is not actually available on Windows(courtesy of Microsoft not having it available oob)
* https://uutils.github.io/coreutils/docs/installation.html#winget use this rust version of coreutils to run the rm command
* you can also use the bash shell preinstalled with git(https://gitforwindows.org/) or mingw(https://www.msys2.org/)
* for && to work either use cmd(sorry) replace && for ;(idk if this actually works) or use Powershell (or what i want to call it which is Powershell OSS)(https://github.com/PowerShell/PowerShell) which you really should use anyways due to the numerous improvements from Windows Powershell which is still on 5
