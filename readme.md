##Virtualenv
source ~/git/learndjango/venv/bin/activate

pip install https://www.djangoproject.com/download/1.7c1/tarball/
pip install psycopg2
pip install --upgrade selenium            #for testing

##Database

sudo su - postgres
createdb learndjango
createuser -P learndjango
P: learndjangoadmin
psql
GRANT ALL PRIVILEGES ON DATABASE learndjango TO learndjango;
