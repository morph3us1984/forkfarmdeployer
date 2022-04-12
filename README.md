# forkfarmdeployer
This short script enables you to deploy a farm with ALL Chia forks in a single script. 

For further configuration I recommend using forktools*:

https://github.com/Qwinn1/forktools

*This script installs forktools if you do not comment out the line.

For the problem of solving port conflicts, I recommend using "forkports" which is part of forktools. I also use Pitchfork* to solve some port conflict before running any forks.

https://github.com/ageorge95/pitchFORK-chia-forks-ports-check

*This script installs PitchFork if you do not comment out the line.

You will need "git" to be installed on your linux. I recommend Ubuntu 20.04 LTS

sudo apt install git


I use "THE LIST" to get the links to the fork´s github pages for this script.

THE LIST: https://docs.google.com/spreadsheets/d/1ttIK-TQwwWeY4XarapjKAYJIgDJ5Kk9yjvBPLIlrpdg/edit#gid=0


DISCLAIMER: This version of the script or the listed forks in this script and THE LIST are no recommendation. It is just a collection of existing forks. You should know/decide if you want to farm them or not.

Deleting or disabling installtion of specific forks:

Either delete or comment the line out (with a leading #) for that specific fork.

Adding new forks

Take one fork install line and copy it into your favorite text editor. Change the github link. Now search and replace the fork command. For example for Chia the command is "chia". For Flax the command is "flax". Most, if not all forks keep this unofficial "convention"
