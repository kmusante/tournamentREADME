# tournamentREADME
README file for TOURNAMENT
##SYNOPSIS
The attached two files _TOURNAMENT.PY_ and TOURNAMENT.SQL are a Python module and PostgreSQL database to keep track of players and matches in a game tournament.  These programs were written as my final project in Udacity's intro to Computer Programming.  The rubric may be found here:  https://classroom.udacity.com/nanodegrees/nd000/parts/0001345403/project

The game tournament will use the Swiss system for pairing up players in each round: players are not eliminated, and each player should be paired with another player with the same number of wins, or as close as possible.

##How to Run Code
1. Code is meant to be run on a virtual machine.  You will need to first install a Virtual Box and Vagrant.

2. Next run `vagrant up` then `vagrant ssh`

3. In the VM, type `\i tournament.sql`

