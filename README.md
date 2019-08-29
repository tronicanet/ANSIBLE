# ANSIBLE

https://www.digitalocean.com/community/tutorials/how-to-install-and-configure-ansible-on-ubuntu-18-04

Comandos básicos ad-hoc

ansible 10.0.0.1 -m ping -i host.txt  # para leer de un inventario local

ansible 10.0.0.226 -a 'echo hola'

ansible 10.0.0.226 -m apt -a 'name=vim state=present' -b -K


https://github.com/adolfintel/speedtest
