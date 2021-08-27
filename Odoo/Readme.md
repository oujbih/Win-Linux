# Install postgresql
```
alias pycharm='bash /home/oujbih/Downloads/pycharm-community-2021.2.1/bin/pycharm.sh'
https://www.youtube.com/watch?v=DUJ4I7EKQnM&list=PLT3v18VYaHYV5u23IMGVZdXQ4s7aLGCPD&index=4
- How to install Postgres
sudo apt install postgresql
- How to create a Postgres user and set a password for Postgres user
sudo su - postgres -c "createuser -s odoo13"
sudo su postgres = psql = ALTER ROLE odoo13 WITH PASSWORD 'odoo13';
- How to clone Odoo 13.0 community edition
git clone https://github.com/odoo/odoo --depth 1 --branch 13.0 --single-branch .
- How to install all python dependencies required for Odoo 13.0
sudo pip3 install -r requirements.txt
- How to download wkhtmltopdf
wget ht
- How to install wkhtmltopdf
sudo apt install ./wkhtmltox_0.12.5-1.bionic_amd64.deb
- How to Configure Odoo 13.0 with PyCharm

# Note  psycopg2 not working 
pip install psycopg2-binary
pip3 uninstall Werkzeug  # will uninstall earlier version
pip3 install Werkzeug==0.11.15 # sudo

# Add 
$ sudo apt install git
$ git config --global user.name "Your full name"
$ git config --global user.email "xyz@odoo.com"

```
