# P5-Linux-Server
Udacity Project 5 - Linux Server Configuration

IP Address: 52.35.79.220

SSH Port: 2200

URL: http://ec2-52-35-79-220.us-west-2.compute.amazonaws.com/



Installed Software:
apache2
libapache2-mod-wsgi
postgresql
postgresql-contrib
pip
setuptools
flask
postgresql-dev.X.Y
libpq-dev
python-dev
psycopg2
sqlalchemy
apach2-threaded-dev
mod_wsgi
git
httplib2
fail2ban
glances
cron-apt

Fail2ban was installed to ban ip addresses for multiple failed authentition attempts, Glances for monitoring, cron-apt for automatic updates (set to default of 4AM update).


UFW was conifgured as specified in the instructions and set to 


Additional permission changes in the app folder structure was need to facilitate file uploads (for saving, deleting files and folders).


Stackoverflow, askubuntu, postgres docs, flask docs and the udacity course on Linux Server Configuration was used as reference.
