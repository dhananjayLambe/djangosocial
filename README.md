# djangosocial


sudo yum -y update  
enable GUI on ubuntu server    
https://www.rorymon.com/blog/how-to-rdp-to-ubuntu/   

install google chrome    
 
https://www.linuxbabe.com/ubuntu/install-google-chrome-ubuntu-18-04-lts    


install 3.7    
https://linuxize.com/post/how-to-install-python-3-7-on-ubuntu-18-04/    

install edge template   https://django-edge.readthedocs.io/en/latest/     


install prerequsite software   

set up  python virtual  env on ubuntu server     

https://vitux.com/install-python3-on-ubuntu-and-set-up-a-virtual-programming-environment/   
https://vitux.com/install-python3-on-ubuntu-and-set-up-a-virtual-programming-environment/    

sudo apt-get update   
sudo apt-get install build-essential libssl-dev libffi-dev python-dev   
pip3 --version   
sudo apt-get update    
sudo apt install python3-pip    
sudo apt-get install python3.7-venv    
python3.7 -m venv py37env     
sudo apt-get update     


note - Now that pip3 is installed on your system, you can install any pip package by using the following command syntax:    

$ pip3 install [package-name]    


activate python enviroment     

. py37env/bin/activate    

pip3 install django    
django-admin --version    
django-admin.py startproject --template=https://github.com/arocks/edge/archive/master.zip --extension=py,md,html,env my_proj
cd my_proj/     
pip install -r requirements.txt    
cp settings/local.sample.env my_proj/settings/local.env    
sudo apt update    
cd src    
cp my_proj/settings/local.sample.env my_proj/settings/local.env   
python manage.py migrate    
python manage.py createsuperuser    
python manage.py runeserver    



Install postgresql database and connection    
refer-    
https://www.linode.com/docs/databases/postgresql/how-to-install-postgresql-on-ubuntu-16-04/   


sudo apt install postgresql postgresql-contrib    
sudo passwd postgres    

su - postgres    
psql -d template1 -c "ALTER USER postgres WITH PASSWORD 'welcome#1234';"    
createdb my_projdb    
\l liist of the database    
\q exit    

sudo apt-get install python3 python-dev python3-dev \
     build-essential libssl-dev libffi-dev \
     libxml2-dev libxslt1-dev zlib1g-dev \
     python-pip   
sudo apt install python3.7-dev   

pip install psycopg2   
python manage.py makemigrations   
python manage.py migrate   


Install GitHUB For code Repository

git config --global user.name "dhananjayLambe"
git config --global user.email "drl171291@gmail.com" 





