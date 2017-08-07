Please note that I changed the password to "password" for psql


Follow the following steps to change the password of User "Postgres"
1) Vagrant Up
2) Vagrant SSH
3) sudo -u postgres psql
4) ALTER USER postgres PASSWORD 'password';

To run the project:
1) Python logs.py