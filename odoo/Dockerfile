FROM odoo:15.0

# change to the root user
USER root

RUN apt-get update 
#RUN apt-get upgrade
RUN apt-get install -y pkg-config libxml2-dev libxmlsec1-dev libxmlsec1-openssl python3-pip python3-qrcode git
RUN apt-get install -y gcc
RUN apt-get install -y python3-dev
RUN apt-get install nano
RUN pip3 install xmlsec
RUN pip3 install git+https://github.com/pysimplesoap/pysimplesoap.git@master

# change to the odoo user
USER odoo
