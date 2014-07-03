##Virtualenv
source ~/git/learndjango/venv/bin/activate


##Database

sudo su - postgres
createdb learndjango
createuser -P learndjango
P: learndjangoadmin
psql
GRANT ALL PRIVILEGES ON DATABASE learndjango TO learndjango;
