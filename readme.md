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

You have installed Django's auth system, and don't have any superusers defined.
Would you like to create one now? (yes/no): yes
Username: learndjango
Email address: jhooey@gmail.com
Password: learndjangoadmin
Superuser created successfully.
