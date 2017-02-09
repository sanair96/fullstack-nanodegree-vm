#rdb-fullstack
=============
###Tournament Database based on psql

##Steps to be Followed to run the code
1. Install Virtual Box and Vagrant, Git Bash(Only Windows users) onto your PC.
2. Clone this Repository onto your PC
3. Open Git Bash shell in the cloned folder where pg_config.sh file is present.
4. Run the Following commands
..* vagrant up
..* vagrant ssh
..* cd /vagrant/tournament
..* psql -f tournament.sql
..* python tournament_test.py

*Please note It is essential to run the commands in the order provided to successfully run the program.*
