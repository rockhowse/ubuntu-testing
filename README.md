# ubuntu-testing
Simple example code, using Ubuntu + Python + PostgreSQL.

# dependencies

OS: ubuntu-trusty64 ~ https://vagrantcloud.com/ubuntu/boxes/trusty64

Python:  v2.7.6  ~ no pip/wheel by default

Pip:     v1.5.4  ~ sudo apt-get install python-pip

wheel:   v0.24.0 ~ installed by default with python-pip/wheel

twisted: v13.2.0 ~ sudo apt-get install python-twisted

PostgreSQL: v9.4 ~ use postgres install from postgres site http://www.postgresql.org/download/linux/ubuntu/

                    sudo deb http://apt.postgresql.org/pub/repos/apt/ trusty-pgdg main
					sudo wget https://www.postgresql.org/media/keys/ACCC4CF8.asc
					sudo apt-key add
					sudo apt-get update
					apt-get install postgresql-9.4