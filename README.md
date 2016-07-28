# tournamentREADME
README file for TOURNAMENT
##SYNOPSIS
The attached two files _TOURNAMENT.PY_ and TOURNAMENT.SQL are a Python module and PostgreSQL database to keep track of players and matches in a game tournament.  This code was written as my final project in Udacity's intro to Computer Programming.  The rubric may be found here:  https://classroom.udacity.com/nanodegrees/nd000/parts/0001345403/project

The game tournament will use the Swiss system for pairing up players in each round: players are not eliminated, and each player should be paired with another player with the same number of wins, or as close as possible.

##How to Run Code
1. Code is meant to be run on a virtual machine.  You will need to first install a Virtual Box and Vagrant.

2. Next run `vagrant up` then `vagrant ssh`

3. Next change directory to the drive where these files are located and type `psql` 

4. In the VM, type `\i tournament.sql`  to connect to the database and create the tables.

5. Verify the code passes by using Udacity proprietary software.  You must get this from Udacity directly and then type `python tournament_test.py` This test file with validate the TOURNAMENT.PY file

##About the Developer
While I really didnt understand how to utilze SQL prior to this project I now have a rudimentary understanding and although I was not up for the extra credit, I feel competent enough to recreate this as needed for a similar project.  Thank you for reading.


